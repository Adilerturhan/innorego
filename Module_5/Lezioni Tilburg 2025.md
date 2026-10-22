# Module 5: AI and data regulation

07/10/2025

Avv. Chiara Gallese Nobile, Ph.D., CIPP/E, MSCA
Tilburg University

TILT

## Outline

*   Introduction: data collection for machine learning
1) Basic principles of Data Protection
2) Basic principles of AI Auditing
3) Basic principles of AI Ethics
4) The new AI Act proposal
5) Applying ethical principles to data sets: practical examples
*   Conclusion
*   Q&A

## INTRODUCTION

**WHY THIS COURSE?**

You will be able to:

*   Understand data collection practices
*   Recognize applicable laws and regulations
*   Recognize ethical principles related to AI
*   Apply theoretical principles in practice
*   Avoid sanctions and reputational damage

## RECENT LAWSUIT & SANCTION CASES

*   IBM
*   ClearviewAI
*   ChatGPT

**What did they do wrong?**

## WRONG DATA COLLECTION!

| Data Scraping | Information | Data use |
| :--- | :--- | :--- |
| Scraped the web collecting images, code and texts without consent | Did not provide information about their practices | Used copyrighted materials and personal data without authorization |

## IBM

[IMAGE: Screenshot of a Global Data Review article titled "IBM sued for biometric data scraping" with the IBM logo visible.]

Allegedly scraped the web to collect random people images

## CLEARVIEW AI

[IMAGE: Screenshot of an article titled "Selfie scraping Clearview AI hit with another €20M ban order in Europe" overlaid on a graphic visualization of a human face/head covered in a network of connected lines.]

Used innocent people faces to train their AI system aimed at recognizing criminals in public spaces by Law Enforcement Authorities

## OPEN AI

[IMAGE: Screenshot of an article titled "Italy became the first Western country to ban ChatGPT. Here’s what other countries are doing."]

Scraped the web to indiscriminately collect personal data and copyrighted material

## …AND MORE

[IMAGE: Screenshot of an article titled "In generative AI legal Wild West, the courtroom battles are just getting started."]

## WHY COULDN’T THEY COLLECT PUBLICLY AVAILABLE DATA?

1.  **COPYRIGHT LAWS.** «Publicly available» does not equal to «public domain». Trademarks, logos, databases, and copyrighted materials are still protected by law even if they are accessible to the public on a website.
2.  **DATA PROTECTION LAWS.** Personal data of living persons are still protected by privacy laws even if they are available online.
3.  **WEB SCRAPING LAWS.** In some countries, such as Europe, web scaping is regulated.
4.  **CONTRACT LAWS.** Each website has different contractual rules.
5.  **ETHICS.** There are some ethics rules that prevent from stealing images without consent, whitout information, and for detrimental uses.

## COPYRIGHT LAWS

[IMAGE: Screenshot of the Disney+ website featuring a large image of The Mandalorian, with red circles highlighting the Disney logo and the Mandalorian character.]

## DATA PROTECTION LAWS

1.  CONVENTION 108+ (55 Countries)
2.  GDPR (the whole EU)
3.  NATIONAL LAWS (each country)

**NAMES AND OTHER INFORMATION IN WEBSITES ARE STILL PROTECTED BY DATA PROTECTION LAWS!**

## THE DATABASE DIRECTIVE

[IMAGE: An arrow pointing to the text box is labeled "NOT AI TRAINING."]

In the case between **Ryanair** and the websites **Volagratis** and **Lastminute**, scraping activity **to provide comparison in tickets prices** was deemed lawful by the Court of First Instance, the Court of Appeal of Milan, and the Civil Cassation insofar as copyright protection of the information contained on Ryanair's site was **excluded**, since “the organization of the data is inspired by management purposes and performs functions of information on the products of the company that manages the site, **without an appreciable degree of creative intellectual contribution**”. The sui generis right was excluded as well, because, according to the judge, the fact that Ryanair granted the right to extract its data for a ‘symbolic’ price of €100.00 would demonstrate not the wish to protect such data, but rather the aim of preventing third parties from marketing its flights.

## WEB SCRAPING LAWS 1

[IMAGE: A blue curved arrow is labeled "NOT AI TRAINING" and points toward the text box.]

EU LAW: Directive (EU) 2019/790 on copyright and related rights in the Digital Single Market (‘DSM Directive’), Article 4, provides an exception from copyright **ONLY** for “reproductions and extractions of lawfully accessible works and other subject matter for the purposes of **TEXT AND DATA MINING\***”, except where “the use of works and other subject matter referred to in that paragraph **has not been expressly reserved** by their rightholders in an appropriate manner, such as machine-readable means in the case of content made publicly available online”.

\* **automated computational analysis of information** in digital form

## WEB SCRAPING LAWS 2

US LAW: In 2021, the Supreme Court decision **Van Buren v. United States** stated that scraping publicly available internet information isn’t criminalized by the federal computer crime law.

In the long legal battle between **LinkedIn Corp. and hiQ Labs Inc.**, a California District Court in 2017 and Ninth Circuit panel in 2019 first ruled in favor of the latter.

See the case description and links to relevant documents in the article on the National Law Review at the following link:
https://www.natlawreview.com/article/hiq-and-linkedin-reach-proposed-settlement-landmark-scraping-case

## LINKEDIN CORP. v. HIQ LABS INC.

HiQ Labs was a small company that began scraping public profile data and data restricted to registered users from LinkedIn users in order to create a **business analytic service**. HiQ Labs filed a declaratory judgment request for a preliminary injunction after receiving a cease-and-desist letter from LinkedIn demanding that hiQ discontinue its scraping activities. The case went to the **Supreme Court**, which granted LinkedIn's petition for *certiorari* and **returned the matter to the Ninth Circuit for further consideration**. In April 2022, the Ninth Circuit upheld the lower court's preliminary injunction **in favor of hiQ**, however, in October of the same year, a California District Court ruled in **favor of LinkedIn**. This most recent ruling is noteworthy since it primarily addresses **contract liability** for violating a website's user agreement and its restrictions on scraping, as well as making fraudulent accounts.

## RYANAIR DAC v. BOOKING HOLDINGS INC. 1

In **Ryanair DAC v. Booking Holdings Inc.**, the famous travel company allegedly acquired information by scraping the ticketing portion of the Ryanair website. According to Ryanair, the action of the defendant violated the Computer Fraud and Abuse Act (CFAA).

The Court held that ``In order for the CFAA’s “without authorization” and “exceeds authorized access” elements to apply, some sort of **authentication mechanism** (e.g., the use of usernames and passwords) must be employed to limit access to the website. If the information on the website is **publicly available** without requiring users to authenticate themselves, a violation of the terms of use or the defiance of a cease-and-desist letter will not give rise to liability under the CFAA".

## RYANAIR DAC v. BOOKING HOLDINGS INC. 2

However, the Court also noted that ``Ryanair also alleges that the defendants engaged in screen scraping in violation of the terms of use of the Ryanair website and that the defendants continued to do so even after Ryanair sent each defendant a cease-and-desist letter. Although those allegations would be insufficient to establish liability under the CFAA if the contents of the myRyanair portion of the website were accessible to the public without authentication, **courts have found cease-and-desist letters to withdraw authorization to access a protected portion of a website when an authentication mechanism protected access to that portion of the website**".

## CONTRACT LAWS

1.  **EU LAW:** contract laws differ depending on the single Member States’ law.
2.  **US Case law:** see the cases mentioned in the previous slides
3.  **India Law:** electronic contracts are valid and enforceable and violating a contract that prohibits data scraping could be a violation of contract law. It also might violate section 43 of the Information Technology Act, enacted in 2000, which prohibits unauthorized access to a computer resource or extracting data from a computer resource.

The general rule is that web scraping **can be limited by a contractual clause**. However, as we have seen in the Italian Ryanair case, exceptions apply for specific purposes.

## PUBLIC DOMAIN DATA

Some digital objects or data are not covered by copyright laws, such as:

*   Mere facts
*   Works whose copyright expired
*   Works whose license allows its use as public domain data (CC0)
*   Works that have no creative intellectual content

## ILLICIT CONTENT

Sometimes, we can find online some illicit content, such as stolen data, pornographic materials involving minors of non-consenting individuals, information about terrorist activities, and such.

When performing web scraping to train AI system, it is extremely important to exclude this material, as the **mere possession might be considered a criminal offence**.

## ETHICS

**EU GUIDELINES:** AI HLEG Trustworthy AI Guidelines

**INTERNATIONAL GUIDELINES:**

Universal Guidelines for AI (2018)

OECD AI Principles (2019)

G20 AI Guidelines (2019)

UNESCO Recommendation on AI Ethics (2021)

## 1. BASIC PRINCIPLES OF DATA PROTECTION

## SOURCES OF LAW

GDPR is not the only law applicable to data protection. There are also international conventions, national laws, Constitution, EU treaty, and other sources of law. Legal instruments are arranged **hierarchically**.

## SOURCES OF LAW

[IMAGE: Illustration of the Earth from space.]

…implemented differently in each Member State

## MATERIAL AND TERRITORIAL SCOPE

**GOALS:** Protecting personal data of natural persons, Facilitating the exchange of data within the EU

| GDPR DOES NOT APPLY TO: | GDPR APPLIES TO: |
| :--- | :--- |
| ❌ Personal or household activity | ✅ Data **Controller** or **processor** established in the EU |
| ❌ Competent authorities for **criminal offences** or **criminal penalties** | ✅ Activities **targeting** of subjects located in the EU |
| ❌ EU bodies, offices, agencies | ✅ Competent authorities for purposes **other than law enforcement** |
| | (Data Subject’s nationality does not matter) |

