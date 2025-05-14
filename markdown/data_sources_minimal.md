# Minimal Data Sources Extract

## Account Activity Logs
- **Group:** Transaction & Payment Data
- **Code:** DS0001
- **Description:** Detailed records of all actions within financial accounts, covering financial transactions and changes to account settings, including timestamps, user identifiers, and related metadata.
- **Short Description:** Account Activity Logs record every financial transaction and account setting change, capturing timestamps, user identifiers, and related metadata essential for uncovering anomalies and suspicious behaviors. They are critical for AML/CFT threat modeling, helping trace illicit fund flows and identify potential money laundering or terrorist financing activities.

---

## Adverse Media & Court Filings
- **Group:** Watchlists & Adverse Data
- **Code:** DS0003
- **Description:** Aggregated records from media sources and official legal documents (e.g., court filings, lawsuits) highlighting negative news, legal actions, and alleged misconduct associated with individuals or entities.
- **Short Description:** Adverse Media & Court Filings compiles negative news, legal actions, and related misconduct records from media outlets and official court documents, offering critical insights into potential illegal activities or reputational risks essential for AML/CFT threat assessments.

---

## API & Bulk-Instruction Logs
- **Group:** N/A
- **Code:** DS0051
- **Description:** Comprehensive audit trails capturing all programmatic payment instructions initiated through channels such as open-banking APIs or SFTP/bulk file uploads. These logs record critical details including client identifiers, authentication token scopes, job statuses, timestamps, payload metadata, and the specifics of each payment instruction. They provide visibility into both individual and batch payment activities, enabling the detection of automated or scripted mass-payment behaviors.
- **Short Description:** Detailed audit trails of programmatic payment instructions (open-banking APIs, SFTP/Bulk files), including client ID, token scope, job status and payload metadata, essential for detecting scripted mass-payment behaviour.

---

## Asset Declarations
- **Group:** Legal, Regulatory & Licensing Data
- **Code:** DS0024
- **Description:** Statements disclosing an individual’s or entity’s assets, liabilities, and financial interests, often required for public officials or certain high-profile individuals. These records provide a snapshot of declared wealth, enabling verification of stated financial positions.
- **Short Description:** Asset Declarations offer a verified snapshot of an individual’s or entity’s wealth, assisting AML/CFT professionals in detecting inconsistencies between declared and actual financial positions. By illuminating potential discrepancies or unexplained assets, they support the identification of suspicious financial activities, such as money-laundering or terrorist financing.

---

## ATM Usage & Geolocation Data
- **Group:** Transaction & Payment Data
- **Code:** DS0040
- **Description:** Detailed records of ATM usage, including geolocation data, date and time stamps, transaction types and amounts, and other related metadata.
- **Short Description:** ATM Usage & Geolocation Data provides vital insights into customers’ transaction patterns—combining location, timing, and transaction metadata—to identify high-risk activities, suspicious withdrawals, or structuring attempts. By analyzing this granular data, financial institutions can enhance AML/CFT adversarial threat modeling through early detection of anomalous behavior tied to money laundering and terrorism financing.

---

## Bank Account Data
- **Group:** Transaction & Payment Data
- **Code:** DS0023
- **Description:** Comprehensive data on individuals’ or entities’ bank accounts, including account numbers, ownership details, account types, balances, and transaction histories.
- **Short Description:** Bank Account Data provides detailed account information—such as account numbers, ownership details, balances, and transactions—essential for tracing illicit financial flows and identifying potential money laundering or terrorist financing activities. This data is critical for AML/CFT threat modeling because it reveals patterns of suspicious transfers and helps pinpoint high-risk individuals or entities.

---

## Blockchain and Cryptocurrency Data
- **Group:** Transaction & Payment Data
- **Code:** DS0045
- **Description:** Comprehensive data from public blockchain ledgers and related analytics, including transaction IDs, timestamps, sender and receiver addresses, and amounts for digital asset transactions.
- **Short Description:** This data source provides critical visibility into the flow of digital assets by capturing transaction IDs, timestamps, wallet addresses, and transaction amounts on public blockchain ledgers. It is essential for tracing illicit activities, identifying high-risk entities, and detecting patterns of money laundering or terrorist financing attempts involving cryptocurrencies.

