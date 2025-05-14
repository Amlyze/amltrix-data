# Minimal Mitigations Extract

## Access Authentication & Monitoring
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Tactical
- **Code:** M0008
- **Description:** A combined procedural and technological measure that employs multi-factor authentication to robustly verify user identity and continuously supervises real-time access to financial institution systems. By incorporating two or more independent authentication factors (for example, passwords plus device-based or biometric credentials), it ensures strong identity verification and reduces the risk of unauthorized access. Concurrently, it monitors user sessions to identify suspicious usage patterns or privilege misuse, providing early warning of potential insider threats or external breaches. This measure underpins AML/CFT defenses by safeguarding critical investigative data and maintaining the integrity of monitoring processes. In practice, it enhances security culture, ensures adherence to regulatory obligations, and helps thwart the misuse of internal platforms for money laundering or terrorist financing.
- **Short Description:** Implement multi-factor authentication and real-time access monitoring to proactively detect and prevent unauthorized use, insider threats, and fraud, thereby enhancing AML/CFT compliance. This approach strengthens identity verification protocols and provides continuous oversight of user actions within financial systems.

### Lifecycle Stages

- **Ongoing Relationship** – Constant session monitoring.
- **Post Alert** – If suspicious logins occur, you might strengthen authentication or investigate.
- **Onboarding** – Setting up multi-factor authentication for new clients or new employees.
- **Ad Hoc Interaction** – If a non-regular user needs certain system access.

---

## Blockchain Monitoring
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0011
- **Description:** Blockchain Monitoring is a specialized technology-based control that financial institutions integrate into their AML/CFT frameworks to detect, investigate, and disrupt illicit activities in cryptocurrencies and digital wallets. By applying advanced analytics and chain analysis, it traces fund flows, identifies abnormal or suspicious transaction patterns, and illuminates connections among blockchain entities. This increased transparency enables the filing of suspicious transaction reports, targeted asset freezing, and focused investigations against threats such as layering, ransomware-related flows, and cross-border transfers exploiting the pseudonymous nature of digital assets. Integrated into existing compliance workflows, Blockchain Monitoring significantly strengthens an institution’s capability to safeguard against the misuse of cryptocurrency services and enhance overall AML/CFT controls.
- **Short Description:** Blockchain Monitoring leverages specialized analytics and software to continuously track and analyze cryptocurrency transactions, enabling the identification of suspicious activity patterns, tracing of illicit fund flows, and prompt detection of potential money laundering and fraud.

### Lifecycle Stages

- **Ongoing Relationship** – Continuously track wallet addresses.
- **Post Alert** – Investigate suspicious blockchain flows.
- **Onboarding** – If a customer uses crypto from the start, monitoring might begin at or shortly after onboarding.

---

## Cash Transaction Reporting (CTR)
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0007
- **Description:** Cash Transaction Reporting (CTR) is a procedural AML control that obliges financial institutions (FIs) to identify and report large or threshold-based cash transactions to relevant authorities. By requiring timely disclosures of significant in-branch or electronic cash movements, CTR creates a reliable audit trail and strengthens FIs’ ability to detect and disrupt criminal strategies involving bulk cash, structuring, or rapid layering. Within an FI’s operating environment, staff or automated systems track cash inflows and outflows, flag those above the set reporting threshold, and then submit CTRs. This process improves transparency, helps investigators map illicit fund flows, and deters criminals by making it more difficult to conceal high-value or repetitive cash activity.
- **Short Description:** Cash Transaction Reporting (CTR) mandates that financial institutions document and disclose large or threshold-based cash transactions to authorities, providing an audit trail that helps identify and investigate suspicious cash flows. This systematic reporting strengthens AML defenses by ensuring heightened visibility and accountability for high-value cash movements.

### Lifecycle Stages

- **Onboarding** – Large initial deposits could trigger CTR obligations from day one.
- **Ad Hoc Interaction** – If there is an unusual one-off cash deposit from a non-client or an occasional relationship.
- **Ongoing Relationship** – The core scenario, as customers conduct regular cash transactions.

---

## Client Relationship Termination
- **Functional Category:** Relationship Actions
- **Application Level:** Tactical
- **Code:** M0029
- **Description:** Client Relationship Termination is a procedural measure used by financial institutions (FIs) to end all formal dealings with a customer after confirming that the customer’s money laundering or terrorist financing risks cannot be managed within acceptable thresholds. Its primary AML/CFT purpose is to remove any remaining channels for illicit fund placement or layering that might persist when enhanced due diligence, ongoing monitoring, or other remedial actions fail to mitigate high risks. In practice, this control is typically enacted after repeated or escalating attempts—such as requesting additional information—remain unfulfilled or the customer’s overall risk profile becomes unmanageable. By ceasing the relationship, the FI both disrupts criminal misuse of its services and protects itself from further reputational or regulatory harm. Thorough internal review and senior management escalation generally precede the decision, ensuring that termination is applied only after other safeguards prove insufficient or the client remains non-responsive to key AML/CFT requirements.
- **Short Description:** Client Relationship Termination is the final AML safeguard invoked when a customer's money laundering or terrorist financing risks remain unmanageable despite enhanced due diligence, prompting institutions to close all accounts and sever ties. This decisive step mitigates further exposure, protecting against regulatory and reputational harm.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – “Refusal to onboard” is effectively early termination of the prospective relationship.
- **Onboarding** – If high risk is discovered mid-process.
- **Ongoing Relationship** – If the client’s behavior is too suspicious or unmanageable.
- **Post Alert** – If the client’s behavior is too suspicious or unmanageable.