## GDPR BASIC PRINCIPLES - DEFINITIONS

[IMAGE: Icon representing people/data subjects, arrow pointing to "Personal data," arrow pointing to "Processing," and icon representing a computer/online data.]

**Regardless of the format**
(mathematical form too)

## Data directly or indirectly related to a natural person, such:

*   Biometric data (photos, MRI scans, voice, and video recording)
*   Genomic expression information
*   Profiling (any habits, personality tests, work assessment, preferences)
*   Identifiers (nickname, cookies, browser settings)
*   Location data (GPS, ZIP code)
*   Opinions (religious believes, political opinion)
*   Feelings (burnout information, mood information)
*   Income, debt and borrower reliability information

## DATA COLLECTION IS A FORM OF DATA PROCESSING

*   Web scraping
*   Text mining
*   Receiving data from third parties
*   Performing interviews, focus groups, surveys
*   Making experiments and clinical analysis
*   Analyzing samples
*   Online tracking
*   GPS monitoring
*   Collecting data from IoT

## Data processing includes:

*   Collecting and Recording data
*   Storing, uploading and archiving data
*   Modifying, Analyzing and Deleting data
*   Using data to create something else (e.g., images, tables)
*   Sharing, disseminating, or making data available otherwise
*   Organizing or structuring data
*   Reading or looking at the data
*   Using data to communicate (e.g., sending emails)
*   Changing the format or the size of data
*   Using data to train a model
*   Accessing data through VPN

## DATA PROCESSING EXAMPLES IN MACHINE LEARNING

*   Collecting data
*   Analyzing data
*   Putting data into a data set
*   Preprocessing data
*   Feeding data to train the model

## [IMAGE: Flowchart detailing the Machine Learning Life Cycle]

**The Machine Learning Life Cycle**

1.  **Define Project Objectives**
    *   Specify business problem
    *   Acquire subject matter expertise
    *   Define unit of analysis and prediction target
    *   Prioritize modeling criteria
    *   Consider risks and success criteria
    *   Decide whether to continue
2.  **Acquire & Explore Data**
    *   Find appropriate data
    *   Merge data into single table
    *   Conduct exploratory data analysis
    *   Find and remove any target leakage
    *   Feature engineering
3.  **Model Data**
    *   Variable selection
    *   Build candidate models
    *   Model validation and selection
4.  **Interpret & Communicate**
    *   Interpret model
    *   Communicate model insights
5.  **Implement, Document & Maintain**
    *   Set up batch or API prediction system
    *   Document modeling process for reproducibility
    *   Create model monitoring and maintenance plan

## GDPR BASIC PRINCIPLES – BASIC CONCEPTS

[IMAGE: Grid of boxes showing the 7 GDPR principles, plus accountability.]

| lawfulness, fairness and transparency | purpose limitation | data minimisation | accuracy |
| :--- | :--- | :--- | :--- |
| storage limitation | integrity and confidentiality | accountability | [Empty] |

## LAWFULNESS

Legal basis for processing

Respect of GDPR

Respect of other relevant laws and regulations (national and international)

## LAWFULNESS IN MACHINE LEARNING

*   Make sure you can collect and use the data
*   Respect the license of the data set
*   Inform the data subjects about data processing, when needed
*   Sign the appropriate agreement, when needed
*   Discard the data you don’t need
*   Keep the data safe and secure
*   Delete the data when you do not need it anymore
*   Document GDPR compliance

## FAIRNESS

Consider how it affects the interests of data subject

Consider what the data subject expects

Do not discriminate

## FAIRNESS IN MACHINE LEARNING

*   Perform the legitimate interest assessment (LIA)
*   Perform the risk assessment
*   Perform the transfer impact assessment (TIA)
*   Perform the re-use assessment
*   Perform the data protection impact assessment (DPIA)
*   Do not use data to harm data subjects

## TRANSPARENCY

Record of activities

Privacy notice/policy

Right to access

## PURPOSE LIMITATION

Personal data must be used only for lawful purposes

Controller must communicate all purposes to data subjects

Further purposes must be compatible with the original ones

[IMAGE: A 3D figure standing next to a large red STOP sign. Circles around the sign illustrate various processing activities with arrows pointing to the figure or other uses: Ask questions, Send information, Sell data to other companies, Marketing, Perform market analysis, Profile perspective clients, Send invoices.]

## DATA MINIMIZATION

*   Only data **strictly necessary** for each **purpose** can be collected, used and shared
*   It is not possible to collect data «just in case» they may be useful in the future
*   While choosing data, other laws and code of conduct must be considered

[IMAGE: Concentric circles illustrating data minimization for a COVID-19 ICU analysis. The outermost circle is "Data of all ICU patients 2010 -2021", narrowing down to the center "Data that can be used" (Data related to ICU admissions in Milan during 2020).]

**Do you need to analyze COVID-19 ICU admissions in Milan during 2020?**

## ACCURACY

Personal data must be correct

Personal data must be updated

Data that are not correct or updated must be deleted

[IMAGE: Illustration showing an outdated speaker photo (Dr. Caia in 1982) next to a confused figure (Dr. Caia in 2021) surrounded by question marks, suggesting inaccurate information at a "2021 Conference."]

## STORAGE LIMITATION

Personal data must be kept only for the time **strictly necessary** for each purpose

After the retention time has expired, data must be deleted

If data must be kept longer for one purpose, data still cannot be used for different purposes

[IMAGE: Image of rows of archive boxes with a large red stamp overlay reading "LEGAL DEPARTMENT ONLY."]

## INTEGRITY AND CONFIDENTIALITY

Personal data must be kept safe

Cyber security measures must be implemented

Only authorized people can access the data

[IMAGE: A black smartphone resting on a book titled "Charles" and a laptop, wrapped in heavy metal chains and a padlock.]

## ACCOUNTABILITY

Controller is responsible for compliance

There are no minimum requirements, Controller must assess the risks

Controller must demonstrate that everything was done in compliance with GDPR

[IMAGE: Cartoon illustration of a monkey/bear character working at a desk, looking at a laptop. A checklist labeled "GDPR LIST" is prominently displayed. A thought cloud above the character shows a cloud icon with an upward arrow (upload) next to a large red NO symbol.]

## LEGAL BASIS

[IMAGE: Icons representing six legal bases for processing.]

*   Law, regulations, decrees, ordonnances, Court orders
*   Contract
*   Consent
*   Legitimate interest
*   **Public interest** (Points to LED Directive)
*   Protecting vital interests

## LEGAL BASIS IN AI

*   **LEGITIMATE INTEREST** (research, further use of public data sets)
*   **CONSENT**
*   **PUBLIC TASK** (train models for law enforcement)

In clinical trials, see: https://ec.europa.eu/health/sites/default/files/files/documents/qa_clinicaltrials_gdpr_en.pdf

## CAN YOU REUSE SOMEONE ELSE’S DATA SET?

It depends on the specific circumstances. You must assess if the lawful conditions are met:

*   Do the other party have the right to give you their data? If not, it is illegal to use the data set
*   Do you need an agreement to transfer the data?
*   What is your legal basis?

## CONSENT

Different from ethical Informed consent

Must be **freely given, specific, informed and unambiguous**

For special categories of data, for transfer abroad, and for automated decision making and profiling, it must be also **explicit**

## WITHDRAWAL OF CONSENT

*   Data subject has the right to withdraw consent at any time. If it happens, the data processing must be stopped.
*   The withdrawal is valid only for future processing, and what has been done before remains lawful.

## SPECIAL CATEGORIES OF DATA

[IMAGE: Icons representing nine special categories of data.]

*   Health
*   Social security number
*   Ethnicity
*   Sexual orientation or gender identity
*   Religious or philosophical beliefs
*   Political opinions or Trade Union
*   Genetic
*   Criminal conviction
*   Biometric

## HEALTH DATA

Physiological measurements (blood pressure, blood analysis, muscles performance)

Psychological state of mind (burnout, mood)

Neurodiversity information (ADHD, Asperger, Dyscalculia, Dyslexia, Non-verbal disorder, etc.)

## WHY ARE SPECIAL DATA DIFFERENT FROM OTHER TYPES OF DATA?

*   If made public, the consequences may be severe

> "Among the hiring managers polled about the hiring process at work, 65% said it was important to know a candidate's stance on racial equality, and 56% said the same for gender equality (LGBTQ+ rights (51%), immigration (38%) and politics (35%) also placed highly. Those five issues were so important to some respondents that they admitted to rejecting applicants based on those topics. Among this group, 29% said they banned someone based on one of their stances on racial equality, 27% did for gender equality, 20% did for LGBTQ+ rights, 18% for a candidate's political stance, and 16% for their thoughts on immigration."

> "Personality tests used in the hiring process have consistent patterns of correlations with sociodemographics"
Elleman, Lorien G., et al. "The personality of US states: Stability from 1999 to 2015." *Journal of Research in Personality* 72 (2018): 64-72.

## DATA CONTROLLER

**Data Controller**
Legal person, public authority, agency or other body which **determines the purposes and means** of the processing of personal data

**Joint Data controllers**
Two or more legal persons, public authorities, agencies or other bodies who **share and decide the purposes and means of processing**

## WHEN ARE YOU A DATA CONTROLLER?

*   When you collect data
*   When you receive data, and you use it for your own purposes
*   When you are a processor, and you use data against the Controller’s instructions