---

## Business Activity and Operations
- **Group:** Business & Financial Records
- **Code:** DS0030
- **Description:** Data on a business’s commercial, industrial, or professional operations, including revenue figures, operating expenses, and related metrics, often compared with reported financial information to identify discrepancies or anomalies.
- **Short Description:** Business Activity and Operations data offers insights into a company’s revenue, expenses, and operational metrics, enabling the comparison of actual activity to reported financial information. These comparisons help uncover potential anomalies or discrepancies, facilitating the detection of money laundering or terrorist financing risks in AML/CFT threat modelling.

---

## Casino and Gambling Transaction Records
- **Group:** Transaction & Payment Data
- **Code:** DS0041
- **Description:** Comprehensive data on gambling transactions and activities, including aggregated information on game types, betting frequency, transaction amounts, participant identities, deposit and withdrawal data, and other relevant details across casinos and related operations.
- **Short Description:** Casino and Gambling Transaction Records provide a comprehensive view of gambling activities—covering game types, betting frequency, transaction amounts, participant identities, and deposit/withdrawal data—enabling investigators to detect high-risk patterns, uncover suspicious flows, and identify potential money laundering or terrorist financing schemes.

---

## Commodity Market Data
- **Group:** Market & Instrument Data
- **Code:** DS0009
- **Description:** Information on commodity prices, price indices, origins, types, and values, including historical and current market trends. Financial institutions may reference this data to assess and validate commodity-related transactions in contexts such as trade finance.
- **Short Description:** Commodity Market Data provides historical and current information on commodity prices, indices, origins, types, and values, enabling financial institutions to cross-verify the legitimacy of commodity-related transactions. In AML/CFT adversarial threat modelling, this data is crucial for detecting anomalies and uncovering potential trade-based money laundering activities.

---

## Commodity Transaction Data
- **Group:** Transaction & Payment Data
- **Code:** DS0044
- **Description:** Detailed records of commodity purchases, sales, or exchanges, including transaction dates, parties involved, commodity types, quantities, and prices. These records help verify the legitimacy and scope of commodity-related transactions, especially in trade finance scenarios.
- **Short Description:** Commodity Transaction Data captures comprehensive details of commodity trades—including dates, parties, types, quantities, and prices—enabling verification of transaction legitimacy and scope. This data source is crucial for detecting anomalous or suspicious flows in trade finance, supporting effective AML/CFT threat assessments.

---

## Communication Records
- **Group:** OSINT & Communication Data
- **Code:** DS0042
- **Description:** Records of electronic communications, including emails, phone calls, messaging apps, and social media, capturing metadata such as sender/receiver details and timestamps. Where legally permissible, the content may also be included. These logs can help identify suspicious instructions, insider collusion, or other high-risk interactions among individuals or entities.
- **Short Description:** Communication Records provide critical metadata and, where permissible, content of electronic interactions that uncover potential insider collusion, suspicious instructions, or other high-risk exchanges. By tracing communication patterns among individuals and entities, this data source enables targeted AML/CFT threat detection and investigation.

---

## Company & Beneficial Ownership Registries
- **Group:** Corporate & Ownership Data
- **Code:** DS0049
- **Description:** Consolidated records providing official or aggregated details of organizations, such as registration and incorporation data, licensing, shareholders, directors, ownership structures, partnership or trust information, and membership changes.
- **Short Description:** Company & Beneficial Ownership Registries consolidate key organizational data—including formation, shareholder and director details, and ownership structures—into a single authoritative source. They are crucial for uncovering hidden ownership networks and potential shell entities, making them an essential resource in AML/CFT adversarial threat modelling.

---