---

## Country Risk Assessment
- **Functional Category:** Risk Management & Governance
- **Application Level:** Tactical
- **Code:** M0001
- **Description:** A structured procedural measure where financial institutions systematically categorize and assign risk ratings to jurisdictions based on corruption levels, regulatory robustness, sanctions status, and other relevant indicators. This enables targeted allocation of compliance resources and intensified due diligence for higher-risk geographies. By adjusting scrutiny and monitoring according to country risk ratings, FIs improve their ability to detect suspicious activities, mitigate potential misuse of services by criminals, and align with a risk-based approach for AML/CFT compliance.
- **Short Description:** Financial institutions employ country risk assessments to systematically categorize jurisdictions based on corruption levels, regulatory gaps, and sanctions exposure. These findings drive targeted AML/CFT controls such as heightened monitoring, enhanced due diligence, service restrictions, and other tailored risk-based measures.

### Lifecycle Stages

- **Onboarding** – Check the customer’s principal jurisdictions during initial setup.
- **Ad Hoc Interaction** – A one-off transaction with a high-risk country.
- **Ongoing Relationship** – Re-check as countries’ statuses change, or if a client expands into new regions.

---

## Customer Due Diligence (CDD)
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0003
- **Description:** Customer Due Diligence (CDD) is a core procedural control requiring financial institutions to identify and verify key details about their customers (including beneficial owners) at the outset of a business relationship and on an ongoing basis. By collecting and verifying personal and corporate information (for example, via official documents, digital identity checks, or biometric methods), CDD prevents anonymous or misrepresented account usage and clarifies who truly owns or controls an account or legal entity. This transparency underpins effective AML/CFT measures by enabling enhanced transaction monitoring, detection of unusual or suspicious activity, and targeted risk management. CDD’s practical relevance lies in its requirement for financial institutions to maintain accurate, up-to-date customer data so they can promptly spot red flags (such as atypical transactions or changes in ownership), fulfill mandatory reporting obligations, and conduct timely investigations when necessary. As a result, CDD provides a foundational layer that helps ensure compliance, safeguards institutional reputations, and diminishes opportunities for illicit abuse of financial products and services.
- **Short Description:** Financial institutions systematically gather, verify, and keep customer information current—covering both direct customers and beneficial owners—to reduce anonymity and fraud risks. This robust approach underpins effective ongoing monitoring of suspicious or unusual transactions, forming a core preventive AML measure.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – Basic screening (e.g., PEP, sanctions) can happen before fully onboarding.
- **Onboarding** – Formal CDD is required by regulation at account opening.
- **Ongoing Relationship** – Periodic refresh and updates to keep data accurate.

---

## Customer Education and Awareness
- **Functional Category:** People & Awareness
- **Application Level:** Tactical
- **Code:** M0016
- **Description:** Customer Education and Awareness is a procedural and organizational control designed to prevent and detect money laundering (ML), terrorist financing (TF), and other financial crimes by informing and empowering customers. In practice, financial institutions provide clear, targeted messaging through campaigns, advisories, onboarding materials, and ongoing communications, teaching customers how to spot suspicious red flags and protect their accounts. By equipping customers with practical guidance—such as fraud avoidance tips, indicators of trade-based money laundering, and reporting channels—FIs strengthen overall AML/CFT outcomes. This control increases vigilance among legitimate clients, widens the institution’s protective footprint, and supports investigative efforts when abnormalities arise. Concrete measures can include community workshops, digital bulletins, in-app security prompts, or tailored outreach for vulnerable segments. By embedding customer-facing education in AML/CFT frameworks, FIs reinforce responsible behavior, enhance transparency, and help minimize illicit exploitation of products or services.
- **Short Description:** By informing customers about financial crime risks, safe transaction practices, and the importance of regulated channels, institutions foster greater vigilance and reduce vulnerability to fraud. Through clear onboarding materials, outreach campaigns, and advisory guidance, customers gain the knowledge needed to protect themselves from illicit schemes and uphold AML/CFT compliance.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – The FI might provide guidance about safe usage.
- **Onboarding** – Education about recognized red flags, disclaimers, and user responsibilities.
- **Ongoing Relationship** – Periodic warnings or updates (e.g., scam alerts).

---

