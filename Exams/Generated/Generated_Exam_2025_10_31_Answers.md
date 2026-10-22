# JBL110: Innovation & Regulation - Final Exam (Answer Key)

**Date:** October 31, 2025

---

### **Question 1: Regulatory Strategies and the 'Pacing Problem'**

**a) Based on the lecture materials from Module 1, identify and describe three distinct regulatory strategies that are reflected in the DSA, DMA, and AI Act. For each strategy, explain its core mechanism and provide a specific example of its application within one of these legal acts.**

*   **Risk-Based Regulation:** This strategy prioritizes regulatory actions based on the level of risk an activity poses. It requires developing risk-scoring mechanisms to focus resources on the most harmful areas.
    *   **Example:** The **AI Act** is fundamentally a risk-based instrument. It categorizes AI systems into unacceptable, high, and low/minimal risk tiers. High-risk systems (e.g., those used in critical infrastructure or employment) are subject to strict mandatory requirements, such as data governance and human oversight, while low-risk systems (e.g., chatbots) face lighter transparency obligations.

*   **Disclosure (or Transparency):** This strategy mandates the provision of information to users or regulators to enable informed decisions and oversight. It aims to correct information asymmetries.
    *   **Example:** The **Digital Services Act (DSA)** imposes significant disclosure requirements on large online platforms. They must be transparent about their content moderation practices, the functioning of their recommendation algorithms, and provide clear information to users when their content is removed.

*   **Market-Harnessing Controls / Command & Control:** This strategy channels market forces or imposes direct obligations to alter market structures and prevent anti-competitive behavior. The DMA uses a command-and-control style to achieve market-harnessing goals.
    *   **Example:** The **Digital Markets Act (DMA)** imposes *ex-ante* obligations on designated "gatekeeper" platforms. For instance, Article 6(11) commands gatekeeper search engines to provide access to ranking, query, and click data to rival search engines on fair, reasonable, and non-discriminatory (FRAND) terms. This is a direct command intended to harness market forces by enabling smaller competitors.

**b) Discuss the concept of "regulatory disconnect" as presented in Module 1. How do the horizontal, vertical, and institutional dimensions of this disconnect apply to the regulation of General Purpose AI systems, as discussed in the context of the AI Act?**

Regulatory disconnect, or the "pacing problem," refers to the gap between the fast pace of technological innovation and the slower pace of regulation.

*   **Horizontal Dimension (Timing):** This concerns *when* to regulate. For General Purpose AI (GPAI), regulating too early could stifle innovation before its potential is realized. Regulating too late could allow powerful, potentially biased systems to become deeply embedded, making risks difficult to mitigate. The AI Act's approach of regulating GPAI models based on their potential to become high-risk systems is an attempt to connect at a foundational stage without being overly prescriptive about all future applications.

*   **Vertical Dimension (Specificity):** This concerns the level of regulatory detail (technology-specific vs. technology-neutral). A purely technology-neutral approach (e.g., applying only general liability rules) might be too vague for the unique risks of GPAI. A highly technology-specific approach would quickly become obsolete. The AI Act attempts a layered approach: it sets general, principle-based requirements for GPAI models, while the more specific rules apply when these models are integrated into a high-risk *application*.

*   **Institutional Dimension (Regulator):** This concerns who regulates. A traditional government body may lack the technical expertise and agility to oversee GPAI. The AI Act establishes an AI Board and relies on national competent authorities, creating a specialized institutional framework. The challenge is ensuring these bodies have the necessary resources, independence, and expertise to address the complex and evolving nature of GPAI, thereby maintaining the "regulatory connection."

**c) Considering the five characteristics of 'good' regulation discussed in Module 1, evaluate the EU's risk-based approach in the AI Act. Does this approach effectively create 'good' regulation for a rapidly advancing technology like AI? Justify your answer.**

The five characteristics of 'good' regulation are: 1) supported by legislative authority, 2) appropriate accountability, 3) fair, accessible, and open procedures, 4) sufficient expertise, and 5) efficiency.