## Contractual and Invoice Data
- **Group:** Business & Financial Records
- **Code:** DS0013
- **Description:** Information on contractual agreements and invoices, including payment terms, parties involved, invoice identifiers, amounts, and client details. Often referenced by financial institutions to validate account activity and confirm the legitimacy of business transactions.
- **Short Description:** Contractual and Invoice Data provides detailed insights into the nature and legitimacy of commercial relationships by capturing terms, parties, and transaction details. This information is essential in AML/CFT adversarial threat modelling to verify business authenticity, trace suspicious payments, and detect potential illicit financing activities.

---

## Correspondent and Cross-Border Transaction Data
- **Group:** Transaction & Payment Data
- **Code:** DS0047
- **Description:** Information on cross-border financial transactions, covering transaction amounts, participating institutions, involved countries, currencies, settlement processes, and account relationships. This data is typically collected from banks, payment processors, and other intermediaries through correspondent banking relationships.
- **Short Description:** This dataset offers critical insight into cross-border money flows, including transaction details, institutional partnerships, and account relationships, enabling the detection of complex laundering structures and jurisdictional risk. By tracing the movement of funds and identifying high-risk or sanctioned endpoints, investigators can more effectively uncover and mitigate global money laundering and terrorism financing networks.

---

## Currency Exchange Transactions
- **Group:** Transaction & Payment Data
- **Code:** DS0014
- **Description:** Records of currency conversion activities, including spot trades, forward contracts, and swaps, typically covering timestamps, trading parties, exchange rates, volumes, and settlement details.
- **Short Description:** Currency Exchange Transactions capture the detailed mechanics of currency conversion activities—including trades, parties, rates, volumes, and settlements—and enable the identification of suspicious patterns and potential cross-border movements that may signal money laundering or terrorist financing risks.

---

## Customs and Asset Seizure Records
- **Group:** Customs, Border & Trade Data
- **Code:** DS0015
- **Description:** Official data on goods and financial assets seized by customs or enforcement authorities, including details about the items seized, parties involved, and any associated legal proceedings.
- **Short Description:** Customs and Asset Seizure Records provide official details on confiscated goods, financial assets, and the parties involved, enhancing visibility into cross-border illicit flows or suspicious activities. This information is crucial for identifying high-risk networks and potential legal or regulatory actions within AML/CFT adversarial threat modelling.

---

## Customs and Border Records
- **Group:** Customs, Border & Trade Data
- **Code:** DS0004
- **Description:** Comprehensive records from customs and border authorities detailing the movement of goods and individuals, including imported and exported items, shipping routes, tariffs, and related documentation.
- **Short Description:** Customs and Border Records provide detailed insights into the cross-border movement of goods and individuals, capturing shipping routes, tariffs, and related documentation. These records are integral to detecting and investigating trade-based money laundering, illicit trafficking, and other complex cross-border financial crimes.

---

## Device & Browser Fingerprint Data
- **Group:** N/A
- **Code:** DS0050
- **Description:** Aggregated device ID, browser fingerprint, and behavioral biometric telemetry are collected during user interactions with digital channels, such as web or mobile applications. This data includes unique device characteristics (e.g., hardware configuration, operating system, installed fonts, screen resolution), browser attributes (e.g., user agent, plugins, timezone), and behavioral patterns (e.g., typing rhythm, mouse movements, touch gestures). By analyzing these attributes, organizations can accurately identify and link accounts or sessions that may appear unrelated but are actually associated with the same device, browser, or user. This capability is essential for detecting automated activity, preventing account takeover, and uncovering fraudulent schemes where individuals attempt to mask their identity or control multiple accounts. Device and browser fingerprint data is a key component in advanced fraud detection and AML/CFT monitoring systems.
- **Short Description:** Aggregated device-ID, browser-fingerprint and behavioural-biometric telemetry captured during digital-channel sessions, enabling linkage of seemingly unrelated accounts controlled by the same automation tool.

---

## Digital Banking & Cybersecurity Event Data
- **Group:** Access & Security Data
- **Code:** DS0008
- **Description:** Information about online and mobile banking activities, including IP logs, device usage patterns, unauthorized access attempts, transaction anomalies, and related cybersecurity events.
- **Short Description:** This data source captures critical digital channel indicators—including IP logs, device fingerprints, and suspicious login attempts—that help institutions detect and investigate unauthorized transactions or anomalous activities. It bolsters AML/CFT threat modeling by providing key insights into potential cyber-enabled fraud, money laundering, and terrorist financing schemes occurring via online and mobile banking.