## Data Protection and Security Controls
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Tactical
- **Code:** M0027
- **Description:** Data Protection and Security Controls are technological and procedural measures designed to protect the confidentiality, integrity, and availability of AML-critical data. By encrypting sensitive information, enforcing strict access controls, securing storage solutions, and conducting periodic security audits, financial institutions ensure only authorized personnel can handle or modify AML data. This safeguards critical information from breaches, tampering, or unauthorized disclosure, thereby supporting accurate transaction monitoring, due diligence, and investigations. Through these controls, institutions maintain data reliability, strengthen AML/CFT efforts, and uphold compliance obligations, reducing opportunities for criminals to exploit compromised or manipulated information.
- **Short Description:** Data Protection and Security Controls establish a robust framework of technical and procedural safeguards—such as data encryption, secure access measures, and periodic audits—to maintain the confidentiality, integrity, and availability of critical AML data and protect sensitive customer information. These measures minimize the risk of breaches, ensuring continuous security and compliance in AML operations.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Protecting confidential data is relevant from the very beginning (setting up systems) to final record destruction. Realistically, it never “turns off.”

---

## Designation of Nominated Officer
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Tactical
- **Code:** M0012
- **Description:** This is an organizational measure requiring the formal appointment of a dedicated AML/CFT officer (commonly referred to as an MLRO or BSA Officer). By consolidating oversight under one officially accountable individual, the institution enhances governance of AML/CFT policies, fosters consistent policy implementation, and streamlines suspicious activity reporting. The designated officer serves as a central liaison with regulators, coordinates response to emerging risks, and ensures that suspicious transactions are identified, escalated, and reported promptly. This strengthens the institution’s overall capacity to detect and prevent money laundering by establishing clear leadership and accountability for AML/CFT program performance.
- **Short Description:** A formal AML/CFT officer (MLRO/BSA Officer) is appointed to develop and oversee AML policies, coordinate suspicious activity reporting, and liaise with regulators, promoting centralized oversight and strengthened governance for effective program implementation.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Organizational measure to appoint a single individual (MLRO or BSA Officer) with overarching AML accountability.

---

## Do Not Mitigate
- **Functional Category:** Risk Management & Governance
- **Application Level:** Strategic
- **Code:** M0010
- **Description:** This classification applies when introducing additional AML/CFT measures could unintentionally increase illicit misuse risks or hinder legitimate transactions beyond the expected benefits. In such scenarios, financial institutions refrain from implementing new controls and instead rely on risk-based approaches to preserve financial inclusion and operational efficiency. By choosing not to introduce further measures, FIs avoid inadvertently pushing illicit activity into unregulated channels or placing undue burdens on low-risk clients. However, they must still ensure existing regulatory obligations are met, regularly assess changing risks, and confirm that the decision not to mitigate aligns with broader compliance and business objectives.
- **Short Description:** In scenarios where standard AML/CFT controls could inadvertently elevate risk, limit legitimate access to financial services, or create operational inefficiencies, direct tactical mitigation should be avoided. Instead, organizations should evaluate alternative risk-based solutions to prevent driving illicit activity underground while safeguarding lawful transactions.

### Lifecycle Stages

- **Onboarding** – An FI might decide no extra measures are needed if standard checks suffice and risk is low.
- **Ongoing Relationship** – If a risk reevaluation shows further controls might be counterproductive.

---

## Employee Background Screening
- **Functional Category:** People & Awareness
- **Application Level:** Tactical
- **Code:** M0014
- **Description:** Employee background screening is a procedural measure requiring systematic checks of new hires and relevant existing staff (including identity, criminal, regulatory, and professional records) to identify any links to illicit or unethical behavior. By preventing the employment or retention of personnel who may facilitate money laundering or terrorist financing, it reduces insider threats such as collusion, fraud, or unauthorized use of sensitive information. Within financial institutions, this control ensures that individuals entrusted with transactional oversight, customer due diligence, or compliance responsibilities meet integrity standards. Regularly updating screening processes and escalating adverse findings further strengthens AML/CFT governance by limiting opportunities for staff exploitation in laundering or terrorist financing schemes.
- **Short Description:** Thoroughly verify staff credentials, criminal histories, and any prior misconduct to ensure only qualified, trustworthy individuals are employed. This proactive measure bolsters AML compliance by mitigating insider threats, reducing the risk of collusion, and safeguarding the institution’s integrity.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Focuses on internal hiring and ongoing staff checks, not a direct client interaction.

---

## Enhanced Due Diligence (EDD)
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0002
- **Description:** Enhanced Due Diligence (EDD) is a procedural control requiring financial institutions to perform deeper analysis and verification of customers or relationships considered higher risk for money laundering or terrorist financing. This includes thoroughly assessing sources of wealth and funds, scrutinizing beneficial ownership structures (including complex or opaque arrangements), and applying more frequent and rigorous monitoring. By demanding senior management approval for high-risk accounts and continuously verifying key information, EDD increases transparency and deters illicit financial flows, ensuring higher vigilance in identified elevated-risk scenarios.
- **Short Description:** Enhanced Due Diligence (EDD) involves deeper background checks, verification of beneficial ownership, and stricter scrutiny of high-risk customers (e.g., complex trust structures or PEPs) to verify sources of wealth and funds. By applying more rigorous oversight and ongoing monitoring, EDD mitigates heightened ML/TF risks and maintains clear visibility of customer activities.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – If a red flag surfaces early, EDD may be triggered.
- **Post Alert** – Additional deep dives if suspicious activity is found.
- **Onboarding** – If a red flag surfaces early, EDD may be triggered.
- **Ongoing Relationship** – Continuous deeper checks if risk escalates.