## PROCESSOR

*   Natural or legal person, public authority, agency or other body which processes personal data **on behalf of** the Data Controller
*   Provides sufficient **guarantees** to implement appropriate technical and organisational measures
*   Follows instructions, cooperates, gives notice of Data breaches
*   Returns or deletes Data

## WHEN ARE YOU A DATA PROCESSOR?

*   When you are paid to perform analysis on data or to train a model for someone else
*   When you help someone for free and you follow their instructions
*   When you store data for someone else

## SUB-PROCESSOR

*   NATURAL OR LEGAL PERSON, PUBLIC AUTHORITY, AGENCY OR OTHER BODY WHICH PROCESSES PERSONAL DATA ON BEHALF OF THE CONTROLLER AFTER BEING APPOINTED BY THE PROCESSOR
*   FOLLOWS INSTRUCTIONS AND COOPERATES, GIVES NOTICE OF DATA BREACHES
*   RETURNS OR DELETE DATA
*   WRITTEN AUTHORIZATION BY THE DATA CONTROLLER, WHO CAN OBJECT

## DATA AGREEMENTS

[IMAGE: Two stylized 3D figures shaking hands, emerging from laptop screens.]

*   They are not independent agreements, there has to be an underlying contract, i.e. a reason why data are transfered between Parties

## PRIVACY ROLES

[IMAGE: Circular diagram centered on "ROLE," connected to "Independency," "Service," and "Collaboration."]

## DATA TRANSFER/SHARING AGREEMENT

[IMAGE: Illustration of a handshake overlaid on circuit patterns.]

*   Between two autonomous Controllers
*   When each party determines the purpose of the processing separately
*   There must be a legal basis that allows the transfer
*   Privacy notice pursuant to art. 14 should be provided at the first contact

## JOINT CONTROLLERSHIP AGREEMENT

[IMAGE: Illustration of several people seated around a circular table reviewing documents.]

*   Between two joint Controllers
*   It determines in a transparent manner their respective responsibilities
*   It duly reflects the respective roles and relationships of the joint controllers *vis-à-vis* the data subjects
*   The essence of the arrangement shall be made available to the data subject

## DATA PROCESSING AGREEMENT

*   Between Data Controller(s) and Processor(s)
*   A contract or other legal act binding the processor to the controller
*   It sets out the subject-matter and duration of the processing, the nature and purposes of the processing, the type of personal data and categories of data subjects
*   It determines specific tasks and responsibilities of the processor
*   It considers the risk to the rights and freedoms of the data subject

## DATA TRANSFER OUTSIDE THE EU

[IMAGE: Flowchart showing four stages of data transfer mechanisms.]

1.  Adequacy decision
2.  Appropriate safeguards (standard contract clauses, approved code of conduct, international agreements)
3.  Binding corporate rules (intragroup + approved by the authority)
4.  Exceptions (consent, contractual obligation, vital interests)

## PRIVACY NOTICES

**Art. 13 and 14**

*   Clear language
*   Simple wording
*   Adapting to data subject’s level
*   Translation into data subject’s mother tongue

## PRIVACY NOTICES: WHAT SHOULD I WRITE?

**Art. 13 and 14**

*   Name of Controllers, Processors, DPO and source of data
*   Categories of data
*   Purposes of processing and further processing
*   Legal basis
*   Retention time
*   Transfer of Data and recipients
*   ADM and Profiling
*   Separate consent boxes
*   Rights of the Data Subjects

## RIGHTS OF THE DATA SUBJECTS

[IMAGE: Flowchart illustrating the sequence of data subject rights.]

Transparency → Access → Rectification → Erasure

↓

Restriction → Portability → Object → Not subject to ADM

## RIGHTS OF THE DATA SUBJECTS

**DEROGATIONS**

| [IMAGE: Judge gavel icon] | For **scientific or historical research** purposes or **statistical** purposes, **law** may provide for derogations from **Articles 15, 16, 18 and 21** if they render **impossible** or seriously impair the achievement of the specific purposes |
| :--- | :--- |
| [IMAGE: Museum/Archive building icon] | For **archiving** purposes in the **public interest**, **law** may provide for derogations from **Articles 15, 16, 18, 19, 20 and 21** if they render **impossible** or seriously impair the achievement of the specific purposes |
| [IMAGE: Microscope icon] | **Art. 17 shall not apply in some cases when the processing is necessary for freedom of information, public interest, scientific research, or for legal claims** |

*   Art. 15: access
*   Art. 16: rectification
*   Art. 17: erasure
*   Art. 18: restriction
*   Art. 19: notification
*   Art. 20: portability
*   Art. 21: objection

## SECURITY MEASURES

*   Technical and organizational measures
*   Best practices of data governance
*   Considering the **size** of the organization, the **budget** available, the **type of data**
*   Assess the **risks** for data subject
*   **Privacy by design** – **Privacy by default** principles
*   Penetration tests
*   Regular audits

[IMAGE: Flowchart illustrating security measures: Physical measures → Managing data access → Backup and data integrity measures → Cryptography, firewall, passwords → Security policy.]

## RISK ASSESSMENT

**Likelihood and impact**

*   Destruction
*   Loss
*   Unauthorized change
*   Unauthorized access
*   Unauthorized disclosure

## ANONYMIZATION

[IMAGE: Silhouettes of a crowd of people.]

## ANONYMOUS, ANONIMIZED, PSEUDONYMIZED

**Anonymous data:** there were no identifying data in the first place

**Anonymized data:** identifying data were removed

**Pseudonymized data:** it is still possible to re-identify data using a key

## ARE ANONYMIZED DATA TRULY ANONYMIZED?

> “In 2008, an anonymised Netflix dataset of film ratings was deanonymised by comparing the ratings with public scores on the IMDb film website in 2014; the home addresses of New York taxi drivers were uncovered from an anonymous data set of individual trips in the city; and an attempt by Australia’s health department to offer anonymous medical billing data could be reidentified by cross-referencing “mundane facts” such as the year of birth for older mothers and their children, or for mothers with many children.”
Read more at: 'Anonymised' data can never be totally anonymous, says study | Data protection | The Guardian

## EXAMPLES

**DE-IDENTIFICATION EXAMPLE**

| Direct Identifier |
| :---: |
| **Name** | **Birth Date** | **Postal Code** | **Ice Cream** |
| Bob Smith | Jan 1, 1957 | K1A 0B1 | Chocolate Chip |
| Alice Wilson | Mar 3, 1963 | B1K 1A0 | Vanilla |
| -- | -- | -- | -- |

**DE-IDENTIFICATION EXAMPLE**

| Indirect (Quasi) Identifiers |
| :---: |
| **Name** | **Birth Date** | **Postal Code** | **Ice Cream** |
| Bob Smith | Jan 1, 1957 | K1A 0B1 | Chocolate Chip |
| Alice Wilson | Mar 3, 1963 | B1K 1A0 | Vanilla |
| -- | -- | -- | -- |

https://www.slideshare.net/mikenowakowski/data-privacy-anonymization-reidentification
K Anonimity: https://www.researchgate.net/figure/K-anonymized-Data-Set-k3_tbl1_281467551

## EXAMPLES

**DE-IDENTIFICATION EXAMPLE**

| **ID** | **Name** | **Birth Date** | **Postal Code** | **Ice Cream** |
| :--- | :--- | :--- | :--- | :--- |
| 47562 | Bob Smith | Jan 1, 1976 | K1A 0B1 | Chocolate Chip |
| 17236 | Alice Wilson | Mar 3, 1963 | B1K 1A0 | Vanilla |
| -- | -- | -- | -- | -- |

| **ID** | **Ice Cream** |
| :--- | :--- |
| 47562 | Chocolate Chip |
| 17236 | Vanilla |
| -- | -- |

**RE-IDENTIFICATION LINKAGE**

[IMAGE: Venn diagram illustrating re-identification linkage. One circle is "Ice Cream," overlapping with a circle containing "Birth Date," "Postal Code," and a partially overlapping "Secondary Source" circle. The Secondary Source contains "Name," "Postal Code," and "Telephone."]

## ANONYMIZATION TECNIQUES

**Evaluation of main techniques**

| | Is singling out still a risk? | Is linkability still a risk? | Is inference still a risk? |
| :--- | :--- | :--- | :--- |
| **Pseudonymisation** | Yes | Yes | Yes |
| **Noise addition** | Yes | May not | May not |
| **Substitution** | Yes | Yes | May not |
| **Aggregation or k-anonymity** | No | Yes | Yes |
| **L-diversity** | No | Yes | May not |
| **Hashing/ Tokenization** | Yes | Yes | May not |

**No single technique eliminates all risks**

*   **No singling out**
*   **No linkability**
*   **No inference**

Source: LawSG-20180329 GDPR Dr Jambert Talk (panopto.eu)

## CASE STUDIES

**Are those data correctly anonymized?**

| Assigned ID | Gender | Year of birth (age) | Disease | Hospital | Date of admittance |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A001 | F | 1979 | Renal calculi | Eindhoven | 19-03-2017 |
| A002 | M | 1955 | Prostatic cancer | Eindhoven | 20-03-2017 |
| A003 | M | 1955 | Prostatic cancer | Eindhoven | 18-06-2017 |
| A004 | M | 1980 | Renal calculi | Eindhoven | 08-09-2017 |
| A005 | F | 1980 | Renal calculi | Eindhoven | 01-12-2017 |
| A006 | F | 1955 | Prostatic cancer | Eindhoven | 27-12-2017 |