---

## Document Management Systems
- **Group:** Customer Onboarding & Identity Data
- **Code:** DS0021
- **Description:** Centralized platforms for storing, organizing, and managing a variety of records—such as KYC files, contracts, and other supporting documents—typically providing secure retrieval, version control, access permissions, and audit trails.
- **Short Description:** Document Management Systems centralize and secure sensitive records such as KYC files and contracts, offering version control, access permissions, and audit trails. In AML/CFT adversarial threat modeling, they play a key role by enabling oversight of document integrity and user activities, helping detect unauthorized access or alterations.

---

## Document Verification
- **Group:** Customer Onboarding & Identity Data
- **Code:** DS0027
- **Description:** Specialized systems or services that authenticate and validate official identification documents—such as passports or IDs—detecting potential forgeries, inconsistencies, or tampering.
- **Short Description:** Document Verification services confirm the legitimacy of official identification documents, detecting forgeries and inconsistencies to mitigate identity fraud risk. Integrating these checks into AML/CFT frameworks fortifies KYC processes and compliance efforts against illicit finance.

---

## Donation Platforms & Donor Records
- **Group:** Transaction & Payment Data
- **Code:** DS0026
- **Description:** Records from online fundraising platforms and associated donation logs, including donor identities, amounts, contribution dates, and intended purposes.
- **Short Description:** Donation platform and donor records offer detailed insights into individual contributions, including donor identities, amounts, dates, and intended purposes, which help detect suspicious patterns, fund flows, or potential misuse in support of illicit activities.

---

## Employee Records
- **Group:** Employment & HR Data
- **Code:** DS0028
- **Description:** Comprehensive records of employee identities, roles, and relevant employment details, used to track internal accountability and detect potential conflicts of interest or misconduct.
- **Short Description:** Employee Records capture detailed information on employees’ identities, roles, and employment histories, enabling monitoring for insider threats and conflict-of-interest red flags. They are critical in AML/CFT threat modeling to help maintain internal accountability and prevent misconduct.

---

## Exchange & Trading Activity Records
- **Group:** Transaction & Payment Data
- **Code:** DS0046
- **Description:** Records of trades and transactions on regulated financial exchanges, covering securities, commodities, derivatives, and cryptocurrencies. Typically includes trade volumes, dates, prices, counterparties, timestamps, transaction identifiers, and related compliance details.
- **Short Description:** Exchange & Trading Activity Records offer detailed insights into securities, commodities, derivatives, and cryptocurrency transactions, capturing key data points like trade volumes, dates, counterparties, and compliance indicators. They are critical for detecting potential illicit flows, anomalies, and patterns relevant to AML/CFT adversarial threat analysis.

---

## Financial Audits
- **Group:** Business & Financial Records
- **Code:** DS0031
- **Description:** Audit reports containing independent examinations of an organization's financial statements and internal controls, typically conducted by external auditors, providing an objective assessment of financial accuracy and compliance with accounting standards.
- **Short Description:** Financial audits offer a critical, independent assessment of an organization’s financial statements and internal controls, helping identify inaccuracies or compliance gaps that may signal money laundering or terrorist financing risks. Their robust, external perspective makes them a key data source in AML/CFT adversarial threat modeling, informing risk assessment and mitigation strategies.

---

## Financial, Business & Tax Records
- **Group:** Business & Financial Records
- **Code:** DS0007
- **Description:** Documentation and official filings covering an entity's financial activities, including balance sheets, profit-and-loss statements, tax returns, and related records. Typically referenced to evaluate an entity's financial stability, verify reported performance, and identify discrepancies or anomalies in financial profiles.
- **Short Description:** Financial, Business & Tax Records furnish verifiable insights into an entity’s financial health and transactions, enabling AML/CFT professionals to spot discrepancies, validate reported performance, and identify potential anomalies indicative of illicit activity.

