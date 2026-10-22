# JBL110 Innovation & Regulation — Generated Exam (November 2025) — Answers and Mark Scheme

This answer sheet provides:
- Detailed mark scheme (tables) for each sub-question
- Model answers
- Clear “Yes/No/Uncertain” conclusions for problem questions (Q2–Q5)

Cite course materials by in-repo path where helpful:
- Module 1: `Module_1/lecture_1.md`, `Module_1/lecture_2.md`, Butenko & Larouche; Baldwin et al. strategy notes; risk-based regulation materials
- Module 2: `Module_2/Health data sharing pt 1.md`, `Module_2/Health data sharing pt 2.md`, EHDS materials in `Module_2/OJ_L_202500327_EN_TXT.md`, `Module_2/IPOL_STU(2022)740054_EN.md`
- Module 3: `Module_3/Lecture Competition Law - MOK - FINAL.md`
- Module 4: `Module_4/MENDIS_IP & Data Driven Innovation_Slides.md`
- Module 5: `Module_5/Lezioni Tilburg 2025.md`, `Module_5/Identifying Bias in Data Collection.md`, `Module_5/Investigating Fairness with FanFAIR.md`, `Module_5/Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md`

---

## Q1 — Module 1: Regulatory Strategies and Innovation (20 pts)

### Mark scheme

| Part | Points | Criteria |
|-----:|-------:|---------|
| a    | 6      | Correct, succinct definitions of: command-and-control; performance-based; incentive-based; self-/co-regulation; risk-based; experimentalist (sandboxes, pilots, sunset). Clear contrasts on information needs, enforceability, accountability, adaptability. |
| b    | 6      | Two concrete sectoral examples (e.g., content moderation co-/self-reg plus platform duties; EHR interoperability performance-based + risk-based). Specifics: mechanisms used, outcomes (benefits/shortfalls), institutional context. |
| c    | 5      | Accurate distinction “for innovativeness” vs “of innovation”; pacing problem articulated; meta-regulatory tools (reviews, metrics, oversight, adaptive planning). Trade-offs (innovation vs precaution, capture risks). |
| d    | 3      | Plausible, defended strategy mix tailored to gen-AI + user video; measurable success metrics; acknowledgement of risks and mitigations. |

### Model answer (outline)

a) Definitions and contrasts:  
- Command-and-control: prescriptive input rules; high certainty; costly to update; info burden on regulator; strong ex ante clarity.  
- Performance-based: outcome targets; innovation-friendly; requires measurement/verification capacity; possible gaming.  
- Incentive-based: taxes/subsidies, tradable rights; efficient if externalities measurable; equity and distributional concerns.  
- Self-/co-regulation: industry codes with state backstop; flexible, quicker; risks of under-enforcement/capture; relies on transparency and auditability.  
- Risk-based: allocate oversight proportional to harm/likelihood; requires robust risk assessment; can miss systemic risks if data poor.  
- Experimentalist (sandboxes/pilots/sunset): test-learn-adapt; time-bound approvals; needs evaluation capacity and exit criteria.

b) Examples:  
- Content moderation (see `Module_1/YouTube Content Moderation and Regulatory Strategies_Model Answer.md`): co-regulation with platform duties, transparency reporting; self-reg codes; performance-based illegal content removal SLAs; mixed success—improved responsiveness but concerns over due process and over-removal.  
- EHR interoperability: performance-based standards + risk-based oversight (e.g., higher scrutiny for high-risk interfaces), procurement incentives. Benefits: interoperability gains; challenges: vendor lock-in and compliance costs.  
Alternative examples: fintech sandboxes; medical devices post-market surveillance.

c) For innovativeness vs of innovation (Butenko & Larouche; `Module_1/why data ownership is the wrong approach.md`):  
- “For innovativeness”: enabling infrastructure (interoperability, data access, procurement, IP/standards).  
- “Of innovation”: addressing risks (safety, privacy, consumer protection).  
- Pacing problem: innovation outruns rulemaking → prefer performance-, risk-based, and experimentalist approaches with mandated evaluations, transparency, and adaptive reviews.

