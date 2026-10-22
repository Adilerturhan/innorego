# JBL110 Innovation & Regulation — Generated Exam (November 2025)

Total points: 100  
Time: 3 hours  
Answer all five question sets. Allocate your time according to points. Be concise but precise. Where relevant, apply the structured approach from `Exams/Guide to solving problem questions.md` (Issue–Rule–Application–Conclusion). Cite course materials (by in-repo path) when useful.

Permitted materials: This is a closed-book exam unless otherwise indicated by your course policies.

Structure:
- Q1 (Module 1): Essay on regulatory strategies and innovation (20 pts)
- Q2 (Module 2): EHDS secondary use scenario (20 pts)
- Q3 (Module 3): Competition law (Arts. 101 & 102 TFEU) scenario (20 pts)
- Q4 (Module 4): Database, copyright & sui generis scenario (20 pts)
- Q5 (Module 5): Web scraping, anonymization, AI Act, bias & data governance scenario (20 pts)

You must state a clear “Yes/No/Uncertain” conclusion for problem questions (Q2–Q5) before your reasoning.

References to course materials:
- Module 1: `Module_1/lecture_1.md`, `Module_1/lecture_2.md`, Baldwin et al. notes and strategy overviews; Butenko & Larouche (e.g., `Module_1/why data ownership is the wrong approach.md`)
- Module 2: EHDS background (`Module_2/Health data sharing pt 1.md`, `Module_2/Health data sharing pt 2.md`, `Module_2/OJ_L_202500327_EN_TXT.md`, `Module_2/IPOL_STU(2022)740054_EN.md`)
- Module 3: `Module_3/Lecture Competition Law - MOK - FINAL.md`, ACD mock prompts
- Module 4: `Module_4/MENDIS_IP & Data Driven Innovation_Slides.md`, Database & TDM materials
- Module 5: `Module_5/Lezioni Tilburg 2025.md`, `Module_5/Identifying Bias in Data Collection.md`, `Module_5/Investigating Fairness with FanFAIR.md`, `Module_5/Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md`

---

## Question 1 — Module 1: Regulatory Strategies and Innovation (20 pts)

Essay question. Draw on `Module_1/lecture_1.md` and `Module_1/lecture_2.md` plus the assigned readings.

A new sectoral regulator is tasked with shaping the regulatory framework for generative AI services that integrate health-information search (non-clinical advice) and user-generated video platforms. The regulator considers a mix of:
- Command-and-control (prescriptive) rules
- Performance-based rules
- Incentive-based instruments (taxes/subsidies; tradable permits)
- Self-regulation and co-regulation
- Risk-based regulation
- Experimentalist approaches (e.g., sandboxes, sunset clauses)

a) Define each strategy and contrast their core mechanisms, accountability levers, and typical information requirements. (6 pts)

b) Using concrete examples from at least two sectors (e.g., content moderation; health data/EHR interoperability), explain how two different mixes of strategies have been applied in practice. What worked, what didn’t, and why? (6 pts)

c) Discuss “regulation for innovativeness” versus “regulation of innovation” (see Butenko & Larouche and course notes). How does the pacing problem influence choice of strategy, and how can meta-regulatory tools (e.g., oversight bodies, mandatory evaluation) mitigate risks? (5 pts)

d) Propose and defend an optimal strategy mix for the regulator’s remit above. State trade-offs and how you would measure success ex ante and ex post. (3 pts)

---

## Question 2 — Module 2: EHDS Secondary Use Scenario (20 pts)

Read `Module_2/Health data sharing pt 1.md`, `Module_2/Health data sharing pt 2.md`, and background EHDS documents (e.g., `Module_2/OJ_L_202500327_EN_TXT.md`). You are advising a public data access body on requests to access data for secondary use under the EHDS.

Scenario: The OncoLens Consortium (universities + SMEs) requests access to:
- Hospital EHR extracts (diagnoses, imaging metadata, lab results)
- National cancer registry records (incidence, outcomes)
- Genomic panels from a public biobank linked to phenotypic cohorts
- Real-world data from CE-marked medical devices (home ECG wearables)
- Health insurance claims (reimbursements), plus de-identified patient feedback surveys

They propose two projects:
1) Train a foundation model to assist oncology imaging triage for EU hospitals.
2) Build a commercial risk-scoring API for private insurers to price cancer policies.

a) For each dataset above, identify the likely health-data category under EHDS Art. 51 and state whether it should generally be made available for secondary use. Justify with EHDS objectives, typical exclusions/protections, and safeguards (do not recite verbatim provisions). (8 pts)

b) Assess whether Project 1 is a permitted purpose for secondary use and under what conditions. Do the same for Project 2. (4 pts)

c) Outline the data permit conditions the access body should impose: anonymization vs pseudonymization, security, data localization, IP/know-how protection, re-use restrictions, and disclosure controls (e.g., statistical confidentiality). (4 pts)