---

## Financial Instrument & Securities Market Data
- **Group:** Market & Instrument Data
- **Code:** DS0035
- **Description:** Comprehensive datasets covering stocks, bonds, derivatives, and other investment vehicles, including the instrument’s name, type, issuer, maturity date, interest rate, real-time and historical pricing, trading volumes, and market trends. Financial institutions may reference this information to monitor investments and detect unusual price or volume movements.
- **Short Description:** Financial Instrument & Securities Market Data provides real-time and historical details for a wide range of investment vehicles, enabling the identification of abnormal price fluctuations and trading volumes. Its comprehensive coverage of instruments and market trends is critical in detecting suspicious transactions and potential money laundering or terrorist financing activities.

---

## Fraud Data
- **Group:** Watchlists & Adverse Data
- **Code:** DS0033
- **Description:** Information on known or suspected fraudulent activities, including identity theft, payment card fraud, or scam patterns, compiled from reported incidents, industry warnings, or shared alerts.
- **Short Description:** Fraud Data captures critical intelligence on emerging and known fraudulent activities—such as identity theft, payment card fraud, and scam patterns—providing valuable insights into adversarial tactics and risk indicators. It enables financial institutions to proactively detect, assess, and counter evolving threats within AML/CFT frameworks.

---

## Geographical & Jurisdictional Risk Data
- **Group:** Legal, Regulatory & Licensing Data
- **Code:** DS0005
- **Description:** Consolidated information on countries, regions, legal jurisdictions, and AML/CFT laws, regulations, and enforcement practices, used to assess geographic and regulatory risk and identify anomalies in financial transactions.
- **Short Description:** This dataset consolidates country-specific AML/CFT laws, regulations, and enforcement practices to identify high-risk regions and detect anomalies in financial transactions. By highlighting geographic and jurisdictional vulnerabilities, it is instrumental in assessing and mitigating AML/CFT threats.

---

## Geographical Transaction Data
- **Group:** Transaction & Payment Data
- **Code:** DS0048
- **Description:** Location-based records of financial transactions, including origin, destination, amounts, timing, and relevant geolocation metadata for analyzing cross-border transactions and payment flows.
- **Short Description:** Geographical Transaction Data captures origin, destination, timing, amounts, and geolocation metadata for financial transactions, enabling the detection of suspicious cross-border flows. By highlighting jurisdictional interactions and transaction pathways, this data source is crucial for spotting potential AML/CFT threats and unraveling complex illicit networks.

---

## Individual, Entity & Public Records Databases
- **Group:** Customer Onboarding & Identity Data
- **Code:** DS0020
- **Description:** Aggregated information on individuals and organizations from government registries, publicly available sources, and private third-party providers, including identity details, legal status, and beneficial ownership data.
- **Short Description:** These databases consolidate verified identity information, entity status, and beneficial ownership details from multiple sources, enabling comprehensive due diligence and risk assessments. Their use ensures more accurate identification of suspicious activity and helps prevent misuse of financial systems for illicit purposes.

---

## Job Recruitment Data
- **Group:** Employment & HR Data
- **Code:** DS0037
- **Description:** Records from online job recruitment platforms, including job postings, candidate applications, and employment details. These data can reveal unusual recruitment patterns or potential money mule schemes.
- **Short Description:** Job Recruitment Data provides insights into unusual hiring practices, such as the recruitment of money mules, supporting the detection and disruption of potential money laundering or terrorist financing activities. By examining candidate applications and employment details, investigators can identify suspicious patterns that signal illicit financial flows.

---

## KYC & Customer Due Diligence Records
- **Group:** Customer Onboarding & Identity Data
- **Code:** DS0039
- **Description:** Comprehensive internal dataset containing verified customer identities, personal and business details, addresses, beneficial ownership information, account relationships, transaction summaries, risk metrics, financial statements, and business activity records.
- **Short Description:** KYC and Customer Due Diligence Records provide verified identities, beneficial ownership details, and in-depth financial and business activity information, serving as a key dataset for detecting and assessing risks in AML/CFT adversarial threat modeling. This dataset underpins customer profiling, supports compliance checks, and enhances anomaly detection across financial transactions.