The AI Act's risk-based approach attempts to achieve 'good' regulation as follows:
*   **Legislative Authority & Accountability:** The Act is a formal EU Regulation, providing clear legislative authority. It establishes accountability by placing clear obligations on providers of high-risk systems and creating supervisory bodies (AI Board, national authorities) to oversee compliance.
*   **Fair & Open Procedures:** The Act includes provisions for conformity assessments, post-market monitoring, and the right for users to be informed, which contributes to procedural fairness. The tiered risk approach is designed to be accessible, applying the heaviest burdens only where necessary.
*   **Expertise:** The approach acknowledges the need for specialized knowledge by creating dedicated bodies like the AI Board. However, a key challenge will be ensuring these bodies can recruit and retain the necessary technical talent to keep pace with AI development, which is crucial for the regulation's long-term success.
*   **Efficiency:** The risk-based approach is inherently designed for efficiency. By focusing the most stringent (and costly) requirements on high-risk applications, it avoids overregulating the entire AI market, allowing innovation in low-risk areas to proceed with fewer burdens. This targeted intervention aims to provide net benefits without stifling the broader AI economy.

In conclusion, the risk-based approach is a strong framework for creating 'good' regulation for AI. It balances protection with efficiency and establishes clear lines of authority and accountability. Its ultimate success will depend on the practical implementation, particularly the ability of regulatory institutions to maintain sufficient expertise.

---

### **Question 2: Health Data Sharing and the European Health Data Space (EHDS)**

**a) Explain the difference between the 'primary use' and 'secondary use' of health data as defined in the EHDS Regulation. Describe one key regulatory mechanism the EHDS establishes for each type of use.**

*   **Primary Use:** This refers to the processing of health data for the direct provision of healthcare to an individual (Art. 2(2)(d)). It is about using a patient's data for their own treatment.
    *   **Mechanism:** A key mechanism for primary use is the creation of a **European electronic health record exchange format (EHR-EF)** (Art. 15). This standardizes the format of health records, ensuring that a patient's data (e.g., patient summaries, e-prescriptions) is interoperable and can be accessed and understood by healthcare professionals across different EU Member States through the **MyHealth@EU** infrastructure.

*   **Secondary Use:** This refers to the processing of health data for purposes other than the initial reason for collection, such as scientific research, innovation, policy-making, or regulatory activities (Art. 2(2)(e)). It is about using aggregated or anonymized data for the benefit of society.
    *   **Mechanism:** A key mechanism for secondary use is the establishment of **Health Data Access Bodies (HDABs)** in each Member State (Art. 55). These bodies act as a single point of contact for researchers or companies seeking access to health data. They manage data access applications, issue data permits, and provide access to the data through a secure processing environment, streamlining the process while ensuring data protection.

**b) A health insurance company, "Aeolian," wants to develop an AI-based lifestyle coach using fitness tracking data from the "VitaFit" app to provide preventative advice to all residents of a fictional EU Member State. According to the EHDS framework (Module 2), what steps must Aeolian take to gain access to this data for secondary use? Address the roles of the Health Data Access Body (HDAB) and the data holder in your answer.**

To gain access to the VitaFit app data for secondary use, Aeolian must follow the administrative procedure outlined in the EHDS Regulation:

1.  **Submit a Data Access Application:** Aeolian (the "Health Data User") must submit a data access application to the **Health Data Access Body (HDAB)** of the Member State where the data is located.
2.  **Application Content:** The application must specify the purpose of the data use (developing an AI coach for preventative lifestyle interventions), demonstrate that this purpose contributes to the general interest of society (reducing healthcare costs, improving health outcomes), and detail the specific data categories needed.
3.  **HDAB Review:** The HDAB will review the application to ensure it complies with the allowed purposes for secondary use (Art. 53) and does not fall under the prohibited purposes (e.g., for marketing or developing harmful products, Art. 54).
4.  **Data Permit Issuance:** If the application is approved, the HDAB will issue a **data permit** to Aeolian (Art. 68). This permit specifies the conditions under which the data can be used.
5.  **Data Holder's Role:** The HDAB will then request the data from the **data holder** (in this case, the company behind the VitaFit app). The data holder is obligated to make the data available to the HDAB upon receipt of a valid request based on the data permit (Art. 60).
6.  **Secure Processing Environment:** The HDAB will make the data available to Aeolian within a **secure processing environment** (Art. 73). Aeolian will not receive the raw data directly; instead, they will conduct their analysis and AI model training within this controlled environment, and can only extract the results (e.g., the trained model), not the underlying data.