## CASE STUDIES

**Are those data correctly anonymized?**

| Assigned ID | Gender | Year of birth (age) | Disease | Hospital | Date of admittance |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A001 | F | **1979** | Renal calculi | **Tilburg** | 19-03-2017 |
| A002 | M | 1955 | Prostatic cancer | Eindhoven | 19-03-2017 |
| A003 | M | 1955 | Prostatic cancer | Helmond | 19-03-2017 |
| A004 | M | 1980 | Renal calculi | Eindhoven | 01-12-2017 |
| A005 | F | 1980 | Renal calculi | Eindhoven | 01-12-2017 |
| A006 | F | **1955** | Prostatic cancer | Eindhoven | **01-12-2017** |

These data are not anonymous but **pseudonymized**. The hospital still retains the patients’ names, and it is possible to single out specific patients among the others. In this example, the last patient is clearly a trans woman.

## 4. THE AI ACT

## What is considered AI in the new regulation?

[IMAGE: Illustration showing a stylized side profile of a human head with brain synapses overlaid onto circuitry patterns.]

a) **Machine learning approaches**, including supervised, unsupervised and reinforcement learning, using a wide variety of methods including deep learning

b) **Logic- and knowledge-based approaches**, including knowledge representation, inductive (logic) programming, knowledge bases, inference and deductive engines, (symbolic) reasoning and expert systems

c) **Statistical approaches**, Bayesian estimation, search and optimization methods

## AMENDMENTS TO THE DEFINITION – ARTICLE 3

«‘artificial intelligence system’ (AI system) means a system that is designed to operate with **elements of autonomy** and that, based on **machine and/or human-provided data and inputs**, infers how to achieve a given set of objectives using **machine learning and/or logic- and knowledge based approaches**, and produces system-generated outputs such as **content (generative AI systems), predictions, recommendations or decisions, influencing the environments** with which the AI system interacts»

## The protection of citizens’ rights

The most important innovation of the proposal is the establishment of **four risks categories for AI systems**, in order to protect citizens' fundamental rights. The explanatory memorandum attached to the proposal, in fact, notes that the use of AI with its specific characteristics (e.g. opacity, complexity, dependency on data, autonomous behaviour) can adversely affect a number of fundamental rights enshrined in the EU Charter of Fundamental Rights. The proposal seeks to ensure a high level of protection for those fundamental rights and aims to address various sources of risks through a clearly defined **risk-based approach**.

## Classification of AI systems

The risk categories are related to the degree (intensity and scope) of risk for the safety or fundamental rights of citizens and are classified in **three** different groups:

(i) **unacceptable risk**
(ii) **high risk**
(iii) **low or minimal risk** (+1 = no risk)

Taking inspiration from the product safety legislation, the classification of risks is based on the intended purpose and modalities for which the AI system is used, not only on their specific function. Depending on the national legal system, the qualification of high risk may have consequences over liability, such as that under art. 2050 of the Italian Civil Code.

## Banned technology

[IMAGE: Large blue circle with a horizontal stripe, signifying a ban or prohibition.]

Some AI systems are no longer allowed in the EU, with few exceptions, such as those that:

*   deploy **subliminal techniques** beyond a person’s consciousness in order to materially **distort** a person’s **behaviour**
*   **exploit** any of the **vulnerabilities** of a specific group of persons due to their age, physical or mental disability
*   Are used by the P.A. for the **evaluation** or classification of the **trustworthiness** of natural persons based on their social behaviour or their characteristics
*   use ‘**real-time’ remote biometric identification** systems in **publicly accessible spaces** for the purpose of **law enforcement**

## Biometric identification systems for law enforcement

*   use ‘**real-time’ remote biometric identification** systems in **publicly accessible spaces** for the purpose of **law enforcement**: **unacceptable risk**

**Remote biometric identification systems** are defined as an AI systems ‘for the purpose of identifying natural persons at a distance through the comparison of a person’s biometric data with the biometric data contained in a reference database, and without prior knowledge of the user of the AI system whether the person will be present and can be identified’ (Article 3(36)).

The Proposal distinguishes ‘real-time’ and ‘post’ remote biometric identification. **Real-time remote biometric identification systems** are defined as AI systems ‘whereby the capturing of biometric data, the comparison and the identification all occur without a significant delay’. This definition introduces a mechanism to avoid circumvention, specifying that *real-time remote biometric identification systems* encompass both ‘instant identification’ and ‘limited short delays’ (Article 3(37)). **Post remote biometric identification systems** stand for any other type of remote identification system (Article 3(38)).

## Real time identification

Only systems that fulfill these requirements are banned:

*   only ‘**real-time’ remote biometric identification** (not ex post identification)
*   systems used in **publicly accessible spaces** (not private spaces)
*   for the purpose of **law enforcement** (not other purposes)

There are also exceptions, including the search of victims, the prevention of threats to the life or safety of individuals, or the identification of a perpetrator or suspect of a criminal offense (punished with a minimum of 3 years of conviction), subject to a judicial review most of the time.

## Biometric data

Data relating to the physical, physiological or behavioral **characteristics of an individual** which allow their **unique identification**, such as facial images or dactyloscopic data.

You need to be particularly careful when you handle this type of data

## EDPB guidelines

**Guidelines 3/2019 on videosurveillance**

The intensive use of video devices has an impact on citizen’s behaviour. Significant implementation of such tools in many spheres of the individuals’ life will put an additional pressure on the individual to prevent the detection of what might be perceived as anomalies. De facto, these technologies may **limit the possibilities of anonymous movement and anonymous use of services** and generally limit the possibility of remaining unnoticed. Data protection implications are massive.

## Risks of biometrical profiling

**Privacy issues:** intrusive facial recognition/ profiling of **behaviours** in public and private spaces. Video surveillance systems usually collect massive amounts of personal data which may reveal data of a highly personal nature and even special categories of data. Indeed, apparently non-significant data originally collected through video can be used to infer other information to achieve a different purpose (e.g. to map an individual’s habits). Biometric identification practices necessarily affect individuals who have **no reason to be observed**.

In addition to privacy issues, there are also risks related to possible malfunctions of these devices and the **biases** they may induce. Researchers report that software used for facial identification, recognition, or analysis performs differently based on the age, gender, and ethnicity of the person it’s identifying.

Algorithms would perform based on different demographics, thus, bias in facial recognition threatens to reinforce the prejudices of society. That is why, data controllers must also ensure that biometric data processing deriving from video surveillance be subject to regular assessment of its relevance and sufficiency of guarantees provided

## RECITAL 33

«Technical inaccuracies of AI systems intended for the remote biometric identification of natural persons can lead to **biased results** and entail discriminatory effects. This is particularly relevant when it comes to age, ethnicity, race, sex or disabilities. Therefore, ‘real-time’ and ‘post’ remote biometric identification systems should be classified as high risk. In view of the risks that they pose, both types of remote biometric identification systems should be subject to specific requirements on logging capabilities and human oversight.»

## What is bias?

The term **bias** is used by Friedman and Nissenbaum, who say it “refers to computer systems that **systematically and unfairly discriminates against certain individuals or groups of individuals in favor of others**”. By extension pre-existing **societal bias** is “**bias that originates from society at large, such as from organizations (e.g., industry), institutions (e.g., legal systems), or culture at large**. (E.g., gender biases present in the larger society that lead to the development of educational software that overall appeals more to boys than girls)”. Pre-existing bias can be **implicit and subconscious**, rather than malicious in intent.

Source: “Does Technology Have Race?’’, Hankerson et al, 2016

## Examples

[IMAGE: Amazon Rekognition Performance on Gender Classification showing accuracy rates for darker males (98.7%), darker females (68.6%), lighter males (100%), and lighter females (92.9%).]

## Examples

[IMAGE: Screenshot of a Google Photos classification error, mislabeling two African American individuals as "Gorillas."]

Google and its gorillas

## Examples

[IMAGE: Comparison of an original low-resolution image of a male face and an AI-generated high-resolution result, showing a significant change in appearance.]

## Examples

[IMAGE: Two images of individuals annotated with circles highlighting facial features and clothing/accessory descriptors classified by an AI system. The annotations circle multiple elements like Forehead, Hair, Smile, Chin, Eyebrow, Happy, Black Hair, Outerwear, Sleeve, Coat, Collar, Flash Photography, etc.]

## Examples

[IMAGE: Two images of individuals annotated with circles highlighting hair, clothing, and accessory descriptors classified by an AI system, with different elements circled in red and green.]

## Examples

[IMAGE: Two images of individuals annotated with circles highlighting appearance and role descriptors classified by an AI system, with different elements circled in red and green.]

## WHY DO WE CARE ABOUT BIAS?

*   1) Because it can lead to discrimination towards individuals or groups
*   2) Because it can lead to inaccurate results
*   3) Because it can cause errors and damage to people
*   4) Because it can cause negative effects on society

## TYPES OF BIASES AND ERRORS IN DATA SETS & MODELS

*   Selection bias
*   Overfitting and underfitting the data
*   Reporting Biases
*   Overgeneralization Bias
*   Group Attribution Biases
*   Implicit Biases
*   Variance
*   Automation bias

## SELECTION BIAS

When data are selected in a way that is not representative of the distribution of data in real life, **selection bias** occurs. This occurs as a result of improper randomization during data collection.

When randomization is improperly achieved during data collection, **sampling bias** occurs.

When data are not chosen in a representative way, **convergence bias** occurs. For instance, your dataset does not accurately reflect the group of people who did not buy your goods if you just survey the half of your consumers who actually bought your product.

