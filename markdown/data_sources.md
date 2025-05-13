# Data Sources

## [Account Activity Logs](https://framework.amltrix.com/data-sources/DS0001)

**Description:**
Detailed records of all actions within financial accounts, covering financial transactions and changes to account settings, including timestamps, user identifiers, and related metadata.

### Related Techniques
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Records internal notes, customer instructions, and incremental withdrawal requests.
- Reveals explicit instructions by account holders to split withdrawal amounts into smaller increments, aligning with structuring techniques.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Records all activities within customer accounts, including transaction frequencies, timestamp history, and usage patterns.
- Detects sudden increases in wire activity or abnormal timing, consistent with layering techniques in wire transfers.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Maintains granular records of account interactions, including transaction details, account setting changes, and corresponding timestamps. This helps detect: 

- Unusual outgoing transfers or sudden spikes in deposit volume consistent with coerced payments.
- Pattern shifts that indicate attempts to mask extorted funds, such as rapidly moving funds into front businesses or intermediary accounts.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Tracks sub-account creation, inter-account transfers, authorized signatories, and account setting changes.
- Facilitates detection of fragmented deposits or frequent transfers to multiple sub-accounts, highlighting potentially concealed flows of illicit money within real estate entities.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Contain all actions within a customer’s account, including balance adjustments and transaction attempts. Investigators identify unauthorized or unexplained modifications that indicate digital document or transaction tampering.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Detailed records of account actions and changes, including transaction timestamps and user-initiated modifications.
- Identifies rapid in-and-out fund movements or short holding durations indicative of layering strategies linked to IVTS.
- Strengthens internal investigations by providing granular insight into unusual activity patterns within accounts.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Shows all changes to account profiles (e.g., contact info, password resets), with timestamps and user identifiers.
- Identifies rapid or unusual modifications made immediately after a compromised login, supporting timely investigation of unauthorized account alterations.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Tracks changes in account permissions, signatories, and access across multiple accounts.
- Detects frequent additions or removals of regional agents without documented justification.
- Helps identify suspicious account management patterns indicative of intermediary-driven transactions.
- [Cash Deposits](https://framework.amltrix.com/techniques/T0004) — - Documents comprehensive account actions, including deposits, transfers, and user-initiated changes in real-time.
- Pinpoints suspicious deposit timing or repetitive deposit actions across multiple accounts or branches.
- Assists in reconstructing the sequence of placement steps when investigating layered cash flows.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Contains detailed records of all actions within financial accounts, including transaction events, setting changes, login timestamps, and user identifiers.
- Supports detecting unusual surges in micro-deposits or withdrawals that deviate from normal account usage patterns, helping identify micro-structuring strategies.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Captures updates to expense categories and financial records in accounting systems, including timestamps, user information, and details of modifications. This helps identify repeated reclassifications of personal expenses as business expenses, a hallmark of expense fraud schemes.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Captures changes in account settings, payment methods, and linked beneficiaries for unemployment claim disbursements, helping to detect frequent reconfigurations or suspicious alterations indicative of potential fraud or unauthorized access.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Records vendor account openings, profile changes, and associated logins with timestamps.
- Reveals suspiciously rapid vendor account creation followed by immediate invoice submissions, indicative of a fake vendor operation.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Track user actions within accounts, including the initiation or approval of fund transfers, changes to account settings, and timestamps.  
- Identify which officials or employees executed questionable entries or transfers, facilitating the attribution of suspicious activity to specific individuals.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Documents all account-level changes, including modifications to authorized users, traders, and owners. These logs help identify sudden or frequent reassignments of beneficial ownership, which is a hallmark of manipulation.

---

## [Adverse Media & Court Filings](https://framework.amltrix.com/data-sources/DS0003)

**Description:**
Aggregated records from media sources and official legal documents (e.g., court filings, lawsuits) highlighting negative news, legal actions, and alleged misconduct associated with individuals or entities.

### Related Techniques
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Collects negative news coverage, legal disputes, and court documents referencing individuals or entities involved in antiquities-related crimes, such as forged provenance or stolen artifacts. This helps identify high-risk parties and strengthens the investigation into potentially illicit cultural artifact transactions.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Aggregated records from media sources and legal documents highlighting negative news, lawsuits, or official proceedings.

This data may reveal publicized scandals or legal challenges involving diplomats or state officials, especially where immunity was invoked to avoid AML scrutiny.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Aggregated negative news coverage and official court records can highlight prior legal actions, past criminal behaviors, or lawsuits filed under different name variants. This information helps investigators uncover instances where offenders have attempted to conceal or alter their identities to avoid matching past adverse media or legal proceedings.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Compiles negative news stories, legal proceedings, and court documents involving individuals or entities. These records help investigators detect allegations of bribery, embezzlement, or personal misconduct, offering insights into possible corruption cases and justifying heightened scrutiny of the involved accounts.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Compiles negative news articles, legal actions, or court documents indicating potential wrongdoing by donors, staff members, or charitable entities.
- Flags key individuals associated with fraud, money laundering, or terrorist financing allegations.
- Alerts investigators to reputational and legal risks tied to a charity’s management or major funding sources.
- [Counterfeit Currency](https://framework.amltrix.com/techniques/T0092) — - Aggregates negative media reports, legal actions, and court rulings.
- Highlights customer involvement or potential links to known counterfeiting operations, aiding in risk assessment and investigation.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Aggregated records of negative news coverage and official legal documents (e.g., lawsuits, criminal charges) referencing individuals or entities. This data enables investigators to:

- Link suspicious deposit spikes to local reports of intimidation or threats, indicating possible extortion.
- Identify named persons or groups charged with or suspected of extortion, aligning deposit patterns with known criminal activity.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Aggregates negative news articles, legal actions, or lawsuits involving sponsors, sports clubs, or affiliated individuals.
- Helps uncover prior allegations of corruption, fraud, or money laundering, supporting enhanced due diligence on dubious sports sponsorship funding.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Aggregates press articles, lawsuits, and other public legal records highlighting alleged or confirmed misconduct. Negative media coverage or legal actions related to labor exploitation can indicate forced labor activity generating illicit proceeds.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Aggregates negative news stories, legal proceedings, and allegations involving persons or companies.
- Exposes reported arms trafficking activities, past charges, or ongoing investigations, enabling financial institutions to conduct enhanced due diligence and identify high-risk customers or transactions.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — - Aggregates negative media reports, legal documents, and criminal proceedings related to an individual.
- Flags customers under investigation or with prior convictions who are renting deposit boxes.
- Aids in enhanced due diligence for customers who may be concealing illicit assets.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — Aggregated records from media sources and official legal documents (e.g., court filings, lawsuits) highlight potential controversies or suspicious arbitration cases. These sources help detect repeated questionable settlements, verify inconsistencies in claimed disputes, and uncover negative patterns associated with arbitration participants, indicating possible manipulation of awards for money laundering.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Aggregates negative news/articles and official legal records involving individuals or entities.
- Discloses investigations, indictments, and convictions for illegal deforestation, wildlife trafficking, or related environmental offenses.
- Informs ongoing monitoring of high-risk clients or partners connected to environmental crime.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Aggregated reports, news articles, and legal documents link individuals or entities to corruption, bribery, or environmental crimes. By identifying subjects of negative coverage or legal actions related to timber permitting abuses, these sources assist in investigating illegal logging networks.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Gathers negative news coverage, legal proceedings, and allegations linked to entities or individuals.
- Uncovers any reported criminal affiliations, lawsuits, or regulatory actions that suggest the business may be acting as a front for illicit activities.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Aggregates negative news, legal actions, and misconduct allegations linked to individuals or entities.
- Helps uncover involvement in or past charges related to sex trafficking or sexual exploitation, informing enhanced due diligence.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Aggregates negative media reports, legal claims, or enforcement actions involving individuals or entities. This data assists investigators by:

- Identifying parties with a documented history of trade-based misconduct or fraudulent invoicing.
- Revealing potential links to past money laundering or other financial crimes.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Aggregated media findings and legal records indicate historical noncompliance or regulatory actions involving crypto ATM operators. This data helps identify high-risk operators who may permit large transactions, weak KYC, and other risky behaviors linked to money laundering through crypto ATMs.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Aggregates negative news stories, legal proceedings, and official court documents indicating allegations of wrongdoing or illicit activities.
- Reveals past or ongoing legal challenges faced by CBI/RBI applicants, assisting in identifying higher-risk individuals or entities seeking alternate residency or citizenship.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — Aggregated records from public and legal documentation (e.g., lawsuits, criminal charges, regulatory actions) highlight involvement in art fraud, price manipulation, or other suspicious practices. 

- These details allow investigators to identify individuals or entities with a history of questionable art dealings, aligning with the patterns of Art Market Manipulation.
- Specifically, by cross-referencing named parties and allegations in these records with ongoing or prior art transactions, compliance teams can flag potential vulnerabilities or previously concealed illicit activities.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Aggregates negative news and legal records indicating reported fraud, contested ownership, or suspicious valuations tied to freeport activity. Aids in uncovering prior allegations or legal actions related to high-value asset storage.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Compiles negative news and legal documents that may link NEP facilitators to criminal activities or watchlists. Investigators can verify whether individuals or entities repeatedly engaging in off-the-record exchanges appear in court filings or negative press.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Aggregates media reports and legal documents, highlighting previous sanctions, litigations, or allegations. Investigators use this data to identify links to sanctioned or high-risk individuals funneling illicit funds into businesses.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Aggregates negative news, publicly reported legal actions, lawsuits, and criminal proceedings involving individuals or entities.
- Directly aids in detecting applicants with histories of sanctions, fraud, or corruption seeking CBI/RBI to evade scrutiny.
- Enables AML professionals to assess reputational and legal risks tied to individuals who may exploit citizenship or residency programs to launder illicit proceeds.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Aggregates negative news, legal actions, and criminal records.
- Reveals prior minor offenses or financial vulnerabilities that indicate susceptibility to recruitment as cash mules.
- Allows investigators to correlate criminal histories with suspicious international travel or cash-carrying activity.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Aggregates negative media coverage, legal disputes, and official court documents involving individuals or entities. This information uncovers evidence of prior involvement in illegal mining, metal trafficking, or related corruption.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Aggregates court records, lawsuits, regulatory filings, and negative media coverage referencing professional intermediaries. This enables analysts to identify prior investigations, sanctions, or suspicious conduct associated with these professionals.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Consolidates negative news articles, legal actions, and court documents, revealing known or alleged involvement in counterfeit trade, relevant criminal proceedings, or regulatory violations.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Compiles negative news coverage, lawsuits, and legal actions involving individuals or entities. This helps identify prior allegations, ongoing litigations, or regulatory interventions against purported investment firms, signaling potential fraud risk or misconduct.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Aggregates news reports, legal actions, and regulatory findings on entities suspected of trade-based money laundering. This information flags parties previously involved in suspicious letter of credit activities or other high-risk trade finance schemes.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Provides:

- Negative news coverage referencing judicial corruption, suspicious rulings, or manipulative legal processes.
- Official legal documents (e.g., lawsuits, rulings, indictments) detailing key parties, case timelines, and outcomes.

How it supports AML detection:

- By cross-referencing news media and official court documentation, institutions can identify allegations of bribery or coerced rulings, potentially revealing the manipulation of legal outcomes to legitimize illicit funds via fraudulent judgments or settlements.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — Aggregated records of negative news, legal actions, and court proceedings can uncover alleged financial crimes or laundering schemes linked to entertainment companies or their principals. These records offer critical insights when evaluating sudden capital inflows or questionable offshore ownership structures.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Aggregate negative news, legal actions, or investigations linked to offshore gambling operators.
- Uncover hidden beneficial owners or prior enforcement actions signaling high AML risk.

This data helps investigators identify reputational and legal red flags associated with suspected laundering activities through offshore gambling businesses.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Consolidates negative news, lawsuits, and regulatory actions against individuals or entities.
- May reveal known involvement of professional facilitators setting up complex, multi-jurisdictional corporate structures.
- Helps identify higher-risk corporate formations or ongoing legal proceedings tied to money laundering activity.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Aggregates negative news coverage, legal actions, and court proceedings.
- Identifies individuals or entities previously implicated in fraud or misrepresentation, revealing heightened risk.
- Helps corroborate suspicious applications or transactions with prior legal disputes or criminal charges for fraud.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Aggregates negative news stories, legal actions, indictments, and court documents referencing misconduct and criminal complaints.
- Enables investigators to identify individuals or entities previously implicated in child exploitation, providing critical leads for AML monitoring and rapid escalation.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Aggregates negative media reports, lawsuit details, and legal actions involving individuals or entities.
- Identifies known or suspected involvement in wildlife trafficking, smuggling, or related illegal activities.
- Supports enhanced due diligence and ongoing monitoring of high-risk clients or transactions.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Aggregates negative news, legal documents, and lawsuits involving individuals or entities.
- Reveals prior legal actions or complaints against alleged social media 'employers' or recruiters.
- Supports AML detection of fraudulent job offers or ongoing scams, linking them to repeated patterns of money mule recruitment.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Aggregated negative news, legal documents, and court proceedings can highlight maritime hijackings, ransom negotiations, or associated prosecutions. This data helps identify risk indicators linked to entities or individuals suspected of piracy, enabling proactive AML measures.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Aggregates negative news coverage and legal documents detailing investigations, prosecutions, or alleged misconduct.
- Provides early warning of entities or individuals implicated in drug trafficking or related financial crimes.
- Supports enhanced due diligence by revealing public allegations or legal actions connected to narcotics networks.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Aggregate negative news coverage or legal proceedings involving individuals or entities.  
- Highlight allegations of corruption, ongoing lawsuits, or convictions that support investigative efforts into potential misappropriation of public funds.

---

## [Customs and Border Records](https://framework.amltrix.com/data-sources/DS0004)

**Description:**
Comprehensive records from customs and border authorities detailing the movement of goods and individuals, including imported and exported items, shipping routes, tariffs, and related documentation.

### Related Techniques
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Provides official data on individual cross-border movements, cargo details, and flagged irregular entries.
- Helps match financial transaction anomalies with potential physical smuggling activities, particularly where repeated undocumented crossings are involved.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Documents the movement of goods, shipping routes, and related customs declarations.

Although diplomatic pouches generally bypass standard inspection, these records can at least confirm declared shipments, frequencies, or any customs interactions that may hint at possible misuse of diplomatic channels for illicit asset transfers.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Includes official import/export data, shipping routes, and cargo declarations verified by customs authorities. By comparing declared goods and volumes with L/C documentation, investigators can uncover inconsistencies or inflated invoices indicative of red/green clause abuse.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Details import and export activity, including declared goods, shipping routes, and related documentation.
- Helps confirm whether shipments align with declared commodities, identifying potential misreporting of illicit goods.
- Provides a cross-reference point to detect inconsistencies between financial transactions and physical shipments.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Provides official data on cross-border movements of goods, including declared volumes, routes, and tariffs. This allows investigators to identify anomalies in repeated shipments, suspicious border crossings, and inconsistent commodity declarations that may suggest smuggling.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Contains official import/export data, shipping routes, and merchandise declarations.
- Allows comparison of declared agricultural goods against actual shipment volumes and routes.
- Identifies inconsistencies in product type or quantity that may indicate trade-based manipulation involving farming or livestock.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Provides official data from customs and border authorities on imported and exported goods, including declared contents, shipping routes, and tariffs.  
- Enables verification of repeated or cyclical shipment patterns inconsistent with genuine trade flows, helping identify potential carousel schemes where the same goods are re-imported and re-exported among related entities.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Contain official shipment data, including quantities, weights, declared values, and shipping routes.
- Enable verification of invoice values against actual goods shipped.
- Flag exports processed through higher-risk jurisdictions where oversight may be lax.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — Contain official import and export information, including product types, shipping routes, declared values, and tariffs. By cross-referencing these records with transaction and trade documentation data, investigators can detect discrepancies or inconsistencies indicative of Black Market Peso Exchange, such as under-invoicing, over-invoicing, or smuggling patterns.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Comprehensive records detail cross-border shipment movements, including declared cargo, tariffs, and inspection details. By tracking actual shipping routes, comparing declared contents with customs filings, and reviewing inspection outcomes, investigators can identify suspicious diversion patterns, hidden intermediaries, or inconsistent documentation indicative of illicit trade activity.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Contains comprehensive records of goods entering or leaving a country, details on shipping routes, bills of lading, and declared contents. This supports the detection of cross-border shipments of counterfeit pharmaceuticals and enables targeted AML investigations of illicit trade routes.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Includes official import/export logs, shipping routes, declared cargo details, and border inspection reports. By cross-referencing these records against declared timber volumes, species, and export permits, investigators can identify undeclared or mismatched shipments, revealing potential illegal logging activity and associated laundering of proceeds.
- [Commingling Environmental Crime Proceeds](https://framework.amltrix.com/techniques/T0057) — - Encompasses official records on cross-border movements of goods, shipping routes, and declared categories.
- Cross-checks declared exports or imports of environmental or wildlife products against actual shipments.

These records help detect misdeclared or concealed goods, identifying potential commingling of illicit shipments with legitimate trade flows.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Provides official records of individuals' cross-border movements, enabling the detection of multiple or inconsistent travel documents linked to the same person. Such data helps confirm whether a customer is using varying passports or nationalities for travel, which can signal higher money laundering risk in multi-citizenship identity schemes.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Provides official records from customs and border authorities detailing declared values, quantities, and routes of shipped goods.
- Cross-referencing these with invoice documentation helps uncover false or overstated shipments characteristic of invoice manipulation.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — Provides official import and export declarations, cargo manifests, and border-control logs, enabling verification that shipments actually took place and matched the declared routes or commodities in documentary collection transactions. This helps uncover nonexistent or misrepresented shipments often used to hide illicit financial flows.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Contains official import/export data from border authorities, including declared valuations, shipping routes, tariffs, and inspection outcomes.
- Enables cross-referencing of declared diamond shipments against actual customs filings, helping to identify forged documents, undisclosed re-exports, and potential misdeclarations.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Provides official trade manifests, customs export/import filings, shipping routes, and declared cargo details.
- Validates the actual physical movement of goods across borders, helping detect phantom shipments or duplicated routes indicative of circular trade schemes.
- [Pre-Shipment Finance Manipulation](https://framework.amltrix.com/techniques/T0072) — Provides official data on the cross-border movement of goods, including customs declarations, tariff classifications, and inspection results. By matching these records with financed export claims, investigators can confirm whether shipments actually occurred, exposing inconsistencies in declared quantities or values.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Documents import-export activities, including declared goods, routes, and involved parties.
- Enables identification of shipments that deviate from legitimate channels or are destined for sanctioned jurisdictions under false pretenses.
- [Daigou Networks](https://framework.amltrix.com/techniques/T0013.006) — Encompasses official import and export data, shipping routes, and related customs documentation, illuminating:

- Frequent use of informal or unregistered couriers for large quantities of consumer goods.
- Multiple shipping addresses or varying beneficiary names tied to the same entities.

These details allow AML teams to correlate irregular goods movements, repeated shippers, and declared values, revealing high-risk patterns consistent with Daigou networks.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Contains official records of cross-border movements of goods, including item descriptions, declared values, shipping routes, and customs forms.
- Allows investigators to detect inconsistencies in declared diamond shipments, identify unusual trans-shipment points, and verify if shipments bypass or misdeclare customs controls.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Documents the cross-border movement of goods and people, including shipping routes, imported/exported items, and related customs declarations.

- Helps identify suspicious shipments transiting conflict zones or embargoed jurisdictions, highlighting possible arms-related contraband hidden within declared cargo.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Official data on the movement of individuals and cash across international borders.
- Reveals instances where large sums of cash are physically transported to exploit off-book or unofficial exchange rates.
- Assists investigators in correlating unreported cross-border movements with subsequent suspicious currency conversions.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Official declarations, shipping routes, and import/export details that confirm actual goods crossing borders.
- AML Relevance: Enables verification of claimed cross-border shipments against official customs data, helping detect phantom or forged shipments in fictitious trade deals.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Documents the cross-border movement of goods, including declared values, shipping routes, and associated documentation.
- Supports detection of suspicious undervalued or misdeclared shipments of precious metals or luxury items indicative of high-value goods laundering.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Documents import and export declarations, shipping routes, and required certifications for jewelry.
- Comparing declared values to actual market prices and verifying missing or incomplete certificates (e.g., Kimberley Process) helps detect suspicious under- or over-valuation.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Includes official import/export data, shipping routes, commodity classifications, and declared values. This data helps investigators:

- Detect repeated shipments of the same commodities without clear commercial rationale.
- Analyze cross-border flows for suspicious patterns, such as unclaimed or returned goods.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Documents cross-border movements of goods and individuals, including declared items, shipping routes, and tariffs.
- Assists in identifying undeclared or misrepresented precious commodities, a common tactic in smuggling schemes.
- [Cross-Border Cash Smuggling](https://framework.amltrix.com/techniques/T0065) — - Provide official records of declared and inspected currency at border checkpoints.
- Detail individuals' or shipments' cross-border movements, enabling the detection of suspicious or inconsistent declarations.
- Support case investigations by confirming travel dates, entry/exit points, and associated documentation that may reveal undeclared cash smuggling activity.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — - Contains import/export declarations, shipping routes, and documentation of artworks crossing borders.
- Identifying frequent cross-border transportation or free-trade zone usage reveals patterns of potential laundering through minimized oversight and undisclosed beneficial ownership in the art market.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Records cross-border cash or monetary instrument declarations and seizures at entry or exit points.
- Enables detection of large or frequent cross-border payments by junket operators and VIP clients that are not consistent with legitimate gambling volumes.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Provides official data on the cross-border movement of goods, including shipping routes, tariffs, and declared items.
- Facilitates the confirmation of actual import/export activities in free trade zones versus declared trade documentation.
- Helps detect repeated re-exports or suspicious cargo volumes that may indicate layering within FTZs.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — - Maintains official records on imported and exported goods, including shipping routes, tariffs paid, and customs declarations.
- Facilitates detection of repeated amendments, forged filings, re-labeled goods, or suspicious changes in product descriptions within bonded warehouses, indicative of possible illicit layering or misrepresentation.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Contains official records of cross-border shipments, including declared goods, shipping routes, volumes, and tariffs. Investigators can cross-check these data points to detect inconsistencies or non-existent cargo (phantom shipments), identify potential over- or under-invoicing based on declared versus actual imports, and confirm or refute suspicious last-minute route changes indicative of illicit trade-based manipulation.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Covers entry and exit data for individuals, goods, or currency across national borders.
- Correlates the physical transport of assets by local agents with suspicious transaction spikes.
- Supports the detection of undeclared or repeated cross-border cash movements linked to the same beneficiaries or accounts.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Includes official import/export filings, declarations, shipping routes, and commodity details.
- Comparing these records with submitted shipping or customs documents helps identify tampering or misrepresentation in trade documents used to move illicit funds across borders.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Provides official documentation of declared cash amounts and cross-border movements at entry/exit points.
- Enables verification of the stated amounts against the actual physical movement of currency.
- Helps detect repeated or suspicious declarations inconsistent with legitimate travel or transactional patterns.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Documents declared goods, shipping routes, valuations, and relevant import/export filings.
- Facilitates the detection of misappropriated gold purity or classification, revealing discrepancies between declared and actual gold content when crossing borders.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Reflects declarations of imported and exported items and identifies instances of transporting bearer instruments across borders.
- Flags incomplete or missing disclosures relevant to the physical movements of bearer certificates.
- Aids investigations by pinpointing cross-border transfer routes frequently used to conceal the origin or destination of bearer instruments.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Encompasses official data on goods moving across borders, capturing shipping routes, multiple transshipment points, declared values, and inspection results. This contributes to:

- Uncovering suspicious or circuitous shipping paths for precious metals or gemstones with no clear commercial justification.
- Detecting potential misuse of relaxed oversight in certain jurisdictions.
- Enhancing investigations into cross-border movements tied to trade-based money laundering schemes.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — Comprehensive documentation of the movement of goods and people across borders, including declarations, shipping routes, and related details. This data assists in identifying physical cash smuggling routes near conflict-prone or minimally supervised regions and detecting mismatched or incomplete customs declarations linked to illicit cross-border activity.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Provides documentation of cross-border cash declarations and any seized amounts. Correlating these records with subsequent fiat or crypto movements helps identify instances where large cash sums enter a jurisdiction and are quickly converted into or out of cryptocurrency, indicating potential NEP patterns.
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Captures declared currency amounts, traveler details, and cross-border entry/exit logs. Cross-referencing these data with subsequent deposits or withdrawals of high-denomination notes can reveal undeclared currency movements tied to illicit transport.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Shows whether the declared goods in a Bill of Exchange transaction actually crossed borders and in what quantity, helping identify phantom shipments or misrepresented cargo.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Includes official import/export entries, shipping manifests, and customs clearances.
- Supports verification of whether purported cross-border shipments actually occurred, exposing fabricated or inconsistently reported settlement documents.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Provides records of cross-border movements of individuals and goods.
- Captures declared or discovered currency amounts, travel routes, frequencies, and inspection outcomes.
- Enables AML investigators to identify travelers carrying large sums of cash, spot repeated use of specific routes, and detect patterns of structuring amounts below reporting thresholds.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Tracks the movement of goods across international borders, including detailed import/export data, shipping routes, and declared commodity values.

This data helps uncover situations where valuable commodities, particularly gold, are physically moved without corresponding formal fund transfers, an essential feature of Hot Transfers.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Details cross-border shipments, declared commodities, shipping routes, and customs filings. This data enables the detection of misdeclared or undocumented mineral exports, which are common in illegal mining schemes.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Contains import and export declarations, shipping fees, and routing details related to the cross-border movement of goods.
- Enables detection of abnormally high shipping or import fees for collectibles that exceed typical costs, indicating possible layering.
- Corroborates declared valuations and routes for collectible shipments, helping reveal discrepancies or potential cost manipulation.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Contains authoritative information on goods movements, declared values, and shipping routes.
- By comparing declared shipment details in financial instruments with the actual customs records, investigators can detect discrepancies or forged references.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Provides data on import/export activities, shipping routes, and declared goods crossing national borders.
- Assists in identifying suspicious shipments or misdeclared cargo potentially concealing narcotics, precursor chemicals, or drug profits.
- Aids in detecting trade discrepancies that may indicate smuggling or trade-based money laundering linked to drug operations.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Official records maintained by customs and border authorities track the movement of goods across ports or borders. 

- By comparing declared shipments in trade documentation with actual customs entries or exits, investigators can reveal discrepancies that signal ghost shipments.
- Identifies cargo that was never physically processed, indicating artificially constructed shipment paperwork.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Contains official documentation of imported or exported goods, shipping routes, and declared duties.
- Helps verify the authenticity of tobacco shipment declarations, duty-free claims, and cross-border transit details.
- Supports detection of manipulated or missing customs documentation that may conceal smuggling activities.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — These records track the movement of goods and related documentation across national borders, including shipments of precursor chemicals. By comparing declared items against typical business operations, financial institutions can detect suspicious imports or exports consistent with illicit drug manufacturing activities.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Documents declared shipping routes, destinations, and actual goods movement. 

- Permits verification of declared commodity routes and transit points.
- Helps detect suspicious free trade zone usage, last-minute rerouting, or unexplained detours commonly exploited in commodity-based laundering.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Centralizes data on goods movement across borders, including shipping routes, import/export details, and tariffs.
- Enables detection of complex or unusual shipping patterns, such as vessel flag changes or multi-jurisdiction routes used to disguise illicit oil trades.
- Allows comparison of declared cargo specifics with recorded border entries, uncovering discrepancies in oil shipments.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Comprehensive records of goods crossing borders include declared values, item descriptions, shipping routes, and the use of free ports or trade zones. This data helps detect suspicious or inconsistent customs declarations for cultural artifacts, indicating potential smuggling or illicit trafficking.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Provides official records on the movement of goods and related permits required at border checkpoints.
- Helps detect fabricated transport or harvesting permits by comparing declared shipments with actual customs data.
- Identifies discrepancies between claimed and actual commodity flows used to mask illicit activities.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Contains import and export records, shipping routes, and associated documentation.
- Allows verification of declared goods and detection of discrepancies in shipments linked to illegal wildlife, timber, or other contraband.
- Identifies unusual or repeated transit routes indicative of laundering through cross-border movements.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Documents actual goods movement and clearance, including declared values, quantities, shipping routes, and inspection outcomes.
- Allows investigators to compare official customs data with trade invoices, exposing potential misinvoicing when goods or valuations do not match reported information.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Data from customs authorities detail official imports, exports, and cross-border movements of goods. Comparing these records with claimed import/export expenses can uncover inconsistencies indicative of misrepresented transactions.
- [Negotiable Instrument Purchases](https://framework.amltrix.com/techniques/T0110) — - Official records of cross-border movements, declarations, and inspections, including disclosure or seizure of bearer negotiable instruments.
- Assists in detecting undeclared international transportation of negotiable instruments to circumvent currency reporting requirements.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Logs declared imports and exports, including valuable goods shipped across borders into or out of freeports. Detects discrepancies between declared items and actual shipments, indicating possible smuggling or unreported asset movements.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Provides official logs of goods, shipments, and individuals crossing borders.
- Contains shipping routes, commodity details, and declarations that may reveal discrepancies or hidden wildlife products.
- Supports detection of fraudulent or incomplete documentation used to conceal illicit wildlife cargo.

---

## [Money Service Business (MSB) Registries](https://framework.amltrix.com/data-sources/DS0029)

**Description:**
Official or government-run registries listing licensed money service businesses or remittance providers, including their licensing status and operational details.

### Related Techniques
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Lists licensed money service businesses with their licensing status and operational details. Validating whether an MSB is registered or has any red flags helps uncover unlicensed or complicit providers supplying large-denomination notes for illicit cross-border transport.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — Contains official or government-run records listing licensed money service businesses (MSBs) and remittance providers, including their licensing status, ownership details, and operational scope. These records help identify and verify authorized MSBs used for alternative payment channels, enabling AML teams to detect illicit or unlicensed operations. Cross-referencing registration data with observed transactions helps pinpoint higher-risk or unauthorized service providers facilitating funds movement outside regulated banking systems.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Lists licensed MSBs and check-cashing services, detailing their locations and licensing status.
- Validates whether payroll checks are being cashed through legitimate channels or circumventing standard payroll systems.
- Reveals patterns of high-volume cash-outs at MSBs that may indicate unreported wage payments.
- [Mobile Payment Systems](https://framework.amltrix.com/techniques/T0134.002) — Contains official licensing and registration information for money service businesses, including mobile payment and remittance service providers. By verifying regulatory compliance status, investigators can identify unregistered or illegally operating mobile payment entities that may facilitate illicit fund movements and layering activities.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Official or government-maintained lists of licensed money service businesses are essential. Checking these registries helps identify unlicensed hawaladars operating outside regulatory purview, enabling AML teams to spot unauthorized remittance activity indicative of hawala networks.
- [Disguised Remittance Transfers](https://framework.amltrix.com/techniques/T0040.001) — Contains official licensing and operational details of MSBs, enabling the detection of customers who use multiple remittance providers to bypass monitoring thresholds or obscure the overall volume of disguised remittances.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — Official or government-run registries of licensed MSBs include licensing status and operational details. Cross-referencing an MSB’s declared operations and ownership with these registries helps detect unlicensed or fraudulently acquired licenses, identifying potential front or controlled MSBs used for illicit transactions.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Lists licensed and registered MSBs, including any sub-agents and license particulars.
- Validates whether agents or sub-agents are operating under proper regulatory frameworks.
- Detects unregistered or unauthorized sub-agents who may be bypassing AML/CFT controls.
- [Independent Payment Agents](https://framework.amltrix.com/techniques/T0113.001) — - Provides official licensing and regulatory status of payment institutions, including sub-agents and remittance providers.
- Supports verification of whether sub-agents are legally registered or exceed permitted scopes under the principal license, preventing unlicensed or white-labeled providers from operating illegally.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Lists registered or licensed remittance and money service providers.
- Helps identify unlicensed or suspicious third-party remitters potentially used to deposit or move funds through funnel accounts, especially across borders.
- Allows compliance teams to check if frequent cross-border transfers involve regulated MSBs or unregistered entities, indicating heightened funnel-account risk.
- [Informal Micro-Finance Schemes](https://framework.amltrix.com/techniques/T0096) — - Provides official listings and licensing status of money service businesses and remittance providers.
- Identifies unlicensed or unregistered entities operating as informal micro-finance or remittance channels, revealing gaps in AML oversight.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — Provides official or government-run registries listing licensed and authorized remittance providers, including their licensing status and operational details. This data helps identify unlicensed or suspicious MSBs potentially engaged in hijacking legitimate inbound transfers, a central tactic of cuckoo smurfing.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Provides official listings of licensed MSBs, including their licensing status and operational details.
- Allows verification of whether an entity is absent from the registry, indicating potential unlicensed MSB activity.
- Facilitates detection of MSBs circumventing AML requirements by operating without proper authorization.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Contains official licensing and registration information for money service businesses.
- Verifies whether hawala or underground remittance providers have legal authorization, helping identify unregistered IVTS operations.
- Supports AML investigators in confirming the legitimacy of purported MSB activities.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Lists licensed and regulated money service businesses, helping to identify if laundering schemes involve unlicensed or poorly regulated operators. Frequent cross-currency swaps conducted via questionable MSBs are a common tactic in advanced layering scenarios.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Lists licensed money remitters, exchange houses, and payment service providers, including licensing status and operational details.
- Reveals whether agents in multiple jurisdictions operate under valid MSB licenses or function illegally.
- Supports investigations by cross-referencing suspicious remittance patterns with noncompliant or unregistered MSB entities.
- [Remittance Splitting](https://framework.amltrix.com/techniques/T0016.003) — - Lists licensing, location, and operational details of registered remittance and money service providers.
- Confirms whether transfers are conducted through properly licensed or potentially unregistered/loosely supervised MSBs.
- Helps identify the use of multiple or regional remittance businesses in structuring illicit proceeds.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Provides official information on licensed money service businesses, including their licensing status and operational details.
- Assists in confirming whether customers are using unlicensed or lesser-regulated MSBs.
- Aids in detecting structured transactions and the frequent use of unregulated entities for repeated currency exchanges.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Official listings of licensed money service businesses or remittance providers, including their licensing status, registration numbers, and operational details.

- Direct AML Relevance: Enables financial institutions to identify unregulated or informal brokers facilitating Black Market Peso Exchange, as they often operate outside official licensing frameworks and are used to bypass currency controls.
- [Structuring](https://framework.amltrix.com/techniques/T0016) — - Lists licensed money service businesses and associated registrations, including ownership and operational scopes.
- Identifies whether the same individual or entity is using multiple MSBs for repeated sub-threshold transactions that collectively exceed reportable limits.
- Aids in determining if reported MSB usage aligns with the customer’s declared profile and accounts, revealing potential structuring activity.
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Lists officially licensed or regulated money remitters, including their operational details.
- Aids in detecting unregistered or informal money transfer providers commonly used for laundering smaller proceeds from street-level offenses.
- Supports better scrutiny of remittance flows and helps flag irregular cash movements via unlicensed entities.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Lists licensed or registered currency exchange and money service providers, including their authorization status.
- Identifies unlicensed or rogue exchange offices that may facilitate illicit conversions.
- Helps monitor compliance requirements for regulated MSBs, detecting those with potential AML lapses.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Lists licensed MSBs and remittance providers with details on operational status and regulatory compliance.
- Aids in identifying unregistered remittance channels or suspicious MSBs frequently involved in smuggling fee transactions.

---

## [Geographical & Jurisdictional Risk Data](https://framework.amltrix.com/data-sources/DS0005)

**Description:**
Consolidated information on countries, regions, legal jurisdictions, and AML/CFT laws, regulations, and enforcement practices, used to assess geographic and regulatory risk and identify anomalies in financial transactions.

### Related Techniques
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Contains risk assessments of AML/CFT controls and enforcement levels across various jurisdictions.
- Identifies ties to high-risk or under-regulated regions susceptible to hidden insider trading activity.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Consolidated information on countries’ AML/CFT regimes, risk ratings, and regulatory enforcement.

Identifying cross-border transactions with high-risk or lightly regulated jurisdictions helps detect layering or the flight of illicit funds under the guise of diplomatic privileges.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — - Provides details on high-risk jurisdictions and data centers with weak AML oversight.
- Aids in detecting network traffic from regions commonly used by criminals for proxy-based obfuscation.
- Supports investigators in evaluating whether certain IP addresses or hosting providers are operating in risky or non-cooperative jurisdictions.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — Aggregates risk indicators for various countries and regions, including AML/CFT regulatory standards, enforcement levels, and known secrecy jurisdictions. Helps identify high-risk origins or routes of alleged foreign investments, flagging potential illicit proceeds disguised as FDI.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Identifies high-risk regions where healthcare providers may be difficult to vet. This helps investigators apply enhanced scrutiny to early superannuation withdrawal requests that reference medical documentation from such jurisdictions.
- [Trust-Based Obfuscation](https://framework.amltrix.com/techniques/T0088.002) — - Identifies secrecy-friendly jurisdictions with weak or non-transparent beneficial ownership requirements.
- Helps pinpoint higher-risk trust structures established in offshore locales frequently exploited to conceal ultimate controllers.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Contains risk ratings and regulatory information by country or region. Reviewing this data helps identify OTC brokers operating in high-risk or weakly regulated jurisdictions, aligning with known hotspots for unregulated cryptocurrency trading.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Highlights risk levels and AML/CFT enforcement variations across different jurisdictions where agents operate.
- Helps detect cross-border segments with weaker supervision or less rigorous KYC practices.
- Enables targeted monitoring of payments flowing through higher-risk locations commonly exploited by sub-agents.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — Geographical risk data outlines known high-risk jurisdictions, AML enforcement levels, and risk ratings, including:

- Country-specific red flags or heightened regulatory scrutiny.
- Contextual information on cross-border transactions.

Identifying chargebacks initiated from high-risk regions helps detect potentially fraudulent disputes and laundering attempts involving jurisdictions with lax oversight.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Consolidates information on high-risk jurisdictions and AML/CFT enforcement practices.
- Facilitates analysis of wire transfers to or from regions flagged for elevated risk, aligning with known layering channels.
- [Burn and Mint Transfers](https://framework.amltrix.com/techniques/T0005.001) — Offers risk-based insights on countries, regions, and regulatory environments. In relation to Burn and Mint Transfers, this data:

- Identifies potential use of burn addresses or bridging services in high-risk or unverified jurisdictions
- Highlights cross-border layering strategies exploiting weaker regulatory controls
- Supports deeper geographic risk analysis of complex cross-chain token movements
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Supplies risk assessments for countries and regions, highlighting high-risk or sanctioned jurisdictions. Discrepancies between a customer's claimed domicile and the associated geographic risk profile can indicate falsified residency or manipulated identity claims.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Provides risk profiles and AML/CFT regulatory information for various jurisdictions, enabling institutions to identify high-risk regions where multiple cross-currency swaps may be conducted to exploit lax oversight. This data helps investigators pinpoint patterns of frequent multi-jurisdictional transfers and assess heightened layering risks in specific countries.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — Provides consolidated risk ratings, regulatory information, and enforcement profiles for different countries and regions. By referencing this data, investigators can identify unusual cross-border payment routes involving higher-risk or conflict-prone jurisdictions, ensure enhanced scrutiny of transactions in weakly regulated areas, and spot potential layering schemes exploiting jurisdictional vulnerabilities.
- [Correspondent Banking](https://framework.amltrix.com/techniques/T0104) — Consolidates information on higher-risk or poorly regulated jurisdictions, including AML enforcement practices and regulatory frameworks. Leveraging this data helps the correspondent bank apply enhanced due diligence measures and detect potentially suspicious cross-border transactions flowing from or into high-risk areas.
- [Domestic Bulk Cash Delivery](https://framework.amltrix.com/techniques/T0119) — Provides detailed information on intranational differences in AML/CFT regulations, enforcement, and compliance standards, highlighting regions with weaker oversight where criminals might attempt to transport and deposit large sums of cash domestically. This data enables financial institutions to prioritize those areas for enhanced due diligence and detect unusual in-country cash flows consistent with bulk cash deliveries.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Aggregates current risk assessments for each jurisdiction, focusing on AML/CFT regulations, enforcement levels, and known vulnerabilities.
- Helps identify higher-risk regions where local agents may exploit lax controls, facilitating the detection of suspicious cross-border dealings.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Consolidated information on countries and jurisdictions, including AML/CFT regulations, levels of enforcement, and risk indicators. 

- Identifies free trade zones and high-risk regions frequently exploited for trade-based money laundering.
- Supports risk-based screening of shipments routed through less regulated jurisdictions.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — - Provides risk ratings and AML regulatory conditions across various locations.
- Highlights banks operating in high-secrecy jurisdictions where criminals may prefer renting deposit boxes.
- Assists in identifying elevated risk scenarios stemming from deposit box usage in weak AML environments.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Consolidates information on regional AML/CFT risks, customs oversight, and regulatory enforcement levels.
- Flags exports involving jurisdictions known for weak trade supervision or minimal invoice verification.
- Guides enhanced monitoring of transactions where inflated export values may go unnoticed.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Assesses the AML risk profiles of countries involved in trade finance transactions. Investigators can prioritize enhanced scrutiny when transactions repeatedly involve high-risk or secrecy jurisdictions known for weak AML controls.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Identifies high-risk or non-cooperative jurisdictions where intermediaries may operate to evade stricter AML controls.
- Flags intermediary accounts or transactions linked to regions with elevated money laundering vulnerabilities.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Classifies countries and regions by AML/CFT risk profiles, highlighting jurisdictions with weak governance and lax oversight.
- Identifies cross-border donation flows originating from or transiting through high-risk areas.
- Helps investigators prioritize scrutiny of charities receiving funds from regions known for higher terrorism or money laundering risks.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Provide risk ratings and watchlists for jurisdictions with known secrecy or weak AML enforcement.
- Flag cross-border premium payments or annuity disbursements involving high-risk regions.
- Identify potential higher risk associated with policyholders or beneficiaries connected to these jurisdictions.

This information supports enhanced scrutiny of suspicious cross-border annuity transactions and helps detect geographic-based ML red flags.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Consolidates country- and region-specific regulatory and sanctions risk information.
- Flags high-risk or sanctioned jurisdictions in transaction flows, supporting targeted investigations for possible sanctions evasion activities.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Consolidated intelligence on regions or jurisdictions known for organized crime or extremist activities. This data assists in: 

- Flagging accounts receiving or sending funds to areas associated with extortion or forced payment schemes.
- Enhancing risk-based monitoring by prioritizing geographies linked to intimidation or coercion.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Consolidates risk profiles of countries and territories, including secrecy or high-risk jurisdictions. This data helps identify offshore or uncooperative issuers of prepaid cards and e-wallets, enabling targeted monitoring of cross-border activities likely to facilitate laundering.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Outlines AML risk levels for specific regions and jurisdictions hosting sports clubs or sponsoring entities.
- Assists in identifying high-risk areas known for lax financial regulations where criminals may channel funds via sports sponsorship.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Consolidates data on countries or regions with heightened conflict, limited AML controls, or known arms embargoes.
- Assists in identifying transactions or clients linked to high-risk jurisdictions often exploited by arms traffickers, enabling enhanced scrutiny and risk-based monitoring.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Consolidated information on AML/CFT enforcement levels and regulations across different countries.
- Highlights regions with lax oversight or inadequate exchange controls, aligning with known laundering hotspots.
- Assists in risk-scoring transactions involving high-risk or undersupervised jurisdictions for currency exchange.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Consolidates risk ratings and AML standards for different regions.
- Pinpoints funnel account transactions involving high-risk or lax regulatory jurisdictions, highlighting suspicious cross-border flows.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Provides risk assessments of global jurisdictions, including regulatory strength, AML/CFT enforcement practices, and relevant country-specific advisories.

- Helps identify high-risk cross-border movements of game tokens or digital items, especially where criminals exploit weaker AML regimes.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Consolidates country risk levels, AML/CFT compliance standards, and known vulnerabilities related to trade misinvoicing.
- Supports enhanced due diligence by focusing investigative efforts on higher-risk jurisdictions and trade lanes frequently associated with misinvoiced transactions.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Consolidates information on jurisdictions with lax AML oversight and high offshore secrecy. This data helps flag the use of offshore insurance policies in regions known for minimal regulatory scrutiny, linking policy activities to geographic risk assessments.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Consolidates information on high-risk jurisdictions, AML regulations, and geographic risk factors.
- Flags cross-border instant exchanges involving suspicious or prohibited regions, indicating elevated laundering risk.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Consolidates AML/CFT risk profiles of countries and jurisdictions.
- Flags transactions involving high-risk or weakly regulated regions that facilitate precious commodity smuggling.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — Provides consolidated information on high-risk or lightly regulated jurisdictions, helping to identify payment token transactions or counterparties associated with areas known for weaker AML/CFT compliance and detecting potential exploitation of regulatory gaps.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Consolidates country- and region-specific regulations and AML/CFT risk factors, enabling the identification of high-risk or secrecy-prone jurisdictions commonly used by virtual companies to obscure beneficial ownership.
- [Governance Token Obfuscation](https://framework.amltrix.com/techniques/T0067.003) — Consolidates country- and region-specific AML/CFT regulations, risk levels, and enforcement practices. Investigators can:

- Pinpoint governance token transactions linked to jurisdictions with minimal AML oversight.
- Identify potential regulatory arbitrage or non-compliant regions that criminals exploit to evade detection.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Provides country- or region-specific AML/CFT risk profiles and regulatory landscapes.
- Flags high-risk or secrecy-prone jurisdictions commonly used to obscure beneficial ownership.
- Alerts investigators to potential misuse of offshore accounts or cross-border structures for service contract manipulation.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Identifies offshore or secrecy jurisdictions with lax regulations frequently involved in manipulated insurance schemes.
- Flags high-risk regions or countries for suspicious cross-border premium or claim transfers.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Consolidates data on the AML/CFT risk profiles of different countries or regions. This data assists investigators by:

- Flagging countertrade transactions involving jurisdictions lacking robust regulations or oversight.
- Prioritizing scrutiny of deals in corruption-prone or high-risk regions.
- [Geographically Dispersed Cash Deposit](https://framework.amltrix.com/techniques/T0053) — - Highlights jurisdictions with weaker AML/CFT enforcement or higher corruption risk.
- Enables targeted monitoring of cross-border cash deposits that exploit regional differences in reporting thresholds or oversight.
- Assists in risk-scoring geographically dispersed deposits and prioritizing investigative resources accordingly.
- [Third-Party Payments](https://framework.amltrix.com/techniques/T0073) — Aggregates risk profiles for countries and financial institutions, highlighting those with AML/CFT weaknesses or high corruption rates. Identifying multiple third-party payments originating from high-risk jurisdictions helps flag transactions that deviate from a customer’s usual geographic profile and may signal laundering attempts.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Consolidates risk assessments of countries, regions, and jurisdictions.
- Highlights high-risk or sanctioned areas where trade flows may be exploited.
- Supports identification of unusual or unsupported shipping routes and potential geopolitical risk factors in documentary collections.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Consolidates information on high-risk or weakly regulated jurisdictions relevant to syndicated trade finance transactions.
- Aids in evaluating the cross-border dimension of syndicated deals, highlighting potential regulatory gaps exploited to mask beneficial ownership or inflate loan values.
- [Insurance Policy Overfunding](https://framework.amltrix.com/techniques/T0090.002) — - Identifies whether refunds or withdrawals are directed to jurisdictions with weak AML regulations or high levels of financial secrecy, enabling enhanced scrutiny of cross-border policy disbursements.
- Flags transactions flowing to or from high-risk regions, supporting more targeted investigations into insurance policy overfunding and subsequent layering techniques.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Consolidates information on jurisdictions with weak AML regimes or high secrecy standards. Linking beneficial ownership changes to these locations can reveal intentional efforts to evade scrutiny and exploit minimal transparency requirements.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Aggregates information on high-risk jurisdictions, regulatory requirements, and known trade anomalies.
- Flags invoiced transactions involving suspect regions or mismatched business addresses potentially linked to invoice manipulation.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Rates countries and regions based on AML/CFT enforcement levels, revealing captive insurance entities registered in minimal-oversight or secrecy jurisdictions.
- Enables risk-based analysis of cross-border premium payments or claim settlements.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Displays risk ratings for countries and regions known for facilitating or hosting loosely regulated mining operations.
- Flags payments or connections to high-risk jurisdictions where minimal KYC or regulatory oversight may enable illicit mining.
- Assists in assessing whether remote mining locations pose significant money laundering or sanctions-evasion risks.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Provides profiling of jurisdictions with weak corporate disclosure requirements.
- Identifies mismatches between a company’s registration location and its principal business markets.
- Aids in assessing cross-border layering risks where corporations exploit varying disclosure obligations.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Maps countries, territories, and regions to their AML/CFT risk profiles, highlighting secrecy jurisdictions or areas with weak oversight.
- Facilitates enhanced screening of transactions and accounts linked to high-risk locations.
- Supports risk-based monitoring and alerts when repeated or unexplained usage of such jurisdictions is detected.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Consolidates information on AML/CFT regulatory environments, legal frameworks, and enforcement practices across various jurisdictions.
- Supports the identification of high-risk CBI/RBI programs in jurisdictions with minimal oversight and suspicion regarding large cross-border capital transfers from high-risk regions.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — - Consolidates risk ratings and regulatory details for various regions.
- Detects unusual inbound transactions from uncharacteristic or high-risk jurisdictions, indicating potential cuckoo smurfing activities.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Contains information on high-risk or sanctioned jurisdictions, including those known for lax AML/CFT controls.
- Helps identify and flag mining-related transactions linked to countries where remote mining services might facilitate sanctions evasion or added anonymity.
- [Privacy Coins](https://framework.amltrix.com/techniques/T0116) — - Consolidates information on regulatory environments and AML/CFT enforcement levels by jurisdiction.
- Flags high-risk or poorly regulated regions where privacy coin usage may be prevalent or unmonitored, helping investigators target higher-risk geographic corridors for privacy coin transactions.
- [Independent Payment Agents](https://framework.amltrix.com/techniques/T0113.001) — - Consolidates risk assessments for countries and regions, highlighting regulatory frameworks, AML/CFT enforcement levels, and potential vulnerabilities.
- Supports targeted oversight of sub-agents operating in offshore or high-risk jurisdictions, enabling risk-based monitoring of payment flows.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Provides risk profiles of regions and jurisdictions, highlighting areas with weak oversight or prevalent illegal mining. This helps flag the movement of precious metals through high-risk routes or smelting points.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Consolidates risk profiles of various jurisdictions, including known secrecy havens.
- Highlights high-risk regions with weak AML regulations frequently involved in transaction chaining.
- Helps investigators detect transfers passing through or originating in jurisdictions with no legitimate connection to the customer.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Consolidates country-level regulatory environments and identifies regions with high risk or lax AML enforcement.
- Identifies entertainment-related funds or sponsorships flowing from or to suspicious jurisdictions, enabling investigators to prioritize cross-border reviews.
- Facilitates the recognition of high-risk geographies associated with multi-jurisdictional event promotions that may be used to layer illicit funds in the entertainment industry.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — - Consolidates information on jurisdictions with high AML/CFT risk, including known regulatory weaknesses or inadequate customs oversight.
- Assists in prioritizing investigations when bonded warehouses operate in regions prone to minimal enforcement or higher incidences of illicit trade.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Consolidates information on AML/CFT regulations, enforcement, and risk levels across different jurisdictions. Investigators can pinpoint high-risk routes and identify suspicious multi-jurisdictional structuring or exploitation of weaker regulatory environments, which are prevalent in trade-based laundering.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Consolidates AML/CFT risk profiles for countries and regions, highlighting areas with weak regulatory controls.
- Supports risk-based monitoring by flagging transactions to custodial mixers in high-risk jurisdictions, aligning with suspicions of minimal AML oversight.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Country-level AML/CFT risk ratings, regulatory requirements, and enforcement practices.
- Highlights suspicious use of offshore or high-secrecy jurisdictions where private investment companies can obscure illicit proceeds or evade oversight.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Identifies foreign jurisdictions with weak AML controls or enforcement and highlights cross-border operational risks.
- Helps detect educational institutions registered in high-risk locations yet directing transactions elsewhere, indicating possible laundering through foreign nonprofit entities.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Consolidates information on freeport jurisdictions known for secrecy laws or minimal disclosure obligations. Enables risk-based assessment of storage in high-secrecy regions and helps identify cross-border activity where local regulations may hinder standard AML controls.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Consolidates information on regions and countries known for weak AML controls or prevalent human trafficking.
- Supports transaction monitoring by highlighting high-risk corridors or suspicious geographic flows.
- Assists in prioritizing reviews of funds passing through trafficking hotspots or poorly regulated jurisdictions.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Identifies high-risk jurisdictions with weak regulatory frameworks or known usage of bearer shares.
- Flags frequent cross-border transactions or shipments involving locations associated with limited transparency.
- Supports enhanced risk assessments when bearer instruments are moved into or out of jurisdictions with heightened AML/CFT concerns.
- [Dividend Stripping](https://framework.amltrix.com/techniques/T0147.003) — Provides insights into countries or regions with lax short-selling or share-lending regulations, or minimal enforcement. Firms can monitor dividend-related transactions originating from or flowing through high-risk jurisdictions to identify potential dividend stripping schemes.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Consolidates information on high-risk regions, regulatory environments, and AML/CFT compliance standards.
- Highlights the use of recently formed or front companies in jurisdictions with weaker enforcement or higher corruption risk.
- Flags the unusual involvement of multiple risky locations in circular L/C transactions, raising suspicion of trade misrepresentation.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Details risk levels associated with various jurisdictions, including those with weak AML regulations or known secrecy practices. This data supports the screening of fund domicile and cross-border investment flows for potential layering or concealment in high-risk or offshore locations.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Compiles AML/CFT risk ratings and disclosure requirements across various jurisdictions. This aids in identifying high-risk or secrecy-friendly regions used to obscure beneficial ownership or launder funds into legitimate enterprises.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Consolidates risk information on high-tax and low-tax jurisdictions, cross-border hotspots, and regulatory regimes.
- Identifies border regions frequently used for contraband tobacco movements and flags suspicious fund flows involving these locations.
- Supports prioritizing enhanced monitoring where tobacco smuggling risks are highest.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Provides risk insights on specific countries and regions, including their AML/CFT frameworks, corruption indices, and known vulnerabilities in citizenship-by-investment programs. Linking these risk ratings to account openings or transactional activity tied to high-risk jurisdictions helps detect layering schemes involving alternate passports from secrecy havens or jurisdictions with weaker AML enforcement.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Consolidated information on AML/CFT regulations, enforcement practices, and risk ratings by country or jurisdiction.
- Directly helps flag applications for citizenship/residency originating from or targeting high-risk or secrecy-prone jurisdictions.
- Supports AML detection efforts by correlating the applicant’s geographical background or investment targets with known risk factors in CBI/RBI programs.
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Highlights jurisdictions where high-denomination bills remain in frequent use or are subject to weak oversight. Correlating travel to these regions with unusual note transactions helps uncover potential cross-border cash smuggling activities.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Consolidates risk ratings and AML/CFT enforcement levels for countries and regions.
- Supports the identification of transactions routed through or initiated in jurisdictions with weak AML oversight, a common trait of alternative payment channels.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Provides risk profiles and regulatory details for various jurisdictions.
- Identifies regions with minimal real estate licensing or weak consumer protection, which are used to register timeshare scam companies.
- Flags incoming payments from higher-regulation regions as potential high-risk cross-border transactions.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Offers regional insights on typical agricultural capacities and subsidy ranges. Identifies anomalies when high-value subsidy payments are directed to areas with minimal farmland or poor agricultural infrastructure, suggesting fraudulent claims.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Consolidates risk indicators for various jurisdictions, focusing on AML/CFT controls, secrecy laws, and enforcement levels. Comparing Bill of Exchange transactions involving high-risk countries can indicate elevated money laundering risk or collusion with minimal oversight.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Consolidates information on specific countries and regions, focusing on AML/CFT regulations, telemarketing industry norms, and relevant risk indicators.
- Identifies discrepancies when entities claim extensive call-center operations in jurisdictions lacking a robust telemarketing sector or licensing frameworks.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Centralizes risk ratings, AML/CFT compliance statuses, and details about cross-border financial frameworks.
- Identifies high-risk jurisdictions or specialized payment systems (e.g., SUCRE) often targeted for document manipulation schemes.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Consolidates risk information on countries' AML/CFT compliance and enforcement practices.
- Pinpoints higher-risk jurisdictions lacking robust regulatory oversight, where illicit market manipulation activity may be more easily concealed.
- Assists in focusing surveillance on trades originating from or routed through weakly regulated regions.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Compiles risk profiles of different jurisdictions and helps flag invoices originating from high-risk or weakly regulated regions. This supports enhanced scrutiny of repeated invoicing tied to high-risk areas.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Consolidates country and regional risk information, including AML regulatory environments, corruption indices, and known weak borders.
- Assists AML teams in identifying high-risk travel routes or jurisdictions where cash couriers can evade strict controls.
- Helps flag suspicious itineraries involving known high-risk corridors or frequent changes to avoid regulated border crossings.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Consolidates risk assessments and regulatory information on specific countries or regions.
- Identifies jurisdictions known for weak transparency or lax oversight in property transactions.
- Assists analysts in monitoring high-risk geographic targets for potentially illicit real estate investments.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Consolidates information on jurisdictions with weak construction permit requirements or lax AML/CFT enforcement.
- Aids in flagging properties located in high-risk areas where inflated renovation costs may go undetected due to minimal oversight.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Offers region-specific risk ratings and information on AML/CFT regulatory environments. 

- Identifies localities with significant organized crime presence or paramilitary influence.
- Flags cross-border transfers to jurisdictions with weak AML controls potentially used for layering extorted funds.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Highlights jurisdictions with weak AML frameworks or incomplete carbon market regulations.
- Supports risk assessment of carbon credit trades that involve brokers or platforms in high-risk regions, enabling targeted investigations of questionable cross-border activity.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Consolidates risk profiles of various jurisdictions, including known secrecy havens or offshore centers.
- Flags consulting firms routing transactions through high-risk regions without legitimate reasons, revealing possible efforts to obscure illicit flows.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Provides insight into high-risk jurisdictions, AML/CFT regulations, and enforcement levels across regions. Criminals may exploit weak oversight in certain jurisdictions to layer or integrate illicit capital through private equity or hedge funds.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Provides insight into regulatory environments and the transparency of jurisdictions associated with issuing institutions.
- Assists in detecting heightened risk from poorly regulated or opaque offshore entities that issue or handle suspect financial instruments.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Aggregates information on high-risk or secrecy jurisdictions, enabling checks on offshore or cross-border mirror trades. By correlating trade and fund transfer destinations with known low-transparency regions, institutions can detect higher-risk layering patterns that lack legitimate commercial rationale.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Provides risk ratings and AML/CFT enforcement levels across different countries or regions.
- Identifies high-risk or weakly regulated jurisdictions that may be chosen for cross-border cash declarations.
- Flags unusual or high-risk routes used to move currency under the guise of legitimate declarations.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Consolidates country risk ratings, regulatory environments, and corruption indices for various jurisdictions.
- Pinpoints loans tied to regions with lax AML controls or high corruption risk, consistent with known loan-based laundering practices.
- Informs risk-based scrutiny for cross-border lending to higher-risk jurisdictions.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Consolidates information on regional AML/CFT regulations, enforcement practices, and known high-risk areas.
- Helps contextualize transactions involving jurisdictions with known drug production or trafficking routes.
- Supports risk-based monitoring by highlighting cross-border dealings in regions with weaker oversight or higher incidence of narcotics activity.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Highlights jurisdictions with weak controls, including free trade zones commonly exploited for the transshipment of illicit diamond consignments.
- Supports risk-based prioritization of suspicious shipping routes or business relationships in high-risk areas.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Consolidates risk assessments of countries or regions known for high rates of fraud or minimal AML controls.
- Enables investigators to spot potentially suspicious international transfers linked to romance mule recruitment in high-risk jurisdictions.
- Aids in prioritizing enhanced due diligence for customers or counterparties operating from or sending funds to these regions.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Highlights AML regulations and enforcement levels across different regions, enabling the identification of betting activity concentrated in areas with weaker oversight. Correlating this data with actual betting shop locations helps detect deliberate exploitation of lower-compliance jurisdictions to launder illicit funds.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Consolidates risk ratings, regulatory profiles, and AML/CFT enforcement data for different countries and territories.
- Flags high-risk regions known for pig butchering call-center operations, enabling enhanced scrutiny of cross-border transactions.
- Assists in assessing the legitimacy of fund flows directed to or from suspicious jurisdictions.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Contains jurisdiction-specific risk indicators, AML regulations, and enforcement records. This data:

• Flags secrecy havens or countries with weak AML oversight used in offshore transfers.
• Informs risk-based analyses of cross-border flows to high-risk destinations.
• Helps prioritize enhanced due diligence for transfers involving known offshore hotspots.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Aggregates AML/CFT enforcement data, sanctions lists, and risk ratings for various countries. This facilitates the detection of red/green clause beneficiaries or intermediaries located in offshore or high-risk jurisdictions where regulatory oversight is weak.
- [Ransomware Payments](https://framework.amltrix.com/techniques/T0049.001) — - Consolidates data on high-risk jurisdictions, including unregulated or foreign-based cryptocurrency exchanges.
- Aids in flagging ransom proceeds liquidated in regions with weak AML controls or minimal regulatory oversight.
- Alerts investigators to geographic risks associated with cross-border movements of ill-gotten funds following ransomware extortion.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Provides risk ratings, relevant AML/CFT laws, and enforcement details by region.
- Flags high-risk jurisdictions known for sourcing precursor chemicals, such as certain regions in the People’s Republic of China.
- Supports enhanced due diligence on cross-border transfers and trade activity.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Consolidates risk profiles for countries and regions, including information on regulatory regimes and cross-border AML requirements.
- Identifies discrepancies when crypto ATM activity occurs in high-risk or unexpected jurisdictions, highlighting potential layering.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — Provides risk ratings and control assessments of different jurisdictions, correlating claimed residency with actual login or transaction geolocations. Identifies potential exploitation of countries with lax remote verification standards or misalignment between declared location and high-risk operation zones.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Provides risk assessments and enforcement records tied to specific regions or jurisdictions, identifying high-risk ports or countries. Flags unusual trade routes that deviate from normal patterns, helping to narrow down potential diversion schemes.
- [Wash Trading](https://framework.amltrix.com/techniques/T0094.002) — - Provides data on AML/CFT regulatory environments, enforcement levels, and risk ratings across various jurisdictions.
- Flags accounts or entities operating in high-risk or weakly regulated jurisdictions where collusive wash trading may go undetected.
- Aids in prioritizing investigations by highlighting cross-border transactions involving higher-risk regions for potential wash trading.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Identifies regulatory weaknesses and levels of secrecy in various jurisdictions.
- Highlights high-risk or offshore locations commonly exploited to create multi-layered corporate entities.
- Assists investigators in prioritizing cross-border flows for enhanced scrutiny.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Identifies offshore regions with lax licensing standards or weak AML regulations.
- Flags high-risk countries often used by illicit gambling operators seeking anonymity or minimal disclosure.

Using this data, institutions can apply enhanced scrutiny to transactions and registrations tied to suspect offshore hubs, strengthening AML efforts.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Consolidates risk profiles of countries and jurisdictions, including AML/CFT regulations, enforcement levels, and corruption indices.
- Helps pinpoint high-risk or secrecy-prone regions involved in manipulated oil trade routes.
- Informs enhanced due diligence triggers when suspicious corridors or partner jurisdictions appear in oil-related transactions.
- [Deceptive Tax Filings](https://framework.amltrix.com/techniques/T0014.007) — Provides risk classifications for countries and regions, highlighting secrecy jurisdictions or minimal tax regimes. By correlating transfers to these high-risk locales with declared income, investigators can identify structures created to conceal revenues or evade taxes, revealing deceptive filing patterns.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Aggregates AML risk profiles of jurisdictions and legal frameworks.
- Assists in flagging diamond trade routes that pass through high-risk countries with lax AML controls.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Consolidated information on high-risk regions, regulatory oversight levels, and environmental protection statuses helps identify jurisdictions known for illegal logging or weak controls. This information guides enhanced scrutiny of timber transactions from those areas.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Information on AML/CFT enforcement levels and known offshore havens across various jurisdictions.
- Flags high-risk locations used for arbitration or company registration, helping identify suspicious cross-border arrangements facilitating illicit fund transfers.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Consolidates risk profiles of jurisdictions lacking adequate valuation oversight.
- Highlights frequent jewelry transactions routed through high-risk regions, aiding in the detection of potential layering and value manipulation schemes.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Consolidates risk indicators and AML/CFT enforcement levels by country or region. Investigators can flag shipments or payments moving through high-risk jurisdictions or tax havens frequently exploited in smuggling schemes.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Consolidates information on AML/CFT laws, regulatory enforcement, and risk profiles by jurisdiction.
- Identifies high-risk or poorly regulated cryptocurrency exchanges used for layering and obfuscating beneficial ownership in this technique.
- [Insurance Beneficiary Substitution](https://framework.amltrix.com/techniques/T0089) — - Consolidates information on high-risk or secrecy-prone jurisdictions and their level of AML/CFT enforcement.  
- Identifies policyholders or beneficiaries repeatedly located in high-risk regions, flagging potential international layering tactics and highlighting anomalous cross-border insurance policy transfers.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Consolidates risk information about jurisdictions known for secrecy or limited AML transparency. Flags higher-risk proxies or beneficial owners operating from these areas, enabling deeper due diligence to identify concealed ownership.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Consolidates information on jurisdictions with elevated money laundering or sanctions risks.
- Enables identification of accounts or transactions linked to higher-risk geographies, supporting enhanced due diligence on potential mule accounts operating in or routing funds to such locations.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Consolidated information on regional risk, maritime piracy hotspots, and cross-border vulnerabilities is used to flag transactions flowing from high-risk piracy regions or carrying elevated jurisdictional risk. This aids in detecting potentially illicit ransom-related activity.
- [In-Person Gambling Imitation](https://framework.amltrix.com/techniques/T0107) — - Identifies high-risk or weakly regulated jurisdictions where gambling operations may be exploited for money laundering.
- Flags mismatches between a customer's stated location and the jurisdiction of the gaming venue or platform.
- Assists compliance teams in assessing cross-border risk exposure for in-person or hybrid gambling transactions.
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Consolidates information on country-level AML/CFT enforcement, secrecy laws, and transparency standards.
- Assists in identifying high-risk or secrecy jurisdictions involved in cross-border asset management deposits, enabling enhanced scrutiny of suspicious patterns or jurisdictional arbitrage.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Identifies high-risk states or regions known for unemployment benefit fraud, focusing monitoring efforts on claims or government disbursements originating from flagged jurisdictions and correlating unusual deposit volumes with known fraud hotspots.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Provides insight into high-risk or hawala-prevalent jurisdictions, enabling proactive risk scoring for cross-border flows that do not match customer profiles or declared business activities.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Identifies regions or jurisdictions with limited audit requirements or lax financial oversight. Entities filing restated financials or shifting accruals under such regimes raise red flags for potential accrual manipulation that might otherwise remain undetected.
- [Lottery Scams](https://framework.amltrix.com/techniques/T0144.015) — Consolidates details on countries or regions with weak or lax lottery regulations. Investigators use this data to flag entities claiming to manage sweepstakes in high-risk jurisdictions and to identify unusual transaction flows to or from known hotspots for fraudulent lottery activities.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Profile countries or regions based on their AML/CFT regulations, transparency, and level of corruption risk.
- Flag high-risk jurisdictions or secrecy havens where public officials may transfer stolen funds to hinder tracing.
- [Securities Account Ownership](https://framework.amltrix.com/techniques/T0088.001) — Consolidates AML/CFT risk indicators and beneficial ownership transparency levels across various regions, supporting the detection of:

- Securities accounts tied to secrecy-friendly jurisdictions with minimal disclosure.
- High-risk or lightly regulated industries lacking robust beneficial ownership oversight.
- Multi-jurisdictional setups that obscure the actual controllers behind accounts.

This data enables a risk-based review of complex cross-border structures used in securities account manipulation.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Offers risk insights on different regions, highlighting areas with lax regulatory oversight or secrecy laws. By detecting bond transactions or related interest payments that tie back to high-risk jurisdictions, compliance teams can flag suspicious external flows or potential regulatory evasion.

---

## [Professional Licensing & Affiliation Databases](https://framework.amltrix.com/data-sources/DS0006)

**Description:**
Databases containing information on professional roles, licenses, memberships, and affiliations.

### Related Techniques
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — Contains official licensing details, professional affiliations, and disciplinary records for attorneys, accountants, and other regulated professionals. This data helps confirm legitimate licensure, identify sanctioned individuals, and detect high-risk professional involvement in orchestrating illicit activities under confidentiality covers.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Provides official or recognized records of professional qualifications, licenses, and memberships for consulting or service-oriented entities.
- Helps verify whether firms claiming expertise are actually credentialed, revealing potential shell or front companies lacking legitimate capacity.
- Supports AML investigations by confirming professional legitimacy and identifying discrepancies between claimed and actual qualifications—key indicators of possible service contract manipulation.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Verifies the credentials of physicians or healthcare providers cited in medical documents used to justify early withdrawals, exposing falsified or non-existent practitioners involved in fraudulent hardship claims.
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Databases containing official information on the licenses, certifications, and memberships of accounting or tax professionals. This data:

- Confirms whether advisors or accountants endorsing contradictory financial statements are validly licensed.
- Identifies prior disciplinary actions or irregularities, suggesting possible complicity in underreporting earnings.
- Strengthens AML investigations by revealing unqualified or unethical professional involvement facilitating undeclared income.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Confirm the licensing status, professional memberships, and affiliations of insurance brokers or intermediaries.
- Verify whether brokers hold legitimate credentials or if they appear unlicensed.

These databases enable the detection of unauthorized or complicit intermediaries who may be facilitating illicit annuity contracts.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — Houses official records of professional licenses, memberships, and affiliations for intermediaries such as lawyers, accountants, and brokers. This data supports AML investigations by verifying the legitimacy of intermediary services and identifying unlicensed or fraudulent operators who may facilitate nominee or straw-man arrangements.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — Includes official records of real estate licensing, bar memberships, and other professional credentials. Verifying these records confirms whether timeshare brokers or attorneys are genuinely licensed or have had past violations, which is key to detecting fraudsters posing as legitimate service providers.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Provides details on licensed professionals (e.g., lawyers, accountants), their regulatory status, and affiliations.
- Reveals repeated involvement of certain professionals facilitating cross-border deals for sanctioned clients, aiding in uncovering professional enablers of evasion.
- [Real Estate Auction](https://framework.amltrix.com/techniques/T0108.001) — Databases containing official licensing and credential information for intermediaries and agents:

- Verify whether real estate auction facilitators hold valid professional licenses, helping identify suspicious or unlicensed intermediaries.
- Support detecting collusive or fraudulent practices by confirming legitimate credentials for all parties involved in the auction process.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Confirm legitimate insurance or risk management credentials for individuals controlling or operating the captive insurer.
- Highlight discrepancies between stated qualifications and actual professional affiliations, supporting suspicion of sham insurers.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — List the credentials and affiliations of third-party software developers or consultants. Investigators verify the backgrounds of individuals responsible for implementing tools that enable unauthorized transactions or document edits.
- [Unlicensed Real Estate Brokerage](https://framework.amltrix.com/techniques/T0133) — Lists professional licenses and affiliations for individuals and organizations, verifying whether a real estate intermediary holds valid licensing. This data directly identifies unlicensed brokers, supporting AML investigations where a party lacks mandatory licensure or professional standing.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Houses information on professional credentials, regulatory licenses, and affiliations. Checks against these records help detect unregistered or under-regulated advisors who may facilitate laundering through opaque investment channels.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Databases detailing legitimate professional licenses, affiliations, and regulatory memberships required in heavily regulated industries.
- Facilitates validation of specialized permits or credentials, highlighting unregistered or spurious documentation commonly used to disguise illicit activity.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Verifies supplier and distributor credentials, including licensing and professional affiliations, to help identify unlicensed entities claiming to deal in pharmaceutical products.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Houses records of professional licenses and memberships in industry bodies. Checking these databases confirms whether an investment firm or advisor is legitimately authorized to solicit funds, helping to expose unauthorized or unregistered activities consistent with fraud.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — - Verifies the licensing status, professional memberships, and affiliations of insurance providers, underwriters, and intermediaries.
- Helps identify unlicensed or lightly regulated offshore entities, highlighting potential misuse of corporate structures or shell operations to facilitate money laundering.
- [Cooperative or Mutual Institution Deposits](https://framework.amltrix.com/techniques/T0120) — - Provides information on individuals’ professional roles, licenses, and affiliations.
- Helps assess whether those taking governance positions in cooperatives or mutual institutions are qualified.
- Reveals potential infiltration by individuals with suspicious backgrounds or lacking legitimate credentials.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Holds official records of legal, accounting, and other professional licenses or memberships, including disciplinary actions and current status. Investigators can confirm an intermediary’s credentials and uncover any sanctions or regulatory violations that could indicate a higher risk for money laundering facilitation.

---

## [Commodity Market Data](https://framework.amltrix.com/data-sources/DS0009)

**Description:**
Information on commodity prices, price indices, origins, types, and values, including historical and current market trends. Financial institutions may reference this data to assess and validate commodity-related transactions in contexts such as trade finance.

### Related Techniques
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Offers reference market prices and trends for different commodities, enabling direct comparison between declared invoice values and actual market rates. Such comparisons can reveal deliberate over- or under-invoicing schemes central to commodity smuggling.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Provides commodity prices, indices, and historical market trends for agricultural products, livestock, or raw materials.
- Enables validation of reported crop or livestock prices and sales figures against real market values.
- Identifies unusual price variances or manipulated valuations used to inflate or understate agribusiness revenues in laundering schemes.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Provides real-time and historical commodity price information and market trends. 

- Enables direct comparison of invoiced commodity prices against prevailing market rates to detect over- or under-invoicing.
- Supports investigations by revealing unsubstantiated price discrepancies indicative of trade-based money laundering.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — Provides reference prices, historical valuations, and price indices for precious metals and gemstones. By comparing declared jewelry worth to credible market benchmarks, financial institutions can detect artificially inflated or deflated valuations indicative of money laundering schemes.
- [Commingling Environmental Crime Proceeds](https://framework.amltrix.com/techniques/T0057) — - Provides pricing indices, origins, and historical or current market trends for various commodities.
- Identifies transactions priced significantly above or below typical benchmark values for environmental or wildlife goods.

This data source flags inflated or undervalued trades indicative of laundering or commingling illicit proceeds.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Provides official pricing, historical trends, and benchmarks for gold.
- Allows verification of gold transaction valuations to detect potential overpricing or underpricing schemes used for laundering.
- [Inflated Transaction Pricing](https://framework.amltrix.com/techniques/T0008.002) — - Offers reliable market benchmarks, historical trends, and real-time pricing indices for various commodities.
- Enables direct comparisons of invoiced amounts to typical market rates, exposing potential overpricing in trade transactions used to disguise illicit funds.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Offers market-based diamond pricing references.
- Supports AML by comparing declared diamond values against standard market rates to identify artificially inflated valuations.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Provides confirmed market prices and benchmarks for precious metals, gemstones, and other commodities.
- Supports direct comparison of invoiced jewelry sale amounts to typical market values.
- Detects manipulated price points (e.g., grossly inflated or undervalued) used to launder proceeds.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Provides real-time and historical pricing, trade volumes, and valuations for commodities, enabling the verification of invoice amounts and product values stated in Bill of Exchange transactions. This helps detect over-invoicing or under-invoicing schemes and flags unrealistic pricing compared to prevailing market levels.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Provides real-time and historical commodity prices, indices, and market trends.
- Compares declared export invoice values to prevailing market rates or average commodity prices.
- Detects significant overpricing indicative of fraudulent export valuations.
- [Counterfeit Goods](https://framework.amltrix.com/techniques/T0143.001) — Provides reference pricing and market trends for various goods. By comparing declared product values against recognized commodity benchmarks, financial institutions can detect indications of counterfeit goods through price discrepancies or mismatches with typical market valuations. This helps identify under- or over-invoicing schemes that criminals may use to disguise the true nature and value of counterfeit products.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Pricing indexes and historical/current market values for various commodities.  
- AML Relevance: Supports the detection of inflated or underpriced commodity invoices by comparing declared trade values against real market benchmarks, revealing potential misinvoicing in fictitious trade schemes.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Presents pricing and market information for commodities, including forests and fisheries.
- Allows comparison of declared transaction values with actual market prices.
- Exposes under- or over-invoicing schemes used to launder proceeds from illegal natural resource exploitation.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Provides standard commodity values, typical volumes, and market trends for timber products. Comparing declared prices or quantities with market benchmarks can reveal suspicious underreporting or overvaluation, indicating potential misinvoicing or trade-based laundering.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Provides reference prices, indices, and historical trends for commodities such as gold or diamonds.
- Helps identify inflated or inconsistent valuations and frequent reappraisals used to manipulate asset prices in layering schemes.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Contains real-time and historical commodity pricing, including reference indices, typical market valuations, and trade volumes.
- Supports direct comparison of declared invoice amounts with prevailing market prices to identify over- or under-invoicing patterns commonly associated with trade misinvoicing.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Provides up-to-date and historical pricing, market trends, and valuations of precious commodities.
- Aids in comparing invoice or declared values against real market rates to detect mispricing consistent with smuggling or laundering.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Offers current and historical commodity pricing, enabling the comparison of declared prices against prevailing market rates. Detects overvaluation or undervaluation of goods, a common tactic in trade diversion to disguise illicit value.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Provides reference prices, historical trends, and valuation benchmarks for various commodities.
- Enables comparison of declared goods' prices against realistic market values to spot over- or under-invoicing.
- Helps validate the plausibility of trade transactions executed in free trade zones.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — - Contains historical and current prices, types, and valuation references for commodities.
- Allows comparison of declared values for precious commodities stored in bonded warehouses, aiding in spotting inconsistencies or forged certifications that may signal laundering activities.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Contains real-time and historical market values for various commodities. By comparing declared invoice prices to current market benchmarks, investigators can detect over- or under-invoicing practices, which are common indicators of illicit value transfer within trade-based money laundering.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Provides benchmark pricing and market trends for the commodities listed on trade finance invoices. By comparing declared invoice values with prevailing market rates, investigators can detect potential over- or under-invoicing schemes.
- [Shipping Document Manipulation](https://framework.amltrix.com/techniques/T0069) — Provides real-time and historical commodity pricing information, enabling direct comparison between declared values in shipping documents and actual market rates. This supports AML detection by uncovering over-invoicing and under-invoicing schemes often used to obscure illicit fund movements in trade transactions.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Provides real-time and historical market pricing for diamonds, enabling scrutiny of declared values in trade documentation.
- Assists in identifying suspiciously undervalued diamond shipments that deviate significantly from prevailing market rates.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Provides recognized market prices, indexes, and historical trends for commodities, including precious metals and gemstones. This information helps:

- Identify mispricing or undervalued/overvalued trades that may conceal illicit proceeds.
- Compare transaction values against prevailing market rates to detect significant discrepancies.
- Enhance investigations into possible fraudulent or artificial pricing schemes.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Information on commodity prices, typical market rates, and standard volumes enables institutions to compare declared shipment values and volumes against prevailing market benchmarks. This comparison can reveal inflated or unrealistic valuations often used in ghost shipping schemes.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Provides market prices, indices, and valuations for commodities like oil, including historical trends.
- Enables comparison of declared invoice values for oil shipments against real-time or benchmark pricing to detect under- or over-invoicing.
- Helps assess the plausibility of reported commodity grades and volumes used in fraudulent trade documentation.
- [Pre-Shipment Finance Manipulation](https://framework.amltrix.com/techniques/T0072) — Offers real-time and historical pricing information for commodities, including market trends and price indices. Financial institutions can compare reported export values with established market rates to detect inflated or fictitious prices indicative of pre-shipment finance manipulation.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Provides benchmark commodity prices and historical market trends.
- Comparing declared invoice pricing against prevailing market rates uncovers over-invoicing or under-invoicing, which is indicative of invoice manipulation.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Provides up-to-date and historical commodity pricing and market trends. This data assists investigators by:

- Comparing declared invoice values against market benchmarks to reveal over- or under-invoicing.
- Detecting unusual pricing patterns inconsistent with normal commodity fluctuations.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Provides standard market prices and historical trends for commodities.
- Enables detection of under- or over-valued goods in documentary collections.
- Assists in identifying misrepresentation of cargo values used to launder funds through fraudulent trade invoices.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Offers real-time and historical pricing benchmarks for goods traded on global markets. By comparing declared prices in red/green clause letters of credit (LCs) against market rates, institutions can detect over- or under-invoicing tactics commonly used to launder funds.

---

## [Contractual and Invoice Data](https://framework.amltrix.com/data-sources/DS0013)

**Description:**
Information on contractual agreements and invoices, including payment terms, parties involved, invoice identifiers, amounts, and client details. Often referenced by financial institutions to validate account activity and confirm the legitimacy of business transactions.

### Related Techniques
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Encompasses contracts, invoices, receipts, and related documentation, covering payment terms, amounts, and parties involved. This data:

- Validates the source of declared revenue by checking corresponding invoices or receipts.
- Reveals when claimed income lacks any supporting contractual or invoice documentation.
- Detects inconsistencies in amounts or transaction frequency, suggesting unrecorded or fabricated earnings.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Documents contract terms, invoices, payment references, and amounts.
- Enables the discovery of inflated or dubious consultancy and facilitation fee invoices used to mask bribe payments.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Compare stated project costs to standard market rates or industry benchmarks to identify inflated or excessive disbursements.
- Verify the authenticity and amounts of invoices to uncover potential over-invoicing or unsubstantiated charges.
- Match payment schedules to contractual milestones, flagging irregular or off-sequence payments.
- Track unexplained revisions to invoices or cost estimates that deviate from legitimate project progress.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Includes official contracts and invoices documenting the nature and value of contractor services.
- Allows AML staff to validate contractor payments within payroll, detecting any fabricated or non-existent services billed as payroll expenses.
- [Deceptive Tax Filings](https://framework.amltrix.com/techniques/T0014.007) — Includes detailed invoices, contracts, and related records underlying declared expenses or deductions. Systematic comparison with reported amounts can uncover inflated or fabricated deductions, signaling tax filing manipulations.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Includes detailed invoice and contract records tied to diamond shipments.
- Enables detection of inflated or fraudulent invoice values, corroborating repeated re-export or misdeclarations.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Contains details of contractual agreements and invoices, including payment terms, invoice identifiers, amounts, and parties. By comparing these records to official statements and transaction logs, investigators can detect forged or manipulated invoices that do not match legitimate contractual obligations.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Stores detailed records of invoices, including invoice numbers, amounts, and contractual obligations.
- Facilitates comparison of invoiced jewelry shipments against actual goods delivered or recognized market values.
- Helps isolate artificially inflated or duplicate invoices indicating contrived revenue streams.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Contains official records of vendor invoices, including invoice identifiers, itemized charges, payment terms, and amounts. These details enable thorough verification of expense claims, helping detect inconsistencies such as mismatched or inflated invoice amounts, duplicated invoice references, and nonexistent vendor relationships, which are commonly indicative of expense report fraud.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Payment terms, contractual obligations, invoice amounts, and supporting documentation.
- AML Relevance: Highlights discrepancies, inflated or forged invoices, and unusual payment schedules frequently tied to fictitious trading arrangements.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Detailed records of contractual terms, invoice amounts, payment schedules, and parties to each agreement.  
- AML Use: Facilitates scrutiny of inflated or round-figure invoices, multi-layered installment structures, and excessive fees, which can signal over-invoicing or artificially boosted valuations in player transfers or sponsorship deals.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Contains records of invoices and contractual agreements, including identifiers, amounts, and parties.
- Comparing these details with the reference numbers, values, or payee data in financial instruments can uncover forged or inconsistently stated amounts, indicating possible document manipulation.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Details agreements, invoices, and related payment documents, enabling detection of inflated or artificial service fees.
- Allows cross-checking whether reported intermediary services align with legitimate business operations.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Includes invoice amounts, contract terms, and payment instructions for goods or services provided.
- Helps detect inflated or under-invoiced transactions that may disguise sanctions evasion within trade documentation.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Contains information on contracts, invoices, payment terms, and relevant transaction references.
- Supports comparison of stated invoicing details against actual goods or services delivered, revealing potential false-invoice fraud.
- Assists in tracing the flow of generated proceeds from bogus invoicing and verifying the legitimacy of supporting documents.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Contains documentation of sponsorship or image-rights agreements and related invoices.
- Enables AML teams to validate the legitimacy of the advertised deliverables and trace payments to confirm actual sports-related activity, detecting sham or inflated contracts used for laundering.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Contains detailed information on contracts, invoices, and related payment terms, including invoice amounts, parties involved, and issuance dates.
- Provides a direct means to compare recorded accounting entries against authentic contract and invoice records, identifying over-invoicing, backdating, or fabricated documents.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Details invoices, payment terms, and parties involved, providing evidence for the legitimacy of stated commercial activities.
- Allows comparison between declared earnings and actual invoicing, detecting potential false or inflated invoicing used to mask illicit revenue.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Contains key details of contracts and invoices, such as parties involved, invoice identifiers, amounts, and payment terms.
- Cross-referencing these details against actual shipments or market data helps detect inflated, duplicated, or otherwise manipulated invoices, which are typical of invoice manipulation schemes.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Provides detailed invoices and contractual agreements, including item descriptions, amounts, payment terms, and parties involved.
- Enables cross-checking for inflated prices, repetitive anomalies, or missing product details, revealing artificially created or overstated sales transactions.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Covers the specific details of contracts and associated invoices, including fee structures, billing rates, and scope of services.
- Enables comparison of stated consulting or intermediary fees to typical industry norms, revealing inflated commissions used in loan fraud schemes.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Holds relevant contracts, feasibility studies, business plans, and invoices associated with foreign capital transfers.
- Verifies that inbound foreign investments are supported by genuine documentation, uncovering cases where large inflows lack a legitimate contractual basis.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — - Contains official invoice references and contract details, including payment terms and amounts.
- Verifies whether inbound funds align with legitimate agreements, uncovering partial or missing legitimate remittances supplanted by illicit deposits.
- [Inflated Transaction Pricing](https://framework.amltrix.com/techniques/T0008.002) — - Includes original contracts, invoices, line items, pricing details, and payment terms.
- Enables detection of inflated prices, hidden fees, duplicate invoicing, or unexplained price changes.

Financial institutions can validate invoice amounts against actual payments, revealing overcharging indicative of inflated transaction pricing.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Contains transaction invoices, payment terms, parties involved, and invoice identifiers.
- Enables verification of contract specifics (e.g., quantities, prices, contractual obligations) in free trade zone deals.
- Assists in identifying over- or under-invoicing practices common in FTZ trade-based money laundering.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Provides visibility into contract agreements, payment terms, and invoice details (invoice identifiers, amounts, and involved parties).
- Enables verification of claimed goods or services, scrutiny of credit notes or invoice adjustments, and detection of unjustified pricing variations among related entities.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — - Contains details of sale agreements, invoices, payment terms, and parties involved.
- Helps confirm the authenticity of art sale documentation, spot large cash payments or missing standard payment records, and verify the legitimacy of transactions that might be manipulated to launder funds.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Contains invoices and contracts specifying goods or services, payment terms, and pricing details.
- Detects unusual or inflated invoicing practices within affiliated entities.
- Helps confirm whether invoiced goods or services were delivered, correlating with actual transaction flows.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Holds copies of production contracts, invoices, royalty agreements, and licensing deals.
- Allows verification of authenticity, amounts, and terms of entertainment-related transactions.
- Helps detect disproportionate or suspicious fees that may be used to launder funds through bogus entertainment invoicing.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Contains contract terms, obligations, parties, billing schedules, and invoice details.
- Enables thorough review of claimed service deliverables and fee justification.
- Helps identify artificially inflated invoices, lacking or vague deliverables, and suspiciously high payments disguised as service fees.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Contains details of invoices and contractual agreements referencing specialized compliance or licensing documents.
- Enables detection of inconsistent or fictitious fee structures, issuance dates, or other discrepancies indicating forged sector permits or fabricated licensing costs.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Contains records of purported timeshare service contracts, invoices, and fee structures.
- Supports validation of whether claimed taxes, closing costs, or other charges correspond to genuine resale or exit agreements.
- Reveals discrepancies when repeated fees are collected without any documented progress toward concluding deals.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Stores and cross-references invoices or contracts submitted for subsidy eligibility, including item descriptions, amounts, and involved parties. This data helps uncover fictitious or manipulated documentation used to inflate subsidy claims.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Provides official invoice and contract details, including amounts, parties involved, and payment terms. This data helps detect inflated or duplicated invoices in Bill of Exchange transactions and confirms whether claimed values match genuine trade agreements.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Covers contracts, invoices, payment terms, parties to the agreement, and documented amounts.
- Allows verification of claimed telemarketing or call-center services and detection of sham invoices lacking credible details.
- Supports reconciliation between declared service fees and legitimate invoices or supporting documentation.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Provides invoice details, including numbers, dates, values, product descriptions, and counterparties, as well as contractual clauses.
- Allows for the verification of inconsistencies in repeated or revised settlement documents, uncovering fabricated trade values or items.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Provides invoice identifiers, amounts, payment terms, parties involved, and related details. This data is crucial for identifying duplicated or overlapping invoices, verifying consistent beneficiary information, and detecting repeated billing for the same goods or services.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Maintains official contract terms, historical invoice records, and payment instructions.
- Enables direct comparison of past and present invoice details (e.g., vendor names, addresses, bank account information) to detect subtle discrepancies indicative of impersonation.
- Supports verification of legitimate versus fraudulent invoices in accounts payable processes.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Contain detailed clauses, fee structures, and invoice data relevant to athlete image rights agreements.
- Help verify whether stated licensing or sponsorship fees are consistent with the athlete’s market value, uncovering inflated or fabricated payments used to disguise illicit funds.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — Captures contracts, invoices, payment terms, and service descriptions, enabling the comparison of stated consulting work against actual deliverables. This helps detect repetitive short-term engagements, inflated charges, or nonexistent outputs characteristic of fictitious advisory billings.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Contains contractual agreements, invoicing details, billing schedules, and supporting documentation.
- Facilitates detection of inflated fees, nonexistent services, or suspicious consulting engagements used to disguise illicit funds as legitimate revenue.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Enables scrutiny of the authenticity, amounts, line items, and parties listed on invoices or contracts. Helps identify repeated or duplicated invoices across different alleged creditors and verifies if services or goods align with the entity’s actual business activities.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Includes details of professional service contracts and invoices, documenting parties involved, fees charged, and claimed services. This information allows investigators to identify inflated, fictitious, or unjustified legal or advisory fees used to mask illicit fund transfers.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Contains invoice references, line items, contractual terms, amounts, and relevant parties.
- Facilitates detection of fabricated invoices or sham contracts used to disguise alleged loan disbursements or repayments.
- Helps investigators match transaction flows with underlying documentation to uncover anomalies in loan-back schemes.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Captures invoice and contractual details, such as product descriptions, quantities, and pricing, enabling the detection of misalignments or unusual terms that may indicate falsified medical products.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Contains records of renovation contracts, invoices, payment terms, and parties involved.
- Supports scrutiny of claimed project costs for authenticity and alignment with typical market rates, helping to identify inflated or falsified renovation invoices.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Encompasses contracts and invoices outlining payment terms, buyer/seller details, invoice identifiers, and amounts.
- Validates whether a shelf company has genuine business activities, as a lack of legitimate invoices or contracts can signify a dormant enterprise repurposed for illicit financial flows.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Provides detailed information on commercial contracts, invoices, payment terms, invoiced amounts, and descriptions of goods/services.
- Enables the identification of unusual references, such as letters of credit used to back each other, detecting circular collateral arrangements.
- Reveals repeated or inconsistent invoice references across multiple letters of credit, exposing the absence of real underlying trade.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Encompasses contracts, invoices, and associated documentation detailing goods and services.  
- Enables scrutiny of invoice descriptions, values, and counterparties to confirm legitimate chemical transactions.  
- Flags falsified or misrepresented invoices designed to hide precursor chemical procurement.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Provides invoice details, such as invoice numbers, amounts, references to goods/services, and contract terms.
- Supports the detection of fictitious invoices by identifying missing purchase orders, nonexistent delivery records, or other discrepancies that reveal fake vendor transactions.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Contains contracts, invoices, and payment terms for domestic or international transactions.
- Highlights inconsistencies between claimed trade deals and actual settlement methods, pinpointing disguised offset or net-settlement IVTS arrangements.
- Supports verification of legitimate business activity versus fabricated or inflated invoices used to conceal illicit funds.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — - Includes contract documents, purchase orders, and invoices with amounts, parties involved, and payment terms.
- Enables comparison of awarded contract prices against market benchmarks to detect inflated or deflated pricing.
- Helps identify patterns of bid rotation, abrupt price revisions, or favoritism indicating bid manipulation.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Contains formal agreements and invoices supporting inter-company transactions.
- Helps verify whether cross-border transfers between related entities are backed by legitimate documentation.
- Detects non-existent or inflated contracts often used to justify illicit fund flows in layered corporate networks.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Contains details of sales contracts and invoices, including item descriptions, payment terms, and pricing. This data allows for the verification of artifact valuations and the detection of false or inflated invoices used to launder funds through antiquities transactions.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Invoices, contracts, and related documents detail the goods or services associated with a transaction. Comparing this data with fund purposes enables the detection of discrepancies that may indicate misrepresented payments.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Contains reinsurance contracts, invoices, and billing details that may reveal unusual terms.
- Detects inflated premiums, fabricated claims, or other anomalies in contract structures.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Contains details of contracts and invoices, including payment terms, parties, amounts, and references.
- Facilitates validation of invoiced amounts against contractual obligations, exposing over-invoicing, under-invoicing, or unusual advanced/partial payments.
- Supports identification of trade-based FX manipulation through mismatched or unjustified invoicing practices.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Contains details of contracts, invoice identifiers, amounts, and goods/services.
- Facilitates detection of fabricated or altered invoices and verifies that recorded transactions match actual agreements.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Contains details on formal contracts, invoices, payment terms, and involved parties.
- Permits verification of legitimate hosting, hardware, or energy costs related to remote mining, highlighting any fabricated invoices or inflated contracts fueling illicit transactions.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Contains original invoice and contract details such as amounts, parties, and official references.
- Comparing submitted documentation to these authentic records can reveal inflated or altered invoice data, signifying possible forgeries.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Contains details of invoices, contractual agreements, amounts, and involved parties.
- Enables detection of suspicious re-invoicing practices or repeated usage of identical invoices across multiple transactions, indicating potential carousel schemes.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Provides details of contracts and invoices, including amounts, identifiers, parties, payment terms, and references to goods or services.
- Validates whether issued invoices correspond to actual commercial activities.
- Identifies fictitious or inflated invoices claiming VAT refunds in support of carousel fraud.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Shows details about invoices and contracts, including parties, amounts, and goods or services. Detects potential over-invoicing or fictitious transactions used to settle hawala obligations covertly.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Contains details of contractual agreements and invoicing (e.g., counterparts, services rendered, amounts).  
- Identifies fraudulent vendors or invoices used to route public monies into personal or third-party accounts under the guise of legitimate spending.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Includes details of commercial agreements and invoices, such as payment terms, parties involved, and invoice amounts.
- Enables verification of declared oil shipment values and allows cross-referencing with commodity market pricing.
- Helps uncover patterns of inflated or falsified invoices, which are a core element of oil and fuel transaction manipulation.

---

## [Currency Exchange Transactions](https://framework.amltrix.com/data-sources/DS0014)

**Description:**
Records of currency conversion activities, including spot trades, forward contracts, and swaps, typically covering timestamps, trading parties, exchange rates, volumes, and settlement details.

### Related Techniques
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — Records of currency exchange activities include spot trades, forward contracts, and swaps. By analyzing rates used, timestamps, volumes, and settlement details, investigators can detect inflated or deflated exchange rates, unusual patterns of currency conversions, or suspicious layering across multiple jurisdictions. This helps identify potential foreign exchange manipulation in trade.
- [Casino Mule Networks](https://framework.amltrix.com/techniques/T0011.003) — Details all foreign currency conversions, including timestamps, amounts, exchange rates, and parties involved. Helps identify repetitive or large-scale transactions with minimal legitimate justification, highlighting layering activities in casino-based money laundering schemes.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Maintains records of currency conversions, including timestamps, exchange rates, trading parties, and settlement details.
- Identifies repeated or structured foreign exchange transactions used to layer proceeds from smuggled diamonds across multiple currencies, thwarting investigative traceability.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Provides detailed records of all fiat currency exchanges, including timestamps, exchange rates, volumes, and counterparties.
- Enables detection of repeated high-value conversions and structured sub-threshold exchanges, which are indicators of layering in illicit currency swaps.
- Allows tracing of suspicious cross-currency movements that obscure the origin of funds.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Documents currency conversions, including timestamps, volumes, exchange rates, and counterparties.
- Identifies frequent or unexplained multi-currency exchanges that lack a legitimate business rationale, which is a red flag for funnel account usage.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Logs details of currency conversions, including timestamps, exchange rates, volumes, and trading parties.
- Allows comparison of exchanged amounts abroad with initially declared sums.
- Facilitates detection of layering or disproportionate exchanges used to disguise the origin of funds.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — Provides records of currency conversions, including timestamps, parties, exchange rates, volumes, and settlement details. By analyzing frequent or unjustified cross-currency activity, investigators can identify hidden layering or suspicious payment routing in different currencies.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Records of currency conversions (e.g., spot trades, forwards, swaps), including timestamps, trading parties, exchange rates, traded amounts, and settlement details.

- Direct AML Relevance: Supports detection of parallel or excessive exchange rates, disproportionate volumes of currency conversions, and other anomalies that may signal Black Market Peso Exchange transactions.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Contains records of all currency conversion activities (spot trades, forward contracts, swaps), including timestamps, involved parties, exchange rates, transaction volumes, and settlement details.
- Facilitates detection of repeated cross-currency trades or suspicious layering patterns.
- Helps identify incremental or small-denomination transactions structured below thresholds.
- Supports investigation of transaction flows inconsistent with usual hedging or routine business activities.
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Detailed records of currency conversions, including spot trades, timestamps, exchange rates, and settlement details. Analyzing these data alongside travel records can reveal suspicious exchanges of large notes for smaller denominations (or vice versa), indicating possible physical transport of illicit funds.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — Provides comprehensive records of currency conversion activities, including spot trades, forward contracts, and swaps. It captures timestamps, exchange rates, volumes, counterparties, and settlement details to identify repeated or high-volume conversions in high-risk jurisdictions. This enables the detection of suspicious foreign exchange patterns and anomalies that deviate from established customer profiles.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — Centralizes records of currency trades, including timestamps, exchange rates, and volumes. Enables the detection of high-volume or unauthorized currency exchanges, a common practice of unlicensed MSBs.
- [Cross-Border Cash Smuggling](https://framework.amltrix.com/techniques/T0065) — - Track the conversion of smaller denominations into larger notes near travel dates, reducing bulk and aiding clandestine transportation.
- Record exchange rates, volumes, and counterparties to reveal abnormal pre- or post-travel exchange activity.
- Aid in detecting the refining of currency specifically intended to evade cross-border detection.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Detailed records of currency conversions cover timestamps, exchange rates, volumes, and involved parties. This data exposes frequent cross-currency swaps and rapid layering activities across multiple denominations, helping detect potential structuring and arbitrage maneuvers.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Documents foreign currency exchange activities, including volumes, timestamps, exchange rates, and parties involved.
- Flags suspiciously frequent or high-value exchanges unrelated to a customer’s normal business or income.
- Helps trace the possible conversion of illicit cash across borders as part of courier operations.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Record details of foreign currency conversions, including timestamps, rates, and involved parties.
- Help detect sudden or large-scale forex activity by officials that does not match legitimate government expenditures, indicating possible layering.

---

## [Transaction Logs](https://framework.amltrix.com/data-sources/DS0019)

**Description:**
Comprehensive records of financial transactions across all channels, capturing both account details (e.g., ownership, balances) and transaction data (e.g., timestamps, amounts, currencies, parties, transaction identifiers). This includes deposits, withdrawals, wire transfers, card payments, ATM usage, investment trades, remittances, gaming transactions, peer-to-peer transfers, cryptocurrency flows, and other forms of money movement.

### Related Techniques
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Provides comprehensive details of financial transactions, including timestamps, amounts, and involved counterparties.
- Enables detection of unusual routing through intermediary accounts, repeated usage of the same intermediary, or abrupt changes in intermediary usage patterns indicative of layering.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Provides comprehensive records of each financial transaction, capturing the initiator, time, amount, and the accounts involved. Helps detect potential proxy usage by identifying initiators who are not the registered owner or signatory and flagging patterns inconsistent with the known account holder.
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Provides detailed records of financial transactions (e.g., timestamps, amounts, counterparties, and channels).
- Facilitates detection of patterns such as multiple small-value deposits, sub-threshold structuring, and frequent peer-to-peer payments.
- Helps identify anomalies in cash-intensive business operations, supporting investigations into potential laundering of illicit proceeds derived from common offenses.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Captures all financial transactions, including amounts, timestamps, parties, and account details.
- Enables detection of smurfing or structuring patterns, common at the placement stage of illicit proceeds from commodity trafficking.
- Provides a transaction trail for tracing funds used in the purchase or sale of illicit commodities.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Captures inbound timeshare-related fees or deposits from victims, including timestamps, amounts, and payor details.
- Traces subsequent onward transfers, particularly rapid or high-volume outflows to unrelated or offshore accounts, revealing suspicious fund flows lacking legitimate timeshare resale or exit activity.
- Enables pattern analysis of repeated inbound payments labeled as taxes, closing costs, or marketing fees.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Includes comprehensive records of each financial transaction, capturing timestamps, amounts, counterparties, and related metadata.
- Enables detection of sudden surges in token purchases or repeated high-value transactions during fundraising.
- Assists investigators in tracing subsequent money flows from the token sale to other wallets or accounts, revealing potential layering or fraudulent activities.
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Provides timestamps, amounts, and transaction channels (e.g., ATM, teller, online) for withdrawals.
- Enables detection of structured patterns, such as multiple withdrawals under reporting thresholds, and rapid cash-outs following electronic deposits.
- [Financial Product Overfunding](https://framework.amltrix.com/techniques/T0086) — - Captures detailed financial transaction data, including deposit and withdrawal amounts, timestamps, involved parties, payer details, and related metadata.
- Enables detection of overfunding patterns, such as excessive deposits above normal thresholds, and subsequent requests for partial or early withdrawals.
- Identifies third-party payments made to policies or accounts, helping to flag unsupported relationships between payers and policyholders.
- Facilitates tracing of layering activity across multiple institutions or jurisdictions by examining the timing and sequencing of transactions.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Provides timestamps, amounts, and account identifiers for each superannuation withdrawal, enabling the detection of multiple or closely timed early withdrawal requests. Investigators can correlate the frequency and timing of withdrawals with suspicious documentation patterns.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Provides detailed records of all financial transactions tied to insurance policies, including timestamps, amounts, beneficiary details, and counterparties. This data helps detect irregular or rapid funding and redemption patterns indicative of potential layering and illicit fund movements through offshore insurance products.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Provides detailed records of premium payments, claim payouts, refunds, and other insurance-related transactions to identify suspicious or inflated amounts.
- Enables detection of layering schemes through frequent or structured cross-border payments.
- Reveals patterns of early cancellations, large refunds, or partial surrenders inconsistent with typical insurance practices.
- [Cash Wage Payments to Undocumented Workers](https://framework.amltrix.com/techniques/T0052.001) — - Provides a record of cash withdrawals and financial transactions, including timestamps, amounts, and account details.
- Helps detect patterns of recurring, unexplained cash withdrawals coinciding with typical payroll periods, indicating off-the-books wage disbursements to undocumented workers.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Records all wire transfers and associated metadata, including timestamps, amounts, sender/receiver details, and reference fields.
- Enables the comparison of declared trade values in cross-border settlement documents with actual transaction amounts, helping to detect inflated or fabricated payments.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Contains comprehensive records of financial transactions, including deposits, withdrawals, checks, and transfers.
- Facilitates matching of actual wage-related outflows with reported payroll amounts, identifying large cash withdrawals or unexplained transfers during payroll cycles.
- Aids in uncovering off-the-books payments and discrepancies in reported wage expenses.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — Transaction logs provide complete records of all credit card and payment transactions, including:

- Timestamps, transaction amounts, merchant details, and customer account identifiers.
- Dispute data capturing who initiated chargebacks, when, and for how much.

These details directly help identify suspicious patterns of recurrent chargebacks, collusion between merchants and customers, or attempts to keep dispute ratios low by managing transaction volumes.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Provides comprehensive records of financial transactions, including timestamps, amounts, origin and beneficiary account details, and references.
- Detects suspicious changes in vendor payment instructions or unusual layering and funneling of stolen funds.
- Helps reveal anomalies in payment patterns consistent with vendor impersonation.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Captures all wire transfers, including timestamps, amounts, currencies, and counterparties.
- Enables pattern detection of multiple, rapid wire transfers across accounts or jurisdictions indicative of layering.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Captures all account and transaction details, including timestamps, amounts, currencies, and counterparties. This enables the detection of frequent high-value or cross-border transfers initiated by entities lacking any physical presence. Such patterns can indicate potential layering or integration efforts characteristic of virtual company structures.
- [In-Person Gambling Imitation](https://framework.amltrix.com/techniques/T0107) — Records all external financial inflows and outflows to gambling accounts, including timestamps, amounts, and counterparty details. This data enables the tracing of cross-border layering, repetitive structured deposits or withdrawals, and potential commingling of illicit funds leveraging gambling platforms.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — Captures transaction origin IP addresses, timestamps, amounts, and involved parties, enabling cross-referencing of IP data against known proxy or suspicious hosting providers. This helps investigators detect potential anonymizing service usage, such as Tor, VPNs, or rotating proxies, and identify high-risk connection behaviors that mask the user’s true location.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Records the details of every financial disbursement, including amounts, timestamps, recipients, and account references for payroll payments.
- Helps detect repeated payroll disbursements to the same individuals, multiple employees sharing the same bank account, and other anomalies indicative of ghost employees or fictitious wages.
- [Peel Chain](https://framework.amltrix.com/techniques/T0070.002) — Comprehensive records of deposits, withdrawals, and other monetary movements across user accounts capture timestamps, amounts, account identifiers, and counterparties. These logs help correlate on-chain peel chain hops with off-chain transactions, revealing patterns of rapid micro-transfers and layering attempts.
- [Undisclosed Payment Aggregation](https://framework.amltrix.com/techniques/T0138) — - Provide comprehensive records of transactions, including deposit amounts, timestamps, payer/recipient details, and transaction identifiers.
- Enable detection of suspicious patterns, such as sudden settlement spikes, repetitive small-value deposits, or the commingling of multiple merchants’ funds into a single TPPP/aggregator account.
- Support uncovering unusual refund or credit activities indicative of illicit mixing of proceeds.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Provide complete records of inbound and outbound transactions, including payment references or memos.  
- Reveal patterns such as multiple small inbound transfers from unrelated payers followed by quick onward forwarding.  
- Directly support AML investigations by highlighting suspicious movement of funds and unusual references connected to social media-based recruitment schemes.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Provide detailed records of inbound and outbound financial transactions, including timestamps, amounts, and counterparties.
- Monitor claimed export reimbursements and subsequent fund flows to identify anomalies or suspicious layering.
- Detect rapid transfers and multi-step movements that obscure the ultimate beneficiaries of overvalued export proceeds.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Comprehensive records of all financial transactions (timestamps, amounts, currencies, parties, etc.) linked to the sports club’s accounts.  
- AML Use: Allows detection of large, frequent, or unexplained capital injections and suspicious transaction patterns that may indicate inflated player fees, hidden sponsorship inflows, or other laundering tactics tied to club financing.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Logs both inbound and outbound account activity with timestamps, amounts, and references, helping to directly correlate cash introductions at borders with subsequent cryptocurrency purchases or sales indicative of NEP methods.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Provides timestamps, amounts, currencies, counterparties, and geographic details for payments and deposits.
- Enables identification of frequent cross-border transactions with tobacco suppliers in low-tax jurisdictions, supporting detection of inconsistencies with stated import duty or customs documentation.
- Facilitates monitoring of large or repetitive cash deposits that exceed normal retail cigarette sales volumes, indicating potential smuggling proceeds.
- [Daigou Networks](https://framework.amltrix.com/techniques/T0013.006) — Provides comprehensive financial transaction records, enabling the detection of the following Daigou-related red flags:

- Repeated or large-volume purchases of high-value consumer goods, suggesting surrogate shopping on behalf of others.
- Rapid succession of cash deposits followed by cross-border transfers for suspected luxury goods purchases.
- Transaction references indicating purchases ‘on behalf of friends or clients’ without formal business arrangements.

This data supports investigators in identifying unusual spending patterns, layered transactions, and potential straw buyer activities linked to Daigou networks.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Comprehensive records of financial transactions detail senders, recipients, amounts, and timestamps. 

- Enable detection of third-party payments not listed on official trade documentation.
- Assist in identifying unusual funding patterns that suggest trade-based money laundering.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Captures inbound and outbound transaction details, including timestamps, amounts, and counterparties, across agent or sub-agent accounts.
- Reveals patterns of structured deposits and layering, including multiple sub-threshold transactions.
- Enables tracing of funds through different payment providers or aggregators, helping identify hidden links in the payment chain.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Provides a complete record of all financial transactions across accounts (e.g., deposits, withdrawals, transfers). This data enables investigators to:

- Identify recurring high-value or otherwise suspicious deposits that lack a legitimate explanation.
- Detect suspicious transaction references (e.g., 'forced donation') or narratives indicative of coerced funds.
- Recognize rapid transfers from receiving accounts to intermediaries shortly after deposit, suggesting layering of extorted proceeds.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Provide comprehensive records of financial transactions, including timestamps, amounts, currencies, counterparties, etc., across all channels.
- Enable the identification of repeated manual overrides, suspiciously rapid approvals, or high-risk transaction patterns tied to specific employees, revealing potential insider collusion or bypass of established AML checks.
- [Peer-to-Peer (P2P) Transfers](https://framework.amltrix.com/techniques/T0134.001) — Provides granular transaction data, enabling the detection of repeated peer-to-peer (P2P) transfers just below regulatory reporting thresholds, a common tactic for structuring.
- [ATM Structuring](https://framework.amltrix.com/techniques/T0016.004) — - Provides detailed records of all deposits, withdrawals, timestamps, and amounts, enabling investigators to identify frequent, low-value ATM transactions that aggregate just below reporting thresholds.
- Allows cross-referencing with account data to confirm whether multiple individuals (smurfs) are depositing into the same account, thus revealing potentially structured deposits under threshold limits.
- Facilitates pattern analysis of repeated amounts and deposit intervals to detect suspected ATM structuring schemes.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Provides itemized records of financial transactions (e.g., dates, amounts, counterparties).
- Enables investigators to spot recurring or unusually large invoiced amounts disguised as jewelry sales.
- Facilitates cross-referencing transaction patterns with market benchmarks or shipping records to identify fictitious or inflated activity.
- [Chain Hop](https://framework.amltrix.com/techniques/T0005) — - Captures detailed records of deposits, withdrawals, and transfers, including timestamps, amounts, and account identifiers.
- Enables detection of unusual patterns where frequent crypto conversions are combined with fiat transactions to obscure cross-chain activities.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Captures granular transaction details, including timestamps, amounts, currencies, account identifiers, and metadata for each donation or payment flow.
- Enables the identification of suspicious spikes in donation activity, rapid layering attempts, and cross-referencing of multiple high-risk donor sources or incomplete donor information.
- Assists investigators in detecting anomalies such as unusually large or frequent donations that are inconsistent with typical funding patterns.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Captures timestamps, amounts, involved parties, and account identifiers for all financial transactions.

This data reveals transaction patterns linked to diplomatic or state-owned entities, including large or frequent cash movements, cross-border transfers, and potential structuring or layering activities, assisting AML teams in flagging suspicious flows under diplomatic cover.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Provides detailed records of financial transactions, including timestamps, amounts, accounts, and parties involved.
- Enables identification of patterns such as large or frequent purchases of luxury goods or precious metals beyond a customer’s typical financial behavior, supporting detection of potential laundering through high-value asset conversions.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Provides comprehensive records of financial transactions, including timestamps, amounts, counterparties, currencies, and account details.
- Enables detection of unusual transaction flows or persistent transfers to sanctioned entities, indicating possible sanctions evasion strategies.
- [Loyalty Points](https://framework.amltrix.com/techniques/T0106) — Transaction logs capture detailed records of loyalty point purchases, conversions, redemptions, and transfers, including timestamps, amounts, account identifiers, and cross-platform movements. These data points are critical for identifying unusual volume or frequency of loyalty point transactions, detecting cross-border or multi-jurisdiction transfers, and flagging rapid acquisition or redemption patterns indicative of layering or laundering activities.
- [Counterfeit Currency](https://framework.amltrix.com/techniques/T0092) — - Provides detailed records of financial transactions, including timestamps, amounts, denominations, and account details.
- Enables identification of suspicious deposit patterns (e.g., repeated small-denomination deposits, sub-threshold structuring, or sudden spikes).
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Provides comprehensive details on financial transactions, including timestamps, amounts, parties involved, and account references.
- Enables detection of unusual or repetitive transaction patterns that may indicate fraudulent funding or layering of newly acquired proceeds.
- Facilitates verification of transaction authenticity and cross-checking against reported invoices or contracts in fraud schemes.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Provides comprehensive records of financial transactions, including timestamps, amounts, and counterparties.
- Reveals suspicious layering patterns, structured deposits, or rapid fund movements associated with shell companies.
- Enables comparison of transactions against the entity’s stated business activities to detect mismatches.
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Captures detailed deposit amounts, frequencies, cross-border wires, sub-account transfers, and other transaction metadata (e.g., timestamps, counterparties).
- Enables detection of large lump-sum deposits from multiple unassociated sources, frequent reallocations of funds, and complicated layering strategies that indicate potential misuse of asset management accounts.
- [Ponzi Schemes](https://framework.amltrix.com/techniques/T0144.019) — Track all monetary inflows from new investors, outflows to earlier participants, and inter-account transfers. This enables investigators to identify the recycling of funds, short holding periods, and layering consistent with Ponzi-like operations, as well as detect the absence of genuine revenue generation.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Captures detailed records of in-game financial transactions, including timestamps, amounts, counterparties, and transaction identifiers.
- Helps detect suspicious patterns such as unusually large or rapid microtransactions, repetitive purchases of in-game currency using stolen payment methods, or swift conversions back into fiat or cryptocurrency.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Provides comprehensive records of deposits, withdrawals, wire transfers, and other transactions, including timestamps, amounts, and counterparties.
- Facilitates detection of unusually frequent or structured cash deposits, funneling patterns, and cross-border transfers tied to suspected drug proceeds.
- Helps investigators trace the flow of funds and identify layering or integration steps used by criminal enterprises involved in drug trafficking.
- [Underground Gambling](https://framework.amltrix.com/techniques/T0107.007) — - Captures comprehensive financial transactions across accounts, including timestamps, amounts, parties, and transaction types.

- Reveals external flows of funds into or out of suspected gambling operations, highlighting unusual transfers or large cash movements tied to suspected underground venues.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Provide a comprehensive record of all financial transactions, including timestamps, transaction identifiers, amounts, and cross-border details. Tracking deposit frequencies, reload behaviors, and offshore flows helps uncover structuring, micro-deposits, and suspicious layering in prepaid and e-wallet accounts issued by secrecy-jurisdiction providers.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Detailed records of all financial transactions, including timestamps, amounts, initiating parties, and references to mergers and acquisitions (M&A). Investigators can identify unusually large or frequent merger-related payments, detect rapid layering maneuvers across multiple accounts, and uncover patterns inconsistent with legitimate corporate acquisitions, signaling possible fictitious or manipulative M&A activity.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Captures comprehensive transaction details, including timestamps, amounts, counterparties, and payment references, enabling the detection of suspicious or unexplained payments.
- Supports investigations into bribery by correlating abnormal transfers with key decision-making periods or official involvement.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Records all financial flows labeled as sponsorship or image-rights payments, including timestamps, amounts, and counterparties.
- Enables investigators to detect unusually large transactions, sudden spikes in club funding, or repetitive layering through multiple accounts, exposing potential money laundering patterns in sports sponsorship deals.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Capture comprehensive details of financial transactions, including timestamps, amounts, parties involved, and transaction identifiers.
- Facilitate direct comparison of actual transaction data with reported accounting entries. This helps detect backdated or altered financial records and identify discrepancies in recorded revenues or expenses.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Captures details of financial transactions, including timestamps, amounts, currencies, and involved parties. These records help identify unusual wage payment patterns, large cash withdrawals, or the commingling of legitimate payroll with forced labor proceeds. By analyzing transaction flows, investigators can detect structuring or layering schemes associated with forced labor earnings.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Provides comprehensive records of financial transactions across accounts and channels, covering timestamps, amounts, currencies, parties, and transaction methods.
- Enables investigators to trace and identify suspicious or unusual payment patterns potentially linked to illicit proceeds derived from child exploitation, such as repeated small deposits, irregular layering attempts, or funneling across multiple accounts.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Provides comprehensive records of financial transactions, including timestamps, amounts, currencies, parties, and transaction identifiers.

- Enables investigators to pinpoint high-value or repetitive transfers that could indicate proceeds from arms sales, and flags suspicious transaction patterns or unusual flows linked to potential illicit arms dealings.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Provides detailed records of both in-game and external financial transactions, including timestamps, amounts, parties, and transaction IDs. This data enables the identification of unusual patterns, such as numerous small-value card charges, rapid conversions to or from in-game currencies, or cross-platform item trades, which may indicate potential money laundering through virtual worlds.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Provides comprehensive records of financial transactions, including date, time, amounts, payors, payees, and transaction references.
- Enables detection of multiple or structured commodity purchases below reporting thresholds, which may indicate smuggling or layering strategies.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Contains detailed records of all financial transactions, such as deposits, withdrawals, transfers, timestamps, amounts, and counterparties, for real estate or property-management accounts.

- Allows investigators to identify patterns of commingled funds, unusual spikes in rent or service fee deposits, and repetitive transactions that may indicate layering in high-cash-flow real estate operations.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Captures all financial transactions with timestamps, amounts, currencies, and involved accounts.
- Highlights sudden surges in conversion volume or after-hours activity, revealing potential layering or obfuscation patterns.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Comprehensive records of financial transactions across accounts, including timestamps, amounts, currencies, and counterparties.
- Enables correlation of currency exchange activity with subsequent layering transactions to different accounts or jurisdictions.
- Assists in tracing the flow of converted funds through multiple financial channels.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Provides detailed records of all deposits, withdrawals, transfers, and related metadata, including timestamps, amounts, and counterparties.
- Enables detection of structured deposits below reporting thresholds and rapid inbound-outbound flows, directly revealing funnel account patterns.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Details financial transactions, including timestamps, amounts, and originating/destination accounts. By mapping the flow of timber sale proceeds, it reveals suspicious fund movements, layering, or rapid transfers commonly associated with laundering illicit logging revenues.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Provides records of actual cash inflows and outflows, including timestamps, amounts, counterparties, and transaction identifiers. Investigators can compare these real transaction flows against accrual-based revenue or expense entries in financial statements to detect discrepancies indicative of potential accrual manipulation.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Captures timestamps, amounts, beneficiaries, counterparties, and transaction metadata for all incoming and outgoing funds.
- Helps identify unusual increases in revenue, inconsistent transaction volumes, or other patterns indicating potential commingling of illicit proceeds within legitimate sales.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Provides comprehensive records of financial transactions, including timestamps, amounts, currencies, parties, and transaction identifiers, related to the purchase or sale of collectibles.
- Enables detection of transactions priced significantly above or below typical market values, revealing possible price manipulation.
- Helps identify repeated consecutive sales of the same item with inconsistent pricing, suggesting intentional layering or artificial inflation.
- Facilitates recognition of structured transactions deliberately kept below thresholds to avoid AML scrutiny.
- Allows monitoring of sudden spikes in activity for customers with no prior record of high-value collectible trading.
- [Anonymous Networking](https://framework.amltrix.com/techniques/T0015) — - Records timestamps, amounts, currency types, and parties involved in each financial transaction.
- Facilitates the identification of recurring or structured transactions initiated from anonymizing networks, enabling pattern analysis of unusual transaction frequencies or amounts masked by hidden IP addresses.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Provides comprehensive transaction details such as timestamps, amounts, currencies, counterparties, and transaction identifiers across various channels.
- Enables detection of sub-threshold structuring, frequent batch transfers, and recurring, precisely timed payments—key indicators of automated layering.
- Helps identify abnormal transaction velocities and repeated uniform amounts consistent with scripted or algorithmic transfer activity.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Identify large or unusual cash-based inflows or outflows that finance construction costs, highlighting potential over-invoicing or layering steps.
- Track payment schedules and amounts, detecting irregular intervals or suspicious recipient accounts, such as shell entities.
- Reveal foreign or unknown funding origins, flagging high-risk jurisdictions or unverified investor sources.
- Monitor excessive payroll or wage disbursements to non-verified individuals, revealing ghost employees or inflated labor costs.
- Expose the misdirection of NGO or charitable funds intended for construction into personal or affiliate accounts.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Provides detailed records of financial and in-game transactions, including timestamps, amounts, currency types, and account identifiers.

- Enables detection of suspicious layering or structuring patterns where in-game tokens are acquired and rapidly converted back to fiat or cryptocurrency, facilitating early detection of potential laundering schemes.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Comprehensive records of financial transactions include declared payment purposes, timestamps, amounts, currencies, and counterparties. This data helps identify frequent or unauthorized modifications to stated fund purposes, revealing potential misrepresentation.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Provide detailed records of incoming and outgoing funds, timestamps, and counterparties.
- Help identify patterns of immediate pass-through transactions or unusually high volumes consistent with money mule activities.
- Support detection of repeated incoming credits from unknown payors followed by rapid onward transfers.
- [Darknet Marketplace Transactions](https://framework.amltrix.com/techniques/T0100) — - Contains detailed records of all financial transactions, including fiat deposits/withdrawals, transfers, and card payments.
- Enables investigators to correlate spikes in account activity with inbound or outbound cryptocurrency flows tied to Darknet marketplace transactions, revealing potential layering or sudden volume anomalies.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Comprehensive records of financial transactions, highlighting amounts, dates, senders, and ultimate beneficiaries of arbitration-related transfers.
- Supports identifying large or layered fund movements labeled as 'arbitration awards,' flagging discrepancies between named litigants and actual recipients.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Provides comprehensive records of account ownership, balances, and transaction details, including timestamps, amounts, currencies, and parties. In corruption cases, these logs help trace suspicious fund flows, identify layered transactions, and detect anomalies that exceed a public official’s legitimate income sources.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Provides detailed records of all money flows, including credits, debits, timestamps, and parties involved.
- Enables investigators to identify structuring, funnel account usage, or other suspicious patterns tied to the proceeds of forced prostitution or sexual exploitation.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Provides comprehensive records of purchases, sales, and related financial transactions for jewelry.
- By identifying repeat transactions of the same piece at inconsistent valuations, financial institutions can detect possible layering attempts or artificial price manipulation.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Capture deposit timestamps, transaction amounts, account identifiers, and subsequent fund movements to reveal repeated submissions of the same or near-identical checks and rapid outflow patterns. These logs directly aid in the AML detection of suspicious remote deposits and quick withdrawals.
- [Insurance Policy Overfunding](https://framework.amltrix.com/techniques/T0090.002) — - Captures premium payment amounts, frequency, and timing, enabling the detection of overfunding or multiple high-value payments to insurance policies beyond typical requirements.
- Shows funding sources, including third-party or cash-based contributions, highlighting potential layering or illicit inflows.
- Tracks policy refunds, partial surrenders, or withdrawals, revealing suspicious early redemptions and rapid fund movements indicative of money laundering.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Provides timestamps, amounts, currency types, sender/receiver account details, and transaction identifiers for all financial movements.
- Enables detection of unusual spikes in crypto investments, frequent transfers to new wallets, and rapid outflows indicative of pig butchering scam activity.
- Supports investigation by correlating suspicious transaction patterns with potential scam communications or high-risk jurisdictions.
- [Geographically Dispersed Cash Deposit](https://framework.amltrix.com/techniques/T0053) — - Captures deposit timestamps, amounts, branch or institution identifiers, and account details.
- Helps detect patterns of structured cash deposits below reporting thresholds across multiple locations to obscure the source of funds.
- Facilitates monitoring of rapid or sequential deposits by multiple individuals, enabling quick identification of potential smurfing activity.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Captures comprehensive records of financial transactions from newly opened or existing accounts. Sudden high-value or rapid transaction patterns linked to questionable identity documentation can be identified and flagged, helping to expose potentially manipulated or fraudulent account setups.
- [Third-Party Payments](https://framework.amltrix.com/techniques/T0073) — Captures all incoming and outgoing payments, including payer details, timestamps, and transaction references. This allows institutions to identify recurrent or unusual third-party payers who have no apparent relationship with the primary account holder, helping to flag potential attempts to obscure beneficial ownership.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Contains comprehensive records of financial transactions, including fiat-to-crypto conversions, timestamps, amounts, and counterparties.
- Reveals frequent, large-value conversions associated with layering intentions, aiding in uncovering suspicious fiat-to-cryptocurrency entry points for this technique.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Transaction logs from crypto ATMs capture deposit and withdrawal amounts, timestamps, and user or wallet identifiers. This data enables the detection of structuring attempts, such as repeated sub-threshold deposits, rapid consecutive deposits, and suspicious transaction bursts, supporting investigations into layering or unusual activity patterns.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Tracks financial transactions in detail, capturing timestamps, amounts, counterparties, and account balances. This data helps pinpoint large or unusual commodity purchases by parties with no historical engagement in that sector, suggesting possible smuggling activity.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — - Provides detailed records of financial transactions—including amounts, timestamps, parties, and routing details—that help identify large or irregular lobbying or campaign donations.
- Enables detection of multiple reimbursements from a single source, highlighting potential straw donor schemes.
- Assists in tracing funds routed through intermediaries or shell entities to uncover suspicious donation patterns.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Captures each financial movement, including timestamp, amount, counterparty details, and channel, tied to the compromised account.

- Helps investigators identify abnormal transaction patterns, unusually high-value transfers, or other anomalies occurring shortly after unauthorized account access.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Comprehensively records transaction details, including loan disbursements, repayment amounts, and related parties.
- Helps identify mismatched repayment patterns, phantom goods payments, or unusual flows inconsistent with legitimate trade finance arrangements.
- [Cross-Border Cash Smuggling](https://framework.amltrix.com/techniques/T0065) — - Capture deposits, withdrawals, and transfers, including timestamps, amounts, and denominations.
- Enable correlation of suspicious cash deposits or withdrawals with recent cross-border travel.
- Reveal patterns of structuring or repeated transactions just below reporting thresholds after international trips.
- [Payroll Deduction Loan Repayment](https://framework.amltrix.com/techniques/T0029) — - Provide comprehensive records of financial transactions, including timestamps, amounts, parties, and transaction codes, related to payroll-deduction installments.
- Enable the detection of disproportionate or accelerated loan repayments that do not align with the borrower’s legitimate salary or normal pay cycles.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Provide a detailed record of cash withdrawals and transfers, including timestamps, amounts, and account details.
- Tracking frequent or large cash withdrawals aligned with payroll cycles can detect illicit wage disbursements concealing illegal funds.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Provides comprehensive records of deposits, withdrawals, timestamps, amounts, and counterparties.
- Enables detection of patterns such as multiple small deposits, rapid withdrawals, and mismatches between deposit and withdrawal addresses—key indicators of custodial mixer usage.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Tracks deposit timestamps, amounts, and counterparties, along with subsequent onward transfers.
- Enables investigators to identify suspicious inflows soon after a victim responds to a phishing-based job offer.
- Reveals transaction patterns consistent with money mule activity, such as near-immediate onward transfers and unexplained incoming funds.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Captures all financial transactions, including timestamps, amounts, parties, and transaction IDs, across different channels.
- Facilitates the detection of co-mingled legitimate and suspicious contributions, helping to identify layering or rapid fund movement characteristic of fraudulent fundraising schemes.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Provide comprehensive records of financial transactions, covering dates, amounts, parties, and counterparties.
- Enable detection of rapid layering or structuring of disbursed relief funds into personal or third-party accounts lacking legitimate business purposes.
- Support tracing of illicit proceeds across accounts or geographies, revealing suspicious fund flows.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Encompasses all financial transactions, including account or ownership references, timestamps, amounts, and counterparties. Correlating changes in beneficial ownership with transaction details can expose suspicious sequencing, layering, or asset movement.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Contain detailed transaction records (e.g., timestamps, amounts, involved accounts, and transaction references). Investigators compare original entries with altered records to uncover suspicious modifications or forged data, directly indicating digital document manipulation.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Logs capture all financial inflows and outflows, including timestamps, amounts, sender and recipient account details, and channels used. By analyzing transaction patterns, investigators can identify rapid transfers, layered movements, or other anomalies indicating potential misuse of government relief funds.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Maintains detailed records of inter-company payments, including timestamps, amounts, and parties involved.
- Helps identify unusual or frequent cross-company transfers that lack an economic rationale.
- Correlates with invoice or contractual data to detect fabricated or inflated billing among affiliated entities.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Capture details on transactions (timestamps, amounts, counterparties) to identify unusual or high-risk activity linked to newly created or impersonated accounts.
- Facilitate pattern analysis to detect abrupt large transactions soon after opening accounts with questionable identity credentials.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Captures detailed transaction records, including timestamps, amounts, currencies, sender/receiver details, and reference IDs, for both domestic and cross-border payments.
- Enables detection of repeated or structured flows to and from secrecy jurisdictions, revealing potential layering and unusual routing of funds.
- Facilitates pattern analysis to spot anomalies or deviations from a customer’s typical profile, highlighting offshore exploitation risks.
- [Smurfing](https://framework.amltrix.com/techniques/T0016.005) — Provides detailed records of financial transactions, including timestamps, amounts, depositors, recipients, and channel information. This directly supports smurfing detection by:

- Identifying numerous low-value deposits deliberately kept below reporting thresholds.
- Aggregating transaction data to reveal hidden connections among accounts or depositors.
- Highlighting patterns of frequent small deposits or withdrawals consistent with smurfing behavior.
- [NFT-based Value Obfuscation](https://framework.amltrix.com/techniques/T0064) — - Provides comprehensive records of financial transactions, linking fiat inflows and outflows to NFT trades.
- Enables identification of funds that enter or leave regulated channels immediately following high-value NFT sales, suggesting potential layering or integration steps.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Captures detailed records of all financial transactions, including carbon credit payments, rapid cross-border fund transfers, and subsequent outflows to high-value purchases or offshore accounts.
- Facilitates tracing the frequency, volume, and timing of transactions to identify anomalies, such as unusually large or frequent carbon credit trades lacking commercial rationale.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Captures comprehensive records of financial transactions, including amounts, timestamps, currencies, and counterparties.
- Supports detection of sub-threshold structuring or frequent cross-border wires consistent with smuggling proceeds.
- Enables investigators to reconstruct transaction flows potentially linked to illicit migrant transportation fees.
- [Inflated Transaction Pricing](https://framework.amltrix.com/techniques/T0008.002) — - Provide details of actual payment amounts, timestamps, and involved parties.
- Highlight overpayments beyond contractual terms or frequent high-value transfers.

These records help detect recurring inflated payments with no corresponding refunds, a hallmark of inflated transaction pricing schemes.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Captures timestamps, amounts, parties, and currency details for transactions flowing through free trade zone accounts.
- Highlights large, round-sum, or structured transactions inconsistent with the stated business activities.
- Reveals spikes or patterns of layering within FTZ-linked accounts compared to normal volume.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Provides comprehensive records of financial transactions (e.g., deposits, withdrawals, wires). Investigators can cross-check acquisition-related flows, detect uncommonly large or frequent capital injections, and verify whether reported business income aligns with actual incoming funds when identifying potentially illicit business acquisitions.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Provide comprehensive records of financial transactions, including timestamps, amounts, parties, and referencing accounts.
- In the context of remote mining, these logs help detect large or repetitive payments to hosting providers and unusual returns from unknown wallets, indicating potential laundering of newly mined assets.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Captures comprehensive financial transaction details, including timestamps, amounts, currencies, counterparties, and identifiers, across various channels.
- Facilitates the detection of frequent or unexplained invoice adjustments, circular fund flows, and other anomalous inter-company transfers indicative of manipulated transfer prices.
- [Independent Payment Agents](https://framework.amltrix.com/techniques/T0113.001) — - Provides comprehensive records of financial transactions, including timestamps, amounts, currencies, involved parties, and transaction identifiers.
- Supports detection of sub-agent activity hidden under the aggregator’s name and reveals anomalies in transaction volumes or patterns that can indicate unreported or high-risk payment channels.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Transaction logs capture deposit amounts, timestamps, origin accounts, and related metadata. This data helps identify large or frequent contributions that exceed the contributor’s known income and detect patterns of rapid layering or multiple rollovers across pension accounts, supporting investigations into potential illicit fund flows.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Captures transactional data, including timestamps, amounts, currencies, parties, and account details.
- Enables tracing of suspicious transaction chains across jurisdictions, revealing layering attempts by local agents or fixers.
- Supports correlation of transaction spikes with known or suspected cross-border agent activities.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Capture timestamps, amounts, counterparties, and transaction references. Analysis can reveal patterns of large capital inflows or outflows with no legitimate economic purpose, consistent with manipulated fund activities.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Provide detailed records of deposits, withdrawals, wire transfers, card payments, and other monetary flows.
- Enable investigators to spot anomalous or large inflows labeled as sponsorship, ticket revenue, or licensing fees beyond typical entertainment business norms.
- Support detection of layering through round-number or repeated transactions consistent with laundering via entertainment fronts.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Documents the timing, amounts, and recipients of outgoing payments, enabling investigators to detect suspicious patterns of payables to newly formed or unverified creditors. Reveals potential layering of multiple outflows orchestrated to fictitious or shell entities under the guise of legitimate expenditures.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Offers comprehensive records of fund movements, capturing timestamps, amounts, currencies, and account details. By correlating these logs with trading data, investigators can track subsequent fund transfers after mirror trades, identifying potential layering and quick cross-border shifts of illicit proceeds.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Records transaction details, including timestamps, amounts, accounts, and related metadata.
- Enables the identification of rapid or large transfers of refunded tax proceeds to offshore or high-risk destinations.
- Supports the detection of layering or swift fund diversion indicative of fraudulent rebate activities.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Detailed bookkeeping of all deposits, withdrawals, wire transfers, and investment movements, including timestamps, amounts, and counterparties.
- Enables detection of layering schemes, unusual fund flows, and cyclical transactions that deviate from legitimate investment patterns.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Captures comprehensive transaction details, including timestamps, amounts, counterparties, and transaction channels, for all financial movements.
- Supports AML detection by identifying large or structured payments used to fund or liquidate gold purchases, highlighting patterns consistent with layering or integration strategies.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Provides detailed records of transaction amounts, timestamps, parties, and related metadata.
- Enables detection of unusually large or frequent tuition/donation payments from individuals not affiliated with the institution and helps identify layering or structuring patterns within the school's accounts.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Provide comprehensive records of deposits, withdrawals, wire transfers, and other account movements.
- Enable identification of recurring structuring or layering patterns typical of trafficking networks.
- Help detect funnel account usage and apparent co-mingling of illicit funds from forced labor or sexual exploitation.
- [Insurance Beneficiary Substitution](https://framework.amltrix.com/techniques/T0089) — - Provides detailed records of premium payments, policy surrenders, and beneficiary or policyholder changes, including timestamps, amounts, and transaction identifiers.

- Enables detection of rapidly shifting or high-value payments characteristic of layering strategies in insurance beneficiary substitution, helping investigators trace potentially illicit account movements and analyze the funding sources behind large premium injections or surrenders.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Captures the flow of funds associated with trade finance facilities (e.g., letter of credit proceeds) to verify whether they ultimately reach legitimate suppliers or shipping lines. Investigators can track suspicious onward transfers or layering patterns across multiple accounts and jurisdictions.
- [Cash Deposits](https://framework.amltrix.com/techniques/T0004) — - Provides detailed records of deposit timestamps, amounts, and transaction references for each account.
- Enables detection of recurring deposit patterns, sub-threshold structuring, and unusually high deposit frequencies inconsistent with stated customer profiles.
- Supports cross-checking deposit sources to identify potential third-party or multi-location deposit behaviors.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Capture all premium payments to the captive insurer and subsequent claim or refund disbursements to help identify circular flows of funds tied to potential laundering.
- Reveal unusual payment patterns, such as inflated premiums or rapid and frequent claim paybacks, that exceed legitimate coverage or risk profiles.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Provides comprehensive records of financial transactions across accounts and channels, including timestamps, amounts, currencies, counterparties, and unique transaction identifiers.
- This data is critical for detecting cyclical transaction patterns where funds are returned to their original source, lacking legitimate economic purpose.
- [Crowdfunding Campaign Manipulation](https://framework.amltrix.com/techniques/T0044) — - Captures comprehensive records of monetary flows (e.g., deposits, fund transfers, withdrawals) across accounts.
- Identifies clustering of small donations or structured transactions suggestive of layering.
- Enables tracking of disbursements to multiple unrelated accounts without clear charitable expenditures.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Presents comprehensive timelines of financial transactions, including timestamps, transaction identifiers, and related accounts.
- Identifies rapid or overlapping issuance of letters of credit, indicating circular movement of funds.
- Pinpoints patterns where sequential letters of credit are used without corresponding underlying trade.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Capture all financial transactions tied to mining hardware purchases, energy bills, or cloud-based mining fees.
- Help identify repetitive or large-sum payments that could signal layering or illicit funds being funneled into mining operations.
- Enable cross-referencing of outgoing transactions for remote mining services, revealing potential money laundering flows.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Captures detailed transaction records (timestamps, amounts, parties, references), revealing:

- Large or frequent 'court-ordered' deposits that do not align with typical legal timelines.
- Settlement funds suddenly appearing in accounts with no credible court documentation.

How it supports AML detection:

- Identifies unusual or high-value movements labeled as legal settlements, enabling investigators to link potentially fraudulent court awards to suspected money laundering activities.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Includes comprehensive records for inbound or outbound capital injection transactions, capturing timestamps, amounts, counterparties, channels, and references. This helps identify unusual investment inflows exceeding a business's typical financial scale and track repeated or structured transfers from multiple sources, revealing potential layering or commingling of illicit funds.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Captures deposit entries and subsequent refunds for canceled or uncompleted bids, providing a record of potential layering or integration activities.
- Tracks payment flows across multiple accounts or third-party checks, helping identify suspicious layering or funneling patterns.
- Enables detection of repeated deposit-refund cycles that may signify disguised movement of illicit funds through auction platforms.
- [All-Cash Real Estate Transactions](https://framework.amltrix.com/techniques/T0010.005) — Captures comprehensive payment information, including amounts, timestamps, deposit methods, and withdrawal channels. This data enables the detection of multiple cashier's checks or structured payments from different institutions used to fund real estate purchases and bypass reporting thresholds.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — - Provides comprehensive records of inbound deposits, including timestamps, amounts, sender information, and references.
- Enables detection of mismatches between expected and actual senders or amounts, revealing illicit deposits substituting legitimate remittances.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Contains transaction details (timestamps, amounts, account numbers, counterparties) for each financial movement.
- Enables detection of large or frequent outgoing payments labeled as consultancy or management fees.
- Assists in tracing flows of funds to shell or obscurely owned companies, revealing suspicious layering or integration of illicit proceeds.
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Contains records of deposits, withdrawals, transfers, and other account activities, including timestamps, amounts, parties, and transaction identifiers. This data:

- Facilitates comparison between actual cash inflows and the income declared in financial statements or tax filings.
- Flags recurring high-value deposits or transactions inconsistent with an individual's stated occupation or salary range.
- Highlights suspicious patterns of deposits labeled as 'business income' from entities lacking formal registration.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Provides detailed records of financial transactions, including timestamps, amounts, recipients, and references describing permit or licensing fees.
- Facilitates detection of anomalous high-value payments to newly formed or unverified entities, indicating possible reliance on forged sector-specific documentation to justify those transactions.
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Comprehensive records of financial transactions, including note denominations, timestamps, and associated account details. Correlating the repeated use of large-value notes with cross-border activity helps detect the concealed transport of illicit funds.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Captures detailed records of financial transactions and money movements across various channels, including timestamps, amounts, currencies, parties, and transaction identifiers.
- Supports the detection of unusual patterns involving prepaid cards, app-based remittances, or cryptocurrency transfers, flagging rapid or high-volume movements indicative of layering or structuring.
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — - Records all financial transactions routed through professional intermediaries (e.g., attorney trust accounts), including timestamps, amounts, and parties involved.
- Enables detection of structured transactions below reporting thresholds and rapid in/out flows that exploit professional secrecy.
- Helps trace the movement of illicit funds disguised under attorney-client or professional privilege claims.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Provides comprehensive, timestamped records of deposits, withdrawals, transfers, and payments, including amounts, counterparty details, and transaction IDs.
- Enables detection and aggregation of repeated small transactions under reporting thresholds, which collectively may indicate micro-structuring tactics.
- [Unlicensed Real Estate Brokerage](https://framework.amltrix.com/techniques/T0133) — Provides comprehensive records of financial transactions, including amounts, timestamps, origin and beneficiary accounts, and payment instruments. This enables investigators to identify large or irregular payments processed through unlicensed brokers, detect transactions from unrelated overseas accounts, and trace flows of funds that bypass standard AML checks.
- [Match-Fixing](https://framework.amltrix.com/techniques/T0107.005) — - Captures comprehensive transaction details, including timestamps, amounts, sources, recipients, and account information.
- Reveals large, unexplained payments to players or officials from high-risk or flagged sources.
- Supports tracing funds used for bribery or coercion in match-fixing schemes and identifying abnormal payment flows.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Comprehensive records of subsidy deposits include details such as amounts, timestamps, originating accounts, and subsequent fund movements. This data helps identify unusually large or frequent subsidy credits and trace rapid transfers into unrelated accounts, indicating potential layering or commingling of fraudulent proceeds.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Provide comprehensive records of all transaction details, including timestamps, amounts, sources, and destinations.
- Facilitate the identification of large, unexplained deposits or sudden capital inflows that enable manipulative stock trading.
- Compare inbound funds with subsequent equity purchases to confirm the integration of illicit capital into market transactions.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Provide detailed records of inbound and outbound wire transfers, deposit amounts, references, timestamps, and counterparties.
- Enable detection of suspicious patterns, such as large deposits labeled as telemarketing income with no legitimate business rationale.
- Help identify multiple small or medium-value inbound transfers from unrelated parties without supporting contracts or legitimate business relationships.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Provides timestamps, amounts, and transaction identifiers for financial inflows and outflows, including deposits into and withdrawals from escrow accounts.
- Assists in detecting irregular or rapidly repeated transactions linked to real estate purchases and flips.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Provides comprehensive records of financial transactions, including timestamps, senders, recipients, amounts, and references.
- Enables detection of repeated 'advance fee' references, multiple small inbound transfers from unrelated parties, and rapid onward structuring of received funds—hallmarks of advance fee fraud.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Provides comprehensive records of deposits, withdrawals, wire transfers, and cash transactions tied to agribusiness accounts.
- Allows detection of unusual or large inflows (e.g., government subsidies) and outflows that are inconsistent with typical agricultural revenue patterns.
- Helps identify high-volume cash deposits that do not align with local farming practices or seasonal norms, indicating potential illicit fund placements.
- [Remittance Splitting](https://framework.amltrix.com/techniques/T0016.003) — - Provides detailed records of remittance transactions, including sender/recipient details, timestamps, amounts, and transaction identifiers.
- Enables detection of repeated small-value transfers from multiple senders, highlighting structuring below reporting thresholds.
- Allows investigators to identify rapid withdrawals or cash pickups, supporting analysis of suspicious layering activities.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Provide comprehensive records of financial transactions and account details, including timestamps, amounts, currencies, and parties.
- Enable detection of repeated round amounts, structured payments, or clusters of high-value deals in short timeframes, revealing potential layering or other suspicious patterns tied to inflated image rights payments.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Provides comprehensive records of all financial transactions, including timestamps, parties, account details, transaction amounts, and identifiers.

This data helps detect Hot Transfers by identifying offsetting or reciprocal transactions with near-zero net movement, indicating potential informal value transfer arrangements.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — Transaction logs capture the flow of funds into and out of the fictitious consulting firm, including timestamps, amounts, sender/receiver details, and associated reference data. This enables the detection of rapid inflows followed by quick outflows, layering maneuvers, and inflated consulting fees that exceed typical market norms.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Records comprehensive transaction data, including timestamps, amounts, account details, and counterparties.
- Enables tracking of circular or repetitive fund movements among shell companies.
- Assists investigators in identifying large-scale money flows consistent with carousel fraud patterns.
- [Casino Mule Networks](https://framework.amltrix.com/techniques/T0011.003) — - Consolidates records of all financial transactions, capturing deposits of casino-issued checks into external bank accounts.
- Allows investigators to trace subsequent fund movements and potential structuring across multiple accounts, revealing additional layering after casino chip redemptions.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Detailed records of all incoming and outgoing financial transactions, including timestamps, amounts, and counterparty information.
- AML Relevance: Identifies suspicious government benefit deposits, tracks concurrent wage and benefit payments, and flags rapidly withdrawn or transferred funds indicative of fraudulent claims.
- [Bank Infrastructure Manipulation](https://framework.amltrix.com/techniques/T0132) — - Document all financial movements and provide details on amounts, timestamps, and originating and destination accounts.
- Enable comparison of actual transaction activity against configured control thresholds to spot transactions that bypass normal alerts.
- Help uncover anomalies related to insider suppression of alerts or unauthorized system parameter changes.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Capture comprehensive details on fund movements through accounts controlled or managed by professional intermediaries, including timestamps, amounts, counterparties, and transaction references. This helps investigators detect unusual patterns, layering, and frequent fund transfers lacking clear commercial rationale.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Provides comprehensive records of incoming and outgoing transactions across financial accounts, including timestamps, amounts, counterparties, and account identifiers. By isolating large or repeated OTC-related inflows and outflows, investigators can spot patterns indicative of cash-to-crypto conversions that avoid regulated exchanges.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Provide comprehensive records of all financial transactions (e.g., wire transfers, deposits, withdrawals). Investigators can trace ransom payments routed from insurers, shipping firms, or families to potential pirate networks, identifying suspicious transaction patterns or unexpectedly large cross-border flows that may indicate the laundering of ransom proceeds.
- [Informal Micro-Finance Schemes](https://framework.amltrix.com/techniques/T0096) — Captures financial transaction details, including dates, amounts, counterparties, and account identifiers. This enables the detection of suspicious deposit-withdrawal patterns, rapid fund turnover, and concurrent contributions to multiple informal savings groups that exceed a participant’s verifiable financial profile.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Provide official transaction details, including timestamps, transaction identifiers, and amounts.  
- Cross-check these transaction records with the reference numbers and amounts on allegedly forged financial instruments to reveal mismatches indicative of document tampering.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Provides a chronological record of all incoming and outgoing payments for loan disbursements and repayments.
- Identifies suspicious patterns such as immediate defaults, closed-loop fund flows returning to the same beneficial owner, or third-party payors lacking clear ties to the borrower.
- Supports retrospective tracing of funds to confirm whether loan proceeds are actually applied as stated or diverted to illicit recipients.
- [Money Mule Exploitation](https://framework.amltrix.com/techniques/T0011) — - Capture timestamps, amounts, sending and receiving account identifiers, currencies, and transaction types to enable the detection of suspicious or repetitive deposits, structured amounts below reporting thresholds, and rapid in-and-out fund transfers.
- Allow comparison of actual transaction behaviors against expected customer profiles, highlighting anomalies such as quick outbound transfers from newly opened accounts.
- Facilitate tracing of layering or circular flows through multiple linked accounts, a hallmark of money mule exploitation.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Captures financial transaction details, timestamps, involved accounts, and related metadata. When multiple departments or service providers handle segments of a transaction chain in isolation, these logs highlight segmented flows with limited cross-referencing, supporting the detection of compartmentalized processes.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Provides comprehensive records of all financial transactions (e.g., timestamps, amounts, parties) to detect patterns indicative of counterfeit pharmaceutical sales, such as large bursts of structured payments, multiple low-value transfers, or frequent refunds and chargebacks.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Captures comprehensive records of financial transactions, including timestamps, amounts, parties, and currencies.
- Allows investigators to identify missing entries, inconsistent transaction details, or anomalous changes that may indicate tampering.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Provides itemized records of all financial transactions, including timestamps, amounts, counterparties, and references (e.g., 'storage fees'). This enables investigators to detect repeated high-value payments to freeport or private storage operators that lack apparent commercial justification, indicating potential layering or placement of illicit funds.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Provides detailed records of inbound and outbound financial transactions, including timestamps, amounts, counterparties, and account details. This data supports the detection of investment fraud by identifying suspicious consolidation of victim funds, rapid transfers to unrelated accounts, and potentially fraudulent transaction patterns.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Detailed records of financial transactions capture unemployment benefit deposits, enabling the detection of unusual patterns such as multiple benefit payments from different jurisdictions to the same account, concurrent wage and benefit deposits, or sudden spikes in government credits. This data is critical for identifying potentially fraudulent claims.
- [Rental Income Schemes](https://framework.amltrix.com/techniques/T0010.004) — - Captures deposit amounts, timestamps, frequencies, and counterparties for rental payment transactions.
- Enables detection of suspicious patterns, such as multiple large cash deposits exceeding market rates or clustered within a short period.
- Facilitates identification of layering or commingling of illicit funds following the initial deposit.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Contains records of all financial movements, including timestamps, amounts, currencies, account details, and initiator information. This data supports AML detection by uncovering:

- Large, round-amount transactions authorized by newly installed management without legitimate economic purposes.
- Sudden spikes in transaction volumes or new account openings following ownership changes.
- Unusual patterns of internal transfers or asset movements within the institution.

Such anomalies can highlight infiltration, where criminals exploit their control to conduct high-risk or suspicious activities.
- [Cheque Fraud](https://framework.amltrix.com/techniques/T0144.010) — - Capture check deposit details, including timestamps, amounts, payors, and deposit channels, as well as subsequent withdrawals or transfers.
- Facilitate the identification of returned checks that have already been withdrawn, revealing potential fraudulent float exploitation.
- Provide concrete evidence of suspicious deposit and withdrawal patterns linked to possible check fraud schemes.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Provides a comprehensive record of deposits, withdrawals, and cross-border transfers, enabling the detection of unusual cash movements, high-frequency or structured transactions, and potentially unlicensed intermediary activity consistent with hawala operations.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Provides comprehensive records of inbound and outbound transactions, including timestamps, amounts, currencies, and counterparties.
- Reveals potential romance mule activity by showing frequent incoming funds from multiple unrelated sources and rapid onward transfers with limited justification.
- Highlights abrupt changes in transaction patterns, such as sudden increases in cross-border payments after establishing a romantic connection.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Provides comprehensive records of all financial transactions, including amounts, timestamps, counterparties, and related metadata for each account.  
- Enables detection of sudden large inflows or outflows, rapid turnover of funds, or the reactivation of dormant accounts, all of which are red flags for shelf companies used to facilitate rapid layering or conceal illicit proceeds.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Captures subsequent financial transactions after gambling proceeds are redeemed, including deposit timestamps, amounts, payment methods, and beneficiary account details. This helps identify patterns where illicit funds labeled as gambling winnings are consolidated or transferred to other financial accounts, facilitating the detection of layering techniques.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Comprehensive records of financial transactions, including timestamps, amounts, currencies, and counterparties, enable the detection of repeated or rapid currency swaps that indicate layering attempts. Investigators can trace the sequence and pattern of conversions used to obscure the illicit origin of funds.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Captures detailed records of all financial transactions, including timestamps, amounts, counterparties, and account references. This data:

- Reveals unusual or high-frequency transfers to offshore accounts.
- Highlights cyclical fund movements, suggesting layering across multiple jurisdictions.
- Allows comparison of the actual flow of funds against a customer’s historical profiles and stated business activities.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Tracks all financial movements, including deposits, withdrawals, wire transfers, and remittances.
- Enables pattern analysis to uncover unusually high volumes or repetitive transfers linked to unlicensed MSBs.
- Helps detect cash-heavy or off-the-books transactions that bypass regulated channels.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Contains detailed records of all transactions, including timestamps, amounts, and counterparties.
- Helps track potential unreported inflows of funds, cross-border transfers to concealed accounts, and suspicious layering indicative of tax evasion.
- [Ransomware Payments](https://framework.amltrix.com/techniques/T0049.001) — - Provides comprehensive records of both fiat and digital asset transactions, including timestamps, amounts, counterparties, and currency types.
- Enables detection of abrupt shifts from traditional fiat usage to intensive cryptocurrency activity following ransom demands.
- Helps investigators identify unusual spikes in transaction volumes or sudden changes in payment channels consistent with ransomware extortion.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Captures comprehensive records of inbound wire transfers, including amounts, timestamps, currencies, and counterparties.
- Enables detection of unusually large or frequent inbound flows labeled as foreign capital injections that exceed an entity’s typical financial capacity or normal business activity.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Provides comprehensive records of all financial transactions, including timestamps, amounts, and counterparties.  
- Enables detection of unusual payment patterns or incremental transfers to chemical suppliers or brokers lacking a clear business purpose.  
- Helps identify repeated small transactions, layering attempts, and structuring tactics used to obscure the procurement of precursor chemicals.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Captures comprehensive deposit and withdrawal records, including timestamps, amounts, account ownership, and cross-channel activity.
- Enables detection of structured, repetitive, or round-amount cash deposits into crypto ATMs, revealing potential mule-based layering schemes.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — - Maintains a detailed record of all financial transactions, including timestamps, amounts, account identifiers, and transaction sources.

- Allows for the correlation of unusual or high-value fund movements with potentially fraudulent voice requests, aiding in the detection of out-of-pattern transactions that may result from deepfake instructions.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Comprehensive records of check deposits and other financial transactions include payee names, account holder identities, timestamps, and amounts. By comparing the declared payee name to the verified account holder identity, institutions can identify suspicious discrepancies or forgery attempts that indicate name alteration.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Provides post-opening transaction details (timestamps, amounts, counterparties, velocities).
- Assists in identifying abnormal usage patterns or rapid fund movements common in accounts opened with fake or stolen identities.
- [Cooperative or Mutual Institution Deposits](https://framework.amltrix.com/techniques/T0120) — - Captures deposit timestamps, amounts, counterparties, and transaction references.
- Allows detection of large or frequent member deposits that deviate from typical patterns.
- Enables tracing of possible layering activities or funds cycling through multiple cooperative accounts.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Captures detailed financial transaction data (e.g., timestamps, amounts, currencies, parties) across various channels.
- Enables identification of unusual or structured payment patterns indicative of layering or commingling proceeds generated from illicit wildlife trafficking.
- Supports tracing the flow of funds across accounts and institutions for investigative follow-up.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — Tracks financial activity post-onboarding, including transactional timestamps, amounts, and counterparties. Compares declared account profiles with actual high-value or anomalous transactions soon after remote identity setup, flagging potential laundering through newly established accounts.
- [Test Payment Probing](https://framework.amltrix.com/techniques/T0035) — - Provides detailed records of all financial transactions, including timestamps, amounts, parties, and transaction identifiers.
- Enables detection of patterns where repeated small payments are followed by much larger transfers, indicating threshold probing attempts.
- Supports identification of rapid or consecutive small transactions across multiple accounts or channels, aiding in investigating potential AML evasion strategies.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Provides comprehensive records of invoice payments, refunds, and other fund movements with timestamps and counterparties.
- Uncovers partial refunds or suspicious redirections of funds soon after invoice settlement, aligning with bribery or fraudulent kickback schemes typical of fake vendors.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — - Comprehensive records of financial transactions, including timestamps, amounts, and counterparties.
- Helps detect structured payments or suspicious commissions related to rigged contracts, such as round-number transactions or repeated smaller sums below reporting thresholds.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Records all financial transactions, capturing timestamps, amounts, parties, and account details.
- Enables detection of improperly diverted public funds through unusual transfers to personal or third-party accounts, as well as large cross-border wires to secrecy jurisdictions.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Records cross-border and domestic fund flows, including timestamps, amounts, and involved accounts.
- Identifies rapid layering transactions and complex routing through multiple corporate entities.
- Correlates transaction patterns with corporate structures to spot suspicious multi-jurisdictional behavior.
- [Public WiFi Networks](https://framework.amltrix.com/techniques/T0015.003) — - Records timestamps, amounts, currencies, and IP addresses for all transactions, demonstrating when and where financial activities occur.
- Enables detection of unusual or rapid high-value transfers originating from public WiFi hotspots, highlighting deviations from typical account behaviors.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Capture deposit amounts, references to gaming proceeds, and payer details.
- Identify payout amounts, recipients, and timestamps from gambling operator accounts.
- Reveal inbound and outbound cross-border fund flows referencing e-wallets or prepaid cards.

These logs help detect unusual transaction patterns, such as large or frequent deposits labeled as gaming proceeds with minimal actual betting activity, and trace suspicious payouts, supporting AML investigations into potential layering of illicit funds.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Records all financial transactions, including amounts, timestamps, currencies, and counterparties, covering deposits, wire transfers, and other movements.
- Enables tracing of suspicious fund flows associated with manipulated oil invoices or shipments.
- Supports identification of layering patterns where proceeds from falsified transactions move quickly through various accounts.
- [Temporary Shell Companies](https://framework.amltrix.com/techniques/T0001.002) — - Captures inbound and outbound financial transactions, including timestamps, amounts, and counterparties.
- Enables detection of sudden spikes in transaction volume or rapid fund movements before company dissolution.

This directly supports identifying short-lived shell entities used for quick laundering campaigns.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Comprehensive records of all financial transactions involving customers' accounts, detailing timestamps, amounts, recipients, and references. This data helps identify sudden spikes or unusual patterns in artifact-related transactions, such as private auction purchases at inflated prices.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Provides comprehensive records of inbound and outbound financial transactions, covering timestamps, amounts, currencies, and counterparties. This data helps detect frequent deposits from unconnected parties followed by quick withdrawals or transfers, as well as transaction volumes exceeding the customer's stated profile or occupation.
- [Cryptocurrency Mixing](https://framework.amltrix.com/techniques/T0003) — Capture comprehensive financial movements, including deposit and withdrawal records, timestamps, amounts, and counterparties, across banking and cryptocurrency channels. For cryptocurrency mixing, these logs reveal repeated or structured flows to and from high-risk wallets, sudden spikes in outbound transfers, and deviations from a customer’s typical transaction profile indicative of layering or concealment.
- [Virtual Private Network](https://framework.amltrix.com/techniques/T0015.001) — - Records the details of financial transactions, including timestamps, amounts, sending and receiving account data, and source IP information.
- Helps investigators identify high-value or structured transactions initiated from VPN endpoints.
- Supports unraveling layered funds by correlating masked IP addresses with suspicious transaction patterns.
- [Structuring](https://framework.amltrix.com/techniques/T0016) — - Provides timestamps, transaction amounts, account identifiers, and deposit/withdrawal records for all financial movements.
- Enables detection of multiple sub-threshold transactions conducted in quick succession or across various channels.
- Facilitates aggregation analysis to identify total funds moved by a single user, flagging suspicious structuring patterns designed to circumvent reporting thresholds.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Includes detailed records of all in-game and external transactions, such as timestamps, amounts, currency types, and counterparties. This enables the detection of unusual flows between different gaming platforms or third-party sites, helping to identify patterns of layering or value transfers that lack legitimate gaming rationale.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — - Consolidates information on all financial transactions, including the timing and amounts of safe deposit box rental fee payments.
- Allows correlation of cash deposits or withdrawals with safe deposit box usage intervals.
- Helps identify structured cash payments or other anomalies tied to the deposit box rental.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — - Provides time-stamped records of all financial transactions, including bidding increments, payment flows, and settlement amounts.  
- In the context of art auctions, these logs help identify anomalous bidding patterns (e.g., round-number or repetitive increments) and track unusual payment routes or multiple intermediaries indicative of potential manipulation.
- [Domestic Bulk Cash Delivery](https://framework.amltrix.com/techniques/T0119) — Capture comprehensive details of deposits, including timestamps, amounts, denominations, parties, and channels. This enables the analysis of repeated sub-threshold transactions and unusual cash volumes. These records allow investigators to identify potential structuring that aligns with domestic bulk cash deliveries.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Provides comprehensive records of all financial transactions, including timestamps, amounts, account details, and counterparties.
- Shows the sequence of currency movements, enabling detection of potential layering, frequent cross-currency conversions, and unknown beneficiaries.
- Helps isolate unusual or rapid activity inconsistent with the customer’s typical business cycle or operational profile.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Provides comprehensive records of financial transactions, including timestamps, amounts, counterparties, and relevant identifiers.
- Enables detection of suspicious transactions that match or slightly exceed CBI/RBI thresholds, monitoring of partial refunds after thresholds are met, and identification of patterns indicative of layering or concealment of funds.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Provides comprehensive records of monetary transactions, including timestamps, amounts, currencies, counterparties, and transaction types. This data helps detect unusual payment methods, structuring below reporting thresholds, and large or irregular flows tied to fraudulent online storefronts, enabling analysts to uncover potential layering of illicit proceeds.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Provides comprehensive records of deposits, withdrawals, transfers, timestamps, amounts, and counterparties. 

- Enables investigators to correlate payment patterns with known extortion schedules.
- Detects structuring below reporting thresholds, frequent cash deposits in high-crime areas, and immediate transfers laundered into legitimate accounts.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Captures timestamps, amounts, currencies, parties, and transaction identifiers across multiple channels.
- Facilitates detection of micro-transactions, rapid fund flows, and layering across accounts or institutions.
- Enables investigators to reconstruct complex transaction patterns and trace funds through multiple layers involved in transaction chaining.
- [Negotiable Instrument Purchases](https://framework.amltrix.com/techniques/T0110) — - Provides comprehensive transaction details, including timestamps, amounts, payees, and instrument types, for each negotiable instrument purchase.
- Enables the detection of structuring patterns, such as repetitive sub-threshold purchases or deposits, and rapid redemption across different institutions.
- [Virtual IBANs](https://framework.amltrix.com/techniques/T0027) — - Provides complete records of deposits, withdrawals, and transfers, capturing timestamps, amounts, and IBAN references.
- Directly supports the detection of repeated usage of multiple virtual IBAN references, unusually short holding periods, and rapid fund layering outflows, enabling targeted AML investigations.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Captures all inflows and outflows of funds, including timestamps, amounts, counterparties, and transaction channels, enabling the detection of:

- Large or frequent purchases of precious metals or gemstones that deviate from a customer’s profile.
- Rapid resale or short holding periods indicative of quick layering or integration.
- Suspicious transaction flows potentially aimed at concealing illicit proceeds.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Provides detailed records of financial transactions, including timestamps, amounts, parties, currencies, and transaction identifiers.
- Enables detection of large or round-figure transactions, layering across multiple MSB-owned accounts, and unusual volumes compared to the MSB’s declared operations.
- Supports AML teams in identifying and investigating transaction patterns that may indicate complicit or controlled MSBs masking illicit flows.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Captures detailed records of deposits, withdrawals, transfers, and investment trades, including timestamps, amounts, counterparties, and associated account details. This information helps detect suspicious patterns such as large or structured deposits, unusual redemption activity, and rapid cross-border fund movements indicative of layering schemes in investment portfolios.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Captures all financial activity within accounts, including timestamps, amounts, counterparties, and transaction channels.
- In the context of CBI/RBI, these logs reveal sudden inflows or rapid movement of funds coinciding with golden passport applications, unusually high commissions to agents, or direct payments to officials.
- Enables AML analysts to detect and investigate suspicious payment flows, asset liquidations, and potential bribery or corruption tied to citizenship or residency programs.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Captures all financial movements associated with Bill of Exchange transactions, including timestamps, amounts, and sender and receiver details. This information can reveal the repayment of illicit funds, layering attempts, and unusual repayment patterns or unrelated funding sources.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Captures transaction timestamps, amounts, currencies, and involved parties. By reviewing these logs, investigators can identify multiple payments or disbursements for the same goods or services, revealing repeated billing patterns suggestive of multiple invoicing.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Provides detailed records of reimbursement transactions, including amounts, timestamps, and counterparties. This data allows for the detection of suspiciously high claims, duplicate submissions, or repeated partial claims strategically kept below internal review thresholds, all indicative of potential expense report fraud.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Capture detailed records of all financial transactions, including timestamps, amounts, and payment methods. For lottery money laundering, these logs:

- Reveal bulk cash purchases of tickets or frequent purchases in short timeframes.
- Highlight repetitive prize redemptions near reporting thresholds.
- Correlate sudden spikes in lottery activity with large cash deposits or other suspicious funding sources.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Provides detailed records of premium payments, including amounts, timestamps, payer identities, and associated refunds, enabling the detection of suspicious or structured third-party payments.
- Identifies short-lived policies that generate unusually large payout requests, supporting the investigation of potentially illicit early surrenders.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Captures bond purchase and redemption details, such as timestamps, amounts, and payment methods, across customer accounts. This data helps identify unusual patterns, such as frequent high-value bond purchases and rapid redemptions, as well as discrepancies in how funds are introduced or withdrawn. This supports the detection of layering within bond investment schemes.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Captures details of each financial transaction, including timestamps, amounts, counterparties, and channels.
- Enables identification of sub-threshold structuring, multiple small deposits, or offset-based transfers—hallmarks of informal value transfer systems.
- Supports detection of rapid movement or layering across accounts consistent with IVTS patterns.
- [Lottery Scams](https://framework.amltrix.com/techniques/T0144.015) — Captures timestamps, amounts, references, and counterparties for all financial movements, including deposits labeled as 'lottery fees' or 'prize taxes' and disbursements marked as 'winnings.' Investigators can track patterns of small incoming payments from unrelated parties and subsequent layering or structuring consistent with lottery scam operations.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Records full details of financial transactions, capturing timestamps, amounts, parties, and references.
- Supports cross-referencing of actual payments with consulting invoices to pinpoint inflated or fabricated transactions indicative of laundering.

---

## [Loan Agreements and Credit Facilities](https://framework.amltrix.com/data-sources/DS0032)

**Description:**
Formal contracts related to lending and credit products—such as personal loans, mortgages, credit cards, and lines of credit—detailing loan amounts, interest rates, repayment schedules, and collateral. These records enable financial institutions to assess borrowers, track repayment patterns, and identify irregular credit usage.

### Related Techniques
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Provides details on trade finance and credit instruments, including letters of credit issued for diamond shipments.
- Helps uncover repeated financing requests tied to the same parcels at inflated valuations without sufficient justification.
- [Pre-Shipment Finance Manipulation](https://framework.amltrix.com/techniques/T0072) — Includes detailed records of pre-shipment financing terms, such as loan amounts, repayment schedules, disbursement conditions, and collateral requirements. By comparing these agreements with purported export transactions, investigators can identify irregularities or inconsistencies that may indicate misuse of pre-shipment finance.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Includes formal contracts and supporting details for loans, credit cards, and other financing.
- Helps confirm whether submitted documents (e.g., invoices, applications) align with legitimate funding needs or signal fraudulent borrowing.
- Allows investigators to cross-reference financed amounts with identified bogus claims, revealing potential false documentation or repetitive fraud patterns.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Contains detailed loan contracts, repayment schedules, and credit facility terms for real estate acquisitions and refinances.
- Helps uncover rapid or repeated refinancing of properties soon after purchase, a tactic commonly used to layer or extract illicit proceeds in high-cash-flow real estate schemes.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Contains records of loans, lines of credit, and the collateral used to finance trade transactions.
- Identifies multiple invoicing schemes where the same invoice or shipping documentation is submitted for repeated financing requests.
- [Third-Party Payments](https://framework.amltrix.com/techniques/T0073) — These records provide details on the authorized borrower, repayment terms, and declared funding sources for loans and credit lines. By comparing actual repayments against documented agreements, financial institutions can detect suspicious third-party payments or structured deposits by individuals not listed in the contract, thereby uncovering potential layering or disguised ownership of funds.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Provides formal contracts outlining syndicated loan terms and structures, including participating lenders, interest rates, repayment schedules, and collateral.
- Facilitates identification of unusual or inflated loan amounts, repetitive amendments, or overlapping participants, revealing potential collusion or concealed beneficial ownership in trade finance arrangements.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Details formal credit arrangements between casinos, junket operators, and VIP customers, including loan amounts, interest rates, and repayment terms.
- Identifies large or unjustified credit lines granted without legitimate wealth documentation, raising suspicion of money laundering.
- [Payroll Deduction Loan Repayment](https://framework.amltrix.com/techniques/T0029) — - Include formal loan contracts and repayment schedules, detailing amounts, interest rates, terms, and associated collateral.
- Facilitate cross-checking of actual repayment transactions against agreed-upon schedules to detect unusual repayment acceleration or multiple overlapping payroll-deduction notes.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Facilitates thorough verification of letters of credit, standby letters of credit, and other trade finance instruments used in purported transactions. By reviewing loan terms, borrowing parties, repayment schedules, and beneficiary details, investigators can detect inflated or fraudulent trade transactions.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Documents details of credit lines, loan amounts, and collateral. By reviewing these records, one can detect overlapping or simultaneous financing instruments (e.g., multiple letters of credit) tied to the same underlying goods, revealing repeated invoice submissions.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Contains principal amounts, repayment schedules, collateral details, borrower-lender identities, and other obligations.
- Helps detect anomalies like repeated restructuring, strategic defaults, or nonexistent collateral arrangements.
- Enables verification of the stated loan purpose against the actual use of funds, exposing fictitious or sham loan agreements.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Contains contractual records of letter of credit issuances, amendments, and repayment terms. Analyzing these documents helps identify frequent amendments, unusually large advance payments, or other credit irregularities symptomatic of red/green clause abuse.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Contains details of loans, collateral, repayment schedules, and borrower profiles.
- Detects suspicious collateral-based loans secured by precious metals or gemstones lacking proper ownership or origin documentation.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Comprehensively details the underlying collateral, supporting documentation, and obligations used to secure financing. This is useful in uncovering inflated or duplicated invoices used as collateral to disguise nonexistent transactions and launder funds under the pretense of legitimate credit arrangements.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Provides detailed information on trade finance instruments such as letters of credit and bills of exchange, including payment terms, collateral details, and parties involved. This data source is pivotal for identifying unusual amendments, inflated administrative costs, and repetitive re-invoicing structures that obscure the true value or legitimacy of shipped goods in trade-based schemes.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Includes records of credit terms, disbursement, and repayment schedules tied to Bill of Exchange discounting or financing. Cross-referencing these details can reveal repayment from illicit funds, early payoffs, or misalignment with legitimate trade flows.

---

## [Fraud Data](https://framework.amltrix.com/data-sources/DS0033)

**Description:**
Information on known or suspected fraudulent activities, including identity theft, payment card fraud, or scam patterns, compiled from reported incidents, industry warnings, or shared alerts.

### Related Techniques
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Collects reported incidents and patterns of identity fraud, including known methods of forging documents or impersonating legitimate customers.
- Allows cross-referencing of suspicious identity profiles against documented fraud cases.
- Enhances detection by highlighting recurring impersonation patterns reported within the institution or by industry alerts.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Compiles details of known or suspected fraudulent activities, including identity theft incidents and document-forgery methods. By matching incoming early superannuation withdrawal requests against these documented fraud patterns, investigators can quickly detect and block potentially forged or stolen identity claims.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Contains known fraud or financial crime records for individuals or entities.
- Helps identify high-risk parties engaged in questionable insurance or reinsurance schemes.
- [Cross-Chain Bridges](https://framework.amltrix.com/techniques/T0005.002) — - Consolidates information on addresses and entities flagged for suspicious or illicit on-chain activities.
- Assists in identifying linkages between cross-chain bridge transactions and known fraudulent addresses or watchlists.
- Facilitates rapid detection of bridging patterns involving addresses previously reported for scams, hacks, or other unauthorized activities.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Aggregates known or suspected fraudulent wallet addresses, flagged entities, and scam patterns.
- Correlates donor or organizational information with existing fraud databases to identify potential illicit involvement or repeated risk signals.
- Helps detect addresses using mixing or tumbling services previously associated with suspicious activity.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Aggregated information on known or suspected fraudulent activities includes identity theft reports, compromised personal data, and forged documentation patterns. By cross-referencing customer applications and account changes against these records, financial institutions can identify potential identity manipulation and investigate suspected synthetic or stolen identities more effectively.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Consolidates reports of known or suspected fraud incidents, alert lists, and scam patterns.
- Helps institutions detect repeat offenders, suspicious methodologies, or new fraud typologies.
- Enables more targeted investigations where similar or identical fraud indicators appear (e.g., false invoicing patterns).
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Contains records of known or suspected fraudulent activities, identity theft cases, and scam patterns from industry sources and shared alerts.
- Directly supports the detection of repeat fraudsters or stolen IDs used to apply for relief, enabling proactive identification of potential scams.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Provides aggregated records on known or suspected fraudulent checks, forged or altered instruments, and repeated deposit scams. By cross-referencing newly deposited checks with these fraud databases, institutions can identify potential matches or suspicious patterns associated with remote deposit capture more quickly.
- [Remote Verification Bypass](https://framework.amltrix.com/techniques/T0135) — - Aggregates known or suspected identity theft records, compromised documents, and other fraud patterns.
- Enables direct cross-checking of user-submitted IDs against known fraudulent profiles, revealing attempts to bypass remote verification with stolen or forged credentials.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — - Consolidates information on identity theft, payment card fraud, and scam patterns.
- Supports the detection of stolen or synthetic IDs used in fraudulent unemployment claims by cross-referencing known fraudulent identities.
- Shares industry alerts on emerging unemployment fraud schemes, facilitating early identification of suspicious claims or accounts.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Provides records of known or suspected fraud, including scam patterns and reported incidents. This helps flag potential romance or social media recruitment approaches associated with money mule activities and identify accounts linked to similar fraud typologies.
- [Cheque Fraud](https://framework.amltrix.com/techniques/T0144.010) — - Consolidates records on known or suspected fraudulent activities, including stolen checks, identity theft incidents, and frequently used scam techniques.
- Enables cross-referencing of ongoing check fraud patterns or flagged payors with existing fraud alerts, supporting earlier detection of high-risk deposits.
- [Online Gambling](https://framework.amltrix.com/techniques/T0017) — - Contains records of known or suspected fraudulent identities, including stolen or compromised payment credentials.
- Enables detection of accounts opened using fraudulent details or stolen data.
- Helps identify the use of compromised payment cards to fund online gambling accounts, linking suspicious identities to broader fraud patterns.
- [Counterfeit Currency](https://framework.amltrix.com/techniques/T0092) — - Consolidates internal and shared industry intelligence regarding fraudulent activities.
- Logs incidents of suspected or confirmed counterfeit currency, such as repeated serial numbers or device-flagged anomalies in deposited banknotes.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Contains records of compromised payment methods, stolen card details, and prior fraudulent activity.
- Supports identification of high-risk in-game currency acquisitions funded by illicit sources or unauthorized payment methods.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Tracks known or suspected fraudulent activities, including stolen credit cards, compromised accounts, and scam patterns. It helps detect repeated small-value card purchases or suspicious payment methods used to load gaming wallets, which are common tactics for laundering funds in virtual worlds.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Consolidates repositories of known or suspected fraudulent activities related to stolen digital items, compromised gaming accounts, or ongoing scam patterns.
- Enables financial institutions to flag transactions associated with recognized fraudulent game assets, preventing the rapid monetization of illicit tokens.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Contains blacklisted addresses, compromised wallets, or known fraudulent accounts associated with prior illicit activity.
- Supports rapid identification of suspected funds derived from or destined for illegal sources when instantly swapped or layered.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Aggregates known or suspected instances of fraudulent activity linked to individuals or entities.
- Identifies parties with a history of document forgery or trade-based fraud.
- Assists in detecting repeat offenders exploiting documentary collection mechanisms.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Contains information on institutions or entities previously flagged for fraudulent activities or compliance breaches.
- Assists in detecting lenders with a history of risky or noncompliant practices, possibly enabling syndicated trade loan manipulation.
- [Lottery Scams](https://framework.amltrix.com/techniques/T0144.015) — Provides information on known or suspected fraudulent activities and scam patterns, including reported lottery scam typologies, associated email addresses or phone numbers, and patterns of advance fee fraud. Investigators use these details to cross-reference repeat perpetrators, identify recurring victim complaints, and detect transactions matching known lottery scam behaviors.
- [Chip Dumping](https://framework.amltrix.com/techniques/T0107.003) — - Contains records of known fraudulent payment methods or compromised payment cards.  
- Enables detection of deposits originating from stolen cards or flagged payment sources used to fund chip dumping accounts.  
- Supports investigations by correlating fraudulent payment activity with rapid or unusual chip losses to conspirator accounts.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Contains information on known or suspected fraudulent activities, entities, and individuals.
- Flags tax agents or intermediaries with a history of involvement in fraudulent refund schemes.
- Helps uncover networks of repeat offenders and patterns consistent with tax rebate fraud.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Contains alerts, reports, and patterns associated with known scams, including telemarketing and phone-based fraud.
- Facilitates the identification of vulnerable individuals, such as older adults, who may have been coerced into sending funds under false pretenses.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — Fraud data consolidates reported and known fraudulent activities, including:

- Documented patterns of identity theft, payment card fraud, and chargeback-related scams.
- Correlation with known fraudulent profiles or blacklisted entities.

By comparing disputed transactions against known fraud trends, investigators can identify malicious patterns underlying fraudulent chargebacks more quickly.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Compiles reports of known or suspected fraudulent behavior, scam patterns, and associated entities. Financial institutions can cross-reference new investment clients or promoters with existing fraud alerts to identify potential links to previous scams or social engineering efforts.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Contains detailed reports of known or suspected fraud incidents, including romance scam tactics and blacklisted identities (e.g., phone numbers, email addresses, account credentials).
- Enables investigators to match ongoing suspicious activity against prior romance scam patterns, quickly identify repeat offenders, and spot recurring stories or ruses typical of romance mule recruitment.
- Facilitates faster detection of emerging scam trends and potential links to organized fraud networks, strengthening AML efforts against romance scam recruiters.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Consolidates records on reported and confirmed fraud incidents, including pig butchering scam typologies, associated phone numbers, email addresses, wallet addresses, or websites involved in scams.
- Facilitates early detection by matching new activity against known fraudulent patterns, enabling timely intervention, enhanced investigations, and potential account restrictions.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Contains records of known or suspected fraudulent activities, stolen personal data, or compromised identity details.
- Supports cross-referencing newly submitted identity information against blacklists or detected fraud cases to identify potential fake or stolen KYC documentation.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — - Consolidates histories of known or suspected fraud incidents, including impersonation scams, associated methods, and impacted accounts.

- Helps investigators identify repeat or correlated deepfake-based scams and cross-reference impersonation techniques across multiple customer accounts or institutions.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Compiles lists of flagged or blacklisted entities, accounts, and addresses linked to suspicious or illicit activities.
- Helps identify vendor bank details matching known fraud or sanction databases, suggesting potential fake vendor involvement.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Aggregates known scam patterns, reported incidents, and suspected fraudulent activity linked to false charitable appeals.
- Supports investigative efforts by matching current fundraising behaviors with established fraud typologies or alerts.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Includes whistleblower tips, reported allegations of misconduct, and known or suspected internal fraud incidents.  
- Helps uncover insider wrongdoing by consolidating internal reports and alerts on potential employee collusion or other misconduct.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Centralizes reported incidents of unauthorized transactions, phishing attempts, or disputed charges.
- Highlights patterns of disputed activity and connects known fraud events to compromised accounts, aiding in ongoing investigations.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — Contains information on known or suspected fraudulent activities (e.g., scam phone numbers, email addresses, and patterns) specifically associated with advance fee fraud schemes. Financial institutions can cross-reference suspicious incoming payments or customer profiles against documented scam indicators, thereby enhancing the detection and investigation of potential 419 or lottery scam transactions.

---

## [Individual, Entity & Public Records Databases](https://framework.amltrix.com/data-sources/DS0020)

**Description:**
Aggregated information on individuals and organizations from government registries, publicly available sources, and private third-party providers, including identity details, legal status, and beneficial ownership data.

### Related Techniques
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Aggregates background information on all involved parties, confirming legitimacy or highlighting red flags.
- Verifies whether entities have an operational history in insurance or connections to prior financial crimes.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Aggregated databases provide identity, residency, and other personal or corporate details.
- Supports cross-referencing employee credentials or business information with official government or reputable third-party records.
- Detects mismatches or indications of undocumented individuals, suggesting concealed payroll operations.
- [Disguised Remittance Transfers](https://framework.amltrix.com/techniques/T0040.001) — Aggregates official and publicly available data, including legal registrations, affiliations, and historical records, on individuals or organizations. This information verifies the legitimacy of claimed charitable recipients or family relationships, revealing inconsistencies that suggest a disguised transfer.
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Aggregates information on individuals and entities, including legal registration, public records, and known affiliations.
- Confirms whether individuals or associated businesses have ties to known petty crime or street gang activities.
- Enhances due diligence efforts by cross-referencing relevant profiles against suspected or confirmed criminal backgrounds.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Aggregate information on businesses and individuals from government registries, public sources, and private databases.
- Verify importer legitimacy and operational status, exposing shell entities that pay above-market prices.
- Help discern whether entities involved in export overvaluation exist solely to facilitate illicit transactions.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Aggregate identity and registration information on individuals and entities from public and private registries.
- Validate the actual existence and status of vendors or customers cited in manipulated revenue or expense accruals, uncovering sham entities used to falsify financial records.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Cross-references addresses, phone numbers, and identity attributes against public or official databases to detect anomalies, such as multiple claimants using a single address, and inconsistencies that suggest potential collusion or synthetic identity usage.
- [Real Estate Auction](https://framework.amltrix.com/techniques/T0108.001) — Aggregated identity details (e.g., names, addresses, family ties, corporate affiliations) from government registries and public sources.

- Helps detect potential collusion among auction participants by identifying shared addresses, overlapping corporate links, or family relationships.
- Flags individuals or entities appearing in multiple auctions under suspicious or interrelated ownership structures.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Aggregates information on organizational registrations, operational histories, and key individuals.
- Used to verify the legitimacy of entities involved in trade transactions, ensuring that suspicious or nonexistent parties are flagged for potential misinvoicing.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Aggregated data from official registries and public sources demonstrate an entity's or individual's legal status and background. This data is used to confirm the legitimacy of stated beneficiaries or business operations, highlighting any misrepresented fund purposes.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Aggregates external data on individuals and organizations, including official registries, public filings, and third-party records. Cross-referencing this information with customer-submitted details can highlight address mismatches, fraudulent identity claims, or overlapping attributes shared across multiple synthetic profiles.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Aggregates public and commercial data on individuals or entities, allowing cross-referencing of stated beneficial ownership details against multiple sources. Discrepancies or incomplete filings often signal potential ownership manipulation.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Aggregate identity information from government registries and commercial data providers to enable the verification of personal and business details.
- Help identify fictitious or inconsistent records, revealing possible identity impersonation or synthetic identities.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Aggregated public and official information about individuals and entities includes identity details, legal status, and beneficial ownership data.
- Cross-referencing submitted personal or corporate documentation against these records helps uncover inconsistencies or evidence of forged identities or misrepresented details.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Aggregates information from official registries and public sources, including identity details, legal statuses, and historical citizenship data. By cross-referencing these records, financial institutions can validate claimed nationalities, detect newly granted passports, and highlight inconsistencies where a single individual appears under multiple citizenships without legitimate rationale.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Aggregates data on businesses and individuals, including registration details, affiliations, and beneficial ownership.
- Helps uncover collusion or coordinated schemes among multiple entities submitting nearly identical cross-border settlement documents.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Aggregates identity details, public filings, and entity information from government registries and open sources.
- Aids in correlating personal identifiers, signatories, or contact information across multiple offshore corporations and real estate holdings.
- Enhances detection of overlapping control persons in multi-entity structures used to obscure foreign property ownership.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Aggregates public and official records about individuals and entities, including identity details, addresses, and registration data.
- Assists in verifying submitted personal information and spotting inconsistencies or duplicates across multiple account applications.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Provides aggregated data on individuals and businesses, including names, registration details, beneficial ownership, and entity status.
- Enables verification of the legitimacy of purported consulting clients, helping to identify fictitious or shell entities used to inflate revenue or commingle illicit proceeds.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Aggregated identity and legal status details from government registries and third-party providers.
- AML Relevance: Exposes unverifiable or nonexistent employees when cross-referenced against official records, revealing fictitious or duplicated identities.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Aggregates personal and entity information from government registries and public sources, including identity, corporate affiliations, and legal status. This data supports AML detection by identifying newly appointed bank executives or owners with suspicious backgrounds, high-risk associations, or ties to industries prone to money laundering, indicating potential criminal infiltration.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Aggregates identity, affiliation, and ownership details from official and public sources. Cross-referencing bettors, staff, or owners in these databases helps uncover undisclosed relationships among repeat winners or frequent ownership shifts in betting shops, revealing potential collusion or criminal affiliations.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Aggregated data from government registries and private providers contains identity details, addresses, and background information on individuals and entities. It cross-checks addresses, contact information, and ownership data with shipping documents, identifying fictitious or unverifiable listings commonly seen in ghost shipping schemes.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Aggregated information on individuals and organizations includes identity details, professional affiliations, and legal status. This data is used to verify whether a customer legitimately has involvement in archaeology, museums, or cultural heritage and to identify any red flags indicating illicit activity.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — Aggregates government and publicly accessible records, such as civil registries, address databases, and business affiliations, allowing direct cross-checking of a customer’s stated information against official sources to detect nonexistent, mismatched, or suspicious identity details.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Aggregated government and public records detailing the identity, affiliation, and legal standing of individuals or entities. This information can confirm or refute claimed beneficiary relationships and expose fraudulent next-of-kin designations in pension schemes.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Contains aggregated data on the legitimacy, registration, and operational history of counterparties. When entities report significant accruals tied to parties with no verifiable commercial activity or prior relationship, these databases help confirm or refute the authenticity of those claims, uncovering possible fraudulent accruals.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Aggregates public data on individuals and entities, including addresses, incorporation records, and prior directorships.
- Supports cross-checking of suspicious corporate formations or frequent changes in registration details across borders.
- Helps trace potential shell or front companies used in multi-jurisdiction laundering networks.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Government and publicly available registries contain official records of legal name changes, historical aliases, and any publicly filed identity data. Cross-referencing these databases enables investigators to confirm legitimate name changes or detect undisclosed variations, enhancing the ability to spot suspicious identity manipulation.

---

## [Document Management Systems](https://framework.amltrix.com/data-sources/DS0021)

**Description:**
Centralized platforms for storing, organizing, and managing a variety of records—such as KYC files, contracts, and other supporting documents—typically providing secure retrieval, version control, access permissions, and audit trails.

### Related Techniques
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Retains and organizes digital copies of submitted documentation for superannuation withdrawals. By comparing new claims with previously filed certificates, investigators can detect repeated or identical forged documents used across multiple accounts.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Centralized repositories of official contracts, player transfer documents, sponsorship agreements, and version histories.  
- AML Use: Helps detect incomplete, conflicting, or duplicated documentation (e.g., player transfer fees or sponsor contracts) that may indicate inflated or fabricated financial arrangements within the sports club.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Maintain requests and submissions of project documentation (e.g., cost breakdowns, progress reports), identifying delays or omissions.
- Track version control and revisions of documents, revealing frequent or unexplained changes to cost estimates or invoices.
- Provide an audit trail of all uploaded or modified files, highlighting potential attempts to conceal or alter evidence.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Stores submitted KYC documents, corporate filings, and other due diligence records.
- Detects incomplete or insufficient supporting information for accounts linked to high-risk jurisdictions.
- Enables auditors to trace submission timelines and identify purposeful document gaps that hinder transparency.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Store and manage supporting documentation (contracts, invoices, receipts) with version control and access logs.
- Enable verification of document authenticity, ensuring that accounting entries match legitimate invoices and receipts rather than forged or altered documents.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Stores and organizes multiple versions of relevant documentation, such as loan agreements, addendums, and supporting records, across co-lenders.
- Facilitates cross-checking for version discrepancies or unauthorized modifications that indicate intentional manipulation of syndicated finance documents.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Tracks submission, version history, and completeness of all documents related to junket operators and VIP clients.
- Identifies repeated postponements or partial responses that may indicate attempts to evade due diligence processes for junket-based transfers.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Store and organize insurance policies, claim documents, and supporting evidence.
- Facilitate the review of policy terms, risk coverage justification, and the validity of claim documentation, aiding in the detection of fabricated or inflated insurance claims.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Store and version electronic records, such as invoices, statements, and supporting files. Investigators examine changes across multiple versions to detect unexplained edits or fabrications that may indicate document manipulation.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Central repository holding corporate formation records, dissolution filings, and related documents.
- Enables verification of the stated reasons for frequent entity changes and cross-checking the authenticity of corporate paperwork.
- Supports investigators in obtaining detailed corporate documentation for analysis.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Stores official and draft versions of fund documentation, including valuation and performance reports. By comparing different document versions or changes over time, investigators can detect forged or manipulated records.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Centralized platforms store and track versions of financial and identification documents.
- Audit trails and version histories enable the detection of unauthorized alterations or suspicious modifications consistent with document forgery techniques.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Maintains records and version histories of asset documentation, including appraisal certificates or ownership filings for items stored in freeports. Enables the detection of suspicious alterations, missing records, or inconsistent documentation related to high-value assets.
- [Insurance Beneficiary Substitution](https://framework.amltrix.com/techniques/T0089) — - Stores and organizes policy documents, contracts, and updates related to insurance policies.  
- Facilitates the review of the frequency, timing, and legitimacy of changes to policyholder or beneficiary details, highlighting unusual or unsubstantiated modifications indicative of layering activity.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Central repository of digital copies of contractual agreements, proposals, addenda, and supporting documents.
- Tracks versioning, upload timestamps, and signatories for each document.
- Reveals inconsistencies or fabricated documentation used to justify purported consulting or management services.
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — - Stores transaction-related documentation, including legal or accounting briefs, retainer invoices, and supporting records.
- Enables investigators to locate repeated instances of 'professional privilege' claims that omit critical beneficial ownership or source-of-funds details.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Maintains version histories, timestamps, and user access logs for submitted settlement documents.
- Reveals repeated or suspicious alterations in cross-border documentation, aiding in the detection of manipulated invoices or trade references.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Stores and indexes receipts, invoices, and expense forms with version control and document histories. Investigators can detect duplicate receipts, identify unauthorized revisions, and pinpoint forged or altered documentation indicative of expense reimbursement fraud.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Store reference copies and official templates for financial instruments, checks, or promissory notes.
- Comparing submitted documents against the archived originals or authorized templates can uncover unauthorized modifications or forgeries.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Stores and tracks version histories of internal policies, procedures, and compliance documentation. This data helps identify policy revisions that weaken AML controls following suspicious ownership or leadership changes, revealing potential infiltration by criminals seeking to disable or circumvent oversight.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Centralized platforms store and track M&A-related documentation, such as board resolutions, internal memos, and purchase agreements. This data helps investigators verify document authenticity, detect forgeries or inconsistent version histories, and maintain audit trails. These capabilities support the identification of fictitious or altered corporate records indicative of sham M&A deals.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Store and track all versions of official documents, invoices, and related supporting records.  
- Provide audit trails of edits or newly uploaded files, detecting falsification of ledger entries or budget authorizations linked to stolen public funds.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Stores scanned check images and related metadata, enabling the clear detection of physically altered or suspicious checks, such as mismatched payee or endorsement details, when deposited via remote capture. This directly supports AML investigations by flagging unusually modified instruments before they clear.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Maintains version control and revision history for stored invoices and related documentation.
- Identifies frequent or unexplained invoice changes indicative of manipulative practices, such as repeated or inflated billing.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Stores and manages financial documents with version control and audit trails.
- Reveals unauthorized edits or suspicious changes to official records, enabling targeted investigations of potential tampering.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Centralized storage of wage statements, HR documents, and employer-submitted records.
- AML Relevance: Enables detection of repetitive, inconsistent, or fabricated wage documentation used in fictitious employer-employee fraud schemes.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Store and organize relevant legal, financial, and corporate documents, including formation records, contracts, and due diligence files. By reviewing version histories, access logs, and stored documents, investigators can identify inconsistencies, missing data, or other anomalies linked to suspicious intermediary activities.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — - Central storage of official tender documentation, including bid submissions and withdrawal notices.
- Version control and audit trails help detect synchronized proposals, last-minute amendments, and abrupt withdrawals, indicating possible collusive bid manipulation.

---

## [Financial Audits](https://framework.amltrix.com/data-sources/DS0031)

**Description:**
Audit reports containing independent examinations of an organization's financial statements and internal controls, typically conducted by external auditors, providing an objective assessment of financial accuracy and compliance with accounting standards.

### Related Techniques
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Provides independent audit findings on financial statements, highlighting inflated premiums, irregular claims, or non-standard reinsurance practices.
- Offers insight into discrepancies between reported figures and actual insurance activity.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Contain independent assessments of internal controls, policy adherence, and organizational compliance.  
- Highlight repeated policy breaches, breakdowns in segregation of duties, and other red flags of insider manipulation of AML processes.
- [Ponzi Schemes](https://framework.amltrix.com/techniques/T0144.019) — Contains independent examinations of an organization's financial statements and internal controls, helping to identify discrepancies between claimed returns and actual performance, a common hallmark of Ponzi schemes.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Financial audits involve independent examinations of financial statements, highlighting discrepancies, material misstatements, or unusual accrual treatments. These reports can uncover disclaimers or qualifications from auditors pointing to potential revenue manipulation or misleading liability classifications.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Provides independent evaluations of an entity’s financial statements and record-keeping practices.
- Detects multiple sets of conflicting invoices or shipping documents, a hallmark of fictitious operations.
- Identifies irregular bookkeeping entries pointing to fraudulent jewelry sales or duplicated records.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Independent examinations of financial statements, internal controls, and record-keeping.
- Highlights systematic discrepancies or repeated adjustments consistent with tampering in official records.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Provide independent audit assessments of an organization's financial statements and internal control systems.
- Reveal suspicious accounting practices, control weaknesses, or repeated adjustments indicative of intentional financial record manipulation.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Comprehensive external or internal audit reports can uncover discrepancies by verifying a fund’s reported financial statements, calculations, and supporting documentation. These reports highlight manipulated valuations or unsubstantiated performance claims central to this technique.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Provides independent audit findings and details on internal financial controls.
- Highlights discrepancies or missing information in agricultural production reports or expense records.
- Helps uncover areas where criminals may be hiding sustained losses or fabricating financial statements to launder illicit funds.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Independent examinations of financial statements and internal controls include official audit or due diligence reports for M&A transactions. These records confirm the authenticity of reported financial figures and highlight any discrepancies, forged documentation, or rapidly altered audit opinions—key signals of fraudulent or fictitious mergers and acquisitions.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Consists of independent audit reports examining an organization's financial records.
- Supports the detection of manipulated or falsified statements used to hide taxable income or misrepresent expenditures.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Provide independent audit reports evaluating the accuracy of financial records and compliance with internal controls.
- Uncover missing funds, unauthorized write-offs, or irregular entries that indicate corrupt misappropriation schemes.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Offers independent examinations of an organization’s financial statements and internal controls to confirm legality and accuracy. This data highlights mismatches between reported income and injected capital, indicating potential money laundering or inflated valuations.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Include independent examinations of financial statements, focusing on payroll accuracy and related internal controls.
- Detect hidden wage liabilities or significant cash outflows not reflected in formal records.
- Strengthen AML investigations by verifying that official accounting aligns with actual wage expenditures.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Auditor reports evaluate the accuracy of financial statements and internal controls.
- They flag irregular fair value adjustments or questionable accounting practices.
- They provide independent confirmation of a company’s declared finances, uncovering hidden ownership or money flows.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Contains independent audit reports examining an entity’s financial statements and controls. These reviews help identify discrepancies in reported investment returns or misstatements in fund management, a common hallmark of Ponzi-type or fraudulent schemes.

---

## [Safe Deposit Box Access Records](https://framework.amltrix.com/data-sources/DS0034)

**Description:**
Records tracking access to safe deposit boxes, including the date, time, and identity of the individual accessing the box.

### Related Techniques
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Tracks when, how often, and by whom safe deposit boxes are accessed.
- Helps uncover the storage of high-value precious metals or gemstones inconsistent with a customer’s profile, indicating possible smuggling or laundering of illicit proceeds.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — - Records each access event, including the date, time, and identity of the authorized user.
- Enables the detection of unusual or frequent visits that may indicate illicit storage or transactions.
- Supports cross-referencing with transaction patterns to identify potential structuring or hidden cash movements.

---

## [Online & Digital Payment Platform Data](https://framework.amltrix.com/data-sources/DS0022)

**Description:**
Consolidated records from online payment platforms, e-wallets, and fintech payment processors, covering transaction details, user identifiers, operational data, balances, transaction volumes, and related metadata.

### Related Techniques
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Consolidates transaction details from P2P or digital payment services, including user identifiers, transfer volumes, and timestamps.
- Supports identification of repeated small payments that collectively form significant sums, potentially used to layer illicit funds.
- Facilitates detection of unusual P2P transaction clusters lacking a legitimate economic rationale.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Consolidates transaction details, user identifiers, balances, and platform usage metrics.
- Helps detect unusual payment flows, anonymous transfers, and unregistered e-wallet activities possibly linked to sexual exploitation proceeds.
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Captures e-wallet or digital account transactions, including cash-out requests.
- Identifies frequent or structured conversions of online balances to physical currency, supporting investigations of immediate cash-out schemes.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Captures transaction records, user identifiers, and operational data from e-wallets or digital payment providers.
- Allows tracing of small contributions made through common payment tools, identifying repeated or coordinated transfers into a single beneficiary account.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — Payment platform data captures usage records from e-wallets and fintech processors, including:

- Multiple payment accounts or methods tied to the same user.
- Transaction timelines and volumes across different platforms.

This data helps pinpoint customers employing diverse payment instruments to execute and later dispute transactions, revealing recurring chargeback abuse patterns.
- [Chip Dumping](https://framework.amltrix.com/techniques/T0107.003) — - Captures transaction details, user identifiers, e-wallet usage, mobile payment methods, and related operational data from digital platforms.
- Identifies suspicious deposit or withdrawal patterns, frequency, and velocity across multiple accounts.
- Correlates with casino transaction records to detect rapid chip transfers and potential collusion or funneling of funds in chip dumping schemes.
- [Online Gambling](https://framework.amltrix.com/techniques/T0017) — - Captures e-wallet and digital payment transactions, including user identifiers, timestamps, amounts, and device details.
- Reveals structured or frequent deposits funneled from digital payment accounts into multiple gambling accounts.
- Supports detection of layering attempts leveraging alternative payment methods to obscure the origin of funds.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Compiles records of user identities, transactions, and operating details from digital wallets and payment platforms. This data helps uncover abrupt or large-value withdrawals and conversions from game environments to fiat, often via third-party brokers with lax AML controls.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Consolidates user account details, transaction histories, and payment flows on digital platforms and e-wallets.
- Enables detection of unusual bursts of in-game currency purchases, frequent microtransactions, and rapid withdrawals to external accounts or cryptocurrency conversions.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Consolidates transaction details from fintech payment processors, mobile wallets, and online payment interfaces.
- Helps map repetitive and rapid routing of funds across diverse payment services, consistent with automated layering.
- Identifies unusual usage across multiple digital payment methods lacking clear economic rationale.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Includes e-wallet transaction information, user account details, balances, and usage patterns. Analysis of cross-border transfers, partial anonymity features, and repeated low-value transactions helps detect layering and threshold evasion linked to offshore e-wallet issuers.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Contains detailed records from e-wallets and other digital payment services, including user identifiers, transaction timestamps, amounts, and operational metadata.
- Helps uncover potentially high-volume or atypical payments associated with the sale, distribution, or facilitation of exploitative content involving minors.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Captures transaction details from online payment processors and e-wallets, including user identifiers, transaction dates, and amounts.

- Helps identify abnormal purchase patterns for in-game assets, rapid liquidation of gaming items, and potentially high-frequency or large-volume transactions inconsistent with typical gameplay.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Captures bidding and payment logs on online auction and payment platforms.
- Identifies staged or nonexistent competition, repeated winning by the same bidder, or other auction irregularities, uncovering sham or fictitious sale events.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Stores transaction volumes, user account details, and cross-border payment flows for e-wallets or fintech platforms.
- Highlights incomplete or forged customer information for large or frequent gambling-related transfers.

This data aids AML detection by flagging suspicious digital payment behaviors and unverified accounts funneling illicit proceeds through offshore gambling.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Consolidates transaction details, user identifiers, and operational data from e-wallets or app-based remittance services.
- Highlights inconsistencies in user information across multiple platforms, detecting potential misuse or rapid account switching.
- [Mobile Payment Systems](https://framework.amltrix.com/techniques/T0134.002) — Captures transaction details from mobile wallets and P2P payment platforms, including timestamps, amounts, user IDs, and transaction types. This data enables the detection of unusual volume spikes, structured transaction patterns, and frequent switching among different mobile payment services for layering.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Includes records from e-wallets and fintech platforms detailing transaction amounts, payment methods, and funding sources. In lottery-focused laundering:

- Pinpoints the use of prepaid cards or anonymous payment methods for ticket purchases.
- Helps identify layering attempts through multiple online platforms.
- Correlates unusual digital payment flows with lottery purchases or redemptions.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Consolidated records from e-wallets and fintech payment processors, covering transaction details, user identifiers, balances, and usage patterns.
- Helps reveal micro-amount flows dispersed across multiple digital platforms in short timeframes, indicative of micro-structuring.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Collects transaction details, user identifiers, shipping confirmations, and refund records from e-commerce and digital payment services. This data allows analysts to identify inflated pricing, detect unfulfilled orders, spot frequent high-value refunds with minimal justification, and pinpoint other suspicious patterns indicative of manipulated online sales or sham transactions.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Captures transaction details from digital auction sites, e-wallets, and similar fintech platforms used for collectible purchases and sales.
- Helps identify frequently used online channels with limited record-keeping that facilitate partial concealment of collectible trades.
- Detects large volumes of auctions or private sales inconsistent with a customer’s profile, indicating potential money laundering activity.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Tracks e-wallet and digital payment usage, including transaction details, user identifiers, and refund/chargeback records. This helps detect potentially fraudulent or excessive refunds tied to substandard pharmaceuticals.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Tracks e-wallet and fintech payment processor transactions, including user identifiers, transaction amounts, and metadata.
- Detects patterns of rapid or high-volume transfers through digital channels, often exploited by drug traffickers for layering.
- Facilitates the identification of cross-platform money flows that circumvent traditional banking controls.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — These records include transaction timestamps, amounts, user identifiers, device or platform usage logs, and cross-platform flow details from e-wallets, digital payment processors, and peer-to-peer platforms. This data is essential in tracing the layering of payment tokens across multiple online channels, identifying suspicious patterns such as smurfing, and detecting unverified or non-compliant users exploiting minimal KYC requirements.
- [Test Payment Probing](https://framework.amltrix.com/techniques/T0035) — - Includes transaction details and metadata from e-wallets and fintech platforms, enabling the identification of small-scale probing behaviors across digital channels.
- Helps correlate changes in transaction patterns or account details after initial test payments, indicating criminals' adaptation to detected monitoring rules.
- [Peer-to-Peer (P2P) Transfers](https://framework.amltrix.com/techniques/T0134.001) — Allows monitoring of P2P-specific transaction amounts, helping to identify patterns of structured transfers that remain below mandated reporting limits.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Provides records from e-wallets and fintech payment processors, including transaction details, user accounts, and usage patterns.
- Detects whether a single agent or sub-agent is splitting or aggregating transactions across multiple digital platforms.
- Supports identification of structured deposits, rapid fund movements, and other anomalies possibly obscured by multi-provider usage.

---

## [Financial Instrument & Securities Market Data](https://framework.amltrix.com/data-sources/DS0035)

**Description:**
Comprehensive datasets covering stocks, bonds, derivatives, and other investment vehicles, including the instrument’s name, type, issuer, maturity date, interest rate, real-time and historical pricing, trading volumes, and market trends. Financial institutions may reference this information to monitor investments and detect unusual price or volume movements.

### Related Techniques
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Provides real-time and historical pricing, market volumes, and trading trends for securities.
- Enables detection of anomalous price and volume spikes immediately before corporate announcements.
- Supports correlation of trade timing with non-public or market-moving events, exposing potential insider dealing.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Provides official market information, including pricing and trading activity for financial instruments.
- Allows comparison of declared asset values versus actual market prices.
- Flags privately arranged transfers outside regulated exchanges that can mask beneficial ownership changes.
- [Securities Account Ownership](https://framework.amltrix.com/techniques/T0088.001) — Provides real-time and historical data on various securities, including pricing, volumes, and market trends, to detect:

- Suspicious spikes in trade volumes or abrupt asset flows.
- Unusual price movements suggesting potential manipulation or wash trading.

By comparing actual trading data with normal market conditions, investigators can identify patterns indicative of securities account manipulation and layering activities.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Allows comparison of typical market rates for insurance or reinsurance arrangements.
- Helps detect significantly inflated premiums or coverage that deviate from standard industry benchmarks.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Monitors trading and usage of various financial instruments, including hedging products, derivatives, and related securities.
- Helps detect inconsistencies between normal hedging strategies and suspicious FX movements aimed at concealing illicit proceeds.
- Supports investigations into abnormal derivative positions used to legitimize unusual currency flows in trade finance contexts.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Includes real-time and historical pricing, trading volumes, and instrument details. By comparing a fund’s reported valuations and returns with actual market data, investigators can detect inflated or fabricated performance metrics, revealing suspicious discrepancies indicative of investment fund manipulation.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Provides real-time and historical pricing data, trading volumes, and market trends for stocks, bonds, and other securities.
- Enables detection of sudden spikes in trading volume, unusual price movements, rapid reversals, and other anomalies indicative of artificial market manipulation.
- Facilitates comparison of specific asset performance against broader market benchmarks to identify potential pump-and-dump or spoofing schemes.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Real-time and historical data on stocks, bonds, and other securities, including pricing, trading volumes, and issuer details.
- Helps identify patterns of high-volume liquidation, short-term trading, or suspiciously large holdings that may be used to layer or obscure illicit funds within investment portfolios.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Provides real-time and historical data on financial instruments, including trade volumes, price movements, instrument types, and market benchmarks. Analysts can compare typical trading strategies against actual fund activity to identify excessive asset turnover, rapid portfolio rebalancing, or other deviations suggestive of money laundering through investment vehicles.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Provide real-time and historical pricing, trading volumes, and market trends for stocks and other securities.
- Enable detection of transactions at prices deviating significantly from prevailing market rates, a hallmark of stock manipulation.
- Facilitate monitoring of sudden volume or price spikes in low-liquidity stocks frequently targeted for pump-and-dump schemes.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Includes real-time and historical pricing, trading volumes, and instrument details. By comparing actual trade activity against typical market conditions, financial institutions can identify unusual patterns, such as consistent offset trades with identical volumes and minimal price impact, which are suggestive of mirror trading.
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Includes trading volumes, pricing, and other market data for stocks, bonds, and similar financial instruments.
- Helps identify sudden liquidations, rapid turnover of recently acquired assets, or unusual trading patterns that contradict declared long-term investment strategies, indicating potential money laundering.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Provides comprehensive information on bonds and derivatives, including structural details, trading volumes, and pricing history. This data aids in identifying complex or opaque bond structures, unusual trading activity, and potentially short holding periods inconsistent with typical investment strategies.
- [Offsetting Transactions](https://framework.amltrix.com/techniques/T0102) — - Provides real-time and historical data on pricing, trading volumes, and market trends for stocks, bonds, derivatives, and other securities.
- Correlates trade executions with market conditions, allowing for the identification of trades that deviate from typical price ranges or exhibit no genuine market impact.
- Aids in detecting artificially high liquidity, suspicious matched orders, and offsets that result in no net economic change.
- [DeFi Transactions](https://framework.amltrix.com/techniques/T0067.004) — Offers real-time and historical token pricing, yield rates, and market benchmarks, helping to identify abnormal valuations or manipulated yields within DeFi transactions that may indicate illicit layering or fund obfuscation.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Contains comprehensive trading and pricing data for stocks, bonds, and other securities, including historical performance and market trends. This information can be used to compare an investment scheme's claimed returns with actual market performance, revealing discrepancies indicative of fraud.

---

## [Trade Documentation](https://framework.amltrix.com/data-sources/DS0036)

**Description:**
Official documents required for international trade, such as shipping logs, customs declarations, bills of lading, invoices, and certificates of origin. Often used to verify the legitimacy of cross-border transactions, confirm declared goods, and detect potential trade-based anomalies.

### Related Techniques
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Includes shipping logs, customs declarations, bills of lading, and invoices.
- Allows comparison of declared goods and values to detect inconsistencies.
- Essential for uncovering fabricated or inflated trade transactions in shell-based layering.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Comprises shipping logs, bills of lading, customs declarations, invoices, and certificates of origin.
- Helps confirm the legitimacy and declared nature of exported or imported commodities.
- Enables cross-checking financial transactions against physical shipment data to reveal trade-based money laundering attempts.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Encompasses bills of lading, shipping manifests, and other trade-related documents to confirm the authenticity of shipped goods, quantities, and routes. This helps identify phantom shipments or discrepancies between claimed and actual trade activity in Bill of Exchange financing scenarios.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Includes shipping logs, customs declarations, bills of lading, and invoices detailing cross-border commodity movements. Investigators can compare declared shipments with actual goods and pricing to identify misdescription, under- or over-invoicing, and document inconsistencies indicative of smuggling.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Comprises bills of lading, commercial invoices, and shipping records for agricultural goods.  
- Facilitates cross-checks of stated product types, quantities, and routes with industry norms.  
- Highlights discrepancies in declared logistics arrangements that may signal fraudulent or inflated trade transactions used for laundering.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Encompasses official shipping logs, bills of lading, and other trade certificates.
- Compares declared product or shipment details in cross-border settlement documents with actual shipping data, exposing fraudulent or fabricated records.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — Comprises shipping logs, bills of lading, customs declarations, and certificates of origin used in international trade. This data helps verify declared goods, identify commodity mislabeling, and flag unusual shipping routes or volumes indicative of precursor chemical trafficking.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Includes bills of lading, shipping logs, invoices, and other required documents.
- Allows comparison of declared goods, quantities, and prices to detect inflated or inconsistent valuations.
- Verifies importer details and cross-checks them against official records to expose suspicious recipients.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Consists of shipping logs, bills of lading, invoices, and certificates of origin, allowing for the verification of declared mineral shipments. This cross-check helps detect inconsistencies in reported volume, origin, or value that may indicate illegal mining activities.
- [Cross-Border Cash Smuggling](https://framework.amltrix.com/techniques/T0065) — - Includes bills of lading, shipping manifests, and customs declarations for cargo and mail shipments.
- Helps detect discrepancies between declared goods and concealed currency, indicating potential cross-border smuggling of cash hidden in commercial or mail shipments.
- Provides documentary evidence of shipping routes, raising red flags if there is no legitimate commercial rationale for the transport.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Official records required for international trade include shipping logs, bills of lading, customs declarations, and invoices. 

- These records allow for the verification of declared commodities, routes, and transaction details.
- They facilitate the detection of discrepancies such as over/under-invoicing, unexplained changes to shipping routes, or amendments to letters of credit.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Provides official trade records, including bills of lading, commercial invoices, shipping manifests, and certificates of origin.  
- Enables direct verification of declared goods, quantities, and values against official paperwork, revealing suspicious discrepancies or valuations indicative of trade misinvoicing.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Covers shipping logs, bills of lading, certificates of origin, and related documentation.
- Facilitates cross-checking of sector-specific permits (e.g., harvesting or export certificates) against actual trade records.
- Enables detection of falsified or non-existent documents used to justify suspicious commodity transactions.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — Trade Documentation encompasses official shipping logs, customs declarations, bills of lading, and invoices that confirm whether genuine goods or services changed hands. This data helps detect phony or inflated trade-based offset transactions commonly used in IVTS to mask cross-border settlements.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Encompasses official shipping records, customs declarations, bills of lading, and certificates of origin.
- Enables detection of repeated exports or imports of identical diamond parcels and verification of declared shipments.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Encompasses shipping manifests, bills of lading, customs declarations, and certificates of origin.
- Validates that purported jewelry shipments actually occurred, matching invoice or payment records.
- Identifies absent or contradictory trade documents suggestive of nonexistent shipments or falsified imports.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Comprises official shipping logs, bills of lading, customs declarations, and certificates of origin.
- Assists in identifying hidden routes, re-shipments, or final destinations associated with sanctioned countries concealing illicit flows.
- [Daigou Networks](https://framework.amltrix.com/techniques/T0013.006) — Includes official bills of lading, invoices, and customs declarations for imported goods, enabling:

- Verification of declared values, item types, and quantities against financial transactions for potential misrepresentation.
- Detection of repeated shipments of high-demand consumer goods exceeding normal personal usage.

This documentation helps investigators confirm whether import activities align with legitimate trade or mask Daigou-facilitated laundering.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Includes bills of lading, shipping logs, customs declarations, invoices, and certificates of origin.
- By comparing declared goods and quantities with actual shipments, investigators can detect disguised arms consignments and trace patterns indicative of arms trafficking.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Bills of lading, shipping logs, invoices, letters of credit, and other official trade records.  
- AML Relevance: Enables comparison of declared goods, values, and shipping details to identify inconsistencies, forged documents, or mismatched records indicative of fictitious cross-border transactions.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Encompasses bills of lading, invoices, and shipping manifests for international trade.
- Validates declared goods and quantities, revealing potential misinvoicing or false documentation.
- Highlights suspicious trade-based activities tied to environmental crime proceeds.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Encompasses bills of lading, shipping invoices, and certificates of origin for timber shipments. By verifying declared cargo details (e.g., volumes, species, origin) against official paperwork, it reveals mismatches or missing permits indicative of illegal logging or trade-based laundering.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Official records and paperwork related to international or domestic trade, such as bills of lading and shipping logs, can be cross-referenced with the declared purpose of import or export transactions to reveal potential misrepresentation.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Includes bills of lading, invoices, and certificates of origin relevant to jewelry shipments.
- Missing or inconsistent documentation for high-value items can signal manipulated valuations used to conceal illicit funds or evade regulations.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Comprises shipping logs, bills of lading, invoices, and customs declarations for cross-border transactions. This data helps investigators:

- Uncover contradictory, duplicated, or inflated invoice details in countertrade deals.
- Verify the authenticity of trade flows, detecting cyclical or repeated shipments of the same goods.
- [Third-Party Payments](https://framework.amltrix.com/techniques/T0073) — Comprises invoices, bills of lading, and other shipping records that identify the official buyer, seller, and payment terms. Comparing these records against transaction data helps detect discrepancies when a third party, not named in the trade documents, makes or receives payments, indicating potential concealment of real beneficiaries.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Includes shipping records, customs declarations, bills of lading, and invoices related to underlying trade transactions.
- Allows cross-checking declared goods, quantities, and values against actual shipments, revealing inflated or falsified trade data supporting loan manipulation.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Encompasses shipping records, invoices, and certificates of origin used in cross-border trade.
- Verifies declared commodity types, quantities, and values, exposing mislabeling or falsified documentation central to precious commodity smuggling.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Encompasses shipping logs, bills of lading, and certificates of origin used to validate cross-border shipments. Investigators compare trade-related documents to internal invoices or statements to uncover forged entries or inconsistent details in manipulated records.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Comprises invoices, bills of lading, and shipping records for international transactions.
- Distinguishes legitimate trade activities from fabricated sales or suspicious payments funneled through trade-based channels.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Includes bills of lading, certificates of origin, shipping logs, and customs declarations.
- Enables verification of shipping details, routes, and commodity descriptions to detect forged or incomplete documents.
- Helps identify inconsistencies in declared goods, values, and counterparties indicative of documentary collection manipulation.
- [Inflated Transaction Pricing](https://framework.amltrix.com/techniques/T0008.002) — - Covers shipping logs, bills of lading, and customs declarations.
- Facilitates reconciliation of declared goods, quantities, and valuations against invoiced amounts.

This cross-check helps reveal inflated or otherwise manipulated pricing in cross-border trade scenarios.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Contains official trade records such as bills of lading, shipping logs, customs declarations, and product classifications.
- Allows comparison of declared goods, product codes, and values to uncover misclassification, inflation, or under-reporting of goods and services used to conceal illicit fund transfers.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — - Comprises shipping logs, bills of lading, cargo manifests, and related documents essential for cross-border commerce.
- Enables investigators to track repeated amendments, discrepancies between declared and actual goods, or inconsistencies in declared values, which are key red flags for money laundering via bonded warehouses.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Involves bills of lading, shipping logs, and certificates of origin that describe goods, valuations, and transit routes.
- Matching these with provided shipping paperwork highlights inconsistencies or manipulated entries, indicating document forgery in trade-based laundering schemes.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Includes official shipping documents (e.g., bills of lading, invoices, certificates of origin) used in cross-border trade. 

- Allows detection of ghost shipping by verifying the authenticity and consistency of container numbers, shipping addresses, and invoice references across multiple transactions.
- Helps identify repeated reuse of identical documentation, last-minute alterations, or mismatches in declared goods and volumes, all of which may indicate nonexistent shipments.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Includes bills of lading, shipping manifests, and invoices for international shipments. Validates the movement of high-value assets and uncovers missing or inconsistent paperwork for items stored in or transferred through freeports.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Provides official shipping logs, bills of lading, customs declarations, and insurance documents necessary to substantiate or refute claimed trade activity. Reviewing these records helps uncover potential fraudulent or inflated shipments, phantom cargo, or mismatches between financed goods and actual deliveries.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Consists of shipping logs, invoices, customs declarations, certificates of origin, and appraisal reports for precious metals or gemstones. This data helps:

- Detect mismatched certificates or inconsistent provenance records.
- Validate transaction details (e.g., quantity, quality, or type of precious commodities) against declared documentation.
- Uncover potential trade-based money laundering tactics, such as falsified documentation or over-/undervaluation schemes.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Maintains shipping logs, customs declarations, bills of lading, and other trade-related records.
- Permits validation of declared goods, repeated shipments, and potential phantom transactions used to disguise circular flows.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Bills of lading, invoices, shipping logs, certificates of origin, and other official trade records.

- Direct AML Relevance: Crucial for detecting under- or over-invoicing, repetitive shipments with inconsistent pricing, and mismatches between declared goods and shipping details, all indicative of Black Market Peso Exchange.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Includes bills of lading, invoices, certificates of origin, and shipping logs for cross-border transactions.
- Allows verification of declared goods and detection of inconsistencies in shipping documents where wildlife products might be disguised.
- Supports investigation into potential trade-based money laundering schemes.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Includes shipping manifests, bills of lading, invoices, and certificates of origin for cross-border transactions.
- Helps verify declared tobacco products, detecting mislabeling or inconsistent documentation that conceals smuggling.
- Reveals repeated use of deceptive shipping routes or incomplete trade details associated with tobacco shipments.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Includes shipping logs, customs declarations, bills of lading, invoices, and certificates of origin related to FTZ transactions.
- Enables detection of over- or under-invoicing, repeated re-exports, and discrepancies in declared cargo.
- Validates whether goods actually enter or leave the free zone or simply circulate to mask the true flow of funds.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Encompasses shipping records, manifests, bills of lading, and related logistical documents, allowing direct comparison of declared goods and services against invoiced details. This data helps confirm whether shipments are actually duplicated or whether reference numbers are reused to support multiple billings.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Contains shipping logs, customs declarations, and bills of lading.
- Verifies whether goods are genuinely shipped or delivered, exposing fabricated transactions when the physical movement of merchandise is absent or contradicted.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Encompasses bills of lading, invoices, customs declarations, and shipping records for cross-border trade.
- Allows for scrutiny of commodity quantities, declared values, and shipment timelines.

These records support the detection of Hot Transfers involving trade-based offsets by revealing inconsistencies or mismatches in shipping schedules, product values, or invoicing that disguise the true flow of funds.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Comprises shipping records, customs declarations, bills of lading, and certificates of origin.
- Validates whether goods or services are physically moved or provided as described.
- Exposes repeated or cyclical shipments among related entities indicative of VAT carousel abuse.
- [Shipping Document Manipulation](https://framework.amltrix.com/techniques/T0069) — Provides official records needed to verify cross-border shipments (e.g., bills of lading, manifests, shipping logs, invoices). This data directly supports AML detection by:

- Tracking version histories of shipping documents to identify suspicious or excessive amendments that may indicate document tampering.
- Checking for insufficient or imprecise product details, missing or contradictory invoice information, and repeated or duplicated shipping document identifiers.
- Verifying whether listed carriers, routes, and packaging methods align with the declared goods.
- Ensuring essential supporting documentation (e.g., purchase orders, contracts) is present.
- Detecting inconsistencies between declared cargo and a party’s typical business scope.

These checks help expose forged or manipulated shipping records used to disguise illicit funds.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Includes shipping logs, bills of lading, and other official documentation for cross-border transactions.  
- Matching these documents against the data presented in letters of credit or other financial instruments helps identify inflated or fictitious values.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Comprises bills of lading, shipping logs, customs declarations, invoices, and certificates of origin.
- Verifies legitimate trade flows versus suspected trade-based money laundering or shipments masking drugs.
- Enables investigators to detect discrepancies between declared goods versus routes and parties involved.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Includes bills of lading, invoices, and certificates of origin, capturing commodity classification details and declared valuation.
- Helps expose misdeclared or under-invoiced diamond shipments and verify the authenticity of Kimberley Process Certificates.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Encompasses bills of lading, shipping manifests, and related customs forms. Cross-referencing these records with the stated terms in red/green clause letters of credit (LCs) helps confirm whether actual shipments match declared cargo and values.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Includes bills of lading, shipping logs, cargo descriptions, customs declarations, and other official trade paperwork. Cross-referencing these details can reveal inconsistent routes, mislabeling of goods, or last-minute changes that signify trade diversion.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Provides official records for international trade (e.g., bills of lading, customs declarations, certificates of origin) and detailed shipping data.
- Enables comparison of declared shipment volumes, destinations, and product grades with actual records to detect falsification or inconsistencies.
- Supports identification of over-/under-invoicing, forged shipping documents, and other anomalies central to oil and fuel transaction manipulation.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Includes shipping records, customs declarations, bills of lading, and chain-of-custody documents for cross-border shipments. This data helps match declared origins, destinations, and valuations of cultural artifacts with official shipping and ownership documentation, revealing discrepancies indicative of illicit trade.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Encompasses bills of lading, customs declarations, and other official documents detailing cross-border shipments.
- Shows declared valuations, origins, and quantities of goods, aiding in the detection of improper valuations or incomplete documentation linked to laundering high-value assets.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Includes official shipping records (bills of lading, customs declarations, packing lists) detailing contents and quantities.
- Cross-checking these documents against invoice data helps identify discrepancies between declared goods and invoiced amounts or values.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Includes critical trade documents, such as bills of lading, commercial invoices, shipping manifests, and certificates of origin, used to validate declared goods, quantities, prices, and shipping details. Financial institutions and investigators can compare these documents against other records to uncover multiple re-invoicing, phantom shipments, or inflated costs in trade-based money laundering schemes.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Includes bills of lading, shipping logs, invoices, certificates of origin, and related records.
- Assists in uncovering undervaluation or reclassification of gold by comparing declared information with actual purity or market benchmarks, exposing potential trade-based laundering.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Includes shipping logs, customs declarations, bills of lading, and certificates of origin.
- Verifies the existence and legitimacy of goods or shipments purportedly linked to letters of credit.
- Detects repetitive or non-existent shipping documents, clarifying whether actual trade activity supports the circulation of funds.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Includes shipping logs, customs declarations, invoices, and bills of lading for cross-border trade.
- Reveals overstated export values or bogus transactions used to claim inflated tax rebates.
- Corroborates declared shipments with actual goods to detect fraudulent export-based rebate schemes.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Provides bills of lading, import/export declarations, and shipping details, assisting in cross-checking declared versus actual goods and detecting rerouted or disguised counterfeit pharmaceuticals.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Provides official records required for international trade, such as shipping logs, bills of lading, invoices, customs declarations, and certificates of origin.
- Enables cross-checking of declared goods or services against actual shipments, revealing inflated, understated, or misrepresented transactions.
- Assists in detecting suspicious discrepancies in invoice values or foreign exchange trades that may indicate trade manipulation and illicit fund movements.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Covers shipping logs, customs declarations, and bills of lading. When paired with hawala, fraudulent or inflated trade records may be used to mask illicit cross-border fund movements, making these documents critical for verification.

---

## [Job Recruitment Data](https://framework.amltrix.com/data-sources/DS0037)

**Description:**
Records from online job recruitment platforms, including job postings, candidate applications, and employment details. These data can reveal unusual recruitment patterns or potential money mule schemes.

### Related Techniques
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Includes job postings, candidate applications, and employment details from recruitment platforms.
- Identifies suspicious postings offering high compensation for cross-border travel or courier-like roles.
- Supports AML detection by flagging patterns of potential 'cash mule' recruitment, correlating individuals' job applications with frequent international travel carrying large sums of cash.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Provides verified records of legitimate job postings and employment offers on recognized platforms.
- Reveals any mismatch between the account holder’s claimed recruitment scenario and actual job listings. This directly supports AML investigations by identifying fraudulent or fabricated recruitment claims typical of money mule schemes.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — - Contains job postings, candidate applications, and employment details from recruitment platforms.
- Helps detect fictitious employer-employee relationships or inflated wage records used to justify higher unemployment benefits.
- Cross-referencing claimants’ stated employment histories with actual recruitment records can expose potential fraud.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Provides records of job listings, employer details, and candidate applications, facilitating the detection of sham job offers targeting individuals to receive or move illicit funds as part of a mule scheme.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Encompasses job postings and candidate information referencing off-the-books or cash-based wages.
- Identifies businesses advertising or attracting undocumented workers, uncovering potential hidden payroll schemes.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Includes job listings, candidate applications, and recruitment platform records.
- Identifies unrealistic job postings featuring 'payment processing' or quick cash offers.
- Helps detect patterns of fake recruitment ads targeting victims for money mule roles.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Document job postings and candidate placements through recruitment agencies.
- Detect minimal legitimate hires but significant wage flows indicative of human trafficking fronts.
- Uncover nonexistent positions or misrepresented roles used to funnel illicit proceeds.
- [Money Mule Exploitation](https://framework.amltrix.com/techniques/T0011) — - Consists of postings, applications, and records from recruitment platforms, allowing for the identification of suspicious or fraudulent job ads that promise easy income for receiving and transferring funds.
- Helps link newly opened accounts to potentially compromised or complicit individuals recruited as mules through dubious advertisements.
- Supports investigations by pinpointing clusters of applicants who might have been directed to open accounts for illicit fund movements.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Contain records from job postings, candidate applications, and recruitment portals.
- Reveal job ads focusing on payment processing responsibilities rather than genuine employment qualifications.
- Identify applicants recruited under suspicious terms, such as using personal accounts for business-like transactions.

---

## [Virtual Asset Service Provider (VASP) Data](https://framework.amltrix.com/data-sources/DS0038)

**Description:**
Data from Virtual Asset Service Providers, including detailed logs of digital asset transactions such as amounts, timestamps, wallet addresses, sender and receiver information, and associated account details, as well as user activity within cryptocurrency exchanges (e.g., trading volumes, order details, and user behaviors).

### Related Techniques
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — - Includes user account details, wallet addresses, KYC records, trading activities, and deposit/withdrawal logs from crypto exchanges.
- Links in-game or NFT transactions to external off-ramps, helping trace final conversion into fiat or mainstream cryptocurrencies for AML investigations.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Stores detailed logs of user registration, wallet addresses, and transaction histories within exchange or token launch platforms.
- Provides visibility into large purchases, suspicious deposit or withdrawal patterns, and user-level behaviors for potential money laundering or fraudulent fundraising activities.
- [Cross-Chain Token Wrapping](https://framework.amltrix.com/techniques/T0067.002) — **Data Provided:**

- Detailed logs of digital asset transactions, including amounts, timestamps, and wallet addresses processed by VASPs.
- User account information, trading volumes, and history of interactions between custodial and decentralized platforms.

**How It Supports Detection/Investigation:**

- Identifies the use of multiple VASPs with lax AML measures to conduct large-scale wrapped token transfers.
- Detects suspicious bridging flows and cross-chain activities facilitated through VASP infrastructure.
- Supports uncovering patterns of rapid token wrapping and unwrapping designed to obscure the origin of funds.
- [Cryptocurrency Mixing](https://framework.amltrix.com/techniques/T0003) — Contains detailed logs of digital asset transactions, including amounts, timestamps, and wallet addresses, along with related customer information. This data helps identify interactions with non-compliant mixers or addresses flagged for mixer involvement, monitor KYC gaps, and trace high-volume or repetitive transactions associated with layering via mixing platforms.
- [Peel Chain](https://framework.amltrix.com/techniques/T0070.002) — Includes VASP-held transaction logs, user account details, wallet address assignments, and deposit/withdrawal records, allowing the linkage of on-chain peel chain hops to specific exchange user accounts or identities. This data is critical for detecting suspicious patterns, such as multiple micro-deposits or rapid withdrawals, and correlating them with on-chain evidence of layering and fragmentation in a peel chain scheme.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Encompasses detailed logs from VASPs, including user account information, transaction histories, wallet addresses, and trading patterns, correlated with crypto ATM activity. This data enables more robust tracking of digital asset flows, linking on-chain movements to real-world identities and uncovering layering or structuring schemes across different service platforms.
- [Burn and Mint Transfers](https://framework.amltrix.com/techniques/T0005.001) — Contains records of user accounts, transactions, and compliance details from VASPs. For Burn and Mint Transfers, such data:

- Reveals bridging or swapping of newly minted tokens shortly after burn events
- Indicates minimal-KYC or decentralized platforms enabling cross-chain re-minting
- Helps assess whether users are bypassing stricter compliance measures

By analyzing VASP data, investigators can trace layering or obfuscation attempts involving burn-and-mint schemes.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — Includes transaction logs, user activity metrics, wallet addresses, and device or IP data from non-custodial or minimal-KYC crypto service providers. This data:

- Details rapid conversions across different digital assets, revealing layering patterns.
- Captures user behaviors and potential multi-account usage to identify suspicious high-velocity transactions.

By leveraging VASP data, investigators can trace crypto swaps across multiple platforms, a common tactic in instant exchange-based laundering.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Captures exchange-level logs from virtual asset platforms, including detailed transaction records, user account details, order books, and compliance checks. This data enables investigators to trace how rug pull proceeds are converted or moved within various trading environments, linking wallet addresses to identifiable user accounts and uncovering laundering patterns.
- [Ransomware Payments](https://framework.amltrix.com/techniques/T0049.001) — Provides logs of digital asset transactions and user activity within cryptocurrency exchanges and other virtual asset service providers. This includes wallet addresses, user identities, trading volumes, deposit and withdrawal records, and associated account details. Such explicit data is crucial for tracing ransomware proceeds, detecting suspicious cross-exchange transfers, and potentially linking illicit wallets to real-world entities.
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Captures all customer wallets on file with regulated platforms, including whether they meet KYC standards.
- Helps confirm that certain external wallets remain outside custodial compliance, aligning with the 1591 indicator.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Records digital asset and related fiat deposits, withdrawals, and transaction details, including timestamps, amounts, and counterparties.
- Supports the detection of suspicious or high-volume transfers connected to remote mining, including payments for mining contracts and subsequent flows of newly generated cryptocurrency.
- [Cryptojacking](https://framework.amltrix.com/techniques/T0020.002) — - Includes exchange-level transaction logs, user account information, wallet addresses, and trading volumes.
- Helps trace suspicious conversions of newly mined cryptocurrency into fiat or other digital assets, supporting the detection of cryptojacking proceeds and related laundering activity.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Contains user account information, wallet addresses, transaction details, and trading activities within cryptocurrency exchanges.
- Highlights suspicious transfers to unregulated exchanges or mixers linked to sanctioned addresses, aiding in sanctions evasion investigations.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Includes exchange and wallet activity records, user identities, and transaction details from cryptocurrency platforms.
- Helps trace conversions of in-game currency to digital assets and vice versa, especially when assessing suspicious deposits or withdrawals tied to gaming accounts.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Contains logs of digital asset transactions, including wallet addresses, transaction timestamps, sender and receiver information, and amounts.
- Facilitates the detection of cryptocurrency flows used to receive or launder funds tied to child exploitation, enabling enhanced tracing of illicit proceeds across blockchain networks.
- [Privacy Wallets](https://framework.amltrix.com/techniques/T0034.001) — - Includes detailed records of customers’ digital asset transactions, wallet addresses, deposit and withdrawal logs, and associated account details maintained by VASPs.
- Helps investigators identify the use of privacy wallets, trace rapid or suspicious transfers, and correlate user activity with KYC information to detect layering and anonymity-enhancing behaviors.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Captures cryptocurrency transaction logs, wallet addresses, account details, and user activities on digital asset platforms.
- Enables tracing of crypto flows used to launder proceeds from sexual exploitation, identifying high-risk wallets and layering tactics.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Contains logs of digital asset transactions, including amounts, timestamps, wallet addresses, and user details, on centralized or decentralized platforms.

- Supports tracing the conversion of game currencies to cryptocurrency or fiat, where minimal KYC requirements may be exploited for laundering.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Contains transaction logs, user records, and trading activity related to cryptocurrency exchanges and other digital asset service providers. This data helps trace funds involved in fraudulent crypto investment offerings and identify patterns of rapid layering or sudden fund withdrawals.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Provides detailed logs of user accounts, deposit and withdrawal records, wallet addresses, and transaction volumes across both regulated and unregulated exchanges.
- Facilitates the detection of repetitive or unexplained transfers among multiple wallets, the identification of newly opened accounts with minimal prior activity, and the recognition of high-risk crypto-exchange usage for this technique.
- [NFT-based Value Obfuscation](https://framework.amltrix.com/techniques/T0064) — - Captures detailed trading and user account information from NFT marketplaces and cryptocurrency exchanges, including order histories, volumes, and price points.
- Enables detection of artificially inflated NFT sale prices, unusual trading spikes, and suspiciously coordinated transactions among multiple wallets or accounts.
- [Privacy Coins](https://framework.amltrix.com/techniques/T0116) — - Includes records on VASP licensing status, transaction logs, and KYC procedures for cryptocurrency exchanges and platforms.
- Aids in detecting reliance on unlicensed or poorly regulated platforms offering privacy coin trading with minimal or non-existent KYC checks, highlighting elevated risks of laundering activity.
- [Cross-Chain Bridges](https://framework.amltrix.com/techniques/T0005.002) — - Captures account creation details, KYC documentation, and transaction logs within VASP platforms, including cross-chain bridging transactions to and from user accounts.
- Enables investigators to detect suspicious bridging activity, such as rapid or unexplained changes in bridging frequency, usage of minimal-KYC bridging services, and potential layering via multiple blockchains.
- Verified identities and beneficial ownership details help attribute bridged funds and identify parties involved in cross-chain movements, supporting deeper AML investigations.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Captures detailed logs from cryptocurrency exchanges and other VASPs, including wallet addresses, transaction histories, and user activity.
- Enables reviewing user interactions with known custodial mixer addresses or identifying patterns indicative of layering and rapid turnover via mixer services.
- [Utility Tokens](https://framework.amltrix.com/techniques/T0067.005) — - Provides comprehensive records of digital asset transactions and user activities, including wallet addresses, deposit and withdrawal logs, and any available KYC checks maintained by VASPs.
- Enables detection of suspicious utility token usage, such as high-frequency trades, multiple bridging transactions across chains, and rapid token movements with no clear legitimate purpose.
- Supports identification of accounts lacking robust identification or repeatedly transferring large volumes of tokens that may indicate layering or illicit fund flows.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Provides user account information, transaction logs, and bridging activities across digital asset platforms.
- Helps link multiple wallets or accounts under the same user engaging in cross-asset transfers.
- Supports detection of unusual transaction volumes and rapid bridging frequently involved in transaction chaining.
- [Asset Valuation Manipulation](https://framework.amltrix.com/techniques/T0045) — Contains logs of digital asset and NFT transactions, including amounts, timestamps, wallet addresses, and trading parties. By analyzing patterns of repeated sales between related addresses at artificially high or low prices, investigators can detect wash trading or collusive price manipulation, which are common techniques used to distort digital asset valuations.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Contains logs of digital asset transactions, including wallet addresses, timestamps, amounts, and user account details. By comparing these records with fiat transaction logs, investigators can identify large or repeated cryptocurrency trades conducted via OTC desks with minimal KYC. This helps detect unregulated laundering channels and trace the flow of funds.
- [Virtual Token](https://framework.amltrix.com/techniques/T0067) — Provides detailed logs from centralized or semi-regulated cryptocurrency exchanges and other VASPs, including user account information, deposit and withdrawal records, trading histories, and KYC data. This helps link on-chain addresses to real customers when available, detect suspiciously frequent token conversions or bridging activities, and identify layering attempts across both decentralized and regulated platforms.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — Captures detailed transaction logs, wallet addresses, user identification records, and trading patterns from VASPs. This enables the detection of repeated small transactions, unusual address changes, and cross-exchange token flows indicative of potential layering or structuring.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Includes detailed logs of digital asset transactions, such as wallet addresses, transaction timestamps, and cryptocurrency-to-fiat conversions.  
- Reveals rapid liquidation of crypto proceeds to fund precursor chemical purchases.  
- Facilitates identification of abnormal or high-volume transactions lacking legitimate supporting documentation.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Consists of internal VASP records, including user profiles, wallet addresses, and transaction logs tied to crypto ATM usage.
- Provides additional context (e.g., linked accounts, velocity checks) not visible on public blockchains.
- Enables detection of multiple mules transacting through the same VASP-managed entity or wallet address, confirming organized layering activity.
- [Darknet Marketplace Transactions](https://framework.amltrix.com/techniques/T0100) — - Includes user account data, transaction logs, and trade activity on centralized or decentralized exchanges, covering amounts, counterparties, timestamps, and bridging or swap protocols.
- Identifies patterns of rapid transfers between different digital assets or blockchains without legitimate business purposes.
- Reveals layering attempts through decentralized exchange activities and cross-chain bridging specifically tied to Darknet marketplace proceeds.
- [Decentralized Mixers](https://framework.amltrix.com/techniques/T0003.002) — - Provides detailed logs of user and transaction data from regulated or semi-regulated exchanges.
- Enables tracing of funds as they move between decentralized mixers and VASP accounts, bridging on-chain activity with identifiable account holders.
- Assists investigators in linking suspicious on-chain mixer transactions to real-world user profiles maintained by VASPs.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Contains detailed logs of user activity on cryptocurrency exchanges and other VASPs, including deposit and withdrawal events.
- Helps identify the movement of newly minted coins into exchange wallets and subsequent conversions to fiat or other digital assets.
- Facilitates tracing suspicious flows if criminals attempt to disguise illicit proceeds via multiple VASP accounts.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Contains logs of digital asset transactions, including wallet addresses, timestamps, volumes, and counterparty information across cryptocurrency exchanges.
- Supports identifying micro-structuring through repeated low-value crypto transfers, which collectively mask larger laundering schemes.
- [DeFi Transactions](https://framework.amltrix.com/techniques/T0067.004) — Contains aggregator or exchange transaction logs, user account details, and usage patterns, allowing investigators to correlate wallet addresses, detect chain-hopping events, and link suspicious DeFi activity to identifiable user accounts where possible.
- [Governance Token Obfuscation](https://framework.amltrix.com/techniques/T0067.003) — Includes detailed logs from centralized or semi-decentralized exchanges and bridging platforms, capturing user account data, transaction details, and flows of governance tokens. This data helps investigators trace conversions, link user identities, and detect suspicious patterns when governance tokens are moved or swapped, complementing on-chain analysis.

---

## [Customs and Asset Seizure Records](https://framework.amltrix.com/data-sources/DS0015)

**Description:**
Official data on goods and financial assets seized by customs or enforcement authorities, including details about the items seized, parties involved, and any associated legal proceedings.

### Related Techniques
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Contains information on seized goods or financial assets related to customs violations or illicit trade.
- Enables financial institutions to uncover previously interdicted shipments or assets linked to suspected traffickers.
- Supports investigations by identifying repeated patterns of asset confiscations or associated parties.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — Official data on goods and financial assets seized by customs or enforcement authorities, including details about the items seized, seizure location, and the parties involved. This helps:

- Confirm direct ties to illicit tobacco shipments by linking seizures back to specific entities or transactions.
- Identify patterns of repeated smuggling activity or use of specific routes and carriers for illegal tobacco transport.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Details goods or assets seized by customs or enforcement authorities, including the parties involved and documented reasons for seizure.
- Identifies repeat offenders, networks, or methods linked to illicit arms smuggling, guiding further financial investigations and due diligence.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Documents items and financial assets seized by authorities, including wildlife products, timber, or proceeds from illegal environmental activities.
- Identifies arrested or flagged individuals/entities connected to environmental crimes.
- Links seizures to financial accounts or shipments for potential money laundering investigations.
- [Cross-Border Cash Smuggling](https://framework.amltrix.com/techniques/T0065) — - Document official seizures of undeclared or misdeclared currency at border points.
- Provide details on seized assets, involved individuals, and any subsequent legal actions.
- Enable investigators to match seized funds with suspected smuggling patterns or networks.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Documents items seized by customs or enforcement authorities, including wildlife products and derivatives.
- Provides details on parties involved and associated legal proceedings.
- Helps financial institutions detect connections between customers and seized assets or shipments.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Official documentation of goods and financial assets seized by customs or enforcement agencies.
- Highlights instances where large sums of undeclared currency are intercepted at borders.
- Assists investigations by revealing prior seizure incidents linked to individuals or networks consistently engaging in bulk cash smuggling.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Includes official records of seized shipments and assets, enabling the identification of known counterfeit pharmaceutical trafficking routes and the parties involved in illicit trade.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Details on goods, cash, and assets confiscated at borders or during law enforcement operations.
- Identifies parties involved in narcotics smuggling or laundering attempts and the nature of seized assets.
- Supports ongoing financial investigations by confirming links between seized assets and suspected drug-related transactions.

---

## [Legal Documentation & Records](https://framework.amltrix.com/data-sources/DS0016)

**Description:**
Collections of binding legal documents—including contracts, deeds, court orders, and judgments—used to verify legal rights, obligations, and relationships in financial dealings.

### Related Techniques
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Encompasses binding legal and regulatory documents, including court orders, recorded statements, and other official records.
- Allows financial institutions to track formal requests for transaction information, note any refusals citing immunity, and document legal steps taken against diplomatic or state-owned entities suspected of illicit activity.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Stores formal contracts, deeds, and legally binding documents validating asset transfers.
- Identifies missing or incomplete legal paperwork for high-value transactions.
- Highlights potential reliance on fictitious or backdated agreements to conceal true ownership changes.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Contains binding legal documents, corporate filings, contracts, and court records. When different segments or departments hold only partial legal paperwork, these records help demonstrate that no single entity has a comprehensive view of financial or operational arrangements.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — Provides official legal documents such as notarized deeds, court orders, and judgments. Cross-referencing these documents with submitted records helps detect forgery or fabrication, especially when criminals alter or counterfeit legal papers to legitimize financial transactions or misrepresent ownership and obligations.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Provides official legal documents, such as contracts, board resolutions, or court rulings, used in mergers or acquisitions. Key data points include:

- Authentic copies of share purchase agreements, asset purchase agreements, and related legal instruments.
- Signatory information, terms, and clauses that enable cross-verification of claimed M&A structures.

By examining these records, investigators can detect contradictions, incomplete provisions, or unusual terms indicative of a fictitious transaction.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Encompasses binding legal documents, including acquisition contracts, deeds, and corporate formation papers, revealing transaction terms, involved parties, and official approvals. This helps confirm legitimate purchase agreements or detect unusual clauses indicating potential laundering.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Consists of incorporation papers, contracts, court records, and other legally binding documents.
- Helps uncover discrepancies in ownership claims or shadow directors connected to sanctioned entities, emphasizing hidden beneficial owners.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Comprises formation documents, contracts, and trust deeds, detailing legal frameworks.
- Detects unusual or non-standard legal structures masking beneficial ownership.
- Supports cross-checking official corporate documents with actual operational control.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Official arbitration filings, settlement agreements, tribunal decisions, and other binding legal records.  
- Enables detection of fabricated or incomplete documentation, unusually rapid or collusive proceedings, and disproportionate settlement amounts—key indicators of arbitration settlement manipulation.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Includes official legal documents such as court orders, judgments, motions, appeals, and related filings.

How it supports AML detection:
- Validates the legitimacy of legal settlements and identifies unusual legal procedures or accelerated rulings.
- Detects repeated appeals against asset-freezing measures, suggesting deliberate tactics to shield illicit funds under the guise of legal processes.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Includes official powers of attorney, signatory authorizations, and other legal instruments. Enables the detection of broad or indefinite delegations of authority that may conceal a true beneficial owner behind a proxy.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Encompass contracts, amendments, and other legally binding agreements.
- Allow scrutiny of frequent or unusual changes in athlete image rights contract terms that facilitate repeated adjustments to payment amounts or ownership structures, indicating potential manipulation.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Include employment contracts, NDAs, and other formal documentation provided to recruits.
- Reveal clauses instructing recruits to use personal accounts for incoming funds without specifying legitimate business functions.
- Support investigations by highlighting unusual or vague contract terms associated with money mule activities.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Confirms the validity and chain of custody for bearer instruments through contracts, court filings, or related legal documents.
- Allows compliance teams to substantiate stated ownership and trace prior holders of the instruments.
- Reveals legal disputes or restrictions tied to bearer instruments, essential for comprehensive AML investigations.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Include official legislative documents, court filings, and regulatory rulings on budget allocations or financial misconduct.  
- Verify whether transfers or write-offs had legal authorization and note any resulting investigations or disciplinary measures taken against officials.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Comprises official documents such as insurance contracts and claim documentation. This data helps identify fraudulent claims, such as insuring phantom vessels, and detect fabricated or staged events used to legitimize illicit payouts in offshore insurance schemes.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Maintains validated court orders, official permits, and compliance filings, enabling confirmation of legitimate mining rights. This data source helps pinpoint entities operating without proper authorization or under fraudulent documentation.

---

## [KYC & Customer Due Diligence Records](https://framework.amltrix.com/data-sources/DS0039)

**Description:**
Comprehensive internal dataset containing verified customer identities, personal and business details, addresses, beneficial ownership information, account relationships, transaction summaries, risk metrics, financial statements, and business activity records.

### Related Techniques
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Consolidates verified identities, addresses, beneficial ownership information, and risk assessments.
- Helps detect shell or cover entities lacking verifiable operating history, confirming whether purported sellers or buyers are legitimate.
- [Asset Cloaking](https://framework.amltrix.com/techniques/T0009) — - Contains verified personal and business identity data, addresses, and beneficial ownership declarations.
- Enables cross-checking of customer-reported owners with external corporate registries to detect inconsistencies.
- Helps identify undisclosed controllers or suspicious layering that indicates asset cloaking.
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Maintains verified identities, beneficial ownership information, risk profiles, and customer backgrounds.
- Detects unusual trading activity by identifying customers with limited trading experience who suddenly engage in high-value transactions around key corporate announcements.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Contains customer-provided sector permits, certificates, and other compliance documents made available during onboarding or periodic reviews.
- Allows financial institutions to validate the consistency and authenticity of these specialized documents, detecting indications of forgery or tampering.
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Contains verified identification details, business profiles, and risk ratings of customers.
- Reveals inconsistencies between declared earnings or business activities and actual financial behavior.
- Helps detect accounts or beneficial owners with prior petty crime or gang affiliations, refining AML risk assessments for common offenses.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Contains verified individual and entity identities, official roles, beneficial ownership details, and account relationships.

This data enables financial institutions to detect discrepancies in declared diplomatic or state-owned entity accounts, verify the legitimacy of high-value transactions, and assess the risk profile of individuals claiming diplomatic immunity.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Includes verified customer identities, beneficial ownership data, stated account purposes, and transaction summaries.
- Allows comparison of actual micro-transaction patterns against declared financial profiles to spot inconsistencies indicative of micro-structuring.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — - Contains official customer details, including declared addresses or regions of operation.
- Enables direct comparison of reported locations against observed IP geolocation data from transaction and system logs.
- Facilitates detection of location inconsistencies indicative of proxied or obscured network access.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Contains verified customer information, including personal and business details, beneficial ownership, and transaction summaries.
- Supports detection of hidden controllers and suspicious relationships within networks perpetrating sexual exploitation, facilitating effective AML investigations and risk assessments.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Contains verified customer identities, business activities, risk profiles, and financial statements.

How it supports AML detection:
- Compares declared business activities and financial capacity with the scale or frequency of legal settlements.
- Flags inconsistencies between a customer’s known profile and large court-ordered payments, indicating potential abuse of court rulings to launder funds.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Consolidates verified customer identities, beneficial ownership structures, and compliance risk assessments.
- Reveals shell or recently formed companies lacking legitimate operations or credentials.
- Assists in verifying actual activity and raising red flags for suspicious contracting arrangements.
- [Financial Product Overfunding](https://framework.amltrix.com/techniques/T0086) — - Contains verified identity information, beneficial ownership details, and customer risk assessments.
- Reveals discrepancies between a customer's stated financial profile and actual behavior (e.g., repeated large deposits followed by immediate withdrawals).
- Helps verify the legitimacy of third-party payers who fund policies or accounts without documented relationships to the primary holder.
- Tracks changes in beneficiaries or beneficial owners, enabling detection of policy or account ownership shifts used to obscure true controllers.
- [Insurance Policy Overfunding](https://framework.amltrix.com/techniques/T0090.002) — - Provides verified personal and financial background details, enabling comparison of stated income or wealth against large or repeated insurance premium payments.
- Identifies beneficial owners or third-party payers to detect unrelated or suspicious funders with no legitimate link to the policyholder.
- Evaluates any discrepancies between declared financial status and actual overfunding or early redemptions, flagging potential money laundering activity.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Houses verified customer details and historical profile changes. Comparing recent updates, such as contact information or personal data, with imminent early withdrawal claims helps detect last-minute alterations that suggest fraudulent activity.
- [Cross-Chain Token Wrapping](https://framework.amltrix.com/techniques/T0067.002) — **Data Provided:**

- Verified customer identities, beneficial ownership information, declared accounts and wallets, business activities, risk profiles.

**How It Supports Detection/Investigation:**

- Enables verification of whether newly created or active wallets for wrapped token transactions are disclosed by the customer.
- Allows comparison of customer-stated business or investment purposes against complex cross-chain wrapping patterns.
- Aids in investigating discrepancies between declared customer profiles and observed asset flows.
- [Burn and Mint Transfers](https://framework.amltrix.com/techniques/T0005.001) — Contains verified customer identities, beneficial ownership data, and declared sources of funds or business rationale. For Burn and Mint Transfers, these records allow investigators to:

- Compare stated economic purposes with actual on-chain activity involving burn addresses.
- Identify discrepancies between customer-declared funds and large or repeated burn-and-mint transactions.
- Assess whether customers’ stated profiles align with abrupt changes in transactional behavior indicative of cross-chain layering.
- [DeFi Transactions](https://framework.amltrix.com/techniques/T0067.004) — Includes verified identity information, beneficial ownership data, and risk profiles. This enables financial institutions to link DeFi wallet addresses to known or unknown customers, identify self-custodial wallets lacking verification, and flag sudden suspicious activity on DeFi platforms.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Contains verified customer identities, financial profiles, risk metrics, and beneficial ownership details.
- Allows comparison of wire transfers with the customer’s stated financial capacity and expected activity to flag anomalies in layering schemes.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Contains verified identities, employment status, financial profiles, and beneficial ownership details.
- Helps detect inconsistencies between a customer’s declared income or business activity and suspicious cross-border cash-carrying patterns.
- Enhances risk assessment of individuals who may be facilitating cash courier activities.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Includes verified identities, addresses, beneficial ownership data, and customer risk metrics.
- Highlights discrepancies or incomplete information related to high-risk jurisdictions.
- Assists investigators in assessing whether offshore entities or addresses align with declared business operations, revealing potential secrecy exploitation.
- [Remittance Splitting](https://framework.amltrix.com/techniques/T0016.003) — - Consolidates verified customer identities, including personal details, risk profiles, and beneficial ownership data.
- Uncovers inconsistencies in identification documents or repeated usage of different identities by the same individual.
- Supports linking senders and beneficiaries to verify legitimate relationships and detect layering in remittance transactions.
- [Cross-Chain Bridges](https://framework.amltrix.com/techniques/T0005.002) — - Contains verified customer identities, ownership details, risk profiles, and declared financial backgrounds.
- Enables comparison of a customer’s stated wealth or transaction patterns against high-value or frequent cross-chain bridge transfers.
- Helps identify inconsistencies or anomalies in bridging activities that do not align with the customer’s known profile or expected financial behaviors.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Contains verified customer identity data, personal and business details, and relevant risk metrics.
- Helps confirm or refute legitimate employment documentation referenced in social media recruitment claims.
- Directly supports AML investigations by identifying inconsistencies between claimed job offers and actual customer profiles, a common red flag in mule recruitment.
- [Correspondent Banking](https://framework.amltrix.com/techniques/T0104) — Houses verified customer identities, beneficial ownership information, and ongoing due diligence data for respondent banks and their customers. This enables the correspondent bank to verify that newly onboarded accounts have been properly vetted, preventing criminals from exploiting incomplete or outdated KYC to launder funds through correspondent channels.
- [Cryptocurrency Mixing](https://framework.amltrix.com/techniques/T0003) — Stores verified customer identities, beneficial ownership data, and detailed account transaction histories. Investigators can correlate suspicious on-chain mixer usage with specific customer profiles, identify undisclosed sources of funds, and detect significant deviations from a customer's stated transaction patterns.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Identify any known relationships or affiliations between policyholders and beneficiaries.
- Verify the policyholder’s declared financial profile and investment objectives.
- Provide a chronological record of policy amendments and beneficiary changes.
- Document the origins of supplied funds and verify their legitimacy.
- Capture declared addresses, citizenship, or residency, highlighting high-risk jurisdictions.
- Assess the stated purpose and supporting documentation of annuity structures.
- Uncover beneficial owners or controlling interests behind all parties to the contract.
- Examine intermediary or broker backgrounds during annuity contract setup.

These records are crucial for verifying identities, tracking changes in ownership or beneficiaries, and detecting inconsistencies that indicate potential money laundering.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — - Contains verified identity and background information, including addresses, beneficial ownership, and risk assessments.
- Cross-references newly submitted details with established records to uncover discrepancies or fabricated credentials.
- Enables AML teams to detect remote identity theft or synthetic profiles by comparing claimed identities to known data.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Contain verified customer identities, beneficial ownership information, documented source of funds, and historical changes to customer risk profiles.
- Support detection of unauthorized or suspicious modifications to customer records, enabling identification of insider collusion in altering due diligence data.
- [Ponzi Schemes](https://framework.amltrix.com/techniques/T0144.019) — Contain verified customer identities, financial backgrounds, and source-of-funds documentation. Investigators can identify large or unexplained investments, discrepancies between declared income and actual contributions, and a lack of supporting documents—key red flags in Ponzi schemes.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Verify declared business activities and transaction volumes for agents and sub-agents, identifying inconsistencies with reported turnover.
- Confirm ownership, beneficial owners, and any undisclosed control relationships among agents or sub-agents.
- Compare inbound funds to stated sources and documented backgrounds, highlighting suspicious or undocumented inflows indicative of potential laundering.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Contains verified identity details, beneficial ownership, and customer background information.
- Supports detection of suspicious diamond transactions by checking if customers possess legitimate industry experience and a verifiable source of funds.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Contains verified identities, beneficial ownership data, and source-of-funds declarations for sponsors and related parties.
- Supports AML by confirming the legitimate backgrounds of sponsors and identifying discrepancies in declared origins of funds for sports sponsorships or betting accounts.
- [ATM Structuring](https://framework.amltrix.com/techniques/T0016.004) — - Contains verified customer profiles, declared sources of funds, and expected transaction behaviors, which can be compared against frequent sub-threshold ATM deposits.
- Enables identification of deviations from the customer’s financial profile, revealing red flags when ATM usage and deposit volumes exceed or contradict stated activity.
- Supports more thorough investigation of unusual account activity by linking customer risk assessments to emerging structuring indicators.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Verified identities, beneficial ownership data, high-risk jurisdiction flags, and due diligence files on sponsors or investors.  
- AML Use: Facilitates assessing the legitimacy of entities injecting funds into the club and identifying potential hidden relationships or shell structures that disguise illicit funding sources.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Contains verified identities, declared occupations, and risk parameters. This information helps identify sudden surges of new accounts opened by individuals with limited local or employment history and flags inconsistencies between stated background and actual transaction activity.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — - Contains verified details of customer financial profiles, address information, and the stated purpose for renting a deposit box.
- Enables institutions to assess the legitimacy of deposit box usage against customer income, business activities, and risk factors.
- Facilitates early detection of inconsistencies (e.g., no plausible reason for needing physical storage).
- [Informal Micro-Finance Schemes](https://framework.amltrix.com/techniques/T0096) — Contains verified identities, financial profiles, and ownership information, allowing analysts to spot individuals lacking legitimate income sources, identify proxy contributors, and confirm whether multiple group contributions align with a customer’s declared financial capacity.
- [Money Mule Exploitation](https://framework.amltrix.com/techniques/T0011) — - Contain verified identity documents, personal and address details, and beneficial ownership information.
- Reveal patterns of multiple new accounts opened by individuals with matching addresses, nationalities, or identical ID documents, consistent with money mule recruitment.
- Include declared source-of-wealth data that can be cross-checked against actual account activity to identify discrepancies indicative of mule exploitation.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Houses verified customer information, including beneficial ownership data and ongoing due diligence outcomes. Repeated failure to supply valid ownership records or reliance on digital documents alone can reveal virtual entities exploiting minimal disclosure requirements.
- [Chain Hop](https://framework.amltrix.com/techniques/T0005) — - Consolidates verified customer identities, beneficial ownership information, and account activity profiles.
- Detects newly created or multiple exchange accounts used to disperse assets across different blockchains and flags mismatches between declared business purposes and actual cross-chain activities.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Verified identity information, ownership details, and business profiles for individuals and entities associated with the investment company.
- Summaries of transaction activities, declared source of funds, and risk assessments.

These details reveal undisclosed or nominee owners, questionable ownership transfers, and inconsistencies in financial or background information—key indicators of potential laundering activities within private investment structures.
- [In-Person Gambling Imitation](https://framework.amltrix.com/techniques/T0107) — - Provides verified customer identities, personal and business details, and beneficial ownership information.
- Enables casinos and financial institutions to confirm whether a single individual controls multiple gambling accounts and to identify potential misuse of face-to-face ID checks.
- Assists in detecting high-risk or sanctioned customers who use minimal wagers and rapid chip redemptions under the guise of legitimate gambling.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Contains verified customer identities, historical transactional behaviors, and risk assessments.
- Helps detect sudden changes in cryptocurrency usage (e.g., new mixer transactions) or discrepancies between declared and actual wallet addresses, supporting investigations into suspicious mixer involvement.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Contains verified identity and beneficial ownership information, enabling the detection of hidden relationships or incomplete disclosures by intermediaries.
- Facilitates the validation of authorized signatories or proxies and cross-checking their stated roles.
- Supports jurisdiction-based risk assessments for intermediaries operating in high-risk or non-cooperative regions.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Includes verified identities, risk profiles, and beneficial ownership details maintained by financial institutions. By reviewing customer data linked to high-volume timber transactions, it helps detect clients lacking legitimate business rationale for large-scale proceeds.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Provides verified identifying details (e.g., names, addresses, beneficial owners), risk profiles, and documented relationships for customers and intermediaries.
- Helps detect potential ties to sanctioned individuals or front companies, allowing enhanced due diligence to pinpoint undisclosed connections or suspicious cross-border activities.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Contains verified identities, addresses, and beneficial ownership information.
- Facilitates detection of synthetic or falsified customer profiles used in fraudulent schemes.
- Supports ongoing monitoring of customer activity against stated business or personal backgrounds, revealing red flags if behavior diverges from legitimate profiles.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Contains verified personal and business information—such as identities, beneficial ownership, and risk profiles—collected during onboarding and ongoing due diligence. This data supports extortion-related AML efforts by:

- Verifying the legitimacy of sources behind large or recurring deposits that lack a clear business rationale.
- Identifying suspicious or opaque ownership arrangements indicative of front businesses used to commingle extorted proceeds.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Holds verified identity information, beneficial ownership data, and risk profiles, enabling scrutiny of account owners and transferees. These records help detect scenarios where multiple account or asset 'gifting' events exploit insufficient customer due diligence.
- [Underground Gambling](https://framework.amltrix.com/techniques/T0107.007) — - Contains validated customer identities, addresses, beneficial ownership details, and overall risk assessments.

- Helps confirm whether bettors are providing legitimate identification, detect incomplete or inconsistent ID details, and compare declared income against gambling activity levels to identify potential illicit fund placements.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Contains verified identities, customer backgrounds, beneficial ownership data, and due diligence risk findings. Reviewing these details enables financial institutions to detect forged or unverified documentation and identify suspicious account holders acquiring offshore prepaid cards or e-wallets.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Contains verified personal and business details, ownership information, and risk metrics.
- Aids in identifying suspicious accounts or relationships potentially used to funnel bribe payments or hide beneficiary details.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Contain verified identities, beneficial ownership details, and risk profiles of customers and counterparties.
- Help confirm the legitimacy of entities appearing in manipulated financial records, detecting potential fabricated or high-risk relationships that facilitate fictional revenues or expenses.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Contains verified customer identities, beneficial ownership information, addresses, and risk profiles.
- Helps identify individuals or entities with suspected ties to arms trafficking by verifying declared business activities, detecting links to sanctioned entities, or uncovering incomplete disclosures indicative of illicit arms dealings.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Contains verified customer identity data, personal and business details, and risk profiles. This information helps uncover accounts with incomplete or inconsistent identification, minimal verification, or transactional volumes misaligned with declared user profiles—key red flags when criminals exploit lax KYC in virtual environments.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Contains verified customer identities, beneficial ownership data, and stated business activities.
- Allows comparison of declared customer profiles against frequent or high-volume foreign exchange transactions.
- Supports detection of misaligned account activity, where currency swaps and cross-border fund transfers contradict stated business objectives.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Contains verified identities, addresses, beneficial ownership details, and risk assessments.
- Facilitates thorough examination of clients engaging in sectors with high environmental crime risk.
- Flags inconsistent or false documentation provided by shell entities or politically exposed persons involved in resource exploitation.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Contains verified customer information, including identities, beneficial ownership, and stated account purposes.
- Supports the detection of funnel accounts by comparing declared business activities against actual cross-border transaction patterns, exposing inconsistencies.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Contains verified customer identities, declared financial profiles, beneficial ownership details, and risk metrics.
- Facilitates comparison between a customer’s stated wealth or business activities and high-value asset purchases, aiding in the detection of transactions inconsistent with the customer’s legitimate profile.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Contains verified customer identities, addresses, beneficial ownership data, and risk profiles.
- Detects discrepancies in declared ownership or business purposes, indicating potential shell company usage.
- Aids in verifying the legitimacy of management and operational staff claims.
- [Real Estate Auction](https://framework.amltrix.com/techniques/T0108.001) — Comprehensive internal datasets containing verified customer identities, beneficial ownership information, risk assessments, and transaction profiles.

- Detects inconsistencies between buyer profiles and the scale of real estate acquisitions, identifying potential straw purchasers.
- Validates whether auction venues enforce due diligence protocols to collect beneficial ownership data, flagging those with inadequate checks that enable anonymity.
- [Anonymous Networking](https://framework.amltrix.com/techniques/T0015) — - Provides vetted customer identity details, declared addresses, and documented justifications for using anonymity tools.
- Enables detection of inconsistencies between customer-provided information and actual usage of anonymizing networks, supporting investigations into potentially concealed identities or illegitimate privacy claims.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Contains verified customer identities, stated business activities, and beneficial ownership information.
- Supports comparison of declared business or individual profiles against actual high-volume automated transactions, highlighting potential misalignment.
- Helps detect entities or individuals misusing automated systems inconsistent with their stated financial or operational background.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Includes verified customer identities, risk profiles, transaction histories, and account relationships.  
- Provides insight into customers with limited or no gaming background who engage in large-scale game item transactions, helping detect suspicious or fraudulent usage of in-game currencies.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Capture detailed identity and background information for project managers, beneficial owners, and key personnel, revealing inconsistencies or evasive explanations.
- Document financial profiles, declared sources of funds, and ownership structures to support deeper analysis of suspicious financing.
- Verify or challenge PEP status and high-risk attributes, especially when public officials award or invest in suspicious construction projects.
- [Darknet Marketplace Transactions](https://framework.amltrix.com/techniques/T0100) — - Includes verified personal and business details, risk profiles, and beneficial ownership information.
- Helps detect discrepancies between declared customer activities and actual high-volume or high-risk cryptocurrency transactions associated with darknet marketplaces.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Contains verified identity details, addresses, beneficial ownership information, and risk assessments collected during onboarding. This information highlights undisclosed or unverifiable project team members, a common red flag in rug pulls. Investigators can uncover incomplete or nonexistent background references, prompting heightened scrutiny of high-risk profiles.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Verified customer identities, beneficial ownership details, and business profiles related to arbitration participants.
- Supports examining whether claimants or beneficiaries have valid connections to the dispute, revealing newly formed or shell entities lacking legitimate operating history.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Includes verified customer identities, beneficial ownership details, source-of-funds information, and risk profiles. This data is essential for uncovering hidden owners behind offshore insurance policies and detecting discrepancies between declared customer profiles and actual premium payments or policy redemptions.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Contains verified identity details, declared occupations, financial profiles, and beneficial ownership information.
- Enables investigators to spot inconsistencies between a customer’s stated profile and actual account activity, such as unexplained receipt or transfer of funds.
- Flags incomplete, contradictory, or vague transaction purposes cited by individuals who may be unwitting mules in romance scams.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Contains verified identities, addresses, beneficial ownership structures, and income details. For corruption investigations, these records confirm potential PEP status, declared sources of wealth, and highlight inconsistencies suggesting embezzlement or abuse of office.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Contains verified customer details, asset declarations, and insurance coverage data.
- By examining ongoing updates to jewelry valuations or appraisals, analysts can detect inconsistencies or repeated changes lacking credible justification, revealing potential laundering.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Holds verified customer identities, business profiles, and risk assessments. Investigators can identify entities or individuals lacking legitimate experience in commodity trading, which raises suspicion of involvement in smuggling networks.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Provides comprehensive customer profiles, including stated income or business models, beneficial ownership details, and typical transaction behaviors. Comparing remote deposit capture volumes and check issuers against these records helps detect unexplained deposit activity and anomalies.
- [Cryptojacking](https://framework.amltrix.com/techniques/T0020.002) — Contains verified customer identities, beneficial ownership data, business activity information, and risk assessments. These records enable the detection of potential cybersecurity weaknesses and discrepancies between declared activity and funds stemming from illicit cryptomining, facilitating more accurate AML investigations into cryptojacking proceeds.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Provides verified identities and business profiles of customers, along with beneficial ownership details, normal trade patterns, and risk classifications. This data helps investigators:

- Identify unusual countertrade deals or goods that deviate from the customer’s usual scope.
- Verify that parties involved in the exchange have legitimate capacities to conduct the specified trade.
- Detect shell entities or suspicious intermediaries lacking transparent ownership.
- [Geographically Dispersed Cash Deposit](https://framework.amltrix.com/techniques/T0053) — - Provides verified customer identities, addresses, and beneficial ownership details.  
- Allows comparison of declared residence or business locations against actual deposit locations to spot inconsistencies.  
- Identifies potential collusion among multiple depositors linked by overlapping personal identifiers or contact information, indicating coordinated smurfing.
- [Third-Party Payments](https://framework.amltrix.com/techniques/T0073) — Contains verified information on customer identities, beneficial ownership, and documented risk assessments. By cross-referencing depositors’ identities with these records, institutions can detect incomplete or inconsistent details provided by third-party depositors, revealing hidden ownership or suspicious funding sources.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — - Contains verified customer identities, beneficial ownership information, and supporting documentation on client business activities.
- Helps confirm the legitimacy of purported lobbying entities or donors.
- Identifies shell companies and clarifies organizational structures, detecting anomalies in fundraising or campaign donation channels.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Verified customer identity data, addresses, and risk profiles indicate whether an individual using a crypto ATM underwent adequate due diligence. This helps uncover accounts with minimal identification, detect potential exploitation of weak KYC controls, and inform further AML investigations.
- [Ransomware Payments](https://framework.amltrix.com/techniques/T0049.001) — - Contains verified customer identities, beneficial ownership information, and documented wallet addresses.
- Helps identify newly created or unregistered cryptocurrency wallets by comparing them against a customer’s established profile.
- Supports investigations by corroborating suspicious wallet activity with known customer attributes to uncover undisclosed connections to ransomware proceeds.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Contains verified identities, ownership details, and risk assessments for borrowers, co-lenders, and intermediaries.
- Helps detect undisclosed conflicts of interest, repeated reliance on a single lead arranger’s KYC checks, and overlapping beneficial ownership structures that facilitate syndicated loan fraud.
- [Governance Token Obfuscation](https://framework.amltrix.com/techniques/T0067.003) — Contains verified customer identities, beneficial ownership information, and historical activity profiles. Investigators can:

- Detect sudden or unexplained governance token activity among users with minimal or no prior DeFi involvement.
- Identify mismatches between declared risk profiles and high-volume or complex token swaps.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Provides verified identities, beneficial ownership details, addresses, and risk metrics for individuals or corporations across multiple jurisdictions.
- Helps confirm the identities of sub-agents or authorized signers, detect unusual changes in signatories, and ensure consistency with declared beneficial owners.
- Supports AML investigations by revealing undisclosed connections or hidden relationships across different jurisdictions.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Contains verified customer identities, stated employment details, and risk levels.
- Enables cross-checking of supposedly legitimate job offers or employers cited by customers.
- Detects discrepancies or incomplete information indicative of phishing-based mule recruitment.
- [Payroll Deduction Loan Repayment](https://framework.amltrix.com/techniques/T0029) — - Contains verified customer identities, declared salary and employer information, and overall financial profiles.
- Allows validation of payroll deduction amounts against actual income levels and employer data to uncover fraudulent or excessive repayments.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Consolidate verified customer data, ownership structures, and declared payroll figures.
- Cross-check official payroll information with actual wage outflows to highlight discrepancies, revealing off-the-books transactions.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Contains verified identities, declared sources of wealth, beneficial ownership, and account relationships.
- Identifies discrepancies between the customer's documented profile and high-value precious commodity transactions, supporting the detection of potential smuggling activities.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Contains verified customer identities, beneficial ownership details, and stated business activities.
- Helps confirm whether the volume and nature of invoiced trade transactions align with the customer's known profile and legitimate operations.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Central repository of verified customer identities, beneficial ownership details, wealth sources, and risk assessments.
- Flags missing or incomplete documentation for high-value junket transactions, ensuring deeper scrutiny of VIP clients and beneficial owners.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Provides verified details on beneficial owners, personal and business information, signatories, risk metrics, and historical changes. In the context of beneficial ownership manipulation, these records help identify unusual or frequent changes in controlling interests, detect nominee owners, and confirm whether declared owners match official or transactional records.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Identify and verify beneficial owners, shareholders, and controllers of the captive insurer.
- Flag owners lacking relevant insurance expertise, high-risk profiles, or frequent changes in controlling parties, which may indicate possible shell structures or hidden ownership.
- [Cooperative or Mutual Institution Deposits](https://framework.amltrix.com/techniques/T0120) — - Contains verified identity details, beneficial ownership information, and risk profiles for members.
- Supports identifying under-documented individuals rapidly depositing large sums.
- Facilitates verification of declared sources of wealth, uncovering infiltration by high-risk or unqualified individuals.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Contains verified customer and beneficial ownership data, declared business activities, and official identification.
- Allows comparison of stated mining capacity or energy usage against the actual scale of hardware purchases and mining rewards.
- Enables validation of a customer’s legitimacy for conducting cryptocurrency mining activities.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Store verified customer identity details, including documents and addresses, to confirm legitimate identity or flag mismatches.
- Document historical changes or repeated anomalies to expose potential impersonation patterns across multiple accounts.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Contains verified customer identities, addresses, beneficial ownership details, risk assessments, and evidence of the source of funds.
- Supports identification of incomplete or inconsistent documentation regarding capital injections for CBI/RBI and highlights reluctance to provide comprehensive financial records.
- [NFT-based Value Obfuscation](https://framework.amltrix.com/techniques/T0064) — - Contains verified customer identities, beneficial ownership, and risk profiles of individuals operating NFT-related accounts.
- Helps confirm or reveal discrepancies in reported ownership details for blockchain wallets, facilitating the linkage of pseudonymous NFT transactions to actual persons or entities.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Contains verified identities, beneficial ownership data, and customer financial profiles. By examining investor backgrounds and sources of funds, institutions can detect suspicious or undisclosed beneficial owners injecting illicit capital under the guise of legitimate investment.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Provides verified identities, beneficial ownership details, and address information for entities established in free trade zones.
- Enables detection of shell or non-operational companies by verifying declared business activities, physical premises, and source of funds.
- Supports ongoing monitoring to identify unverified ownership changes in FTZ entities.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Contains verified information on customers and beneficial owners, including identity data, ownership structures, risk profiles, and source-of-funds documentation. Investigators can confirm whether the individuals behind new or multiple corporate acquisitions are genuinely identified and assess mismatches in declared backgrounds or funding sources.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Contains verified identities, beneficial ownership, addresses, and account relationships. This data is crucial for detecting newly created or unverifiable online accounts, frequent or rapid changes in customer details, and mismatched identity information, all of which indicate potential fraudulent e-commerce activities.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Contain verified customer identities, beneficial ownership details, and documented business profiles.
- Facilitate verifying a customer's claimed involvement in remote mining and identifying discrepancies, such as inadequate industry knowledge or contradictory background details.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Documents verified customer identities, beneficial ownership data, and relationships among accounts.
- Reveals connections between traders who may appear unrelated but share common ownership or affiliations.
- Aids in identifying collusion and repeated trading among accounts linked to the same individuals or entities.
- [Privacy Coins](https://framework.amltrix.com/techniques/T0116) — - Contains verified customer data, including identities, beneficial owners, and account relationships.
- Helps identify cases where multiple accounts controlled by the same individual or entity funnel funds into privacy coin wallets without a clear business rationale, flagging potential layering or structuring across multiple accounts.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Contains verified customer identities, beneficial ownership details, and account relationships.
- Enables linking of multiple accounts or entities controlled by the same individual, which is vital in identifying rapid account openings or closures used in Transaction Chaining.
- Assists in revealing suspicious patterns where a single customer repeatedly opens accounts in different jurisdictions without clear business rationale.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Contains verified details of customers, including beneficial ownership, declared business activities, and investment backgrounds.
- Helps identify potential mismatches between a customer’s stated knowledge of carbon credit markets and their significant investment behaviors, indicating possible money laundering or misuse of accounts.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Contains verified identities, addresses, and beneficial ownership details for individuals and entities.
- Helps detect nominee directors or layering tactics across different jurisdictions.
- Comparing declared ownership against registry data can expose inconsistencies indicative of multi-jurisdiction laundering schemes.
- [Onion over VPN](https://framework.amltrix.com/techniques/T0015.005) — - Contains customer identity and declared location details, correlating official user information with observed system access.
- Facilitates discrepancy analysis between stated residency and the IP geolocation from which transactions/logins originate.
- Supports detecting location mismatches indicative of Onion over VPN usage, aiding AML investigations.
- [Negotiable Instrument Purchases](https://framework.amltrix.com/techniques/T0110) — - Contains verified customer information, beneficial ownership data, and documented source-of-funds details.
- Identifies repeated refusals or gaps in source-of-funds documentation, aiding in the detection of suspicious negotiable instrument purchases and deposits.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Contain verified identity details and risk profiles for high-value or frequent gambling customers.
- Highlight incomplete or missing KYC documentation, revealing offshore gambling operators that fail to perform robust customer due diligence.

These records support AML detection by uncovering accounts lacking proper verification or risk controls, which can be exploited for laundering through offshore gambling services.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Encompasses verified identity details, beneficial ownership data, and customer risk profiles.
- Monitors changes in personal or tax identification data tied to repeated refund claims.
- Aids in detecting deliberate identity manipulation to secure fraudulent tax rebates.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Contains verified customer identities, financial profiles, and supporting documentation.
- Enables investigators to confirm if declared sums match the customer’s legitimate sources of funds.
- Helps identify potential discrepancies in declared reasons for cross-border cash movements versus actual business or personal profiles.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Encompasses verified identities, beneficial ownership details, and information regarding customers’ high-value assets or transactions. Highlights instances where clients are unwilling to disclose the nature or valuation of assets for freeport storage, prompting deeper scrutiny into potential illicit use.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Contains verified information on donors, payers, beneficial owners, and controlling parties of the nonprofit institution.
- Supports validation of legitimate affiliations, revealing suspicious or unverified donors and owners who may be exploiting the institution’s nonprofit status for laundering.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Contains verified identity information, risk profiles, and compliance checks for customers.
- Helps identify incomplete or inconsistent documentation among individuals managing dubious fundraising campaigns with minimal verification, flagging potential fraud.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Contains verified customer identities, beneficial ownership details, and risk profiles.
- Allows verification of inconsistent or incomplete documentation, especially when customers claim legitimate business while concealing proceeds from forced labor or sexual exploitation.
- Supports detection of atypical or unexplained changes in customer information and account activities.
- [Electronic Gaming Machine Ticket Redemption](https://framework.amltrix.com/techniques/T0054) — Provides verified customer identity details, beneficial ownership information, and relationship mappings. This data helps identify whether individuals exchanging or consolidating TITO vouchers are legitimately connected or part of collusive activity, enabling enhanced scrutiny of unusual or unexplained voucher transfers.
- [Virtual IBANs](https://framework.amltrix.com/techniques/T0027) — - Contains verified customer information, including beneficial owners, business activities, and account relationships.
- Enables validation of legitimate business purposes for virtual IBAN usage and identification of suspicious discrepancies in declared activities versus actual fund movements.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Maintains verified customer profiles, beneficial ownership details, and expected transaction behaviors, enabling comparison of stated business purposes against actual multi-currency swap activities. Discrepancies can indicate high-risk layering and misuse of customer accounts.
- [Dividend Stripping](https://framework.amltrix.com/techniques/T0147.003) — Includes verified customer identities, beneficial ownership details, and account relationships. These records help detect sudden or repeated changes in declared beneficial owners around dividend dates, indicating potential collusion or attempts to obscure rightful ownership.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Aggregates verified customer profiles, including financial standing, business activities, and risk assessments. Specifically relevant for:

- Identifying customers newly or unexpectedly engaged in high-value precious metals or gemstone trading.
- Comparing declared sources of wealth or business profiles against actual commodity trading volumes.
- Exposing sudden or unexplained escalation in trading activity that may suggest money laundering.
- [Cash Deposits](https://framework.amltrix.com/techniques/T0004) — - Contains declared income, source of funds, beneficial ownership information, and overall risk profile of customers.
- Facilitates comparison of stated financial capacity against large or frequent cash deposits, flagging potential inconsistencies.
- Provides essential background to investigate the legitimacy of deposit activity and identify hidden relationships or beneficial owners.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Contains verified customer identities, beneficial ownership information, and account relationships.
- Enables detection of rapid ownership changes, frequent entity acquisitions, or expansions lacking operational legitimacy that facilitate circular flows.
- [Crowdfunding Campaign Manipulation](https://framework.amltrix.com/techniques/T0044) — - Includes verified identity information, addresses, beneficial ownership data, and risk profiles.
- Facilitates the verification of beneficiary or project owner credentials to identify inconsistencies or unverifiable individuals.
- Helps expose sham campaigns or questionable parties lacking proper documentation.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Contain originally verified customer financial documents and identity details. Investigators compare newly submitted or altered documents with stored originals to uncover inconsistencies or evidence of digital record manipulation.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Contains verified identity, ownership, and beneficial ownership data for customers and entities.
- Identifies shell or front companies operating in multiple jurisdictions with questionable business rationale.
- Supports evaluating newly formed or high-risk entities involved in suspicious letters-of-credit transactions.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Verified customer identities, ownership and control structures, addresses, transaction histories, risk ratings, and financial statements.

- Direct AML Relevance: Enables institutions to identify undisclosed beneficial owners or high-risk customers engaged in cross-border trade that may conceal illicit proceeds via Black Market Peso Exchange networks.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Contains verified customer identities, business details, beneficial ownership information, and risk profiles.
- Highlights gaps or inconsistencies in customer onboarding and monitoring, such as employees creating accounts on behalf of multiple unrelated clients or bypassing KYC checks.
- Assists AML teams in detecting MSB staff collusion and subversion of internal controls used to hide beneficial owners or high-risk relationships.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Includes verified customer identities, addresses, and beneficial ownership details.
- Enables detection of overlapping beneficial owners, suspiciously shared corporate addresses, or unexplained ownership changes.
- Facilitates cross-checking patrons, revealing potential shell or front companies hidden within corporate structures.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Contains verified identities, beneficial ownership details, account relationships, and risk profiles. These records help detect intermediaries with limited or inconsistent documentation who repeatedly appear in NEP transactions and assess whether customers have legitimate backgrounds or risk indicators.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Holds verified customer identities, beneficial ownership details, expected transaction patterns, and risk profiles. These records are critical for uncovering discrepancies in declared income versus invested amounts, unexplained changes in investor profiles, or layered ownership structures used to obscure the ultimate source of funds.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Contains verified customer identities, beneficial ownership structures, and due diligence findings. This data helps investigators identify newly introduced or dormant entities, nominal stakeholders with no legitimate business roles, or investors from high-risk backgrounds linked to the enterprise.
- [Asset Valuation Manipulation](https://framework.amltrix.com/techniques/T0045) — Encompasses verified customer information, including personal and business details, financial statements, and documentation of asset purchases or appraisals. This data enables the verification of legitimate valuations by confirming the existence of independent appraisals and identifying missing or forged documentation, which is critical for detecting manipulated valuations.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Contains verified identity and beneficial ownership details, financial profiles, and transaction summaries for individuals and entities.
- Highlights discrepancies between a customer’s known financial capacity and continued high-value auction activity.
- Aids AML investigations by flagging participants whose actual wealth may not justify large or frequent auction transactions.
- [All-Cash Real Estate Transactions](https://framework.amltrix.com/techniques/T0010.005) — Contains verified identification details, beneficial ownership data, source-of-funds documentation, and records of requests for additional information. This data helps validate the legitimacy of high-value cash real estate buyers, flag incomplete disclosures, and detect refusals to provide proof of funds.
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Contains verified identity details, declared occupations, business and ownership information, and documentation gathered during onboarding or ongoing monitoring. This data:

- Verifies the legitimacy and registration status of businesses or individuals claiming informal operations.
- Identifies missing or refused documentation, possibly indicating an attempt to conceal true earnings.
- Checks stated occupation or expected income range against observed transaction flows to detect underreporting.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Stores verified details on beneficial owners, authorized persons, and overall customer profiles. Facilitates the comparison of listed signatories with actual transaction initiators to uncover inconsistencies or mismatches indicative of proxy arrangements.
- [High-Denomination Currency Transport](https://framework.amltrix.com/techniques/T0065.002) — Contains verified identity details, expected cash usage profiles, and beneficial ownership information. Comparing declared usage against actual requests for or deposits of high-value currency helps identify suspicious inconsistencies tied to cross-border note transport.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Contains verified identification documents, personal and business details, and beneficial ownership information.
- Allows cross-checking user profiles across multiple remittance apps or crypto platforms, uncovering inconsistent or fabricated credentials.
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — - Contains verified identity and beneficial ownership information, account relationships, and risk metrics.
- Highlights incomplete or missing beneficial ownership details when professionals invoke confidentiality.
- Monitors frequent changes in professional intermediaries and refusal or delay in disclosures, revealing potential abuse of privileged accounts.
- [Mobile Payment Systems](https://framework.amltrix.com/techniques/T0134.002) — Contains verified identity and beneficial ownership data for mobile payment account holders, ensuring the authenticity of provided credentials and detecting falsified or stolen identities that facilitate illicit layering or cross-border transfers.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Contain verified customer identities, financial profiles, and source-of-funds documentation. For lottery schemes, these records:

- Help confirm or refute claimed sources of wealth or gambling finances.
- Uncover inconsistencies between declared income and high-value lottery spending.
- Identify third-party claimants lacking legitimate ties to winnings.
- [Unlicensed Real Estate Brokerage](https://framework.amltrix.com/techniques/T0133) — Includes verified customer identity data, beneficial ownership details, and collected AML documentation. This resource highlights instances when real estate transactions proceed without standard due diligence, enabling the detection of deals undertaken by unlicensed brokers lacking proper KYC checks.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Contains verified identities, professional qualifications, risk ratings, and transaction summaries for customers.
- Helps confirm if purported timeshare brokers or attorneys have legitimate credentials and business histories.
- Facilitates detection of inconsistencies between fee-based inflows and the customer’s stated services.
- [Match-Fixing](https://framework.amltrix.com/techniques/T0107.005) — - Contains verified identities, addresses, beneficial ownership data, and risk profiles for each customer.
- Facilitates the detection of multiple accounts with inconsistent or missing KYC details linked to match-fixing schemes.
- Assists in verifying customer legitimacy and uncovering potentially collusive or fraudulent account registrations.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Contain verified customer identities, beneficial ownership structures, risk profiles, and financial statements.
- Help identify accounts controlled by the same individuals or entities, even when using nominee investors.
- Uncover misalignments between declared wealth and actual investment activity in capital markets.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Contains verified customer identities, beneficial ownership details, and risk profiles, supporting the identification of shell companies or counterparties lacking legitimate business activities. This data helps reveal discrepancies in the stated business purpose for Bill of Exchange usage.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Contains identity documents, beneficial ownership information, transaction profiles, and risk assessments for customers and entities.
- Helps confirm whether purported call-center owners or operators are accurately represented and meet due diligence requirements, uncovering overlooked associations or control persons.
- [Decentralized Mixers](https://framework.amltrix.com/techniques/T0003.002) — - Contains verified identity data (e.g., names, addresses, beneficial owners, risk profiles) for customers.
- Enables investigators to identify customers with incomplete or suspicious KYC profiles who transact with decentralized mixers.
- Assists in tracing real-world identities behind wallet addresses linked to mixer activity, highlighting potential illicit use.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Aggregates customer identity, financial, and risk profiling details, including declared income and business activity.
- Helps identify customers engaging in frequent real estate flips or high-value transactions through escrow that exceed their known financial profiles.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Stores verified customer identity details, addresses, and transactional risk profiles.
- Facilitates the detection of suspicious account behavior tied to advance fee fraud, such as sudden changes in contact information or inconsistent explanations for frequent incoming 'advance fee' payments.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Contains verified customer and entity information, including ultimate beneficial owners, organizational structures, and risk profiles.
- Enables enhanced due diligence on complex or layered agribusiness setups by confirming declared owners and cross-checking any undisclosed controllers.
- Helps uncover high-risk relationships or secrecy-jurisdiction incorporations that obscure real ownership.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Contains verified customer identification details, beneficial ownership information, historical account relationships, and risk profiles.
- Facilitates comparison between declared customer financial circumstances and extensive foreign property transactions.
- Supports enhanced due diligence to uncover suspicious or unverified ownership structures in cross-border real estate deals.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Contains verified customer identities, business details, beneficial ownership information, and comprehensive risk assessments.
- Includes documentation (or lack thereof) on formal agreements and relationships.

This information helps identify customers conducting trust-based transactions without formal contracts, a common red flag in Hot Transfers where documentation is minimized.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Contains verified identities, ownership details, and due diligence findings for customers and businesses. 

- Identifies abrupt or coerced changes in ownership or management.
- Flags high-risk associations with organized crime and unexplained cash transactions indicative of extortion.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — Maintains verified customer identities, beneficial ownership details, and risk profiles, facilitating the comparison of disclosed consulting operations versus actual activities. This helps identify front entities, low-substance operations, or conflicting ownership information central to fictitious consulting schemes.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Includes verified customer identities, financial statements, and risk metrics.
- Enables comparison of declared financial profiles with large or frequent currency conversions.
- Assists in detecting cumulative activity that exceeds normal client expectations or risk parameters.
- [Casino Mule Networks](https://framework.amltrix.com/techniques/T0011.003) — - Provides verified identity details, declared income sources, and financial backgrounds of casino patrons.
- Enables detection of discrepancies between claimed financial capacity and actual transaction sizes, helping identify potential mules or unexplained wealth in the casino environment.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Contains verified personal details, identity documents, and beneficial ownership information.
- Enables detection of repeated or overlapping data points (e.g., addresses, phone numbers) across accounts, alerts on frequent or unexplained changes to customer profiles, and supports verification of authenticity for new account applications.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Verified personal and business information, including identification details and ownership data.
- AML Relevance: Checks the authenticity of alleged employees’ identities and the legitimacy of their association with the business.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Contains verified identity details, beneficial ownership information, and source-of-funds data for policyholders and premium payers.
- Exposes unexplained third-party relationships or financing, supporting the detection of opaque ownership structures and suspicious early policy surrenders.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Contain verified identities, beneficial ownership details, and risk assessments of both clients and professional intermediaries. This enables investigators to confirm stated credentials, identify hidden stakeholders, and detect incomplete or misleading disclosures that may conceal illicit financial activities.
- [Privacy Wallets](https://framework.amltrix.com/techniques/T0034.001) — - Contains verified identities, risk profiles, stated business activities, and transaction histories.
- Reveals when privacy wallet transactions deviate from a customer’s typical profile or stated purpose, indicating potentially unjustified anonymity-seeking behavior.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — KYC & CDD records provide verified customer identity information, including:

- Official personal details such as names, addresses, and identification documents.
- Historical changes to customer addresses and contact information.

Access to accurate identity data helps pinpoint inconsistent or fraudulent information supplied during chargeback disputes and detect stolen or synthetic identities used in collusive chargeback schemes.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Contains verified identification, beneficial ownership details, and customer risk profiles. Reviewing these records helps confirm whether multiple accounts executing mirrored trades share the same or concealed controlling parties, exposing layering schemes that shift value with minimal oversight.
- [Virtual Token](https://framework.amltrix.com/techniques/T0067) — - Includes verified identity data, beneficial ownership details, and risk assessments for customers.
- Allows comparison of declared wallet addresses and source of funds against actual usage.
- Identifies potential mismatches, undisclosed addresses, or suspicious multi-wallet patterns that may indicate layered token transactions.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Includes verified identities, onboarding notes, and documented justifications for account activities. For knowledge compartmentalization, these records can expose inconsistencies or gaps where individuals or departments have incomplete or fragmented knowledge of broader business operations.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Houses verified customer profiles, beneficial ownership data, and ongoing due diligence updates, enabling the detection of high-risk or frequently changing suppliers and beneficiaries in counterfeit pharmaceutical schemes.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Contains verified identities, ownership details, and client interactions, allowing analysts to identify unusual reliance on bearer instruments.
- Enables financial institutions to verify or challenge the authenticity of declared ownership over bearer certificates and detect refusal to provide sufficient beneficial ownership information.
- Supports tracking changes in customer profiles that may indicate evasive or anonymous behavior consistent with bearer instrument misuse.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Holds verified identities, beneficial ownership, risk profiles, and supporting documentation for borrowers and lenders.
- Identifies shell entities or undisclosed high-risk associations and uncovers changes in customer details post-loan approval.
- Cross-checks declared financial or business information to spot inconsistencies or omissions indicative of loan fraud.
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Contains verified customer identities, beneficial ownership details, and stated investment objectives or rationales.
- Identifies incomplete or inconsistent beneficial ownership documentation, repeated refusals to provide the source of funds, and discrepancies in declared investment purposes—key AML red flags for cross-border asset management accounts.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Encompasses verified identification details, beneficial ownership data, risk assessments, and financial disclosures.
- Enables detection of customers with unverifiable or inconsistent sources of funds for gold purchases, reflecting inadequate or bypassed due diligence.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Holds verified identity, employment, and personal information. Cross-referencing these details with claimed unemployment eligibility helps detect discrepancies such as mismatched work history, questionable residential addresses, or incomplete personal details, which may indicate stolen or synthetic identities.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Contain verified customer identities, beneficial ownership details, and transaction histories.
- Facilitate the detection of customers with no legitimate involvement in the diamond sector or whose transaction patterns contradict their stated business activities.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Encompasses verified customer profiles, beneficial ownership data, risk assessments, and AML compliance actions. This data helps detect infiltration when:

- A bank experiences disproportionate growth in high-risk customers or sectors post-acquisition.
- Large capital infusions occur from undocumented or opaque sources.
- Enhanced due diligence is bypassed for high-value clients.
- Suspicious transaction reporting declines abruptly after leadership changes.

These patterns may indicate that criminals in control are circumventing or disabling compliance safeguards.
- [Metaverse-based Asset Transfers](https://framework.amltrix.com/techniques/T0066.001) — - Includes verified customer identities, declared sources of wealth, and account background information.
- Enables detection of mismatches between stated financial profiles and high-volume or complex metaverse-based transactions.
- Flags newly onboarded accounts lacking rigorous CDD or showing sudden spikes in metaverse asset trading activity.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Houses comprehensive identity and business information, including beneficial ownership details, risk assessments, and historical activity. Enables the detection of fictitious or inconsistent customer profiles, which are often exploited by hawala operators for untraceable fund flows.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Encompasses verified customer identity documents, risk assessments, ownership structures, and related due diligence findings. These records help detect uncooperative entities, confirm investor identities, and identify high-risk customers or suspicious requests for secrecy in fraudulent investment setups.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Capture verified identity, stated occupation, and expected account usage.
- Enable detection of inconsistencies between the customer’s declared employment and actual financial activities.
- Document explanations (or lack thereof) for incoming funds and changes in personal information coinciding with suspicious transactions.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — Encompasses verified customer identities, beneficial ownership details, wallet addresses, transaction summaries, and risk assessments. This supports the detection of inconsistencies in source-of-funds declarations and helps identify frequent wallet address changes that may signal attempts to evade AML controls in payment token activities.
- [Insurance Beneficiary Substitution](https://framework.amltrix.com/techniques/T0089) — - Contains verified identity details, beneficial ownership information, and risk ratings for policyholders and beneficiaries.
- Allows investigators to confirm or refute legitimate relationships among policy participants and to identify repeated, unjustified substitutions of policyholders or beneficiaries, indicating potential layering attempts.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Provides verified customer identities, risk profiles, declared income, and due diligence outcomes. This data helps detect inconsistencies between reported financial capacity and wagering volumes, and identifies staff failures or overrides in collecting or verifying required customer information for high-value bettors.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Contains verified identification details, proof-of-funds documents, and account ownership information.
- Monitors changes in customer profiles and verifies the legitimacy of funds used for crypto investments in unregulated platforms.
- Enables enhanced reviews when inconsistent or updated customer data signals potential fraud or scam involvement.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Includes verified customer identities, ownership structures, risk assessments, and declared business activities. This data:

• Validates the authenticity and legitimacy of customers involved in offshore transfers.
• Identifies undisclosed beneficial owners or contradictory ownership claims.
• Supports enhanced scrutiny of high-risk offshore transactions that deviate from declared business profiles.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Includes documented customer identities, beneficial ownership information, and source-of-funds details, as required by AML regulations.
- Detects the absence or insufficiency of KYC procedures often associated with unlicensed MSBs looking to remain hidden.
- Highlights incomplete CDD, pointing to potential illicit operations.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Provides verified customer identities, prior trade engagements, and risk profiles. By reviewing a customer’s historical involvement in trade finance and matching it against newly issued red/green clause letters of credit, institutions can detect anomalies such as sudden or unjustified usage of advanced credit facilities.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — Contains verified customer identities, personal and business details, beneficial ownership information, and due diligence interviews. This data is essential for assessing the legitimacy of a client’s cross-border banking relationships and identifying inconsistencies or unusual justifications for multiple international banks in a single payment sequence.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Contains verified identity details, business registration documents, addresses, and beneficial ownership information.
- Enables thorough cross-checking of vendor-submitted data for inconsistencies or fabricated details, helping identify fictitious suppliers posing as legitimate vendors.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Contains verified identities, beneficial ownership information, and business activity profiles of customers and corporate entities.
- Helps uncover shell or front companies used to mask precursor chemical procurement.
- Validates the stated line of business and flags discrepancies when activity does not match the declared purpose.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Provides verified customer and business identity details, prior KYC data, beneficial ownership information, and historical business or personal data.
- Helps detect discrepancies or repeated changes in identity or business details across relief applications, indicating potential fraud or misrepresentation.
- Facilitates cross-checking newly submitted application data against historically verified information.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Provides verified identity details, beneficial ownership information, transaction summaries, risk ratings, and financial background data for each customer.
- In the context of CBI/RBI applications, this information helps detect discrepancies in declared wealth, identify multiple or conflicting identity documents, and flag sudden changes in financial profiles.
- Directly supports AML detection by revealing whether investments for citizenship/residency are sourced from illicit funds or inconsistent with the applicant’s stated profile.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Comprehensive internal data on verified customer identities, historical name usage, addresses, and beneficial ownership. Cross-referencing newly declared names against prior records helps detect undisclosed aliases or repeated name variations indicative of deliberate identity manipulation.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Provides verified customer identities, beneficial ownership information, declared financial profiles, and associated risk assessments. This data helps detect mismatches between customers’ stated risk/income profiles and their bond activity, identify ownership structures that place bonds in relatives’ or third-party names, and assess unexplained sources of funds.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Provides verified identification documents, beneficial ownership details, and risk profiles for customers.
- Enables detection of individuals or entities who lack proper licensing or offer inconsistent information about cross-border transfers, exposing potential unregulated IVTS usage.
- Validates whether stated remittance activities align with known customer profiles, helping pinpoint suspicious or opaque trust-based arrangements.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Internal files contain verified identities, business details, and historical transaction data for customers. 

- Confirms declared addresses, ownership structures, and trade activities, helping to detect suspiciously incomplete or contradictory details that may indicate ghost shipping.
- Ensures alignment of the actual customer profile with shipping claims.
- [Test Payment Probing](https://framework.amltrix.com/techniques/T0035) — - Contains verified customer profiles, financial backgrounds, and expected account activity.
- Assists in comparing recent small transactions against a customer’s normal financial habits to flag unusual probing attempts.
- Helps investigators correlate suspicious low-value ‘test’ transfers with known legitimate or high-risk customer attributes, refining monitoring thresholds.
- [Smurfing](https://framework.amltrix.com/techniques/T0016.005) — Stores verified customer identities, addresses, ownership information, and risk profiles. This data helps detect smurfing by:

- Revealing accounts with shared personal or contact details that appear unrelated on the surface.
- Comparing declared financial profiles or expected account activity to actual deposit patterns, potentially exposing structuring through smurfing.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Contains verified customer identities, beneficial ownership data, addresses, and risk profiles. Investigators can identify potential shell companies or disguised beneficial owners orchestrating illicit trade diversion. Supports direct review of the customer's ultimate beneficiary and final destination claims for shipped goods.
- [Wash Trading](https://framework.amltrix.com/techniques/T0094.002) — - Contains verified identity data, beneficial ownership information, financial profiles, and business activity details.
- Enables comparison of declared financial resources against actual trading activity, helping uncover mismatched capital or business operations.
- Facilitates linking multiple accounts under the same beneficial owner to detect self-dealing trades.
- [Lottery Scams](https://framework.amltrix.com/techniques/T0144.015) — Includes verified identities, beneficial ownership information, addresses, business registration documents, and risk assessments for individuals or entities claiming to operate lotteries or sweepstakes. Investigators use this data to confirm the legitimacy of licensing claims, detect misrepresentations of business purpose, and identify whether operators are authorized to conduct gaming or remittance activities.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Contain verified identity details, declared sources of income, and beneficial ownership information for customers, including public officials.  
- Cross-checking these data with unusually high government-related deposits or substantial personal holdings helps uncover hidden misappropriation.
- [Public WiFi Networks](https://framework.amltrix.com/techniques/T0015.003) — - Contains verified customer identities, documentation, and addresses, enabling the assessment of whether account openings or modifications align with legitimate user details.
- Facilitates the detection of suspicious or falsified identity information submitted from public WiFi locations, where criminals may mask their true details.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Provides verified customer and business profiles, beneficial ownership data, and declared operational scope.
- Assists in comparing the stated business size or nature against actual revenue sources, particularly large cash inflows purportedly from cigarette sales.
- Aids in identifying potential discrepancies in business activity or beneficial ownership that suggest illicit tobacco smuggling revenues.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Includes verified identity documents, personal and business details, addresses, beneficial ownership information, and ongoing risk assessments. By reviewing these records for each customer account, institutions can detect inconsistent nationality declarations, track newly introduced passports or ID documents, and identify undisclosed dual or multiple citizenship usage. This directly helps uncover attempts to evade scrutiny by leveraging different passports or nationalities.
- [Undisclosed Payment Aggregation](https://framework.amltrix.com/techniques/T0138) — - Consolidate verified identities, beneficial ownership details, authorized signatories, and risk profiles for merchants and associated accounts.
- Facilitate the detection of unauthorized or fraudulent merchant account openings and identity misuse, particularly in cases where criminals open TPPP or merchant accounts without legitimate consent.
- Enable cross-referencing of payers with approved client lists and verify business relationships, exposing suspicious funds lacking lawful connections.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Houses customer identification documents, risk profiles, and due diligence notes, including any declared provenance or acquisition history for artifacts. This data facilitates a deeper investigation of a customer’s capacity to legitimately deal in high-value antiquities.
- [Offsetting Transactions](https://framework.amltrix.com/techniques/T0102) — Includes verified customer identities, beneficial ownership details, and account relationships. This data helps confirm whether multiple accounts involved in offsetting trades are ultimately controlled by the same individuals or entities, revealing collusion or layering.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Contains verified identification details, beneficial ownership information, and self-reported business data.
- Supports scrutiny of declared addresses, operational capacity, and the individuals behind the jewelry business.
- Enables ongoing monitoring of ownership changes to expose opacity or frequent ownership shifts.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Contains verified identities, risk ratings, and supporting documentation for donors, board members, and key stakeholders.
- Enables verification of legitimate donor profiles and detection of incomplete or fraudulent KYC submissions.
- Facilitates screening for infiltration by criminals or parties with unknown or suspicious backgrounds attempting to misuse charitable entities.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Contain verified customer identities, business activities, beneficial ownership data, and financial profiles.
- Help assess whether declared export revenues align with a customer’s known capacity and historical performance.
- Reveal potential discrepancies when actual operations do not match the scale of export claims.
- [Structuring](https://framework.amltrix.com/techniques/T0016) — - Contains verified customer identification data, beneficial ownership information, account relationships, and risk profiles.
- Allows comparison of declared customer details with observed multiple account usage below reporting thresholds.
- Helps identify whether the same individual is using multiple accounts or aliases to evade detection of aggregated deposit amounts.
- [Daigou Networks](https://framework.amltrix.com/techniques/T0013.006) — Contains verified customer identities, personal/business details, and beneficial ownership information, helping detect:

- Discrepancies between stated personal profiles and high-volume commercial-like purchasing or shipping activities.
- Potential straw buyers or surrogate shoppers misrepresenting their actual source of funds.

Using KYC data helps confirm whether clients’ payment volumes and cross-border import expenses align with their declared profiles, aiding AML investigations into Daigou operations.
- [Counterfeit Currency](https://framework.amltrix.com/techniques/T0092) — - Contains verified customer identities, declared business activities, and ongoing risk assessments.
- Allows detection of inconsistencies between legitimate business rationale and actual cash handling, as well as identifying prior criminal associations or negative history relevant to counterfeiting.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Contains verified identification details, addresses, beneficial ownership information, and risk assessments.
- Allows financial institutions to identify potential links to known child exploitation networks or suspicious profiles, enhancing monitoring and scrutiny of relevant accounts.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Contains verified customer and corporate documentation, ownership details, and records of attempts to obtain further financial information.
- Helps identify refusals or delays in providing financial statements or disclosures, suggesting potential front company concealment strategies.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Comprehensive customer data—including identities, business activities, risk profiles, and transaction summaries—enables a direct comparison between the declared purpose of funds and the client's known profile. This helps uncover inconsistencies suggesting misrepresentations.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Contains verified customer identities, beneficial ownership, addresses, and risk profiles.
- Helps identify accounts with minimal or missing KYC information, a hallmark of instant swap platforms with weak compliance controls.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Contains verified personal and business details, addresses, beneficial ownership data, and transactional risk profiles.
- Identifies whether participants in the token sale have undergone proper identity checks or if wallets remain unverified.
- Flags large contributions from high-risk or newly created accounts potentially linked to fraudulent fundraising or money laundering.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Includes verified personal details, addresses, beneficial ownership information, and risk profiles. By comparing these records against newly provided identity data or sudden changes, financial institutions can detect inconsistencies, uncover synthetic or stolen identities, and flag suspicious identity updates for further investigation.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Provides verified identities, beneficial ownership details, and business justifications for involved parties.
- Allows financial institutions to detect unregistered or informal actors lacking legitimate economic purposes.
- Helps identify gaps or inconsistencies that may suggest off-the-record asset transfers.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Contains verified customer identities, ownership details, historical account information, and risk assessments. These records confirm eligibility representations in relief applications, highlight deviations from stated customer profiles, and identify potential synthetic or stolen identities used to fraudulently obtain government funds.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Encompasses verified customer identities, beneficial ownership data, and transaction risk profiles.
- Detects newly created exchange or wallet accounts lacking legitimate business purposes, enabling scrutiny of account holders engaging in this cryptocurrency layering technique.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Contains verified customer identities, beneficial ownership data, and risk profiles.
- Reveals parties with prior suspicious activity, high-risk jurisdiction exposure, or newly formed entities lacking operational history.
- Helps confirm legitimate business purposes and identify red flags in documentary collection transactions.
- [Domestic Bulk Cash Delivery](https://framework.amltrix.com/techniques/T0119) — Includes verified identities, authorization details, and business profiles of customers and depositors, allowing for the detection of unauthorized third-party couriers and confirmation that cash inflows align with declared business activities. This data enables thorough investigations into suspicious deposits tied to domestic bulk cash deliveries.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Maintains verified customer information, business activities, beneficial ownership structures, and risk profiles.
- Enables comparison of declared business operations against actual foreign exchange transactions, identifying incongruent volumes or patterns.
- Highlights entities that appear dormant or lack physical presence but engage in high-volume FX activities, signaling potential trade-based laundering.
- [Utility Tokens](https://framework.amltrix.com/techniques/T0067.005) — - Contains verified customer identity information, beneficial ownership details, and account relationships.
- Helps detect minimal or anonymous KYC scenarios, flagging individuals or entities engaged in utility token transactions without verifiable identities.
- Facilitates correlation of on-chain or exchange data with real-world customer profiles, exposing potential use of multiple new wallets lacking proper KYC documentation.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — - Contains verified customer identities, declared sources of incoming funds, and expected transaction profiles.
- Highlights discrepancies between the purported remittance source or amount and the actual credited amounts from unrelated parties.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Maintains verified customer identities, beneficial ownership details, and due diligence findings.
- Helps detect frequent changes in beneficial ownership or identity discrepancies that may conceal smuggling proceeds.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Contains verified personal and financial details (e.g., declared income, employment status, and beneficiary information). These records support detecting pension contributions that exceed the customer’s known financial profile and pinpoint suspicious or undocumented beneficiary changes.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Contains verified identity and business profiles, addresses, beneficial ownership data, and risk metrics used to confirm the authenticity of submitted documentation.
- Cross-referencing newly provided documents with established KYC information helps uncover inconsistencies indicative of potential forgeries.
- [Chip Dumping](https://framework.amltrix.com/techniques/T0107.003) — - Includes verified customer identity documents, account creation timelines, and beneficial ownership information.
- Helps detect newly registered or minimally vetted accounts quickly engaging in high-value chip transactions.
- Provides a means to identify multiple suspicious accounts linked to the same individual or incomplete KYC profiles, a common tactic in chip dumping.
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Includes verified customer identities, beneficial ownership details, risk scores, and account profiles.
- Aids in identifying new or unexplained usage of self-hosted wallets, sudden changes in external addresses, and questionable explanations for sources or uses of funds, which may signal high-risk activity.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Contains verified information on farmland registration, beneficial owners, declared business scope, and operational scale. Examining any sudden or repeated changes to these records prior to subsidy disbursements helps detect inconsistencies and insufficiently supported claims.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Stores verified vendor data, including official contact details, authorized signatories, and beneficial ownership.
- Monitors updates to vendor profiles and triggers internal checks to validate the authenticity of changed contact information.
- Enables swift verification of vendor identity before processing payments to prevent impersonation.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Contains verified identities, beneficial ownership details, and overall risk assessments. Reviewing these records helps identify contradictory explanations for repeated invoices, detect shell or front entities, and support further investigation of suspicious billing patterns.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Contains verified identities, ownership details, and risk profiles of clients. Reviewing these records for parties transacting through OTC desks reveals whether minimal or no due diligence was performed, highlighting potential laundering risks.
- [Loyalty Points](https://framework.amltrix.com/techniques/T0106) — These records provide verified customer identities, beneficial ownership information, and account relationships. For loyalty point programs, KYC data helps identify individuals or entities that control multiple loyalty accounts, enabling the detection of aggregating or pooling strategies and verifying whether account holders are high-risk or suspicious.
- [Rental Income Schemes](https://framework.amltrix.com/techniques/T0010.004) — - Contains verified identities, beneficial ownership details, and source-of-funds information for landlords and tenants.
- Facilitates the identification of falsified tenancy agreements or financed rent from illegitimate sources, ensuring that parties to rental transactions are genuine.
- [Cheque Fraud](https://framework.amltrix.com/techniques/T0144.010) — - Contain verified identity documents, beneficial ownership information, and account opening details, enabling the detection of inconsistent or suspicious customer profiles.
- Provide baseline transaction behavior and risk assessments, allowing for the identification of anomalies such as sudden large check deposits from unknown payors.
- Help verify the legitimacy of recently opened accounts used for rapid withdrawals following fraudulent check deposits.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Contains verified identities, beneficial ownership details, and risk assessments of customers and related parties.
- Identifies genuine investor profiles, helping to flag suspicious or incomplete due diligence where purported foreign investors lack legitimate business ties.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Provides verified customer identity information, including names, dates of birth, addresses, and ownership details.
- Allows financial institutions to cross-check submitted personal data for consistency, detect reused or stolen identities, and identify discrepancies in documentation.
- [Independent Payment Agents](https://framework.amltrix.com/techniques/T0113.001) — - Contains verified customer identity data, including personal details, addresses, and beneficial ownership information.
- Helps detect instances where sub-agents bypass or fail to document required onboarding steps, ensuring compliance with AML/CFT obligations.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Contains verified customer identities, business profiles, ownership information, and AML risk assessments.
- Enables detection of undisclosed relationships, suspicious backgrounds, or repeated misuse of consulting services to launder funds.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Contains verified identity data, personal details, and documentation of customers.
- Detects minimal or inconsistent identification used at crypto ATMs, indicating potential mule activity or attempts to bypass KYC controls.

---

## [ATM Usage & Geolocation Data](https://framework.amltrix.com/data-sources/DS0040)

**Description:**
Detailed records of ATM usage, including geolocation data, date and time stamps, transaction types and amounts, and other related metadata.

### Related Techniques
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Logs ATM withdrawal timestamps, transaction amounts, and physical terminal locations.
- Identifies anomalous withdrawal patterns or geographically dispersed usage of prepaid cards, which can signify illicit layering or shared credentials.
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Details the physical locations and timestamps of ATM withdrawals.
- Helps uncover patterns of withdrawals across multiple machines or regions in short time intervals to evade reporting thresholds.
- [ATM Structuring](https://framework.amltrix.com/techniques/T0016.004) — - Captures the specific ATMs used, including exact locations, timestamps, and deposit amounts, helping to confirm sub-threshold patterns across different machines.
- Enables analysis of transaction clustering in certain geographic regions or unusual ATM activity outside the customer’s typical area.
- Assists in linking multiple depositors (smurfs) using various ATMs to structure funds undetected by traditional branch-based monitoring.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Provides ATM usage details, including location, timestamps, transaction types, and amounts.
- Enables detection of unusual withdrawal or deposit patterns possibly tied to on-the-ground prostitution activities and the funneling of cash proceeds.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Logs deposit locations, timestamps, and details for ATM or branch transactions.
- Reveals patterns of structured cash deposits in multiple locations consistent with funnel account operations.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Records of crypto ATM usage capture geolocation data, timestamps, transaction types, and amounts. This information helps identify suspicious location-based patterns, such as coordinated small deposits by multiple individuals, irregular usage in distant regions within short timeframes, or intensive activity at unusual hours.
- [Cheque Fraud](https://framework.amltrix.com/techniques/T0144.010) — - Logs the time, location, and frequency of ATM-based check deposits, revealing geographically dispersed or rapid deposit patterns.
- Helps identify multiple deposits made in quick succession across different branches or ATMs, consistent with check fraud layering tactics.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Logs customer withdrawals and deposits at ATMs, including Bitcoin ATM transactions, along with associated geolocation points.
- Detects sudden or large-value crypto purchases via Bitcoin ATMs, aligning with pig butchering scam instructions.
- Flags anomalies where usage patterns conflict with a customer’s historical ATM activity or geographic profile.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Captures ATM withdrawal locations, timestamps, amounts, and frequency.
- Enables detection of frequent, small withdrawals across multiple ATMs or foreign locations, aligning with micro-structuring methods used to layer illicit funds.
- [Smurfing](https://framework.amltrix.com/techniques/T0016.005) — Captures location, date, time, and amount details for ATM transactions. This supports smurfing detection by:

- Showing multiple small cash deposits performed across different ATMs or geographic locations in quick succession.
- Identifying unusual patterns in the distribution of low-value deposits suggestive of smurfing activity.
- [Cash Deposits](https://framework.amltrix.com/techniques/T0004) — - Tracks precise ATM deposit details (e.g., date, time, amount) and geolocation of deposit activities, enabling the identification of repetitive or structured cash deposits across different ATM locations.
- Helps detect sub-threshold deposit patterns, such as frequent or staged deposits in quick succession, which are indicative of potential structuring.
- Assists investigators in correlating deposit behavior with customer profile data to pinpoint anomalies in cash deposit volumes or frequencies.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Provides detailed records of crypto ATM usage, including locations, timestamps, and transaction details.
- Helps identify abnormal or cross-jurisdictional usage patterns, revealing potential layering or mule activity involving rapid deposits of illicit cash.

---

## [Communication Records](https://framework.amltrix.com/data-sources/DS0042)

**Description:**
Records of electronic communications, including emails, phone calls, messaging apps, and social media, capturing metadata such as sender/receiver details and timestamps. Where legally permissible, the content may also be included. These logs can help identify suspicious instructions, insider collusion, or other high-risk interactions among individuals or entities.

### Related Techniques
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — Records from corporate emails, phone calls, and messaging platforms capture metadata such as sender/receiver details, timestamps, and—where legally permissible—message content. These logs can reveal unauthorized sharing of material non-public information, suspicious instructions around market-moving announcements, or collusion among insiders, directly supporting investigations of illicit trading activity.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Logs or metadata of communications, such as emails, phone calls, and messaging app exchanges, can reveal insider collusion, corrupt instructions, or expedited approvals from government officials manipulating the relief program process.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Captures logs of customer interactions (emails, calls, messages) where permissible by law.
- Documents reluctance or evasiveness in justifying fund origins or offshore transactions.
- Helps investigators correlate suspicious communication patterns with cross-border or secrecy jurisdiction activity.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Logs communications, including social media messages and phone calls, providing metadata about recruitment instructions.
- Identifies cross-communication among multiple recruited mules.
- Reveals direct instructions to route illicit funds.

This evidence helps tie suspicious activity to specific social media recruiters or networks.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — - Provides logs of phone calls, emails, or messaging app records that can reveal explicit threats or demands from criminal groups.
- Assists investigators in confirming that recurring payments are coerced under extortion schemes, linking communications to suspicious financial activity.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Logs capture the metadata (and sometimes content, where legally permissible) of electronic communications, including emails, calls, and messages. By reviewing or correlating this data with suspicious transactions, investigators can:

- Identify explicit references to intimidation, threats, or forced payments.
- Uncover direct communications indicating extortion-based fundraising activities.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Contains logs of emails, phone calls, and messaging app conversations used for alleged recruiting.
- Links suspicious instructions or demands directly to phishing-based job offers, providing critical investigative evidence of money mule solicitations.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Encompass internal emails, chat messages, and other communications, capturing both metadata and (where permissible) content.  
- Expose instructions using coded or informal language to coordinate or conceal questionable transactions or data changes by insiders.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Includes emails, phone logs, and messaging app records among borrowers, co-lenders, intermediaries, and other relevant parties.
- Helps identify discussions or instructions pointing to collusion, such as agreeing to inflate invoices, bypass due diligence, or conceal beneficial ownership in syndicated trade loan arrangements.
- Enables investigators to trace communication patterns that align with suspected manipulations of trade finance and credit agreements.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Contains call logs, emails, and messaging app data (where permissible).
- Discloses instructions or coercion related to funnel account usage, as well as contradictory explanations for cross-border transfers.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Captures metadata from electronic communications, such as emails, phone calls, and messaging app exchanges, potentially including sender/receiver details and timestamps.
- Identifies possible grooming, recruitment, or coordination activities linked to child exploitation, supporting targeted investigations when illicit financial indicators are present.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Retains whistleblower reports, employee complaints, and other relevant communications.
- Uncovers potential tips or direct allegations of bribery, supporting investigative follow-up.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Contains metadata (sender, receiver, timestamps) of messages and calls; where permissible, may include content.
- Helps uncover coordination of sexual services, negotiation of payments, and distribution of illicit proceeds among traffickers or exploiters.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Collects metadata (and, where permissible, content) of calls, emails, messages, or social media communications.
- Reveals references to dark web platforms or suspicious discussions related to precursor chemical sourcing.
- Helps correlate communication patterns with financial transactions to detect illicit procurement arrangements.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Include emails, phone calls, and chat logs where impersonators might provide conflicting identities or refuse further verification.
- Enable the review of communication patterns that reveal deceptive arguments or repeated inconsistencies in customer identification.
- [Match-Fixing](https://framework.amltrix.com/techniques/T0107.005) — - Collects metadata from emails, phone calls, and messaging apps, such as sender/receiver details and timestamps.
- Identifies potential coordination or collusion among bettors, players, and officials involved in manipulating match outcomes.
- Assists investigators in uncovering illicit communication patterns related to match-fixing arrangements.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Captures email and messaging logs, revealing suspicious or spoofed instructions to alter vendor payment details.
- Helps detect compromised or impersonated accounts rerouting institutional payments to unauthorized recipients under the guise of legitimate projects.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Captures metadata (and, where permissible, content) of electronic communications such as emails, phone calls, and messages.
- Verifies whether instruction changes were made solely via email or from suspicious domains.
- Identifies urgent payment requests, domain mismatches, or typosquatting indicative of vendor impersonation.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Encompasses emails, phone call logs, and messaging app data involving professional intermediaries and their clients. Investigators can uncover explicit or implicit instructions to structure transactions, obscure ownership details, or evade AML controls.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Include logs of calls, emails, and messaging app exchanges between recruiters and account holders.
- Can show explicit instructions to use personal accounts for rapid fund transfers and highlight secrecy or urgency demands.
- Support investigations into the nature of recruitment dialogues and financial transaction directives.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Provides transcripts or metadata of calls, messages, and other communications. In the context of knowledge compartmentalization, these records help identify contradictory or limited explanations given by different individuals, revealing deliberately siloed information about transaction purposes or roles.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Contains logs of phone calls, emails, or messaging app exchanges where hawala participants might use coded or encrypted instructions to arrange or confirm fund movements, aiding investigations into concealed or suspicious activities.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Captures electronic messages, phone calls, and social media communications, including metadata (sender, receiver, timestamps).
- Supports the detection of romance mule recruitment by identifying scam-related language, urgent requests for assistance, or scripted instructions from purported romantic partners.
- Provides valuable context for investigators to link suspicious transactions with documented communications referencing money movement under romantic pretenses.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Includes messaging, email, and call logs (and content where permissible) between customers and external parties.
- Reveals romantic or friendly overtures mixed with investment solicitations, a hallmark of pig butchering scams.
- Allows investigators to correlate transaction activity with manipulative communication tactics used by fraudsters.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Includes emails, phone logs, and messaging archives that reveal the frequency and content of communications between investors and the local entity.
- Identifies instances where minimal or no interaction contradicts significant labeled foreign investments, suggesting potentially fictitious arrangements.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — Logs capturing emails, phone calls, and other messaging platforms typically document timestamps, sender/recipient identities, and—in jurisdictions where permissible—content. Analyzing these records can reveal collusive arrangements, instructions to withdraw bids, and other conspiratorial communications consistent with bid manipulation.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Capture phone call and messaging metadata (e.g., duration, frequency, participants, timestamps) to verify genuine call center operations.
- Reveal inconsistencies if declared large-scale telemarketing revenue does not match actual call volume or communication patterns.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Captures metadata and, where permissible, the content of donor or management communications (emails, calls, messaging apps).
- Discloses unclear or evasive donor instructions, false statements of purpose, or contradictory claims about fund usage.
- Supports investigations by correlating suspect messages with suspicious donation timing or unusual board changes.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Captures emails, chat messages, and social media communications, including pertinent timestamps and metadata.
- Reveals instances where private keys or wallet credentials are improperly requested under the guise of token sale requirements.
- Uncovers abrupt changes or suspicious instructions in official channels, aligning with common ICO exit scam behaviors.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Captures emails, messages, or calls among fund managers, investors, and other parties. Analysis may uncover explicit collusion or instructions to manipulate investment returns or conceal illicit capital.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — - Captures audio/video call logs, transcripts, and messaging activity, including timestamps, caller/recipient details, and any recorded content.

- Enables comparison of suspected deepfake calls with known legitimate recordings to identify discrepancies in voice, speech patterns, or video artifacts, supporting the detection of impersonation attempts.

---

## [Geographical Transaction Data](https://framework.amltrix.com/data-sources/DS0048)

**Description:**
Location-based records of financial transactions, including origin, destination, amounts, timing, and relevant geolocation metadata for analyzing cross-border transactions and payment flows.

### Related Techniques
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Identify significant cross-border transactions and the involved jurisdictions.
- Highlight inflows from high-risk or poorly regulated regions used to fund construction projects.
- Support enhanced due diligence on foreign investors whose geographic profile presents elevated AML risk.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Maps transaction origin and destination locations against known customer activity patterns.
- Reveals geographical inconsistencies (e.g., transactions initiated from regions not typical for legitimate account usage), indicating potential account takeover.
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Contains location-based transaction records, including origin, destination, and geolocation metadata.
- Assists in detecting cross-border or multi-jurisdictional flows to and from self-hosted wallets, highlighting potential structuring or layering across different regions.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Provides location-based records of financial transactions, including origins and destinations.
- Facilitates detection of unusual diamond trading patterns involving high-risk or sanctioned jurisdictions.
- [ATM Structuring](https://framework.amltrix.com/techniques/T0016.004) — - Incorporates location-based records of financial transactions, allowing direct comparison of the customer’s usual regions of economic activity against sudden or widespread ATM deposits in multiple areas.
- Flags anomalies where deposit volumes and geographic dispersion deviate significantly from established norms, indicating possible structuring activities.
- Aids in assessing whether ATM-related transactions are suspicious based on mapped proximity or cross-regional patterns without a legitimate business rationale.
- [Peer-to-Peer (P2P) Transfers](https://framework.amltrix.com/techniques/T0134.001) — Tracks geographic metadata for each transaction, revealing inconsistencies when P2P transfers originate from diverse or improbable locations that contradict the account holder’s profile.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Tracks the origin and destination of in-game currency transactions, including cross-border flows and high-risk geographies.
- Supports detection of large-volume in-game value movement involving jurisdictions known for lax AML regulations, lacking a legitimate business or gameplay rationale.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Captures location-based details of financial transactions, including origins, destinations, and timing.
- Reveals geographically dispersed high-value purchases made in quick succession, indicating potential layering or deliberate confusion of regulatory jurisdictions.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Details the origins and destinations of financial transactions, including country identifiers, cross-border flows, and associated metadata.
- Enables monitoring of in-game currency exchanges traversing jurisdictions with lax AML controls, highlighting potential transnational laundering techniques.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Captures origin, transit, and destination details for cross-border shipments and related financial flows.
- Enables detection of unusual or circuitous shipping routes that may signal deliberate misinvoicing or masking of true shipment values.
- [Geographically Dispersed Cash Deposit](https://framework.amltrix.com/techniques/T0053) — - Provides detailed origin and destination metadata for financial transactions, including branch locations or regional identifiers.
- Facilitates detection of rapid deposits in multiple distant areas, a hallmark of smurfing.
- Enables geo-mapping of deposit clusters to spot emerging patterns inconsistent with a customer’s normal activity.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Highlights fund movements originating from or destined for high-risk or offshore jurisdictions.
- Identifies questionable premium payments or claim disbursements linked to secrecy locations, aiding in the detection of disguised cross-border layering.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Captures location-based details of financial transactions and shipping routes, including origin, destination, timestamps, and relevant geographic metadata. This data helps identify unusual or convoluted cross-border routing, last-minute changes to shipment destinations, and inconsistencies with normal trade lanes, all of which can signal trade-based laundering.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Tracks the origin, destination, and geo-coordinates of financial transactions.
- Helps trace multi-jurisdictional routes and layering strategies indicative of funnel account schemes.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Capture transactional origin and destination details with associated geolocation.
- Highlight frequent remittances or financial flows to zones at high risk for human trafficking.
- Cross-reference with other records to confirm suspicious movement of funds tied to exploitation networks.
- [Crowdfunding Campaign Manipulation](https://framework.amltrix.com/techniques/T0044) — - Provides location-based records of financial transactions (e.g., IP addresses, geolocation metadata).
- Allows comparison of donor origins against the campaign’s stated location or beneficiary region to detect anomalies.
- Supports identification of potential layering, where illicit funds are split and routed from multiple jurisdictions.
- [Mobile Payment Systems](https://framework.amltrix.com/techniques/T0134.002) — Provides cross-border origin and destination data for mobile transactions. This data identifies unusual or high-risk jurisdictions and detects discrepancies between declared residency or business location and actual transaction flows, supporting the identification of layering and structuring patterns in mobile payments.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Contains location-based records of financial transactions, capturing origin, destination, amounts, and geolocation metadata.
- Enables identification of transaction clusters near vulnerable border areas or known smuggling corridors.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Tracks transaction origin and destination points, including geolocation metadata.
- Facilitates detection of unusual cross-border flows, especially where established banking channels are bypassed for lesser-regulated alternatives.
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — - Tracks cross-border transfers involving professional intermediary accounts and identifies offshore or high-risk destinations.
- Pinpoints transactions masked under client confidentiality, revealing risk patterns indicative of layering or integration strategies.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Provides location-based metadata for financial transactions, including the origin and destination of funds.
- Identifies patterns of multiple micro-amount deposits from diverse regions funneling into a single account, a common indicator of micro-structuring.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Tracks the geographic origin and destination of financial transactions, covering both domestic and cross-border movements.
- Detects shifts in vendor payment routes or payments to atypical jurisdictions inconsistent with the vendor’s usual operations.
- Helps flag potential higher-risk regions for closer scrutiny when a vendor's account details suddenly change.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Provides origin and destination geolocation details for financial transactions.
- Exposes irregular cross-regional inbound deposits labeled as ‘advance fees,’ helping to flag potential international or multi-regional scam activity.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Provides geolocation details of financial transactions, including origin, destination, amounts, and related jurisdictional metadata.
- Enables detection of mismatched currency flows involving locations not aligned with the customer’s declared business or residence.
- Assists in identifying high-risk or unusual cross-border routes used to layer illicit funds.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Reveals the origin and destination locations of fund flows, enabling analysts to identify unusual cross-border transfers orchestrated by professional intermediaries that exceed typical geographic coverage or regulatory norms.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Tracks the origin and destination of cross-border transactions, highlighting specific jurisdictions, transaction volumes, and timing.
- Helps reveal offshore routing patterns by shell companies leveraging jurisdictions with limited transparency, facilitating layering or obfuscation of transaction flows.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Tracks transaction origin and destination geolocation metadata.
- Flags the channeling of funds through jurisdictions lacking robust banking oversight or commonly associated with hawala networks.
- Helps correlate cross-border flows with customer profiles to identify unusual or unauthorized IVTS-related routes.
- [Public WiFi Networks](https://framework.amltrix.com/techniques/T0015.003) — - Captures geolocation details for each transaction, allowing comparison of the actual transaction origin with the customer’s declared address or usual location.
- Highlights anomalies when transactions originate from diverse or distant public WiFi hotspots in short timeframes, indicating possible location obfuscation.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Correlates transactions with their geographic origin or destination to reveal cross-border fund flows. In rug pull scenarios, sudden movements of capital to multiple or opaque jurisdictions may indicate layering efforts to obscure the funds' final recipients.
- [Domestic Bulk Cash Delivery](https://framework.amltrix.com/techniques/T0119) — Contains location-based details of deposit and withdrawal activities, showing branch usage and distances from a customer’s usual business or residential areas. This data helps identify suspicious cluster deposits along domestic transport routes, consistent with bulk cash deliveries.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Captures origin, destination, and route details for financial movements.
- Enables detection of frequent or repeated cross-border trips involving smaller declared amounts (smurfing).
- Helps aggregate multiple declarations below thresholds that collectively sum to higher illicit totals.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Tracks the originating and destination countries tied to financial transactions. This data:

- Pinpoints repeated or high-value transfers to offshore locations.
- Detects sudden geographic shifts in a customer’s transaction profile.
- Supports investigation into layering tactics through multiple foreign jurisdictions.

---

## [Real Estate & High-Value Asset Ownership and Transaction Records](https://framework.amltrix.com/data-sources/DS0043)

**Description:**
Databases containing comprehensive information on the ownership, purchase, and transfer of real property and other high-value assets (such as vehicles, luxury goods, fine art, and precious metals). These records typically include details like property addresses, transaction dates, purchase values, involved parties, and beneficial ownership data.

### Related Techniques
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Details ownership and transaction data for real estate and other high-value assets. For corruption inquiries, linking expensive asset acquisitions with minimal reported income helps expose bribery proceeds or embezzled funds laundered through property purchases.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Provides official records and transaction details related to real property and other high-value assets, including ownership history, purchase amounts, and involved parties. In the context of this technique, these records enable investigators to trace and verify the legitimacy of investments in real estate or high-value assets, uncover hidden beneficial owners, and detect suspicious cross-border ownership transfers in jurisdictions with minimal disclosure requirements.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — These records provide official information on property ownership, transaction dates, purchase prices, and involved parties. By comparing property acquisition and ownership data against reported business income and historical ownership changes, investigators can detect suspicious transfers or rapid flips indicative of commingling or layering in high-cash-flow real estate operations.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Details farmland ownership histories, land classification statuses, and associated property appraisals.
- Detects repeated reclassifications of agricultural land (e.g., to building land) or inflated valuations inconsistent with normal market conditions.
- Traces transfer records to expose suspicious farmland sales or undervalued/overvalued appraisals used to disguise illicit funds.
- [Deceptive Tax Filings](https://framework.amltrix.com/techniques/T0014.007) — Captures ownership and transaction data for properties, luxury goods, and other high-value assets. Large acquisitions or frequent asset trades that exceed reported income suggest undisclosed funds and potential tax underreporting in deceptive filings.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Documents property ownership details, transaction values, and asset transfers. Reviewing farmland ownership specifics and any suspicious changes in property records supports the detection of fraudulent or nonexistent farmland used in subsidy applications.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Details property deeds, asset purchase histories, and beneficial ownership for real estate or luxury assets.
- Facilitates detection of covert acquisitions by sanctioned individuals leveraging opaque corporate vehicles in permissive jurisdictions.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Details ownership history, transaction dates, and purchase prices for real estate and other high-value assets (e.g., fine art, jewelry).
- Uncovers repeated flips or short holding periods consistent with layering and verifies provenance to detect irregularities in recordkeeping.
- [Real Estate Auction](https://framework.amltrix.com/techniques/T0108.001) — Comprehensive records of property ownership and transfers, including transaction dates, purchase amounts, parties involved, and property valuations.

- Identifies large or suspicious cash payments in real estate auctions.
- Correlates auction sale prices with known market values to detect potential overbidding or underbidding.
- Flags frequent rapid resale or ‘flipping’ patterns that may indicate layering attempts.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Tracks ownership changes and recorded valuations for high-value assets, including jewelry.
- Identifies abnormal fluctuations in appraised values when the same item is transferred multiple times, indicating potential manipulation for layering or illicit value movement.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Details ownership, purchase amounts, transaction dates, and beneficial parties for real property and luxury assets.
- Facilitates identification of undeclared or undervalued acquisitions that may conceal proceeds of tax evasion.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — - Contains comprehensive records of ownership and transaction history for high-value assets, including fine art, with details on purchase values, dates, and involved parties.
- Detects rapid reselling, unexplained price deviations, or incomplete provenance information, which align with potential art market manipulation patterns.
- [Unlicensed Real Estate Brokerage](https://framework.amltrix.com/techniques/T0133) — Contains official records of real estate and high-value asset transactions, including property addresses, dates, purchase values, and involved parties. This data helps uncover repeated usage of the same unregistered intermediary, unusual property pricing, and missing licensed broker details—key red flags for unlicensed real estate brokering.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Contains acquisition details for farmland, livestock, and other high-value assets, including documented valuations, sale dates, and owners of record. Investigators can flag anomalous pricing, abrupt farmland purchases, or livestock transactions lacking sound commercial rationale, consistent with agricultural sub-techniques of laundering.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Databases of real property and other valuable assets, including purchase details, beneficial owners, and transactional histories.
- Helps uncover investment strategies involving opaque assets that can serve as conduits for laundering funds through private equity or holding companies.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Captures registration, transfer, and ownership details of art, jewelry, and other high-value assets. Helps track frequent changes in ownership or inflated valuations for items in freeports, revealing possible manipulation or laundering activity.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Document ownership and transactions of real property and valuables.
- Enable detection of sudden acquisitions funded by unexplained deposits potentially tied to trafficking proceeds.
- Help trace beneficial owners of real estate or luxury items used to launder illicit funds from forced labor or sexual exploitation.
- [Asset Valuation Manipulation](https://framework.amltrix.com/techniques/T0045) — Provides official records on the ownership, purchase, and transfer of high-value assets (e.g., real estate, fine art, luxury items), including transaction dates, prices, and parties involved. These details enable the detection of over- or under-valued sales, identification of repeated ownership transfers at inconsistent values, and comparison of declared prices with typical market benchmarks—key indicators for uncovering manipulated asset valuations.
- [All-Cash Real Estate Transactions](https://framework.amltrix.com/techniques/T0010.005) — Provides official records of property ownership, purchase amounts, transaction dates, and beneficial owners. This data helps identify large or unusual all-cash real estate purchases, verify market values, and detect potential use of shell companies or layered ownership structures to launder illicit funds.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Contains recorded data on property or high-value asset purchases, transaction values, beneficial owners, and historical sales.
- Enables detection of inflated real estate valuations or suspicious partial refunds once CBI/RBI conditions are satisfied, revealing potential laundering schemes.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Tracks ownership and transfers of real property and other high-value assets, including purchase dates, prices, and involved parties.
- For CBI/RBI applicants, helps identify significant asset acquisitions used to meet minimum investment thresholds, potentially funded by illicit proceeds.
- Supports AML detection by comparing declared financial profiles against large-scale property or luxury asset purchases indicative of money laundering attempts.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Details property ownership transfers, transaction dates, purchase values, and involved parties.
- Highlights rapid property flips, discrepancies in purchase and resale amounts, and the use of escrow services, supporting the detection of layering through quick resale schemes.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Provides detailed information on property purchases and transfers, including addresses, transaction dates, purchase values, and involved parties.
- Allows identification of foreign real estate acquisitions and tracking of property flipping or rapid sales.
- Facilitates verification of beneficial ownership data for overseas properties linked to shell companies or trusts, helping uncover hidden ownership structures in cross-border laundering schemes.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Maintains information on ownership, purchase, and transfer of high-value assets, including fine art, precious metals, and collectibles.
- Verifies declared valuations for collectible items, detecting artificially inflated or deflated transaction prices.
- Cross-checks reported ownership histories and provenance details, revealing potential anomalies in repeated sales or questionable authenticity.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Provides official records of property ownership, sale dates, purchase values, and declared renovation details.
- Facilitates direct comparison between recorded property conditions, typical local construction costs, and stated improvement expenses to detect inflated or fictitious renovation claims.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Contains details on property and luxury asset purchases, transaction amounts, and beneficial owners.
- Helps trace the integration of drug proceeds into real estate or other high-value acquisitions used to launder illicit funds.
- Identifies unexplained wealth, asset flipping, or suspicious property deals tied to narcotics profits.
- [Asset Cloaking](https://framework.amltrix.com/techniques/T0009) — - Includes registration and transaction details for properties and high-value assets.
- Highlights ownership changes across potentially related offshore entities or nominees.
- Aids in detecting cyclical or rapid asset transfers designed to obscure the ultimate owner.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Provide official registration and purchase details of valuable assets, including property transfer histories, buyer identities, and purchase amounts.
- Uncover disproportionate asset acquisitions by public officials lacking legitimate funding sources, signaling potential misappropriation.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Contains ownership and transaction details for high-value assets, including cultural artifacts. This data helps detect artificially inflated valuations, identify suspicious ownership transfers, and pinpoint repeated flips of the same item among closely related parties.
- [Trust-Based Obfuscation](https://framework.amltrix.com/techniques/T0088.002) — - Provides official documentation on the ownership and transfer of real estate, yachts, aircraft, artwork, and other high-value assets.
- Enables investigators to trace the ultimate controllers of valuable holdings often placed under trusts or similar fiduciary arrangements to hide beneficial ownership.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Provides official records on real estate or high-value asset ownership and transfers.
- Reveals discrepancies between registered owners and de facto controllers.
- Flags untraceable or informal asset transfers indicative of off-the-record deals.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Captures ownership and transaction histories for high-value assets (e.g., yachts, aircraft, fine art), highlighting frequent or rapid transfers. Such data helps uncover layering or unexplained changes in beneficial ownership aimed at obscuring true asset controllers.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Provides details on ownership, purchase, and transfer of high-value assets stored or traded in freeports.
- Identifies prolonged storage, beneficial owners of valuable items (e.g., artwork, precious metals), and minimal disclosure patterns.
- Supports investigations into concealed ownership and suspicious asset movements within free trade zones.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Documents purchases and transfers of real estate, luxury goods, and other high-value assets.
- Helps trace the rapid redeployment of illicit carbon credit proceeds into tangible assets, a common layering method in money laundering schemes.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Documents ownership histories and transaction values for properties, artwork, luxury vehicles, and similar high-value goods.
- Allows comparison of auction sale prices against typical market benchmarks to detect undervalued or inflated transactions.
- Helps identify repeated flipping or rapid turnover of items that may signify layering or integration of illicit funds.
- [Informal Micro-Finance Schemes](https://framework.amltrix.com/techniques/T0096) — Comprehensive ownership and transaction details for real property and other significant assets enable investigators to link lump-sum group disbursements to subsequent high-value purchases and confirm whether these acquisitions align with the parties’ legitimate financial profiles.
- [Rental Income Schemes](https://framework.amltrix.com/techniques/T0010.004) — - Contains property ownership information, transaction history, and valuations.
- Enables cross-checking declared rental income against actual property specifics and occupancy records to detect inflated or fictitious rents.
- Supports identification of properties with no legitimate tenant activity.

---

## [Commodity Transaction Data](https://framework.amltrix.com/data-sources/DS0044)

**Description:**
Detailed records of commodity purchases, sales, or exchanges, including transaction dates, parties involved, commodity types, quantities, and prices. These records help verify the legitimacy and scope of commodity-related transactions, especially in trade finance scenarios.

### Related Techniques
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — Captures detailed records of precious commodity trades, including the commodity type, quantity, transaction date, parties involved, and pricing. This granular data helps detect suspicious trading frameworks and pricing anomalies, enabling direct cross-checks against declared values or documentation for potential misrepresentation or smuggling.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Provides detailed records of commodity transactions, including:

- Commodity type, quantity, dates, and involved parties.
- Cross-checks against invoice details to identify over/under-invoicing.
- Facilitates comparison between declared shipping/route details and actual commodity movements.
- Enables detection of last-minute changes to commodity specifications in letters of credit or other trade finance instruments.

By correlating these records with official trade documentation, market pricing data, and transaction logs, investigators can spot discrepancies in pricing, quantities, or routes that commonly indicate trade-based money laundering.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Offers detailed records of commodity purchases, sales, or exchanges, including transaction dates, parties involved, commodity types, and prices. This data helps to:

- Verify the legitimacy and scope of precious metals or gemstone transactions.
- Detect unusual patterns or repeated trades that deviate from typical market behavior.
- Support investigations into potential layering or integration tactics within trade-based laundering schemes.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Detailed records of commodity purchases, sales, or exchanges cover transaction dates, parties involved, commodity types, quantities, and prices. Investigators can cross-check the existence and details of commodity trades against invoices and shipping records, identifying potential over- or under-invoicing or phantom shipments used for trade-based manipulation.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — - Contains detailed records of commodity trades, including transaction dates, quantities, prices, and involved parties.
- Allows AML investigators to confirm the authenticity of reported countertrade transactions and identify repeated or circular movement of the same goods.
- Helps detect discrepancies between declared trades and actual market activity, exposing possible over- or under-invoicing schemes.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Details commodity trades, including dates, parties, quantities, and transaction pricing.
- Aids AML by verifying frequent high-value diamond transfers or re-valuations indicative of layering.
- [Commingling Environmental Crime Proceeds](https://framework.amltrix.com/techniques/T0057) — - Contains records of commodity trades, including volumes, prices, counterparties, and transaction dates.
- Pinpoints anomalies in trade patterns for environmental or wildlife commodities, such as sudden spikes or repetitive transactions.

This data aids in identifying suspicious trading activity and the potential laundering of proceeds from illegal resource extraction.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Captures transaction-level details of precious metals trades, including the parties involved, quantities, trade dates, and pricing. Institutions use this data to detect suspiciously large or repeated trades that exceed typical production capacity or market norms, indicating potential illegal mining proceeds.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Includes records of actual commodity trades, transaction dates, involved parties, quantities, and agreed-upon prices.
- Allows direct cross-checking of declared invoice amounts and trade details against authentic commodity transactions, helping expose undervaluation or overvaluation consistent with misinvoicing.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — Provides detailed records of commodity purchases, sales, and exchanges, including transaction dates, parties involved, commodity types, quantities, and prices. For bonded warehouses storing precious commodities, these records enable investigators to trace the final disposition of goods, cross-check reported valuations, and identify discrepancies indicative of potential layering or misrepresentation.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Tracks commodity trades, including transaction dates, parties, types of commodities, quantities, and prices.
- Allows validation of declared goods against market norms, revealing discrepancies in volume or value.
- Supports detection of abnormal trading patterns that may signify illicit commodity transfers.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Provides granular records of carbon credit trades, including timestamps, volumes, counterparties, and transaction values.
- Enables cross-referencing trade data with financial transaction logs to detect discrepancies, high-velocity trades, or patterns indicative of layering and tax fraud.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Contains detailed records of commodity trades, including quantities, dates, parties, and prices.
- Validates the legitimacy of buy/sell patterns and repeated shipments in FTZs.
- Aids in detecting contrived trade cycles or inflated/deflated pricing schemes used for layering illicit funds.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Provides detailed records of gold trades, including transaction amounts, volumes, types (physical or digital gold), counterparties, and timestamps.
- Facilitates detection of repeated, structured, or mixed-mode gold transactions (physical and digital) and short holding periods that can signal layering or integration.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Contains records of diamond purchases, sales, or exchanges, including transaction dates, parties, quantities, valuations, and references.
- Allows investigators to confirm whether declared transactions align with legitimate commodity trading patterns, assisting AML detection in trade finance scenarios.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Provides detailed records of commodity trades (e.g., transaction dates, parties, commodity types, quantities, and prices). By comparing these records with shipping documents and declared values, investigators can detect over- or under-invoicing, hidden buyers or sellers, and other irregularities commonly used to conceal smuggling or misrepresent the true value of goods.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Captures transaction-level details for commodity trades, including the type of commodity, quantities, prices, dates, and counterparties.
- Supports verification of declared oil volumes, ensuring alignment with actual sales or exchanges.
- Helps detect misrepresented or inflated oil transactions, a key risk in trade-based money laundering schemes.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Captures actual commodity purchase/sale records, including volumes, prices, and counterparties.
- Enables direct comparison of real commodity trades with invoiced details to detect inflated or underpriced entries.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — Provides detailed records of commodity trades, including transaction dates, parties involved, commodity types, quantities, and purchase prices. By comparing actual commodity transaction data against shipping documents or invoices, investigators can detect fabricated or mismatched trade flows indicative of fictitious cross-border deals.

---

## [Politically Exposed Persons (PEP) Lists](https://framework.amltrix.com/data-sources/DS0002)

**Description:**
Databases detailing individuals holding prominent public or political positions, including their official roles, associated entities, and known affiliations.

### Related Techniques
- [Trust-Based Obfuscation](https://framework.amltrix.com/techniques/T0088.002) — - Identifies whether trust beneficiaries, trustees, or associated beneficial owners are PEPs.
- Highlights increased ML/TF risk when prominent or politically connected individuals are shielded by trusts.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Screen project stakeholders against sanctioned or high-risk individuals who hold prominent public responsibilities.
- Flag Politically Exposed Persons (PEPs) who invest in or facilitate construction contracts without legitimate, verified sources of wealth.
- Assist in evaluating heightened risk factors associated with corruption or abuse of public office in the awarding of government construction projects.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — Provides directories of individuals occupying prominent public roles, their close associates, and known affiliations. Screening applicants against these lists:

- Identifies high-risk or politically connected individuals seeking CBI/RBI.
- Facilitates enhanced due diligence for potentially corrupt or sanctioned officials.

Ensures financial institutions can detect and properly manage higher-risk applications that may exploit citizenship/residency programs for illicit gain.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Provides details of individuals holding public or political roles, including their official positions and affiliations. This data helps identify hidden beneficial owners or proxies who may be politically exposed, triggering enhanced due diligence to uncover concealed ownership or control.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — PEP lists provide details on individuals holding prominent public or political roles and their known affiliations. Cross-referencing donors, intermediaries, or recipients against PEP lists can uncover potential bribery or political influence in campaign donations or lobbying activities, directly supporting AML investigations.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Contains details on individuals in prominent public or political positions, including official roles and affiliations.
- Helps identify potential bribery targets or participants by flagging transactions and relationships involving PEPs, who are at heightened risk of corruption.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Names and known affiliations of individuals holding senior public or political offices and their close associates.  
- AML Use: Identifies whether high-profile or politically influential figures are involved in sports club investments or sponsorship deals, highlighting increased corruption and money laundering risks.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — Identifies individuals holding public or political positions who may be involved in large-scale corruption schemes masked by fictitious consulting. Cross-referencing parties against PEP databases helps expose heightened risk scenarios where corrupt officials channel illicit funds through inflated advisory fees.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Identify individuals holding prominent public or political positions, as well as their close associates.
- Increase risk assessment for high-profile or influential policyholders or beneficiaries.
- Support enhanced due diligence to detect bribery- or corruption-related money laundering risks.

Using PEP lists helps financial institutions ensure proper scrutiny of annuity contracts when politically exposed individuals are involved.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Identifies public officials or individuals in prominent political roles, along with their known affiliations. In corruption scenarios, referencing PEP lists ensures transactions involving these high-risk individuals receive enhanced scrutiny, helping detect potential bribery or kickbacks.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Catalogs individuals holding high-profile public or political roles, along with their known affiliations and designations.
- Helps identify CBI/RBI investors who are PEPs seeking to potentially bypass enhanced scrutiny or exploit alternate citizenship pathways.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Contains records of individuals holding prominent public or political positions and their associated entities.
- Helps identify government officials in oil-rich countries who participate in or facilitate suspicious oil deals.
- Flags potential corruption or bribery risks in manipulated oil and fuel transactions.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Databases identifying individuals in high-profile political or public positions.
- Critical for enhanced due diligence on investment company owners or significant shareholders who may pose elevated corruption and money laundering risks.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Comprehensive listings of PEPs and their associates, including their positions, affiliations, and risk designations.
- Ensures enhanced due diligence for high-risk PEPs involved in junket-related transactions, mitigating corruption and money laundering risks.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Includes data on individuals who hold (or have held) prominent public or political positions, along with known affiliations.
- Reveals if MSB owners, directors, or connected parties are PEPs, raising corruption and high-risk flags.
- Assists investigators in prioritizing scrutiny of MSBs potentially controlled or influenced by high-risk or politically exposed actors.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Maintains databases of individuals in prominent public or political positions.
- Alerts financial institutions to heightened corruption risks, including potential collusion with wildlife trafficking networks.
- Enables closer scrutiny of transactions involving PEPs linked to wildlife transport permits or regulatory approvals.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Lists individuals holding senior public or political roles, including known positions and affiliations. Screening against these lists helps detect high-profile or corruption-related risks when significant business investments originate from politically exposed persons (PEPs).
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Includes information on individuals holding prominent public or political roles, their known associates, and relevant designations. This data source aids investigations by flagging newly appointed bank directors or executives who are PEPs or linked to criminal networks, which could potentially signal organized crime infiltration.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — PEP lists typically include names, government or political roles, associated entities, and known affiliations. By comparing awarding officials or beneficial owners against these lists, organizations can detect potential conflicts of interest, corruption, or collusive practices involving public officials in manipulated tenders.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Provides profiles of individuals in public or political positions, including their official roles, known affiliates, and associated risk factors.
- Enables identification of officials or close associates who may be diverting public funds, thereby focusing investigations on potential corruption.
- Cross-checking PEP status with suspicious financial movements helps reveal misappropriation schemes and triggers enhanced due diligence where warranted.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — PEP lists typically include:

- Official roles or political functions, affiliations, and known associates.
- Personal identification details (e.g., name variations, dates of birth).

This data helps detect potential conflicts of interest or corrupt collusion if relief program disbursements or approvals involve individuals in positions of power, supporting investigations into government relief fraud schemes.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — PEP lists typically include names, official roles, known affiliations, and relevant political or diplomatic positions. This data allows for the identification of diplomatic or state-related figures with potential immunity claims or official privileges, aiding in the detection and investigation of suspicious activity involving diplomatic channels.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Lists high-ranking public officials and other individuals who may present heightened corruption or money laundering risks. Checking insurance policy owners or beneficiaries against PEP lists helps uncover politically connected parties exploiting offshore insurance schemes.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Databases of individuals in high-level public or political roles often include aliases or variant spellings. Comparing customer names against PEP lists helps institutions uncover concealed PEP status that may arise from deliberate name alterations.

---

## [Financial, Business & Tax Records](https://framework.amltrix.com/data-sources/DS0007)

**Description:**
Documentation and official filings covering an entity's financial activities, including balance sheets, profit-and-loss statements, tax returns, and related records. Typically referenced to evaluate an entity's financial stability, verify reported performance, and identify discrepancies or anomalies in financial profiles.

### Related Techniques
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Discloses officially filed financial statements, tax returns, and related documents. Used to identify mismatches between reported revenues and large amounts funneled through hawala channels, indicating potential illicit activity.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Covers audited statements, tax returns, and related filings indicating actual revenues, expenses, and operational capacity.
- Reveals overstated or falsified financials used to secure subsidized loan terms or justify larger loan amounts.
- Uncovers discrepancies between reported and true performance, flagging fraudulent activity in loan applications.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Includes financial statements and tax filings documenting revenues, expenses, and payroll costs. Comparing these disclosures with known industry benchmarks can reveal underreported wages or hidden profits associated with forced labor practices.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Contains balance sheets, profit-and-loss statements, tax filings, and related financial documentation for property management or real estate entities.  

- Enables cross-verification of declared operational income, rental revenue, and reported expenses against actual transaction flows, identifying discrepancies or inflated figures that suggest commingling.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Encompasses financial statements, tax filings, and profit-and-loss reports.
- Reveals discrepancies in reported valuations or manipulative accounting practices.
- Assists investigators in verifying whether reported corporate finances match real economic activity.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Holds financial statements, profit-and-loss reports, and tax filings for entities.  
- Enables validation of reported income or expenses against actual business performance, highlighting potential fraud.  
- Helps spot discrepancies in revenues or asset flows that do not align with ordinary business operations, revealing artificial inflation or false documentation.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Provides insight into the normal operating revenues and reported financials of clubs or sponsoring entities.
- Enables comparison of typical business size to sponsorship sums, highlighting disproportionately large or unjustified sponsorship payments that may indicate laundering.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Provides official financial statements, accounting records, and tax filings that can confirm or refute the legitimacy of reported liabilities. Facilitates cross-checking payables entries with declared expenses and verifying the authenticity of vendors or creditors. Supports identifying fabricated or inflated liabilities that do not match the entity’s operational or financial profile.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Offers insight into declared revenues, tax filings, and corporate financial statements.
- Assists in detecting inconsistent VAT returns or questionable tax refund claims associated with carbon credit carousel schemes and advanced layering techniques.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Includes official financial statements, tax returns, and detailed business performance metrics.  
- Facilitates comparison of reported operating margins, revenues, and geographic coverage against industry norms to detect anomalies common in front company setups.
- [Funnel Accounts](https://framework.amltrix.com/techniques/T0083) — - Includes official financial statements, business filings, and tax returns.
- Validates whether sudden cross-border transfers or funnel deposit patterns align with legitimate financial activity, uncovering concealed or illicit proceeds.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — Comprehensive financial statements, tax returns, and related filings demonstrate a vendor’s operational legitimacy. Cross-referencing reported business income, expenses, and tax liabilities helps uncover vendors with no genuine operational footprint, indicating a likely fake vendor setup.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Covers profit-and-loss statements, balance sheets, and tax returns, enabling verification of reported income and expenditures. In corruption probes, this data reveals hidden revenue streams, sham businesses, or inconsistencies suggesting kickbacks or embezzlement.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — Contains formal financial statements, tax returns, and business filings detailing labor costs, revenues, and workforce information. This enables investigators to compare declared payroll expenses against official tax declarations, identify discrepancies (e.g., inflated wages), and uncover ghost or phantom employees by analyzing potential mismatches in reported labor costs and actual tax or financial records.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Contain an entity’s financial statements, tax filings, and business performance data, enabling investigators to compare declared beneficial ownership structures against reported revenues, expenses, and tax obligations. This comparison helps identify inconsistencies that may indicate ownership manipulation.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Covers tax filings, balance sheets, and other official business financials.
- Supports cross-referencing declared figures with internal records, uncovering manipulations or missing entries indicative of tampering.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Provide official filings such as tax returns, balance sheets, and profit-and-loss statements.
- Corroborate a policyholder’s declared financial capacity and sources of funds.
- Reveal discrepancies between reported earnings or assets and large annuity contributions.

These records help confirm the legitimacy of funds used for annuity purchases and detect potential misrepresentation or laundering of illicit proceeds.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Provide official filings such as financial statements, profit-and-loss reports, and tax returns of clubs and intermediaries.
- Permit verification of declared endorsement or licensing revenues against actual commercial activities, uncovering discrepancies.
- Detect potential tax irregularities and unsubstantiated income streams, indicative of inflated fees or nonexistent commercial exploitation tied to image rights deals.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Includes financial statements, tax returns, and other official filings.
- Reveals discrepancies between reported business activities and actual financial performance.
- Highlights a lack of genuine revenue or operational expenses, suggesting shell-type structures.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Official financial statements, tax returns, and related filings reflect reported revenues, expenses, and liabilities.
- Help identify inconsistencies or manipulations in recorded figures by cross-checking against actual business transactions and historical filings.
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Includes official financial statements, profit-and-loss records, balance sheets, tax returns, and other formal business documents. This data:

- Allows cross-checking of declared income against actual transaction histories to uncover underreported earnings.
- Identifies significant gaps between reported revenue and observed cash inflows, indicating possible undeclared funds.
- Provides insight into discrepancies within accountant-verified statements, aiming to detect complicit behavior in underreporting.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Contains financial statements, corporate filings, and tax returns, revealing a business’s revenue streams, expenses, and overall financial health. It can confirm the absence of legitimate income supporting significant "storage fees" or inconsistent flows from multiple shell entities to the same private storage facility.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Provides official filings and statements (e.g., balance sheets, tax returns, profit/loss statements).
- Reveals discrepancies in reported revenue or business operations for companies suspected of concealing proceeds.
- Assesses the legitimacy of cash flows from sectors prone to environmental crime (e.g., timber or fishing).
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Provides official filings such as tax returns, profit-and-loss statements, and balance sheets.
- Enables detection of discrepancies between stated and actual revenues, identification of misclassified expenditures, and confirmation of reported taxable income.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Covers an entity’s financial statements, tax filings, and business performance disclosures. Investigators can compare the project's claimed business model with actual filings to uncover discrepancies, which are frequent indicators of exit scams and rug pulls.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Official financial filings, tax returns, and business statements are essential documents. Cross-referencing these records against relief program submissions can uncover discrepancies in reported revenue or operational scale, helping to expose misrepresentations used to qualify for government funds.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Contains official tax returns, financial statements, business registrations, and related filings.
- Allows cross-verification of claimed operating losses or payroll data used in relief applications.
- Helps detect inflated or inconsistent financials that deviate from historical filings, indicating potential fraud or misrepresentations.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Contains official financial statements, tax returns, and supporting business filings.
- Enables comparison of reported turnover and VAT returns against actual documented income and expenses.
- Detects discrepancies and anomalies indicative of carousel fraud, such as inflated or repetitive VAT refund claims.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Contains an entity's or individual's financial statements, tax returns, and other filings. By comparing declared financial capacity with large premium payments or policy redemptions in offshore schemes, anomalies indicating laundering or layering can be detected.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Encompasses official financial statements, tax returns, and supporting business documentation. By reviewing details such as journal entries, balance sheets, and tax filings, investigators can spot irregular accrual entries, retroactive revenue adjustments, or unjustified reclassifications, all of which are hallmarks of accrual manipulation.
- [Temporary Shell Companies](https://framework.amltrix.com/techniques/T0001.002) — - Includes official financial statements, tax returns, and related filings.
- Reveals limited or fabricated financial footprints, indicating potential fictitious activity.

This data underpins the identification of shell companies formed briefly for illicit transactions or fraudulent tax schemes.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Provides official financial statements, tax filings, and business registrations detailing actual revenue, operational capacity, and corporate purpose.
- Enables comparison of declared foreign capital injections against an entity’s legitimate financial profile to pinpoint discrepancies or lack of genuine commercial rationale.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Covers official financial statements, tax returns, and corporate filings that outline an entity’s financial performance and obligations.
- Assists investigators in verifying actual financial capacity and legitimate sources of capital purportedly used to meet CBI/RBI thresholds.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — Provides official financial statements, tax returns, and related filings that help verify declared consulting revenues, operational expenses, and tax compliance. These records enable analysts to detect discrepancies in reported income, identify artificially inflated fees, and confirm whether criminals are using timely tax payments to appear more credible while concealing illicit proceeds.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Covers official financial statements, tax returns, and declarations of income or expenses. Comparing reported farm revenues and declared operating costs with subsidy requests can reveal inconsistencies that indicate fraudulent subsidy claims.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Official filings such as balance sheets, tax returns, and profit-and-loss statements.
- Helps compare the financial capacity of parties with the settlement amounts claimed in arbitration, identifying disproportionate or dubious awards.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Details an entity’s historical financial statements, declared tax information, and reported business activities.
- Allows investigators to uncover discrepancies between the borrower’s actual capacity and the inflated loan amounts or trade volumes claimed in syndicated loan agreements.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Includes entities’ financial statements and tax filings, offering insights into reported revenue, operating expenses, and overall financial health.
- Enables cross-verification of declared renovation costs against actual financial capacity and reported expenditures, highlighting discrepancies indicative of potential laundering.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Includes official filings such as profit-and-loss statements, balance sheets, tax returns, and comparative valuations for similar entities. Investigators can verify declared purchase prices, revenue, and expenses against standard benchmarks or historical data, identifying overvalued or undervalued acquisitions or overstated profits used to mask illicit funds.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Includes official tax returns, financial statements, and historical filing data.
- Compares declared income, reported business performance, and past filing patterns against refund claims.
- Detects discrepancies, elevated refund amounts, or unusually frequent filing cycles linked to fraudulent tax rebates.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Includes official filings such as tax returns, balance sheets, and profit-and-loss statements.
- Enables comparison of declared income or business revenues against high-value foreign real estate purchases.
- Supports analysis of financial inconsistencies or anomalies indicative of money laundering activity through offshore property ownership.
- [Rental Income Schemes](https://framework.amltrix.com/techniques/T0010.004) — - Provides official financial statements, tax returns, and other filings indicating declared rental income.
- Allows comparison of reported rental revenue with actual deposit data or property ownership records to expose inconsistencies or evidence of laundering.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Official filings and historical financial documents (e.g., tax returns, profit-and-loss statements).
- AML Relevance: Confirms whether declared wages and business income match legitimate financial history and tax data, helping detect forged or overstated wage records.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Official financial statements, profit-and-loss reports, tax returns, and business filings showing the club’s broader financial health.
- AML Utility: Enables cross-checking declared revenues from sponsorship, ticket sales, or transfers against verified financial disclosures, revealing inconsistencies that may indicate inflated income or laundered funds.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Contains official filings, tax returns, balance sheets, and profit-and-loss statements. Reviewing these documents helps confirm or refute an entity’s claimed investment performance and financial stability, flagging inconsistencies indicative of fraudulent activities.
- [Cash Wage Payments to Undocumented Workers](https://framework.amltrix.com/techniques/T0052.001) — - Documents reported financial statements, including wage expenses, payroll taxes, and business income.
- Allows investigators to compare official wage expenditures against actual cash outflows, revealing concealed labor expenses for undocumented workers.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Provide audited or official financial statements and filings. Investigators compare these records to internal transaction data or user-uploaded documents to detect mismatched balances, manipulated entries, or fabricated invoices.
- [Dividend Stripping](https://framework.amltrix.com/techniques/T0147.003) — Contains official tax filings and financial statements revealing multiple or duplicative reimbursement claims for the same dividend. Cross-referencing this information with trading data helps uncover fraudulent dividend stripping schemes.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Consolidates balance sheets, profit-and-loss statements, and official tax filings.
- Verifies reported revenues, operating expenses, and agricultural yields against declared financial data to detect inconsistencies.
- Identifies inflated or false financial statements used to disguise illicit funds as legitimate agribusiness income.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Official filings such as tax returns, balance sheets, and profit-and-loss statements.
- Comparative analysis can reveal discrepancies between an investment company’s reported activities and its actual financial operations, signaling possible laundering or false reporting.
- [All-Cash Real Estate Transactions](https://framework.amltrix.com/techniques/T0010.005) — Offers official financial statements, tax returns, and business records to cross-verify declared income or assets with large all-cash real estate purchases, enabling the detection of unsubstantiated funds or unexplained wealth.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Covers official financial statements, tax returns, and business filings detailing revenues, expenses, and profit/loss.
- Enables cross-referencing of declared transfer pricing, royalty fees, or management fees with actual financial performance and tax filings to spot potential under-reporting or inflated rates.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Supply official financial statements, tax returns, and other business filings to compare actual revenues, capacity, and tax claims.
- Cross-check claimed export-related refunds or sudden revenue spikes against reported sales data and industry benchmarks to identify potential overvaluation.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Comprises official financial statements, profit-and-loss reports, and tax filings.
- Reveals discrepancies between reported sales and declared income, helping identify fabricated or overstated revenue streams.
- Corroborates or contradicts claims of legitimate commercial activity through comparison with operational capacity and transactional records.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — These records disclose official financial statements, tax returns, and business performance data. By cross-referencing declared investment returns with official filings, investigators can detect inconsistencies that indicate manipulated valuations or fabricated performance. This helps confirm whether real operational data aligns with the reported fund performance, revealing potential misrepresentations or false returns central to investment fund manipulation.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Covers official financial statements, reported business income, and tax filings, enabling the detection of discrepancies between declared revenues and significant capital injections. Investigators can identify suspiciously high investments that lack clear justification and verify alignment with legitimate business performance.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Includes official filings and statements regarding revenue, taxes, and overall financial performance.
- Reveals whether reported cigarette revenues align with paid excise or import duties, helping to detect undeclared or underreported tobacco imports.
- Uncovers discrepancies in tax filings or business revenues that could indicate proceeds from smuggling operations.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Contains official financial statements, tax returns, and related disclosures for institutions and businesses. This data assists in detecting infiltration by identifying inconsistencies between reported bank financials and actual transaction volumes, suggesting that criminal insiders may be manipulating records to conceal illicit activities.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Includes official financial statements, tax filings, and payroll records for a given entity.
- Allows cross-referencing declared payroll liabilities and withholdings against actual reported headcounts and remuneration to detect potential underreporting.
- Supports AML investigations by revealing discrepancies or anomalies in tax and financial disclosures, indicating possible payroll tax evasion activities.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Contains official filings such as audited financial statements, operating expenditures, tax returns, and related documentation.
- Reveals discrepancies between reported charitable expenditures and actual donation inflows, indicating potential misappropriation.
- Aids investigators in matching the declared financial activity of non-profits against the real usage of funds.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Include tax returns, financial statements, and official filings of revenue and expenses.
- Comparing reported payroll expenses and tax liabilities with observed cash wage payouts helps detect under-reported income or hidden wage distributions.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Includes balance sheets, profit-and-loss statements, and tax filings. Reviewing these records can uncover inconsistencies or a complete absence of legitimate financial documentation, which may indicate online-only or fictitious corporate entities.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Includes official financial statements, tax filings, and detailed business expense records. 

- Detects discrepancies between reported income and actual cash deposits that may signal extortion.
- Highlights unexplained or excessive expenses aligning with protection payment demands.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Review audited financials, tax returns, and reported revenue to validate the insurer’s legitimate business scale.
- Detect discrepancies or unusually rapid growth in assets, mismatched premiums versus claims, and large tax write-offs suggesting laundering via inflated premiums or bogus claims.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Official financial statements and tax filings (e.g., tax returns, audited financials) verify an individual’s or entity’s declared income sources, wealth levels, and tax obligations. This data helps detect discrepancies between reported finances and large or frequent pension contributions, identifying potential illicit fund injections, layering, or unexplained rollovers within pension schemes.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Contains audited financial statements, profit-and-loss reports, and filed tax returns.
- Assists in identifying revenue inconsistencies, such as reported earnings far exceeding plausible operational capacity.
- Reveals discrepancies between declared jewelry sales and external market or transactional evidence.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Contains official financial statements, tax filings, and business registrations.
- Supports verification of claimed production budgets, event expenses, and sponsorship income in entertainment ventures.
- Identifies discrepancies between reported income and actual tax declarations or listed expenses that may indicate laundering.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Contains official filings of earnings, taxes, and business revenues. Cross-referencing these records with substantial bond returns helps detect discrepancies, such as significantly higher interest income than reported income, suggesting potential laundering using bond instruments.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Includes financial statements, profit-and-loss records, and tax filings.
- Compares declared consulting revenues with operational capacity or industry benchmarks.
- Identifies unsubstantiated or over-inflated revenue claims intended to legitimize illicit funds.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Documents an entity’s financial statements, business performance, and tax filings, revealing discrepancies between declared production volumes and actual revenues. This helps detect undeclared or underreported income linked to illicit mineral sales.

---

## [Digital Banking & Cybersecurity Event Data](https://framework.amltrix.com/data-sources/DS0008)

**Description:**
Information about online and mobile banking activities, including IP logs, device usage patterns, unauthorized access attempts, transaction anomalies, and related cybersecurity events.

### Related Techniques
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Provides IP logs, device usage patterns, login timestamps, and alerts on suspicious behavior.
- Helps detect unusual login patterns, rapid address changes, or dispersed wallet usage indicative of potential money laundering through self-hosted wallets.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — - Tracks device attributes such as operating system, time zone, language settings, and user-agent details.
- Helps identify suspicious session anomalies or rapid changes in device fingerprints consistent with rotating proxy usage.
- Strengthens AML investigations by flagging inconsistent device characteristics originating from potentially anonymized connections.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Includes IP logs, device usage patterns, and alerts on unauthorized access attempts within online banking portals.
- Assists in detecting compromised accounts, unusual login activity, or cybersecurity incidents correlating with the fraudulent redirection of educational institution payments.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Captures IP addresses, device identifiers, and login timestamps across online and mobile trading platforms.
- Enables detection of multiple trading accounts accessed from the same device or location, helping to uncover coordinated or collusive trading patterns.
- Highlights suspicious or unauthorized login attempts, supporting the identification of orchestrated manipulation using advanced electronic trading channels.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Logs and analyzes account access patterns, device fingerprints, and profile modification events. Excessive or repeated alterations to personal details after account opening can indicate identity manipulation efforts or account takeovers.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Captures IP addresses, device fingerprints, and session details for online banking, helping identify the repeated use of the same device or IP to deposit checks into multiple accounts under different names. This supports AML investigations of remote deposit capture abuse and potential collusive activity.
- [Bank Infrastructure Manipulation](https://framework.amltrix.com/techniques/T0132) — - Captures patch deployment history, vulnerability scans, and intrusion attempts, revealing gaps where core systems may be exploited.
- Logs cybersecurity events, such as suspicious network traffic or repeated failed authentication attempts, indicating potential compromise of bank infrastructure.
- Helps link unpatched software vulnerabilities to observed manipulations of AML or transaction monitoring systems.
- [Peer-to-Peer (P2P) Transfers](https://framework.amltrix.com/techniques/T0134.001) — Captures IP addresses, device identifiers, and other technical details, enabling the detection of overlapping user fingerprints across supposedly unrelated P2P accounts.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Logs authentication events, device fingerprints, and IP addresses. This data helps detect multiple or unexpected devices accessing newly opened accounts, indicating possible external control or 'mule herding,' which is commonly seen in money mule recruitment.
- [Anonymous Networking](https://framework.amltrix.com/techniques/T0015) — - Provides IP logs, device usage patterns, and connection details for each online banking session or transaction.
- Enables monitoring and flagging of repeated access attempts from known anonymizing networks (e.g., Tor exit nodes, VPN endpoints).
- Assists investigators in correlating suspicious IP usage or rapid geolocation changes to detect potential misuse of anonymity tools and mitigate laundering risks.
- [Mobile Payment Systems](https://framework.amltrix.com/techniques/T0134.002) — Includes IP addresses, device identifiers, and geolocation data for mobile payment platforms. This data allows for the detection of device or geographic anomalies, such as multiple wallet registrations from the same device or IP address mismatches. It supports the investigation of layered account usage, cross-border activities, and rapid fund transfers.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — Collects device fingerprints, IP addresses, login timestamps, and other cybersecurity signals within digital banking channels. Correlating these with suspicious voice-based transactions helps uncover deepfake impersonation by spotting anomalous device or network usage.
- [Virtual Private Network](https://framework.amltrix.com/techniques/T0015.001) — - Captures online banking events, including IP usage, device fingerprints, and account access details.
- Identifies consistent VPN usage in account opening or management activities.
- Supports AML investigations by correlating suspicious login methods with KYC records to detect potentially hidden user locations.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Tracks failed login attempts, device fingerprints, and suspicious cybersecurity events (e.g., flagged IPs, unauthorized login alerts).

- Supports the detection of compromised accounts by revealing repeated access attempts, new device usage, or known malicious IP indicators.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Includes records of software usage, transaction anomalies, and unauthorized access attempts. Investigators identify unapproved plugins or scripts used to manipulate transaction data in real-time, bypassing standard logs.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Monitors account creation and closure patterns, revealing rapid account turnover potentially linked to transient mining operations.
- Tracks anomalous login attempts or suspicious device usage associated with mining payment flows.
- Flags repeated or coordinated account activities that may facilitate the layering of illicit proceeds through multiple digital channels.
- [Test Payment Probing](https://framework.amltrix.com/techniques/T0035) — - Tracks user session information, IP logs, and transaction status changes, highlighting repeated initiation and quick cancellation of small transactions used to gauge thresholds.
- Supports investigation of abnormal login patterns and rapid reversals, suggesting deliberate testing of AML controls.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Track device fingerprints, IP addresses, and session metadata to identify repeated usage patterns across supposedly distinct accounts.
- Detect anomalies in remote onboarding or login behavior to indicate potential impersonation or account takeover.
- [Remote Verification Bypass](https://framework.amltrix.com/techniques/T0135) — - Captures IP addresses, device usage patterns, and authentication attempts, enabling the detection of multiple remote account creations from the same device or IP range.
- Identifies the use of proxies, VPNs, or other anonymizing services during account registration or verification.
- Monitors aborted verification procedures followed by immediate re-attempts under new credentials or data, helping to reveal suspicious patterns indicative of remote verification bypass.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Encompasses IP logs, device usage patterns, and login activity for online and mobile platforms. In lottery schemes, this data:

- Detects geographically dispersed IP addresses or multiple devices used for lottery ticket purchases.
- Flags unusual account access patterns linked to suspicious ticket-buying or prize-redemption activity.
- Supports investigation of compromised or third-party account usage.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Monitors IP addresses, device fingerprints, and network activity for digital banking sessions.
- Identifies inconsistencies between a customer’s claimed location and the actual device or network attributes, revealing possible fake identities or impersonation.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — Captures IP addresses, device fingerprints, and usage patterns in online banking environments. It reveals multiple account creations from the same device or IP address and detects anonymizing tools such as VPNs and proxies. This data helps identify unusual remote onboarding behaviors consistent with online identity deception.
- [Public WiFi Networks](https://framework.amltrix.com/techniques/T0015.003) — - Provides IP logs, device usage patterns, and session metadata from online and mobile banking channels, revealing whether connections originate from public, potentially unsecured hotspots.
- Identifies VPN or proxy usage layered on public WiFi, helping detect deliberate obfuscation of user location and identity.
- Correlates multiple session logs to expose suspicious simultaneous or rapid-sequence logins from disparate public IP addresses, indicating potential coordinated misuse.
- [Onion over VPN](https://framework.amltrix.com/techniques/T0015.005) — - Records login attempts, authentication failures, and suspicious device/browser fingerprints.
- Highlights anomalies in user session patterns (e.g., sudden IP address changes, usage of known anonymizing IPs).
- Assists in correlating frequent or failed logins through Tor/VPN networks with potential illicit activity masked by multi-layered encryption.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Encompasses cybersecurity alerts, malware detections, unauthorized access attempts, and suspicious system events.
- Uncovers malicious code or anomalies specifically designed to alter or erase transaction records.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Tracks IP addresses, device fingerprints, and account creation patterns to identify coordinated or high-risk activities in offshore gambling.
- Detects large volumes of new high-value accounts or potential fraudulent access attempts, indicating layering schemes.

These data points assist compliance teams in investigating suspicious digital behavior linked to under-monitored offshore gambling sites.

---

## [Employee Records](https://framework.amltrix.com/data-sources/DS0028)

**Description:**
Comprehensive records of employee identities, roles, and relevant employment details, used to track internal accountability and detect potential conflicts of interest or misconduct.

### Related Techniques
- [Bank Infrastructure Manipulation](https://framework.amltrix.com/techniques/T0132) — - Provide detailed information on employees' identities, roles, and internal privileges.
- Help identify staff with elevated permissions or unusual responsibilities that could facilitate internal system manipulation.
- Support investigations into potential insider collusion or unauthorized overrides of AML controls within the institution's infrastructure.
- [Cash Wage Payments to Undocumented Workers](https://framework.amltrix.com/techniques/T0052.001) — - Maintains comprehensive data on officially registered employees, including their roles, wages, and tax-related information.
- Exposes discrepancies between declared workforce details and the actual labor force observed on-site, highlighting off-the-books payments to undocumented workers.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Encompasses detailed internal HR data on employee identities, roles, wages, and employment status.
- Enables cross-checking of reported employee numbers, compensation amounts, and workforce composition against actual records.
- Supports detection of hidden or misrepresented employees and underreported wages used in payroll tax evasion schemes.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Details employee identities, roles, and employment history. Frequent staffing changes or limited knowledge transfer in key roles, as reflected in these records, may indicate siloed or intentionally constrained awareness of overall transactions.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Cross-check official staff rosters against wage disbursements to reveal non-existent employees or inflated payroll costs.
- Identify discrepancies between declared roles and actual work performed on construction projects.
- Flag large or repeated wage payments to individuals lacking verifiable employment credentials.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Provides official HR data for all employees, including personal details, roles, and employment status.
- Enables cross-checking of payroll recipients against verified employees to identify ghost employees or inflated workforce counts.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Contains identity and employment details for betting shop staff, including roles and responsibilities, enabling the detection of potential staff collusion or conflicts of interest. This data helps investigators confirm whether employees are improperly overriding AML checks or ignoring suspicious betting patterns in exchange for financial gain.
- [Payroll Deduction Loan Repayment](https://framework.amltrix.com/techniques/T0029) — Contains official HR or employer database details, including job position, salary, and employment status, to validate the legitimacy of an individual's payroll deductions. This helps detect fictitious or fraudulent employment arrangements used to obscure illicit loan repayments.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Document employees’ roles, responsibilities, and hierarchical structures.
- Help detect potential collusion or management override in financial recordkeeping by identifying individuals with the authority to alter accrual entries or bypass internal controls.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Contains detailed information on employees, including identities, roles, and wages. These records can reveal inconsistencies in reported payroll expenditures, such as underpayment or 'ghost' employees, commonly seen in forced labor operations. Cross-referencing employee rosters with actual labor output helps detect exploitation.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Contains data on employee identities, roles, salaries, and employment status.
- Comparing actual staffing levels with reported payroll outlays can expose ghost employees or inflated headcounts, revealing off-the-books payments indicative of potential money laundering or tax evasion.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Contains official HR or payroll data confirming employee identities, roles, and workforce size.
- Validates or refutes exaggerated payroll or headcount claims made to justify inflated relief amounts.
- Helps detect nonexistent employees or erroneous workforce records used to secure larger disbursements.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Document staff roles, responsibilities, and authority levels. Investigators determine whether a single individual has the ability to create, approve, and modify digital transactions, uncovering insufficient segregation of duties that enables manipulation.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Contain identities, roles, and employment history of staff entrusted with managing or approving public fund disbursements.  
- Identify anomalies such as a single individual holding uncommonly broad financial authority or refusal to follow mandatory leave policies, possibly hiding ongoing embezzlement.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Provide details of employee identities, roles, and payroll data.
- Help identify false or suspicious wage payments, non-existent employees, and underreported labor in potential forced-labor fronts.
- Enable cross-checking payroll expenses against actual workforce operations to detect exploitation patterns.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Contains employee roles, salaries, and job responsibilities, enabling cross-referencing of claimed expenses with typical job-related outlays. This helps identify employees filing excessive or anomalous reimbursements and potential collusion, such as multiple employees submitting identical receipts.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Contains comprehensive details on employees, including positions, hire dates, qualifications, and role changes. This data helps detect infiltration by revealing rapid or repeated shifts in senior management or the appointment of unqualified personnel, both of which can signify that criminals are placing loyal individuals in key decision-making roles.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Include details of employees’ roles, responsibilities, vacation history, disciplinary actions, and training records.  
- Allow detection of employees who avoid taking leave to hide illicit activities or who have prior compliance issues suggesting high insider risk.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Maintains employee identities, roles, compensation, and leave patterns.
- Facilitates the detection of unusual increases in personal wealth, refusal to delegate tasks, and other potential red flags of bribery or corruption.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Contains detailed staff employment data, roles, and affiliations within the financial institution.
- Reveals potential conflicts of interest or unusual staff assignments that could facilitate illicit activities.
- Supports internal investigations to identify complicit employees who may manipulate compliance measures or reporting processes.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Maintains comprehensive employment data, including the number of staff, roles, payroll information, and dates of employment.
- Validates whether a call center’s reported workforce aligns with the revenue they claim, revealing potential exaggerations or fictitious staff listings.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Comprehensive details on employee identities, roles, and employment history.
- AML Relevance: Validates legitimate employee information and helps expose fraudulent or nonexistent employees that are central to the scheme.

---

## [Product & Service Usage Data](https://framework.amltrix.com/data-sources/DS0010)

**Description:**
Consolidated data on how customers utilize financial products and services, including usage frequency, transaction volumes, product types, and related usage metrics.

### Related Techniques
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Details how accounts utilize financial products and services, including usage frequency, transaction volumes, and service types.

By comparing typical diplomatic mission usage with actual activities, investigators can detect anomalies, such as personal expenditures or sudden spikes in service usage, pointing to potential misuse of diplomatic privileges.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Shows how insurance policies are utilized, including the frequency of claims, early cancellations, or unusual usage patterns.
- Reveals abnormal usage such as short policy durations, large refunds, or partial surrenders, indicating potential manipulation.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Consolidates information on a customer's typical usage patterns and transaction volumes across financial products.
- Helps identify anomalous spikes in product usage (e.g., sudden or repeated purchases of expensive goods) that may indicate laundering via high-value asset transactions.
- [Undisclosed Payment Aggregation](https://framework.amltrix.com/techniques/T0138) — - Documents the normal range and frequency of product or service usage (e.g., transaction size, refund rates) under typical merchant conditions.
- Highlights anomalies such as unusual spikes in refund or credit activity and repetitive small incoming payments without legitimate rationale.
- Enables investigators to spot funneling or structuring tactics designed to commingle illicit proceeds with normal merchant transactions.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Shows how accounts engage with the gaming platform (e.g., login frequency, game progression, social interactions). Comparing normal user behavior against accounts focused on frequent digital asset trades without genuine gameplay helps detect laundering in virtual worlds.
- [Remote Deposit Capture](https://framework.amltrix.com/techniques/T0117) — Tracks customer usage patterns across financial products, including remote deposit capture, detailing sudden shifts in deposit channel preferences or high-value check deposits. Such data aids AML detection by identifying anomalous RDC usage and deviations from expected customer behavior.
- [Insurance Policy Overfunding](https://framework.amltrix.com/techniques/T0090.002) — - Monitors multiple insurance product purchases under a single customer account and subsequent early redemptions or cancellations.
- Identifies unusual usage timelines, such as policy cancellations soon after purchase, which are inconsistent with normal policy life cycles.
- Tracks changes in beneficiary details shortly before disbursement requests, potentially indicating layering attempts.
- Highlights customer willingness to incur financial penalties or fees for quick withdrawals, suggesting laundering through policy surrenders.
- Reveals cross-institution or historical patterns of repeated purchase-and-redeem cycles, indicating systematic money laundering behavior.
- Captures customer focus on early redemption terms, signaling potential misuse of flexible insurance products.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Details how a business or account holder utilizes specific financial products and services, including usage frequency and transaction methods. This helps identify investments made predominantly in cash or through opaque channels that deviate from sector norms.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Tracks the lifecycle of insurance products, including policy inception, premium schedules, and early surrender events.
- Identifies patterns of frequent or early surrenders, highlighting potentially illicit layering or integration through seemingly legitimate insurance payouts.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Consolidates customer usage patterns across financial products and services.
- Highlights sudden or unusual increases in collectible auction activity by customers not previously engaged in such trading.
- Detects abrupt shifts in usage volumes that may signify layering or integration of illicit funds under the guise of collectible transactions.
- [Loyalty Points](https://framework.amltrix.com/techniques/T0106) — Tracks historical usage patterns of loyalty programs, including normal accumulation and redemption behaviors, enabling the detection of sudden changes in point usage volume or frequency. This helps uncover abrupt increases or rapid redemptions commonly associated with the layering of illicit funds through loyalty schemes.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Monitors changes in an entity’s product or service lines to newly introduce offshore gambling.
- Tracks usage frequency and transaction volumes tied to gambling services, detecting anomalies or sudden spikes.

These insights confirm the legitimacy of declared gambling operations and flag abrupt shifts in business focus indicative of potential money laundering schemes.
- [Financial Product Overfunding](https://framework.amltrix.com/techniques/T0086) — Aggregates detailed metrics on how financial products are actually utilized, including usage frequency, transaction volumes, and product feature engagement. For overfunding schemes, it reveals customers who show minimal legitimate interest and instead focus on rapid, high-volume deposits and early withdrawals, indicating potential laundering.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Provides insights into how customers utilize specific financial products and services, including frequency, volumes, and product types.
- Reveals patterns where foreign exchange or hedging products are deployed gratuitously or at odds with a company’s stated operational needs.
- Aids in flagging customers whose FX usage deviates significantly from their usual business profile, indicating potential manipulation.

---

## [Open-Source Intelligence (OSINT)](https://framework.amltrix.com/data-sources/DS0011)

**Description:**
Publicly available information from websites, social media platforms, news outlets, and public records. This may include user profiles, corporate announcements, and other open data relevant to verifying identities and analyzing associations.

### Related Techniques
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Gleans publicly available information from social media, online forums, and websites to verify personal or business claims.
- Identifies negative news or scam alerts about fraudulent trading platforms promoted in pig butchering.
- Corroborates suspicious relationship-building activities or questionable investment endorsements.
- [Money Mule Exploitation](https://framework.amltrix.com/techniques/T0011) — - Includes publicly accessible data from social media, forums, and websites advertising quick-money schemes or job offers targeting potential money mules.
- Provides insights into mule recruitment networks and communications, enabling analysts to cross-reference online postings with individuals opening new accounts.
- Reveals social media patterns or user interactions that indicate potential involvement in organized mule activities.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Encompasses publicly available data from websites, social media, news outlets, and public records. This information helps identify duplicate product listings, verify inconsistent business claims, and detect newly established websites with suspiciously high transaction volumes or minimal online presence, revealing potential fraudulent e-storefronts.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Collects publicly available data from news articles, social media, corporate announcements, and other open platforms about professional intermediaries. This enables investigators to uncover adverse information, suspicious associations, or regulatory red flags linked to these service providers.
- [Counterfeit Currency](https://framework.amltrix.com/techniques/T0092) — - Aggregates publicly accessible information, including social media posts, online marketplaces, and specialized forums.
- Can reveal possession or advertisement of counterfeiting equipment, suspicious behaviors, or associations not captured in traditional banking data.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Includes public records, website data, and social media posts to verify physical premises and examine the legitimacy of stated operations.  
- Detects inconsistencies when businesses claim active operations at addresses that appear vacant, shared, or virtual, suggesting a possible front.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Gathers publicly available data from the dark web, social media, and other sources, including listings of stolen gaming assets.
- Assists in correlating suspicious in-game items, compromised accounts, or large-scale item theft with potential laundering schemes.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Gathers publicly accessible information from media, websites, and social platforms to confirm affiliations and identify risks.
- Verifies connections between payers and individuals employed by border or port authorities who may be complicit in smuggling.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Aggregate publicly available information on intermediaries or brokers, including websites, social media, and news sources.
- Verify regulatory status and licensing, identifying potential unlicensed or complicit operators.
- Check for negative media coverage, historical sanctions, or collusion.

OSINT investigations support detecting rogue or uncredentialed brokers who may facilitate illicit annuity schemes.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Involves publicly available information from websites, social media, and news outlets.
- Helps confirm whether any genuine promotional or marketing campaigns actually occurred, thereby detecting fabricated or nonexistent sponsorship activities used to launder illicit funds.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Incorporates publicly available information—websites, social media, public records—to verify claimed operations.
- Identifies lack of valid business premises, employees, or other signs of a functional enterprise.
- Corroborates (or refutes) reported commercial activities for shell company detection.
- [Money Mule Recruitment](https://framework.amltrix.com/techniques/T0140) — Collects publicly available information from websites, social media, and online forums to identify suspicious or misleading job postings that promise easy income for transferring funds, a key indicator of money mule recruitment.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Aggregates publicly available data (websites, social media, official announcements) on purported lotteries, timeshares, or inheritance processes.
- Assists in verifying whether advertised schemes are genuine or part of advance fee fraud by uncovering discrepancies or confirming there is no legitimate underlying entity.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — - Provides reference data on known Tor exit nodes, proxy IP addresses, and suspicious hosting services.
- Enables cross-checking of session and transaction IPs against publicly documented anonymizing networks.
- Helps investigators identify IP ranges frequently associated with criminal or high-risk proxy usage, thereby enhancing AML detection and investigation capabilities.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Provides publicly available information on auction house policies and participant identity requirements, uncovering potential gaps in AML controls.
- Identifies private or sealed bidding processes that facilitate anonymity and hinder oversight.
- Supports investigations by revealing unregulated or high-risk auction platforms frequently used to conceal illicit funds.
- [Cross-Chain Bridges](https://framework.amltrix.com/techniques/T0005.002) — - Aggregates publicly available information about decentralized bridge platforms, including KYC policies and user experiences.
- Allows investigators to identify minimal-KYC or non-compliant bridges used to facilitate illicit cross-chain transfers.
- Supports enhanced due diligence by verifying public disclosures (e.g., social media, community forums, platform announcements) around cross-chain services and user activities.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Includes publicly available data from websites, social media, forums, and news outlets. Investigators can detect abrupt project website shutdowns, unverified or anonymous online personas, and social media hype campaigns, which are warning signs of a rug pull. OSINT also helps verify project claims and track online footprints that may reveal fraudulent or rapidly abandoned crypto ventures.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Provides domain registration details, social media, and public postings.
- Enables checks for newly registered or impersonated domains and unrealistic online job adverts.
- Helps identify phishing or scam recruitment tactics pointing to money mule recruitment schemes.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Publicly accessible information from media outlets, websites, and social platforms.

Open Source Intelligence (OSINT) can uncover reports of unusual diplomatic shipments, abuses of immunity, or repeated diplomatic pouch usage to transport financial instruments, aiding investigators in corroborating suspicious activity claims.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Collects publicly available information (e.g., company websites, social media, business directories) to verify vendor legitimacy. Discrepancies between claimed vendors on expense reports and publicly documented entities can reveal shell or non-existent vendors used for fraudulent expense reimbursements.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Aggregates publicly available data from news outlets, social media, and websites to identify reported incidents of artifact theft, looting, or suspicious auctions. This information can verify or refute provenance claims, highlight known smuggling networks, and reveal any publicly documented controversies related to the parties or artifacts.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Identifies cloud-based or remote mining providers widely reported to have negligible KYC or AML controls.
- Correlates negative news, user reviews, or regulatory warnings about mining platforms that bad actors exploit.
- Provides context on emerging trends, enabling investigators to pinpoint newly listed unregulated mining services.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Aggregates publicly accessible data from websites, social media, news articles, and other open records.
- Confirms whether a listed company address is merely virtual or a mailbox service, indicating potential misuse of a shelf company lacking any real operational footprint.
- [Temporary Shell Companies](https://framework.amltrix.com/techniques/T0001.002) — - Verifies the legitimacy of registered business addresses, revealing virtual offices or mail-drop services.
- Corroborates the absence of genuine commercial premises.

This helps confirm ephemeral shell companies that lack a real operational footprint.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Gathers publicly accessible data such as online profiles, social media posts, and scammer blacklists.
- Assists investigators in correlating suspicious account usage or identities with known romance scam masterminds or commonly reported ruses.
- Facilitates cross-referencing of personal details against widely circulated romance scam scripts or flagged recruiter profiles.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Gathers publicly available data from social media and other online platforms regarding campaign details, user aliases, and beneficiary information.
- Enables monitoring of altered or repeatedly re-launched fundraising campaigns, revealing potential deceptive practices in fraudulent social media fundraising.
- [Sexual Exploitation](https://framework.amltrix.com/techniques/T0058.002) — - Gathers publicly available information from websites, social media, and other open data sources.
- Assists in detecting online advertisements or solicitations of sexual services, linking them to illicit financial flows.
- [Anonymous Networking](https://framework.amltrix.com/techniques/T0015) — - Collects publicly available information, including any dark web affiliations, onion addresses, or marketplace references.
- Assists in correlating anonymized financial transactions with reported dark web activities, identifying potential links to illicit marketplaces or hidden user identities.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Publicly available information from social media platforms, websites, and online forums.
- Detects suspicious activities or communications referencing the grooming and exploitation of minors, enabling more targeted financial investigations.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Aggregates publicly available information such as social media updates, domain registrations, corporate announcements, and other online data.
- Validates project documentation and team credentials by comparing them against credible sources and identifying plagiarized materials.
- Detects sudden removal or alteration of websites or social media profiles, signaling potential exit scams or fraudulent conduct.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Gathers publicly available information, such as local building regulations, licensing data, and contractor business profiles.
- Enables verification of contractors’ operational histories and reported construction projects, identifying fictitious or unsubstantiated renovation claims.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Provides publicly accessible data—including social media, press releases, and NGO/grant registrations—that can validate or refute claimed philanthropic activities. In the event of sham NGO or foundation usage within agribusiness or charitable contexts, OSINT helps confirm the absence of genuine charitable operations.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Publicly available information from news outlets, social media, and maritime forums regarding piracy incidents, ransom demands, or facilitators supports investigations by revealing potential networks, negotiation patterns, or newly emerged suspects tied to ransom laundering.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Compiles publicly available information, such as online forums, auction listings, and dealer credentials.
- Supports verification of claimed provenance and valuation for collectibles, detecting inconsistencies or missing documentation.
- Identifies unverified or questionable dealers lacking legitimate track records.
- Cross-references external data to confirm the authenticity of claimed sales or the existence of particular high-value items.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Publicly available information from social media, news outlets, and other open data sources.
- AML Relevance: Helps detect nonexistent or dubious employment histories and spot red flags like fake profiles or inconsistent public records.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Publicly available data from social media, news sources, and other online platforms can confirm or contradict customers' submitted personal details. This information helps identify inconsistencies or evidence of stolen or fabricated identities involved in identity manipulation schemes.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — OSINT involves gathering publicly available information from websites, social media, and other open sources to verify a firm's actual business presence, operational footprint, and staff. These details help identify virtual or shell offices that may indicate a fictitious consulting setup.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Publicly available information, such as player market valuations, club ownership disclosures, media reports on sponsors, and industry analytics.  
- AML Use: Enables cross-referencing public player valuation benchmarks, confirming sponsor legitimacy, and verifying reported attendance figures, helping to detect artificially inflated revenues and questionable sponsor arrangements.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Includes public data from websites, social media, and other open channels, enabling the monitoring of unregulated online marketplaces, suspicious digital advertising, and unverifiable pharmaceutical brand promotion to help detect counterfeit medicine networks.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Includes publicly accessible information from websites, social media, and forums. This data helps scrutinize promotional claims, track abrupt changes in disclaimers, and analyze recruitment tactics used in fraudulent 'guaranteed return' investment schemes.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Collect publicly available information from job boards, social media, and other online platforms.
- Aid in detecting unrealistic recruitment ads, mass unsolicited offers, or suspicious online communication patterns.
- Help verify employer legitimacy and identify posts referencing quick payment processing jobs with minimal skills required.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Includes publicly available information from websites, social media, and news outlets about third-party developers or software tools used for transaction manipulation. Investigators verify whether external parties are offering or facilitating digital document forgery or unauthorized transaction editing.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Aggregates publicly available information (e.g., websites, social media, news) that may reveal unregulated money exchangers, informal networks, or references to off-the-record currency exchanges. By examining this data, investigators can identify key players or brokers facilitating NEP.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Collects publicly accessible information, such as social media, online forums, and web content.
- Identifies discussions or recruitment postings for underground cash courier or informal money-transfer networks.
- Supports AML investigations by uncovering potential relationships or organizational structures that facilitate bulk cash smuggling.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Combines public records, news articles, and local sources to verify actual farming operations or the legitimacy of NGOs/foundations claimed to support agribusiness.  
- Identifies whether agribusinesses exist in remote or non-productive locations and reveals any lack of real activity.  
- Detects potential shell foundations or NGOs by confirming or refuting reported philanthropic or operational activities in the agricultural sector.  
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Aggregates public information from websites, social media, forums, and surface or dark web listings.
- Detects advertisements for precursor chemicals, equipment, and potential leads on supplier or broker networks.
- Assists in investigating suspicious entities and verifying the legitimacy of claimed business operations.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Publicly available information from websites, social media, corporate registries, and news outlets.
- Helps verify the investment company’s stated operations and legitimacy, flagging minimal online footprints or contradictory public information indicative of shell or front entities.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Provides publicly available reference data on market pricing for virtual items, external RMT platforms, and user activities. This supports the detection of inflated or irregular pricing structures and the identification of unregulated marketplaces facilitating cross-platform trades.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Includes information from public websites, social media platforms, and news outlets, which may contain misleading or false statements regarding securities or assets.
- Helps detect pump-and-dump schemes by identifying coordinated promotional campaigns or negative disinformation that artificially manipulates market sentiment.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Publicly available information, including news articles, corporate websites, and social media, can reveal contradictions in a fund’s declared operations, beneficial ownership, or performance claims, potentially exposing manipulative practices.
- [Crowdfunding Campaign Manipulation](https://framework.amltrix.com/techniques/T0044) — - Gathers publicly available data from social media, news outlets, and official campaign pages.
- Assists in validating the authenticity of fundraising narratives by identifying vague or inconsistent details.
- Helps detect multiple campaigns operated by the same entity or overlapping beneficiary information.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Gathers publicly available social media data, online postings, and user reports.
- Identifies suspicious recruitment ads, scam alerts, or negative coverage regarding purported social media 'employers.'
- Correlates the timing of job postings or discussions with observed account activity, supporting direct linkage to money mule schemes.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — - Provides publicly available data on phone numbers, domain registrations, IP addresses, and other digital footprints.  
- Enables verification of newly registered domains or unrecognized phone numbers used in deepfake impersonation attempts, helping flag suspicious contact points not associated with legitimate account holders.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Aggregates publicly available information on custodial mixer operators, including location and regulatory status.
- Assists in identifying mixers operating in jurisdictions with minimal AML oversight or those flagged for illicit activities, thereby supporting enhanced due diligence.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Aggregates publicly available information, such as social media, news reports, and web content, to verify declared ownership structures and identify undisclosed relationships. This process helps uncover adverse media or hidden affiliations that may confirm proxy arrangements.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Publicly accessible information from websites, media outlets, social networks, and industry directories is used to verify whether purported licensing authorities or documents exist and match official references.
- This enables the detection of fabricated credentials or organizations by cross-checking claimed sector compliance against recognized regulatory bodies and published industry standards.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Leverages publicly accessible data sources, such as domain registrations, website content, and contact details, to identify suspicious overlaps or entire absences of legitimate activity associated with virtual enterprises. OSINT can reveal multiple entities sharing identical addresses, phone numbers, or other corporate details, suggesting potential shell setups.
- [Precious Commodity Smuggling](https://framework.amltrix.com/techniques/T0048.003) — - Gathers publicly accessible data from news outlets, social media, and investigative reports.
- Provides insights on private couriers, hidden shipment methods, or emerging smuggling trends related to precious commodities.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Aggregates public data, such as news articles, social media, and publicly available records, on individuals and entities. 

- Verifies if recipients labeled as charity, donation, or membership fee beneficiaries are actually paramilitary or extremist groups demanding protection payments.
- Helps confirm or refute suspicious affiliations not evident in internal banking data.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Verify the physical presence, staff, and operational legitimacy of the captive insurer.
- Uncover external media or public records revealing nonexistent offices, fake claim events, or questionable business backgrounds of key personnel.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Aggregates publicly accessible data such as brand information, corporate announcements, and product authenticity details.
- Allows verification of claims about jewelry origin, quality, or business legitimacy by cross-checking publicly available information.
- Assists in detecting misrepresentations or contradictions in advertised versus actual business operations.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Collects publicly accessible data from websites, social media, and news reports to verify the legitimacy of individuals and agents.
- Uncovers unlicensed intermediaries or suspicious practices in CBI/RBI applications, including inflated fees or questionable accreditation.
- Supports AML detection by revealing the presence of fraudulent or non-compliant advisors and identifying red flags in applicant backgrounds.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — - Consists of publicly available records, including news articles, social media, and official announcements, useful for verifying claimed lobbying activities.
- Allows cross-checking a lobbyist’s or donor’s public profiles, ensuring stated political or advocacy engagements are genuine.
- Detects inconsistencies between reported lobbying expenses and verifiable public events or hearings.
- [Match-Fixing](https://framework.amltrix.com/techniques/T0107.005) — - Aggregates publicly available data from news outlets, social media, and official publications.
- Enables correlation of reported match anomalies or rumored bribery incidents with suspicious betting patterns.
- Supports gathering additional context on participants, events, and potential integrity breaches tied to match-fixing.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Aggregates publicly available data from forums, marketplaces, and social platforms where in-game currency or items might be traded at unofficial exchange rates.
- Helps investigators link accounts or individuals advertising or conducting illicit third-party exchanges, facilitating the detection of unregulated trades.
- [Ponzi Schemes](https://framework.amltrix.com/techniques/T0144.019) — Captures public-facing information on promotional activities, referral campaigns, and network-driven recruitment. This helps reveal the marketing and recruitment patterns typical of a Ponzi scheme and uncovers social media or online platforms used to solicit new investors.
- [Underground Gambling](https://framework.amltrix.com/techniques/T0107.007) — - Gathers publicly accessible information from news outlets, social media, and community forums that may reference unlicensed or underground gambling venues.

- Identifies local reporting on illicit activities, neighborhood complaints, or advertisements for unregulated gambling, supporting investigations into hidden or unregistered operators.

---

## [Trust Information and Accounts](https://framework.amltrix.com/data-sources/DS0012)

**Description:**
Comprehensive information about trusts, including their structure, beneficiaries, trustees, associated financial accounts, transaction histories, and legal documentation. This data helps verify the legitimacy of trust-related activities and confirm the identities of key parties.

### Related Techniques
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Provides details on trust structures, including settlors, beneficiaries, trustees, and related account activities.
- Supports verification of opaque trusts used to mask beneficial ownership in cross-border asset management arrangements.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — Contains in-depth records of trusts, including settlors, trustees, beneficiaries, and related financial accounts. 

- Clarifies ownership structures where trusts are used to hide real estate holdings in foreign jurisdictions.
- Aids in identifying ultimate beneficial owners and detecting potentially suspicious trust arrangements supporting cross-border property transactions.
- [Exploitation of Professional Privileges](https://framework.amltrix.com/techniques/T0033) — Provides detailed records on trust structures, trustees, beneficiaries, and transactional histories. By analyzing the formation and activity of legal trusts, investigators can detect unusual IOLTA or trust account usage and reveal hidden beneficial ownership concealed by professional secrecy claims.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Contains information on trustees, beneficiaries, and trust agreements, helping identify layers of control established by intermediaries.
- Supports verification of whether a trust arrangement is legitimate or used to conceal beneficial ownership.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Offers comprehensive records of trust structures, trustees, beneficiaries, historical amendments, and related financial accounts. Reviewing these details can uncover beneficiary manipulations, repeated changes to controlling parties, and inconsistencies with the stated trust purpose.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Provides details on trust deeds, trustees, beneficiaries, and associated accounts. Professional intermediaries may establish or administer trusts to conceal ultimate ownership, and these records help detect such hidden relationships or unexplained trust activities.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Details fiduciary or mutual trust fund arrangements, including trustees, beneficiaries, and transaction histories.
- Uncovers hidden contributors or pooled funds behind foreign investments, revealing obscured beneficial ownership across multiple participants.
- [Asset Cloaking](https://framework.amltrix.com/techniques/T0009) — - Contains trust deeds, trustee and beneficiary information, and associated financial accounts.
- Helps uncover trust-based layering or private foundations that mask beneficial owners.
- Enables validation of reported trust activities to detect suspicious or undisclosed controlling parties.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Provides comprehensive details on trust structures, including beneficiaries, trustees, associated financial accounts, and transaction histories.
- Helps uncover hidden beneficial ownership or multi-layered corporate vehicles used in multi-jurisdiction arrangements.
- Cross-referencing trust documents (e.g., balance sheets, tax returns) with corporate filings can reveal unexplained ownership patterns or suspicious relationships.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Provides comprehensive information on trust structures, trustees, beneficiaries, associated accounts, and transaction histories. This data helps:

- Identify potential involvement of offshore trusts designed to obscure true ownership.
- Verify the identities of beneficiaries and trustees who may be linked to layering activities.
- Track cross-border financial flows passing through trust accounts, supporting detection of offshore layering schemes.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Detailed records of trusts, including their structure, trustees, beneficiaries, and account activities.
- Identifies hidden ownership or complex trust layers behind arbitration participants, suggesting collusion or concealment of illicit beneficiaries.
- [Trust-Based Obfuscation](https://framework.amltrix.com/techniques/T0088.002) — - Provides official trust deeds, trustee and beneficiary details, powers of attorney, and signatory records.
- Enables detection of undisclosed or frequently changing beneficial owners and nominal trustees.
- Helps identify suspicious signatory or beneficiary changes that reveal trust-based obfuscation attempts.

---

## [Business Activity and Operations](https://framework.amltrix.com/data-sources/DS0030)

**Description:**
Data on a business’s commercial, industrial, or professional operations, including revenue figures, operating expenses, and related metrics, often compared with reported financial information to identify discrepancies or anomalies.

### Related Techniques
- [Common Offenses](https://framework.amltrix.com/techniques/T0146) — - Provides operational metrics such as revenue figures, foot traffic data, and expense patterns.
- Enables comparison between reported revenues and actual business capacity, highlighting unexplained cash surges.
- Assists in identifying suspicious spikes in reported income at smaller businesses that may be used to launder proceeds of common offenses.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Documents a project's operational scope, revenue, expenditures, and resources.
- Compares declared project goals or developmental capacity with the funds reportedly raised, identifying potential discrepancies indicative of fraudulent fundraising.
- Highlights mismatches between stated progress and actual business viability or investment requirements.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Detailed records of a business’s operational metrics include actual production levels, livestock counts, farmland acreage, and operating costs. Comparing this operational data against claimed capacities in subsidy applications can reveal potential discrepancies, exposing inflated or falsified production figures.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Detailed records of a business’s real-world operations, revenues, expenses, and relevant operational metrics.
- Facilitates comparison of declared call center capacity (staffing, facilities, overhead) to reported income, highlighting potential inconsistencies indicative of fictitious operations.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Offers detailed operational metrics, including production capacity, revenue figures, operating expenses, and comparative industry benchmarks.
- Enables detection of inflated or fabricated costs (e.g., seeds, fertilizers) and abnormal revenue patterns not aligning with typical agribusiness norms.
- Confirms whether government subsidies or operational claims match actual production output for farmland or livestock.
- Aids in verifying real on-site activities and identifying ghost operations lacking tangible agricultural output.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Includes records of a business’s operating scale, revenue figures, and typical expense allocations.
- Enables direct comparison of declared payroll taxes and workforce sizes to industry norms and operational benchmarks.
- Assists in flagging anomalously low reported payroll obligations inconsistent with actual business activity.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Provide baseline industry metrics (e.g., typical cost structures, staffing needs) for construction projects to help identify inflated or unjustified expenses.
- Offer comparative data on usual operational scope and spending patterns to reveal anomalies in cost estimates or invoices.
- Support ongoing assessment of a company’s actual construction activity against stated business operations.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Reveals an entity’s actual operational scope, risk exposure, and typical insurance needs.
- Identifies mismatches between legitimate business activity and the scale of insurance premiums or claims, suggesting manipulation.
- [Undisclosed Payment Aggregation](https://framework.amltrix.com/techniques/T0138) — - Contains operational data on a merchant’s declared products, services, and revenue streams.  
- Helps investigators compare a merchant’s stated business model against actual transactions, identifying mismatches that may signal unauthorized or illicit deposit activity.  
- Supports validation of declared sales volumes, preventing criminals from hiding illegal fund flows under legitimate business operations.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Captures operational details such as workforce size, machinery, and production capacity. Discrepancies in reported small-scale activity versus large trade volumes may indicate the integration of illicitly mined minerals into official output.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Provides data on a business's commercial scale, revenues, and operational scope.
- Helps AML teams detect inconsistencies between declared diamond trading activities and actual business operations.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Data on a company’s actual commercial operations—such as revenue generation, production processes, and day-to-day transactions—allows for cross-checking against accrued amounts in financial statements. Discrepancies between real operational output and reported accrual balances can signal fraudulent manipulations.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Reflects the practical operational scale, such as sales volumes, workforce size, and inventory data, of the entity.
- Allows comparison of declared jewelry income or transaction volumes against actual capacity.
- Highlights businesses claiming large throughput with negligible operational footprint, indicating possible front activity.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Contains information about a property's typical revenue-generating activities, occupant levels, historical performance metrics, and operational scale.
- Enables comparison of stated occupancy or usage rates with actual transaction volumes, aiding in the detection of abnormally high income and potential mixing of illicit funds.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Includes data on revenue streams, operational scope, and market presence of a business.
- Supports detection of abnormal expansions, sudden shifts in operations, or uncharacteristic activities tied to sanctioned markets or entities.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Contain operational data (daily revenue, production, sales figures) reflecting actual business activities.
- Enable comparison between genuine operational results and reported financial statements, exposing inflated or fabricated revenues and manipulated accruals.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Provides data on a company’s commercial operations, revenue figures, operating expenses, and other key metrics. By comparing declared labor costs with industry norms, investigators can spot suspiciously low payroll expenses or hidden workers, which are indicators of forced labor exploitation.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Documents actual operational metrics, such as inventory levels, supply costs, and operational capacity, that can be contrasted with declared revenues.
- Helps reveal when a purportedly legitimate company shows minimal or inconsistent real activity, a common sign of a front.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Examines an enterprise’s operating footprint, including payroll, facilities, and other operational metrics, to confirm actual commercial activities. Discrepancies between purported revenues and a lack of real expenses or infrastructure can signal a virtual enterprise used for laundering.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Details a company’s normal business functions, operational capacity, and financial performance.
- Helps validate claimed trade volumes, product lines, and shipping requirements.
- Reveals potential misalignment between declared cargo and actual business operations in documentary collection transactions.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Provides insight into an entity’s real operational outputs, revenue streams, and organizational scale.
- Allows comparison of claimed trade capacity and loan repayment feasibility to actual business performance, highlighting inflated or fabricated trade finance needs.
- [Domestic Bulk Cash Delivery](https://framework.amltrix.com/techniques/T0119) — Encompasses a company’s operational metrics, revenue streams, and expected cash handling practices. By comparing declared business activities with observed domestic cash deposits, investigators can identify sudden, unexplained surges in cash flows indicative of bulk cash delivery schemes.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Provides insight into a business’s commercial activities, revenue streams, and operating expenses.
- Allows verification of actual operational history or downturn claims against the relief application’s stated figures.
- Identifies discrepancies where a business’s claimed losses or scale of operations do not match observed commercial activity, indicating potential fraud.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Examine the captive insurer’s operational footprint, including workforce size, operational sites, and actual insurance coverage volumes.
- Compare basic operating metrics (policy count, claims ratio) to industry norms, detecting anomalies such as high premiums with negligible claims or fictitious risk coverage.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Provides insight into a customer’s declared commercial operations and expenses, including energy consumption profiles.
- Allows comparisons between reported mining capacity (e.g., hardware count, power usage) and actual outputs observed on the blockchain.
- Helps identify discrepancies where declared operations do not match suspiciously high mining yields.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Contains verified information on a company's actual operations, revenues, and expenses.
- Assists in determining whether corporate entities are truly active or serve as shells.
- Helps compare reported economic activity against financial statements to detect inconsistencies or fabrication.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Includes data on an entity’s real operational presence, staffing, physical assets, and business activities.
- Helps determine whether affiliated entities charging each other for services or goods actually conduct legitimate operations, thereby exposing shell or paper companies used in transfer pricing schemes.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Detail revenue figures, operational capacity, and expenses for businesses.
- Reveal discrepancies in claimed operations, such as bars or massage parlors, when fronts are used to launder trafficking proceeds.
- Highlight unusual operational patterns or inflated revenues indicating forced labor exploitation.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Includes historical sales, production capacity, or operational data for the businesses involved in trade finance. By comparing financed amounts or volumes with typical production or sales figures, investigators can identify disproportionate or anomalous loan requests or invoices.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Contains information about a business's operations, including revenue, operating expenses, and employee counts.
- Helps identify discrepancies when large transaction volumes are not consistent with the entity's actual operational capacity, suggesting circular movement of funds.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Holds operational data such as attendance records, event scheduling, performance metrics, and ticket sales.
- Enables AML teams to compare reported event revenues or sponsorship deals with actual attendance to reveal inflated or fabricated income.
- Helps detect front usage where reported activity significantly exceeds verifiable operational evidence.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Details actual operational metrics (e.g., production output, sales volumes, service capacity) that enable comparison of real performance against reported financials. This helps reveal inconsistencies such as inflated revenue, understated costs, or disconnected growth trends typical of laundering schemes through allegedly legitimate businesses.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Details on a business’s revenues, expenses, and operational scale. Cross-checking these figures against Bill of Exchange amounts can expose suspiciously large or inconsistent transactions that do not align with the entity’s typical business profile.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Data on a company’s usual commercial scale, revenue, and expenditures.  
- Enables comparison between typical operations and the size or nature of arbitration claims, uncovering potential staged or inflated disputes.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Holds information on a company’s operational practices, revenues, and typical transaction volume. This data allows for the detection of repeated invoicing beyond normal business activity or scale, indicating potential abuse of trade finance arrangements.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Provides insight into a business’s genuine operational presence, such as physical premises, inventory, and workforce data.
- Allows investigators to compare the declared business scope with actual operations.
- Identifies the limited or nonexistent activity typical of shell entities used in carousel schemes.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Information on a business’s operational history, revenue, and day-to-day activities.
- AML Relevance: Reveals a lack of real commercial operations and legitimate payroll outflows, exposing fabricated employer-employee relationships.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Details a firm's day-to-day operational scope, staffing levels, physical premises, and overhead.
- Highlights discrepancies where reported consulting revenue far exceeds observable business capacity or real-world operations.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Data capturing core business operations includes actual revenue, expenses, and operational metrics. By comparing stated deal values with verifiable business performance, investigators can identify artificially inflated or deflated valuations in M&A transactions. This process helps uncover sham acquisitions or manipulated valuations, which are frequently seen in fictitious M&A schemes.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Provides information on a company's declared commercial operations, revenues, expenses, and overall business metrics.  
- Enables comparison of actual activity levels against the official incorporation timeline, identifying cases where a shelf company's older registration date contradicts its minimal or nonexistent operational history.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Contains data on an entity’s core business lines, production capacity, and typical revenue streams. Comparing these operational details with large or frequent red/green clause LC transactions can uncover inconsistencies or fraudulent usage.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Documents an entity’s operational scale, staffing, and production capacities.
- Highlights discrepancies where significant foreign investments do not translate into visible business expansion, suggesting falsely declared economic activity.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Documents reported business activities, revenue sources, and operational footprints.
- Enables comparison between declared operations and actual cross-jurisdiction transactions.
- Aids in detecting shell or dormant companies lacking legitimate activity in multi-layered structures.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Includes operational metrics, procurement cycles, staffing levels, and other core business data.
- Allows comparison of claimed vendor activity against realistic operational patterns, helping to identify anomalies consistent with fake vendor usage.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Document sanctioned budgets, standard workflows, and operational spending for government entities.  
- Compare declared activities or projects with actual financial outflows to detect inflated expenditures or phantom projects indicative of misappropriation.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Assesses the real operational capacity and customer engagement for purported offshore gambling services.
- Compares declared gambling activities with actual records of gaming infrastructure or user volumes.

Such comparisons help expose sham or non-operational gambling businesses that launder illicit funds under the guise of legitimate revenue.
- [Temporary Shell Companies](https://framework.amltrix.com/techniques/T0001.002) — - Compares the declared business purpose with actual operational evidence (e.g., revenues, operational records).
- Highlights discrepancies when an entity claims a commercial purpose but shows no tangible activity.

These insights expose the lack of genuine business operations characteristic of temporary shell companies.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Provides records of a charity’s stated projects, operational scope, and activities.
- Enables cross-checking of reported philanthropic activities against actual resources allocated.
- Helps detect whether incoming donations are consistent with legitimate programming or suggest that funds are being diverted.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Contains data on a company’s operational metrics, such as sales figures, expenses, or foot traffic. These records help: 

- Compare reported operational performance against declared revenue spikes potentially fueled by coerced payments.
- Identify inconsistent or unsubstantiated inflows indicating extortion proceeds disguised as legitimate business income.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Information on a company’s operational scope, revenue streams, and typical commercial activities.
- AML Relevance: Determines whether declared trades align with the entity’s legitimate business profile or signal fictitious deals beyond its normal operations.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Catalogs a company's day-to-day operations, revenue streams, and operational capacity.
- Comparing these operational metrics with high-value or frequent invoices supports the detection of artificially inflated or fabricated trade transactions.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Captures the overall scope of an entity’s operations, including production volumes, client base, and typical employee headcount.
- Allows comparison of reported payroll outlays with actual business size, revenues, and operational scale to detect inflated wages or fabricated workforce claims.
- [Cash Wage Payments](https://framework.amltrix.com/techniques/T0052) — - Details the nature, scope, and operational scale of a business, including revenue patterns and expense structures.
- Identifying excessive reliance on untracked cash wage payments compared to industry norms can reveal concealed or illicit payroll practices.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Provides data about a business's core operations, revenue streams, and expenses, indicating genuine economic activity or the lack thereof.
- Helps detect shell or newly formed entities set up purely to fulfill minimum CBI/RBI investment criteria without genuine commercial operations.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Details a company’s operational metrics, including revenue streams, production capacity, and allocated resources.
- Helps compare reported mining hash rates or production levels with financial inflows/outflows to detect inconsistencies suggesting money laundering.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Contains records of the entity’s stated line of business, operational scope, revenue sources, and expense categories. This allows for a comparison between claimed activities and the nature of recorded payables to detect incongruent or fabricated liabilities.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Tracks operational capabilities, production volumes, and growth patterns, enabling investigators to identify sudden expansions or capital inflows that exceed normal growth rates and lack a justifiable commercial rationale.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Details the operational scope, revenues, and expenses of a company. Comparing these metrics with investors' returns or marketing claims helps expose sham operations or shell entities carrying out fraudulent investment promotions.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Contains actual operating details, including revenue figures and expenses.
- Allows comparison of declared business results with real operational data to spot underreporting or misclassification of expenses aimed at tax evasion.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Provides an organization’s operational metrics, reported revenues, and business capacity.
- Identifies sudden spikes in reported sales without corresponding operational evidence, signaling potentially fictitious or inflated revenues.

---

## [Blockchain and Cryptocurrency Data](https://framework.amltrix.com/data-sources/DS0045)

**Description:**
Comprehensive data from public blockchain ledgers and related analytics, including transaction IDs, timestamps, sender and receiver addresses, and amounts for digital asset transactions.

### Related Techniques
- [Cross-Chain Token Wrapping](https://framework.amltrix.com/techniques/T0067.002) — **Data Provided:**

- Transaction identifiers, timestamps, sender and receiver addresses, wrapped token creation and redemption records, cross-chain bridging events.

**How It Supports Detection/Investigation:**

- Enables tracing of rapid wrap-and-unwrap transactions and multi-chain movements.
- Helps identify suspicious address clusters, repeated bridging steps, and short holding periods indicative of layering.
- Facilitates detection of anomalous funding patterns inconsistent with declared customer activities.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Encompasses on-chain transaction details, including wallet addresses, transaction IDs, timestamps, and amounts. Comparing these data with institution-held fiat transaction logs uncovers OTC trades that consolidate large sums of cryptocurrency without passing through regulated exchange order books.
- [Structuring](https://framework.amltrix.com/techniques/T0016) — - Records on-chain transaction data, including wallet addresses, timestamps, transaction amounts, and receiving parties, across various digital assets.
- Supports tracing of small, repeated transfers dispersed among multiple ephemeral cryptocurrency wallets under the reporting threshold.
- Helps identify patterns of wallet creation and usage consistent with smurfing or structuring in the crypto space.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Provides on-chain transaction records, wallet addresses, and amounts involved in cryptocurrency transfers.
- Supports tracing of crypto deposits into unregulated pathways for conversion into in-game currency or vice versa, revealing potential laundering layers.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Captures cryptocurrency wallet addresses, transaction flows, and analytics to support the identification of unregulated digital payments and laundering methods linked to counterfeit pharmaceutical sales.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Provides on-chain transaction data, including transaction IDs, timestamps, sender/receiver addresses, amounts, and liquidity pool interactions. Investigators can use this data to track large, rapid outflows from ICO wallets, abrupt liquidity removal, and layering across multiple addresses, which are common indicators of rug pull schemes. By analyzing these movements, it becomes possible to link wallet addresses to suspicious activity and trace illicit proceeds.
- [Metaverse-based Asset Transfers](https://framework.amltrix.com/techniques/T0066.001) — - Provides on-chain transactional details (e.g., timestamps, wallet addresses, token amounts) associated with purchasing or selling metaverse-based digital assets.
- Supports detection of high-frequency token swaps, short holding periods, and NFT wash trading by analyzing transaction patterns and wallet clusters.
- Facilitates tracing of illicit token flows and identifying code exploit transactions aimed at manipulating asset values.
- [Tokenized Fundraisings](https://framework.amltrix.com/techniques/T0144.013) — - Provides detailed on-chain records, including wallet addresses, transaction timestamps, amounts, and token movements.
- Enables tracking of newly created or unverified wallets, rapid dispersal of raised funds through multiple smart contract addresses, and frequent conversions to other cryptocurrencies.
- Helps uncover layering attempts and complex fund flows designed to obscure the source of funds from tokenized fundraisings.
- [Governance Token Obfuscation](https://framework.amltrix.com/techniques/T0067.003) — Provides on-chain transaction records, addresses, token contract interactions, bridging transactions, multi-hop transfers, and cross-chain swaps. Investigators can:

- Identify repeated governance token conversions and bridging events.
- Detect unusual transaction volumes, layering patterns, or wallet linkages.
- Correlate wallet addresses to uncover illicit obfuscation of fund flows.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Provides on-chain transaction records, including wallet addresses, timestamps, and transaction amounts.
- Detects the use of mixing, tumbling, or obfuscation services associated with high-risk crypto laundering tactics.
- Enables investigators to trace digital asset flows tied to charitable donations and identify addresses operating from high-risk jurisdictions or flagged for prior illicit activity.
- [Crypto ATMs](https://framework.amltrix.com/techniques/T0063) — Comprehensive on-chain data—including transaction IDs, addresses, timestamps, and amounts—enables the correlation of crypto ATM cash transactions with subsequent wallet movements. This supports the detection of rapid inflows and outflows, layering across multiple wallets, and broader anomalous cryptocurrency activity linked to illicit proceeds.
- [Utility Tokens](https://framework.amltrix.com/techniques/T0067.005) — - Provides on-chain transaction details (e.g., sender/receiver addresses, timestamps, transaction IDs, token types) across multiple blockchains.
- Enables tracing of frequent cross-chain transfers, bridging activities, and repetitive swapping of utility tokens, revealing potential layering or obfuscation methods.
- Identifies cyclical or high-volume token movements unconnected to the token’s intended platform use, suggesting questionable fund flows for AML investigations.
- [NFT-based Value Obfuscation](https://framework.amltrix.com/techniques/T0064) — - Provides on-chain records (transaction IDs, timestamps, wallet addresses, amounts) essential for tracing NFT transactions and identifying patterns of rapid resale, cross-wallet transfers, and inflated prices.  
- Enables investigators to map out wallet ecosystems, detect repetitive self-dealing, and correlate suspicious NFT trades with potential wash trading or mixer usage.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Provides on-chain transaction records for cryptocurrencies and NFTs, including wallet addresses, timestamps, and amounts.
- Detects repeated NFT transfers among related wallets at escalating valuations, indicating artificial price inflation or wash trading.
- Allows investigators to trace asset movements and identify potential manipulation across digital asset markets.
- [Crypto ATM Mule](https://framework.amltrix.com/techniques/T0011.002) — - Tracks on-chain transactions, wallet addresses, and the flow of digital assets.
- Correlates repeated funding of the same wallet address by multiple individuals or suspicious layering patterns once illicit cash is converted to crypto.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Provides on-chain transaction data, including transaction IDs, wallet addresses, timestamps, and transferred values. This data enables the detection of cross-border digital asset flows, identification of suspicious or high-risk crypto usage within e-commerce transactions, and tracing of NFTs or other tokens potentially used to layer illicit funds.
- [Wash Trading](https://framework.amltrix.com/techniques/T0094.002) — - Provides on-chain records for cryptocurrency and NFT transactions, including wallet addresses, timestamps, and amounts.
- Detects repeated self-dealing or wash trading patterns in decentralized environments.
- Helps trace cross-wallet transfers that obscure the origins of funds and beneficial ownership.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — - Public blockchain records of transaction timestamps, addresses, and amounts enable on-chain analytics.
- Detects whether disputed funds are routed to decentralized exchanges or crypto wallets.
- Helps trace layered or obfuscated flows of chargeback proceeds in digital asset environments.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Provides details from public blockchain ledgers and related analytics, including transaction IDs, timestamps, wallet addresses, and amounts.
- Enables tracing of cryptocurrency funds across multiple addresses or wallets, detecting repeated cross-currency layering between fiat and crypto that obscures transaction origin.
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Provides on-chain records (addresses, transaction IDs, timestamps) indicating wallets with no direct linkage to custodial providers.
- Helps detect self-hosted wallets lacking formal KYC oversight, revealing potential illicit usage routes.
- [Peel Chain](https://framework.amltrix.com/techniques/T0070.002) — On-chain transaction details—including addresses, timestamps, amounts, and analytic insights—are used to trace funds across multiple hops. This data uncovers micro-transactions, address reuse, and fragmentation patterns characteristic of peel chain activity, enabling investigators to track the movement of illicit funds.
- [Chain Hop](https://framework.amltrix.com/techniques/T0005) — - Provides on-chain transaction details (e.g., wallet addresses, timestamps, amounts) across multiple blockchains.  
- Enables identification of cross-chain bridging, chain hopping patterns, and usage of decentralized mixers or bridges to obscure the flow of funds.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Captures on-chain transaction details such as sender and receiver wallet addresses, timestamps, and transaction amounts.
- Identifies the usage of cryptocurrency mixers or flagged wallet addresses linked to sanctioned entities, supporting investigations into illicit crypto flows.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Captures cross-chain transaction details such as wallet addresses, transaction hashes, timestamps, and token transfers. This enables investigators to follow digital asset movements across multiple blockchain-based gaming ecosystems, helping uncover obfuscated layering activities or unregulated bridging services.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Captures on-chain transactions for digital assets, including NFTs and cryptocurrencies, such as transaction hashes, wallet addresses, timestamps, and token transfers. This data reveals layering behaviors, wash trading, and multi-leg movements typical of laundering schemes exploiting virtual world marketplaces and cross-platform asset transfers.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Provides blockchain ledger records, including wallet addresses, transaction hashes, timestamps, and amounts.
- Enables tracking of rapid, high-frequency fund movements across multiple digital wallets typical of automated layering.
- Offers a trail for cryptocurrency transfers that can be correlated with traditional transaction logs to identify cross-asset obfuscation strategies.
- [Online Game Currency Conversion](https://framework.amltrix.com/techniques/T0018) — - Provides on-chain records and analytics of cryptocurrency transactions, including wallet addresses, transaction amounts, and timestamps.

- Facilitates tracing the flow of funds when criminals convert in-game currencies to cryptocurrencies, identifying potential mixing or layering through blockchain networks.
- [Darknet Marketplace Transactions](https://framework.amltrix.com/techniques/T0100) — - Provides on-chain transaction details, including addresses, timestamps, and amounts, and identifies wallet clusters associated with Darknet marketplaces or mixers.
- Facilitates tracing of cryptocurrency flows across multiple wallets, chains, and protocols, revealing layering patterns and detecting suspicious cross-chain activity indicative of Darknet marketplace proceeds.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Provides on-chain transaction records, including addresses, timestamps, and amounts.
- Enables tracing of layered transactions across multiple digital asset addresses or blockchains, revealing the flow of illicit funds through instant exchange services.
- [Cryptojacking](https://framework.amltrix.com/techniques/T0020.002) — Offers on-chain transaction records, including wallet addresses, timestamps, and amounts, along with related analytics. By examining repeated small mining-related transfers, anomalous consolidation patterns, and subsequent exchanges, investigators can trace proceeds from cryptojacking and identify layering or integration points in the laundering process.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Provides on-chain transaction details (addresses, timestamps, and amounts) used to trace digital asset movements across personal or external wallets, identify chain-peeling patterns, and detect mixing protocols or CoinJoin transactions.
- Supports investigations by pinpointing transactions linked to privacy services and illustrating cross-wallet transfers common in illicit layering strategies under this technique.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Provides on-chain records of mining reward issuances, wallet addresses involved, and subsequent transfers.
- Helps trace newly minted coins, detect abnormal reward frequencies, and identify rapid liquidation or multi-wallet layering schemes.
- Supports investigators in linking on-chain movements to known or suspected illicit activities.
- [Privacy Coins](https://framework.amltrix.com/techniques/T0116) — - Provides on-chain transaction details such as transaction IDs, blockchain addresses, timestamps, and amounts, even for privacy coins that employ obfuscation features (e.g., ring signatures, stealth addresses).

- Enables partial tracing of transaction flows and identification of rapidly moving assets into and out of privacy coin wallets, supporting investigations into layering and structuring attempts using privacy-focused cryptocurrencies.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Encompasses on-chain records of wallet addresses, transaction amounts, timestamps, and counterparties from public blockchain ledgers.
- Allows tracing of newly mined cryptocurrency flows from remote mining providers to multiple wallets, identifying potential layering or obfuscation attempts.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Includes addresses, timestamps, transaction identifiers, and amounts from public ledgers. This data enables investigators to trace how physical cash introduced by couriers is rapidly converted into digital assets or vice versa, revealing cyclical conversions, short holding periods, and cross-currency flows consistent with Node Exchange Provisioning patterns.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Tracks on-chain digital asset transactions, including wallet addresses, timestamps, and transaction amounts.
- Enables detection of cross-asset 'chain hopping' and peel chain patterns used to split large sums into micro-transactions.
- Assists investigators in tracing funds that move rapidly across multiple blockchain networks, common in transaction chaining.
- [Custodial Mixers](https://framework.amltrix.com/techniques/T0003.001) — - Provides on-chain transaction information, including sender and receiver addresses, timestamps, and amounts.
- Enables direct tracing of funds to mixer-associated addresses, detection of address separation (layering), rapid turnover events, and discrepancies between deposit and withdrawal amounts.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Provides on-chain transaction records (e.g., wallet addresses, timestamps, amounts) and analytics tools for tracing cryptocurrency flows.
- Assists in detecting rapid transfers to external wallets, newly created accounts, and the usage of lightly regulated exchanges that may facilitate laundering.
- [Micro-Structuring](https://framework.amltrix.com/techniques/T0016.001) — - Provides on-chain transaction information, including sender and receiver addresses, transaction amounts, and timestamps.
- Enables analysis of repeated small cryptocurrency movements to multiple or anonymous addresses, commonly used to conceal aggregated funds via micro-structuring.
- [Burn and Mint Transfers](https://framework.amltrix.com/techniques/T0005.001) — Includes detailed on-chain transaction information such as addresses, timestamps, amounts, token transfers, and burn events across various blockchain networks. For burn and mint transfers, these records enable investigators to:

- Identify tokens sent to burn addresses and correlate them with newly minted tokens on other chains.
- Detect cross-chain layering strategies by tracking associated burn and re-mint transactions.
- Pinpoint suspicious or repetitive use of burn addresses and link them to broader illicit activity patterns.
- [Decentralized Mixers](https://framework.amltrix.com/techniques/T0003.002) — - Provides comprehensive on-chain transaction details, such as transaction IDs, timestamps, sender and receiver wallet addresses, and amounts.
- Enables identification of known decentralized mixer smart contracts or aggregator addresses used for mixing.
- Facilitates analysis of cross-chain layering activity after mixers, helping uncover suspicious address clusters or transaction patterns.
- [DeFi Transactions](https://framework.amltrix.com/techniques/T0067.004) — Provides on-chain transaction details, such as wallet addresses, token transfers, bridging events, and liquidity pool interactions. This enables the detection of high-frequency DeFi activities, rapid token swaps, and cross-chain movements indicative of layering or attempted obfuscation.
- [Virtual Token](https://framework.amltrix.com/techniques/T0067) — - Provides on-chain transaction details, including transaction IDs, timestamps, addresses, token types, and amounts from public ledgers, along with related analytics.
- Enables the detection of rapid cross-chain token movements, multiple address hops, and bridging activities.
- Facilitates the identification of layering or obfuscation attempts by analyzing frequent conversions, short holding periods, and irregular token flows.
- [Privacy Wallets](https://framework.amltrix.com/techniques/T0034.001) — - Provides on-chain transaction data, including addresses associated with privacy wallets, timestamps, and amounts.
- Enables detection of rapid consecutive transactions, coinjoin usage, cross-chain transfers, and layering patterns that obscure original fund sources.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Captures on-chain transaction details, wallet addresses, timestamps, and amounts for digital assets. This data is crucial for verifying claimed trading volumes or fund flows in high-yield crypto offerings and identifying illicit transfers or wallet activities associated with fraudulent investment schemes.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — Includes on-chain transaction records, such as wallet addresses, timestamps, and transaction values, enabling the identification of high-frequency transfers, circular flows, and layering across multiple wallets. This is crucial for tracking payment token movements and detecting transactions structured to evade thresholds.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Captures on-chain transaction details, including wallet addresses, transaction hashes, timestamps, and amounts, from public ledgers.
- Assists in tracing complex layering schemes by identifying multiple crypto wallets that rapidly move funds.
- Helps corroborate whether purported investment platforms or wallets are tied to known pig butchering scams.
- [Ransomware Payments](https://framework.amltrix.com/techniques/T0049.001) — - Offers public blockchain ledger information, such as transaction IDs, timestamps, wallet addresses, transaction amounts, and potential mixer addresses.
- Facilitates the tracing of layered transfers, chain-hopping, and rapid multi-wallet movements used to obscure ransomware proceeds.
- Supplies advanced analytics that highlight clusters of related wallets and detect anomalous patterns consistent with ransomware layering strategies.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Provides public ledger records, including transaction hashes, sender/receiver addresses, and timestamps for crypto transactions.
- Aids in tracing large or frequent crypto flows that fund precursor chemicals via dark web channels.
- Highlights layering or mixing techniques used to conceal the source of drug proceeds.
- [Cross-Chain Bridges](https://framework.amltrix.com/techniques/T0005.002) — - Provides on-chain transaction details, including bridging transactions, timestamps, wallet addresses, and transferred amounts across different blockchains.
- Enables cross-chain flow analysis to identify elaborate chain-hopping or layering schemes that obscure illicit fund origins.
- Assists investigators in detecting irregular bridging activities lacking clear business rationale and tracking indicators such as structured transactions or rapid, successive cross-chain hops.

---

## [Exchange & Trading Activity Records](https://framework.amltrix.com/data-sources/DS0046)

**Description:**
Records of trades and transactions on regulated financial exchanges, covering securities, commodities, derivatives, and cryptocurrencies. Typically includes trade volumes, dates, prices, counterparties, timestamps, transaction identifiers, and related compliance details.

### Related Techniques
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Captures transaction timestamps, trade volumes, counterparties, and order details on regulated exchanges.
- Enables detection of suspiciously timed or coordinated trades consistent with illicit exploitation of non-public information.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Document trades across regulated financial exchanges, including trade volumes, timestamps, prices, and counterparties.
- Reveal patterns of rapid buying and selling, circular trading, or artificially high volumes indicative of manipulation.
- Enable detection of spoofing and layering activities through order placement and cancellation logs.
- [Privacy Wallets](https://framework.amltrix.com/techniques/T0034.001) — - Captures cross-chain bridging and swaps, listing details of trades, parties involved, volumes, and timestamps.
- Essential for identifying frequent chain-hopping into privacy wallets or anonymity-focused cryptocurrencies as part of complex layering schemes.
- [Chain Hop](https://framework.amltrix.com/techniques/T0005) — - Logs cross-chain swaps, conversions, and bridging transactions across multiple exchanges, including timestamps, volumes, and counterparties.
- Uncovers rapid or frequent bridging activities not justified by commercial needs, supporting the detection of chain hopping patterns.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Includes transaction logs, trade volumes, counterparties, and timestamps for securities, commodities, and digital assets.
- Enables identification of suspicious trades or large off-market transactions that may conceal sanctions violations or launder associated proceeds.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Includes timestamps, order details, pricing, and counterparties for both traditional and digital asset trades.
- Reveals precisely scheduled or algorithmic transaction patterns disconnected from typical market activity.
- Helps distinguish normal discretionary trading from automated transfer schemes designed to rapidly layer funds.
- [Utility Tokens](https://framework.amltrix.com/techniques/T0067.005) — - Captures trade volumes, timestamps, counterparties, and order details associated with token transactions on regulated or semi-regulated exchanges.
- Enables detection of high-frequency or repetitive utility token trades lacking economic rationale or tied to cross-exchange arbitrage without valid commercial purpose.
- Helps identify potential wash trading or round-trip layering by analyzing trade patterns, price variations, and rapid buy-sell sequences.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Documents trading activity, volumes, and executed orders within regulated markets. Reviewing these records alongside claimed fund performance can expose discrepancies or fabricated returns not corroborated by actual trading data.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Contains detailed logs of trades on regulated financial exchanges, including timestamps, transaction volumes, order details, and prices.
- Reveals potential wash trading, spoofing, and high-frequency manipulative patterns by analyzing order placements, cancellations, and executed trades.
- Identifies whether trades result in genuine ownership changes or are merely circular transactions aimed at misleading the market.
- [Privacy Coins](https://framework.amltrix.com/techniques/T0116) — - Captures detailed records of trades and conversions, including timestamps, trading pairs, volumes, and counterparties involved in converting mainstream cryptocurrencies into privacy coins.

- Assists in identifying large or frequent conversions into privacy coins for potential layering, as well as cross-exchange rapid transfers that obscure the source or destination of funds.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Provides details on trades across regulated financial exchanges, including timestamps, volumes, prices, counterparties, and transaction identifiers. This information enables the detection of mirror trading patterns, such as offsetting trades executed by the same or related parties in different jurisdictions, revealing attempts to disguise funds transfers with no real economic purpose.
- [Dividend Stripping](https://framework.amltrix.com/techniques/T0147.003) — Provides records on short-selling and share-lending transactions, trade timestamps, counterparties, settlement instructions, and share ownership data around dividend record dates. This information enables the detection of suspicious trading patterns and multiple claims of dividend entitlements.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Logs of trades executed on regulated exchanges, including timestamps, volumes, and counterparties.
- Enables detection of market manipulation, pump-and-dump activity, or high-velocity trades aligned with layering or artificially created investment gains.
- [Self-Hosted Cryptocurrency Wallets](https://framework.amltrix.com/techniques/T0034) — - Provides trade details such as asset types, trading pairs, executed volumes, timestamps, counterparties, and price data, enabling the detection of frequent cross-asset conversions from or to self-hosted wallet addresses.
- Helps AML investigators identify unexplained or anomalous asset switching that may indicate layering or obfuscation of illicit funds in non-custodial wallets.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Encompasses trade details on regulated trading platforms, including timestamps, trade volumes, prices, counterparties, and compliance checks.
- Helps uncover repeated or rapid multi-currency trades that mask beneficial ownership.
- Facilitates identification of layering patterns through interlinked trading accounts or various currency pairs on exchanges.
- [Offsetting Transactions](https://framework.amltrix.com/techniques/T0102) — - Provides transaction-level details, such as timestamps, volumes, counterparties, and instrument information, for trades on financial or cryptocurrency exchanges.
- Enables detection of offsetting or near-simultaneous buy and sell orders, matched trades with minimal net position changes, and artificially inflated liquidity.
- Helps identify unusual trade frequencies and volumes that lack genuine economic rationale, revealing wash trade patterns.
- [Wash Trading](https://framework.amltrix.com/techniques/T0094.002) — - Provides detailed data on trades, including timestamps, trade prices, volumes, counterparties, and transaction IDs.
- Enables detection of repeated buy/sell patterns with minimal net changes in position, indicating potential wash trading.
- Supports analysis of anomalous trading volume spikes or offsetting transactions that suggest collusion or self-dealing.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Provides details of trades and currency conversions, including timestamps, volumes, trading pairs, prices, counterparties, and transaction identifiers.
- Supports detection of rapid layering, repetitive swaps, and obscure asset pair usage, all of which are indicative of instant exchange-based laundering.
- [Cryptocurrency Investment](https://framework.amltrix.com/techniques/T0128) — - Captures trading volumes, order details, settlement records, and timestamps from cryptocurrency and financial exchanges.
- Allows detection of repetitive swaps, minimal net gain/loss transactions, and cross-exchange layering, helping to expose suspicious reinvestment patterns aligned with this technique.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Contains user trading and transaction histories for cryptocurrency and other exchange platforms, including timestamps, volumes, and counterparties.
- Enables identification of frequent currency conversions on platforms with lax KYC, highlighting potential layering or sanctions evasion activities.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Provides detailed registers of trades and transactions, including timestamps, volumes, frequencies, and counterparties.
- Identifies large or rapid transactions across newly opened accounts, tracks the consolidation of funds from multiple sources, and flags behavior inconsistent with legitimate trading patterns.
- [Metaverse-based Asset Transfers](https://framework.amltrix.com/techniques/T0066.001) — - Contains transaction records (e.g., trade dates, prices, volumes, counterparties) from centralized or regulated exchange platforms.
- Corroborates successive conversions of proceeds from metaverse asset sales into mainstream cryptocurrencies or fiat.
- Helps identify rapid deposit-withdrawal cycles, short holding periods, and potential layering or wash trading behaviors.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Provides trade volumes, counterparties, timestamps, and pricing data across regulated exchanges. Comparing claimed returns or trading activity with verified market records helps uncover inflated performance reports or nonexistent transactions linked to fraudulent investment strategies.
- [Payment Tokens](https://framework.amltrix.com/techniques/T0067.001) — Contains timestamps, trade pairs, volumes, and counterparties for digital asset conversions, enabling the identification of rapid token-to-fiat or cross-asset swaps across multiple intermediaries with lax KYC controls. This indicates swift layering or integration of illicit proceeds.

---

## [Prepaid Card Transaction Data](https://framework.amltrix.com/data-sources/DS0017)

**Description:**
Information on transactions involving prepaid cards, including transaction amounts, frequencies, card identifiers, and overall usage patterns.

### Related Techniques
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Tracks loading, spending, and withdrawal activities on prepaid cards.
- Detects repeated conversions of card balances into cash amounts just under regulatory thresholds.
- [Structuring](https://framework.amltrix.com/techniques/T0016) — - Captures transaction details, card identifiers, and usage patterns for prepaid or stored-value cards.
- Detects repeated small-value loads or withdrawals and flags cumulative amounts exceeding threshold limits.
- Aids in uncovering structuring via multiple prepaid cards or stored-value accounts used to evade reporting triggers.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Offers detailed records on prepaid card usage, including individual card identifiers, deposit and withdrawal timestamps, transaction amounts, and usage frequencies. Investigators can identify repeated or high-volume reloads, small-amount structuring, and offshore usage patterns tied to secrecy-jurisdiction prepaid cards.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Logs prepaid card loading, usage, and redemption events, including geographical points of transaction.
- Flags frequent or high-value card activities in secrecy jurisdictions that deviate from typical customer profiles.
- Reveals hidden layering or structuring attempts using stored value products in offshore locations.
- [Alternative Payment Channels](https://framework.amltrix.com/techniques/T0134) — - Collects transaction amounts, load frequencies, withdrawal endpoints, and card identifiers specific to prepaid cards.
- Enables identification of rapid loading or withdrawal patterns across multiple locations, revealing potential structuring or layering attempts.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Tracks prepaid card loading, usage, and withdrawal patterns tied to offshore gambling accounts.
- Detects large or frequent cross-border fund movements lacking corresponding betting records.

By monitoring prepaid card activity, investigators can uncover layering strategies exploiting semi-anonymous cards linked to offshore gambling operators.

---

## [Correspondent and Cross-Border Transaction Data](https://framework.amltrix.com/data-sources/DS0047)

**Description:**
Information on cross-border financial transactions, covering transaction amounts, participating institutions, involved countries, currencies, settlement processes, and account relationships. This data is typically collected from banks, payment processors, and other intermediaries through correspondent banking relationships.

### Related Techniques
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Captures cross-border transaction details and intermediary relationships, revealing potentially unlicensed or informal channels used in hawala arrangements, where funds are transferred across jurisdictions outside formal banking routes.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Contains details of cross-border payments, including intermediary banks, countries of origin/destination, currencies, and settlement methods.
- Detects rapid layering of funds across multiple jurisdictions to obscure origins, a common tactic in pig butchering.
- Assists in tracing international pathways that lack commercial or personal justification.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Details cross-border payments, including amounts, countries, bank intermediaries, and settlement references.
- Facilitates the detection of mismatches between declared shipping/invoice data and actual cross-border funds movement, flagging manipulated settlement documents.
- [Currency Exchange Conversions](https://framework.amltrix.com/techniques/T0115) — - Captures cross-border wire transfers involving different countries and currencies.
- Facilitates the identification of multi-jurisdictional layering by linking currency conversion activities to subsequent international transfers.
- Enables the detection of high-risk patterns where criminals quickly move converted funds to foreign accounts.
- [Money Mule Exploitation](https://framework.amltrix.com/techniques/T0011) — Provides detailed records of international transaction flows, including originating and beneficiary institutions, involved countries, currencies, and settlement processes. This data helps identify cross-border funds movement indicative of multi-jurisdictional money mule networks, revealing patterns where mules funnel illicit proceeds through multiple accounts across different regions.
- [Remittance Splitting](https://framework.amltrix.com/techniques/T0016.003) — - Provides comprehensive views of cross-border transactions, including sending/receiving institutions, countries, currencies, and settlement details.
- Identifies the geographic dispersion of remittances and traces funds converging on a single beneficiary.
- Aids in uncovering layering strategies that leverage multiple regions to obscure the origin of illicit proceeds.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — Contains comprehensive information on cross-border financial transactions, including details on participating institutions, origin and destination countries, currencies, settlement processes, and account relationships. Given the rapid rerouting of funds across multiple jurisdictions in automated layering schemes, this data is essential for detecting suspicious multi-jurisdictional flows and identifying potentially orchestrated cross-border transactions designed to obscure illicit origins.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Details cross-border transfers, currencies, and financial intermediaries connected to sponsorship or image-rights payments.
- Highlights repeated inflows from high-risk jurisdictions and offshore accounts, aligning with known methods of layering illicit funds through international sports deals.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Contains details of cross-border transactions, including amounts, currencies, involved financial institutions, and beneficiary jurisdictions.
- Crucial for detecting rapid, complex fund flows across multiple countries linked to carbon credit payments and immediate transfers through special-purpose vehicles.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Tracks cross-border payments, involved institutions, jurisdictions, and transaction details.  
- Identifies unsubstantiated foreign transfers or high-value cross-border flows inconsistent with the stated commercial profile, indicative of potential front company laundering.
- [Online Gambling](https://framework.amltrix.com/techniques/T0017) — - Contains details on cross-border wires, correspondent banking relationships, intermediary banks, and settlement processes.
- Reveals the movement of funds to or from high-risk or lightly regulated jurisdictions.
- Assists investigators in tracing complex cross-border layers of gambling-related transactions.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Tracks international fund movements, including originating and beneficiary institutions, currencies, and settlement details. This data is crucial for identifying high-risk cross-border transfers tied to corrupt officials moving illicit proceeds offshore.
- [Geographically Dispersed Cash Deposit](https://framework.amltrix.com/techniques/T0053) — - Contains information on international transaction flows passing through correspondent banking channels, including amounts, sending/receiving institutions, and involved countries.
- Reveals cross-border deposits and subsequent fund transfers that may hide illicit proceeds.
- Supports investigations into the rapid movement of aggregated funds across multiple financial institutions abroad.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Contains information on cross-border financial transactions and the institutions involved, covering origins, destinations, currencies, and settlement details. This data assists in:

- Identifying frequent or high-value movement of precious metals or gemstones across jurisdictions incongruent with a customer’s usual operations.
- Detecting trade flows through high-risk or non-transparent channels.
- Tracing cross-border patterns consistent with layering and integration strategies.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Provides detailed information on cross-border financial transfers, including involved institutions, sending/receiving jurisdictions, and transaction amounts.
- Assists in identifying suspicious international wires, multi-jurisdictional layering, or unusual volumes linked to smuggling routes.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Consolidates cross-border payment flows, including involved financial institutions, jurisdictions, currencies, and settlement information.
- Pinpoints high-risk or secrecy jurisdictions in transaction chains, helping to track layered or repeated transfers designed to obscure beneficial ownership.
- Supports the investigation of offshore or secrecy exploitation by maintaining a clear record of international money movements and counterparty relationships.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Captures information on cross-border payments, correspondent banking relationships, and involved jurisdictions.
- Highlights unusual payment flows and layering across multiple countries when funds pass through FTZs.
- Provides details to confirm whether declared routing aligns with legitimate business needs.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Includes cross-border financial transactions, participating institutions, currencies, and settlement details. This data helps investigators:

- Identify missing or anomalous payment records, suggesting the use of informal channels for settlement.
- Track the movement of funds across jurisdictions to expose potential laundering patterns.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — Captures details of cross-border financial transactions, including currencies, amounts, originators, beneficiaries, and participating financial institutions. This data helps identify sanctioned or high-risk jurisdictions and uncovers potential sanctions evasion by analyzing transaction patterns and corridors.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Documents cross-border financial flows, including involved jurisdictions and intermediary banks.
- Helps track offshore payment routes and identify secrecy-prone regions, exposing layering or other steps undertaken to obscure the origin of illicit funds in image rights deals.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Contains information on cross-border transactions, including origin and destination countries, currencies, involved banks, and transaction volumes.
- Highlights inconsistencies in cross-border gold transfers and identifies geographic anomalies not aligned with the customer's profile or business.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Contains records of international financial transfers, including intermediaries, involved countries, and transaction details.
- Helps detect structuring or layering across multiple jurisdictions commonly used to obscure drug proceeds.
- Supports tracing funds back to their origin or through complex networks of correspondent accounts linked to drug syndicates.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Captures cross-border wire transfers, including origin and destination institutions and jurisdictions.
- Helps trace complex layering through multiple shell entities across different countries.
- Identifies high-volume or frequent transfers that lack a legitimate economic purpose.
- [Correspondent Banking](https://framework.amltrix.com/techniques/T0104) — Provides detailed records of cross-border wires, including originator and beneficiary details, amounts, currencies, involved institutions, and settlement processes. This helps detect frequent or suspicious patterns, identify missing or incomplete originator/beneficiary data, and flag potential layering or infiltration of illicit funds within the correspondent banking chain.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Tracks cross-border financial flows, including involved institutions, jurisdictions, settlement processes, and currency exchanges. By examining these transaction records, investigators can pinpoint complex layering across multiple jurisdictions, detect irregular fund movements, and identify unsubstantiated cross-border investment transfers.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Details cross-border payments, including sending and receiving institutions, countries involved, transaction amounts, and frequency.
- Helps identify unusual or frequent overseas transfers associated with mule accounts, particularly those lacking legitimate business or personal rationale.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Contains records of cross-border transactions, including sending and receiving institutions, jurisdictions, and transaction amounts.
- Detects unregistered MSBs moving funds internationally without proper oversight.
- Identifies questionable or high-risk inter-jurisdictional payment flows commonly exploited by illicit MSBs.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — This data includes cross-border transaction amounts, participating institutions, involved countries, currencies, settlement processes, and account relationships. It enables tracing of intermediary banks and jurisdictions used within transaction chains, identifying anomalies such as omitted standardized data fields, routing through high-risk jurisdictions, and layering across multiple regulators.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Documents financial transfers across multiple jurisdictions, including originating and beneficiary institutions, as well as settlement details.
- Helps identify the rapid movement of funds that are disproportionate to legitimate oil business structures.
- Provides insight into networks or payment channels frequently used to layer proceeds derived from manipulated oil transactions.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Covers international transaction details, including amounts, counterparties, currencies, and involved institutions.
- Enables pinpointing regions or corridors linked to high-risk commodity trafficking routes.
- Assists in identifying unusual cross-border flows not aligned with legitimate trade activities.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Logs cross-border remittances, participating banks, currencies, and settlement details.
- Helps detect unreported offshore flows or profit shifting across jurisdictions designed to minimize tax liabilities.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Contains details on cross-border transfers, including involved jurisdictions, currencies, and settlement processes.
- Helps identify international layering or rapid fund displacement associated with advance fee fraud proceeds, particularly when scammers move victim payments offshore quickly to evade detection.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Tracks cross-border payment flows, including involved banks, currencies, and jurisdictions.
- Identifies unusual routing or fragmentation of payments tied to documentary collection transactions.
- Helps uncover multi-bank involvement or transactions lacking commercial rationale, indicative of possible manipulations.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Captures cross-border transaction details, covering participating financial institutions, currencies, and settlement processes. Analyzing these records reveals foreign reloads, withdrawals, and transfers linked to offshore e-wallets or prepaid cards, highlighting potential layering through secrecy jurisdictions.
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Captures details of cross-border funds transfers (e.g., amounts, involved banks, jurisdictions).
- Permits identification of repetitive or circular money flows across multiple accounts in different countries.
- Reveals patterns consistent with carousel fraud's cyclical trade and VAT-based illicit proceeds.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Provides details of cross-border wires and related transactions, including amounts, originating and destination countries, and financial intermediaries. This data helps identify suspicious or high-value cross-border transfers linked to antiquities transactions that do not match the customer’s declared business operations.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Details intermediary banks, routing information, and settlement processes for cross-border wires.
- Helps trace funds through multiple financial institutions and countries, revealing the layering chain in wire transfer schemes.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Captures cross-border fund transfers, including correspondent banking details, originating and destination countries, and transaction amounts. This data reveals suspicious cross-border flows into or out of offshore insurance policies.
- [Virtual Token](https://framework.amltrix.com/techniques/T0067) — - Covers cross-border financial flows, associated institutions, currencies, and settlement processes.
- Enables correlation of stablecoin or token movements with foreign transactions, helping detect abrupt cross-border layering or swift swaps intended to evade oversight.
- Supports identification of uncharacteristic international fund transfers that align with virtual token obfuscation strategies.
- [Multiple Currency Conversions](https://framework.amltrix.com/techniques/T0115.001) — - Covers cross-border financial transactions with details on amounts, currencies, jurisdictions, settlement chains, and account relationships.
- Helps identify repeated cross-border layering or jurisdiction mismatches in currency conversion flows, supporting the investigation of structured transactions routed through multiple countries.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Details on cross-border payment flows, corresponding financial institutions, and involved jurisdictions.  
- AML Relevance: Tracks complex international fund transfers that may indicate layering attempts via fictitious trade routes, highlighting risky jurisdictional patterns.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Covers routing details, involved financial institutions, originating countries, and settlement processes for cross-border transactions.
- Identifies funds sourced from or passing through offshore financial centers with lax AML controls, indicating potentially illicit foreign investments.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Details transactions routed through correspondent banks or cross-border channels, identifying sending institutions, recipient accounts, and countries of origin/destination.
- Reveals large incoming transfers from high-risk or non-cooperative jurisdictions specifically directed into CBI/RBI-related accounts, supporting scrutiny of unexplained inflows.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Includes detailed records of cross-border transactions, participating financial institutions, currencies, and settlement processes.
- Facilitates identification of repetitive or high-volume international flows to jurisdictions associated with hawala or other IVTS.
- Assists in flagging unusual settlement patterns bypassing standard wire transfers or regulated channels.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Information tracks international fund transfers, detailing intermediary banks, routing paths, currencies, and involved jurisdictions. This data allows investigators to trace complex cross-border flows under the guise of M&A deals, exposing potential layering or concealment tactics common in fictitious or inflated M&A transactions.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Documents cross-border payment flows, intermediary banks, and settlement routes.
- Exposes hidden or layered transactions processed through multiple payment service providers.
- Supports deeper scrutiny of foreign-based agents and sub-agents masking the ultimate origin or destination of funds.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Captures cross-border payments, including settlement details, involved institutions, and participating jurisdictions. This data assists in detecting significant inbound or outbound transfers routed through OTC brokers, potentially indicating unregulated international flows.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Details cross-border payment flows, correspondent banking relationships, and participating financial entities. This data helps identify overlapping financing of the same shipment or services through different institutions, which is a key indicator of multiple invoicing activity.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Covers international transactions routed through correspondent banking relationships, including originating and beneficiary institutions, involved countries, and transaction amounts.

- Enables tracing of funds flowing to or from known conflict zones or arms-producing regions, revealing high-risk corridors associated with illicit arms trade.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Captures cross-border payment details, including origin and beneficiary banks, involved jurisdictions, and transaction values. By analyzing international flows, it highlights the transnational layering of illegal logging proceeds and flags unusual routing patterns.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Provides information on cross-border transactions and correspondent banking relationships.
- Reveals patterns of layered transfers across jurisdictions used to distance illicit wildlife proceeds from their origin.
- Facilitates the identification of high-risk corridors or account relationships indicative of laundering activity.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Records cross-border and correspondent banking flows associated with insurance premium payments and policy payouts.
- Flags transactions from or to high-risk jurisdictions, indicating potential layering through multiple regions.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Contains details of international financial transactions, including amounts, currencies, geographic routing, and participating financial institutions.
- Assists in uncovering cross-border layering and complex payment flows commonly used to conceal illicit proceeds from child exploitation.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Covers multi-jurisdictional financial flows linked to Bill of Exchange arrangements, including transaction pathways, intermediary banks, and cross-border payment details. This data can reveal layering and circuitous routes typical of trade-based money laundering.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Tracks cross-border fund flows and intermediary banks for timeshare fee transactions.
- Identifies payments to offshore jurisdictions or accounts with no legitimate business rationale.
- Highlights unusual international transfer patterns inconsistent with genuine real estate or closing services.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Covers cross-border payment information, including foreign currency flows and remittance channels.
- Identifies unlicensed or informal pathways used to route tax refunds offshore, potentially avoiding regulatory scrutiny.
- Reveals patterns of layering and fund diversion involving international transfers.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Details of international wire transfers, including transaction amounts, involved countries, intermediaries, and settlement processes. This data reveals how ransom funds may be moved across multiple jurisdictions, aiding in detecting layered flows aimed at concealing illicit maritime piracy proceeds.
- [Knowledge Compartmentalization](https://framework.amltrix.com/techniques/T0149) — Encompasses cross-border transaction details, including amounts, jurisdictions, and participating institutions. Identifies partial transaction patterns spread across different banks or countries, revealing a lack of a unified overview and indicating possible knowledge compartmentalization.
- [Lottery Scams](https://framework.amltrix.com/techniques/T0144.015) — Documents cross-border wires and transactions routed through multiple institutions or jurisdictions. Investigators can identify structuring or layering across remittance channels—a common tactic in lottery scams—by tracing the flow of funds associated with suspicious accounts or recurring scam references in payment details.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Captures transaction details for cross-border payments, including amounts, originating and beneficiary banks, jurisdictions, and settlement routes.
- Enables monitoring of funds transferred from offshore sources into foreign real estate acquisitions.
- Helps detect unusual cross-border flows potentially linked to laundering via foreign property holdings.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Consolidates cross-border transaction details, including institutions involved, countries of origin and destination, currencies, and settlement processes.

This data helps expose net settlement flows across multiple jurisdictions that bypass standard banking or MSB channels, a hallmark of Hot Transfers.
- [Counterfeit Pharmaceuticals](https://framework.amltrix.com/techniques/T0143.003) — Details cross-border funds flow and participating financial institutions, facilitating the detection of suspicious international transfers linked to unregulated pharmaceutical shipments or payments.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Provide details on cross-border money flows, beneficiaries, and involved financial institutions.
- Expose international transfers from or to suspicious jurisdictions.
- Help confirm whether the rapid cross-border movement of funds aligns with a fake job scheme.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Details cross-border transactions, including intermediary and beneficiary institutions, currencies, and involved jurisdictions. This data:

- Reveals multi-hop routing through multiple foreign banks to disguise fund origins.
- Highlights repeated correspondent relationships in high-secrecy jurisdictions.
- Aids in tracing complex layering schemes involving offshore financial institutions.
- [Node Exchange Provisioning](https://framework.amltrix.com/techniques/T0013.003) — Captures cross-border financial flows, detailing transaction amounts, locations, and intermediary institutions. Analysis can reveal patterns where funds move among multiple jurisdictions without transparent business purposes, consistent with NEP’s rapid cross-currency exchanges.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — Provides detailed records of international funds transfers, including amounts, participant institutions, routing details, and settlement processes. Investigators can:

- Compare electronically transferred funds with declared cash movements to uncover inconsistencies.
- Detect layering attempts by tracing cross-border flows through multiple jurisdictions.
- Identify suspicious patterns in cross-border transactions that do not align with legitimate business activities or declared sums.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Covers cross-border payment flows, detailing sending and receiving institutions, involved countries, amounts, and settlement timelines.
- Helps reveal potential layering of smuggled diamond proceeds through multiple jurisdictions or financial institutions.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Information on international wires, intermediary banks, and beneficiary locations.
- Allows tracing of funds routed through multiple jurisdictions, highlighting layering patterns or transfers to secrecy havens often used by illicit private funds.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Details on cross-border fund flows, including amounts, counterparties, jurisdictions, and payment intermediaries.
- Aids in identifying repetitive or circuitous inter-company transfers that may indicate artificially layered transactions or inflated/deflated transfer pricing across multiple jurisdictions.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Tracks international financial transfers, including intermediary banks, ultimate beneficiaries, and cross-border account relationships.
- Identifies complex layering or routing patterns used to shuttle inflated export proceeds to unrelated third-party accounts.
- Helps pinpoint final destinations of suspicious cross-border payments.
- [Virtual IBANs](https://framework.amltrix.com/techniques/T0027) — Captures cross-border transaction details, such as origin and destination countries, intermediary banks, currencies, and settlement paths. This helps identify multi-jurisdictional layering or suspicious rerouting of funds via virtual IBANs, clarifying the true flow of funds and highlighting potential high-risk regions involved.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Tracks cross-border reinsurance payments to detect unusually large or frequent transactions.
- Highlights offshore reinsurance flows potentially aimed at hiding illicit proceeds or layering schemes.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Provides details of cross-border funds transfers, including sending and receiving financial institutions, involved countries, currencies, amounts, and settlement processes. This information is vital for tracing value shifts across jurisdictions following or in conjunction with mirror trading, revealing suspicious layering or rapid flow of proceeds internationally.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — - Provide details of funds transfers between different jurisdictions, including amounts, participating institutions, and settlement processes.
- Help identify large or frequent transnational movements inconsistent with normal business activities, which are common in trafficking networks.
- Aid in tracing layered transactions across multiple borders to obscure illicit origins.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Captures transaction amounts, originating and beneficiary institutions, jurisdictions involved, and settlement processes.
- Helps identify chains of letters of credit across multiple banks by tracking cross-border issuance and usage.
- Reveals circular or closed-loop structures when funds revert to the original source under the guise of trade finance.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Comprises records of cross-border payments, including transaction details, currencies, involved countries, and counterparties. Reviewing this data alongside identity documents can highlight instances where an individual alternates between different nationalities or passports when directing funds internationally, signaling potential evasion of consistent due diligence controls.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Captures details of cross-border financial movements, including intermediary banks, involved jurisdictions, and transaction routes. This helps identify layered investments passing through multiple accounts or high-risk regions before reaching the target business.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — - Details cross-border transactions routed through correspondent banks, including settlement processes and involved institutions.
- Enhances visibility of multi-jurisdictional layering often used in trade finance manipulation.
- Reveals unusual cross-border flows that deviate from legitimate trade activity or established routes.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Information on international financial transactions, intermediary banks, payer/payee details, settlement processes, involved jurisdictions, and currency flows.

- Direct AML Relevance: Uncovers third-party or intermediary payments common in Black Market Peso Exchange, revealing cross-border transfers that bypass regulated channels or official exchange rates.
- [Cuckoo Smurfing](https://framework.amltrix.com/techniques/T0016.002) — - Details cross-border remittances, including intermediary banks, jurisdictions, and settlement processes.
- Identifies unexplained routing changes or partial arrivals consistent with hijacked inbound transfers typical of cuckoo smurfing.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Captures details of cross-border transactions, participating institutions, involved jurisdictions, and newly added correspondent banking relationships. This information helps detect infiltration by revealing sudden growth in high-risk cross-border activities or the rapid expansion of correspondent ties in jurisdictions known for lax AML enforcement, indicating criminals leveraging a controlled institution to layer illicit funds.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Captures international wire transfers, participating countries, and associated beneficiaries or intermediaries. Highlights rapid or high-volume fund movements routed through proxy-held accounts to obscure the original source or beneficial owner.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Captures international fund transfers across multiple institutions. Monitoring these flows is critical for tracing how red/green clause LC proceeds are rapidly dispersed, layered, or redirected to diverse jurisdictions without a clear commercial purpose.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Captures cross-border payment flows, including involved jurisdictions, transaction amounts, and counterparties. By highlighting frequent shifts between countries with varying AML regulations, this data helps identify structured layering strategies that exploit less-regulated corridors.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Details cross-border payments, correspondent banking arrangements, and involved jurisdictions.
- Helps identify high-frequency or repeated payments linked to the same diamond shipments, indicating potential layering.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Contains settlement and routing details for international payments, including involved countries, intermediary banks, and transaction amounts.
- Assists in identifying complex or layered payment structures that may facilitate or mask misinvoiced trade flows.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Provides information on cross-border fund flows and correspondent banking relationships. By examining transaction routes, involved jurisdictions, and unusually high volumes for intangible entities, investigators can uncover red flags consistent with online-only enterprises operating in secrecy-friendly regions.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Capture information on interbank and international transfers, including originating and beneficiary institutions, countries, and transaction amounts.
- Expose patterns of offshore layering or funneling public monies to secrecy jurisdictions where funds are harder to trace.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Captures international payment flows, including sending institutions, beneficiary details, and intermediary banks. Investigators can trace how illicit proceeds from smuggled goods are routed through multiple jurisdictions, bypassing standard trade finance channels.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Contains information on cross-border financial transactions, including involved financial institutions, jurisdictions, settlement details, and transaction flows.
- Highlights potential layering across multiple countries and jurisdictions by analyzing transaction routes and detecting abnormal or high-risk payment paths.
- Useful for uncovering suspicious currency conversions or advanced payment structures indicative of foreign exchange manipulation in trade.
- [Smurfing](https://framework.amltrix.com/techniques/T0016.005) — Provides details on inbound and outbound wire transfers, including sender/receiver information, amounts, currencies, and jurisdictions. This data supports smurfing detection by:

- Detecting frequent small-value cross-border transfers that may be structured.
- Identifying elements of cuckoo smurfing where legitimate inbound remittances are co-opted to disguise illicit funds.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Provides comprehensive records of cross-border transactions, detailing intermediary banks, involved countries, currencies, and settlement processes.
- Identifies complex, multi-jurisdictional transaction chains executed by local sub-agents.
- Enhances AML monitoring by revealing unusual cross-border flows lacking legitimate economic rationale.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Captures details of international pension contributions and cross-border transfers, including amounts, currencies, and involved institutions. This enables the detection of funds rapidly moving across jurisdictions and identifies layering patterns indicative of potential money laundering within pension schemes.
- [Transaction Chaining](https://framework.amltrix.com/techniques/T0070) — - Provides details on cross-border transactions, including amounts, involved countries, and intermediary institutions.
- Enables detection of frequent or high-risk cross-jurisdictional transfers, a hallmark of Transaction Chaining.
- Assists investigators in identifying unusual multi-jurisdictional transaction routes that lack economic justification.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Contains records of international wire transfers, including sending/receiving banks, jurisdictions, amounts, and timestamps.
- Directly helps identify patterns of cross-border funds movement into jurisdictions offering CBI/RBI.
- Supports investigations by revealing high-risk corridors or unusually large inbound transfers that may indicate illicit funds being deployed to secure new residency or citizenship status.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Tracks cross-border transactions, routes, intermediary banks, and jurisdictions used.
- Aids in spotting convoluted routing paths across multiple jurisdictions often used in layering and circular transactions.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Contains information on cross-border transfers, intermediary banks, involved countries, currencies, and settlement instructions.
- Allows detection of repeated or high-value flows from jurisdictions with weak AML oversight, consistent with multi-jurisdiction layering in entertainment ventures.
- Aids in monitoring suspicious routes of foreign revenue inflows purportedly from ticket sales or licensing abroad.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Includes cross-border payment details, such as jurisdictional information, currency flows, and transaction relationships, revealing if bond proceeds or interest payments are routed to high-risk or offshore locations without a clear business rationale.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Documents cross-border payments, correspondent banking relationships, transaction volumes, and currency flows.
- Helps detect excessive or complex layering of funds through multiple MSB or correspondent accounts beyond established business needs.
- Supports AML investigations by highlighting international movement of funds indicative of controlled or complicit MSBs facilitating hidden beneficiaries.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Captures details of cross-border financial transactions, including intermediary or offshore routing, involved institutions, and currencies.

How it supports AML detection:
- Detects settlement proceeds channeled through unusual jurisdictions or third-party accounts.
- Highlights inconsistencies in payment flow timelines, suggesting possible manipulation of the legal process to launder illicit funds via offshore accounts.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Details cross-border financial transactions, including currencies, intermediary banks, and originating/destination jurisdictions.
- Identifies complex routing patterns through offshore accounts or high-risk locations, consistent with layering practices.
- Enables detection of multi-jurisdictional payment flows lacking valid business justification.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Details international transaction pathways, counterparties, and intermediary banks.
- Identifies cross-border layering or structuring through multiple jurisdictions to disguise illicit proceeds within in-game economies.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Captures transaction flows between different jurisdictions, currencies, and financial institutions.
- Reveals cross-border elements in real estate purchases and sales, helping trace the origin of funds when flipping properties through escrow.
- [Daigou Networks](https://framework.amltrix.com/techniques/T0013.006) — Captures details of cross-border payment flows and correspondent banking relationships, helping identify:

- Rapid transfers of pooled funds from multiple sources to overseas accounts for high-value goods purchases.
- Patterns of rotating beneficiary accounts distributing payments for suspected Daigou shipments.

Analysts can detect unusual inflows and outflows indicative of money laundering through surrogate shopping or unregistered trade channels.

---

## [Sanctions Lists](https://framework.amltrix.com/data-sources/DS0018)

**Description:**
Sanctions lists are **official compilations of individuals, entities, and jurisdictions** subject to economic, trade, or financial restrictions imposed by governments and international bodies. These lists are a critical data source for Anti-Money Laundering (AML), Counter-Terrorist Financing (CTF), and Counter-Proliferation Financing (CPF) programs, as they help financial institutions identify **prohibited or high-risk parties** in transactions and customer relationships.  

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

### Related Techniques
- [Correspondent Banking](https://framework.amltrix.com/techniques/T0104) — Encompasses official sanctions lists maintained by governments and international bodies. Screening cross-border transactions against these lists ensures that no illicit payments are processed for sanctioned entities or jurisdictions, helping the correspondent bank uphold sanctions compliance and mitigate AML risk.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — Consolidated sanctions lists from regulatory bodies (e.g., OFAC, UN, EU) detail sanctioned individuals, entities, and vessels. Cross-referencing transactions, beneficial ownership records, and business relationships against these lists enables the direct identification of sanctioned parties attempting to circumvent restrictions.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Official listings of sanctioned individuals, entities, and jurisdictions subject to financial restrictions.
- Ensures sponsors, clubs, or related intermediaries are not sanctioned, preventing illicit funds from passing through disguised sports marketing deals.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Consolidates sanctioned and embargoed individuals, entities, and jurisdictions subject to financial or trade restrictions.

- Arms traffickers often appear on lists related to arms embargoes or national security designations, making sanctions screening essential for blocking or scrutinizing suspicious transactions.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Official compilations of sanctioned individuals, entities, and jurisdictions subject to asset freezes and other restrictions.
- Helps detect attempts to evade sanctions by rapidly swapping assets, a known misuse of instant exchange platforms.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Official compilations of individuals and entities subject to economic, trade, or financial restrictions issued by governments and international bodies.
- Ensures that applicants or beneficial owners under sanctions are flagged, preventing them from using CBI/RBI programs to circumvent restrictions and launder illicit proceeds.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Comprehensive listings of sanctioned individuals, entities, and jurisdictions subject to financial restrictions. Screening investors and beneficial owners against these lists helps identify previously sanctioned or prohibited parties attempting to invest illicit funds into businesses.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Contains official compilations of sanctioned individuals, entities, and jurisdictions subject to financial restrictions.
- In CBI/RBI contexts, screening applicants and their associated entities against these lists helps detect potentially sanctioned parties attempting to gain new legal status under false pretenses.
- Facilitates AML detection by preventing criminals on sanctions lists from bypassing controls through alternate citizenship or residency.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Official listings of individuals, entities, and jurisdictions subject to economic or financial restrictions.
- Allows screening for sanctioned parties or jurisdictions linked to illicit account activity, aiding in identifying unauthorized dealings and heightened AML risk associated with mule transactions.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Official compilations of entities under economic or financial restrictions are essential tools. By screening OTC brokers and their customers against these lists, investigators can identify sanctioned or politically exposed individuals who may be exploiting OTC services to bypass regulated channels.
- [Piracy](https://framework.amltrix.com/techniques/T0148) — Comprehensive listings of sanctioned individuals and entities include those designated for piracy or kidnapping for ransom. Screening transactions against these lists helps block or investigate flows potentially linked to sanctioned pirate groups or their facilitators.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Consolidates individuals, entities, and jurisdictions subject to sanctions, often including those designated for narcotics trafficking.
- Supports customer due diligence and real-time transaction screening to identify blocked or high-risk parties.
- Alerts financial institutions to freeze assets or reject transactions involving sanctioned drug traffickers.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Official watchlists identify designated individuals and their known aliases. Screening customers against these lists highlights attempts to evade sanctions by using variations or subtle misspellings of sanctioned names.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Comprises official lists of individuals, entities, and jurisdictions subject to economic or financial restrictions.
- Enables the screening of donors, beneficiaries, or affiliated parties who may be designated or tied to terrorist organizations.
- Helps detect and block funds linked to sanctioned or prohibited entities attempting to exploit charitable structures.

---

## [System & Network Access Logs](https://framework.amltrix.com/data-sources/DS0025)

**Description:**
Centralized logs capturing user and system activities, network and web traffic, authentication events, IP addresses, timestamps, URLs visited, user-agent strings, and other related details. These logs provide audit trails of user activities and help identify unauthorized access or unusual system interactions.

### Related Techniques
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Tracks user logins, account modifications, and system actions preceding early superannuation withdrawal filings. Alerts investigators to unauthorized activity or rapid account changes consistent with fraudulent or stolen identity claims.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Records device and network usage data, including login IP addresses, timestamps, and session activities. Conflicts between declared residence and consistent foreign IP origins can reveal misrepresented location details indicative of identity manipulation.
- [Chain Hop](https://framework.amltrix.com/techniques/T0005) — - Captures IP addresses, authentication events, and device fingerprints correlated with blockchain bridging transactions.
- Identifies irregular login patterns and rapid device or IP changes that align with cross-chain hops, suggesting potential illicit access or layered laundering attempts.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Track user activity in banking and AML systems, including authentication events, access privileges, override submissions, and data modifications.
- Reveal patterns of employees disabling alerts, bypassing controls, or making suspicious system changes consistent with insider facilitation.
- [In-Person Gambling Imitation](https://framework.amltrix.com/techniques/T0107) — - Records IP addresses, user authentication events, and device usage within gambling platforms.
- Correlates multiple gambling accounts linked by common IPs or devices, helping detect collusive behavior or funneling of funds to a single account.
- Supports investigations into suspicious transactions and staff involvement by providing audit trails of account access and administrative actions.
- [Virtual Private Network](https://framework.amltrix.com/techniques/T0015.001) — - Provides user login records, including IP addresses, timestamps, device information, and geolocation data.
- Enables identification of known VPN or proxy endpoints and detection of sudden, improbable location changes.
- Facilitates investigation by correlating unusual login patterns with potential layering or obfuscation attempts.
- [Cross-Platform Trading](https://framework.amltrix.com/techniques/T0066.002) — Tracks user authentication events, IP addresses, device fingerprints, and account activities across multiple platforms. This reveals potential connections or repeat logins indicative of coordinated cross-game transfers or clandestine 'gifting' strategies.
- [In-Game Currency & Microtransaction Exploits](https://framework.amltrix.com/techniques/T0066.003) — - Captures user login events, IP addresses, device fingerprints, and related session data within gaming platforms.
- Helps identify clusters of interlinked player accounts, item transfer patterns, and minimal legitimate game activity despite large in-game transactions.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Centralized logs capture user actions and system activity, including edits to transaction details or supporting documentation. These logs help detect unauthorized changes to transaction purposes after scrutiny.
- [Virtual Worlds](https://framework.amltrix.com/techniques/T0066) — Collects user login details, IP addresses, session timestamps, and device information. It aids in detecting frequently changing IPs, multiple concurrent connections, or cross-region logins—patterns often associated with layered laundering activities in virtual worlds.
- [Anonymous Networking](https://framework.amltrix.com/techniques/T0015) — - Captures network traces, IP addresses, authentication events, and multi-hop routing paths.
- Helps investigators observe the use of layered encryption or repeated connections from Tor, VPNs, or proxy servers, pinpointing suspicious anonymity-driven access during financial transactions.
- [Automated Transaction Systems](https://framework.amltrix.com/techniques/T0026) — - Captures IP addresses, user authentication events, and device information associated with transaction initiations.
- Helps identify unusual device usage or script-driven accesses that can indicate automated or bot-driven transfers.
- Enables correlation of suspicious transaction patterns with specific login events and potential unauthorized system activities.
- [Darknet Marketplace Transactions](https://framework.amltrix.com/techniques/T0100) — - Captures user access points, including IP addresses, timestamps, and authentication details.
- Helps identify the use of Tor or other anonymizing services during logins and transaction sessions, which is frequently associated with Darknet marketplace activity.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Captures user actions within internal systems, including timestamps, login details, and administrative overrides.
- Identifies repeated or unjustified suppression of AML alerts, manual overrides of monitoring rules, and other complicit staff activities.
- Enables auditors and investigators to trace potential internal collusion that allows illicit transactions to remain undetected.
- [Cryptojacking](https://framework.amltrix.com/techniques/T0020.002) — Provides details of user sessions, device resource usage (e.g., CPU/GPU consumption), IP addresses, and network connections. This information helps detect unauthorized cryptomining software or unusual outbound traffic to cryptomining pools, enabling timely identification and investigation of cryptojacking activities.
- [Account Compromise](https://framework.amltrix.com/techniques/T0076) — - Records IP addresses, timestamps, and user sessions associated with account access.
- Helps correlate suspicious login events (e.g., from unexpected locations or times) with possible account takeover activity.
- [Cryptocurrency Mining](https://framework.amltrix.com/techniques/T0020) — - Captures login events, IP addresses, and network usage patterns.
- Identifies VPN or proxy usage that may hide the true location of mining equipment or cloud-based services.
- Helps detect anomalous remote access and potential obfuscation methods used by illicit miners.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Captures user login activities, IP addresses, device IDs, and related metadata for e-commerce or payment apps. This data helps identify suspicious usage patterns, such as multiple transactions from the same IP or device under different accounts, revealing potentially coordinated manipulation.
- [Chip Dumping](https://framework.amltrix.com/techniques/T0107.003) — - Contains IP addresses, device fingerprints, login timestamps, and other network metadata.
- Identifies cases where multiple purportedly separate player accounts share common access points, indicating potential collusion.
- Assists in uncovering suspicious account overlaps, rapid logins from the same device, and other anomalies consistent with chip dumping schemes.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Record IP addresses, device identifiers, and login timestamps, highlighting geographic or device inconsistencies with the claimed identity.
- Provide audit trails to investigate unauthorized sessions and potential misuse of stolen or fabricated credentials.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Captures user authentication events, IP addresses, timestamps, and changes to account settings (e.g., email, phone).
- Allows detection of unusual or repeated contact detail updates following large inbound 'fee' payments, a common indicator in advance fee fraud schemes.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Tracks user access events, including logins, timestamps, and IP addresses. By correlating expense report modifications with these logs, investigators can detect suspicious after-hours edits, backdating attempts, or repeated modification patterns that indicate intentional fraud.
- [Bank Infrastructure Manipulation](https://framework.amltrix.com/techniques/T0132) — - Track user logins, attempted logins, and changes to system configurations (e.g., AML thresholds, security settings).
- Provide timestamps, user credentials, and activity trails to help investigators detect unauthorized overrides or suspicious after-hours access to administrative functions.
- Facilitate the identification of insider collusion by correlating access patterns with altered AML triggers or disabled security protocols.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Captures detailed traces of user activities, system configurations, and monitoring rule changes. This data helps uncover unauthorized tampering with AML software or the disabling of compliance alerts by insiders, a hallmark tactic when criminals infiltrate a financial institution to suppress detection.
- [Remote Verification Bypass](https://framework.amltrix.com/techniques/T0135) — - Tracks the usage of remote control or screen-sharing tools during the verification process.
- Logs user and system activities (e.g., IP addresses, timestamps, application launches) to identify potential third-party manipulation of the verification interface.
- Helps uncover suspicious remote sessions that may subvert legitimate biometric or ID checks.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Records IP addresses, device information, session timestamps, and login attempts.
- Identifies logins or transaction instructions originating from IPs linked to known scam call centers or high-risk jurisdictions.
- Supports investigative efforts by mapping suspicious access patterns to pig butchering scam networks.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Captures detailed user and system activities, including IP addresses, login timestamps, and authentication events.
- Helps identify suspicious account creation patterns, such as multiple new accounts from the same device or location, and the repeated use of compromised credentials tied to fake or stolen identities.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Logs user authentication, IP addresses, session details, and potential anonymity software usage (e.g., Tor).
- Identifies suspicious network activity consistent with dark web access used to procure precursor chemicals or equipment.
- Correlates unusual access patterns with financial transaction events.
- [Deepfake Impersonation](https://framework.amltrix.com/techniques/T0144.001) — - Contains records of authentication events, user logins, and network activity, including timestamps, IP addresses, and session details.
- Assists in detecting anomalous successful voice-based authentication attempts or unusual logins that may reveal bypassed security checks due to deepfake impersonation.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Captures staff logins, system changes, overrides of transactions or betting records, and any irregular use of internal systems. Such logs help detect unauthorized tampering or selective bypassing of AML checks for high-value players, indicating potential collusion or malicious insider activity in betting shops.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — Captures detailed user session data, including instances of remote desktop or screen-sharing software used during onboarding. This helps to uncover hidden user environments or bypassed identity verification protocols in remote account setups.
- [Smurfing](https://framework.amltrix.com/techniques/T0016.005) — Captures IP addresses, device identifiers, and login timestamps. This data aids smurfing investigations by:

- Identifying multiple accounts accessed from the same device or IP, signaling potential collusion or single-user control of several smurf accounts.
- Pinpointing suspicious login patterns that correlate with bursts of small deposits in different accounts.
- [Wash Trading](https://framework.amltrix.com/techniques/T0094.002) — - Captures IP addresses, device identifiers, login timestamps, and network session data.
- Reveals patterns of multiple trading accounts or wallets being accessed from the same devices or locations, indicating potential self-dealing.
- Enhances investigations by corroborating evidence of collusion through shared system access points.
- [Proxy Servers](https://framework.amltrix.com/techniques/T0015.002) — - Collects session data, including IP addresses, user-agent strings, timestamps, and authentication events.
- Enables correlation of these IPs with known proxy networks, Tor exit nodes, or suspicious short-term hosting services.
- Facilitates detection of frequent or abrupt IP address changes that indicate possible rotating proxy usage.
- Supports investigation by providing a clear audit trail of user sessions and highlighting anomalous network access patterns.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Tracks user activities, including overrides and clearance of high-risk transactions.
- Identifies unauthorized modifications to AML controls, indicative of bribed insiders covering illicit transactions.
- [Instant Exchange Services](https://framework.amltrix.com/techniques/T0032) — - Tracks IP addresses, device details, login timestamps, and possible use of anonymizing tools (e.g., VPNs).
- Detects unusual access patterns, suggesting attempts to conceal user location or identity on instant exchange platforms.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Tracks user logins, session activities, IP addresses, and record modification events.
- Helps pinpoint unauthorized or off-hours access corresponding to suspected alterations in financial records.
- [Digital Document & Transaction Manipulation](https://framework.amltrix.com/techniques/T0012.002) — Record user activities, authentication events, network traffic, and any attempts to bypass audit functions. Investigators analyze unauthorized balance adjustments or overridden logging mechanisms to identify digital tampering with financial records.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Captures IP addresses, timestamps, and user authentication details for account creation and trading platform access.
- Identifies multiple new accounts associated with the same IP or location, suggesting coordinated manipulative trading.
- Provides audit trails useful in correlating suspicious trading patterns with specific network access events.
- [Onion over VPN](https://framework.amltrix.com/techniques/T0015.005) — - Captures IP addresses, authentication events, and timestamps for user logins and web traffic.
- Allows detection of repeated access attempts from Tor exit nodes or known VPN servers.
- Enables investigators to correlate anomalous login locations with potential use of anonymous networking techniques, supporting timely identification of Onion over VPN usage.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Includes IP addresses, device identifiers, timestamps, and user session records tied to account logins.
- Helps detect multiple supposedly different accounts operated from the same endpoint or device, indicating potential mule networks or account takeovers.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Capture detailed records of user logins, access times, and system alterations.
- Reveal unauthorized updates to government financial systems or records, supporting the detection of tampering or falsified entries that mask stolen funds.

---

## [Donation Platforms & Donor Records](https://framework.amltrix.com/data-sources/DS0026)

**Description:**
Records from online fundraising platforms and associated donation logs, including donor identities, amounts, contribution dates, and intended purposes.

### Related Techniques
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Captures donor identities, contribution amounts, and donation histories from online fundraising or donation platforms.
- Verifies whether a purported campaign actually exists, helping detect sudden, unexplained inflows labeled as charitable gifts.
- Cross-checks donor legitimacy against KYC or external profiles to identify anomalies suggesting a laundering scheme.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Track funds donated for nonprofit-driven construction initiatives, verifying final recipients and usage.
- Flag movements of donated assets into personal or affiliate accounts, revealing misuse or misappropriation.
- Detect signs of layering where charitable funds are redirected under false pretexts of building community infrastructure.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — Provides logs of donors, donation amounts, timestamps, and any recorded details from crowdfunding or charitable donation platforms. This data enables investigators to:

- Track unusual spikes or patterns in donations.
- Identify recurring donors, cross-reference incomplete donor details, or detect multiple donations originating from high-risk sources.
- Correlate donation flow with other indicators (e.g., lack of disclosed fund sources, inadequate KYC) to uncover potential laundering activity within charitable organizations.
- [Disguised Remittance Transfers](https://framework.amltrix.com/techniques/T0040.001) — Collects data from online fundraising platforms, including donor identities, amounts, and stated purposes. This allows investigators to distinguish genuine contributions from remittances falsely labeled as charitable donations, a common tactic for disguising illicit funds.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Provides detailed campaign and donor information, including donor identities, donation amounts, timestamps, and references to specific causes.
- Enables detection of repeat or suspicious donations across multiple campaigns, verifies the authenticity of fundraising appeals, and links them to personal accounts instead of legitimate nonprofit organizations.
- [Crowdfunding Campaign Manipulation](https://framework.amltrix.com/techniques/T0044) — - Contains donor account details, donation timestamps, amounts, and associated metadata (e.g., IP addresses).
- Reveals suspicious patterns such as newly created accounts, repeated or large donations from a small group, or inconsistencies in donor profiles.
- Assists in detecting layered contributions aimed at obscuring the origin of illicit funds.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Logs contributions made via online fundraising or charitable platforms, including donor identities, amounts, and timestamps.
- Exposes suspicious or fabricated charitable campaigns used to solicit fraudulent donations.
- Enables cross-checking of donation patterns against known fraud markers (e.g., misappropriated funds, repeated small deposits).
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Logs of donations, donor identities, and designated recipient information allow for the verification of whether purported charitable contributions align with credible charitable organizations, helping to identify possible misrepresentation.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — This data source comprises records from online fundraising platforms, capturing donor identities, contribution amounts, timestamps, and intended purposes. Examining these logs helps identify suspicious donation patterns, detect multiple reimbursements, and confirm compliance with campaign finance rules, thereby aiding in the detection of illicit political contributions.

---

## [Document Verification](https://framework.amltrix.com/data-sources/DS0027)

**Description:**
Specialized systems or services that authenticate and validate official identification documents—such as passports or IDs—detecting potential forgeries, inconsistencies, or tampering.

### Related Techniques
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Authenticates official logging permits to confirm their validity and detect forgery or tampering. By verifying permit security features and confirming legitimate issuing authorities, it helps uncover falsified documentation used to justify illegal timber harvesting.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Validates the authenticity of official identification documents for auction participants.
- Ensures that buyer and seller identities are legitimate, mitigating the risk of straw identities or shell entities.
- Supports AML investigations by confirming the lawful identity of individuals placing or receiving high-value bids.
- [Early Superannuation Withdrawals](https://framework.amltrix.com/techniques/T0109) — Validates the authenticity of supporting documents, including medical certificates and hardship statements, by checking for alterations, duplicate details, or other red flags indicative of forged paperwork in early superannuation claims.
- [Cash Wage Payments to Undocumented Workers](https://framework.amltrix.com/techniques/T0052.001) — - Authenticates and validates identity documents, checking for forgeries or inconsistencies.
- Detects incomplete or invalid identification details used by workers receiving off-the-books wages, indicating possible undocumented status.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — Provides cross-border routing details (e.g., intermediary banks and institutions, sending jurisdictions) to confirm whether remittances follow expected paths. Deviations from the intended route or unexpected foreign participants may indicate the infiltration of illicit proceeds via cuckoo smurfing.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Employs specialized systems to authenticate official identification documents such as passports and IDs.
- Confirming the validity of employee credentials helps detect forged or falsified identities used to conceal true payroll liabilities.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Checks the authenticity and integrity of submitted documents, such as identification, business licenses, or financial statements. By identifying forgeries or alterations, it helps detect falsified eligibility data used to secure government relief funds.
- [Remote Identity Deception](https://framework.amltrix.com/techniques/T0075.001) — Performs automated checks on remotely submitted identification documents, reviewing document metadata, security features, and potential editing traces, to detect synthetic or falsified identities used in remote onboarding. This directly exposes attempts to evade standard face-to-face verification by forging or altering digital documents.
- [Cross-Border Settlement Document Manipulation](https://framework.amltrix.com/techniques/T0012.001) — - Provides specialized tools and forensic checks to identify tampering, forgery, or digital manipulation in key documents.  
- Enhances the validation of cross-border settlement paperwork by flagging signs of fabricated or altered records, strengthening fraud detection beyond standard trade data reviews.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Authenticates and validates official contracts, ownership documents, and identification records.
- Detects forgeries, inconsistencies, or fraudulent paperwork that enable off-the-record deals by bypassing formal documentation requirements.
- Ensures legal records are genuine, preventing criminals from relying on fictitious agreements to conceal asset ownership or transfers.
- [Regulated Exchange Mule Transactions](https://framework.amltrix.com/techniques/T0011.001) — - Performs authenticity checks on official identification documents, detecting forgeries or tampering.
- Facilitates comprehensive comparisons of submitted ID documents across multiple accounts, identifying repeated use of manipulated credentials.
- [Multiple Citizenship Identities](https://framework.amltrix.com/techniques/T0024) — Offers specialized checks and authentication for identity documents, detecting inconsistencies or forgeries. This is particularly relevant for identifying individuals who present multiple passports or citizenship documents, verifying if those documents correspond to the same person, and flagging potentially fraudulent multi-citizenship claims.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Authenticates and assesses the legitimacy of documents prepared or submitted by professional intermediaries, such as incorporation papers, legal contracts, or notarized statements. This helps detect forgeries, altered records, or fraudulent documentation that fuel money laundering schemes.
- [Deceptive Tax Filings](https://framework.amltrix.com/techniques/T0014.007) — Performs authenticity checks on uploaded or filed documents, detecting forgeries or tampering in tax returns and supporting evidence (e.g., financial statements). This helps identify fabricated or manipulated filings indicative of deceptive tax practices.
- [Child Exploitation](https://framework.amltrix.com/techniques/T0058.003) — - Specialized systems authenticate official IDs, passports, or other credentials, detecting potential forgeries or tampering.
- They support the identification of minors misrepresented as adults and criminals using fraudulent documents to obscure their involvement in child exploitation.
- [Misrepresentation of Fund Purpose](https://framework.amltrix.com/techniques/T0040) — Provides specialized checks to confirm the authenticity of invoices, receipts, donation letters, and other supporting documentation used to justify transaction purposes. This helps identify forgeries or alterations indicative of misrepresented fund intentions.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Validates the authenticity and integrity of digital identification documents submitted during account setup or ownership changes. Identifying forged or inconsistent documentation helps expose fictitious owners and online-only corporate setups.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Authenticates identification documents provided by intermediaries, detecting potential forgeries or mismatches.
- Flags inconsistent or incomplete documentation, suggesting nominee or straw-man involvement.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Validates the authenticity of identification documents or corporate paperwork submitted by donors or representatives.
- Detects discrepancies, forgeries, or tampering in official IDs, passports, or charity registration documents.
- Assists in preventing the misuse of falsified documentation to mask true identities or beneficial ownership within non-profits.
- [Offshore Prepaid and E-Wallet Issuance](https://framework.amltrix.com/techniques/T0062.001) — Provides authentication results for submitted identification documents, highlighting any forgeries or inconsistencies. Detecting falsified IDs is essential when criminals exploit minimal verification protocols offered by offshore prepaid and e-wallet providers.
- [Hawala](https://framework.amltrix.com/techniques/T0013.004) — Authenticates identification documents to detect forged or tampered IDs used by hawala brokers or their customers. Ensures legitimate identity data is on file, helping to uncover individuals operating under false credentials.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Validates the authenticity of official documents and certificates.
- Detects forged or inconsistent provenance, authenticity, or ownership records commonly used to launder illicit funds via high-value goods (e.g., artwork, collectibles).
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Verifies the authenticity and security features of official documents.
- Detects signs of alteration or tampering in shipping documents, bills of lading, or invoices.
- Supports the identification of forged documentation commonly exploited in documentary collection schemes.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Verifies the authenticity of submitted identification forms and supporting documents for nonprofit or charitable registration.
- Detects forged, inconsistent, or missing documentation commonly seen when perpetrators cannot substantiate claims in fraudulent social media fundraising.
- [Identity Impersonation](https://framework.amltrix.com/techniques/T0075) — - Assesses the authenticity of provided identification documents to detect potential forgeries, tampering, or photo-layering.
- Facilitates real-time validation of document data fields against official templates and standards, exposing mismatches often seen in impersonation schemes.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Employs specialized systems to authenticate passports, IDs, and other official documents.
- Detects forged or altered documents frequently used to facilitate illegal cross-border travel in smuggling operations.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Specialized systems or services authenticate security features, design elements, and embedded data on official identification documents.
- They detect anomalies in passports, IDs, or other paperwork, indicating forgery or alteration, which is crucial for uncovering falsified identities or misrepresented information.
- [Remote Verification Bypass](https://framework.amltrix.com/techniques/T0135) — - Performs automated authenticity checks on user-submitted ID documents, detecting tampering (e.g., mismatched photos or altered text).
- Compares biometric data from the user’s submission against legitimate reference data to spot potential mismatches.
- Flags repeated re-uploads of the same or slightly altered documents, allowing detection of fraudulent attempts to bypass remote verification.
- [Asset Valuation Manipulation](https://framework.amltrix.com/techniques/T0045) — Specialized systems or services authenticate official documents, such as appraisals or asset certificates. They help detect forged or altered valuation reports and inconsistencies in ownership or provenance records, thereby mitigating attempts to legitimize manipulated valuations.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Validates passports, residency permits, and other official documents to check for forgeries, alterations, or tampering.
- Directly supports investigations into false identities or misrepresented personal histories submitted for CBI/RBI applications.
- Ensures institutions can authenticate documents and detect potential fraudulent background information used to obtain a second citizenship or residency status.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Specialized services or systems that authenticate formal documents by checking issuance details, seals, and official security features.
- Identifies forged, altered, or otherwise invalid specialized permits and sector licenses used to conceal illicit operations behind seemingly legitimate paperwork.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Automated tools and processes for detecting forgeries or alterations in official documents, such as farmland registration papers, property deeds, or production reports. This data helps confirm the legitimacy of records provided to support subsidy claims.
- [Cash Courier](https://framework.amltrix.com/techniques/T0065.001) — - Validates official identification documents (e.g., passports, IDs) to detect forgeries or inconsistencies.
- Helps identify individuals traveling under multiple identities or using falsified documents.
- Crucial in disrupting cash courier schemes reliant on false travel credentials to evade border checks.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Utilizes specialized methods to validate the authenticity of documents by identifying formatting anomalies or edits.
- Enables quick detection of tampered account statements, invoices, or other financial records.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Employs forensic checks and specialized analyses (e.g., digital watermark verification, overwritten text detection) to authenticate financial documents.
- Enables investigators to quickly spot signs of physical or digital tampering in letters of credit or other financial instruments.
- [Unemployment Insurance Fraud](https://framework.amltrix.com/techniques/T0144.008) — Authenticates official identification documents used for unemployment benefit claims by identifying forgeries, tampering, or synthetic identities. This is achieved by comparing document data with authoritative sources and verifying security features.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Authenticates official documents, such as Kimberley Process Certificates, detecting forgeries, altered certificate numbers, or missing signatures.
- Supports direct verification of diamond provenance claims, which is crucial for uncovering fraudulent shipping or licensing documents.
- [Cheque Fraud](https://framework.amltrix.com/techniques/T0144.010) — - Analyzes physical or scanned checks for chemical alterations, tampered payee fields, or other signs of forgery.
- Enables proactive identification of check 'washing' techniques before funds are released.
- [Romance Mule Recruitment](https://framework.amltrix.com/techniques/T0140.003) — - Verifies the authenticity of government-issued identification documents, detecting forgeries or inconsistencies.
- Helps ensure that individuals involved in potentially fraudulent romance-driven transactions are accurately identified.
- Mitigates the risk of fake or stolen identities used by romance scam recruiters or the recruited mules.
- [Pig Butchering](https://framework.amltrix.com/techniques/T0144.009) — - Employs tools and databases to authenticate identity documents (passports, IDs) and detect forgeries or inconsistencies.
- Identifies fraudulent or altered documents used to open accounts or revise identity details in pig butchering schemes.
- Supports enhanced due diligence when customer identification records repeatedly change without plausible explanation.
- [Fake KYC Documentation](https://framework.amltrix.com/techniques/T0023.001) — - Specializes in authenticating official identification documents, detecting tampering, and validating biometric or facial data.
- Enables institutions to identify forged or altered IDs, inconsistent metadata, or mass-produced fake documents used in account openings.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Authenticates and validates official identification documents and business records.
- Detects forged, tampered, or inconsistent documentation used in relief applications.
- Ensures the integrity of supporting documents, revealing potential identity theft or misrepresented financial statements.
- [Name Alteration](https://framework.amltrix.com/techniques/T0023.002) — Systems or services that authenticate passports, IDs, or supporting documents used for name changes by examining security features, photographs, and issuing details. These checks expose forged or tampered documents, revealing fraudulent name alterations.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Specialized systems authenticate official documents, including provenance or authenticity certificates for cultural artifacts. This data helps detect forged or altered documents used to justify the illicit origin or inflated values of artifacts, enabling more accurate due diligence.
- [Safe Deposit Boxes](https://framework.amltrix.com/techniques/T0043) — Authenticates and validates official identification documents, helping detect forged IDs or inconsistencies when criminals attempt to rent deposit boxes under false names or third-party identities.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Specializes in authenticating official documents such as passports, IDs, and business registrations.
- Highlights potential forgeries or tampered identification used to submit fraudulent claims or applications.
- Supports investigators in confirming legitimate documentation for loans, invoices, and government program eligibility.
- [Identity Manipulation](https://framework.amltrix.com/techniques/T0023) — Examines official identification documents, through physical checks or digital forensics, for signs of forgery, incomplete security features, suspicious metadata, or image manipulation. This directly helps uncover tampered or falsified documents used in identity manipulation.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Authenticates physical bearer certificates, detecting forged or altered documentation.
- Verifies issuance dates, certificate numbers, and other security features, ensuring the instrument’s legitimacy.
- Helps investigators confirm or refute claims of rightful ownership or chain of custody for bearer instruments.
- [Remittance Splitting](https://framework.amltrix.com/techniques/T0016.003) — - Validates the authenticity of official identification documents used for remittance transactions.
- Detects forged or altered IDs, as well as the repeated use of different documents by the same sender.
- Assists in identifying individuals who systematically evade controls by using multiple or false identities to remain under reporting thresholds.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Authenticates and detects alterations in official permits, licenses, and geological surveys. This is critical for identifying falsified paperwork often used to legitimize illegally extracted minerals.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Authenticates and examines submitted paperwork, such as signatures or official documents, for potential tampering or forgery. This helps uncover falsified signatures on expense forms commonly used in expense report fraud.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Authenticates official identification documents presented by policyholders or premium payers.
- Detects forged or manipulated documents used to obscure true identities and facilitate illicit policy purchases and early surrenders.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Authenticates and validates official documents, including tax certificates or returns.
- Identifies potential forgeries, alterations, or inconsistencies supporting fraudulent refund claims.
- Ensures submitted tax paperwork aligns with legitimate records.

---

## [Casino and Gambling Transaction Records](https://framework.amltrix.com/data-sources/DS0041)

**Description:**
Comprehensive data on gambling transactions and activities, including aggregated information on game types, betting frequency, transaction amounts, participant identities, deposit and withdrawal data, and other relevant details across casinos and related operations.

### Related Techniques
- [Immediate Cash Conversion](https://framework.amltrix.com/techniques/T0105) — - Monitors chip purchases, redemptions, and related gambling activity.
- Detects scenarios where customers purchase large amounts of chips and immediately redeem them for cash with minimal gameplay.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Details gambling-related transactions, including deposit, withdrawal, and betting activity. When cross-analyzed with OTC trading data, these records help uncover overlapping cash-based or chip redemption behaviors that intersect with OTC conversions, adding additional layers of anonymity.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Provides comprehensive data on gambling-related transactions, including lottery ticket purchases and prize redemptions. Such records enable investigators to:

- Track high-frequency or large-volume lottery ticket purchases.
- Identify unusual or repeated winnings and prize redemption patterns.
- Detect potential third-party claimants or sudden shifts in gambling behavior indicative of lottery-based money laundering.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Contains detailed betting outcomes, deposit and withdrawal amounts, timestamps, and overall transaction histories.
- Enables detection of abnormal gambling outcomes or minimal betting prior to large withdrawals, suggesting contrived or layering transactions.
- [Match-Fixing](https://framework.amltrix.com/techniques/T0107.005) — - Provides comprehensive records of all betting transactions, including deposit amounts, bet types, frequencies, and win/loss outcomes.
- Enables detection of rapid deposit-withdrawal cycles, correlated or simultaneous bets from multiple accounts, and consistently successful wagers on unlikely outcomes.
- Supports investigation of match-fixing by uncovering anomalous betting patterns, sudden shifts in wager size, and suspicious timing relative to sporting events.
- [Electronic Gaming Machine Ticket Redemption](https://framework.amltrix.com/techniques/T0054) — Contains detailed records of TITO (ticket-in, ticket-out) issuance and redemption, amounts inserted into electronic gaming machines, timestamps, betting activity, and payout details. This data enables tracking minimal-play or no-play scenarios, rapid cash-outs, and the overall flow of funds through gaming machines, helping detect patterns consistent with illicit layering or integration.
- [Casino Mule Networks](https://framework.amltrix.com/techniques/T0011.003) — - Captures buy-ins, chip redemptions, and negotiable instrument issuance, including timestamps, amounts, and patron identities.
- Reveals minimal or nonexistent gaming activity, rapid chip conversions, and sequential cashier transactions, supporting the detection of structuring or layering within casino mule networks.
- [Chip Dumping](https://framework.amltrix.com/techniques/T0107.003) — - Provides comprehensive logs of gambling transactions and gameplay, including buy-ins, bet sizes, transaction timestamps, game outcomes, and associated player identifiers.
- Enables direct detection of suspicious transfers of chips through unusual patterns of wins and losses, repeated large losses from the same accounts, and collusive gameplay indicative of chip dumping.
- Facilitates investigations by correlating deposit or withdrawal data with anomalous bet amounts and rapid chip movements.
- [Underground Gambling](https://framework.amltrix.com/techniques/T0107.007) — - Provides detailed records of gambling-related activities, including bet placements, winnings, payouts, and player identities.
  
- Enables analysts to track unusual patterns in betting behavior, detect consistently high payouts, identify accounts engaging in structuring or frequent large transactions, and investigate suspected underground gambling operations.
- [In-Person Gambling Imitation](https://framework.amltrix.com/techniques/T0107) — - Captures detailed data on gambling transactions, including chip purchases, redemption amounts, timestamps, and wagering activity.
- Helps identify minimal betting with rapid chip redemption, structured buy-ins or redemptions under reporting thresholds, and suspicious patterns indicating chip-dumping or match-fixing.
- Facilitates cross-checking receipts and time-stamped records to detect forged documentation or staff collusion in in-person gambling environments.
- [Casino Chip Conversions](https://framework.amltrix.com/techniques/T0107.006) — - Provides granular details of chip purchases, redemptions, TITO vouchers, and patron identities.
- Logs each wager and payout event, enabling analysis of minimal gambling, large or frequent buy-ins, and rapid cash-outs.
- Includes ticket serial numbers, issuance timestamps, and machine reconciliation records, supporting detection of forged receipts or inconsistencies between winnings claimed and actual gaming activity.
- Helps identify unusual chip transfers among patrons and patterns of staged losses or transfers immediately preceding redemptions.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Includes detailed logs of wagers placed, stakes, frequencies, amounts won or lost, and associated identities. This granular view of betting activity allows for the detection of structured bets, repetitive small wagers below reporting thresholds, unusually high-value wins, or potential staff overrides of compliance checks—all pertinent to uncovering manipulations in licensed betting shops.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Verify the legitimacy of betting activity behind large deposits, payouts, or alleged gaming proceeds.
- Compare deposit and withdrawal data with customer betting patterns to detect inconsistencies.

Monitoring these records helps reveal nonexistent or minimal gambling activity used to legitimize illicit funds as gaming revenue.

---

## [Company & Beneficial Ownership Registries](https://framework.amltrix.com/data-sources/DS0049)

**Description:**
Consolidated records providing official or aggregated details of organizations, such as registration and incorporation data, licensing, shareholders, directors, ownership structures, partnership or trust information, and membership changes.

### Related Techniques
- [Carousel Fraud](https://framework.amltrix.com/techniques/T0144.007) — - Contains official or aggregated corporate registration data (e.g., beneficial owners, directors, shareholding structures).
- Helps identify overlapping beneficial owners and directorship changes across multiple entities, indicating potential shell company usage.
- Supports correlation of rapid or suspicious corporate changes with VAT obligations to detect carousel fraud networks.
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Provides official or aggregated entity registration details, including shareholders, directors, and beneficiaries.
- Reveals complex ownership structures, shell companies, or trusts used to channel and obscure insider trading proceeds.
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Provides incorporation details, shareholders, directors, and recorded changes in ownership or authorized signatories.  
- This helps trace ownership shifts in state-owned entities or affiliated corporate structures that may indicate layering or corruption proceeds passing under diplomatic cover.
- [Tax Rebate Fraud](https://framework.amltrix.com/techniques/T0147.002) — - Provides official corporate ownership, registration, and control information.
- Detects newly formed shell companies or irregular ownership changes used to file suspicious refund claims.
- Clarifies beneficial ownership structures exploited to disguise fraudulent tax rebate activities.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Provides official data on company structures, directorships, shareholdings, and ownership relationships. In corruption cases, these registries help trace shell entities or hidden beneficial owners used to launder embezzled funds.
- [Court System Manipulation](https://framework.amltrix.com/techniques/T0047) — Provides details on company registrations, beneficial ownership structures, and historical ownership changes.

How it supports AML detection:
- Uncovers complex or opaque entities repeatedly involved in suspicious lawsuits or legal settlements.
- Identifies hidden beneficiaries behind legal actions, revealing potential shell companies used to launder illicit funds through manipulated court processes.
- [Cash Wage Payments to Undocumented Workers](https://framework.amltrix.com/techniques/T0052.001) — - Contains official incorporation, ownership, and directorship details for companies.
- Helps identify shell or minimally registered entities used to channel cash wage payments off the books, obscuring the ultimate benefactors and the true number of employees or subcontractors involved.
- [Payroll Tax Evasion](https://framework.amltrix.com/techniques/T0147.001) — - Provides incorporation data, shareholder and director details, and beneficial ownership structures.
- Allows identification of shell or front companies used to process payroll expenses without proper tax withholdings.
- Helps trace interrelated entities lacking legitimate business operations that may be set up to conceal true payroll liabilities.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Official records of business incorporation, ownership structures, and registration details.
- AML Relevance: Verifies the legitimacy of newly formed or dormant businesses filing fraudulent wage or unemployment claims.
- [Human Trafficking](https://framework.amltrix.com/techniques/T0058) — Provides official registration details, ownership structures, and historical changes for businesses. By reviewing these records, investigators can:

- Identify undisclosed beneficial owners or shell companies concealing proceeds from forced labor or sexual exploitation.
- Verify the legitimacy of corporate entities presented as recruitment agencies, bars, or massage parlors commonly used to funnel illicit funds.
- Detect connections between entities and higher-risk individuals or suspicious business networks, aiding in uncovering human trafficking operations.
- [Insurance and Reinsurance Manipulation](https://framework.amltrix.com/techniques/T0090) — - Provides official registration and beneficial ownership details of insurers, reinsurance entities, or associated shell companies.
- Uncovers opaque or layered ownership structures used to conceal the ultimate owners behind manipulated insurance arrangements.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Contains information on corporate registration, shareholders, and beneficial owners.
- Enables identification of overlapping ownership among so-called mini umbrella companies used to divide payroll artificially and evade certain thresholds.
- [Export Overvaluation](https://framework.amltrix.com/techniques/T0147.004) — - Maintains official records of corporate registration, beneficial owners, and controlling individuals.
- Uncovers shell or front entities used to channel inflated export proceeds and disguise true ownership.
- Enables financial institutions to identify hidden relationships that facilitate overvaluation schemes.
- [Undisclosed Payment Aggregation](https://framework.amltrix.com/techniques/T0138) — - Provide official records of registration details, shareholders, directors, and beneficial owners, which are crucial for verifying legitimate control over merchant entities.
- Help validate or refute claimed relationships between payers and the merchant, revealing shell companies or hidden ownership structures used to obscure illicit proceeds.
- Aid in tracing beneficial ownership when criminals open aggregator or merchant accounts under false pretenses to conceal the true recipients of funds.
- [Securities Account Ownership](https://framework.amltrix.com/techniques/T0088.001) — Provides official registration and incorporation data (e.g., shareholders, directors, historical ownership changes), enabling AML teams to detect:

- Nominee or proxy structures obscuring the true beneficial owners of securities accounts.
- Front entities or shell companies lacking legitimate activity.
- Sudden changes in listed signatories or controllers.
- Complex, multi-layer ownership arrangements designed to hide real control.

Leveraging this information helps confirm the authenticity of ownership claims and uncover hidden parties behind securities account manipulation.
- [Commodity-based Trade Transactions](https://framework.amltrix.com/techniques/T0125) — Consolidated records of corporate registration, shareholder structures, and beneficial owners: 

- Reveals overlapping ownership or hidden ties across multiple entities involved in a single commodity transaction.
- Supports detection of shell companies and multi-layered intermediaries used to conceal ultimate beneficiaries.
- [Fraud](https://framework.amltrix.com/techniques/T0144) — - Provides official ownership and registration details for companies, including shareholding structures and directorships.
- Assists in uncovering shell entities or undisclosed ownership used to channel fraudulent proceeds.
- Enables cross-verification of declared business activities against actual corporate records, identifying potential misrepresentations in fraudulent setups.
- [Dividend Stripping](https://framework.amltrix.com/techniques/T0147.003) — Provides official registration details, records of shareholders, beneficial owners, and historical ownership changes. Cross-referencing these registries with internal account data helps detect sudden or repeated share ownership shifts engineered to claim multiple dividend refunds in a short timeframe.
- [E-commerce & Marketplace Manipulation](https://framework.amltrix.com/techniques/T0028) — Provides official and aggregated corporate registration details, including beneficial ownership data, directors, and historical ownership changes. This facilitates the verification of e-commerce businesses, detection of shell or front companies, and exposure of hidden ownership structures used to launder funds through fraudulent online storefronts.
- [Transfer Pricing Manipulation](https://framework.amltrix.com/techniques/T0139) — - Consolidates official registration data, shareholder and director information, and beneficial ownership structures.
- Enables tracing of common ownership or hidden relationships among entities, revealing inter-company links exploited in transfer pricing manipulation.
- [Over-the-Counter Cryptocurrency Trading](https://framework.amltrix.com/techniques/T0114) — Provides official company registration and shareholder records to identify the true owners and controllers of OTC brokerages. This data helps confirm whether such entities are legally registered or if they exploit opaque structures to evade AML controls.
- [Ponzi Schemes](https://framework.amltrix.com/techniques/T0144.019) — Provides official registration and beneficial ownership details for entities involved in the scheme, enabling investigators to identify potential shell companies or undisclosed controlling interests used to layer funds within Ponzi operations.
- [Diamond-based Trade Transactions](https://framework.amltrix.com/techniques/T0055.002) — - Contains formal records of entity ownership structures, shareholders, and ultimate beneficial owners.
- Helps reveal overlapping ownership or control of multiple diamond-trading entities lacking legitimate commercial rationale.
- [Cooperative or Mutual Institution Deposits](https://framework.amltrix.com/techniques/T0120) — These registries provide official records of registration, directorship, controlling interests, and ownership structures for cooperatives, mutual institutions, and similar entities. They enable investigators to:

- Identify the true owners or controlling members behind the cooperative or mutual institution.
- Uncover undisclosed beneficial owners or hidden relationships, exposing infiltration by high-risk individuals.
- Compare official governance or membership data with actual account and deposit patterns, highlighting red flags in ownership or control.
- [Forging or Altering Financial Instruments](https://framework.amltrix.com/techniques/T0126) — - Provide official records of entity registration, ownership structures, and directorships.
- Uncover shell entities or overlapping beneficiaries orchestrating the circulation of forged financial instruments to obscure the flow of funds.
- [Sports Club Investments](https://framework.amltrix.com/techniques/T0025) — - Data elements: Official or aggregated corporate filings, ownership structures, shareholder and director details, and partnership records.  
- AML Use: Reveals hidden or opaque ownership networks behind club investors, sponsors, or intermediary firms, helping detect undisclosed beneficiaries or politically exposed influencers involved in funding the club.
- [Virtual Companies](https://framework.amltrix.com/techniques/T0127) — Provides official registration records and ownership structures, assisting in pinpointing enterprises registered under minimal disclosure jurisdictions or multiple entities sharing the same ownership and addresses. This is critical for identifying potential shell or virtual setups.
- [Environmental Crime](https://framework.amltrix.com/techniques/T0145) — - Provides official ownership and registration details for companies.
- Identifies actual and hidden beneficial owners behind front or shell companies.
- Enables the detection of complex ownership structures used to obscure the proceeds of illegal logging or wildlife trafficking.
- [Charitable and Non-Profit Organizations](https://framework.amltrix.com/techniques/T0019) — - Details official registration records, directors, shareholders, and beneficial owners of organizations, including non-profits.
- Enables investigators to detect frequent or suspicious board changes, hidden ownership structures, or infiltration by criminal associates.
- Helps confirm or refute claims regarding a charity’s legitimate governance and oversight.
- [Intermediary-Facilitated Transfers](https://framework.amltrix.com/techniques/T0002) — - Provides official registration and ownership details for companies, revealing hidden corporate structures that may be exploited through nominee arrangements.
- Assists in identifying shell companies or complex ownership chains frequently used by intermediaries to obscure ultimate beneficial owners.
- [Infiltration and Control of Banking Institutions](https://framework.amltrix.com/techniques/T0099) — Provides official registration data on corporations, including beneficial ownership details, shareholding structures, and directorship changes. This data helps detect infiltration by revealing sudden or suspicious ownership changes within a bank, hidden alliances with shell entities, and layered ownership structures indicative of organized crime control.
- [Insurance Annuities](https://framework.amltrix.com/techniques/T0087) — - Provide official incorporation, ownership, and registration details for companies or trusts.
- Reveal hidden or layered ownership structures behind policyholders or beneficiaries.
- Detect complex corporate arrangements used to obscure beneficial ownership in annuity contracts.

Access to these registries helps trace ultimate beneficial owners and mitigate the risk of shell or front entities abusing annuity products for laundering.
- [Sanctions Evasion](https://framework.amltrix.com/techniques/T0141) — - Contains official corporate registration information, shareholder data, and beneficial ownership structures.
- Helps identify shell or front companies used to obscure sanctioned individuals or entities, which is critical for exposing hidden ownership ties in sanctions evasion schemes.
- [Fictitious Trading across Jurisdictions](https://framework.amltrix.com/techniques/T0069.001) — - Data Provided: Registration details, shareholder structures, and beneficial ownership data for entities.  
- AML Relevance: Reveals shell entities or complex ownership arrangements used to conceal criminal proceeds within fabricated or inflated trade transactions.
- [Real Estate Auction](https://framework.amltrix.com/techniques/T0108.001) — Official or aggregated records detailing corporate structures, shareholders, and beneficial owners.

- Identifies shell or front companies used to purchase properties at auction and obscure ultimate ownership.
- Verifies the authenticity of corporate entities, supporting the detection of layered or non-operational business vehicles funneling illicit funds.
- [Extortion](https://framework.amltrix.com/techniques/T0049) — Centralized records of company formations, directorships, and ownership structures reveal potential shell or front companies used to launder extortion proceeds by:

- Uncovering opaque layers of beneficial ownership.
- Verifying registered business activity claims against actual financial inflows associated with coerced payments.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Provides official registration and ownership structures of sponsoring entities or intermediary companies.
- Helps identify the real owners behind front companies used in complex sponsorship or image-rights arrangements, revealing potential offshore or hidden controllers facilitating illicit fund flows.
- [Manipulation of Financial Records](https://framework.amltrix.com/techniques/T0050) — - Provide official data on corporate structures, directors, shareholders, and ownership changes.
- Reveal shell companies or obscure ownership arrangements potentially used to shift liabilities or create fictitious revenues and losses through manipulated accounting entries.
- [Forced Labor](https://framework.amltrix.com/techniques/T0058.001) — Offers official details on company registration, beneficial owners, and changes in shareholding or directorship. This data helps trace front companies or shell entities used to conceal forced labor proceeds and identify ultimate beneficiaries profiting from exploitation.
- [Arms Trafficking](https://framework.amltrix.com/techniques/T0143.002) — - Provides official or aggregated details of corporate entities, including ownership structures, directors, shareholders, and registered addresses.

- Enables investigators to uncover shell or front companies used to mask arms trafficking activities and trace beneficial owners who may be involved in illicit arms trade.
- [High-Cash Flow Real Estate](https://framework.amltrix.com/techniques/T0010.002) — - Provides registration and incorporation details, shareholder information, and beneficial ownership data for entities involved in real estate transactions.

- Enables investigators to trace underlying control persons, detect shell entities, and uncover layered ownership structures used to obscure links to criminal parties.
- [Arbitration Settlement Manipulation](https://framework.amltrix.com/techniques/T0046) — - Consolidated records show corporate registration data, shareholders, directors, and ownership structures.
- Reveals shell companies, newly incorporated entities, or undisclosed beneficial owners involved in arbitration, indicating potential collusive manipulation.
- [Wire Transfer Chains](https://framework.amltrix.com/techniques/T0070.001) — - Provides official or aggregated details on company registration, ownership structures, and controlling parties.
- Helps identify shell or front companies used to open accounts for layering, and uncovers undisclosed beneficial owners who may be involved in complex wire transfers.
- [Illegal Logging](https://framework.amltrix.com/techniques/T0145.001) — Centralized records of corporate registrations, shareholders, and beneficial owners help uncover hidden or opaque ownership structures. This can reveal shell entities potentially used to launder illegal logging proceeds through layered corporate arrangements.
- [Offshore Insurance Schemes](https://framework.amltrix.com/techniques/T0085) — Provides official registration details, ownership structures, and changes in corporate control. This data helps expose multi-jurisdictional corporate layers or shell companies used to obscure the ownership of offshore insurance providers and captive insurers.
- [Front Company](https://framework.amltrix.com/techniques/T0014) — - Provides official details on entity registration, beneficial owners, directors, and historical ownership changes.
- Enables detection of repeated or unexplained changes in management consistent with front companies concealing ultimate beneficial owners.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Provides official registration details, beneficial ownership structures, directors, and shareholders.
- Helps identify nominee directors, fictitious shareholders, or hidden beneficial owners.
- Facilitates detection of shell company usage by verifying actual ownership and cross-checking for unusual overlaps or contradictory information.
- [Fictitious Sales](https://framework.amltrix.com/techniques/T0031) — - Contains official registration and ownership details of businesses, including shareholders, directors, and historical ownership changes.
- Reveals shell or cover companies lacking genuine corporate substance, enabling detection of entities potentially used to orchestrate fictitious sales.
- [Foreign Exchange Manipulation in Trade](https://framework.amltrix.com/techniques/T0081) — - Consolidates official records of an entity’s registration, ownership structure, shareholders, and directors across multiple jurisdictions.
- Facilitates the identification of shell or front companies used to obscure ultimate beneficial owners in foreign exchange transactions.
- Supports due diligence efforts by revealing frequent changes in ownership or hidden controlling interests, which may indicate trade-based FX manipulation.
- [Commodity Trafficking](https://framework.amltrix.com/techniques/T0143) — - Provides official data on registered companies, including incorporation details, shareholders, and ownership structures.
- Unmasks shell or front companies used by commodity traffickers to conceal true ownership.
- Enables investigators to trace beneficial owners, identifying hidden links to illicit trade networks.
- [Trade Misinvoicing](https://framework.amltrix.com/techniques/T0008.003) — - Details formal company registrations, ownership structures, shareholders, and beneficial owners.
- Helps reveal shell entities and hidden ownership arrangements that may enable or conceal trade misinvoicing activities.
- [Rug Pull](https://framework.amltrix.com/techniques/T0144.003) — Provides official registration data, ownership structures, directorships, and beneficial owner details. This enables investigators to verify whether a cryptocurrency project has a legitimate corporate presence or to identify missing or fraudulent ownership disclosures that often signal rug pull scams.
- [Jewelry Valuation Manipulation](https://framework.amltrix.com/techniques/T0045.001) — - Presents formal ownership data for legal entities and beneficial owners.
- Exposes relationships among individuals or entities repeatedly transferring the same jewelry piece, helping uncover collusive activity aimed at manipulating valuations.
- [Off-the-Record Deals](https://framework.amltrix.com/techniques/T0095) — - Contains official company registration details, ownership structures, and shareholder information.
- Helps detect undisclosed ownership changes or shell entities used to conceal real controllers.
- Cross-checks formal ownership records against potential off-the-record transfers or fictitious filings.
- [Service Contract Manipulation](https://framework.amltrix.com/techniques/T0098) — - Official registration details of entities, including incorporation dates, ownership, and directorship information.
- Detects newly established or frequently restructured companies lacking transparent or legitimate business history.
- Supports investigation into beneficial owners behind potentially fictitious or shell consulting firms.
- [Migrant Smuggling](https://framework.amltrix.com/techniques/T0059) — - Consolidates official company registration details, shareholder data, and historical ownership changes.
- Uncovers front companies or shell entities used to layer or obscure migrant smuggling proceeds.
- [Countertrade](https://framework.amltrix.com/techniques/T0079) — Contains official corporate registration, shareholding structures, and beneficial ownership data. This data helps investigators:

- Uncover hidden or multi-jurisdictional ownership used to obscure beneficial owners of countertrade transactions.
- Verify corporate relationships and confirm the ultimate parties behind the exchanged goods or services.
- [Commodity Smuggling](https://framework.amltrix.com/techniques/T0048) — Lists business registration details, directors, and shareholders to unmask front or shell companies used to obscure the real parties behind smuggling operations. Investigators can identify newly formed or opaque entities facilitating illicit trade transactions.
- [Government Relief Program Fraud](https://framework.amltrix.com/techniques/T0144.004) — Provides official incorporation data, ownership structures, and historical changes in directorships or shareholding. This information reveals shell companies or newly formed entities with suspicious timing, facilitating the detection of fraudulent relief applications linked to the same ultimate beneficial owner.
- [Political Contributions](https://framework.amltrix.com/techniques/T0056) — - Provides incorporation details, shareholder information, and corporate histories of lobbying firms or intermediary entities.
- Identifies newly formed or atypical firms used as conduits for illicit political funding.
- Reveals hidden ownership structures or shell entities involved in campaign donations or lobbying payments.
- [Documentary Collection Manipulation](https://framework.amltrix.com/techniques/T0077) — - Contains official records of corporate registrations, shareholders, and beneficial owners.
- Aids in identifying shell or dormant entities used to conceal principal parties behind manipulated documentary collections.
- Provides transparency into ownership structures that may otherwise obscure illicit trade flows.
- [Syndicated Trade Loan Manipulation](https://framework.amltrix.com/techniques/T0078) — - Provides official or aggregated information on corporate structures, shareholders, directors, and beneficial owners.
- Enables detection of shared or hidden ownership across borrower and lender entities, revealing conflicts of interest or collusion in syndicated financing schemes.
- [Fictitious Foreign Investment](https://framework.amltrix.com/techniques/T0061.001) — - Provides official registration details, directorships, shareholding compositions, and beneficial ownership structures.
- Exposes convoluted ownership layering or nominee arrangements used by foreign investors to disguise ultimate beneficial controllers in fictitious investment schemes.
- [Phishing Mule Recruitment](https://framework.amltrix.com/techniques/T0140.002) — - Holds official registration and ownership data for companies.
- Verifies the authenticity of purported employers involved in phishing-based recruitment.
- Uncovers fictitious or unregistered entities used to recruit unwitting money mules.
- [Junket-based Casino Transfers](https://framework.amltrix.com/techniques/T0107.004) — - Provides official corporate registration details, ownership structures, and historical changes.
- Enables identification of underlying controlling parties behind junket operators or affiliates.
- Facilitates detection of shell or front companies used to obscure ownership in junket-based casino transfers.
- [Beneficial Ownership Manipulation](https://framework.amltrix.com/techniques/T0088) — Aggregates official corporate registration details, including shareholder and directorship data, beneficial ownership structures, and historical changes. This data enables the detection of repeated, suspicious changes in ownership, cross-verification with other records, and identification of concealed or high-risk entities.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Document legal incorporation details, layered ownership structures, and registration histories of the captive or associated reinsurance intermediaries.
- Reveal hidden shell or offshore entities used to obscure illicit fund flows.
- [Licensed Betting Shop Manipulation](https://framework.amltrix.com/techniques/T0107.002) — Provides authoritative records of corporate ownership structures and changes, including details on shareholders, directors, and any registered transitions of control. This data enables the identification of frequent or unexplained transfers of beneficial ownership in betting shops, revealing efforts to mask criminal control or launder illicit proceeds.
- [Corporate Structuring](https://framework.amltrix.com/techniques/T0130) — - Consolidates official information on company registration, directors, shareholders, and beneficial owners.
- Identifies common addresses or management across multiple entities, spotting potential layering techniques.
- Tracks repeated entity formation or dissolution events, highlighting manipulative corporate practices.
- Uncovers cross-border registrations used to obscure illicit fund flows.
- [Investment Through CBI/RBI](https://framework.amltrix.com/techniques/T0061.002) — - Maintains official or aggregated details on corporate entities, including shareholders, directors, incorporation data, and ownership structures.
- Assists in detecting instances where multiple CBI/RBI applicants share the same intermediary or beneficial owner, indicating potential collusion or hidden relationships.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Disclose the true owners and controlling parties behind corporate entities and trusts.
- Expose shell or front companies used by public officials to channel or hide misappropriated funds under opaque ownership structures.
- [Inflated Transaction Pricing](https://framework.amltrix.com/techniques/T0008.002) — - Contains official registration details, shareholding, and beneficial ownership information.
- Reveals overlapping ownership structures between buyers and sellers, a key enabler for collusive pricing schemes.

By exposing relationships among transacting parties, investigators can uncover scenarios where inflated invoices serve to move funds between related entities.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Contains official corporate registration details, ownership structures, and beneficial ownership information. This helps identify shell entities, layered ownership, or offshore corporations used to obscure illicit funding sources in manipulated investment schemes.
- [Cross-Border Agent Intermediation](https://framework.amltrix.com/techniques/T0121.001) — - Contains official registration details and ownership structures across multiple jurisdictions.
- Verifies whether local or foreign intermediaries hold ownership stakes, directorship positions, or other controlling roles.
- Facilitates detection of shell or front companies used to obscure beneficial owners and cross-border fund flows.
- [Protection Payments](https://framework.amltrix.com/techniques/T0049.002) — Provides official details on company formation, ownership, directorships, and historical registration changes. 

- Identifies potential shell or front companies used to funnel extortion proceeds.
- Validates the legitimacy of business structures that might otherwise conceal coercive payment flows.
- [Carbon Credit Trading](https://framework.amltrix.com/techniques/T0118) — - Provides official information on corporate structures, shareholders, directors, and ownership hierarchies.
- Helps uncover shell entities or special-purpose vehicles used to mask beneficial ownership in complex carbon credit arrangements and cross-border layering schemes.
- [Bonded Warehouses](https://framework.amltrix.com/techniques/T0112) — - Provides official or aggregated details on business registration, shareholders, directors, and beneficial owners.
- Supports investigations into the ownership history of entities using bonded warehouses, helping to identify shell or front companies with minimal operational footprints and uncover hidden beneficial owners.
- [Fictitious Creditors](https://framework.amltrix.com/techniques/T0103) — Provides official data on corporate registration, ownership structures, and beneficial owners, enabling verification of vendor legitimacy. It is essential to confirm if purported creditors are legitimate businesses or share suspicious overlaps with company insiders.
- [Mirror Trading](https://framework.amltrix.com/techniques/T0101) — Provides official information on corporate structures, including shareholders, directors, and ultimate beneficial owners. Access to these registries uncovers shell or front companies used in mirror trading, revealing the true parties behind complex layering schemes.
- [Document Forgery](https://framework.amltrix.com/techniques/T0012) — - Contains official data on company registration, shareholders, directors, and beneficial owners.
- By verifying corporate documentation against these registries, institutions can uncover forged or misrepresented corporate structures used to mask the true owners of illicit transactions.
- [Bearer Instruments](https://framework.amltrix.com/techniques/T0042) — - Provides official registration data, including directors, shareholders, and historical ownership changes.
- Detects opaque or missing beneficial ownership details for entities issuing or holding bearer shares.
- Helps expose complex corporate structures that rely on bearer instruments to conceal the real beneficiaries.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Official registration records, shareholder information, and beneficial owner disclosures.
- Facilitates detection of shell companies, nominee directors, and frequent changes in ownership structures, which are central tactics in concealing the ultimate beneficiaries of illicit capital.
- [Gold Conversion](https://framework.amltrix.com/techniques/T0055.001) — - Consolidates official registration details, shareholders, directors, and beneficial owners, including historical changes.
- Enables identification of frequent or suspicious changes in ownership of gold dealers or intermediaries, suggesting potential concealment or layering.
- [Freeports and Private Storage](https://framework.amltrix.com/techniques/T0131) — Provides official or aggregated data on business entities, including ownership structures, directorships, and registered shareholders. Supports detecting overlapping beneficial owners among multiple shell companies using the same private storage facility.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Contains official registration data of nonprofit educational institutions, including leadership, ownership structures, and historical changes.
- Aids in identifying frequent or unexplained ownership or management changes that may indicate potential shell or front organizations used for laundering.
- [Trade Finance Manipulation](https://framework.amltrix.com/techniques/T0074) — Details corporate structures, shareholders, and ultimate beneficial owners of entities engaged in trade finance. Reviewing these registries helps identify shell companies, front entities, or collusive participants facilitating trade-based money laundering.
- [Precious Metals & Stones Trading](https://framework.amltrix.com/techniques/T0055) — Contains details on registered businesses, their ownership structures, and key personnel. This data supports:

- Verifying the legitimacy of intermediaries or shell entities involved in precious metals or gemstone trades.
- Identifying beneficial owners who may conceal illicit proceeds under complex corporate setups.
- Detecting undisclosed or suspicious business relationships tied to trade-based laundering.
- [Circular Transactions](https://framework.amltrix.com/techniques/T0039) — - Provides official or aggregated details of organizations, including registration, shareholders, directors, and beneficial owners.
- Facilitates the identification of shell companies and hidden relationships among entities involved in circular transactions.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Provides official registration details, shareholder information, and corporate histories of entities.
- Confirms whether companies have legitimate business operations or are merely shells used in layered L/C schemes.
- Reveals anomalies in corporate registration and activities, exposing fraudulent participation in letters of credit issuance.
- [Black Market Peso Exchange](https://framework.amltrix.com/techniques/T0013.005) — - Data Provided: Official incorporation records, shareholding details, director information, and beneficial ownership data.

- Direct AML Relevance: Helps verify declared ownership structures used in import/export transactions, uncovering hidden controllers or shell entities that facilitate Black Market Peso Exchange.
- [Complicit or Controlled FIs](https://framework.amltrix.com/techniques/T0082) — - Provides official information on company registration, shareholders, directors, and ownership structures.
- Enables confirmation of an MSB’s declared ownership against actual beneficial owners, helping expose shell companies or undisclosed controllers.
- Aids in verifying whether the MSB is covertly owned or directed by criminals or high-risk parties seeking to evade detection.
- [Wildlife Trafficking](https://framework.amltrix.com/techniques/T0145.002) — - Contains data on corporate structures, including registration details, shareholders, directors, and ultimate beneficial owners.
- Helps identify shell companies and undisclosed ownership ties often used to launder proceeds from wildlife trafficking.
- Facilitates linking questionable entities to known traffickers or high-risk networks.
- [Investment in Financial Instruments](https://framework.amltrix.com/techniques/T0061) — Includes official corporate registration details, directors, shareholders, beneficial owners, and historical ownership changes. This information helps identify shell or front companies used to funnel illicit proceeds into investment funds and detect hidden relationships across layered corporate structures.
- [Cigarette Smuggling](https://framework.amltrix.com/techniques/T0048.002) — - Details corporate registration data, shareholding structures, and beneficial owners.
- Detects common ownership or overlapping interests among multiple tobacco-related businesses that may facilitate coordinated smuggling networks.
- Highlights undisclosed beneficial owners potentially involved in transnational smuggling ventures.
- [All-Cash Real Estate Transactions](https://framework.amltrix.com/techniques/T0010.005) — Includes official corporate registration data, directors, shareholders, and beneficial owners. This data helps identify shell companies and undisclosed ownership structures used in all-cash property deals to conceal the true parties and sources of funds.
- [Entertainment Venture Fronts](https://framework.amltrix.com/techniques/T0014.006) — - Provides legal entity and ownership details, identifying hidden or opaque beneficial owners behind entertainment companies.
- Helps investigators trace multi-jurisdictional holdings and unmask ultimate owners of front enterprises used to launder funds.
- Essential for ensuring beneficial ownership transparency in the entertainment industry.
- [CBI or RBI-Based Identity Acquisition](https://framework.amltrix.com/techniques/T0024.001) — - Provides official records of corporate registration, shareholders, directors, and ownership structures.
- Directly aids in identifying shell companies, opaque corporate vehicles, or trusts used to conceal the true source of investment funds for CBI/RBI programs.
- Supports AML detection by verifying whether complex entities are being used to mask beneficial owners or bypass scrutiny in the citizenship or residency application process.
- [Proxy Arrangement](https://framework.amltrix.com/techniques/T0038) — Provides official or aggregated information on company ownership structures, directors, and shareholders. Helps confirm that declared beneficial owners align with registry data, revealing discrepancies that may point to a proxy arrangement.
- [Lottery Winnings](https://framework.amltrix.com/techniques/T0107.001) — Hold incorporation data, shareholder information, and beneficial ownership details for registered entities. In lottery laundering scenarios:

- Verify corporate entities redeeming large prizes when they have no logical link to gaming.
- Identify hidden ownership structures or nominee relationships concealing the true beneficiaries of lottery winnings.
- Correlate corporate activity with suspicious prize-claim patterns.
- [Timeshare Scams](https://framework.amltrix.com/techniques/T0144.014) — - Provides official records of business registration, shareholders, directors, and ultimate beneficial owners.
- Detects multiple newly formed entities under the same owner purporting to offer timeshare resale services.
- Facilitates verification of actual real estate closings or documented transactions tied to these entities.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Offers official details on corporate registration, ownership structures, and key principals. This data is vital for verifying whether entities issuing repeated invoices have legitimate commercial operations or are shell companies used to create multiple billing layers.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Provides official records of corporate ownership structures, including directors and ultimate beneficial owners. Cross-referencing these details helps identify multiple subsidy applications filed under different entities controlled by the same individual or group.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Reveals corporate structures, shareholders, and ultimate beneficial owners, enabling the detection of shell or front companies used to obscure financial flows or arrange fictitious trade deals.
- [Stock Manipulation](https://framework.amltrix.com/techniques/T0094.001) — - Contain official records on companies, shareholders, and beneficial owners.
- Help identify shell entities or undisclosed owners controlling multiple trading accounts.
- Support detection of complex corporate structures used to obscure ultimate beneficiaries in stock manipulation scenarios.
- [Remote Mining](https://framework.amltrix.com/techniques/T0020.001) — - Provide official records of legal entities, including shareholders, directors, and beneficial owners.
- Useful for uncovering shell entities or obscured ownership structures behind remote mining providers or intermediary companies in high-risk jurisdictions.
- [Fictitious Call Center](https://framework.amltrix.com/techniques/T0014.002) — - Aggregates official company registration data, shareholder information, and ultimate beneficial ownership (UBO) details.
- Enables cross-checking of overlapping beneficial owners across entities that claim to be independent call centers, exposing hidden ownership structures.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Documents business registration details, ownership structures, shareholders, and potential shell entities used in property deals.
- Enables verification of ultimate beneficiaries behind real estate transactions involving escrow accounts, helping expose hidden or suspicious actors.
- [Market Manipulation](https://framework.amltrix.com/techniques/T0094) — - Provides official corporate registration data, shareholder details, and beneficial ownership structures.
- Helps uncover shell entities or multiple accounts under common control used to conduct circular or manipulative trades.
- Enables investigators to trace ultimate beneficiaries behind complex corporate setups involved in market manipulation schemes.
- [Advance Fee Fraud](https://framework.amltrix.com/techniques/T0144.002) — - Contains official incorporation and ownership details, allowing for the verification of newly formed or suspicious entities receiving funds.
- Identifies shell or unverified companies frequently used to launder or redirect proceeds from advance fee scams, assisting in tracking ultimate beneficiaries.
- [International Real Estate](https://framework.amltrix.com/techniques/T0010.003) — - Contains official registration data, shareholders, directors, and incorporation details of firms, including offshore entities.
- Enables tracing of multi-layered corporate structures and identifying true beneficial owners behind shell companies holding foreign real estate.
- Supports detection of suspicious or undisclosed cross-border ownership arrangements linked to illicit property investments.
- [Player Image Rights Manipulation](https://framework.amltrix.com/techniques/T0129.001) — - Provide details about the true owners, shareholders, directors, and registration status of companies or intermediaries.
- Assist in identifying shell entities or opaque ownership chains used to conceal beneficial owners involved in image rights manipulations.
- [Hot Transfers](https://framework.amltrix.com/techniques/T0013.002) — - Provides corporate registration details, ownership structures, directorships, and shareholdings.

By revealing interlinked entities that may be engaging in reciprocal trades or netting arrangements, this data source helps identify complex structures facilitating hot transfers through hidden ties between counterparties.
- [Fictitious Consulting Firm](https://framework.amltrix.com/techniques/T0014.003) — Provides official registration details, beneficial owner identities, and records of shareholding or directorship changes. This information uncovers overlapping control or sudden shifts in ownership structures, which are hallmarks of collusion and shell firm misuse in the context of fictitious consultancies.
- [Expense Report Fraud](https://framework.amltrix.com/techniques/T0144.006) — Supplies official registration details and ownership structures of entities. Cross-checking expense claim vendors against these registries helps identify shell companies or completely fictitious vendors involved in fraudulent reimbursements.
- [Agent-Based Transaction Processing](https://framework.amltrix.com/techniques/T0113) — - Provides official registration data, shareholders, directors, and beneficial owners for agent entities.
- Identifies undisclosed or overlapping ownership among multiple agents and sub-agents.
- Cross-referencing these details with transactional data can highlight complex or hidden ownership structures facilitating laundering.
- [Consulting Firm Schemes](https://framework.amltrix.com/techniques/T0098.001) — - Provides official registration data, corporate ownership structures, and beneficial owner details.
- Helps investigators uncover shell or offshore entities behind consulting operations and trace ultimate owners linked to illicit activities.
- [Early Surrender](https://framework.amltrix.com/techniques/T0086.001) — - Reveals registered ownership, directors, and shareholders of entities involved in premium payments.
- Helps uncover complex or intentionally opaque corporate structures used to mask beneficial owners or funnel illicit funds through insurance policies.
- [Professional Intermediaries](https://framework.amltrix.com/techniques/T0060) — Offer official registration and shareholding data, including directors, corporate structures, and beneficial owners. Investigators can trace how professional intermediaries form or manage complex entities, revealing hidden ownership layers used to obscure the origin and destination of illicit funds.
- [Chargeback](https://framework.amltrix.com/techniques/T0091) — Registry data reveals the legal owners, shareholders, and directors of companies, including:

- Structures showing ownership or control overlap between merchants and disputing customers.
- Historical changes in beneficial ownership.

This data source helps expose collusion in fraudulent chargebacks where the merchant and the customer share hidden business interests.
- [Collectible Auction Manipulation](https://framework.amltrix.com/techniques/T0045.002) — - Provides official details on company registration, beneficial owners, and corporate affiliations.
- Identifies shell companies or multiple dealers without verified track records that are used to hide beneficial ownership in collectible transactions.
- Traces links between dealers or auction platforms and potential illicit entities attempting to obscure the origins of funds.
- [Fake Job Recruitment](https://framework.amltrix.com/techniques/T0140.004) — - Contain official registration and ownership information about companies.
- Help verify if an advertised employer is duly registered or if corporate data is contradictory.
- Identify instances where fake or non-existent companies are used in job recruitment scams.
- [Trade-based Transaction Manipulation](https://framework.amltrix.com/techniques/T0111) — Houses official entity information, including registration details, directors, shareholders, and ultimate beneficial owners, enabling the identification of overlapping ownership across multiple import/export businesses. This insight helps detect collusive arrangements used to layer invoices or channel funds through affiliated entities in trade-based money laundering.
- [Renovation Cost Manipulation](https://framework.amltrix.com/techniques/T0124) — - Maintains official records of company formation, ownership structures, and beneficial owners.
- Helps confirm contractor legitimacy and detect newly formed or shell entities issuing suspicious renovation invoices.
- [Asset Management Deposits](https://framework.amltrix.com/techniques/T0123) — - Provides official records of corporate structures, including shareholders, directors, and historical ownership changes.
- Enables detection of shell companies, overlapping beneficial owners, and hidden control structures used to obscure the true owners of cross-border asset management arrangements.
- [Loan Schemes](https://framework.amltrix.com/techniques/T0098) — - Provides official corporate registration data, including beneficial owners, directors, and historical registration changes.
- Exposes offshore shell entities or affiliated companies used to disguise loan-back or back-to-back schemes.
- Enables linkage of borrower and lender under the same beneficial owner, a frequent tactic in disguised loan transactions.
- [Rental Income Schemes](https://framework.amltrix.com/techniques/T0010.004) — - Provides official details of legal entities, including shareholders, directors, and beneficial owners.
- Assists in uncovering shell companies or obscured beneficial ownership structures used to conceal laundering through rental income.
- [Investment Fraud](https://framework.amltrix.com/techniques/T0144.017) — Provides verified details of registered entities, including incorporation data, directors, shareholders, and beneficial owners. This data helps uncover shared ownership or repeated entity registrations used to run parallel, identical investment scams without transparent disclosure.
- [Insurance Beneficiary Substitution](https://framework.amltrix.com/techniques/T0089) — - Provides corporate registration details, ownership structures, and directorship information.
- Assists in identifying shell companies, opaque ownership, or newly added corporate beneficiaries lacking legitimate business activity, thereby revealing potential obfuscation of ultimate beneficiaries.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Centralizes corporate registration details, including shareholders, directors, and beneficial owners.
- Reveals hidden or constantly changing ownership structures used by unlicensed MSBs to conceal operations.
- Helps identify front or shell entities facilitating unregulated money transfers.
- [Red/Green Clause Letters of Credit](https://framework.amltrix.com/techniques/T0074.002) — Consolidates official data on company registration, shareholders, and ultimate beneficial owners. This enables the identification of shell or collusive entities behind red/green clause LCs, especially when layered ownership structures conceal illicit activity.
- [Precursor Chemical Procurement](https://framework.amltrix.com/techniques/T0142.001) — - Contains official registration details and beneficial ownership structures of companies.
- Identifies shell or front companies and undisclosed owners involved in chemical procurement.
- Supports verification of corporate legitimacy and alignment with declared business activities.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Provides official registration details, beneficial ownership structures, directors, and historical changes.
- Allows identification of overlapping beneficial owners across multiple relief claims, shell companies, or newly formed entities lacking legitimate operations.
- Supports verification of ownership details to detect front or nominee arrangements used to secure fraudulent relief payouts.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Centralized records of business entities and their owners capture formations, shareholder details, and historical changes in ownership structures. This data helps expose multi-layered or shifting corporate entities used to hide ultimate beneficial owners in bond transactions.
- [Offsetting Transactions](https://framework.amltrix.com/techniques/T0102) — - Provides official or aggregated details of an entity's registration, ownership structures, shareholders, directors, and beneficial owners.
- Confirms overlapping ownership or control among entities or accounts involved in suspected mirror or offsetting trades.
- Exposes collusion or layering efforts by tying seemingly separate entities back to the same ultimate controlling parties.
- [Ghost Shipping](https://framework.amltrix.com/techniques/T0069.002) — Records detailing official incorporation data, shareholders, directors, and beneficial ownership for registered entities. 

- Verifies legitimate operations, physical premises, and real beneficial owners, exposing shell or nonexistent companies used to mask ghost shipping transactions.
- Identifies inconsistencies between declared shipping entities and their actual corporate information.
- [Bid Manipulation](https://framework.amltrix.com/techniques/T0080) — - Provides official incorporation details, shareholder data, and beneficial ownership structures.
- Facilitates cross-referencing of ownership information among bidding entities to uncover overlapping controllers, indicating potential collusion or use of shell intermediaries in rigged tenders.
- [Trade Diversion](https://framework.amltrix.com/techniques/T0030) — Provides official or aggregated entity registration details, including beneficial ownership, directors, and historical registrations. Enables detection of newly formed or dormant companies, suspicious freight forwarders, or other unverified intermediaries associated with trade diversion schemes.
- [Asset Cloaking](https://framework.amltrix.com/techniques/T0009) — - Provides official corporate registration data, including shareholders, directors, and beneficial ownership details.
- Facilitates cross-referencing to identify shell or front companies used to hide real owners.
- Supports detection of multiple layers of corporate entities and nominee arrangements concealing ultimate beneficiaries.
- [Independent Payment Agents](https://framework.amltrix.com/techniques/T0113.001) — - Provides official and aggregated data on corporate registration, ownership structures, and addresses.
- Enables verification of sub-agents’ legal status, identification of overlapping beneficial owners or contact details, and detection of unlisted premises potentially used for illicit activities.
- [Offshore Gambling Licenses](https://framework.amltrix.com/techniques/T0062.002) — - Confirm the official registration details and physical presence of offshore gambling entities.
- Reveal beneficial owners, shareholders, and dormant front companies that obscure true ownership.

These records enable AML professionals to uncover hidden relationships and shell structures used to mask illicit gambling operations.
- [Oil and Fuel Transaction Manipulation](https://framework.amltrix.com/techniques/T0111.001) — - Contains corporate registration and ownership details (e.g., shareholders, directors, beneficial owners).  
- Helps uncover shell, front, or newly formed entities used to obscure illicit oil and fuel transaction activities.  
- Enables identification of hidden or opaque structures that facilitate fraudulent invoicing and misrepresented ownership in oil deals.  
- [Temporary Shell Companies](https://framework.amltrix.com/techniques/T0001.002) — - Provides official incorporation and dissolution data, revealing short business lifespans.
- Tracks directors, shareholders, and beneficial owners, helping detect nominee roles and sudden changes.
- Identifies repetitive formation and dissolution patterns by the same principals or corporate service providers.

These details directly support detecting ephemeral shell companies used for rapid laundering cycles.
- [Illicit Antiquities Trade](https://framework.amltrix.com/techniques/T0007.001) — Provides information on ownership structures and beneficial owners of legal entities. This data helps uncover shell companies or foreign-registered entities used to obscure the true owners behind antiquities transactions, supporting the identification of undisclosed parties or criminal networks.
- [Correspondent Banking](https://framework.amltrix.com/techniques/T0104) — Contains official records of corporate registrations, shareholders, and beneficial owners. This data helps expose shell or front companies orchestrated through respondent banks, enabling the correspondent bank to identify dormant or suspicious entities lacking legitimate business activities.
- [Fictitious Jewelry Business](https://framework.amltrix.com/techniques/T0014.005) — - Offers official corporate registration details, directors, and historical ownership information.
- Reveals the true controllers behind jewelry businesses, aiding in uncovering front companies.
- Helps detect frequent corporate ownership changes or shell entities lacking genuine operations.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Details formal corporate registrations, ownership structures, shareholders, and directors.
- Assists in identifying overlapping or hidden beneficial owners who might be using multiple entities to buy and sell high-value goods, obscuring true ownership in money laundering schemes.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Provides official records of business registrations, ownership structures, directors, and shareholders.
- Allows detection of frequent or unexplained management changes that may conceal bribery-related entities.
- [Offshore or Secrecy Exploitation](https://framework.amltrix.com/techniques/T0062) — - Provides official incorporation details, shareholder structures, and historical ownership changes for legal entities.
- Verifies whether multiple companies are registered in high-risk or secrecy jurisdictions under the same beneficial owner.
- Uncovers cross-jurisdictional layering and hidden ownership links facilitating offshore exploitation.
- [Art Market Manipulation](https://framework.amltrix.com/techniques/T0045.003) — - Contains official registration data, including shareholders, directors, and ultimate beneficial owners.  
- Enables investigators to unveil hidden ownership structures behind shell companies facilitating art transactions, revealing potential links to money laundering activities via manipulated art sales.
- [Free Trade Zones](https://framework.amltrix.com/techniques/T0041) — - Contains official information on corporate registration, shareholders, directorships, and ownership structures.
- Enables verification of overlapping or rapidly changing beneficial owners across multiple FTZ entities.
- Helps uncover hidden relationships indicative of shell structures or illicit layering.
- [Legitimate Business Acquisitions](https://framework.amltrix.com/techniques/T0014.001) — Holds official information on corporate registration, shareholding, and direct or indirect ownership details. Analysts can identify expedited or clustered acquisitions by the same beneficial owner, pinpoint patterns of questionable rapid expansion, and clarify complex ownership structures used to obscure illicit proceeds.
- [Pension Fund Contributions](https://framework.amltrix.com/techniques/T0037) — Provides official registration details and beneficial ownership information for entities, including self-managed pension funds. This data helps identify undisclosed or suspicious ownership structures and verifies the true parties behind private pension schemes.
- [Cross-Border Payment Routing](https://framework.amltrix.com/techniques/T0121) — Official or aggregated details of organizations, including registration data, shareholders, directors, and ownership structures. This data helps investigators detect repeated cross-border transfers among entities sharing the same beneficial owner, indicating potential layering or shell company usage.
- [Business Investment](https://framework.amltrix.com/techniques/T0036) — Provides official company registration details, shareholding structures, directors, beneficial owner identities, and historical ownership changes. This information allows for the detection of opaque or sudden ownership shifts, offshore entities, and complex corporate layers used to conceal illicit funds.
- [Auction Manipulation](https://framework.amltrix.com/techniques/T0108) — - Provides corporate registration details, shareholder information, and beneficial ownership structures.
- Identifies overlapping beneficial owners repeatedly involved in auction transactions, potentially indicating collusive flipping or layering.
- Helps trace the ultimate parties controlling shell entities used to mask true ownership in auction schemes.
- [Undeclared Earnings](https://framework.amltrix.com/techniques/T0137) — Provides official registration data, ownership structures, and beneficial owner identities. This data:

- Confirms whether an entity presenting business income is legitimately registered or licensed.
- Identifies multiple unregistered companies sharing the same beneficial owner, suggesting potential funneling of undeclared funds.
- Highlights disparities between purported commercial activities and formal registry information, revealing possible underreporting.
- [Sector-Specific Document Manipulation](https://framework.amltrix.com/techniques/T0012.003) — - Provides official corporate registration data, including details of shareholders, directors, and associated licensing or regulatory filings.
- Supports cross-referencing claimed sector-specific credentials or permits against legitimate corporate records, exposing documents inconsistent with genuine ownership or licensing status.
- [Trust-Based Obfuscation](https://framework.amltrix.com/techniques/T0088.002) — - Stores core registration details of legal entities and their beneficial owners.
- Assists in uncovering undisclosed or frequently altered ownership information that may indicate obfuscation through trusts or fiduciary structures.
- [Agricultural Ventures](https://framework.amltrix.com/techniques/T0014.004) — - Provides official records on corporate registrations, shareholder structures, and directorships across multiple jurisdictions.
- Reveals convoluted or multi-layered ownership setups behind agribusinesses, charitable foundations, or NGOs.
- Helps trace ultimate beneficial owners in high-risk or secrecy jurisdictions where agricultural ventures may conceal illicit funds.
- [Social Media Mule Recruitment](https://framework.amltrix.com/techniques/T0140.001) — - Provides official or aggregated details of corporate registration, ownership structures, and beneficial owners.
- Verifies whether purported social media 'employers' hold legitimate corporate standing or are shell/nonexistent entities.
- Enhances AML investigations by identifying fraudulent or unregistered businesses often involved in money mule schemes.
- [Illegal Mining & Mineral Trafficking](https://framework.amltrix.com/techniques/T0145.003) — Provides official registration details, beneficial ownership structures, and licensing information for entities. This data helps identify unlicensed or suspicious corporate vehicles used to conceal illegal mining operations and launder proceeds.
- [Drug Trade](https://framework.amltrix.com/techniques/T0142) — - Contains registration data, ownership structures, directors, and shareholders of companies.
- Aids in uncovering shell or front entities used to launder drug proceeds through complex corporate structures.
- Allows investigators to identify and verify the individuals ultimately controlling entities suspected of financing or facilitating the drug trade.
- [Fictitious Mergers or Acquisitions](https://framework.amltrix.com/techniques/T0130.001) — Official or aggregated records of corporate entities detail shareholders, directors, beneficial owners, and historical ownership changes. This data enables investigators to identify newly formed or dormant shell companies, detect abrupt or unverified changes in control, and correlate ownership structures across multiple jurisdictions, revealing hidden connections that facilitate fictitious M&A transactions.
- [Accrual Manipulation](https://framework.amltrix.com/techniques/T0050.001) — Contains structured information on corporate affiliations, ownership structures, and directors. Investigators can trace intercompany transactions or accrual entries across affiliated entities to detect large or irregular accruals lacking a credible commercial rationale.
- [Diamond Smuggling](https://framework.amltrix.com/techniques/T0048.001) — - Provides entity incorporation data, shareholder details, directorship information, and changes in beneficial ownership.
- Enables identification of shell intermediaries, front companies, and cross-jurisdictional ownership networks used to obscure the origins of diamond smuggling proceeds.
- [Construction Project Schemes](https://framework.amltrix.com/techniques/T0010.001) — - Verify corporate registration details and operating history to detect shell companies or recently formed companies lacking real construction experience.
- Track sudden or frequent changes in beneficial ownership that obscure the true controllers.
- Check subcontractors or affiliated entities receiving large payments to uncover undisclosed relationships or dormant businesses.
- Validate newly formed government contract awardees to ensure they have genuine capacity and are not front entities.
- [Shelf Companies](https://framework.amltrix.com/techniques/T0001.001) — - Contains official registration details, including incorporation dates, addresses, beneficial ownership structures, directorship data, and historical changes.  
- Facilitates detection of repetitive or shared addresses, frequent changes in beneficial ownership, and older incorporation dates without corresponding business activity—key attributes of shelf companies seeking to obscure true control or convey false legitimacy.
- [Offshore Transfers](https://framework.amltrix.com/techniques/T0062.003) — Provides official registration details, shareholder structures, and beneficial ownership information of companies. This data:

- Identifies shell or dormant entities used to layer illicit funds offshore.
- Verifies the business legitimacy and operational status of foreign-registered entities.
- Uncovers complex or rapidly changing ownership arrangements indicating potential offshore layering.
- [Tax Evasion & Fraud](https://framework.amltrix.com/techniques/T0147) — - Discloses organizational structures, shareholders, directors, and ultimate beneficial owners.
- Supports identification of shell companies or undisclosed entities used to shift profits and conceal taxable income.
- [Fake Vendors](https://framework.amltrix.com/techniques/T0022) — - Maintains official records of business registration, beneficial ownership, directors, and shareholders.
- Facilitates cross-referencing vendor claims to identify inconsistencies or fraudulent registrations typical of fake or shell companies used as vendors.
- [Multi-Jurisdiction Corporate Structures](https://framework.amltrix.com/techniques/T0001.003) — - Provides official registration information, directors, shareholders, and beneficial ownership structures across jurisdictions.
- Uncovers layered corporate vehicles or nominee arrangements used to obscure true owners in multi-jurisdiction setups.
- Cross-referencing registry details with trust or KYC records can highlight hidden relationships and suspicious ownership changes.
- [Invoice Manipulation](https://framework.amltrix.com/techniques/T0008) — - Provides official details on legal entities: registration data, shareholders, directors, and beneficial owners.
- Reveals shell or newly formed companies with opaque ownership potentially used for issuing manipulated invoices.

---

## [Bank Account Data](https://framework.amltrix.com/data-sources/DS0023)

**Description:**
Comprehensive data on individuals’ or entities’ bank accounts, including account numbers, ownership details, account types, balances, and transaction histories.

### Related Techniques
- [Diplomatic Channels](https://framework.amltrix.com/techniques/T0084) — - Contains ownership details, account types, balances, and historical transaction statements.
- Facilitates the detection of unusual variations in balance levels, excessive cash withdrawals, or transfers between corporate and personal accounts under diplomatic or state-owned entities, revealing potential misuse of official accounts.
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Offers detailed information on account owners, balances, and transaction histories. In corruption investigations, sudden large deposits or rapidly increased balances can signal misappropriated funds or bribery proceeds funneled through personal or related-party accounts.
- [Fictitious Payroll](https://framework.amltrix.com/techniques/T0068) — - Provides detailed information on each bank account's ownership and transaction history.
- Facilitates the detection of multiple employees or contractors receiving payroll payments into the same account or other patterns indicative of fictitious payroll schemes.
- [Bank Infrastructure Manipulation](https://framework.amltrix.com/techniques/T0132) — - Includes account balances, ownership information, and transaction histories.
- Allows validation of core ledger entries against monitoring system records, helping identify tampering or manipulations in reported account activity.
- Supports detection of discrepancies resulting from unauthorized manual overrides in internal systems.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — Provides detailed data on employees’ personal and business bank accounts, including ownership details, balances, and transaction histories. This information supports AML inquiries into insider facilitation by allowing investigators to uncover suspicious activities, such as unreported inbound funds potentially linked to bribery or corruption.
- [Sports Sponsorship](https://framework.amltrix.com/techniques/T0129) — - Shows ownership details and authorized signatories for clubs' and sponsors' bank accounts.
- Allows detection of sudden changes in account control concurrent with significant sponsorship transfers, suggesting potential front activity or hidden beneficial owners.
- [High-Value Collectibles Conversion](https://framework.amltrix.com/techniques/T0007) — - Provides comprehensive information on account holders, balances, and transaction histories.
- Identifies complex fund movements or layering strategies used to purchase high-value goods, linking transaction flows between multiple accounts and commodity acquisitions.
- [Fraudulent Social Media Fundraising](https://framework.amltrix.com/techniques/T0144.011) — - Provides comprehensive details on account ownership, account opening dates, balances, and transaction histories.
- Assists in detecting newly opened personal accounts receiving large volumes of small donations without any nonprofit registration, indicating potential fraud and fund consolidation tactics.
- [NFT-based Value Obfuscation](https://framework.amltrix.com/techniques/T0064) — - Consists of account ownership details and transaction histories, indicating when large NFT sale proceeds are deposited or withdrawn.
- Assists in detecting sudden spikes in account balances tied to suspicious NFT transactions, aligning with potential laundering activities disguised as art sales.
- [Investment Fund Manipulation](https://framework.amltrix.com/techniques/T0097) — Provides insights into account balances, movement histories, and ownership details, enabling the detection of unusually large or rapid fund flows that are inconsistent with typical investment activity. This alerts investigators to possible manipulations.
- [Cross-Border Currency Declaration](https://framework.amltrix.com/techniques/T0122) — - Includes account ownership details, balances, and transaction histories.
- Supports comparison of deposits with amounts declared at borders or exchanged abroad.
- Detects mismatches and traces possible layering when declared funds re-enter domestic accounts.
- [Investment Companies](https://framework.amltrix.com/techniques/T0061.003) — - Information on account holders, balances, transaction histories, and account structures across multiple financial institutions.
- Supports identification of multiple, often cross-border, accounts used to transfer or layer proceeds through investment companies.
- [Educational Institution Schemes](https://framework.amltrix.com/techniques/T0019.001) — - Displays account ownership, authorized signatories, and transaction histories for personal or business accounts funneling payments labeled as educational fees.
- Assists in uncovering overlapping controllers of multiple accounts and detecting potential layering schemes within the institution's financial ecosystem.
- [Electronic Gaming Machine Ticket Redemption](https://framework.amltrix.com/techniques/T0054) — Offers comprehensive deposit and transaction histories, ownership details, and account balance information. Cross-referencing TITO voucher redemption proceeds with an account holder’s established financial profile helps identify deposits that are inconsistent with stated gambling habits or declared income.
- [Multi-Currency Swap](https://framework.amltrix.com/techniques/T0115.002) — Provides account ownership, balance history, and transaction details, allowing investigators to spot rapid inflows and outflows in multiple denominations. Sudden or repeated currency conversions across various accounts can signal a multi-currency layering technique.
- [Circular Letters of Credit](https://framework.amltrix.com/techniques/T0071) — - Contains account ownership details, balances, and full transaction histories for involved entities.
- Enables detection of looping fund flows where amounts ultimately return to the originating accounts.
- Helps confirm the lack of real economic substance by tracking closed-loop structures in multi-party transactions.
- [Cash Deposits](https://framework.amltrix.com/techniques/T0004) — - Shows account ownership, type, balances, and historical deposit patterns for each customer.
- Enables detection of multiple accounts used to distribute or layer funds, revealing structured placements.
- Helps identify rapid inflows not aligned with normal account activity or stated financial circumstances.
- [Agricultural Subsidy Fraud](https://framework.amltrix.com/techniques/T0144.012) — Includes account ownership details, balances, and transaction histories. Monitoring accounts receiving subsidy deposits helps detect subsequent suspicious transfers, such as quick layering or dispersion of funds unrelated to legitimate farming activities.
- [Bill of Exchange Manipulation](https://framework.amltrix.com/techniques/T0074.001) — Provides details of accounts involved in financing or settling Bill of Exchange transactions, including ownership details, balances, and transaction histories. Cross-checking these can uncover unusual funding sources, repeated early repayments, or overlapping credit usage.
- [Vendor Impersonation](https://framework.amltrix.com/techniques/T0144.018) — - Contains detailed information about new or existing beneficiary accounts, including ownership, account opening date, and balance history.
- Identifies accounts with minimal or inconsistent transaction histories, suggesting potential fraudulent usage.
- Helps confirm whether a receiving account is genuinely associated with the legitimate vendor.
- [Multiple Invoicing](https://framework.amltrix.com/techniques/T0008.001) — Contains ownership details, account types, balances, and transaction histories. This information helps identify multiple accounts receiving payments for the same shipment or service, highlighting potential layering or repeated financing under multiple invoicing schemes.
- [Real Estate Escrow Flip](https://framework.amltrix.com/techniques/T0010.006) — - Contains detailed records of escrow account ownership, balances, and transaction histories.
- Facilitates detection of large or repeated deposits, multiple unexpected payees post-closing, and rapid fund movements indicative of money laundering via real estate flips.
- [Captive Insurance](https://framework.amltrix.com/techniques/T0090.001) — - Reveal the end beneficiaries of claims disbursements or refunds, detecting funds diverted to unrelated parties with no legitimate insurance rationale.
- Provide insight into account balances, transaction patterns, and potential funneling of illicit proceeds through captive insurance accounts.
- [Fictitious Employer-Employee Fraud](https://framework.amltrix.com/techniques/T0144.016) — - Data Provided: Ownership details, balances, and transaction histories of personal or business bank accounts.
- AML Relevance: Identifies the receipt of large government benefit deposits, insufficient payroll expenditures, and overlapping wage and benefit payments in the same account.
- [Tampering with Financial Records](https://framework.amltrix.com/techniques/T0093) — - Provides official account ownership details, balances, and transaction histories.
- Enables cross-verification of customer statements and identification of suspicious discrepancies indicative of record tampering.
- [Unlicensed MSBs](https://framework.amltrix.com/techniques/T0013.001) — - Provides account ownership details, account types (personal vs. business), balances, and transaction histories.
- Helps identify when personal accounts are used for frequent remittance or currency exchange activity, indicative of unlicensed MSBs.
- Assists in detecting mismatches between account usage and legitimate licensing status.
- [Economic Relief Fraud](https://framework.amltrix.com/techniques/T0144.005) — - Contains ownership details, account types, balances, and transaction histories.
- Facilitates identification of newly opened or underutilized accounts used to receive relief funds, followed by swift outflows to unrelated parties.
- Supports analysis of account inflows versus legitimate business activity, uncovering anomalies indicative of fraud or money laundering.
- [Bond Investments](https://framework.amltrix.com/techniques/T0061.004) — Contains detailed information on account ownership, balances, and transaction histories. This data enables financial institutions to trace sudden or large deposits used to purchase bonds, detect the use of multiple accounts for concealment, and monitor related funds being moved to or from bond investments.
- [Informal Value Transfer Systems](https://framework.amltrix.com/techniques/T0013) — - Provides ownership details, account types, balances, and transaction histories across multiple jurisdictions.
- Helps detect affiliated accounts used in offset arrangements for informal settlements, bypassing regulated wires.
- Reveals common ownership links or overlapping signatories indicative of structured IVTS networks.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Provide comprehensive details of individuals' or entities' bank accounts, including account numbers, ownership, balances, and transaction histories.
- Aid in identifying undisclosed personal or third-party accounts linked to public officials, highlighting the flow of government funds into private hands.
- [Insider Trading](https://framework.amltrix.com/techniques/T0136) — - Provides ownership details, account balances, and transaction histories.
- Correlates suspicious securities proceeds with subsequent layering or distribution transactions in insider trading scenarios.
- [Shell Companies](https://framework.amltrix.com/techniques/T0001) — - Provides comprehensive information on account openings, closures, ownership, and transaction histories.
- Identifies sudden increases in account activity or immediate closures following suspicious transactions.
- Assists in evaluating whether account usage is consistent with an entity's stated commercial profile.
- [Insurance Policy Overfunding](https://framework.amltrix.com/techniques/T0090.002) — - Details ownership, account types, and balances for each bank account used to fund premiums or receive insurance refunds.
- Complements transaction logs by confirming account holders, identifying possible third-party accounts, and highlighting mismatches with known customer profiles.
- Supports investigations into whether refunds for overfunded policies are redirected to additional high-risk or unassociated accounts.
- [Virtual IBANs](https://framework.amltrix.com/techniques/T0027) — - Provides details of underlying bank accounts to which multiple virtual IBAN references may point (e.g., ownership, balances, transaction history).
- Assists in correlating numerous virtual IBANs mapping back to the same account, revealing potential excessive layering or undisclosed connectivity among funds.

---

## [Asset Declarations](https://framework.amltrix.com/data-sources/DS0024)

**Description:**
Statements disclosing an individual’s or entity’s assets, liabilities, and financial interests, often required for public officials or certain high-profile individuals. These records provide a snapshot of declared wealth, enabling verification of stated financial positions.

### Related Techniques
- [Corruption](https://framework.amltrix.com/techniques/T0051) — Documents a public official’s declared assets, liabilities, and financial interests. By comparing these declarations with transaction histories, investigators can identify unexplained wealth and uncover illicit enrichment linked to corruption.
- [Insider Facilitation](https://framework.amltrix.com/techniques/T0021) — - Provide transparency into an employee’s declared assets, liabilities, and major financial interests.
- Help detect unexplained wealth or sudden lifestyle changes that may indicate bribery or insider corruption.
- [Bribery](https://framework.amltrix.com/techniques/T0006) — - Contains official disclosures of assets, liabilities, and financial interests by public officials or high-profile individuals.
- Helps detect unexplained wealth or discrepancies indicative of bribe receipts or hidden income sources.
- [Misappropriation of Public Funds](https://framework.amltrix.com/techniques/T0051.001) — - Disclose an official’s legally declared assets, liabilities, and income sources.  
- Cross-referencing declared wealth with actual account balances and purchases can uncover unexplained enrichment indicative of misappropriated public funds.

---