**c) The EHDS includes an opt-out clause (Article 71) for the secondary use of health data. Discuss the tension this creates between the public interest in "harnessing the potential of (existing) data" and the private interest in "individual control and autonomy." How does this reflect the broader challenges of regulating a non-rivalrous good like data?**

The tension created by the opt-out clause is central to the debate on data regulation:

*   **Public Interest:** The secondary use of health data holds immense public interest. Aggregated data can fuel research into diseases, improve public health policies, and drive innovation in treatments and diagnostics. From an economic perspective, data is a non-rivalrous good; its use by one researcher does not prevent its use by another. Maximizing its use can lead to significant societal benefits and economic efficiencies (economies of scope and scale).

*   **Private Interest:** The private interest is rooted in fundamental rights, particularly the right to privacy and data protection. Individuals have a right to control their personal information, especially sensitive health data. The opt-out clause empowers individuals by giving them final say over how their data is used beyond their direct care, upholding the principle of individual autonomy.

The opt-out clause represents a compromise. It acknowledges the immense value of data sharing for the public good but prioritizes individual autonomy. This reflects a broader challenge in regulating data: because data is non-rivalrous and can be easily copied and aggregated, its potential for societal benefit is vast. However, because it is often deeply personal, the potential for harm to individual rights is also significant. A widespread exercise of the opt-out right could lead to datasets that are incomplete or biased, undermining the very public interest goals the EHDS seeks to achieve. This compromise highlights that while data's economic characteristics push for widespread sharing, its connection to human identity and rights necessitates regulatory frameworks that prioritize individual control.

---

### **Question 3: Competition Law in the Age of Big Tech**

**a) Explain the concept of a "dominant position" under Article 102 TFEU. Based on the lecture material from Module 3, what factors would the European Commission consider when determining if a company like Google holds a dominant position in the online search market?**

A "dominant position" under Article 102 TFEU is a position of economic strength that enables an undertaking to prevent effective competition by behaving to an appreciable extent independently of its competitors, customers, and ultimately, its consumers. It is not illegal to be dominant, but it confers a "special responsibility" not to abuse that position.

When determining if Google holds a dominant position in the online search market, the European Commission would consider several factors:
*   **Market Share:** Consistently high market share (often above 80-90% in many EU countries for general search) is a primary indicator of dominance.
*   **Barriers to Entry:** The Commission would assess how difficult it is for new search engines to enter the market and compete. This includes the massive investment required in infrastructure, technology, and, crucially, the vast amounts of data needed to refine search algorithms. Data-driven network effects (more users lead to more data, which improves the service, which attracts more users) create a formidable barrier.
*   **Lack of Countervailing Buyer Power:** Consumers have little power to negotiate terms with Google. The service is offered for "free" in monetary terms, but users provide valuable data, and there are high switching costs in terms of user habits and integration with other services (e.g., Android, Chrome).
*   **Behavioral Independence:** The ability of Google to set its own terms for advertisers (e.g., in AdSense) or to favor its own services (e.g., Google Shopping) in search results without losing significant market share indicates independence from competitive pressure.

**b) The German Federal Cartel Office's case against Meta (Facebook) involved the company's practice of combining user data from different sources (Facebook, Instagram, WhatsApp) without specific consent. The CJEU ruled that data protection considerations under the GDPR can be taken into account in an abuse of dominance case. Explain how forcing users to agree to such data combination could constitute an "abuse" under Article 102 TFEU, referencing the types of abusive conduct discussed in the lecture.**