**Participation bias** is when there are gaps in involvement during the data collection process, making the data unrepresentative.

## OVER- AND UNDER- FITTING

[IMAGE: Icon of a chip.]
In machine learning, **overfitting** occurs when a model is trained with so much data that it begins to learn from the noise and inaccurate data entries in the data set. Machine learning models have trouble predicting new data based on the training data because what they learnt from the noise cannot be applied to new data.

[IMAGE: Icon of a maze/puzzle piece.]
When a machine learning model fails to capture the underlying trend of the data, **underfitting** occurs. In this case, it indicates that the model or algorithm is not fitting the data well enough.

## REPORTING BIAS

The inclusion of only a portion of the results in an analysis, which often only includes a small portion of the evidence, is referred to as **reporting bias**, which can appear in many different ways.

**Citation bias** happens when your analysis is dependent on research that were included in other studies' citations.

When you disregard news sources that are not in your native tongue, you are exhibiting **language bias**.

When studies are given higher weight because they have been published more than once, this is known as **duplicate publication bias**.

**Publication bias** is the tendency for research with favorable results to be published more frequently than those with unfavorable outcomes or insufficient evidence.

**Bias in the reporting of outcomes** happens when some results are selectively reported. In a quarterly report, for instance, you only disclose when the company reports positive results.

**Time lag bias** is a problem when studies take a long time to be published.

## OVERGENERALIZATION BIAS

Overgeneralization occurs when someone extrapolates from one occurrence to all subsequent events, thinking that what you observe in one dataset will also be observed in another.

It happens when you think that, regardless of the dataset's size, what you observe in your dataset is what you would also see if you looked in any other dataset intended to evaluate the same information.

## GROUP ATTRIBUTION BIAS

**Group attribution biases** are the tendency for people to think that a group's beliefs always dictate an individual's traits or that a group's decisions are impacted by the emotions of all of its members.

When you favor those in a group to which you personally belong or have similar interests, you are exhibiting **in-group bias**.

When you stereotype certain members of a group to which you do not directly belong, this is known as **out-group bias**.

## IMPLICIT BIAS

When assumptions are drawn from personal experiences that do not necessarily apply to more generic situations, **implicit bias** results. Without realizing it, people frequently act with bias and stereotypes in mind. Even when we are not aware of it, implicit bias takes the form of opinions and prejudices we have about other people. We could seek for information that confirms our assumptions and ideas while ignoring information that contradicts them.

We might associate, for instance, the white color to peace or purity. White, however, in Chinese and Japanese culture is associated to funerals.

The propensity to look for information in a way that supports or confirms one's preexisting opinions or experiences is known as **confirmation bias** or **experimenter's bias**.

## VARIANCE

The variability in a model's prediction is known as **variance**. High variance models, in contrast to biased models, focus excessively on training data and fail to generalize to new data. On training data, this produces positive outcomes, but on test data, it produces high error rates. Variance can be thought of as the model's sensitivity to changes in the data. From noise, our model might learn. This will lead our model to value unimportant features highly. Low bias and low variance machine learning models are impossible to produce. However, you can try to make a tradeoff between the bias and the variance.

## AUTOMATION BIAS

Automation bias is the propensity for people to favor outcomes or recommendations produced by automated systems and to discount contradictory data from non-automated systems, even when it is accurate. It happens when you act upon this AI-based recommendation without first checking to see if the data was accurate.

For instance, a data scientist relies on the analytics platform's advice to edit or eliminate specific data despite the platform's warnings, which lowers the data's quality.

## BIAS IS AN IMPORTANT CONCEPT IN THE AI ACT – RECITAL 44

“High data quality is essential for the performance of many AI systems, especially when techniques involving the training of models are used, with a view to ensure that the high-risk AI system performs as intended and safely and it **does not become the source of discrimination prohibited by Union law**. High quality training, validation and testing data sets require the implementation of appropriate data governance and management practices. **Training, validation and testing data sets should be sufficiently relevant, representative and have the appropriate statistical properties**, including as regards the persons or groups of persons on which the high-risk AI system is intended to be used. **These datasets should also be as free of errors and complete as possible** in view of the intended purpose of the AI system, taking into account, in a proportionate manner, technical feasibility and state of the art, the availability of data and the implementation of appropriate risk management measures so that possible shortcomings of the datasets are duly addressed. The requirement for the datasets to be complete and free of errors should not affect the use of privacy-preserving techniques in the context of the development and testing of AI systems. Training, validation and testing data sets should take into account, to the extent required by their intended purpose, the features, characteristics or elements that are particular to the specific geographical, behavioural or functional setting or context within which the AI system is intended to be used. In order to protect the right of others from the discrimination that might result from the bias in AI systems, **the providers should be able to process also special categories of personal data, as a matter of substantial public interest** within the meaning of Article 9(2)(g) of Regulation (EU) 2016/679 and Article 10(2)g) of Regulation (EU) 2018/1725, in order to ensure the **bias monitoring, detection and correction** in relation to high-risk AI systems.”

## The concept of ‘High Risk’

Some AI system are considered **high risk** and have to meet certain requirements before being released to the market or to the public. Some examples includes systems used in:

*   Machinery (including robots)
*   Toys
*   Medical devices
*   In Vitro Diagnostic
*   Vehicles
*   Aircrafts
*   Rails

**AI Regulation must be coordinated with MDR, GDPR, and other laws (e.g., civil liability rules)**

## Other High Risk Systems

| Biometric identification and categorisation of natural persons | Management and operation of critical infrastructure | Education and vocational training | Employment, workers management and access to self-employment |
| :--- | :--- | :--- | :--- |
| Access to and enjoyment of essential private services and public services and benefits | Law enforcement | Migration, asylum and border control management | Administration of Justice |

## Mandatory requirements for High Risk Systems

**1. Risk management system:**

a) identification and analysis of the **known and foreseeable risks** associated with each system

b) estimation and evaluation of the risks that may emerge when the system is used in accordance with its **intended purpose** and under conditions of **reasonably foreseeable misuse**

c) evaluation of other possibly arising risks based on the analysis of data gathered from the **post-market monitoring system**

d) adoption of **suitable risk management measures**

## 1. Risk Management System

[IMAGE: Flow chart showing the phases of risk management.]

*   **Risk management measures**
*   **Identification and analysis** of the **known and foreseeable risks** associated with each system during the **whole lifecycle**
*   **Risks assessment related to the use**
    *   Estimation and evaluation of the risks that may emerge when the system **is in use** in accordance with its **intended purpose** and under conditions of **reasonably foreseeable misuse**
*   **Post-market evaluation**
    *   Evaluation of other possibly arising risks based on the analysis of data gathered from the **post-market monitoring system**

## Mandatory requirements for High Risk Systems

**2. Data and data governance:**

Training, validation and testing data sets concerning:

(a) the relevant **design choices**
(b) **data collection**
(c) relevant **data preparation processing operations**, such as annotation, labelling, cleaning, enrichment and aggregation
(d) the formulation of **relevant assumptions**, notably with respect to the information that the data are supposed to measure and represent
(e) a prior assessment of the **availability, quantity and suitability of the data sets** that are needed
(f) examination in view of possible **biases**
(g) the identification of any possible **data gaps or shortcomings**, and how those gaps and shortcomings can be addressed

## 2. Data Management

[IMAGE: Flow chart illustrating the stages of data management required by the AI Act.]

| Stage | Requirements |
| :--- | :--- |
| **Design** | • Design choices/ model choice<br>• Privacy by design and by default<br>• Interpretable/Explainable AI |
| **Collection** | • GDPR<br>• Copyright<br>• Re-use assessment |
| **Preparing** | • Annotation, labelling, cleaning, enrichment and aggregation of data<br>• Data set validation |
| **Assumptions** | • Information that the data are supposed to measure and represent<br>• Features/variables |
| **Assessment** | • Availability, quantity and suitability of the data sets<br>• Testing if data are sufficient/ accurate |
| **Biases** | • Assessment for biases/discrimination<br>• Testing to check if biases are present |
| **Gaps** | • Identification of gaps and shortcomings<br>• Measures to fill and correct them<br>• Testing if measures are effective |

## ARTICLE 10

«To the extent that it is strictly necessary for the purposes of ensuring **bias monitoring, detection and correction** in relation to the high-risk AI systems, the providers of such systems may process **special categories of personal data** referred to in Article 9(1) of Regulation (EU) 2016/679 \[GDPR\], Article 10 of Directive (EU) 2016/680 \[LED Directive\] and Article 10(1) of Regulation (EU) 2018/1725 \[Data protection for public bodies\], subject to **appropriate safeguards** for the fundamental rights and freedoms of natural persons, including technical limitations on the re-use and use of state-of-the-art security and privacy-preserving measures, such as pseudonymisation, or encryption where anonymisation may significantly affect the purpose pursued.»

## Mandatory requirements for High Risk Systems

**3. Technical documentation:**

1.  Drawn **before releasing** the system
2.  **Demonstrate compliance** with the requirements set out in the Regulation and provide national competent authorities and notified bodies with all the necessary information to assess the compliance with those requirements
3.  Enabling the **automatic recording of events** (‘logs’) while the systems is operating

## Mandatory requirements for High Risk Systems

**5. Transparency and provision of information to users:**

(a) the **identity and the contact details** of the provider and, where applicable, of its authorised representative;

(b) the **characteristics, capabilities and limitations** of performance of the system

