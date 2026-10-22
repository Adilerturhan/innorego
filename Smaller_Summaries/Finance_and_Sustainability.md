Module 6 - Financial and Sustainability Data: Data Quality and Testability
The regulation of modern data-driven fields, particularly finance and sustainability, faces a deeper problem than simply unreliable data: testability is uneven [1]. Testability is defined as the cost and credibility of a decisive check an outsider can run to prove a reported number right or wrong [1].
I. The Core Challenge: Data Quality from Sociological and Economic Perspectives
Data quality is a persistent problem in finance, relating to data being unavailable, incomplete, or provided in formats that are not useful (the 'fit-for-purpose' definition) [2, 3]. Both sociological and economic perspectives highlight why data quality is difficult to achieve and regulate [4].
A. Sociological Perspective
From a sociological perspective, numbers [4]:
• Classify and legitimize (Bowker & Star; Porter) [5].
• Create audit cultures (Power) [5].
• Perform the realities they are meant to measure (Espeland & Stevens) [5].
• Involve five dimensions of quantification: Work, Reactivity, Discipline, Authority, and Aesthetics [6].
B. Economic Perspective
From an economic perspective, the costs associated with data are key [5, 7]:
• Costs of measurement and verification shape how markets, contracts, and organizations are structured (Barzel) [5, 7]. Since measurement is costly, people only trade when they believe they know what they are getting, but measuring quality or quantity is never free [7].
• Hard-to-measure outputs distort incentives, encouraging mimicry instead of substance (Holmström & Milgrom) [5].
• Only verifiable obligations can be contracted and enforced (Hart & Moore) [5].
• Economic organization evolves to manage these measurement costs (e.g., vertical integration) [7].
Conclusion on Design: If numbers are intended to reflect reality, the design of the governance regime must maximize verification [7]. The core claim is that modern disclosure and reporting regimes are incomplete because testability is uneven [1].
II. Testability Attributes and Verification Rights
Testability can be broken down into three key attributes applicable to any data regime [8, 9]:
1. Evidentiary anchoring: What evidence ties the claim to reality? This means connection to recognized, checkable proofs (audit trails, observations, documents) [8, 9].
2. Access symmetry: Who can run the test? This refers to the equal ability for insiders, regulators, and third parties to observe or reproduce evidence [9, 10].
3. Identifiability: What exactly is being tested? This requires a stable linkage between a number and its referent entity, event, or process [10, 11].
The source material maps different regulatory approaches based on the cost of verification and the distribution of verification rights [6]:
Verification Rights Distribution
Low Cost of Verification (High Quality)
High Cost of Verification (Low Quality)
Distributed
Open testability
rightarrow High data quality (e.g., open science, transparent audits) [6]
Fragile openness
rightarrow Improvements, but privacy or cost limits quality [6]
Centralized
Regulated accuracy
rightarrow Quality depends on oversight (e.g., central bank stress tests) [6]
Low-quality equilibrium
rightarrow Formal compliance, low recomputability (e.g., ESG, audit monopolies) [6]
III. Case Study 1: Financial Data (Open Finance)
The goal of Open Finance is to promote the free flow of data about mortgages, loans, investments, pensions, and insurance [12]. This is intended to be achieved through data access, sharing, portability, and interoperability, often facilitated by APIs (Application Programming Interfaces) [10, 13]. Open Finance should, in principle, make personal financial data reliable because banks are regulated, APIs are standardized, and access is secured [14].
A. The Data Quality and Testability Problem in Open Finance
Despite the regulatory efforts (like PSD2 and the proposed FDAR), the Open Finance ecosystem remains fragile because its accuracy and completeness are difficult to test in practice [9].
1. Interoperability Challenges: PSD2 encouraged the use of APIs but did not prescribe standards for them, creating interoperability challenges for FinTechs [15, 16]. Different banks structure their transaction data APIs in subtly different ways, making it tremendously challenging and costly for Third-Party Providers (TPPs) to plug in and process data for services like AI [17-19].
2. Regulatory Gaps in FDAR: The proposed Financial Data Access Regulation (FDAR) largely neglects the question of data quality and how it can be assured in the European Financial Data Space (EFDS) [12, 20, 21]. FDAR currently only requires the data holder to make data available "at least in the same quality available to the data holder" [22]. This allows for the reproduction of low-quality data [22].
3. Lack of Cheap, Decisive Tests: Regulators often act as if Open Finance data mirrors the underlying books, but they rarely require cheap, decisive tests [23]. PSD2 mandates API availability but not independent audit access to confirm that API outputs match internal records [23].
4. Application of Testability Attributes in Open Finance:
Attribute
Open Finance Instantiation
Why it Matters
Source(s)
Evidentiary anchoring
Provenance metadata, on-ledger audit trails linking shared API data to original bank records [11].
Ensures API outputs mirror actual account data rather than internal aggregates [11].
[11]
Access symmetry
Regulator and authorized third-party APIs that allow the same queries banks use internally [23].
Prevents one-sided transparency where firms can “see” but others cannot verify [23].
[23]
Identifiability
Stable identifiers (IBANs, LEIs, customer IDs, timestamped transaction hashes) across providers [23].
Allows data from different sources to be matched and checked against each other [23].
[23]
B. Data Quality and AI in Finance
AI systems require high-quality, complete, and accurate training and testing data [21, 24]. The tension between the push for Open Finance (data availability) and the data quality problem is increasing, especially as high-risk AI systems (like creditworthiness assessment tools) are regulated by the AI Act [25-27].
• AI Act Requirements: Article 10 of the AI Act requires training, validation, and testing data sets for high-risk AI systems to be relevant, sufficiently representative, free of errors, and complete [28]. These standards embrace the 'fit-for-purpose' conception of data quality [26].
• Incentive Problem: Banks, which hold the data, have weak incentives to invest in the quality of the data they share, as they often compete with FinTech challengers [29, 30].
• Regulatory Recommendation: To address this, the Commission should develop a conceptual framework for data quality, possibly based on the BCBS Principles for effective risk data aggregation, and implement organizational requirements [31, 32].
IV. Case Study 2: Sustainability Data (Carbon Offsets)
The carbon offset market involves permission to emit 1 ton of
textCO_2 if an equivalent ton is "saved" elsewhere [33]. This regime raises a profound data quality dilemma because the key metric—the counterfactual baseline (emissions that would have happened)—is unobservable [33-35]. This results in deep epistemic uncertainty [33].
A. The Standardized Approach and Over-Crediting Risk
California’s cap-and-trade program relies heavily on offsets, meaning the environmental effectiveness of the program depends on the quality of the carbon offset program [36]. Following criticism of earlier project-by-project approaches (like the CDM), California pioneered a "standardized approach," which shifts the focus of quality control from individual project assessments to the protocol level [37, 38].
However, large uncertainties persist in protocol-level assessments of additionality, baselines, and perverse incentives [39]. Over-crediting occurs when the credits generated exceed the actual effect of the protocol on emissions [40]. The three principal sources of over-crediting observed historically (CDM) and addressed by California's protocols are:
1. Non-additional projects: Projects that would have happened regardless of offset credits [34, 41].
2. Inflated counterfactual baseline scenarios: Overestimating the emissions that would occur without the offset incentive [34, 35].
3. Perverse incentives: Incentives that inadvertently increase emissions elsewhere [34, 42].
B. Challenges in Assessing Additionality and Baselines (Testability Problems)
1. Additionality (Non-additional Projects): The requirement is that reductions must be "in addition to... any other greenhouse gas emission reduction that otherwise would occur" [41].
• Common Practice Assessment Flaws: California operationalizes additionality using a 'common practice' assessment [43]. An early approach to assessing methane capture at abandoned coal mines focused on the number of mines (6% capturing methane) rather than the quantity of emissions (33% of feasible capture already occurring) [44, 45]. This approach risked generating a large proportion of credits from non-additional activities [44].
• High Uncertainty: Even with improved resolution (e.g., excluding mines that captured methane when active), the risk of substantial over-crediting remains [46]. The uncertainty in business-as-usual development is so large that the share of credits from non-additional projects could range from 0 to 100% [47].
2. Baseline Emissions (Inflated Baselines): The baseline scenario never occurs, making it inherently deeply uncertain [35].
• Scientific Uncertainty: In Mine Methane Capture (MMC), the protocol estimates baseline emissions using a model, but project developers’ input choices can lead to over-crediting [35]. Where default parameters are used, ARB applies a discount factor (e.g., 20%) to account for uncertainty, reflecting a subjective expert judgment [48].
• Behavioural Uncertainty: In Rice Cultivation, baselines are defined by either a common practice model (Mid-South) or a farmer's reported past practices (California) [49]. The latter is vulnerable to over-crediting if farmers exaggerate past emissions to earn more credits [50]. The standardized approach, while reducing information asymmetry, increases the risk of adverse selection [51].
C. Perverse Incentives (Low-Quality Equilibrium)
Offset protocols can create financial incentives that undermine the goal of reducing emissions:
• Extending High-Emitting Activities: Offset profits (e.g., from MMC protocol credits) can increase the profitability of coal mining, potentially extending the lives of uncompetitive coal mines and leading to increased emissions from burning the additional coal [42, 52].
• Inducing Crop Switching: In agriculture, providing revenue to rice farmers could shift production from corn to rice. Since rice production is about four times more emissions-intensive than corn, this shift weakens the emission benefits of the protocol [53].
• Weakening Climate Regulation (Political Economy): Offsets create an incentive for those benefiting from offset projects to advocate against legally binding regulations because activities required by law are ineligible for offset credits [54]. The MMC Protocol may have contributed to the Bureau of Land Management's decision not to regulate methane emissions from coal mines on federal lands [55].
• Accidentally Increasing Emissions: To avoid non-additional crediting, the MMC Protocol excludes pipeline injection (considered common practice) while allowing flaring [56]. This creates a perverse incentive for mine owners to flare captured methane for offset credits—even if productive use as fuel would otherwise be economic—potentially increasing overall emissions [57, 58].
D. Conclusion on Sustainability Data Regulation
The sources conclude that due to deep and pervasive uncertainty, using offsets risks lessening total emission reductions and increases uncertainty in whether a climate policy goal has been achieved [59]. Regulators should prioritize:
1. Explicit Quantitative Analysis: Periodically review the expected balance of over- and under-crediting [60].
2. Conservative Estimates: Deliberately reduce the estimated credits by an amount that compensates for anticipated non-additional projects [46, 60].
3. Risk Exclusion: Exclude project types where uncertainty overwhelms emission reduction estimates or where there is a high risk of substantial perverse incentives [61].
It may be more accurate to view offsets not as accurately quantified tons of emissions reductions, but as government-intermediated incentive programmes in which regulated emitters invest, resulting in difficult-to-estimate reductions [62, 63].