---

## Enterprise-Wide Risk Assessment
- **Functional Category:** Risk Management & Governance
- **Application Level:** Strategic
- **Code:** M0030
- **Description:** An Enterprise-Wide Risk Assessment (EWRA) is a strategic, organization-wide measure that identifies, analyzes, and monitors money laundering, terrorist financing, and related financial crime vulnerabilities across all products, services, customer segments, and geographies. By systematically reviewing both internal processes and external risk factors, financial institutions calibrate controls and resource allocations in proportion to the evolving ML/TF threats they face. This operational approach involves: (1) gathering and synthesizing relevant risk intelligence; (2) assessing inherent and residual risks for each line of business; (3) tailoring and enhancing AML/CFT measures based on the identified risk profile; and (4) maintaining a cycle of dynamic review and senior management oversight. The EWRA ultimately fosters informed, risk-based decisions, ensuring more robust detection, disruption, and prevention of illicit financial activity at an enterprise level.
- **Short Description:** An institution conducts an organization-wide evaluation of ML/TF risks across all products, services, and geographies, using these insights to tailor AML policies, optimize resource deployment, and calibrate controls in line with the identified risk profile.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Focuses on the institution’s comprehensive ML/TF risk, typically outside specific client episodes.

---

## Independent Audit and Testing
- **Functional Category:** Risk Management & Governance
- **Application Level:** Strategic
- **Code:** M0019
- **Description:** Independent audit and testing is an organizational measure that periodically and objectively evaluates a financial institution’s AML/CFT framework to ensure its effectiveness, consistency with risk-based policies, and compliance with regulatory requirements. By assigning this task either to an internal team independent from daily compliance operations or to qualified external auditors, institutions identify control gaps, verify the thorough application of policies and procedures, and confirm the adequacy of transaction monitoring and staff training. Through unbiased assessments and clear reports to senior management and boards, this measure improves governance, drives prompt remediation of weaknesses, and reinforces a culture of compliance, ultimately preserving the institution’s integrity in combatting money laundering and terrorist financing.
- **Short Description:** Independent audits and testing ensure AML/CFT controls and processes receive regular, unbiased reviews focused on higher-risk areas, identifying control gaps and verifying compliance with regulatory standards. By validating risk-management practices and governance structures, these audits bolster the overall effectiveness and integrity of an institution’s AML program.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Typically a higher-level, enterprise‐wide measure outside specific customer dealings.

---

## Information Sharing and Collaboration
- **Functional Category:** Risk Management & Governance
- **Application Level:** Strategic
- **Code:** M0022
- **Description:** Information Sharing and Collaboration is a coordinated procedural and organizational measure enabling financial institutions to exchange financial crime intelligence within lawful parameters, both among themselves and with relevant public authorities (e.g., regulators, law enforcement). Its primary AML/CFT purpose is to enhance detection, disruption, and prevention of illicit financial flows by pooling insights on typologies, red flags, and risk patterns. Mechanistically, it promotes stronger due diligence, better transaction monitoring, and more targeted investigations by creating a holistic view of customer and transactional information across multiple institutions. For FIs, this typically takes form in structured public–private partnerships or industry-led consortia, in which data-sharing frameworks and confidentiality safeguards are established to comply with data protection and other regulatory requirements. In practice, it supports faster identification of high-risk relationships, more timely suspicious transaction reporting, and overall improvements in the institution’s AML/CFT posture through aligned and up-to-date risk assessment practices.
- **Short Description:** Information Sharing and Collaboration involves securely and lawfully exchanging financial crime intelligence among financial institutions, regulators, and permissible law enforcement agencies under data protection and confidentiality guidelines. By leveraging public-private partnerships and sharing typologies, it strengthens the detection and disruption of money laundering and terrorism financing threats.

### Lifecycle Stages

- **Post Alert** – Collaborative measures can ramp up when suspicious or high-risk events arise.
- **Not Directly Related (Pre-Interaction)** – FIs often have information-sharing frameworks (e.g., industry groups, public-private partnerships) set up well before dealing with any specific client.

---

## Internal Policies and Procedures
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Strategic
- **Code:** M0009
- **Description:** This procedural and organizational measure creates a structured AML governance framework within financial institutions by clarifying accountability, establishing robust reporting lines, and embedding risk-based controls across all operational areas. It includes measures like segregation of duties, ethical conduct standards, specialized oversight for digital assets, dual authorization for high-risk transactions, and regular policy updates to adapt to evolving regulations. By promoting transparency, consistency, and timely identification of suspicious activities, these internal policies and procedures enhance the institution’s ability to prevent, detect, and escalate money laundering threats, thus strengthening its overall AML defensive posture.
- **Short Description:** Financial institutions implement robust governance frameworks, clear accountability structures, and risk-based controls to systematically identify, mitigate, and respond to potential money laundering activities. By embedding segregation of duties, dual authorization for high-risk transactions, and periodic updates aligned with evolving regulations, these internal policies and procedures strengthen AML compliance and fraud prevention across traditional and emerging areas like digital assets.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – These shape how an FI operates overall, not specifically tied to “customer phases.”