Forcing users to agree to the combination of their data from different services can be considered an abuse of a dominant position under Article 102 TFEU, specifically as an imposition of **"unfair trading conditions"** (Article 102(a)).

The argument is as follows:
1.  **Dominant Position:** Meta is dominant in the market for social networks.
2.  **Imposition of Unfair Conditions:** The "take-it-or-leave-it" nature of the terms of service, where users must consent to the data combination to use the service, is an imposition. This condition is "unfair" because it is not compliant with the principles of the GDPR, which requires consent to be freely given, specific, and informed for each processing purpose. By bundling consent for data combination with access to the service, Meta leverages its market power to force users into an arrangement they might otherwise reject.
3.  **Exploitative Nature:** This practice is exploitative. It harms consumers by diminishing their data privacy and control, which is a key parameter of quality in the digital economy. The abuse lies in using market dominance to extract a non-monetary "price" (i.e., extensive personal data) from consumers under conditions that violate other legal frameworks designed to protect them. The CJEU's ruling confirms that a practice's non-compliance with GDPR can be an indicator of its unfairness under competition law.

**c) Compare the main objectives and enforcement approaches of EU competition law with those of US competition law, as discussed in Module 3. How might these differences lead to divergent outcomes in cases against Big Tech companies, such as the various investigations into Google?**

| Category | EU Competition Law | US Competition Law |
| :--- | :--- | :--- |
| **Main Objective** | Broader focus: protecting the **competitive process** itself, ensuring market integration (the Single Market), and promoting consumer welfare and economic efficiency. | Narrower focus: primarily concerned with **consumer welfare**, often interpreted through a strict economic lens (e.g., impact on prices and output). |
| **Enforcement** | Primarily an **administrative system**. The European Commission investigates, issues decisions, and imposes fines. | Primarily a **criminal law / litigation-based system**. The Department of Justice (DOJ) and Federal Trade Commission (FTC) bring cases to court. |
| **Fines** | Can be very high, up to 10% of a company's annual *worldwide* turnover. | Fines can be substantial but are often based on profits or damages incurred and may be lower than in the EU. |

These differences can lead to divergent outcomes in cases against Big Tech:
*   **Google Shopping Case:** The EU fined Google €2.42 billion for abusing its dominance by favoring its own comparison shopping service in its search results. The EU's focus on protecting the "competitive process" and ensuring a level playing field for rivals made this a clear-cut case of abuse. In the US, it would be harder to prove direct consumer harm, as the search service itself remained free. An argument would have to be made that consumers were harmed by reduced choice or quality, which is a higher bar.
*   **Focus on Data and Privacy:** The EU's broader objectives allow it to more easily incorporate non-price factors like data privacy (as seen in the Meta case) as an element of consumer welfare and competitive harm. The US system, with its stricter focus on price effects, has been slower to treat privacy violations as an antitrust issue.
*   **Proactive vs. Reactive:** The EU's administrative system and *ex-ante* tools like the DMA allow for more proactive regulation to shape the market. The US system is more reactive, relying on lengthy court battles to prove harm after it has occurred, which can be a slow process for fast-moving tech markets.

---

### **Question 4: Intellectual Property and Data Mining**

**a) A university research team wants to perform data mining on a publicly accessible, but subscription-based, online database of scientific articles for a non-commercial research project. The database itself is protected by a *sui generis* database right. The subscription agreement explicitly forbids data mining. Can the research team legally perform the data mining under the DSM Directive? Explain your reasoning, referencing the relevant articles.**

Yes, the research team can legally perform the data mining.