d) Conclusion: “Yes/No/Uncertain” for each requested dataset and for each project, with one-sentence reasons. (4 pts)

State your “Yes/No/Uncertain” first, then show your reasoning.

---

## Question 3 — Module 3: Competition Law (Arts. 101 & 102 TFEU) (20 pts)

See `Module_3/Lecture Competition Law - MOK - FINAL.md` and the ACD mock questions.

Scenario: MedGraph operates the dominant EU platform integrating: (i) hospital scheduling APIs, (ii) app distribution to certified medical-device makers, and (iii) data analytics dashboards. Practices include:
- Exclusive-dealing clauses with top-5 device makers (rebates conditioned on exclusivity).
- MFN clauses requiring partners to offer MedGraph prices/terms no worse than to rival platforms.
- Tying/bundling of the scheduling API to MedGraph’s analytics module for hospital enterprise customers.
- Refusal to grant full real-time API access to a new rival (ClinLink), citing “security/integrity”.

a) Define the relevant product and geographic markets; assess dominance. Specify tests and key indicators. (5 pts)

b) Analyse the exclusivity and MFN clauses under Art. 101: agreement between undertakings, restriction by object or effect, appreciability/affectation of trade, and potential 101(3) efficiencies. (6 pts)

c) Assess tying/bundling and refusal to supply/API access under Art. 102: tests for abuse, objective justifications, and essential facilities doctrine (where applicable). (6 pts)

d) Conclude on “monopolies in play” and likely infringements, and propose proportional remedies/commitments. State a “Yes/No/Uncertain” conclusion first. (3 pts)

---

## Question 4 — Module 4: Database Qualification and Protection (20 pts)

Use `Module_4/MENDIS_IP & Data Driven Innovation_Slides.md` and course readings on the Database Directive.

Scenario: AgriSense curates a platform aggregating farmer-contributed IoT sensor streams (soil moisture, pesticide usage), satellite imagery tiles, and manually verified plot metadata. The platform offers:
- A searchable index by geohash and crop type,
- A harmonized schema with quality scores,
- Downloads of monthly “regional bundles.”

Rival GreenPulse scraped AgriSense over 4 months, reconstructed the bundles, and released a competing dataset with minor relabelling. AgriSense’s ToS prohibit automated scraping.

a) Is AgriSense’s collection a “database” under Directive 96/9/EC? Apply the independence, systematic arrangement, and individual accessibility criteria. (4 pts)

b) Copyright: Does the database qualify for protection via the originality of selection/arrangement? Identify relevant creative choices and what copyright would (and would not) protect. (5 pts)

c) Sui generis right: Has there been a “substantial investment” (qualitative/quantitative)? Analyse extraction/re-utilization, and whether GreenPulse’s conduct amounts to a substantial part or repeated/systematic extraction. (6 pts)

d) Infringement and defenses: Evaluate GreenPulse’s exposure under copyright and sui generis rights, the “lawful user” and insubstantial part exceptions, relevance (if any) of TDM exceptions, and the contractual ToS angle. Conclude “Yes/No/Uncertain.” (5 pts)

Start with “Yes/No/Uncertain,” then provide your structured analysis.

---

## Question 5 — Module 5: Web Scraping, Anonymization, AI Act, Bias & Public Data Re-use (20 pts)

Draw on `Module_5/Lezioni Tilburg 2025.md`, `Module_5/Identifying Bias in Data Collection.md`, `Module_5/Investigating Fairness with FanFAIR.md`, and `Module_5/Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md`.

Scenario: CityEyes wants to scrape municipal open-data portals (public procurement notices, mobility feeds) and public social-media posts tagged to venues. They plan to:
- Build a city-safety score for neighbourhoods,
- Sell an API to landlords and private security firms,
- Train a computer-vision model using CCTV snapshots from city cameras released under an open license,
- Publish “anonymized” datasets and model cards.

a) Web scraping legality: Assess copyright and database rights risks, open-licensing terms, ToS/anti-scraping clauses, and public-sector re-use (Open Data/PSI). Identify when scraping is likely lawful/unlawful. (5 pts)

b) Anonymization & data protection: Are social-media + CCTV datasets “anonymous”? Discuss identifiability, k-anonymity vs differential privacy, linkage risks, DPIA needs, purpose limitation, and safeguards. (5 pts)

c) AI Act: Classify the planned systems (high-risk? GPAI? prohibited practices?) and outline the main obligations (data governance, risk management, logging, transparency, bias mitigation, human oversight). (5 pts)

d) Dataset fairness & bias: Identify likely biases (sampling/coverage, measurement/label, historical/representational). Apply FanFAIR-style principles for public datasets and propose concrete mitigations and governance controls. Conclude “Yes/No/Uncertain” on proceeding and under which conditions. (5 pts)