(c) the **changes** to the system and its performance which have been pre-determined by the provider at the moment of the initial conformity assessment, if any;

(d) the **human oversight measures**, including the technical measures put in place to facilitate the interpretation of the outputs of systems by the users;

(e) the **expected lifetime** of the system and any **necessary maintenance** and care measures to ensure the proper functioning of that AI system, including as regards **software updates**

## Mandatory requirements for High Risk Systems

**6. Human oversight**

Through measures:

(a) identified and **built into the system**, when technically feasible, by the provider **before** it is placed on the market or put into service, and/or

(b) identified by the provider **before** placing the system on the market or putting it into service and that are appropriate **to be implemented by the user**

## Mandatory requirements for High Risk Systems

**7. Accuracy, robustness and cybersecurity:**

Systems shall be **resilient as regards errors, faults or inconsistencies** that may occur within the system or the environment in which the system operates

The robustness of systems may be achieved through **technical redundancy solutions**, which may include backup or fail-safe plans

Systems shall be **resilient as regards attempts by unauthorised third parties** to alter their use or performance by exploiting the system vulnerabilities

The technical solutions to address AI specific vulnerabilities shall include, where appropriate, measures to **prevent and control for attacks** trying to manipulate the training dataset (‘data poisoning’), inputs designed to cause the model to make a mistake (‘adversarial examples’), or model flaws

## RECITAL 50

“The technical robustness is a key requirement for high-risk AI systems. They should be **resilient** in relation to **harmful or otherwise undesirable behaviour** that may result from limitations within the systems or the environment in which the systems operate (e.g. errors, faults, inconsistencies, unexpected situations). High-risk AI systems should therefore be designed and developed with appropriate technical solutions to prevent or minimize that harmful or otherwise undesirable behaviour, such as for instance mechanisms enabling the system to safely interrupt its operation (fail-safe plans) in the presence of certain anomalies or when operation takes place outside certain predetermined boundaries. Failure to protect against these risks could lead to safety impacts or **negatively affect the fundamental rights**, for example due to erroneous decisions or wrong or **biased outputs** generated by the AI system”

## ARTICLE 15

«High-risk AI systems that continue to learn after being placed on the market or put into service shall be developed in such a way to **eliminate or reduce as far as possible** the risk of possibly **biased outputs** influencing input for future operations (‘feedback loops’) are duly addressed with appropriate mitigation measures.»

## Mandatory requirements for High Risk Systems

**8. Quality management system:**

a) a strategy for **regulatory compliance**

b) techniques, procedures and systematic actions for the **design, design control and design verification** of the system

c) techniques, procedures and systematic actions for the **development, quality control and quality assurance** of the system

d) **examination, test and validation procedures**

e) **technical specifications**, including standards, to be applied

f) systems and procedures for **data management**, including **data collection, data analysis, data labelling, data storage, data filtration, data mining, data aggregation, data retention** and any other operation regarding the data that is performed **before** - and for the purposes of - the placing on the market or putting into service of the systems (see n. 2)

## Mandatory requirements for High Risk Systems

**8. Quality management system:**

g) the setting-up, implementation and maintenance of a **post-market monitoring system**

h) procedures related to the **reporting of serious incidents and malfunctioning**

i) the handling of **communication with competent authorities**, including sectoral ones, **providing or supporting the access to data**, notified bodies, other operators, customers or other interested parties

j) systems and procedures for **record keeping** of all relevant documentation and information

k) **resource management**, including security of supply related measures

l) an **accountability framework** setting out the **responsibilities of the management and other staff** with regard to all aspects listed in this paragraph

**9. Providers shall draw up technical documentation required by the Regulation**

## Transparency obligations for certain AI systems

| [IMAGE: Person icon next to a checklist.] | Providers shall ensure that AI systems **intended to interact with natural persons** are designed and developed in such a way that natural persons are **informed that they are interacting with an AI system**, unless this is obvious from the circumstances and the context of the use |
| :--- | :--- |
| [IMAGE: Robot head icon with three dots below.] | Users of an AI system that **generates or manipulates image, audio or video content** that appreciably **resembles existing persons, objects, places or other entities or events** and would falsely appear to a person to be authentic or truthful (‘**deep fake**’), shall **disclose** that the content has been artificially generated or manipulated |

## 2. BASIC PRINCIPLES OF AI AUDITING

## What is AI auditing?

**AI Auditing** is the **review** of the whole AI lifecycle, including the post-market phase, with the aim of identifying and addressing **risks** for citizens and the society. It is carried out through applying legal, ethical and technical principles in practice.

«An ethics-based auditing can improve the quality of decision making, increase user satisfaction, unlock growth potential, enable law-making, and relieve human suffering»
- Mokander & Floridi

## How to perform AI auditing?

An **AI Audit** is carried out through the practical implementation of several **principles**:

*   **Ethics**: checking if the consequences on individuals and society have been taken into account
*   **Human Rights**: checking if fundamental rights of citizens are respected
*   **Law**: checking if legal compliance has been performed (privacy, cybersecurity, national laws, etc.)
*   **Technical good practices**: checking if the system is sound, safe, secure, correct, and biasless (e.g.: avoid sample bias)

## Guidance to perform AI auditing

In the literature, several authors have proposed a method to perform an AI audit, but few have shown how to do it in practice.

Most papers focuses on the technical aspects, such as debiasing techniques and data set balancing.

Floridi et al. suggest a guide to implement the new AI Act requirements in its paper «CapAI»

## 3. BASIC PRINCIPLES OF AI ETHICS

## What is AI Ethics?

**AI Ethics** is a branch of Philosophy; it studies the ethical principles applicable to AI systems and addresses the implications, risks and problems derived from:

1) humans building and employing those systems, and

2) the behavior of autonomous systems

## Most famous ethics guidelines

Universal Guidelines for AI (2018)

OECD AI Principles (2019)

G20 AI Guidelines (2019)

UNESCO Recommendation on AI Ethics (2021)

## Ethical principles

| Ethical principle | Number of documents | Included codes |
| :--- | :--- | :--- |
| **Transparency** | 73/84 | Transparency, explainability, explicability, understandability, interpretability, communication, disclosure, showing |
| **Justice & fairness** | 68/84 | Justice, fairness, consistency, inclusion, equality, equity, (non-)bias, (non-)discrimination, diversity, plurality, accessibility, reversibility, remedy, redress, challenge, access and distribution |
| **Non-maleficence** | 60/84 | Non-maleficence, security, safety, harm, protection, precaution, prevention, integrity (bodily or mental), non-subversion |
| **Responsibility** | 60/84 | Responsibility, accountability, liability, acting with integrity |
| **Privacy** | 47/84 | Privacy, personal or private information |
| **Beneficence** | 41/84 | Benefits, beneficence, well-being, peace, social good, common good |
| **Freedom & autonomy** | 34/84 | Freedom, autonomy, consent, choice, self-determination, liberty, empowerment |
| **Trust** | 28/84 | Trust |
| **Sustainability** | 14/84 | Sustainability, environment (nature), energy, resources (energy) |
| **Dignity** | 13/84 | Dignity |
| **Solidarity** | 6/84 | Solidarity, social security, cohesion |

Jobin, Anna, Marcello Ienca, and Effy Vayena. "The global landscape of AI ethics guidelines." *Nature Machine Intelligence* 1.9 (2019): 389-399.

## Trustworthy AI

AI HLEG recognizes 3 keys elements of Trusworthy AI:

1.  it should be **lawful**, complying with all applicable laws and regulations;
2.  it should be **ethical**, ensuring adherence to ethical principles and values; and
3.  it should be **robust**, both from a technical and social perspective, since, even with good intentions, AI systems can cause unintentional harm.

## The ALTAI List

AI HLEG has drawn a list of 7 elements:

[IMAGE: Flow chart showing "Realisation of Trustworthy AI" leading to "7 Key Requirements" which are evaluated continuously throughout the AI system's life cycle via "Technical Methods" and "Non-Technical Methods." The 7 Key Requirements are listed as: Human agency and oversight, Technical robustness and safety, Privacy and data governance, Transparency, Diversity, non-discrimination and fairness, Societal and environmental wellbeing, and Accountability.]

## Open Ethics Canvas

[IMAGE: Screenshot of the Open Ethics Canvas structure (a grid of 10 blocks: Scope, Users, Key Stakeholders, Values & Interests, Impact Assessment, Changes in Behaviour, Training Data, Personal Data Processing, Components & Subprocessing, Group Interactions, Algorithms & Source Code, Human in the Loop (HITL), Model Performance Metrics, Decision Feedback & Correction, Regulatory Landscape, Mitigation, Failure Modes, Comments, and Decision Space).]

This instrument is used by several companies in order to perform an ethical assessment of their AI systems

**Green:** non-technical ethics
**Grey:** technical ethical assessment
**Yellow:** accountability and human oversight
**Red:** legal assessment and societal liability

## 4. APPLYING ETHICAL PRINCIPLES TO DATA SETS: A PRACTICAL EXAMPLE

## Preliminary remarks

An AI system is only as good as the data it relies on.

**Garbage in = garbage out**

Data sets can be unbalanced, biased, incomplete, too small, inadequate for the intended use, not clean and not validated.

It is extremely important to prepare data **before** feeding it to the AI model.

## Applying ethical and legal principles in practice

[IMAGE: Diagram illustrating the application of principles to AI model training.]

| **Ethical/Legal Principles (Boxed)** | **AI Model Training Process (Oval)** |
| :--- | :--- |
| Non-discrimination | → Data Collection → Data preparation → Data utilization → |
| Fairness | |
| Transparency | |
| Privacy | |
| Copyright | |
| Accountability | |
| Risk management | |
| Quality assessment | |
| Data Governance | |

## How to apply those principles in practice?

[IMAGE: Illustration of a man sitting, holding his head, surrounded by red question marks, with a speech bubble in Japanese reading "Tasukete!" (Help!)]

## Developing AI models for hearing aids

We are working on a project to develop an AI model to help people with **hearing impairments**

The goal is to **help them hear better and understand what it is said in a conversation**, so the model needs to be able to recognize all kind of voices in all settings

People with hearing impairments have **the right not to be excluded** in a conversation

People with speech impairments, with a different accent or pronunciation, with a low/high tone of voice, or that are slow in talking, have **the right to have their voice recognized**

## What could go wrong?

If the data set is **biased** and different categories of people are not represented, this could lead to **discrimination** towards both people with hearing impairments and **underrepresented groups**, as the model will **not be able to recognize all voices**

[IMAGE: Four photographs of diverse people, including a child with Down Syndrome, women in colorful dresses, a crowd of people, and a woman wearing a speech/hearing device.]

## Mozilla Common Voice Data Set

[IMAGE: Screenshot of Mozilla Common Voice Data Set information with callouts.]

| Data Element | Callout |
| :--- | :--- |
| **SIZE** | 2 GB |
| **VERSION** | nl\_105h\_2022-01-19 |
| **VALIDATED HR. TOTAL** | 98 |
| **OVERALL HR. TOTAL** | 105 |
| **LICENSE** | CC-0 | **Type of license** |
| **NUMBER OF VOICES** | 1,462 | **Number of examples** |
| **AUDIO FORMAT** | MP3 | |
| **SPLIT** | Age: 22% 10 - 29, 15% 40 - 49, 10% 30 - 39, 8% 50 - 59, 2% < 19, 1% 60 - 69<br>47% Male, 11% Female | **Age and gender composition** |

[IMAGE: A star-shaped box with a question mark at its center, labeled "Intended use? Type of data? Model choice?"]

## Terms & Conditions

[IMAGE: Screenshot of a download confirmation form with a checkbox that reads: "You agree to not attempt to determine the identity of speakers in the Common Voice dataset" with an arrow pointing to the label "Privacy."]

## Looking into the data set metadata

[IMAGE: Table snippet of data set metadata (client_id, path, sentence, up_votes, down_votes, age, gender, accents, locale, segment, ...)]

## Looking into the data set metadata

[IMAGE: The same table snippet with a question box overlay.]

**Are all relevant metadata present?**

**How can you fill the missing data?**

## Looking into the data set metadata

[IMAGE: The same table snippet with a warning box overlay.]

**Individual identifier = Not anonymous**

**Beware of linking risk**

## Looking into the data set metadata

[IMAGE: The same table snippet with a question box overlay focusing on up_votes and down_votes.]

**How is validation performed?**

**Does it match the intended use?**

**Is it fair or could it lead to biases?**

**Should I provide an alternative validation?**

## Looking into the data set metadata

[IMAGE: The same table snippet with a question box overlay focusing on accents and locale.]

**What accents are present?**

**Are foreigners and vulnerable groups represented?**

## Looking into the data set metadata

[IMAGE: The same table snippet with a question box overlay focusing on age and gender.]

**Are different age and gender types equally represented?**

**Could an imbalance lead to discrimination?**

## DATA SET FAIRNESS 1

**What is data set fairness?**

Research has shown how **data sets convey social bias** in AI systems, especially those based on machine learning. A biased data set is **not representative of reality** and might contribute to perpetuate societal biases within the model. To tackle this problem, it is important to understand how to **avoid biases, errors, and unethical practices** while **creating the data sets**.

## DATA SET FAIRNESS 2

**What is data set fairness?**

Mainstream works in computer science addresses the problem of fairness in a context of prediction-based decisions. Usually, mathematical definitions requires achieving **parities across distributions of outcomes or scores** (common examples include statistical parity and calibration). Definitions can refer to **individuals** (e.g., requiring that similar individuals are treated similarly) or **groups** (e.g., requiring that any error measure is equal across groups, defined by so-called protected characteristics like gender or race).

Mathematical definitions can reflect philosophical conceptualisations, such as the **equality of outcomes and the equality of opportunities**. In general, computer science literature expresses in empirical and formal terms philosophical problems of **distributive justice** in which the goal of fairness is to achieve an **equal allocation of goods**.

## DATA SET FAIRNESS 3

**What is data set fairness?**

The concept of fairness is frequently found also in **text of law** and it has been extensively analysed by the legal scholarship, having its roots in the "**bona fide**" concept in Roman law. The fairness principle is an **overarching obligation** in the European Digital Strategy, for example in Article 5, par. 1, of GDPR, and in the Data Act, but it is also found in the EU and in other countries in many pieces of law, such as Article 8, par. 2, of the Charter of Fundamental Rights of the European Union, contract law, and others.

The data protection law scholarship divide the fairness principle into two elements, **procedural fairness** and **fair balancing**, noting that the concept of fairness is related to the idea of **vulnerability**. The GDPR aims at protecting data subjects, who are in a vulnerable position as opposed to data controllers, therefore it tries to make a balance between the fundamental rights and freedoms of the former and the interests of the latter.

## FAIRNESS ASSESSMENT OF DATA SETS

So far, the assessment of algorithmic fairness in the context of data has followed **two main directions**. A research track regards the analysis of **data curation processes** or the development of new **documentation frameworks**. Recently, Fabris et. Al annotated hundreds of data sets employed in algorithmic research efforts specifying key fairness-related characteristics (e.g. the domain of application, the target task and the sensitive attributes encoded in the data set) in order to address the so-called “documentation debt”.

Another direction focuses on the **empirical analysis of fairness-related data dimensions**. These efforts include **pre-processing techniques** such as sanitization and instance re-weighting and procedures evaluating distinct sources of discrimination in data collection or studying the effect of data-related factors on the fairness of algorithms.

## OUR WORK

Investigating Semi-Automatic Assessment of Data-set Fairness by Means of Fuzzy Logic

**Chiara Gallese**
*Department of Mathematics and Geosciences*
*University of Trieste*
*Trieste, Italy*

**Teresa Scantanburlo**
*Department of Environmental Sciences, Informatics and Statistics*
*Ca’ Foscari University of Venice*
*University of Trieste*
*Trieste, Italy*

**Luca Manzoni**
*Department of Mathematics and Geosciences*
*University of Trieste*
*Trieste, Italy*

**Marco S. Nobile**
*Department of Environmental Sciences, Informatics and Statistics*
*Ca’ Foscari University of Venice*
*Venice, Italy*
*Department of Industrial Engineering & Innovation Sciences*
*Eindhoven University of Technology*
*Eindhoven, The Netherlands*
*Bicocca Bioinformatics, Biostatistics and Bioimaging research center (B4)*
*Monza, Italy*
*marco.nobile@unive.it*

## FANFAIR AIMS

Our work moves along the line of empirical research with some important distinctions. The fairness-related features we explore are **agnostic about the sensitive attribute** in that they capture essential vulnerabilities that may contribute to model (un)fairness.

Another distinct aspect of our approach is to integrate **statistical information** about the data sets (**balance, numerosity, unevenness, incompleteness**) with **qualitative considerations** (**compliance, quality**) which take into account legal and ethical requirements of data-related practices (e.g. GDPR, principles of research integrity). This integration is operated through the application of **fuzzy rule-base logic** and reflected in a score that can be indicative of the fairness potentially introduced by a given data set.

## FANFAIR DEFINITION OF FAIRNESS

Although in our paper we take into consideration GDPR, we do not limit the concept of (legal) fairness to data protection law, but we expand the notion to other areas of law, including the **non-discrimination principle**, that is found, *inter alia*, in the European Convention of Human Rights, the **equity principle**, and the **bona fide principle** in contractual agreements.

In our opinion, a data set which data collection has been flawed by discrimination or another breach of the law (e.g., copyright law, criminal law, medical law) cannot be considered fair.

The **lawfulness criteria** is also in line with the High-Level Expert Group on AI (HLEG AI)'s guidelines on Trustworthy AI.

## FANFAIR FUZZY LOGIC ASSESSMENT

In order to assess the potential fairness of a data set, we identified six different elements that should be addressed before employing the data set. To identify each criteria, we were inspired by general principle of civil law and EU law, and established ethics guidelines.

**TABLE I**
**DESCRIPTION OF THE DATA SET FEATURES / LINGUISTIC VARIABLES CONSIDERED IN THIS WORK.**

| Feature | Meaning |
| :--- | :--- |
| **balance** | How balanced is the data set, with respect to the output labels. |
| **numerosity** | The numerosity of instances with respect to the number of features. |
| **evenness** | A metric assessing the amount of outliers in the data set. |
| **compliance** | How much the data set is compliant with respect to governmental rules. |
| **quality** | A user-defined evaluation of the overall quality of the data set. |
| **incompleteness** | This metric measures the amount of missing data in the data set. |

## BALANCE

A data set can be defined as “balanced” if **all classes are well represented** in the data set. The importance of balance is described in a wealth of literature: an unbalanced data set may produce biased models, unable to generalise and with prejudicial effects on single individuals or entire categories of individuals, such as disparity in accuracy.

For example, if a data set, which is used to train a model aimed at classifying patients in healthy or non-healthy, contains **thousands of examples of non-healthy patients** and only a **few example of healthy individuals**, the model will probably be unable to recognise healthy individuals with high accuracy. It is therefore crucial to have a similar number of examples in each class.

## NUMEROSITY

This data set feature refers to the **quantity of instances** normalised by the **number of features** in the data set. The quantity is important in order to mitigate possible biases in the model output: a model with a low number of examples will not be able to generalise.

To show an example of why this can happen, consider the situation in which all the features have no relation with the outputs to be predicted. In that case, we would like to have a machine learning algorithm to be unable to perform well since there is actually no relation with the between the inputs and the outputs: any learned relation will be purely the effect of chance, it will not be representative of the phenomenon being modelled and will clearly be unable to generalise.

A widespread **rule of thumb** of machine learning suggests that an optimal number of instances S would be 10 × D.

## NUMEROSITY OF WHAT?

Sometimes the **quantity of instances** normalised by the **number of features** in the data set is **high**, because multiple samples were collected from a **single person**. In this case, depending on the problem and the purpose of our model, numerosity might still **not be enough to have a reliable output** and we might need to collect samples from multiple persons.

It is important to talk with the **domain expert** to understand if this is the case.

## UNEVENNESS

This feature refers to the **number of outliers in the examples**. If a value is very different from all other values in the data set, it is important to understand why this occurs. For example, in a data set made of physiological values of non-healthy patients, in the weight column we could find abnormal values (too high or too low).

The **domain expert** will certainly understand that an adult individual cannot have a weight of 100 grams or of 20000 kilograms, and therefore there is an **error in the data collection**. However, outliers might sometimes be just **individuals with unique features** with respect to the average, such as a patient with a weight over 600 kilograms. In this case, there is a **risk of singling out** and the patient’s identity will likely be recognized if the data set is released to the public.

It is important to note that **outliers are not useful for the model**, since they refers to particular cases which might better be assessed individually by the domain expert instead of by an automatic mean such as an AI model. The model will not be able to generalise and give an accurate output for outliers’ cases. Instead, it would be more useful to create a different model specifically calibrated to individuals who present abnormal values.

## QUALITY

This feature refers to the quality of data as **assessed by the domain expert** (such as if an image is clear or complete, or if the sound can be recognised in a recording). The domain expert will make an **assessment** about the quality of the data set, based on the **state of the art** in the specific field (such as medical imaging) and on the needs related to each specific model.

This step is needed because the data collection is often performed by different people without direct supervision (e.g., nurses, young medical trainees, students, etc.), therefore errors in acquiring clear data may occur.

Do not use a data set to train models employed in **critical applications** (e.g., clinical decisions) if a domain expert has not validated the quality of the data.

## INCOMPLETENESS

This feature refers to “**holes**” in the data set regarding **relevant elements**, such as **missing information** about a patient in one or more physiological values. When this circumstance occurs, it is necessary to exploit **imputation techniques** or to **discard the patient** from the data set altogether, if too little information is provided. There are three possible types of incomplete data sets:

1.  some **variables** (e.g., dataframe columns) may have **missing values**. For instance, this might happen when the variable is related to some exam that is only administered to very specific patients;
2.  some **instances** (e.g., dataframe rows) may have **missing values**. For instance, this might happen to fragile patients that cannot undergo some treatments or exams;
3.  finally, the holes can be **randomly distributed** across all variables and instances of the data sets.

## RESULTS OF FANFAIR

These variables represent important characteristics that are automatically extracted by the data set or (in the case of compliance and quality) are entered by the user. FAnFAIR returns a summary of the contribution of all variables to the final fairness value. The contributions are expressed both in fuzzy terms (e.g., “compliance is fairly high”) and by using a visual plot. The final fairness value is calculated as a value between 0 (totally unfair) and 1 (maximum theoretical fairness).

**TABLE II**
**RULE-BASE USED BY FANFAIR FOR THE ASSESSMENT OF DATA SET FAIRNESS.**

| Rule 1: | IF balance IS high THEN $\varphi$ IS high\_fairness |
| :--- | :--- |
| Rule 2: | IF balance IS low THEN $\varphi$ IS low\_fairness |
| Rule 3: | IF numerosity IS high THEN $\varphi$ IS high\_fairness |
| Rule 4: | IF numerosity IS low THEN $\varphi$ IS low\_fairness |
| Rule 5: | IF unevenness IS high THEN $\varphi$ IS low\_fairness |
| Rule 6: | IF unevenness IS low THEN $\varphi$ IS high\_fairness |
| Rule 7: | IF compliance IS high THEN $\varphi$ IS high\_fairness |
| Rule 8: | IF compliance IS low THEN $\varphi$ IS low\_fairness |
| Rule 9: | IF quality IS high THEN $\varphi$ IS high\_fairness |
| Rule 10: | IF quality IS low THEN $\varphi$ IS low\_fairness |
| Rule 11: | IF incompleteness IS high THEN $\varphi$ IS low\_fairness |
| Rule 12: | IF incompleteness IS low THEN $\varphi$ IS high\_fairness |

## Existing techniques (pros & cons)

*   Select a statistically significant sample and check it manually
*   Over- or under-sampling
*   Make your **testing** data set balanced
*   Use automated techniques, e.g., automated gender recognition, to fill the gaps in metadata
*   Use multiple data sets and combine them
*   Collect new data to integrate missing data
*   Use data augmentation and/or synthetic data
*   Pre-process your data to add noise or other relevant elements
*   Compare your model output with that of different models in different settings

## DATA SET BALANCING

If there is a severe imbalance and the dataset is tiny (or high dimensional, etc.), which is frequently the situation in clinical data sets, imbalance could be problematic. Having unbalanced data can be an issue depending on the application's objectives.

For instance, if you want to forecast a given outcome and your data shows that A occurs 99.99% of the time and B occurs 0.01% of the time, your algorithm would likely always suggest A. However, in many cases, we are more curious about why B occurs on occasion than we are about whether the prediction was accurate. We might be interested in good performance on a minority class. Unbalanced data, therefore, becomes a concern. The technique you used is appropriate, but not for your question.

See: https://stats.stackexchange.com/questions/283170/when-is-unbalanced-data-really-a-problem-in-machine-learning

## HOW DO WE SOLVE DATA SET UNBALANCE?

*   **Baseline Methods**
    *   Random over-sampling
    *   Random under-sampling
*   **Under-sampling Methods**
    *   Tomek links
    *   Condensed Nearest Neighbor Rule
    *   One-sided selection
    *   CNN + Tomek links
    *   Neighborhood Cleaning Rule
*   **Over-sampling Methods**
    *   Smote
*   **Combination of Over-sampling method with Under-sampling method**
    *   Smote + Tomek links
    *   Smote + ENN

Source: A Study of the Behavior of Several Methods for Balancing Machine Learning Training Data Author: Gustavo E. A. Batista Presenter: Hui Li University of Ottawa.

## OVERSAMPLING AND UNDERSAMPLING

**You shouldn't over-sample the test set, only the training test**

[IMAGE: Comparison graphic showing Undersampling (reducing samples of the majority class) and Oversampling (copying samples of the minority class) to achieve balance.]

## DATA AUGMENTATION

It is a set of techniques that expand the available dataset without actually collecting new elements: **data augmentation applies controlled random changes to existing data, making modified copies of it, in order to reduce overfitting.**

Like all techniques, it can introduce biases.

## IMPUTATION

Imputation techniques "guess" realistic values that are used to replace missing values (“holes”) in a dataset. The model guesses data by assuming that they are similar to the ones that already are present in the data set, which is going to reinforce any pattern that might be in the data, potentially turning a non-significant pattern into a significant one and thus introducing biases.

Example: Missing data can substantially affect the precision of estimated change in patients reported outcomes scores from clinical registry data. Inclusion of auxiliary information in Multiple Imputation models can increase precision and reduce bias, but identifying the optimal auxiliary variable(s) may be challenging.

(Ayilara, O.F., Zhang, L., Sajobi, T.T. et al. Impact of missing data on bias and precision when estimating change in patient-reported outcomes from a clinical registry. *Health Qual Life Outcomes* 17, 106 (2019). https://doi.org/10.1186/s12955-019-1181-2)

## SYNTETHIC DATA

*   **Synthetic data** is information that's artificially created, it is not collected or generated by real-world events or persons. Generally, it is created by algorithms, but of course it can be generated by hand as well
*   Synthetic data and original data should deliver very similar results when undergoing the same statistical analysis
*   It has the benefit to protect privacy, as real personal data can be avoided. A privacy assurance assessment should be performed to ensure that the resulting synthetic data is not actual personal data, evaluating the extent to which data subjects can be identified in the synthetic data and how much new data about those data subjects would be revealed upon successful identification
*   It might contribute to mitigate bias by using fair synthetic datasets to train artificial intelligence models, manipulated to have a better representativeness of the world
*   The quality of synthetic data is highly correlated with the quality of the original data and the data generation model. Synthetic data may reflect the biases in original data. Also, the manipulation of datasets to create fair synthetic datasets might result in inaccurate data

## ANY QUESTION?

C,.GALLESE@TILBURGUNIVERSITY.EDU

## Credits

Images and videos in this presentation are used under **fair use for educational purposes**.

They belong to/were found in:

**Pixabay**
**Microsoft**
**Slidego**
**Data Protection Network**
**OM Data Consulting**
**Shutterstock**

**johnchow.com**
**inbusiness.kz**
**Avito.ru**
**medium.com**
**million-wallpapers.ru**
**www.flickr.com/people/tim2k**