d) Proposed mix for gen-AI + UGC video health search:  
- Baseline performance standards (safety, transparency, disclaimers); risk-based oversight of high-risk modules; sandbox entry for novel features; co-regulatory codes for moderation + audits; periodic sunset/renewal tied to outcomes (harm rates, complaint resolution times, bias metrics, uptake in underserved groups). Trade-offs addressed via independent audits, public dashboards, and user appeals.

---

## Q2 — Module 2: EHDS Secondary Use Scenario (20 pts)

Conclusion (required):  
- Project 1 (oncology triage): Yes, subject to conditions.  
- Project 2 (insurance risk pricing): Mostly No; likely prohibited/limited purpose, with narrow Uncertain elements depending on national regimes and safeguards.

### Mark scheme

| Part | Pts | Criteria |
|-----:|---:|---------|
| a    | 8  | Correct category mapping (EHRs; registries; biobank/genomic; medical device RWD; insurance claims; surveys). Reasoned availability for secondary use aligned to EHDS aims (research, innovation, public health) and typical exclusions (marketing/advertising; decisions detrimental to individuals), with safeguards (anonymization, permits). |
| b    | 4  | Clear assessment that health-research/innovation uses like triage model training are within permitted secondary uses with strict conditions; insurance pricing uses are generally excluded/restricted; articulate rationale. |
| c    | 4  | Specific permit conditions: anonymization/pseudonymization thresholds; secure processing environments; access body permit; purpose limitation; output controls; IP/know-how and confidential data handling; international transfer constraints. |
| d    | 4  | Crisp Yes/No/Uncertain grid for each dataset × project with one-sentence justifications. |

### Model answer (outline)

a) Category mapping and availability:  
- Hospital EHR extracts → “EHR data”/clinical data (Art. 51 category): generally available for secondary use for research/innovation with anonymization or safeguarded processing; exclude direct marketing/insurance pricing.  
- Cancer registry → “Registries”/public health datasets: strong case for availability for research/public health; strict controls.  
- Genomic panels linked to cohorts → “Biobank/genomic data”: available for research with high safeguards; re-identification risk → controlled access, possibly pseudonymized in secure processing environments.  
- CE-marked device RWD → “Medical device data/real-world data”: generally available for research/innovation; guard trade secrets; device safety concerns imply conditions.  
- Insurance claims → “Administrative/claims data”: research/public health yes under safeguards; insurance pricing uses No (misuse risk, discrimination).  
- Patient surveys (de-identified) → “Patient-reported outcomes/experience”: available for research; validate de-identification.

b) Project 1: permitted with conditions (research/innovation improving care; use in secure environment; no individual-level decisions without clinical validation; no attempt re-identification).  
Project 2: generally not permitted—pricing/underwriting for insurers is not a recognized permitted secondary use and conflicts with anti-discrimination/safeguards; even aggregated outputs risk detrimental re-use.

c) Conditions:  
- Data permit from access body; purpose limitation; anonymization where feasible, else pseudonymization + secure processing enclaves; disclosure controls; DPIA; IP/trade secrets protection clauses; output vetting; non-transfer, no re-identification, no downstream marketing/insurance uses; EU hosting or controlled transfers.

d) Dataset × project grid (example):
- EHRs → P1: Yes (conditions); P2: No (pricing).  
- Registries → P1: Yes (conditions); P2: No.  
- Genomics → P1: Yes (tight controls); P2: No.  
- Device RWD → P1: Yes (conditions; trade secrets guarded); P2: Uncertain→No (likely No).  
- Claims → P1: Yes (research context only); P2: No.  
- Surveys → P1: Yes; P2: No.

---

## Q3 — Module 3: Competition Law (Arts. 101 & 102 TFEU) (20 pts)

Conclusion (required):  
- Dominance: Likely Yes in one or more relevant platform markets.  
- Infringements: Article 101 concerns for exclusivity/MFN; Article 102 concerns for tying and potentially refusal to supply (depending on essential facilities test and justifications).

### Mark scheme

