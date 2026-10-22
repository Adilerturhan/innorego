Module 4 - IP and Data: Regulation of Data Re-usability
The development of Artificial Intelligence (AI) relies heavily on data mining (DM), which is an algorithm-based technology requiring tremendous quantities of data for proper training through machine learning techniques [1-3]. Data mining (or text and data mining, TDM) is defined as any automated analytical technique aimed at analyzing text and data in digital form to generate information like patterns, trends, and correlations [4, 5].
The challenge lies in the fact that while data itself is generally not owned and can be freely re-used, IP laws governing the collection and organization of data into databases can significantly limit this re-usability [6, 7].
I. Legal Frameworks Protecting Databases
The EU Database Directive (DD) provides two distinct regimes for database protection: copyright and the sui generis right [8, 9]. A database is defined as ‘a collection of independent works, data or other materials arranged in a systematic or methodical way and individually accessible by electronic or other means’ [6, 10].
1. Copyright Protection (DD, Art. 3)
Copyright protection extends only to the structure of the database [8].
• Criterion: Protection is triggered if the database is the author’s ‘own intellectual creation’ (AOIC standard of originality) by reason of the selection or arrangement of its contents [11, 12].
• Threshold: This standard requires the author to have made free and creative choices that leave their personal stamp [13, 14].
• Limitation: If the selection or arrangement is dictated by ‘technical considerations, rules or constraints’ (such as following a standard industry format or a logical/alphabetical order), copyright protection does not arise [13-15].
• Impact: Since most digital databases tend to be comprehensive rather than selective, and their structure often follows a logical order to facilitate use, many databases are effectively deprived of copyright protection [13, 16].
2. Sui Generis Protection (DD, Art. 7)
The sui generis right protects the contents of the database considered in whole or in substantial parts [8].
• Criterion: Protection is triggered by a ‘substantial investment’ (measured quantitatively and/or qualitatively) made in obtaining, verifying or presenting the database contents [17-19]. The investment can be financial, material, or human (time, effort, skill, know-how) [17, 19].
• Threshold: The threshold for substantial investment is arguably low [20-22]. Given this low threshold, a significant amount of databases are afforded sui generis protection, which negatively impacts data re-usability [22].
• Duration: Protection lasts 15 years, but this term is renewable with every substantial change, leading potentially to permanent protection (a ‘rolling’ sui generis right) [23-26].
• Scope of Investment: The investment must be in gathering existing materials (obtaining) or monitoring accuracy (verification), but not in the creation of the data itself (excluding ‘spin-off databases’) [20, 27, 28].
II. IP Rights as Barriers to Data Mining
The development of AI through data mining often involves activities that infringe on these established IP rights [29, 30].
1. Copyright Infringement: During the preparation stage of data mining (copying and loading data into a dataset), the database might be copied, including its original structure, amounting to an unauthorized reproduction [31, 32].
2. Sui Generis Infringement: Data mining activities often involve the transfer of a substantial part (if not the entirety) of the contents, amounting to an unauthorized extraction [33-35]. Furthermore, the Database Directive bans the repeated and systematic extraction of insubstantial parts when such acts conflict with the normal exploitation of the database, a prohibition that is highly relevant to algorithmic mining activities [30, 35, 36].
III. TDM Exceptions under the DSM Directive (2019)
To overcome legal uncertainties and adapt copyright rules to new digital uses like TDM, the DSM Directive introduced two mandatory exceptions to copyright and the sui generis right [37-39].
1. Article 3: Scientific Research Exception
This exception facilitates reproductions and extractions for TDM carried out on lawfully accessed subject matter for the purposes of scientific research [40, 41].
• Beneficiaries: It is strictly limited to Research Organizations and Cultural Heritage Institutions [40, 42, 43].
• Limitation: It is not applicable if a commercial undertaking has a decisive influence and would enjoy the results of the research on a preferential basis [42-45]. This is criticized for potentially impeding the emergence of new applications in the private sector, as start-ups and SMEs may not qualify as beneficiaries [42, 46].
• Contractual Status: This exception is mandatory for Member States and is unwaivable by contract (rightholders cannot limit its application via restrictive clauses) [40, 47-49].
2. Article 4: General TDM Exception
This exception aims to encourage private sector innovation [39, 50].
• Beneficiaries: It is open to any person who lawfully accesses the database, including start-ups and SMEs, for TDM purposes [51-53]. The purpose of developing AI clearly qualifies under this exception [51].
• Crucial Limitation (Opt-Out): Rightholders have the possibility to expressly reserve the use of the subject matter [54]. This is done by opting out in an appropriate manner, such as using machine-readable means (e.g., metadata or terms/conditions) for content publicly available online [52, 55, 56].
• Impact: Because rightholders can opt out, the exception's application is left to their discretion [56, 57]. This severely limits the freedom of for-profit miners in the EU, placing them at a competitive disadvantage compared to jurisdictions (like the US) where TDM is considered fair use, even for profit [58].
• Storage: Unlike Article 3, Article 4 only permits the retention of reproductions and extractions for the duration necessary for the TDM purposes, not long-term storage [52, 59].
IV. Contractual Barriers and Unprotected Data
Beyond IP law, data re-usability is significantly hampered by contractual limitations [60, 61].
The Ryanair Ltd v PR Aviation BV case [62, 63] established a critical point regarding databases that fail to meet the standards for IP protection (i.e., they are unprotected by both copyright and the sui generis right) [64-66].
• Contractual Freedom Prevails: The Court of Justice of the European Union (CJEU) held that if a database is unprotected by the DD, the Directive’s provisions—including the mandatory rights of lawful users to extract insubstantial parts (Art. 6(1) and Art. 8 in conjunction with Art. 15 DD)—are not applicable [64-69].
• Private Legislation: This means that the data holder is not precluded from laying down contractual limitations on the use of such a database, enabling them to essentially retrieve unprotected databases from the public domain and afford them protection through contract [65, 66, 70, 71].
• Impact on Innovation: This leads to "rent-seeking behaviour" where highly restrictive contractual terms reduce the possibility of data re-use for start-ups and SMEs, contributing to legal uncertainty as enforceability varies across Member States [27, 60, 61, 72]. The contractual protection of unprotected databases poses a significant obstacle to developing AI [27, 61].
V. Recommendations for a More Balanced Framework
The sources argue that the existing database framework is outdated and fails to strike a proper balance between the rights of database makers and the right to freedom of information, hindering innovation [62, 73, 74].
Recommendations for improvement include:
1. Reversing Contractual Limitations: The introduction of an unwaivable right to re-use non-personal data contained in databases that have been disclosed (i.e., unprotected databases) is recommended to address the negative impact of the Ryanair judgment and restore the integrity of the public domain [71, 75, 76].
2. Reforming the Sui Generis Right: Since the sui generis right is arguably easy to attain and its permanent protection is seen as highly problematic [77, 78], solutions include modifying it (e.g., mandatory registration and a hard limit on renewal terms) or its complete abolition [67, 79-81].
3. Extending TDM Exceptions: Modifying Article 4 of the DSM Directive to remove the opt-out clause for sui generis right holders, making the general TDM exception unwaivable for those databases [82, 83].
4. Data Sharing Initiatives: While the Open Data Directive is promising for public sector data (mandating the availability of high-value datasets under non-discriminatory conditions) [84, 85], the approach to private sector (B2B) data sharing is modest, relying only on non-binding guidance that promotes contractual freedom without tackling restrictive clauses [85-87]. Further research into legally binding data access rights is suggested to address undisclosed, "locked" data [74, 88].