Their right to do so comes from **Article 3 of the DSM Directive**. This article provides a mandatory exception for text and data mining (TDM) for the purposes of scientific research.
1.  **Beneficiary:** The university is a "research organization" as defined in the directive (acting on a non-profit basis or for a public interest mission).
2.  **Lawful Access:** The team has lawful access to the database via their subscription.
3.  **Purpose:** The data mining is for "scientific research."
4.  **Cannot be Overridden by Contract:** Crucially, **Article 7** of the DSM Directive states that any contractual provision contrary to the exception in Article 3 is **unenforceable**. Therefore, the clause in the subscription agreement forbidding data mining is void, and the research team can legally proceed.

**b) Now, consider a for-profit data analytics startup that wants to mine the same database to develop a new commercial product. The database provider has used a `robots.txt` file to signal that it reserves all rights to data mining. Can the startup legally proceed with the data mining under the DSM Directive? Explain why or why not.**

No, the startup cannot legally proceed with the data mining.

The startup would have to rely on **Article 4 of the DSM Directive**, which provides a broader TDM exception for any purpose (including commercial). However, this exception is not absolute.
1.  **Beneficiary:** The startup, as "any person," could potentially benefit from this exception.
2.  **Lawful Access:** Assuming the startup has lawful access (e.g., a subscription).
3.  **Opt-Out Provision:** Article 4(3) allows rightholders to "opt-out" of this exception by expressly reserving their rights in an appropriate manner. For content made publicly available online, Recital 18 specifies that this can be done in a **machine-readable format**, such as a `robots.txt` file or metadata.
4.  **Effect of Opt-Out:** Since the database provider has used a `robots.txt` file to reserve its rights, they have successfully opted out of the Article 4 exception. The startup is therefore bound by the *sui generis* database right, and proceeding with data mining (which constitutes extraction) without a license would be an infringement.

**c) The CJEU case *Ryanair v PR Aviation* established that contractual terms of use can prevent the scraping of a database that is *not* protected by either copyright or the *sui generis* right. Explain the court's reasoning and discuss the implications of this decision for data-driven innovation.**

**Court's Reasoning:** The CJEU reasoned that the Database Directive is intended to harmonize the rights and exceptions for databases that *qualify* for protection under its specific criteria (originality for copyright, substantial investment for *sui generis* right). If a database **does not meet these criteria**, it falls outside the scope of the Directive entirely. Consequently, the limitations and user rights provided by the Directive (such as the rights of a lawful user in Art. 6(1)) do not apply. In the absence of specific IP protection, the owner of the database is free to set conditions for its use based on general principles of contract law. Therefore, Ryanair was entitled to enforce its website's terms of use, which prohibited screen scraping for commercial purposes, against PR Aviation.

**Implications for Data-Driven Innovation:** This decision has significant implications:
*   **Empowers Database Owners:** It empowers the creators of unprotected databases to use contract law as a powerful tool to control access to and use of their data, effectively creating a form of *de facto* property right even where IP law grants none.
*   **Barrier to Innovation:** For data-driven innovators, especially startups and SMEs, this creates a significant barrier. They cannot freely scrape and analyze publicly available data if the website's terms of use forbid it. They must negotiate licenses, which can be costly or may be refused by the data owner, stifling competition and innovation that relies on aggregating data from multiple sources.
*   **Limits the "Public Domain" of Data:** It shrinks the effective public domain of data. Even if data is factual and its compilation doesn't meet the "substantial investment" threshold, it can still be locked away behind contractual walls, limiting its potential for reuse and analysis by third parties.

---

### **Question 5: AI, Bias, and Data Governance**

**a) Define "selection bias" and "implicit bias" as discussed in the lecture materials for Module 5. Provide a real-world example for each, explaining how it could lead to a discriminatory outcome in an AI system used for hiring.**

*   **Selection Bias:** This occurs when the data used to train a model is not representative of the real-world distribution of data. It often results from improper randomization or a flawed data collection process.
    *   **Hiring Example:** An AI model is trained to screen resumes for a software engineering role using the company's historical data of successful hires. If, historically, the company predominantly hired male engineers, the dataset will be skewed. The model may learn to associate characteristics more common in male applicants' resumes with success, and systematically down-rank qualified female applicants, thus perpetuating historical hiring patterns.