---

## Legal Documentation & Records
- **Group:** Legal, Regulatory & Licensing Data
- **Code:** DS0016
- **Description:** Collections of binding legal documents—including contracts, deeds, court orders, and judgments—used to verify legal rights, obligations, and relationships in financial dealings.
- **Short Description:** Legal Documentation & Records provide authoritative evidence of parties’ rights and obligations in financial transactions, helping to validate ownership structures, legal relationships, and compliance obligations. By offering verifiable proof of lawful standing, they support the early detection and mitigation of suspicious activities in AML/CFT adversarial threat modeling.

---

## Loan Agreements and Credit Facilities
- **Group:** Loan & Credit Data
- **Code:** DS0032
- **Description:** Formal contracts related to lending and credit products—such as personal loans, mortgages, credit cards, and lines of credit—detailing loan amounts, interest rates, repayment schedules, and collateral. These records enable financial institutions to assess borrowers, track repayment patterns, and identify irregular credit usage.
- **Short Description:** Loan agreements and credit facilities document key borrower details and credit terms, enabling financial institutions to detect irregular repayment or usage patterns that may indicate money laundering or terrorist financing.

---

## Money Service Business (MSB) Registries
- **Group:** Corporate & Ownership Data
- **Code:** DS0029
- **Description:** Official or government-run registries listing licensed money service businesses or remittance providers, including their licensing status and operational details.
- **Short Description:** Money Service Business (MSB) Registries provide authoritative lists of licensed MSBs or remittance providers, detailing their license status and operational scope. Such information is critical for AML/CFT threat modeling to verify legitimate operators, detect unauthorized activities, and identify potential risk patterns in financial transactions.

---

## Online & Digital Payment Platform Data
- **Group:** Transaction & Payment Data
- **Code:** DS0022
- **Description:** Consolidated records from online payment platforms, e-wallets, and fintech payment processors, covering transaction details, user identifiers, operational data, balances, transaction volumes, and related metadata.
- **Short Description:** This data source consolidates records from various digital payment platforms and e-wallets, offering detailed transactions, user identifiers, and operational metadata. It is critical for detecting high-risk behaviors, pinpointing suspicious patterns, and tracing illicit flows in digital payment networks within AML/CFT threat modeling.

---

## Open-Source Intelligence (OSINT)
- **Group:** OSINT & Communication Data
- **Code:** DS0011
- **Description:** Publicly available information from websites, social media platforms, news outlets, and public records. This may include user profiles, corporate announcements, and other open data relevant to verifying identities and analyzing associations.
- **Short Description:** Open-Source Intelligence (OSINT) leverages publicly available data from websites, social media, news outlets, and public records to verify identities and uncover associations. In AML/CFT threat modelling, it provides critical insights into potential illicit networks and suspicious financial activities, thereby enhancing due diligence and risk mitigation.

---

## Politically Exposed Persons (PEP) Lists
- **Group:** Watchlists & Adverse Data
- **Code:** DS0002
- **Description:** Databases detailing individuals holding prominent public or political positions, including their official roles, associated entities, and known affiliations.
- **Short Description:** PEP lists catalog individuals in or with close ties to prominent government roles, capturing their official positions and notable affiliations. This data source is integral for AML/CFT threat modeling, enabling institutions to identify and monitor high-risk exposure to bribery, corruption, or illicit financial activities.

---

## Prepaid Card Transaction Data
- **Group:** Transaction & Payment Data
- **Code:** DS0017
- **Description:** Information on transactions involving prepaid cards, including transaction amounts, frequencies, card identifiers, and overall usage patterns.
- **Short Description:** Prepaid Card Transaction Data offers insights into transaction amounts, frequencies, identifiers, and usage patterns of prepaid cards, providing a critical basis for detecting potentially suspicious transactions and identifying emerging threat patterns in AML/CFT analysis.

---