---

## Internal Reporting Mechanisms
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Strategic
- **Code:** M0025
- **Description:** Internal Reporting Mechanisms are procedural controls that establish formal, secure, and confidential channels (such as hotlines or portals) for employees to quickly escalate potential money laundering or terrorist financing concerns. Drawing on insights emphasizing a culture of transparency (Record 2065) and the critical function of whistleblower safeguards (Record 981), these mechanisms incorporate clear escalation protocols and privacy protections to encourage staff to flag suspicious activities or unethical conduct early. In financial institutions, this enables timely sharing of relevant information with compliance teams or committees, aiding swift analysis and resolution of AML/CFT risks. By fostering openness and ensuring whistleblower protection, Internal Reporting Mechanisms bolster accountability, strengthen investigative efforts and reinforce ongoing adherence to AML/CFT obligations.
- **Short Description:** Institutions establish formal, secure, and confidential channels (e.g., hotlines, portals) for employees to report suspicious activities, ensuring whistleblower protections and privacy. This fosters a culture of transparency, enabling rapid identification and resolution of AML/CFT concerns by compliance personnel or committees.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Setting up whistleblower hotlines and staff escalation routes is an internal measure, not triggered by a specific client.

---

## Ongoing Due Diligence
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0024
- **Description:** Ongoing due diligence is a procedural and analytical measure that systematically reviews and updates a customer’s risk profile by continuously verifying customer data, transactional patterns, and emerging risk factors. It directly supports AML/CFT objectives by detecting anomalies or red flags in account activity, recalibrating risk assessments, and escalating issues for enhanced monitoring or suspicious activity reporting. Through regular review cycles, financial institutions maintain updated customer information, enabling timely intervention to prevent and mitigate evolving money laundering or terrorist financing threats within their customer base.
- **Short Description:** Ongoing Due Diligence involves continuously monitoring and updating customer risk profiles, transaction activity, and associated data to quickly identify discrepancies or anomalies, enabling timely escalation of potential red flags and recalibration of risk levels to effectively mitigate emerging ML/TF threats.

### Lifecycle Stages

- **Ongoing Relationship** – Typically starts once the customer is onboarded; you keep verifying changes and follow up if suspicious.

---

## OSINT & External Source Verification
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0021
- **Description:** OSINT & External Source Verification is a procedural and investigative measure enabling financial institutions to use publicly accessible information—such as government registers, news outlets, external databases, and social media—to validate the identities, business activities, and beneficial ownership of customers. By systematically cross-referencing internal records with external sources throughout onboarding and ongoing monitoring, institutions can detect discrepancies, hidden ownership tiers, adverse media, and suspicious patterns more rapidly. This enhances due diligence, improves the accuracy of risk assessments, and bolsters investigations, ultimately reducing the possibility of criminal entities exploiting financial services for money laundering or terrorist financing.
- **Short Description:** This measure involves leveraging publicly accessible data and independent source validation to verify identities, uncover hidden ownership structures, and detect suspicious behavior. By continuously monitoring transactions and client profiles throughout the banking relationship, institutions strengthen detection and investigation of potential illicit activities.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – Could be used to vet prospective clients or check new intel at account opening.
- **Onboarding** – Could be used to vet prospective clients or check new intel at account opening.
- **Ongoing Relationship** – Regular checks for adverse media or changes in beneficial ownership.
- **Post Alert** – Additional external intel gathering to investigate suspicious scenarios.

---

## Quality Assurance and Control
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Strategic
- **Code:** M0028
- **Description:** Quality Assurance and Control is a procedural measure that ensures an FI’s AML/CFT program remains reliable, consistent, and aligned with evolving regulatory requirements. It involves structured, routine reviews of existing controls, regular testing (e.g., sampling transaction monitoring outputs or verifying data feeds), and maintaining feedback loops to identify and resolve procedural gaps. By embedding self-assessment or internal reviews into daily operations, institutions can stay vigilant to weaknesses, confirm that compliance activities (such as staff training completion) are tracked, and continuously refine their AML/CFT processes. This proactive approach preserves the effectiveness of risk detection, fosters robust oversight, and fortifies the institution’s overall defense against money laundering and terrorism financing threats.
- **Short Description:** Quality Assurance and Control involves ongoing testing, reviews, and benchmarking to identify and address weaknesses in AML/CFT frameworks, ensuring accuracy, reliability, and compliance. By regularly evaluating controls and incorporating feedback, institutions remain adaptable to evolving industry standards and regulatory requirements.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – Generally an enterprise-level measure that underpins the entire AML framework, not tied to a specific client contact point. Could arguably be ongoing all the time, but from a client-lifecycle perspective, it’s “outside” direct customer interaction.

---