| Part | Pts | Criteria |
|-----:|---:|---------|
| a    | 5  | Proper market definition: product (platform intermediation for hospital-device distribution; scheduling APIs; analytics); geographic (EU-wide or national with cross-border trade). Dominance assessment: shares, barriers (network effects, switching costs, data, certification), buyer power, expansion barriers. |
| b    | 6  | Art. 101: Agreement between undertakings; object/effect analysis for exclusivity and MFN; appreciability; inter-brand foreclosure; platform multi-sided considerations; 101(3) efficiencies (quality assurance, investment) and indispensability. |
| c    | 6  | Art. 102: Tying/bundling tests (coercion, separate products, foreclosure effects, objective justification); refusal to supply/API access (indispensability, elimination of competition, new product test; security justification scrutiny). |
| d    | 3  | Clear final stance on “monopolies” and infringements; proportionate remedies (cease exclusivity/MFN, FRAND API access, interoperability obligations, compliance monitoring). |

### Model answer (outline)

a) Markets: separate but related—(1) hospital app distribution to certified device makers; (2) hospital scheduling API access; (3) analytics dashboards for providers. Geographic: EU or EEA with cross-border effects. Dominance: high market shares, strong network effects (two-sided platform), data scale, certification moat, switching and multi-homing frictions → likely dominance in at least APIs and app distribution.

b) Article 101:  
- Exclusive dealing + rebates: risk of foreclosure of rivals (ClinLink) from key device partners; likely restriction by effect (possibly by object if de facto exclusivity).  
- MFN: may dampen price competition across platforms; risk of softening competition; appreciable effect across Member States.  
- 101(3) rebuttals: claimed efficiencies (quality/security); must be indispensable, fair pass-on, no elimination of competition → difficult if less restrictive measures exist.

c) Article 102:  
- Tying scheduling API to analytics: separate products? If customers want API without analytics, coercion suggests abusive tying; foreclosure effects likely given dominance. Objective justification (integration benefits) assessed for proportionality.  
- Refusal to supply/API: essential facilities doctrine triggers if API access indispensable for effective competition, refusal likely to eliminate competition, and no objective justification. Security/integrity reasons must be concrete and proportionate; FRAND-like access may be required.

d) Remedies: cease exclusivity/MFN; unbundle; provide FRAND API access; monitoring trustee; conduct commitments; potential structural remedies if necessary.

---

## Q4 — Module 4: Database Qualification and Protection (20 pts)

Conclusion (required):  
- Database: Yes.  
- Copyright: Likely Yes if selection/arrangement reflects author’s own intellectual creation.  
- Sui generis: Likely Yes (substantial investment).  
- Infringement: Likely Yes under sui generis (substantial extraction/re-utilization) and possibly copyright; ToS breach adds a contract claim.

### Mark scheme

| Part | Pts | Criteria |
|-----:|---:|---------|
| a    | 4  | Applies Directive 96/9/EC definition: independent materials, systematic/ methodical arrangement, individual accessibility. Distinguishes raw data vs database structure. |
| b    | 5  | Explains originality threshold (author’s own intellectual creation) in selection/arrangement; what is protected (structure, schema, index) vs unprotected facts; identifies creative choices (harmonized schema, quality scoring). |
| c    | 6  | Substantial investment (collecting, verifying, presenting); qualitative and quantitative aspects; “extraction” and “re-utilization”; repeated/systematic extraction equating to substantial part. |
| d    | 5  | Applies rights to GreenPulse’s scraping; exceptions (lawful user; insubstantial parts); TDM exception’s limited role; ToS enforceability. Clear Yes/No/Uncertain conclusion with rationale. |

### Model answer (outline)

a) Database: Independent items (sensor readings, imagery tiles, plot metadata); systematically arranged (geohash index, harmonized schema); individually accessible (search and bundles) → qualifies.

b) Copyright: Protects original selection/arrangement (schema design, quality scoring, index logic), not facts. If choices reflect free and creative decisions beyond technical constraints, originality met.