## Product & Service Usage Data
- **Group:** Product & Service Usage Data
- **Code:** DS0010
- **Description:** Consolidated data on how customers utilize financial products and services, including usage frequency, transaction volumes, product types, and related usage metrics.
- **Short Description:** This dataset provides holistic insights into how customers engage with financial offerings, capturing key metrics such as product usage frequency and transaction volumes. In AML/CFT threat modeling, it is crucial for detecting anomalies and suspicious activity patterns indicative of potential money laundering or terrorist financing.

---

## Professional Licensing & Affiliation Databases
- **Group:** Legal, Regulatory & Licensing Data
- **Code:** DS0006
- **Description:** Databases containing information on professional roles, licenses, memberships, and affiliations.
- **Short Description:** Professional Licensing & Affiliation Databases provide oversight of valid professional roles and memberships, offering critical intelligence for verifying individuals’ credentials and identifying suspicious affiliations. They enhance AML/CFT threat modelling by uncovering unauthorized activities, enabling more effective detection of potential illicit networks.

---

## Real Estate & High-Value Asset Ownership and Transaction Records
- **Group:** Corporate & Ownership Data
- **Code:** DS0043
- **Description:** Databases containing comprehensive information on the ownership, purchase, and transfer of real property and other high-value assets (such as vehicles, luxury goods, fine art, and precious metals). These records typically include details like property addresses, transaction dates, purchase values, involved parties, and beneficial ownership data.
- **Short Description:** This data source offers comprehensive details on real property and high-value asset ownership, including transaction dates, purchase values, and beneficial ownership information. It is critical for tracking hidden or complex asset holdings in AML/CFT threat modelling, helping to detect illicit financial flows and flag possible money laundering activities.

---

## Safe Deposit Box Access Records
- **Group:** Access & Security Data
- **Code:** DS0034
- **Description:** Records tracking access to safe deposit boxes, including the date, time, and identity of the individual accessing the box.
- **Short Description:** Safe Deposit Box Access Records provide a chronological log of individuals’ box entries, including their identities, time, and date of access. This information is crucial for detecting suspicious usage patterns, linking individuals to potential illicit activities, and supporting AML/CFT investigations.

---

## Sanctions Lists
- **Group:** Watchlists & Adverse Data
- **Code:** DS0018
- **Description:** Sanctions lists are **official compilations of individuals, entities, and jurisdictions** subject to economic, trade, or financial restrictions imposed by governments and international bodies. These lists are a critical data source for Anti-Money Laundering (AML), Counter-Terrorist Financing (CTF), and Counter-Proliferation Financing (CPF) programs, as they help financial institutions identify **prohibited or high-risk parties** in transactions and customer relationships.  

Sanctions lists may be maintained by national authorities, supranational organizations, or regulatory bodies. Key examples include:  
- **United Nations Security Council (UNSC) Sanctions List** – Mandated by UN member states for global compliance.  
- **Office of Foreign Assets Control (OFAC) – Specially Designated Nationals (SDN) List** – Maintained by the U.S. Department of Treasury.  
- **EU Consolidated Sanctions List** – Covers EU-wide financial restrictions.  
- **UK Sanctions List (OFSI)** – Maintained by the UK Office of Financial Sanctions Implementation.  
- **Other Country-Specific Lists** – Such as Canada’s Consolidated Sanctions List, Australia’s DFAT List, and Russia’s counter-sanctions lists.  

Sanctions lists are used in AML for:  
1. **Customer Due Diligence (CDD) & Know Your Customer (KYC)** – Screening individuals and entities during onboarding.  
2. **Transaction Monitoring & Screening** – Flagging or blocking transactions involving sanctioned parties.  
3. **Investigations & Reporting** – Supporting Suspicious Activity Reports (SARs) and law enforcement collaboration.  
4. **Trade Finance & Correspondent Banking** – Ensuring compliance in cross-border transactions and supply chains.  