## Record-Keeping & Audit Trails
- **Functional Category:** Organizational & Internal Controls
- **Application Level:** Strategic
- **Code:** M0015
- **Description:** Record-Keeping & Audit Trails is both a procedural and technological control that systematically preserves, organizes, and maintains all relevant transaction records, customer due diligence information, and investigative or regulatory reports. Its primary AML/CFT objective is to create a reliable chronological trail that fosters transparency and traceability, supporting faster detection and investigation of suspicious transactions. By enforcing strict data retention (commonly for five or more years) and utilizing thorough audit logs, financial institutions can reconstruct the flow of funds, uncover irregularities, and produce reliable evidence for enforcement, regulatory, or supervisory actions. In practice, this measure underpins effective compliance and risk management, guiding staff to capture and securely store comprehensive transaction data for subsequent review, while ensuring that internal controls, monitoring, and investigative processes are well-documented and readily accessible for scrutiny by auditors or law enforcement.
- **Short Description:** Maintain thorough records and audit trails of all customer interactions, transactions, and AML activities to enable effective compliance reviews and support forensic investigations. This involves strict data retention policies, regular backups, and robust audit logs that help identify suspicious trends and ensure regulatory adherence.

### Lifecycle Stages

- **Post Termination** – Records are typically retained for years after closure.
- **Pre-Onboarding Engagement** – Must keep records from the start of a prospective or new client.
- **Post Alert** – Maintaining evidence of investigations or escalations.
- **Ad Hoc Interaction** – Documentation of one-off transactions or engagements.
- **Onboarding** – Must keep records from the start of a prospective or new client.
- **Ongoing Relationship** – Logs of transactions, updates, or communications.

---

## Risk-Based Customer Profiling and Segmentation
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0017
- **Description:** Risk-Based Customer Profiling and Segmentation is a procedural and analytical control that classifies customers into distinct risk tiers based on factors such as geographic exposure, transaction patterns, product usage, and industry type. Its primary AML/CFT purpose is to facilitate targeted monitoring and due diligence, focusing enhanced scrutiny on higher-risk segments while minimizing false positives among lower-risk customers. By continuously updating customer profiles and refining segmentation criteria, financial institutions can calibrate transaction monitoring thresholds, direct investigative resources more effectively, and promptly identify unusual behavior for rapid escalation, ultimately bolstering their capacity to detect and deter illicit financial activity.
- **Short Description:** Develop tailored risk profiles for customers by evaluating factors such as transaction activity, product usage, geography, and industry, then update these segments continuously to align AML resources, refine transaction monitoring, and apply appropriate due diligence. This proactive approach helps identify risky deviations early and effectively mitigate higher-risk customer relationships.

### Lifecycle Stages

- **Pre-Onboarding Engagement** – Basic risk segmentation from the start.
- **Onboarding** – Basic risk segmentation from the start.
- **Ongoing Relationship** – Re‐segmentation as the customer’s activity changes.
- **Post Alert** – If a suspicious event triggers a recheck or risk reclassification.

---

## Sanctions & Watchlist Screening
- **Functional Category:** Onboarding & Customer‐Related Due Diligence
- **Application Level:** Tactical
- **Code:** M0005
- **Description:** Sanctions & Watchlist Screening is a combined procedural and technological measure by which financial institutions identify and restrict transactions or relationships involving sanctioned or high-risk individuals, entities, or jurisdictions. It systematically compares customer and transaction data against official sanctions lists (e.g., UN, OFAC, EU), PEP records, adverse media sources, and internal watchlists. This process operates in real time or via scheduled batch checks, flagging or blocking potential matches to prevent unauthorized or illegal transactions. Integrated with KYC/CDD and transaction monitoring workflows, it enables compliance teams to investigate alerts, apply measures such as account freezing or transaction rejection, and perform enhanced due diligence. By disrupting illicit flows and ensuring compliance with AML/CFT standards, it helps protect the institution’s operations from misuse by sanctioned or high-risk parties and mitigates legal and reputational risks.
- **Short Description:** Sanctions & Watchlist Screening systematically identifies and flags individuals or entities by comparing customers and transactions against sanctions lists, PEP databases, adverse media, and internal watchlists. This ensures AML/CFT compliance by preventing unauthorized or high-risk engagements and supporting swift investigation or account restrictions as needed.

### Lifecycle Stages

- **Ad Hoc Interaction** – E.g., a one-time payment from a potential match to a sanctions list.
- **Post Alert** – Additional or repeated screening if suspicious events occur.
- **Pre-Onboarding Engagement** – Standard practice to check prospective clients.
- **Onboarding** – Standard practice to check prospective clients.
- **Ongoing Relationship** – Periodic re-screenings or real-time screening of transactions.

---

