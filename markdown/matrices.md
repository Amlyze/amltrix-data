# Matrices

## [Money Laundering](https://framework.amltrix.com/matrices/amltrix-ml)

**Description:**
Money laundering is the multi-step, cyclical process in which criminals conceal the origins of funds acquired through illegal activities (e.g., fraud, corruption, organized crime) by moving them into the legal financial system under a guise of legitimacy. In the context of AMLTRIX’s adversarial threat model, these activities extend beyond the traditional stages of placement, layering, and integration to encompass early infiltration (access facilitation), operational evasion, concealment mechanisms, and post-integration asset protection—recognizing that criminals can reuse or cycle between these phases as they adapt to avoid detection.



### Tactics

- [Illicit Acquisition](https://framework.amltrix.com/tactics/ML.TA0001) — **Acquisition** and sustainment of illicit funds encompasses both the foundational stage of generating criminal wealth through predicate offenses and the strategic reinvestment of illicit proceeds back into ongoing criminal enterprises. Initially, adversaries accumulate illicit capital via profitable unlawful activities—including fraud, corruption, narcotics trafficking, cybercrime, and theft—forming the economic base that facilitates subsequent money laundering operations. These illicit funds, when successfully concealed at inception, significantly complicate downstream tracing efforts and enable deeper infiltration into legitimate financial systems.

Beyond mere acquisition, adversaries actively reinvest and channel funds back into sustaining and expanding their criminal networks. By recycling illicit proceeds to cover operational costs, procure resources, upgrade capabilities, and finance new illicit ventures, criminals ensure a continuous, self-perpetuating financial loop. Cyclical reinvestment significantly strengthens criminal infrastructure, facilitating increasingly sophisticated methods of generating and laundering further illicit proceeds. AML professionals must, therefore, not only target initial acquisition channels but also understand and disrupt this cyclical financial flow. Effective detection relies heavily on identifying suspicious reinvestment patterns, ongoing irregular asset flows, and the continuous reappearance of previously identified illicit funds within criminal operational contexts.
- [Concealment Mechanisms](https://framework.amltrix.com/tactics/ML.TA0002) — Establishment of concealment mechanisms involves constructing or employing structures, entities, or organizational layers specifically designed to mask the illicit origin or true ownership of criminal proceeds. By introducing distance between the assets and the underlying crime, adversaries minimize the outward visibility of potentially suspicious transactions. These mechanisms often span multiple jurisdictions and incorporate legal or corporate complexities—such as shell companies or layers of nominee ownership—to hinder straightforward tracing of beneficial owners. Detecting these concealment arrangements is a priority for AML efforts, as they can seamlessly blend with routine corporate or financial activities, enabling criminals to embed their illicit funds behind a veneer of legitimacy. Once entrenched, these deceptive structures underpin subsequent laundering stages by offering seemingly lawful gateways for further layering, transfers, or eventual integration into the legitimate financial system.
- [Operational Evasion](https://framework.amltrix.com/tactics/ML.TA0003) — Evasion and operational security entails a range of measures aimed at protecting the secrecy and inner workings of illicit financial operations. By segmenting tasks, compartmentalizing knowledge among co-conspirators, and carefully choreographing the transfer and storage of illicit assets, adversaries aim to stay ahead of investigators and reduce vulnerabilities. Criminals can also fine-tune the timing and methods of their financial movements to mask anomalies and prevent detection. By maintaining strict operational security, money launderers mitigate the risk of exposure, safeguarding themselves and their networks across all stages of the laundering continuum. A lapse in operational security, by contrast, can unravel extensive efforts to conceal illicit proceeds.
- [Access Facilitation](https://framework.amltrix.com/tactics/ML.TA0004) — Access facilitation is the process of establishing reliable entry points into legitimate or less-regulated financial avenues with minimal oversight that could expose illicit transactions. By exploiting regulatory ambiguities or weak compliance regimes, adversaries secure channels to deposit, transfer, and store funds without raising suspicion. These channels may include partnerships with complicit intermediaries, cultivation of professional or personal connections, or use of informal networks to limit the likelihood of intensive scrutiny. Securing and maintaining these reliable pathways remains a core strategic objective, as it ensures that criminals can continue to move illicit assets across financial systems with limited disruption. Undetected access facilitation lays the groundwork for subsequent steps in the laundering process, allowing adversaries to build complexity and concealment around their illegal proceeds.
- [Placement](https://framework.amltrix.com/tactics/ML.TA0006) — Placement marks the first point at which illicit funds converge with legitimate financial or commercial systems. The primary objective at this stage is to transform suspicious proceeds into transaction records that appear lawful, reducing the immediate visibility of criminal origins. Once placed, these assets can be maneuvered with less scrutiny, paving the way for deeper layers of laundering activity.

By embedding funds into accounts or enterprises that appear to operate legitimately, adversaries blend illicit assets into a broader, more conventional financial stream. Though details vary, the common thread is a calculated effort to ensure the funds are accepted in routine financial or commercial processes. This foundation increases the likelihood that subsequent layering schemes will evade detection.

From an AML perspective, placement is often considered the most vulnerable phase for criminals, as sudden or large-scale inflows may trigger red flags. Monitoring atypical deposit patterns or abrupt changes in account behavior serves as a frontline defense. However, once adversaries successfully navigate this phase, the funds become more intricately woven into the legitimate economy, complicating later detection efforts.
- [Layering](https://framework.amltrix.com/tactics/ML.TA0007) — Layering is characterized by a series of complex, often repeated, financial movements designed to obscure the criminal origin of funds. Adversaries reduce the strength of the audit trail by shifting assets through multiple accounts, entities, or jurisdictions, making it difficult for investigators to link them to the initial crime. Each layer further distances the funds from their illegal source, often relying on rapid transfers, currency exchanges, and sophisticated accounting maneuvers to create an intricate transactional web. Success at this stage greatly increases the difficulty of drawing direct connections between the funds and their underlying unlawful activities, paving the way for their gradual absorption into the legitimate financial system.
- [Integration](https://framework.amltrix.com/tactics/ML.TA0009) — **Integration**, often referred to as the final stage of money laundering, where illicitly acquired and extensively layered funds are embedded into legitimate economic activities, rendering their criminal origins indistinguishable from lawful wealth. After undergoing multiple complex transactions to obscure the source, adversaries channel these funds into mainstream investments, real estate, legitimate business operations, or financial instruments, ensuring that illicit proceeds appear fully legitimate and freely usable without arousing suspicion.

A critical dimension of integration is the deliberate **repatriation of illicit proceeds**—often transferring funds back into specific jurisdictions after they have been legitimized or cleaned abroad. Criminals execute this repatriation phase when they judge layering sufficient, seeking practical advantages such as enhanced control, ease of access, and exploitation of familiar regulatory or commercial environments. By returning integrated funds to jurisdictions of operational influence or strategic importance, adversaries leverage local networks, infrastructure, and business operations, solidifying their territorial control and direct oversight of previously concealed assets.

Distinct from merely obscuring asset origins, repatriation explicitly involves strategically timed cross-border movements designed to consolidate control and maximize operational utility in familiar or favorable regulatory contexts. For AML professionals, the integration and repatriation stages present particular challenges, requiring heightened vigilance and international coordination to identify transfers with subtly disguised histories, especially upon reentry into jurisdictions with weaker oversight or substantial criminal influence.
- [Asset Protection](https://framework.amltrix.com/tactics/ML.TA0010) — **Asset protection** denotes the safeguarding and preservation of illicitly acquired wealth against detection, seizure, or legal repercussions, especially once criminal proceeds have entered legitimate financial ecosystems. By strategically dispersing, restructuring, or relocating assets across multiple jurisdictions, financial instruments, or protective structures, adversaries reduce vulnerability to coordinated enforcement actions, complicating investigative tracing and minimizing the risk of asset freezing or confiscation. Additionally, a key aspect of effective asset protection involves proactive liquidity management—maintaining the ability to swiftly mobilize, convert, or redeploy illicit assets in response to emerging threats, investigative actions, or operational opportunities.

To ensure both long-term security and short-term flexibility, adversaries deliberately maintain illicit funds in readily convertible forms or highly liquid instruments, preventing assets from becoming locked in illiquid investments or prolonged holding patterns. Sudden shifts in transactional patterns, frequent cross-jurisdictional conversions, and carefully timed asset liquidations typify sophisticated asset protection and liquidity management strategies. When successfully implemented, these combined approaches provide criminals not only with long-term financial security and reduced susceptibility to law enforcement scrutiny but also decisive operational agility, enabling rapid adjustments to investigative pressures or changing financial environments. For AML professionals, effective detection of these tactics necessitates vigilant cross-border collaboration, sophisticated transaction monitoring, and an in-depth understanding of complex corporate ownership structures and transactional dynamics to unmask the layered beneficial ownership and fluid movement of criminal assets.

---

## [Terrorism Financing](https://framework.amltrix.com/matrices/amltrix-tf)

**Description:**
> ⚠️ **Early-Stage Draft**
>
> This matrix represents an exploratory outline of possible tactics and adversarial objectives related to terrorism financing (TF). 
> It is not yet supported by techniques or indicators, and active development is not currently in progress.  
> **Feedback and expressions of interest from the community are welcome** to help guide future prioritization.

Terrorism financing involves acquiring, managing, and moving funds from both legitimate and illicit sources to support terrorism activities and organizations. This financial process may utilize conventional methods such as donations or lawful businesses, as well as fraudulent schemes, criminal enterprises, and underground networks like hawala. Funds are directed toward recruitment, training, propaganda, logistical support, and execution of attacks. Within adversarial frameworks like kill-chain models, TF comprises diverse tactics including infiltration of legitimate financial institutions and employing layered transactions to evade law enforcement and regulatory detection.

In the AMLTRIX adversarial framework, terrorism financing is modeled distinctly from money laundering, highlighting unique tactics and strategic financial objectives. These tactics aim not only to channel resources effectively toward operational goals but also to ensure the long-term resilience and adaptability of terrorist entities.

The outlined matrix below presents seven foundational tactics, each reflecting stages in the financial lifecycle of terrorist organizations. These tactics provide a conceptual foundation for future development of detection techniques, indicators, and analytical frameworks:

### **Draft Terrorism Financing Tactics Overview**

| **Tactic** | **Description** |
| --- | --- |
| **1. Establishing Funds Collection** | Creating stable inflows via legitimate or illicit channels, such as charities, crowdfunding, businesses, or criminal activities, to sustain fundraising. |
| **2. Fundraising** | Actively increasing financial resources through legal self-financing, criminal enterprises, external support, or manipulation of non-profits. |
| **3. Legitimation** | Gaining credibility and social acceptance by integrating with lawful domains—business, religious affiliations, propaganda, cultural events—to mask financial activities and attract additional funds. |
| **4. Money Movement** | Transferring funds secretly through formal and informal networks like banking, remittances, hawala, cryptocurrency, and physical smuggling to conceal origins and destinations. |
| **5. Value Storage** | Securing funds in discreet, stable assets such as real estate, precious metals, digital wallets, or decentralized finance tools to retain liquidity and minimize detection risk. |
| **6. Resource Procurement and Expenditure** | Directing resources towards operational necessities, including weaponry, communications, logistics, personnel recruitment, and strategic outreach. |
| **7. Operational Continuity** | Ensuring ongoing survival by diversifying funding methods, embedding redundancy, preparing successors, and adapting financial practices to circumvent countermeasures.

### Tactics

- [Fundraising](https://framework.amltrix.com/tactics/TF.TA0009) — Once a funds collection channel is established, this tactic encompasses the methods utilized to actively increase the amount of financial resources available. This may include expanding criminal operations, diversifying funding sources, or implementing sophisticated financial schemes to maximize profits.

**Examples**: 
- Self-Financing through Legal Means: Members may utilize salaries, savings, or legal businesses.
- Criminal Activities: These can range from drug trafficking and robbery to illegal arms sales and extortion.
- External Support: Funding can come from state sponsors, other terrorist organizations, or diaspora communities.
- Exploiting Non-Profit Organizations (NPOs)
- Direct Solicitation and Donations
- External Support (State sponsors, other terrorist organizations, diaspora communities)


- [Money Movement](https://framework.amltrix.com/tactics/TF.TA0010) — This tactic focuses on the strategies and techniques used to transfer funds in a covert and efficient manner. It includes utilizing both formal financial institutions, such as banks and remittance services, and informal channels, such as hawala networks, digital currencies, and physical cash smuggling. The goal is to obscure the origin and destination of funds, making it difficult to track and disrupt financial flows. 

Financial institutions monitor transactions for any unusual money flows, especially those involving remittance services, international wire transfers, digital currencies, and other financial channels that can be exploited. Behavioral indicators largely overlap with indicators of money laundering. 

**Examples**:
 - Cash Smuggling: This involves physically transporting large sums of cash across borders.
 - Money Service Businesses: These offer quick and relatively anonymous ways to transfer funds globally.
 - Formal Banking Systems: While facing stricter controls, banks can still be exploited for money transfers.
 - Enhancement: Consider adding the following sub-framework.out_tactics:
- Informal Value Transfer Systems: This includes Hawala networks, which operate outside traditional financial systems.
- Exploiting New Technologies: Terrorist groups may increasingly leverage cryptocurrencies and online payment platforms to move money.

- [Legitimation](https://framework.amltrix.com/tactics/TF.TA0011) — This tactic involves creating a perception of trustworthiness and acceptability within society and legal frameworks to mask the true nature of terrorist financing operations. This may include using legitimate businesses as a cover, engaging in seemingly philanthropic activities, or leveraging existing social or political structures to gain acceptance.

**Examples**:
 - Investing in Legitimate Businesses
 - Strategic Communication and Propaganda
 - Exploiting Religious and Cultural Practices
 - Establishing a non-profit organization.
 - Strategic Communication and Propaganda: Terrorist groups use propaganda to legitimize their cause and attract financial support.
 - Exploiting Religious and Cultural Practices: Utilizing religious institutions or practices like Zakat can provide a sense of legitimacy and obligation for donors.

- [Establishing Funds Collection](https://framework.amltrix.com/tactics/TF.TA0012) — This tactic focuses on securing a reliable and sustainable avenue for gathering financial resources, rather than the immediate act of acquiring funds. This involves identifying and setting up systems that facilitate the ongoing inflow of money, whether through legitimate means like charitable donations and business ventures or illicit activities such as extortion or criminal networks.

Legal channels can include:
 - Charities and NPOs: Terrorist organizations can exploit legitimate charities and NPOs to raise and move funds. They may pose as legitimate entities, exploit existing entities as conduits, or divert funds intended for legitimate purposes.
 - Crowdfunding: Terrorist organizations can use crowdfunding platforms to solicit donations from a large number of people. This can be done through dedicated platforms, social media, or other online channels.
 - Businesses: Terrorist organizations can establish or invest in legitimate businesses to generate income. These businesses can range from small shops to large corporations.

Illegal channels can include:
 - Criminal activities: Terrorist organizations can engage in a wide range of criminal activities to generate funds, including drug trafficking, smuggling, extortion, and kidnapping for ransom.
 - State sponsorship: Some terrorist organizations receive funding from states. This funding can be provided directly or indirectly, through the provision of weapons, training, or other support.

Once a terrorist organization has established a funds collection channel, it can then use it to collect funds.
- [Value Storage](https://framework.amltrix.com/tactics/TF.TA0013) —  This tactic addresses the methods used to safeguard accumulated funds while maintaining their value and minimizing the risk of detection. It encompasses traditional methods such as investing in assets like gold, precious metals, real estate, and utilizing financial instruments. Additionally, it includes modern techniques like employing cryptocurrencies and utilizing decentralized financial networks for storing value. This tactic is important for maintaining financial stability and liquidity.

**Examples**:
 - Holding Cash: This is a common method, especially for smaller cells or those operating in unstable environments.
 - Investing in Assets: Terrorist organizations may store value in real estate, precious metals, or businesses.

- [Resource Procurement and Expenditure](https://framework.amltrix.com/tactics/TF.TA0014) — This tactic focuses on the strategic allocation of funds for acquiring resources that directly support terrorist operations. This includes financing logistical requirements, procuring weapons and equipment, maintaining communication networks, funding recruitment efforts, and covering operational costs.

**Examples**:
 - Purchasing Weapons and Explosives: This is a primary expenditure for many terrorist groups.
- Operational Costs: This includes travel expenses, communication devices, and paying recruits.
- Propaganda and Recruitment: Terrorist groups invest in producing and disseminating propaganda materials.
- Investing in Legitimate Businesses: This serves both as a source of income and a cover for other activities.
- Social Welfare Programs: Terrorist organizations sometimes provide social services to gain popular support and recruit members
- [Operational Continuity](https://framework.amltrix.com/tactics/TF.TA0015) — This tactic emphasizes the proactive measures taken by terrorist organizations to adapt to changing circumstances and counter-terrorism efforts. It encompasses strategies for maintaining financial stability, diversifying funding sources and transaction channels, adjusting operational methods, and building resilience against disruptions.

**Examples**:
 - Developing Redundant Financial Networks: This helps mitigate disruptions caused by law enforcement actions.
- Training and Succession Planning: This ensures the transfer of knowledge and skills to new members.
- Adapting to Changing Circumstances: Terrorist groups must be able to adapt to evolving counter-terrorism measures and global events.

---

## [Sanctions Evasion](https://framework.amltrix.com/matrices/amltrix-se)

**Description:**
> ⚠️ **Early-Stage Draft**
>
> This matrix represents an early-stage, exploratory outline of possible tactics and adversarial objectives for sanctions evasion.  
> It is not yet supported by techniques or indicators, and active development is not currently in progress.  
> **Feedback and expressions of interest from the community are welcome** to help guide future prioritization.

Sanctions evasion is the deliberate circumvention of national or international economic and trade restrictions targeting specific individuals, entities, or states. Evasion efforts span across corporate structuring, trade manipulation, falsified documentation, and strategic use of weak regulatory environments.

In the AMLTRIX adversarial framework, these behaviors are framed as **tactical objectives** pursued by sanctioned actors and their enablers. Each tactic corresponds to a distinct mode of evasion, providing the foundation for eventual mapping to detection techniques and red flags.

### **Draft Sanctions Evasion Tactics**

| **Tactic** | **Description** |
|-----------|-----------------|
| **Obfuscation of Identity and Ownership** | Creating layers of front companies, nominee directors, and trusts to obscure who truly controls sanctioned assets or entities. This defeats basic due diligence and frustrates beneficial ownership tracing. |
| **Manipulation of Trade Transactions** | Tampering with invoices, cargo descriptions, or shipping routes to hide the origin, value, or nature of goods. Adversaries may transship through neutral countries or falsify end-use declarations. |
| **Exploitation of Financial Systems** | Leveraging complex financial networks, correspondent banking, MSBs, or digital assets to move money while bypassing sanctions filters and transaction monitoring systems. |
| **Deceptive Information and Documentation** | Submitting falsified documents (e.g., KYC, maritime tracking, permits) to obscure the nature of entities or transactions and mislead regulatory checks. |
| **Exploitation of Jurisdictional Vulnerabilities** | Conducting operations in regions with lax or inconsistent sanctions enforcement, such as offshore centers, free trade zones, or non-cooperative states. |
| **Continuous Adaptation and Operational Security** | Frequently evolving evasion methods—such as switching communication protocols, rotating front companies, and tracking regulatory shifts—to stay ahead of enforcement efforts. |

### Tactics

- [Obfuscation of Identity and Ownership](https://framework.amltrix.com/tactics/SE.TA0024) — Concealing the true identities of sanctioned individuals or entities to bypass sanctions controls.

Example Techniques:
 - Creating shell companies and complex corporate structures
 - Using front companies and nominees
 - Employing trusts and legal arrangements to hide beneficial ownership
- [Manipulation of Trade Transactions](https://framework.amltrix.com/tactics/SE.TA0025) — Altering trade practices to disguise the origin, destination, or nature of goods and funds.

Example techniques:
 - Falsifying invoices and shipping documents
 - Under-invoicing or over-invoicing goods
 - Transshipment through third countries
 - Mislabeling goods to avoid detection
- [Exploitation of Financial Systems](https://framework.amltrix.com/tactics/SE.TA0026) — Utilizing financial networks and payment systems to move funds covertly.

Example techniques:
 - Using correspondent banking relationships
 - Employing non-traditional payment methods (e.g., cryptocurrencies)
 - Structuring transactions to evade detection thresholds
 - Utilizing money service businesses in high-risk jurisdictions
- [Deceptive Information and Documentation](https://framework.amltrix.com/tactics/SE.TA0027) — Providing false or misleading information to financial institutions and regulatory bodies.

Example Techniques:
 - Submitting falsified KYC documents
 - Misrepresenting the end-use or end-user of goods
 - Altering vessel tracking data in maritime transactions
 - Using forged licenses or permits
- [Exploitation of Jurisdictional Vulnerabilities](https://framework.amltrix.com/tactics/SE.TA0028) — Leveraging countries with weak sanctions enforcement or regulatory oversight.

Example techniques:
 - Operating through offshore financial centers
 - Using free trade zones with lax controls
 - Engaging financial institutions in non-cooperative jurisdictions
 - Exploiting gaps in international regulatory frameworks
- [Continuous Adaptation and Operational Security](https://framework.amltrix.com/tactics/SE.TA0029) — Adapting methods to avoid detection and maintain the ability to circumvent sanctions over time.

Example techniques:
 - Switching communication channels and encryption methods
 - Regularly changing company names and corporate structures
 - Monitoring regulatory updates to adjust strategies
 - Training staff on evasion techniques

---

## [Proliferation Financing](https://framework.amltrix.com/matrices/amltrix-pf)

**Description:**
> ⚠️ **Early-Stage Draft**
>
> This matrix represents an early-stage, exploratory outline of possible tactics and adversarial objectives for proliferation financing.  
> It is not yet supported by techniques or indicators, and active development is not currently in progress.  
> **Feedback and expressions of interest from the community are welcome** to help guide future prioritization.

Proliferation financing is the financial underpinning of efforts to develop, acquire, or transfer weapons of mass destruction (WMD) and their delivery systems. This often involves dual-use goods and highly covert transactional activity, making detection difficult. Threat actors exploit complex trade networks, regulatory gaps, front companies, and misinformation to obscure funding channels and avoid sanctions.

In AMLTRIX, proliferation financing is modeled as an adversarial financial behavior set that overlaps partially with sanctions evasion and money laundering—but has distinct strategic and tactical dimensions tied to WMD program enablement.

### **Draft Proliferation Financing Tactics**

| **Tactic** | **Description** |
|-----------|-----------------|
| **Fundraising for WMD Programs** | Adversaries generate and sustain funding via both legal and illicit streams—such as state budgets, commercial activities, non-profits, and cybercrime—to support WMD development and procurement. |
| **Legitimization of Illicit Funds** | Illicit gains are blended into the lawful economy by investing in high-value assets or businesses, obscuring their origins and allowing repurposing for proliferation-related spending. |
| **Fund Movement** | Cross-border layering of transactions through financial institutions and informal networks enables obfuscation of fund trails and circumvention of detection systems. |
| **Exploitation of Regulatory Gaps** | Actors leverage inconsistencies in international AML/CFT standards, exploiting informal systems or non-cooperative jurisdictions to move funds undetected. |
| **Resource Acquisition** | Funding is channeled into the acquisition of physical or financial resources necessary for proliferation, often disguised as lawful trade or business activity. |
| **Engagement in Misinformation and Disinformation** | Strategic narratives are deployed to confuse oversight efforts—misleading regulators, investigators, or public narratives about the source, purpose, or end-use of funds and goods. |
| **Structural Legitimation** | Front companies and co-opted legitimate businesses serve as financial façades, enabling movement and receipt of funds while appearing compliant. |
| **Obfuscation of Financial Transactions** | Sophisticated, layered transaction chains are designed to mimic legitimate business operations, blending illicit funds into complex financial flows that hinder tracing back to proliferation objectives. |

### Tactics

- [Fundraising for WMD Programs](https://framework.amltrix.com/tactics/PF.TA0016) — Establishing diverse channels for generating financial resources through both legitimate and illicit means, ensuring a sustainable flow of funds for proliferation activities. This includes exploiting legal business fronts, non-profit organizations, and informal financial systems.

This can be achieved through various means, both licit and illicit:
 - State budgets: Some countries may allocate funds from their national budgets towards WMD programs.
 - Commercial activities: Proliferators might engage in seemingly legitimate commercial activities to generate revenue that can be diverted towards WMD programs. This might involve exploiting natural resources or engaging in international trade.
 - Illicit activities: Criminal activities, such as drug trafficking, arms smuggling, or cybercrime, can provide a source of funding. North Korea, for instance, has been linked to cyberattacks targeting financial institutions and cryptocurrency exchanges.
- [Legitimization of Illicit Funds](https://framework.amltrix.com/tactics/PF.TA0017) — Incorporating illicit funds into the legitimate economy through investments in high-value assets, businesses, or financial instruments. This tactic seeks to blend criminal proceeds with legitimate revenues, making it challenging to trace the origins of the funds. 
- [Fund Movement](https://framework.amltrix.com/tactics/PF.TA0018) — Utilizing complex financial transactions and cross-border transfers to obscure the origins and destinations of funds. This involves layering, using multiple jurisdictions, and exploiting regulatory gaps to avoid detection by financial institutions and authorities.
- [Exploitation of Regulatory Gaps](https://framework.amltrix.com/tactics/PF.TA0019) — Identifying and taking advantage of weaknesses in AML/CFT frameworks across different jurisdictions to facilitate proliferation financing activities. This includes leveraging differences in regulatory standards and utilizing informal financial systems to bypass traditional oversight.

- [Resource Acquisition](https://framework.amltrix.com/tactics/PF.TA0020) — Securing financial or material resources needed for proliferation activities, often through both legitimate and illicit means.
- [Engagement in Misinformation and Disinformation Campaigns](https://framework.amltrix.com/tactics/PF.TA0021) — Utilizing misinformation framework.out_tactics to divert attention from true financial activities, creating narratives that cloud investigative efforts. This involves manipulating information sources to mislead regulators and financial institutions.
- [Structural Legitimation](https://framework.amltrix.com/tactics/PF.TA0022) — Establishing or co-opting legitimate-seeming businesses to mask illicit activities and facilitate the movement of funds. These entities provide a cover for financial transactions related to proliferation financing, complicating detection efforts.
- [Obfuscation of Financial Transactions](https://framework.amltrix.com/tactics/PF.TA0023) — Employing complex and layered financial transactions to obscure the flow of funds and prevent tracing back to proliferation financing activities. This tactic necessitates advanced knowledge of financial systems and may involve multiple intermediary transfers, akin to layering in money laundering. Might involve blending illicit funds with legitimate business operations to create a facade of legality and facilitate further financial transactions.

---

## [Fraud](https://framework.amltrix.com/matrices/amltrix-fraud)

**Description:**
> ⚠️ **Early-Stage Draft**
> 
> This matrix represents an early-stage, exploratory outline of adversarial tactics employed in financial fraud.  
> It is not yet supported by techniques or behavioral indicators, and active development is not currently in progress.  
> **Feedback and expressions of interest from the community are welcome** to help guide future development and prioritization.

Within **AMLTRIX**, **fraud** is defined as a deliberate financial crime involving deceptive practices intended to unlawfully obtain funds, financial assets, financial services, or monetary advantages from individuals, companies, institutions, or markets. Fraud perpetrators intentionally manipulate trust, exploit systemic vulnerabilities, falsify identities or documentation, or misrepresent material facts to induce victims—both consumers and organizations—into initiating or authorizing financial transactions or activities under false pretenses.

Fraud schemes within the financial sector encompass a broad spectrum of activities, such as investment fraud, identity fraud, payment fraud, insurance fraud, lending fraud, vendor invoicing fraud, social engineering attacks, and insider fraud. Adversaries range from opportunistic individuals to highly organized criminal networks employing sophisticated infrastructure and operational planning, often leveraging digital platforms and financial technologies to maximize their reach and impact.

### **Core Characteristics of Financial Fraud under AMLTRIX:**

1. **Financially Motivated Deception**  
   Fraud fundamentally involves manipulating victims’ perceptions—whether individuals or institutions—to voluntarily authorize financial transactions based on false or misleading information. Fraudsters strategically exploit financial trust relationships inherent in banking, investment, insurance, and payment ecosystems.

2. **Voluntary Action under False Pretenses**  
   Unlike direct theft or cyber intrusions, fraud typically leverages the victims’ own actions or authorizations. Victims willingly initiate transactions, disclose sensitive financial details, or grant access believing they are acting legitimately, significantly delaying the detection and intervention process.

3. **Systemic and Individual Vulnerability Exploitation**  
   Fraudsters proactively seek and exploit procedural weaknesses, compliance gaps, ineffective customer authentication processes, or psychological vulnerabilities like greed, urgency, or fear, to successfully facilitate deceptive financial schemes.

4. **Monetary or Financial Asset Focus**  
   Fraud schemes are inherently directed at extracting monetary value, obtaining unauthorized financial access or benefits, or illegitimately diverting financial resources or financial services away from rightful beneficiaries.

5. **Sophisticated Concealment Techniques**  
   Financial fraud involves deliberate obfuscation—such as transaction structuring, layered money transfers, false merchant categorization, or rapid conversion of funds—to disguise the illicit origins of fraudulent proceeds, complicate detection efforts, and frustrate investigative processes.

6. **Linkages to Money Laundering**  
   Funds or financial assets obtained through fraud typically undergo systematic laundering processes—including, but not limited to, placement, layering, and integration—to obscure their illicit origins, avoid detection by financial controls, and facilitate their reintroduction into the legitimate financial system. Fraud proceeds frequently transition into [complex money laundering schemes](https://framework.amltrix.com/matrices/amltrix-ml) modeled comprehensively beyond the traditional PLI (Placement-Layering-Integration) paradigm.

7. **Adaptation, Retargeting, and Persistence**  
   Fraudsters continuously adapt tactics based on previous successes or enforcement pressures. They retarget vulnerable customers or institutions, refine schemes based on detected weaknesses, scale operations through recruitment of intermediaries (such as money mules or insiders), and recycle successful fraudulent methodologies across financial jurisdictions, products, or customer segments.

Framing fraud explicitly as a **financial crime** within the AMLTRIX context provides clarity for financial institutions, regulators, law enforcement, compliance teams, and investigators. It emphasizes fraud’s adversarial, modular nature, allowing precise definition of each fraudulent tactic within the broader fraud lifecycle or kill-chain, thus significantly enhancing detection, prevention, and enforcement capabilities across the financial sector.


## **Draft Fraud Tactics**

| **Name**                           | **Description**                                                                                                                                                                                                                                           |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Reconnaissance & Planning**      | Systematically gathering intelligence about targets, processes, and vulnerabilities, then refining strategies for the upcoming fraud operation. Fraudsters are looking for weak links, data, or organizational blind spots to exploit.                     |
| **Infrastructure & Credential Setup** | Establishing the technical and operational foundation (e.g., synthetic IDs, compromised logins, spoofed websites) to support the fraud scheme. Criminals are preparing malicious domains, forging user accounts, or acquiring stolen credentials.        |
| **Victim Targeting & Profiling**   | Pinpointing specific individuals or institutions most susceptible to fraud, using analytics, data leaks, or insider knowledge. Fraudsters are choosing high-value or easily misled victims to increase the likelihood and scale of success.               |
| **Trust Exploitation**             | Lowering victims’ defenses by impersonating authority figures, forging emotional bonds, or otherwise leveraging perceived credibility. Criminals are creating scenarios that cause victims to ignore normal cautions or controls.                         |
| **Deceptive Execution**            | Directly carrying out the fraud scheme—such as sending phishing emails, making fake phone calls, or delivering false invoices—so victims comply with the fraudulent instructions. Criminals are orchestrating the immediate con that finalizes harm.     |
| **Transaction Facilitation**       | Directing or funneling fraudulently obtained assets through various instruments or accounts. Criminals are making sure stolen funds move from the victim’s control to an account they can access, often using multiple hops or mules.                   |
| **Monetization & Disbursement**    | Turning the stolen assets into spendable, transferable, or salable forms—such as withdrawing cash, converting funds to cryptocurrency, or selling compromised card data. Criminals are ensuring they can realize the financial benefits quickly.         |
| **Concealment & Evasion**          | Masking or erasing traces of the fraud—altering logs, wiping malware footprints, rotating IP addresses—to delay investigative response. Criminals are reducing evidence trails to extend the window of opportunity.                                      |
| **Extended Laundering & Asset Protection** | Ensuring long-term protection and usability of proceeds from fraud through sophisticated money laundering schemes beyond a quick cash-out.                                                                                                                   |
| **Persistence & Retargeting**      | Reusing successful fraud methods—either on the same victims or new ones—by automating scripts, adapting social engineering angles, or waiting until vigilance subsides. Criminals are scaling their operation to repeatedly benefit from proven tactics. |

### Tactics

- [Reconnaissance & Planning](https://framework.amltrix.com/tactics/FRAUD.TA0001) — Systematically gathering intelligence about targets, processes, and vulnerabilities, then refining strategies for the upcoming fraud operation. Fraudsters are looking for weak links, data, or organizational blind spots to exploit.

**Examples:**

* Scanning financial institution websites to find disclosure of security measures.

* Researching publicly available victim data on social media for phishing.

* Mapping payment authorization thresholds or fraud detection measures.
- [Infrastructure & Credential Setup](https://framework.amltrix.com/tactics/FRAUD.TA0002) — Establishing the technical and operational foundation (e.g., synthetic IDs, compromised logins, spoofed websites) to support the fraud scheme. Criminals are preparing malicious domains, forging user accounts, or acquiring stolen credentials.

**Examples:**

* Setting up fraudulent merchant accounts or fake business websites.

* Creating synthetic identities or fake employee profiles.

* Deploying phishing sites or malware-distribution networks.
- [Victim Targeting & Profiling](https://framework.amltrix.com/tactics/FRAUD.TA0003) — Pinpointing specific individuals or institutions most susceptible to fraud, using analytics, data leaks, or insider knowledge. Fraudsters are choosing high-value or easily misled victims to increase the likelihood and scale of success.

**Examples:**

* Using data analytics to pinpoint financially vulnerable groups.

* Identifying companies with weak vendor authentication practices.

* Profiling users based on transaction habits susceptible to social engineering.
- [Trust Exploitation](https://framework.amltrix.com/tactics/FRAUD.TA0004) — Lowering victims’ defenses by impersonating authority figures, forging emotional bonds (e.g., romance), or otherwise leveraging perceived credibility. Criminals are creating scenarios that cause victims to ignore normal cautions or controls.

**Examples:**

* Impersonating bank representatives in scam phone calls.

* Exploiting relationships via romance scams or affinity fraud.

* Leveraging trust in known vendors to authorize fraudulent payments.
- [Deceptive Execution](https://framework.amltrix.com/tactics/FRAUD.TA0005) — Directly carrying out the fraud scheme—such as sending phishing emails, making fake phone calls, or delivering false invoices—so victims comply with the fraudulent instructions. Criminals are orchestrating the immediate con that finalizes harm.

**Examples:**

* Sending convincing phishing emails prompting fraudulent wire transfers.

* Manipulating invoices to redirect legitimate payments.

* Conducting fake investment seminars or deceptive sales pitches.
- [Transaction Facilitation](https://framework.amltrix.com/tactics/FRAUD.TA0006) — Directing or funneling fraudulently obtained assets through various instruments or accounts. Criminals are making sure stolen funds move from the victim’s control to an account they can access, often using multiple hops or mules.

**Examples:**

* Providing mule accounts for receipt and redistribution of stolen funds.

* Facilitating fraudulent payments through compromised payment processors.

* Redirecting legitimate financial flows through manipulated digital wallets.
- [Monetization & Disbursement](https://framework.amltrix.com/tactics/FRAUD.TA0007) — Turning the stolen assets into spendable, transferable, or salable forms—such as withdrawing cash, converting funds to cryptocurrency, or selling compromised card data. Criminals are ensuring they can realize the financial benefits quickly.

**Examples:**

* Rapidly withdrawing stolen funds from compromised accounts.

* Converting fraudulent crypto-assets into fiat currency.

* Selling stolen payment card data on dark web marketplaces.
- [Concealment & Evasion](https://framework.amltrix.com/tactics/FRAUD.TA0008) — Masking or erasing traces of the fraud—altering logs, wiping malware footprints, rotating IP addresses—to delay investigative response. Criminals are reducing evidence trails to extend the window of opportunity.

**Examples:**

* Using transaction structuring or "smurfing" to stay below reporting thresholds.

* Employing anonymized digital currency platforms for transactions.

* Frequently changing IP addresses or device fingerprints.
- [Extended Laundering & Asset Protection](https://framework.amltrix.com/tactics/FRAUD.TA0009) — Ensuring long-term protection and usability of proceeds from fraud through sophisticated money laundering schemes beyond a quick cash-out. 

**Examples:**

* Investing illicit funds into legitimate businesses or real estate.

* Employing complex layering via offshore accounts and shell companies.

* Coordinating professional money laundering networks to integrate stolen funds.

**Linkage to AMLTRIX Money Laundering Matrix:** Detailed [in](https://framework.amltrix.com/matrices/amltrix-ml) [AMLTRIX Money Laundering Matrix](https://framework.amltrix.com/matrices/amltrix-ml), extending beyond traditional PLI (Placement-Layering-Integration) stages by modeling more nuanced and sophisticated concealment and integration tactics.
- [Persistence & Retargeting](https://framework.amltrix.com/tactics/FRAUD.TA0010) — Reusing successful fraud methods—either on the same victims or new ones—by automating scripts, adapting social engineering angles, or waiting until vigilance subsides. Criminals are scaling their operation to repeatedly benefit from proven tactics.

**Examples:**

* Retargeting previous victims with new deceptive narratives.

* Maintaining persistent access to compromised accounts for recurring fraud.

* Re-engaging defrauded entities through altered schemes to extract further value.

---