c) Sui generis: Substantial investments in data acquisition (farmer onboarding), verification (manual QA), and presentation (harmonization). GreenPulse scraped over months to reconstruct bundles → substantial extraction/re-utilization; or repeated/systematic extraction of insubstantial parts amounting to substantial whole.

d) Infringement/defenses: Likely infringement of sui generis; possible copyright infringement of structure if replicated. Lawful user exception unlikely for wholesale scraping; TDM exceptions (from DSM Directive) don’t generally license re-use of protected database contents at scale, and do not override sui generis extraction prohibitions for commercial re-use without conditions. ToS breach supports contractual claim. Conclusion: Yes (infringement likely).

---

## Q5 — Module 5: Scraping, Anonymization, AI Act, Bias & Public Data Re-use (20 pts)

Conclusion (required):  
- Proceed only with tightened conditions: Scraping of open portals under compliant licenses is broadly OK; social media scraping risky (ToS, IP, data protection); CCTV face data not “anonymous” by default; likely high-risk or GPAI obligations under AI Act; significant bias/fairness governance required.

### Mark scheme

| Part | Pts | Criteria |
|-----:|---:|---------|
| a    | 5  | Distinguishes public-sector open data vs protected databases; reads license/ToS; considers sui generis rights, anti-scraping clauses, technical access restrictions; identifies lawful vs unlawful scraping patterns. |
| b    | 5  | Explains anonymization vs pseudonymization; identifiability and linkage risk; DPIA; purpose limitation; appropriate safeguards (suppression, generalization, synthetic data, DP). |
| c    | 5  | Correct AI Act classification for city-safety scoring (likely high-risk if used for access to services/housing/security decisions; or GPAI for underlying models); obligations: data governance, risk management, documentation, logging, transparency, human oversight, robustness, post-market monitoring. Flags prohibited uses if applicable. |
| d    | 5  | Identifies bias types (sampling, measurement, label, historical/representational); applies FanFAIR-style fairness principles; proposes concrete mitigations (audits, diverse sampling, de-biasing, impact assessments, appeals); clear conditional “go/no-go” with controls. |

### Model answer (outline)

a) Scraping:  
- Municipal open-data portals under open licenses (e.g., CC BY, ODbL) → lawful if license terms followed (attribution, share-alike); check technical measures and access policies.  
- PSI/Open Data Directive facilitates re-use of public-sector info but does not override IP/DB rights not held by public body.  
- Social media: ToS often restrict scraping; copyright in user content; database and anti-circumvention concerns; high data protection risk → likely unlawful without permission.  
- Database rights: avoid substantial extraction from protected databases unless license permits.

b) Anonymization:  
- Social media and CCTV are rarely anonymous by default; faces, context, geotags enable re-identification.  
- Use robust anonymization (k-anonymity with l-diversity/t-closeness at minimum) or differential privacy; remove direct/indirect identifiers; limit resolution and temporal granularity; implement secure enclaves; conduct DPIA; purpose limitation and data minimization.

c) AI Act:  
- City-safety scoring used by landlords/security may be high-risk (impacts access to housing/services); underlying model may be GPAI if general-purpose.  
- Obligations: risk management, data governance (representative, free of errors where possible), technical documentation, logs, transparency and human oversight, accuracy/robustness/cybersecurity, post-market monitoring; potential conformity assessment.  
- Prohibited practices: real-time remote biometric identification by law enforcement is restricted; private deployment still triggers strict rules for biometric categorization/identification.

d) Bias & fairness:  
- Biases: sampling (over/under-representation of neighbourhoods), measurement (proxy crime signals), label (noisy reports), historical (over-policing), representational (stigmatizing tags).  
- FanFAIR-style mitigations: document provenance; fairness metrics selection; stakeholder review; diverse sampling; counterfactual evaluation; periodic audits; appeal/correction mechanisms; publish model cards/datasheets; clear allowed use policy; enforceable contractual constraints on clients.  
- Conclusion: Uncertain→Yes only with strong license compliance, DP-grade anonymization, restricted uses, high-risk obligations met, independent audits, and governance gates.

---