## Service Restriction
- **Functional Category:** Relationship Actions
- **Application Level:** Tactical
- **Code:** M0023
- **Description:** Service Restriction is a procedural and technological control through which financial institutions limit, block, or withdraw access to higher-risk products, services, or transaction channels to reduce potential money laundering or terrorist financing misuse. By leveraging predefined criteria—such as suspending high-risk accounts, restricting certain transfers (particularly to high-risk jurisdictions), or allowing only basic banking services for customers under enhanced monitoring—institutions constrain opportunities for criminals to hide or transfer illicit funds. This measure bolsters transactional transparency, ensures additional checks before service reactivation, and enhances investigative capabilities by narrowing the scope of suspicious activity. Typically triggered by specific risk indicators, Service Restriction is embedded in an FI’s AML/CFT framework to promptly contain misuse, strengthen oversight, and prevent escalated ML/TF activities.
- **Short Description:** Financial institutions implement service restrictions to deny or limit access to higher-risk offerings (e.g., suspicious accounts, anonymous features, unlicensed money services) and identity-obscuring methods, thereby curbing illicit activities. These measures reduce the likelihood of ongoing financial crime and facilitate more timely investigations into potential misuse.

### Lifecycle Stages

- **Ongoing Relationship** – If new risk emerges, the FI can freeze or restrict services.
- **Onboarding** – The FI may limit certain products if the initial risk is high.
- **Post Alert** – A direct follow-up if the alert’s risk is unacceptable.

---

## Staff AML Training & Awareness
- **Functional Category:** People & Awareness
- **Application Level:** Tactical
- **Code:** M0013
- **Description:** Staff AML Training & Awareness is an organizational measure that equips employees with relevant AML/CFT knowledge, practical skills, and regulatory guidance. By regularly training frontline and compliance personnel on identifying and escalating red flags, verifying customer information, and understanding regulatory obligations, this mitigation helps detect, prevent, and respond to money laundering or terrorist financing. Through standardized training programs, staff maintain vigilance, apply consistent customer due diligence, and promptly report suspicious activities. This measure strengthens the institution’s overall AML/CFT framework by ensuring employees possess the essential knowledge and skills to identify and mitigate financial crime risks in day-to-day operations.
- **Short Description:** Implementing ongoing AML training ensures employees recognize regulatory requirements and red flags, maintain proper customer verification procedures, and swiftly escalate suspicious activities, thereby fortifying the institution’s AML/CFT controls.

### Lifecycle Stages

- **Not Directly Related (Pre-Interaction)** – This is an internal measure to ensure employees are trained before dealing with customers. Could also be ongoing, but from the client lifecycle perspective, it doesn’t link to a specific client stage.

---

## Suspicious Activity Reporting (SARs/STRs)
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0018
- **Description:** Suspicious Activity Reporting (SARs/STRs) is a procedural and technological control obliging financial institutions (FIs) to identify, assess, and document transactions or account activities that appear unusual or potentially linked to illicit conduct, and then promptly submit standardized reports to their respective financial intelligence units or authorities. It serves an explicit AML/CFT function by driving early detection and escalation of possible money laundering, terrorist financing, or other unlawful activities. In practice, FIs integrate automated surveillance systems and well-defined reporting protocols to generate alerts, train staff to recognize behavioral red flags, and establish clear processes for escalating suspicious activity to designated officers. This increases transparency in the financial sector, supports regulatory obligations, and enhances industry-wide collaboration with investigative authorities. As highlighted in record 1480, effective SAR/STR frameworks often rely on standardized reporting modules and management oversight mechanisms (e.g., ratio of filed reports to cases). Further, record 1426 underscores the need for mandatory staff escalation procedures and clear reporting channels to ensure that unusual activities are properly investigated. Finally, record 938 emphasizes the critical role played by frontline FIs in screening transactions, filing suspicious transaction reports, and sharing relevant intelligence with authorities in a timely manner.
- **Short Description:** Financial institutions implement Suspicious Activity Reporting by identifying red flags, securely documenting and escalating unusual transactions, and submitting standardized reports to financial intelligence units while maintaining strict confidentiality protocols. This detective and corrective measure aids in preventing illicit activities by ensuring timely, compliant, and secure communication of suspicious behaviors to the relevant authorities.

### Lifecycle Stages

- **Onboarding** – If you see suspicious activity from a pre-onboarding prospective client. However, often SAR/STR frameworks assume an established or attempted relationship.
- **Ongoing Relationship** – As soon as a suspicious transaction arises in normal day-to-day monitoring.
- **Post Alert** – The direct escalation if an alert is confirmed suspicious.

---

## Third-Party Risk Management
- **Functional Category:** Risk Management & Governance
- **Application Level:** Strategic
- **Code:** M0006
- **Description:** Third-Party Risk Management is an organizational and procedural control that safeguards financial institutions against money laundering and terrorism financing (ML/TF) vulnerabilities introduced by external vendors, service providers, or other partners. Its primary AML/CFT purpose is to ensure that any third party’s activities, products, or systems meet the institution’s compliance standards, thereby preventing criminal exploitation and maintaining oversight of outsourced operations. In practice, FIs implement ongoing due diligence at the onboarding stage—reviewing the third party’s AML track record, compliance practices, and financial stability—and extend these controls through periodic reviews, audits, and established governance procedures. This helps detect hidden ownership, mitigate risks from large or unexplained third-party transactions, and guarantee an effective response if suspicious behavior arises. By clearly outlining roles, responsibilities, and reporting obligations through service-level agreements and continuous monitoring, Third-Party Risk Management supports a robust control environment and protects the institution’s AML/CFT integrity throughout the vendor lifecycle.
- **Short Description:** Third-Party Risk Management involves conducting comprehensive risk assessments, due diligence, and contractual AML clauses to ensure that external vendors and partners meet regulatory standards. By continuously monitoring these relationships and performing periodic audits, financial institutions can prevent undue financial crime vulnerabilities.