*   **Implicit Bias:** This refers to the unconscious assumptions, stereotypes, and attitudes that people hold, which can be embedded in the data they create. These biases are not intentional but reflect societal or personal prejudices.
    *   **Hiring Example:** A company uses transcripts from hiring interviews to train a model to predict candidate success. If human interviewers unconsciously ask more challenging technical questions to female candidates or interpret answers from male candidates more favorably, this bias becomes encoded in the data. The AI model, learning from this data, might then incorrectly score female candidates lower, not because of their skills, but because it has learned the implicit bias of the human interviewers.

**b) According to the AI Act (Article 10 and Recital 44), what are the key requirements for training, validation, and testing datasets for high-risk AI systems? Explain the purpose of the provision that allows for the processing of special categories of personal data for bias monitoring and correction.**

The key requirements for datasets for high-risk AI systems are:
1.  **Relevance and Representativeness:** Datasets must be sufficiently relevant, representative, and have appropriate statistical properties for the intended purpose of the AI system.
2.  **Free of Errors and Complete:** Datasets should be as free of errors and as complete as possible in view of the intended purpose.
3.  **Appropriate Data Governance:** Providers must implement data governance and management practices, including assessing data availability and suitability, examining for possible biases, and identifying and addressing data gaps.
4.  **Context-Specific:** Datasets must take into account the features and characteristics of the specific geographical, behavioral, or functional setting in which the AI system will be used.

**Purpose of Processing Special Categories of Data:** The AI Act allows for the processing of special categories of personal data (e.g., data on racial or ethnic origin) as a matter of "substantial public interest" for the specific purpose of **bias monitoring, detection, and correction**. The rationale is that to determine if an AI system is biased against a certain demographic group, the system must be tested using data that includes information about that demographic characteristic. Without processing this sensitive data, it would be impossible to measure and correct for biases related to race, gender, or other protected attributes, thereby undermining the Act's goal of preventing discrimination. This processing is subject to appropriate safeguards, such as pseudonymization and technical limitations on re-use.

**c) A developer is creating an AI model for a hearing aid designed to help users understand conversations better. They use the Mozilla Common Voice dataset, which is licensed under CC-0 (public domain). Upon inspection, they find that 47% of the voice samples are from male speakers, while only 11% are from female speakers. Explain why this imbalance is a problem for the intended use of the AI model and describe two techniques (e.g., oversampling, data augmentation) the developer could use to mitigate this data set unbalance.**

**Problem of Imbalance:** This severe gender imbalance in the training data is a significant problem because it will lead to a biased and poorly performing AI model. The model will be trained extensively on male voices and will become very proficient at recognizing and processing them. However, due to the lack of data, it will be far less accurate at recognizing and processing female voices. For the end-user of the hearing aid, this means the device might work well when listening to men but fail to properly amplify or clarify women's speech, potentially making conversations with women *more* difficult. This is a discriminatory outcome that fails to meet the needs of a significant portion of the population the hearing aid is supposed to serve.

**Mitigation Techniques:**
1.  **Oversampling:** This technique involves balancing the dataset by increasing the number of samples in the minority class. The developer could apply random oversampling, which means duplicating the existing audio samples of female speakers until the number of female and male samples is roughly equal in the training set. A more advanced method is **SMOTE (Synthetic Minority Over-sampling Technique)**, which creates new, synthetic samples of female voices that are similar to, but not identical to, the existing ones, providing more diversity for the model to learn from.

2.  **Data Augmentation:** This technique involves creating new, modified copies of existing data to expand the dataset. For the audio data of female speakers, the developer could apply various augmentations to the existing samples. For example, they could slightly change the pitch, add background noise (e.g., cafe sounds, street noise), alter the speed of the speech, or add a slight echo. This creates a larger and more robust set of training examples for the minority class (female speakers), helping the model to generalize better and perform more accurately in diverse real-world environments.