Sanctions lists typically include:  
- **Full Name / Alias / Known Variations**  
- **Date of Birth (DOB) / Place of Birth (POB)**  
- **Passport / National ID Numbers**  
- **Addresses (Registered & Known Locations)**  
- **Business Affiliations / Linked Entities**  
- **Sanctions Program / Designation Authority**  
- **Reasons for Sanction (e.g., Terrorist Financing, WMD Proliferation, Human Rights Violations)**  
- **Restrictions (Asset Freezes, Travel Bans, Trade Restrictions)**
- **Short Description:** Sanctions lists are official records of individuals, entities, and jurisdictions subject to financial or trade restrictions due to concerns like terrorism, proliferation, or human rights violations. These lists are essential for AML/CFT/CPF programs, helping institutions screen customers and transactions to prevent dealings with prohibited or high-risk parties.

---

## System & Network Access Logs
- **Group:** Access & Security Data
- **Code:** DS0025
- **Description:** Centralized logs capturing user and system activities, network and web traffic, authentication events, IP addresses, timestamps, URLs visited, user-agent strings, and other related details. These logs provide audit trails of user activities and help identify unauthorized access or unusual system interactions.
- **Short Description:** System & Network Access Logs provide a comprehensive record of user activities, authentication events, and traffic patterns, forming a critical evidence source for detecting and investigating potential AML/CFT threats. Their detailed audit trails enable stakeholders to identify unauthorized access, abnormal behavior, and early indicators of malicious tactics, strengthening overall defense mechanisms.

---

## Trade Documentation
- **Group:** Customs, Border & Trade Data
- **Code:** DS0036
- **Description:** Official documents required for international trade, such as shipping logs, customs declarations, bills of lading, invoices, and certificates of origin. Often used to verify the legitimacy of cross-border transactions, confirm declared goods, and detect potential trade-based anomalies.
- **Short Description:** Trade Documentation, encompassing shipping logs, customs declarations, bills of lading, and related records, is crucial for validating cross-border transactions and uncovering potential trade-based anomalies. In AML/CFT adversarial threat modeling, these documents enable the detection of suspicious patterns and discrepancies that may indicate illicit trade-financing and money laundering schemes.

---

## Transaction Logs
- **Group:** Transaction & Payment Data
- **Code:** DS0019
- **Description:** Comprehensive records of financial transactions across all channels, capturing both account details (e.g., ownership, balances) and transaction data (e.g., timestamps, amounts, currencies, parties, transaction identifiers). This includes deposits, withdrawals, wire transfers, card payments, ATM usage, investment trades, remittances, gaming transactions, peer-to-peer transfers, cryptocurrency flows, and other forms of money movement.
- **Short Description:** Transaction Logs provide comprehensive financial transaction records across all channels, capturing essential account details, transactional timestamps, amounts, currencies, and identifying information. They are pivotal in AML/CFT adversarial threat modeling by enabling the detection of suspicious patterns, tracing the flow of funds, and strengthening compliance monitoring.

---

## Trust Information and Accounts
- **Group:** Corporate & Ownership Data
- **Code:** DS0012
- **Description:** Comprehensive information about trusts, including their structure, beneficiaries, trustees, associated financial accounts, transaction histories, and legal documentation. This data helps verify the legitimacy of trust-related activities and confirm the identities of key parties.
- **Short Description:** Trust Information and Accounts provides detailed data on the structure, beneficiaries, trustees, and financial histories of trusts, enabling thorough validation of trust-related activities. This information is critical for verifying identities, detecting suspicious transactions, and mitigating money laundering or terrorist financing risks.

---

## Virtual Asset Service Provider (VASP) Data
- **Group:** Transaction & Payment Data
- **Code:** DS0038
- **Description:** Data from Virtual Asset Service Providers, including detailed logs of digital asset transactions such as amounts, timestamps, wallet addresses, sender and receiver information, and associated account details, as well as user activity within cryptocurrency exchanges (e.g., trading volumes, order details, and user behaviors).
- **Short Description:** VASP data delivers granular insight into digital asset transaction patterns, user accounts, and exchanges, enabling detection of suspicious cryptocurrency activities. This detailed transactional and user behavior information is critical for identifying and mitigating money laundering and terrorist financing risks in virtual asset ecosystems.

---