### Lifecycle Stages

- **Onboarding** – If a customer uses external service providers or is introduced by a third party.
- **Ongoing Relationship** – Continuous vendor oversight.
- **Not Directly Related (Pre-Interaction)** – Policies and vendor onboarding requirements are set up before dealing with any specific client’s third parties.

---

## Trade Monitoring
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0026
- **Description:** Trade Monitoring is a structured detective control adopted by financial institutions to systematically scrutinize trade flows and related documentation for price manipulation, misinvoicing, and other suspicious patterns indicative of money laundering or terrorist financing. By verifying trade counterparties, cross-checking shipping and invoice details for inconsistencies (e.g., atypical quantities, false valuations), and assessing the legitimacy of goods and beneficiaries—particularly for high-risk commodities such as precious metals—financial institutions can more effectively detect and disrupt illicit financial flows attempting to exploit trade channels. Leveraging data analytics and comparative techniques (such as unit-price or anomaly detection), this measure strengthens internal AML/CFT investigations and enhances transparency around cross-border and high-risk transactions in international commerce, ultimately mitigating the risk of trade-based money laundering schemes.
- **Short Description:** Implement thorough monitoring frameworks that verify counterparties, cross-check trade documents against market data, and apply heightened scrutiny to high‑risk commodities (e.g., diamonds, precious metals) to detect misinvoicing or anomalous patterns. This systematic approach helps identify and mitigate trade‑based money laundering schemes and other illicit activities.

### Lifecycle Stages

- **Ad Hoc Interaction** – Might be relevant for a one-time trade transaction by a walk-in or an unusual scenario.
- **Post Alert** – Further scrutiny if suspicious patterns emerge.
- **Ongoing Relationship** – Typically applies when the client is active and conducting trade finance or cross-border trade.

---

## Transaction Escrow Management
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0020
- **Description:** Transaction Escrow Management is a procedural measure whereby funds are temporarily held in a dedicated escrow account until specified conditions, including compliance checks and due diligence, are satisfied. By delaying the release of high-risk or large-value transactions, this control ensures thorough verification of customer identities, sources of funds, and supporting documentation prior to final settlement. Through this mechanism, financial institutions interrupt potential money laundering or unauthorized financing activities, reinforce transparency and oversight of transaction flows, and bolster overall AML/CFT defenses by preventing the immediate and unrestricted movement of funds.
- **Short Description:** Transaction Escrow Management involves holding funds in escrow accounts during high-risk transactions until all parties and compliance checks have been satisfied. This ensures added oversight, helping mitigate fraudulent or suspicious activity by preventing direct fund movement until conditions are met.

### Lifecycle Stages

- **Ongoing Relationship** – Commonly used if a client’s transaction triggers a risk rule or needs extra verification.
- **Onboarding** – May be imposed when a new client deposits funds of uncertain origin or when there’s a higher risk flagged during initial setup.
- **Post Alert** – If a suspicious alert arises mid-relationship, escrow can hold funds until additional checks are done.

---

## Transaction Monitoring
- **Functional Category:** Transaction & Activity Monitoring, Escalation
- **Application Level:** Tactical
- **Code:** M0004
- **Description:** Transaction Monitoring is a key detective measure enabling financial institutions to continuously track and evaluate customer transactions across accounts, products, and channels, including digital assets. It relies on rules-based scenarios, advanced analytics, and alert-generation mechanisms to identify activities deviating from a customer’s established risk profile. Detected alerts are escalated through well-defined pathways for investigation, helping determine whether the activity is potentially money laundering, terrorist financing, or another illicit scheme. This control is most effective when supported by accurate, comprehensive data, robust scenario coverage (frequently tuned and enhanced to capture emerging typologies), and a clear escalation process for compliance or law enforcement referrals. Within an FI, it typically integrates with case management systems to document and streamline investigations, ensuring timely alerts and, where necessary, regulatory reporting. By harnessing ongoing oversight, data governance, and scenario refinement, transaction monitoring helps mitigate illicit financial risks, strengthens institutional AML/CFT frameworks, and supports prompt detection and intervention in suspicious transactions.
- **Short Description:** Transaction Monitoring is a detective process that uses real-time or periodic analysis—integrating rules-based scenarios, advanced analytics, and automated compliance checks—to swiftly identify and escalate suspicious activity, ensuring timely investigation and potential regulatory reporting.

### Lifecycle Stages

- **Onboarding** – Immediately upon account creation if the client starts transacting.
- **Ongoing Relationship** – The main scenario.
- **Post Alert** – If a suspicious pattern is detected, monitoring might intensify.
- **Ad Hoc Interaction** – Possible, but usually that merges with Ongoing Relationship.

---
