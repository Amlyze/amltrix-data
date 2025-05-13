# * [AMLTRIX Design: Kill-chain, Tactics & Techniques](https://framework.amltrix.com/design-methodology/adversarial-model)
* [Supplemental Taxonomies](https://framework.amltrix.com/design-methodology/taxonomies):
    * [Risks](https://framework.amltrix.com/design-methodology/taxonomies/risks)
    * [Mitigations](https://framework.amltrix.com/design-methodology/taxonomies/mitigations)
    * [Services & Products](https://framework.amltrix.com/design-methodology/taxonomies/services-products)
    * [Actors](https://framework.amltrix.com/design-methodology/taxonomies/actors)
    * [Value Instruments](https://framework.amltrix.com/design-methodology/taxonomies/instruments)
    * [Data Sources](https://framework.amltrix.com/design-methodology/taxonomies/data-sources)
* [Versioning](https://framework.amltrix.com/design-methodology/versioning)

# AMLTRIX Design: Kill-chain, Tactics & Techniques

- [Chapter 1: Introduction & Chapter Overview](#chapter-1-introduction--chapter-overview)  
- [Chapter 2: Rationale for an Expanded Kill-Chain](#chapter-2-rationale-for-an-expanded-kill-chain)  
- [Chapter 3: Detailed Kill-Chain Tactics](#chapter-3-detailed-kill-chain-tactics)  
- [Chapter 4: Techniques, Subtechniques & Indicators](#chapter-4-techniques-subtechniques--indicators)  
- [Chapter 5: Positioning Typologies within AMLTRIX](#chapter-5-positioning-typologies-within-amltrix)  
- [Chapter 6: Possible Contradictions & Critiques from the Industry](#chapter-6-possible-contradictions--critiques-from-the-industry)  
- [Chapter 7: Conclusion & Future Directions](#chapter-7-conclusion--future-directions)  

---
<h3 id="chapter-1-introduction--chapter-overview"> Chapter 1: Introduction & Chapter Overview </h3>

Money laundering (ML) sits at the nexus of criminal enterprise and the legitimate financial world, exploiting regulatory blind spots, weak enforcement, and creative accounting maneuvers to conceal and move illicit funds. While the **Placement–Layering–Integration (PLI)** model has long dominated AML guidance—from major standards bodies like FATF to national regulations—contemporary laundering threats increasingly go beyond these three phases. **AMLTRIX**, an **adversarial kill-chain framework**, aims to fill these gaps by detailing **eight** distinct tactics criminals use, each with associated **techniques** and optional **subtechniques**.

### 1.1 Purpose and Goals

This chapter lays out **why** AMLTRIX departs from the traditional three-phase model, **how** it benefits from an offense-first perspective, and **what** to expect from an eight-tactic kill-chain. A high-level roadmap includes:

1. The fundamental **limitations** of the PLI paradigm.  
2. The **broader** set of adversarial stages AMLTRIX identifies—encompassing early infiltration, ongoing operational secrecy, and post-integration asset management.  
3. How **tactics, techniques,** and **subtechniques** in AMLTRIX map to real-world ML scenarios.  
4. Potential **industry critiques**, including whether this expanded kill-chain is “too complex” or “beyond daily AML scope.”

Ultimately, this approach is **not** about replacing or negating the classic PLI steps; it is about **unpacking** each step to detail the sub-stages and adversarial maneuvers that criminals actually employ. AMLTRIX remains **modular**—institutions comfortable with the simpler PLI model can continue using it while selectively adopting the new kill-chain insights.

### 1.2 Context: AMLTRIX in Beta

As of its initial **Beta** release, AMLTRIX is an evolving knowledge graph designed to **unify** AML knowledge—spanning everything from high-level risk categories to granular adversarial techniques. By providing this expanded kill-chain methodology, AMLTRIX encourages feedback from:

- **Financial institutions (FIs) and vendors** seeking advanced detection logic.  
- **Regulators and oversight bodies** wanting deeper visibility into new laundering tactics.  
- **Academic and research communities** offering further validation or alternative perspectives.

It is anticipated that **some** stages or tactics may be refined—or that certain sections (e.g., “Illicit Acquisition”) might be separated out if institutions find them less relevant for everyday AML operations. This **open** development approach welcomes suggestions and real-case validations.

### 1.3 Chapter Layout

- **Chapter 1** (this chapter): Introduces AMLTRIX’s kill-chain mindset, clarifies the purpose, scope, Beta status, and previews the entire content.  
- **Chapter 2**: Explores the rationale behind expanding beyond the Placement–Layering–Integration (PLI) model, highlighting its limitations and the benefits of an adversarial approach.  
- **Chapter 3**: Presents detailed explanations of each of AMLTRIX’s eight tactics, distinguishing them from the traditional three-phase model.  
- **Chapter 4**: Defines techniques and optional subtechniques within AMLTRIX, along with associated indicators (red flags).  
- **Chapter 5**: Positions typologies alongside the technique-based approach, explaining how they can coexist or be optionally integrated.  
- **Chapter 6**: Addresses contradictions and critiques the expanded kill-chain may face and provides potential resolutions.  
- **Chapter 7**: Concludes the Beta release by discussing future directions—feedback mechanisms, expansions, and deeper defensive mappings.


---
<h3 id="chapter-2-rationale-for-an-expanded-kill-chain"> Chapter 2: Rationale for an Expanded Kill-Chain </h3>


The conventional money laundering storyline—**Placement, Layering, Integration**—offers a **powerful simplification** that has guided AML policy for decades. It helps novices grasp how criminals introduce illicit funds, obscure them, then blend them back into the legitimate economy. However, over the years, criminal networks have devised more sophisticated routes that don’t always fall neatly into these three boxes. Chapter 2 unpacks the **core shortcomings** of PLI as an **explanatory** or **actionable** model and explains **why** AMLTRIX adds extra tactics, providing a deeper view of how criminals adapt across the laundering lifecycle.

### 2.1 Shortcomings of the Three-Phase Model

#### 2.1.1 Underestimating Preliminary Actions

In many real-world cases, criminals lay **significant groundwork** well **before** what is typically considered “placement.” For example:

- **Establishing infiltration channels** (access facilitation) or forging relationships with complicit professionals.  
- **Creating or purchasing shell companies** (concealment structures) far in advance of receiving illicit funds.

The PLI lens might implicitly bundle these activities under “placement,” but doing so hides how criminals systematically prepare to **circumvent** or **co-opt** compliance checks. AMLTRIX addresses this by designating **Access Facilitation** and **Concealment Mechanisms** as **separate** tactics, giving institutions clearer vantage points to detect infiltration patterns or suspicious corporate formations.

#### 2.1.2 Missing Cross-Cutting Operational Measures

Criminals do not wait until layering to secure themselves from detection; instead, they employ **operational security** measures (compartmentalized tasks, cunning transfer timing, rotating bank accounts) throughout **all** phases of laundering. The PLI approach lumps these maneuvers into a broad “layering” stage—or sometimes ignores them entirely. By contrast, **Operational Evasion** in AMLTRIX stands out as a **cross-cutting** tactic that criminals apply from the moment they decide to launder money until they finalize asset protection or further reinvestment.

#### 2.1.3 Limited Post-Integration Nuance

“Integration” traditionally marks the “end” of laundering, where criminals merge funds into legitimate ventures. But in reality, criminals may:

- Persistently re-layer or re-locate assets if threatened (re-laundering or re-placement).  
- Take steps to **hide** or “firewall” their wealth from legal confiscation, akin to advanced **Asset Protection**.

The three-phase model often overlooks these iterative or cyclical behaviors, leaving AML programs unprepared for criminals who continue to transform or reposition funds. AMLTRIX addresses this gap with an **Asset Protection** tactic that clarifies how launderers **proactively** shield wealth from future crackdowns.

### 2.2 Why an Adversarial Perspective?

#### 2.2.1 Offense-First, Defense-Second

Traditional AML efforts often highlight compliance obligations—KYC, transaction monitoring, staff training—without systematically mapping **the adversary’s** approach to circumvent them. Adopting a perspective akin to **MITRE ATT&CK®** (from cybersecurity) ensures that each **criminal tactic** is matched with **techniques** that defenders can watch for or disrupt. It inverts the question from “How can we comply with regulations?” to “What are criminals doing, and how do we stop them?”

#### 2.2.2 Granularity Leads to Better Countermeasures

By enumerating eight or more laundering tactics, it becomes possible to align mitigations—such as advanced beneficial ownership checks, infiltration detection, or specialized staff training—more precisely with the specific stage they target. A single “placement” bucket is too broad to design nuanced defenses. An adversarial kill-chain approach fosters clarity: each objective criminals pursue triggers distinct red flags, data sources, and detection logic.

### 2.3 AMLTRIX’s Eight Tactics: A Brief Recap

**Illicit Acquisition**  
- Aggregating or re-generating illicit capital from predicate offenses (fraud, corruption, narcotics).  
- Typically outside direct AML detection but relevant for partial signals or re-investment loops.

**Concealment Mechanisms**  
- Forming corporate or legal covers (shells, nominee directors, complex trusts).  
- Distinct from layering, as it focuses on building or deploying those covers well before large-scale transactions.

**Operational Evasion**  
- Continuous operational security: cunning scheduling, compartmentalized tasks, minimal footprints.  
- Cross-cuts all phases, ensuring criminals remain agile in response to potential detection.

**Access Facilitation**  
- Gaining entry points into the financial system, forging relationships with complicit intermediaries.  
- Precedes true “placement” by ensuring reliable deposit or transfer channels are in place.

**Placement, Layering, Integration**  
- Recognizable to mainstream AML, but with greater nuance under AMLTRIX (techniques are more granular, and ties to the other new tactics are highlighted).

**Asset Protection**  
- Securing laundered or partially laundered funds from confiscation or future detection (re-locating, re-laundering, or diversifying holdings for agility).

### 2.4 Balancing Simplicity vs. Detail

#### 2.4.1 Is This Overkill?

Some institutions may worry that naming so many tactics complicates staff training or confuses existing systems that revolve around PLI. AMLTRIX anticipates these concerns and offers a **modular** approach:

- It remains entirely feasible to continue referencing “placement, layering, integration” at a high level.  
- Meanwhile, advanced investigative teams or special units can track events such as “access facilitation” or “operational evasion” in more detail to refine detection triggers or forensic analyses.

#### 2.4.2 Beta Status and Community Feedback

Because AMLTRIX is in an early release phase, adjustments remain on the table. If the industry finds certain tactics (e.g., “Illicit Acquisition”) unhelpful, they can be downplayed—or replaced with more direct references to recognized red flags. Conversely, if feedback suggests merging “Asset Protection” back into “Integration,” that too could evolve. The goal is to surface all steps criminals actually perform, then refine or re-label as best suits institutional practice.

### 2.5 Implications for AML Programs

1. **Enhanced Coverage**: By expanding beyond PLI, compliance teams can identify infiltration (Access Facilitation) or suspicious corporate setups (Concealment Mechanisms) that might otherwise pass under the radar.  
2. **Adaptive Monitoring**: Operational Evasion as a recognized stage encourages continuous pattern tracking (e.g., unusual shifting of funds, ephemeral accounts).  
3. **Forward-Looking**: Asset Protection underscores that criminals remain active after so-called “integration,” prompting ongoing vigilance rather than a one-time check.

### 2.6 Conclusion & Preview of Next Steps

The impetus for a kill-chain approach in AMLTRIX stems from real-world complexity. Laundering is seldom linear or limited to three tidy phases; criminals meticulously plan infiltration, hide behind complex entities, continuously evade detection, and adapt liquidity or ownership structures to remain safe. By enumerating these hidden or ancillary steps, AMLTRIX aligns defense strategies more closely with adversarial reality.

- **Chapter 3** will describe each of the eight tactics in more detail—complete with examples, typical red flags, and suggestions for detection logic.  
- **Chapter 4** moves into techniques and subtechniques, showing how criminals operationalize each tactic.  
- **Later sections** address how these adversarial building blocks link to data sources, risk types, mitigations, and how they might interoperate with more traditional AML typologies.

By adopting this expanded kill-chain, practitioners can preempt infiltration, track day-to-day evasions, and hamper criminals’ attempts to secure their gains over the long run. This adversarial vantage point offers an actionable alternative (or supplement) to the standard PLI matrix, one that invites continuous evolution through industry engagement and real-world testing.

---
<h3 id="chapter-3-detailed-kill-chain-tactics"> Chapter 3: Detailed Kill-Chain Tactics <h3>


Following the rationale for why AMLTRIX expands beyond the three-phase (placement–layering–integration) model, this chapter explores each of the eight kill-chain tactics in detail:

1. Illicit Acquisition  
2. Concealment Mechanisms  
3. Operational Evasion  
4. Access Facilitation  
5. Placement  
6. Layering  
7. Integration  
8. Asset Protection

These tactics outline the adversarial objectives launderers pursue—from generating criminal proceeds to safeguarding them after partial or full integration. Unlike the standard three-step view, AMLTRIX breaks down each sub-stage criminals traverse—shedding light on infiltration, deception, real-time stealth, and post-integration security.

### 3.1 Illicit Acquisition

**Definition**

Criminals generate or accumulate funds via predicate offenses (e.g., fraud, cybercrime, corruption, drug trafficking). Often, they reinvest these proceeds to sustain or expand criminal operations, perpetuating an ongoing cycle of illicit gain and laundering.

**Key Points**

- **Upstream Insight**: Though many financial institutions (FIs) do not directly detect the predicate crime, anomalies or red flags (e.g., suspicious e-commerce activity) can hint at unlawful sources.  
- **Reinvestment Loop**: Funds can loop back into new or existing criminal ventures, quickly generating fresh suspicious capital.  
- **Reductionist**: Rather than enumerating every possible offense, AMLTRIX lumps all predicates under “Illicit Acquisition,” acknowledging that real-world usage might demand deeper offense-specific models or kill-chains.

### 3.2 Concealment Mechanisms

**Definition**

Criminals build or use corporate, legal, or organizational structures—shell companies, nominee layers, complex trusts—to camouflage the true origin and ownership of illegal wealth. These “facades” may be in place long before major transactions occur.

**Key Points**

- **Preparing the Ground**: Setting up these entities can precede the actual movement of criminal proceeds.  
- **Distinct from Layering**: Concealment focuses on forging organizational cover rather than multi-step financial transfers.  
- **Detection Approach**: Watch for questionable beneficial ownership disclosures, suspiciously intricate corporate forms, or unexplained nominee relationships.

### 3.3 Operational Evasion

**Definition**

An ongoing tactic where criminals deploy operational security measures to remain undetected—such as compartmentalizing tasks, rotating channels or accounts, adjusting timing, and monitoring investigative pressure in real time.

**Key Points**

- **Cross-Cutting**: Operational evasion extends across all laundering phases, not isolated to any single step.  
- **Stealth Patterns**: Criminals typically avoid abrupt, conspicuous flows; they break transactions into multiple small moves, adapt swiftly if they sense scrutiny, or distribute knowledge among co-conspirators.  
- **Monitor Behavioral Anomalies**: Frequent account closures, ephemeral e-wallet usage, or suspiciously well-timed transactions can be key signs.

### 3.4 Access Facilitation

**Definition**

Before injecting large sums into the financial system, criminals ensure entry points are established. They might cultivate relationships with complicit service providers, find under-regulated corridors, or misrepresent business activities to secure accounts or partnerships that raise minimal red flags.

**Key Points**

- **Precedes “Placement”**: Deals with infiltration and ensuring future funds face fewer barriers.  
- **Focus**: Involves unscrupulous intermediaries, shell banks, or lightly policed fintech channels.  
- **Detection**: Institutions can look for odd new-account openings, suspicious onboarding processes, or weakly verified beneficial owners.

### 3.5 Placement

**Definition**

“Placement” is the traditional first juncture where illicit proceeds become merged with legitimate systems, typically by depositing or introducing them in a way that masks their direct criminal origin.

**Key Points**

- **Classic AML Phase**: Here is where abrupt cash flows, structured deposits, or funnel accounts often surface.  
- **Vulnerability**: Large or unusual deposits may draw immediate scrutiny, making it a high-risk stage for criminals.  
- **Defenses**: Monitoring atypical deposit patterns or cross-checking transaction volumes can identify suspicious inflows.

### 3.6 Layering

**Definition**

Criminals execute multiple complex transactions—wire transfers, exchanges, currency conversions, trade-based maneuvers—to sever the asset’s link to its criminal source.

**Key Points**

- **Obfuscation**: Repeated layering moves hide the audit trail behind multiple accounts, entities, and jurisdictions.  
- **Common Tactics**: Chain-hopping in crypto, rapid transfers among shell companies, or trade misinvoicing.  
- **Detection**: Following the money becomes challenging; advanced transaction monitoring and cross-border data sharing can help reveal the layered patterns.

### 3.7 Integration

**Definition**

Having obscured their origin, criminals now legitimize illicit funds by merging them into legitimate business, property, or financial instruments. Post-integration, the money appears fully lawful and usable without raising suspicion.

**Key Points**

- **Traditional Final Phase**: In classic AML, integration is often considered the end of laundering.  
- **Implementation**: Investment in real estate, legitimate enterprises, or financial portfolios that camouflage the proceeds within routine economic activity.  
- **Open-Ended**: AMLTRIX acknowledges criminals may keep layering or re-laundering if risk intensifies.

### 3.8 Asset Protection

**Definition**

Beyond integration, criminals continually shield laundered wealth from law enforcement or seizure—through dispersion, rapid liquidation, or offshore repositioning. This ensures criminals can swiftly move or reconvert holdings if threatened.

**Key Points**

- **Long-Term Security**: Criminals stay alert, rotating funds across different jurisdictions and financial instruments.  
- **Combating Enforcement**: Tactics include frequent re-titling of assets, cross-border hops to avoid freeze orders, or layering inside “friendly” legal environments.  
- **Detection**: Patterns of repeated asset flight or suspicious re-allocation can reveal this post-integration tactic.

### 3.9 Relationship to Sanctions Evasion, Terrorist Financing, and Proliferation Financing

While some AMLTRIX tactics or techniques (e.g., shell entities, layering, operational security) can also appear in sanctions evasion, terrorist financing (TF), or proliferation financing (PF), the eight-stage kill-chain is fundamentally oriented toward laundering criminally derived proceeds. Other financial crime domains:

- **Different Goals**: Sanctions evasion focuses on bypassing legal restrictions (not necessarily laundering illicit wealth); TF might involve legitimate donations funding terror, rather than hiding criminal proceeds; PF seeks to acquire or move restricted materials/technology.  
- **Not Entirely Aligned**: AMLTRIX’s premise—concealing the illicit origin of funds—does not fully capture the motivations or typical flows in sanctions, TF, or PF.

#### Future Directions

Dedicated threat matrices for terrorist or proliferation financing may be developed depending on industry feedback and involvement. The current Beta release remains specifically focused on money laundering. As these adjacent threats often share some stealth or layering tactics, future AMLTRIX extensions could adapt or expand the kill-chain logic to better reflect unique patterns of TF, PF, or sanctions violations.

### 3.10 Conclusion & Next Steps

By delineating eight tactics—covering everything from Illicit Acquisition of criminal funds to post-integration Asset Protection—AMLTRIX provides a more granular map of laundering than the classic three-step approach. Crucially, it emphasizes:

- Pre-transaction infiltration (Access Facilitation)  
- Continuous stealth across all phases (Operational Evasion)  
- Foundational corporate subterfuge (Concealment Mechanisms)  
- Long-term safeguarding after partial or full integration (Asset Protection)

Though certain tactics partly overlap with other financial crime areas (sanctions, TF, PF), AMLTRIX’s kill-chain is dedicated to money laundering from criminal proceeds. In the upcoming chapters, techniques and subtechniques underlying each tactic will be discussed, illustrating how criminals enact these stages and offering insight for AML defenders seeking to disrupt each phase in practice.

---
<h3 id="chapter-4-techniques-subtechniques--indicators"> Chapter 4: Techniques, Subtechniques & Indicators </h3>


In AMLTRIX, techniques are the practical methods criminals use to implement each tactic (adversarial objective) in the kill-chain (e.g., “Placement,” “Concealment Mechanisms”). By cataloging these methods at a mid-level of abstraction, AML/CFT teams can map real-world laundering scenarios to structured knowledge in a consistent, machine-readable way.

### 4.1 Techniques: Linking the “Why” to the “How”

#### 4.1.1 Defining a Technique

A technique captures a specific way launderers achieve one or more adversarial tactics. For example:

- Under “Access Facilitation”: “Cultivating relationships with unscrupulous MSBs.”  
- Under “Concealment Mechanisms”: “Forming multi-layered offshore structures in secrecy jurisdictions.”  
- Under “Placement”: “Splitting large sums into multiple small deposits (structuring).”

This mid-level approach is:

- Granular enough to inform detection and mitigation (each technique may have unique red flags).  
- Broad enough that multiple real-life cases (from different countries or business sectors) can match the same technique category.

#### 4.1.2 Mapping a Technique to Tactics

A single laundering method might be primarily aimed at achieving one tactic (e.g., “concealment”), but in many real scenarios, criminals reuse that method in other tactics as well (e.g., layering). AMLTRIX guidance:

1. **One Main Tactic**  
   - For most techniques, a primary or dominant tactic is designated (the stage where that method is most critical).  
   - This preserves clarity in the kill-chain, preventing “everything from mapping to everything.”

2. **Multi-Tactic Linkages (If Equally Relevant)**  
   - If a technique genuinely fulfills two or more tactics with near-equal emphasis, AMLTRIX allows linking it to multiple tactics.  
   - This option should be used selectively, because it can create duplication or confusion if done too liberally. Multi-tactic mapping is recommended only when the technique’s contribution to each tactic is distinct and operationally relevant.

In other words, one technique can reference one or several tactics, but in most cases, a single main tactic suffices—unless a clear need arises to show the technique’s major role in multiple stages.

### 4.2 Subtechniques: Refining or Specializing a Technique

#### 4.2.1 When to Introduce Subtechniques

Subtechniques are optional, used only when distinguishing different variants of the same method adds practical value. For instance, “Use of Shell Companies” might split into:

1. “Offshore Shell Entity” (registered in high-secrecy havens)  
2. “Domestic Shelf Company” (repurposed entity pre-existing in the same jurisdiction)

Both revolve around “shell companies,” but each subtechnique involves distinct red flags, compliance checks, or vulnerabilities.

#### 4.2.2 Avoiding Unnecessary Complexity

In practice, organizations might not need separate “Domestic Shelf” vs. “Offshore Shell” definitions if compliance oversight lumps them together. AMLTRIX therefore remains modular—subtechniques should be created only if the distinctions enhance detection or risk management.

### 4.3 Indicators: Observable Signs of a Technique

#### 4.3.1 What Indicators Are

Within AMLTRIX, indicators (often called “risk indicators” or “red flags”) are observable signs suggesting a particular technique may be in play. For example:

- **Technique**: “Misuse of multiple MSBs for layering”  
- **Indicator**: “Customer sends an unusual volume of small transfers from different MSBs within short intervals, lacking an economic rationale.”

Indicators typically describe suspicious patterns or anomalies that an obliged entity could notice in transaction logs, KYC data, or external reference checks. AMLTRIX lists indicators under each technique to help compliance teams craft targeted detection logic.

#### 4.3.2 Different from Threat Warnings or Risk Events

- **Threat Warnings**: Specific alerts from authorities about a real-time or near-future risk (e.g., “A certain non-EU shell network is known to funnel criminal assets”).  
- **Risk Events**: Real-time triggers in a compliance system (e.g., “Account X attempts a wire to blacklisted Entity Y—block or escalate!”)

By contrast, indicators are generalizable pointers that a technique might be active. They are one component in an institution’s overall risk detection but are not themselves direct “threat warnings” or “event triggers.”

#### 4.3.3 Implementation in AML Systems

Because indicators line up with techniques, a bank or fintech could integrate these red flags into transaction monitoring or KYC processes. For instance, a compliance engine might generate an internal “risk event” whenever it observes multiple sub-threshold deposits described by a “structuring” indicator, prompting closer review or possible suspicious activity filing.

### 4.4 Illustrative Examples

Below are a few hypothetical example techniques (with possible subtechniques and indicators):

1. **Technique**: “Frequent Account Switching” (Under Tactic: Operational Evasion)  
   - **Subtechniques**:  
     1. “Rotating e-wallets monthly”  
     2. “Opening caretaker accounts via proxies and closing them after a single large transfer”  
   - **Indicators**:  
     - Account consistently shut down after inbound transfers.  
     - Minimal or no legitimate transaction history preceding closure.

2. **Technique**: “Multiple Structured Deposits via Branches” (Under Tactic: Placement)  
   - **Indicators**:  
     - Customer visits 3+ branches in one day, each deposit under a known regulatory threshold (e.g., $10k).  
     - No consistent narrative explaining the deposit sources or business activity.

3. **Technique**: “Use of Nominee Directors in Offshore Shell Entities” (Under Tactic: Concealment Mechanisms)  
   - **Subtechniques**:  
     1. “Professional nominees offering ‘director-for-hire’ services in secrecy havens”  
     2. “Reusing the same nominee across multiple unrelated companies”  
   - **Indicators**:  
     - Customer or beneficial owners appear on multiple shell entities with identical addresses.  
     - Corporate structures feature suspicious nominee patterns with minimal legitimate business.

### 4.5 Warnings, Risk Notifications, & Events: Not in AMLTRIX’s Scope

#### 4.5.1 Why They Differ from Indicators

- Threat Warnings or Risk Notifications (as described in some regulatory frameworks) are specifically-targeted announcements from an authority to an obliged entity, highlighting a particular or ongoing threat.  
- Risk Events are real-time triggers or escalations inside an institution’s compliance system.

AMLTRIX enumerates techniques and their indicators—general “red flags” or suspicious patterns. It does not manage or define official threat warnings, risk notifications, or direct “stop/go” messages from regulators. Instead, it provides a knowledge base that institutions can use to build those more immediate warning mechanisms if desired.

#### 4.5.2 Indicator vs. Threat Warning

An indicator might say: “Multiple ephemeral e-wallet accounts opened sequentially, each used for one cross-border transaction,” signifying a possible operational evasion technique.  
A threat warning from a regulator would say: “Group X is funneling illicit funds through ephemeral e-wallet providers in your region—cease or block activity.”  
The first is a pattern tied to a general technique; the second is a case-specific or real-time alert from public authorities.

### 4.6 The Role of Techniques in AMLTRIX

#### 4.6.1 Bridging Tactics & Practice

Techniques translate the why (tactic) into the how (method). By tagging each technique with relevant indicators, AMLTRIX fosters:

- **Operational Relevance**: Each stage (tactic) now has tangible detection points.  
- **Consistency**: Institutions can reference the same set of techniques across different internal systems or training modules, unifying AML efforts.

#### 4.6.2 Subtechniques for Depth

Where an institution needs deeper or more specialized detection logic—perhaps different red flags for “offshore shell” vs. “domestic shelf” usage—subtechniques deliver that extra nuance without complicating the entire knowledge graph.

### 4.7 Conclusion

Techniques (and optional subtechniques) form the methodological core for describing criminals’ actual behaviors in AMLTRIX. Each technique typically aligns with one primary tactic, though it may occasionally map to multiple if the method truly serves multiple stages in a significant way.

Crucially, indicators accompany each technique in AMLTRIX, providing high-level suspicious patterns or red flags. Chapter 5 discusses how these “building blocks” intersect with broader typologies, which are scenario-based groupings that many regulators and AML professionals use in day-to-day compliance.

---

<h3 id="chapter-5-positioning-typologies-within-amltrix"> Chapter 5: Positioning Typologies within AMLTRIX </h3>


> **Note**: AMLTRIX does not currently define typologies as a formal object or mandatory data structure. This chapter outlines how institutions **may** incorporate scenario-based groupings (often called “typologies”) into their AMLTRIX usage, but doing so is **purely optional** and not part of the core Beta release.

### 5.1 Ambiguity & Multiple Definitions of “Typology”

In many AML contexts, a “typology” describes a broad scenario or pattern of laundering activities (e.g., trade-based money laundering, real estate laundering). However, the term “typology” lacks a single, consistent definition across the industry:

- **Regulators (e.g., FATF)** may present typologies as real-world examples or aggregated patterns, often tied to specific risk indicators or case studies.  
- **Some institutions** or publishers avoid the term entirely, opting to talk about red flags, risk indicators, or simply “common laundering scenarios.”  
- **Variations**: One typology might be as simple as “cryptocurrency-based ML,” while another covers entire multi-stage processes (e.g., trade-based ML with multiple steps).

As a result, while the concept of typologies is widespread, the exact meaning can vary significantly. Some typologies are highly granular, detailing each laundering step; others remain generic, focusing on broad risk themes.

### 5.2 Suggested (Optional) Interpretation

Because AMLTRIX is a flexible framework organized around **tactics** and **techniques**, institutions or regulators **may** choose to create “typologies” that link multiple AMLTRIX components into scenario-based narratives. This is **not** an official or required part of AMLTRIX; it is an **optional** approach that can align with certain regulatory, training, or investigative preferences.

#### 5.2.1 Technique-Focused with Optional Scenario Groupings

AMLTRIX primarily catalogs **techniques** (the “how”) mapped to **tactics** (the “why”). If an institution wishes to incorporate typologies, it can treat them as **scenario-level** groupings, each pulling in multiple tactics and techniques under a single theme. For example, “Trade-Based ML (TBML)” might encompass:

- **Access Facilitation**: forging relationships with exporters/importers.  
- **Concealment Mechanisms**: creating overseas shell shipping firms.  
- **Layering**: misinvoicing or phantom shipments.  
- **Operational Evasion**: avoiding scrutiny by timing shipments during local holidays.

If desired, these pieces can be grouped into a single “TBML scenario.” This grouping would **reference** relevant AMLTRIX techniques; it does **not** change the underlying AMLTRIX kill-chain, which remains tactic- and technique-driven.

#### 5.2.2 Why Keep Typologies Fully Optional

Because industry definitions of typology differ widely, AMLTRIX does not enforce a canonical “typology node” or treat typologies as built-in objects. Some institutions or solution providers may find scenario-based groupings beneficial for:

- **Staff training** (using real-world examples).  
- **Regulatory alignment** (matching FATF typology publications).  
- **Case analysis** (assembling multiple techniques under a common narrative).

Others may see no need for a separate typology layer and prefer to focus purely on the tactics-and-techniques structure. Both approaches remain valid under AMLTRIX.

### 5.3 Advantages & Drawbacks of a Typology Layer

1. **Advantages**
   - **Scenario Narrative**: Staff training often benefits from scenario-based learning. Summarizing multiple tactics/techniques under a named scenario can demonstrate how criminals progress from infiltration to asset protection.  
   - **Regulatory Familiarity**: Many national FIUs or bodies like FATF regularly publish “typology reports.” Integrating a typology layer may help institutions stay aligned with these external guidelines or common AML language.

2. **Drawbacks**
   - **Ambiguity**: Without uniform definitions, typologies may overlap or conflict. One jurisdiction’s concept of “trade-based ML” might differ from another’s, leading to confusion.  
   - **Redundancy**: Some typologies duplicate the technique structure without adding unique insight—especially if the scenario is too broad or lacks clear red-flag indicators.

### 5.4 Practical Steps (If an Institution Chooses Typologies)

1. **Create a Scenario-Based Grouping**: An institution may define a conceptual “typology grouping” for each broad laundering scenario it deems relevant (e.g., “Real Estate Laundering,” “Human Trafficking Proceeds”).  
2. **Link to AMLTRIX Techniques**: Each scenario or “typology” can reference the specific techniques that criminals commonly employ within that scenario (e.g., structuring, complex layering, use of shell companies).  
3. **Attach Additional Context**: Regulatory red flags, case studies, or specialized investigative tips can be appended to these groupings for training and analysis.  

Again, these steps are optional; AMLTRIX does not require or standardize them in its Beta release.

### 5.5 Differentiating from Indicators & Risk Notifications

As described in Chapter 4, AMLTRIX focuses on **techniques** and their associated **indicators** to help recognize suspicious patterns. By contrast, a typology approach is primarily a **scenario-building** exercise—tying multiple indicators and tactics together under one thematic umbrella. Risk notifications or threat warnings still remain outside AMLTRIX’s core scope, since they typically involve real-time alerts or targeted notices from authorities.

### 5.6 Reconciling AMLTRIX with Regulatory Typology Reports

When national or international bodies (e.g., FATF) release new typology reports:

1. **Identify** whether new or existing AMLTRIX techniques align with the emerging typology details.  
2. **Consider** creating or updating a scenario-based grouping (if that helps internal processes or training).  
3. **Incorporate** official red flags or risk indicators from the typology report into the relevant AMLTRIX techniques.

This approach can help institutions maintain consistency between widely recognized typology reports and the AMLTRIX adversarial model, while still preserving the tactic–technique structure at the framework’s core.

### 5.7 Conclusion

Typologies, defined here as scenario-based groupings of laundering methods, are **not** a formal or mandatory component of AMLTRIX in its current Beta phase. Rather, they offer an **optional** overlay to organize tactics and techniques into contextual narratives. Some institutions may find this approach valuable for training, regulatory alignment, or thematic analysis, while others prefer to work solely at the tactic–technique level.

By presenting typologies as an optional extension, AMLTRIX keeps its fundamental design straightforward, focusing on the **eight-tactic kill-chain**, **techniques**, and **indicators**. Practitioners can adopt a scenario-based perspective if it serves their needs, or ignore typologies entirely without any loss of functionality. Over time, if user demand supports further development of a typology data model, AMLTRIX may evolve to include more formal structures for scenario-level grouping.

---
<h3 id="chapter-6-possible-contradictions--critiques-from-the-industry"> Chapter 6: Possible Contradictions & Critiques from the Industry </h3>


Adopting an eight-stage kill-chain for money laundering—coupled with a techniques-and-indicators approach—naturally raises questions from institutions and regulators accustomed to the simpler, three-phase (Placement–Layering–Integration) model. This chapter summarizes the most common concerns and how AMLTRIX might address them.

### 6.1 Complexity vs. Utility

**Challenge**

Some practitioners argue that an eight-stage kill-chain, plus optional subtechniques and a robust set of indicators, is “too detailed” for everyday compliance. The traditional three-phase approach (PLI) is easier to communicate and implement at scale.

**Response**

- **Modular Adoption**: AMLTRIX is built to be selective. Institutions can keep referencing the simpler PLI cycle and incorporate new stages (e.g., “Access Facilitation,” “Operational Evasion,” “Asset Protection”) only if they see real benefits in that specificity.  
- **Enhanced Detection**: Where criminals exploit infiltration or advanced layering tactics, the extra detail can yield more targeted detection rules. Over time, advanced compliance teams often find that a granular approach reveals hidden risks missed by broad-brush models.

### 6.2 Overlap with Existing Guidance

**Issue**

Many established frameworks (FATF, Wolfsberg, national regulators) do not explicitly define tactics like “Operational Evasion” or “Access Facilitation.” Institutions worry that aligning with AMLTRIX might cause conflict or confusion when reconciling with official guidance.

**Response**

- **Beta Phase & Feedback**: AMLTRIX is an open-source knowledge graph in Beta, actively seeking user input. New categories—like “Operational Evasion”—can evolve in name, scope, or consolidation based on real-world usage and comfort levels.  
- **Complementary, Not Conflicting**: AMLTRIX does not invalidate older frameworks; it dissects them for deeper nuance. Institutions can map AMLTRIX’s eight tactics to the Placement–Layering–Integration lens without rejecting official categories. Overlaps might exist, but they aim to enrich, rather than replace, recognized guidance.

### 6.3 “Illicit Acquisition” Scope

**Issue**

Predicate offenses are commonly considered beyond the direct coverage scope for financial institutions (FIs), whose compliance obligations usually begin at “placement.” Some practitioners worry that referencing “Illicit Acquisition” might push institutions to investigate crimes themselves—a function outside typical AML processes.

**Response**

- **Single Stage for All Predicates**: AMLTRIX lumps the entire domain of predicate offenses under one heading (“Illicit Acquisition”). This is a deliberately broad, reductionist approach—there is no expectation that institutions will unearth every detail of the underlying crime.  
- **Partial Indicators**: Sometimes an institution may observe hints (e.g., corruption signals, e-commerce fraud patterns). Acknowledging “Illicit Acquisition” helps incorporate these partial indicators into broader AML detection, without implying responsibility for investigating the full offense.  
- **Optional or Removable**: If a given stage is deemed unhelpful, it can be minimized or omitted in practice, focusing instead on the directly observable laundering steps.

### 6.4 Implementation Challenges

**Issue**

Implementing AMLTRIX’s kill-chain and technique-based approach in real-time transaction monitoring or KYC processes may seem resource-intensive—each new tactic or subtechnique could require specialized logic or advanced system modifications.

**Response**

- **Knowledge Graph, Not Mandated Real-Time Coverage**: AMLTRIX is primarily a reference or ontology of adversarial knowledge. It does not require institutions to build real-time alerts for all tactics. Instead, it provides a structured vantage point to refine or expand systems when beneficial.  
- **Gradual Integration**: An institution might start by mapping a few high-priority techniques (e.g., trade-based layering) to existing detection rules, then expand over time. This incremental approach reduces the immediate burden while allowing value to be demonstrated progressively.

---

<h3 id="chapter-7-conclusion--future-directions"> Chapter 7: Conclusion & Future Directions </h3>


As the Beta version of AMLTRIX reaches wider circulation, community feedback will guide how this eight-stage kill-chain—and its associated techniques, subtechniques, and indicators—adapts to diverse AML realities. This chapter outlines how AMLTRIX remains open to ongoing improvements and how it can eventually expand into deeper defensive measures or specialized predicate crime models.

### 7.1 Beta Status & Solicitation of Feedback

#### 7.1.1 Why Beta Matters

AMLTRIX is currently in Beta, meaning its kill-chain structure, definitions, and recommended usage are still evolving. All stakeholders—banks, fintech companies, regulators, academic researchers, and solution vendors—are encouraged to:

- Test the eight-tactic framework against real operational data or existing typologies.  
- Identify potential overlaps, missing tactics, or ambiguous categories.  
- Suggest new techniques, subtechniques, or clarifying indicators if criminal behavior is not adequately covered.

#### 7.1.2 Path to Maturity

As feedback accumulates, AMLTRIX may evolve through:

- **Term refinements**: For example, “Operational Evasion” or “Asset Protection” may require renaming or broader definitions.  
- **Structural adjustments**: Merging or splitting certain tactics, or reconfiguring the approach to “Illicit Acquisition” depending on usage.  
- **Indicator expansions**: Integrating new insights or risk patterns from actual investigations.

### 7.2 Defensive Extensions: Mapping Mitigations & Controls

#### 7.2.1 Linking the Adversarial Model to Defenses

A natural next phase of AMLTRIX is to detail how each tactic and technique can be detected or disrupted—ranging from advanced data analytics to enhanced due diligence. Similar to the MITRE ATT&CK model in cybersecurity, AMLTRIX may:

1. **Map** each technique (e.g., “Smurfing deposits,” “Offshore nominee layering”) to corresponding controls (e.g., real-time threshold alerts, beneficial ownership checks).  
2. **Contextualize** those controls within the broader kill-chain (e.g., which defenses work best at the “access facilitation” vs. “asset protection” stages).

#### 7.2.2 Possible Implementation

- **CDD & KYC**: Mapped specifically to tactics like Access Facilitation or Concealment Mechanisms.  
- **Transaction Monitoring**: Most applicable to Placement and Layering stages.  
- **Internal Controls & Governance**: Relevant to Operational Evasion, ensuring agile and continuous defense against evasive laundering strategies.

As community feedback develops, these mappings will be refined to offer a direct bridge between the adversarial kill-chain and operational defense tools.

### 7.3 Future Refinements & Specialized Kill-Chains

1. **Sub-Typology Drill-Down**  
   - Institutions with high-risk exposure (e.g., trade finance, e-commerce) might benefit from sub-typologies or micro kill-chains (e.g., “Advanced TBML” scenarios).  
   - Similarly, Illicit Acquisition could eventually split into detailed kill-chains tied to specific predicate offenses (e.g., fraud, human trafficking, cybercrime).

2. **Enhanced Detection Logic**  
   - Potential to formalize detection logic or pattern-based rules for each technique.  
   - Example: “If X sub-threshold deposits occur from Y accounts in <Z hours and show no matching invoice data, suspect ‘Smurfing’.”

3. **Integration with Other Domains**  
   - While AMLTRIX is centered on laundering of criminal proceeds, several techniques overlap with sanctions evasion, terrorist financing (TF), or proliferation financing (PF).  
   - In the future, dedicated threat matrices may be created for these domains, contingent on demand and feedback from practitioners.

### 7.4 Key Takeaway

By presenting an eight-tactic kill-chain—enriched with techniques, subtechniques, and indicators—AMLTRIX offers a flexible yet structured perspective for addressing modern laundering threats. While debates may arise (e.g., “Is eight steps too many?” or “Is ‘Illicit Acquisition’ necessary?”), the core value lies in framing laundering as a series of observable, adversarial actions.

The ultimate goals are to:

- Refine defensive controls in a step-by-step manner, from infiltration through asset protection.  
- Adapt or expand specific definitions based on real-world feedback and emerging laundering methods.  
- Facilitate shared vocabulary and structured threat knowledge across institutions, regulators, and investigative partners.

As AMLTRIX transitions beyond Beta, its evolution will continue to be driven by open collaboration and real-world validation—ensuring its relevance, clarity, and utility in confronting complex financial crime.

---

# Design and Governance of Supplemental Taxonomies in AMLTRIX

Alongside the core **Tactics & Techniques** framework for describing money laundering (ML) methods, **AMLTRIX** includes **six supplemental taxonomies**:

1. **Risk Types**
2. **Data Sources**
3. **Value Instruments**
4. **Services & Products**
5. **Mitigations**
6. **Actors**

These categories enrich the **who**, **what**, and **where** of illicit finance, providing a deeper, **holistic** picture beyond the **how** of laundering. Below is an overview of **why** these taxonomies exist, **how** they were designed, and **what** compromises guided their development—along with notes on current **Beta status**, governance aspirations, and the importance of industry feedback.

* * *

## 1\. Why Supplemental Taxonomies Are Needed

### 1.1 Enriching the Picture of Money Laundering

Focusing **exclusively** on **techniques** can obscure broader contextual factors:

*   **Who** is performing or facilitating them (Actors)
*   **Which** financial or non-financial offerings criminals misuse (Services & Products)
*   **What** underlying mediums store or move value (Value Instruments)
*   **Where** relevant evidence might exist (Data Sources)
*   **Which** vulnerabilities criminals exploit (Risk Types)
*   **How** institutions might prevent or detect them (Mitigations)

By **interlinking** these six taxonomies with techniques, AMLTRIX enables more **practical** threat modeling. Institutions can define clearer detection rules and risk-based priorities (e.g., “Red flags for high-risk product usage by a potentially exploited actor, revealed through transaction logs”).

### 1.2 Bridging Regulatory vs. Operational Language

Many regulators (e.g., FATF, EBA) define categories such as “Financial Institutions,” “DNFBPs,” “High-Risk Products,” or “Sanctioned Entities,” while frontline AML practitioners often need more **granular** or **industry-specific** classifications (e.g., “peer-to-peer lending,” “chain-hopping in crypto,” “crowdfunding platforms,” “nonprofit that lacks strong governance”).

The AMLTRIX supplemental taxonomies combine these **top-down** concepts with **bottom-up** operational detail, offering a **common language** that can be easily adapted to local or institutional contexts.

* * *

## 2\. Key Design Principles

### 2.1 Focused Simplicity

Each taxonomy aims to keep categories **broad but recognizable**. More specific nuances can be added via sub-labels, metadata, or local adaptations. For instance:

*   **Risk Types** are grouped into **five** overarching categories (e.g., “Product Risk,” “Customer Risk,” “Channel Risk,” “Geographical Risk,” “Internal Risk”), rather than enumerating dozens of micro-risks.
*   **Data Sources** are assigned to **one** primary classification (“Transaction Logs,” “Open-Source Intelligence (OSINT),” “Customer Onboarding & Identity Data,” etc.), avoiding overlap that complicates usage.

### 2.2 Modularity & Interlinking

While each taxonomy can stand on its own, they become **most useful** when referenced together:

*   **Risk Types** typically link to specific **techniques** (e.g., layering via shell companies → “Customer Risk” from opaque ownership). They **may** in the future relate to other objects as well, but that remains optional.
*   **Actors** reference which **roles** (e.g., legitimate bank, illicit operator) can facilitate certain **techniques**.
*   **Services & Products** describe **offerings** that criminals exploit, which also appear in technique definitions.
*   **Value Instruments** pinpoint the mediums used (crypto, cash, securities), helping clarify how criminals store or move funds.
*   **Data Sources** show where investigators or monitoring systems might spot evidence (e.g., suspicious transactions in “Transaction Logs,” leads from “Open-Source Intelligence (OSINT)”).
*   **Mitigations** specify controls or measures (e.g., “Enhanced Due Diligence,” “Transaction Monitoring”) that reduce the effectiveness of particular techniques.

### 2.3 Bottom-Up + Top-Down

*   **Regulatory Influence**: Many definitions reflect FATF or other standard frameworks (e.g., “DNFBPs,” “PEPs,” “High-Risk Jurisdictions”).
*   **Operational Experience**: Real-world AML lessons shape practical categories like “Cash-Intensive Business,” “Shell or Front Company,” or “Crowdfunding Platform.”

This **combined** approach keeps the taxonomies relevant to both compliance mandates **and** day-to-day AML operations.

### 2.4 Future Adaptability

AMLTRIX is in **Beta** (as of 2025 Q2) and open to suggestions. Money laundering evolves quickly—new digital products, new cross-border payment apps, changing risk factors. These taxonomies remain **high-level** to accommodate ongoing refinements or expansions. Organizations may:

*   Create **sub-categories** or rename items for local needs.
*   Provide **feedback** on reclassification or newly emerging vulnerabilities via the AMLTRIX community ([contributions@amltrix.com](mailto:info@amltrix.com)).

* * *

## 3\. Overview of the Six Supplemental Taxonomies

### 3.1 Risk Types

*   **Scope**: Five categories (Product Risk, Customer Risk, Channel Risk, Geographical Risk, Internal Risk) that reflect a common, **sector-wide** approach to AML risk assessment.
*   **Usage**: Helps institutions systematically identify **which** dimension a laundering technique exploits (e.g., channel risk for remote account openings, product risk for prepaid cards).
*   **Linkage**: Primarily referenced in technique definitions; potential future linkages to other objects remain optional.

### 3.2 Data Sources

*   **Scope**: Categorizes the **repositories or information streams** relevant to AML detection (e.g., “Transaction Logs,” “Customer Onboarding & Identity Data,” “Watchlists & Adverse Data,” “Open-Source Intelligence (OSINT),” “Corporate & Ownership Data,” etc.).
*   **Usage**: In technique definitions, clarifies **where** to find indicators or red flags (e.g., suspicious transaction patterns, adverse media).
*   **Note**: A single data source is placed into **one** category for clarity.

### 3.3 Value Instruments

*   **Scope**: Encompasses **all** recognized ways of holding/transferring value—fiat currencies, commodities, digital tokens, securities, intangible assets, etc.
*   **Usage**: Links to **techniques** to specify which mediums criminals use (e.g., “bearer shares,” “cryptocurrencies,” “precious metals”).
*   **Benefit**: Highlights if a particular method frequently exploits certain non-traditional assets (e.g., NFT-based laundering).

### 3.4 Services & Products

*   **Scope**: Represents **offerings or platforms** (bank accounts, insurance, gambling, real estate services, e-commerce) that criminals can misuse.
*   **Usage**: In technique definitions, clarifies **how** a service or product is exploited to layer or move illicit funds (e.g., “Trade Finance & Commerce Enablement,” “Crypto & Digital Asset Services,” “Real Estate & Property Services”).
*   **Benefit**: Pinpoints which **service lines** or **product features** (anonymity, cross-border transfers) pose ML vulnerabilities.

### 3.5 Mitigations

*   **Scope**: Catalogs **controls or strategies** (e.g., KYC, EDD, transaction monitoring, staff training) that reduce the risk or impact of specific laundering methods.
*   **Usage**: Connects directly to **techniques**—for each laundering approach, AMLTRIX can suggest which mitigations might disrupt it.
*   **Role**: Bridges the gap between **knowing** a technique exists and **acting** to prevent or detect it.

### 3.6 Actors

*   **Scope**: Classifies **who** may be involved—ranging from legitimate banks and law firms to criminal networks or money mules.
*   **Usage**: Identifies typical roles behind certain ML methods (e.g., “Shell or Front Company,” “Professional Money Launderer,” “Potentially Exploited Cash-Intensive Business”).
*   **Context**: A single real-world party can embody multiple roles; AMLTRIX focuses on archetypes for threat modeling.

* * *

## 4\. Governance & Future Development

### 4.1 Beta Status & Community Feedback

Currently, AMLTRIX is in **Beta** (as of 2025 Q2). There is **no** official governance committee or consortium yet. However, the AMLTRIX team welcomes suggestions from regulators, financial institutions, solution providers, and industry experts at [**contributions@amltrix.com**](mailto:info@amltrix.com). Examples include:

*   **Adding/Revising Categories**: If you have an internal classification for new fintech services or specialized instruments, share it.
*   **Proposing Best Practices**: If you discovered an alternate approach that better suits certain markets, AMLTRIX is open to learning.

### 4.2 Adaptability & Local Customization

Users are free to **modify or expand** AMLTRIX for their internal processes, as needed:

*   **Local Extensions**: For instance, subdividing “Services & Products” into narrower categories if local regulations require more detail.
*   **Sharing Back**: Organizations are encouraged (though not required) to share these adaptations with the broader AMLTRIX community, fueling collaborative improvement and refinement.

### 4.3 Not Exhaustive, Not Final

The taxonomies are **not guaranteed** to be comprehensive or perfectly correct for every scenario. The AMLTRIX project openly acknowledges that **industry validation** is key:

*   **Continuous Improvement**: Real-world usage, lessons from investigations, and new legislative changes can refine or alter categories.
*   **Toward Maturity**: As AMLTRIX moves beyond Beta, a more formal governance structure may emerge, possibly co-led with interested stakeholders to steer expansions and maintain a stable versioning process.

* * *

## 5\. Compromises & Known Limitations

*   **Simplicity vs. Specificity**: Keeping top-level categories broad enables quick adoption. More detailed sub-categorizations remain optional.
*   **Jurisdictional Differences**: Definitions (e.g., which businesses count as DNFBPs) vary widely. AMLTRIX uses generalized terms, expecting local users to adapt where needed.
*   **Static Reference vs. Dynamic Reality**: These taxonomies are **conceptual**. They do not automatically update to reflect real-time changes (e.g., a once-legitimate service becomes illicit). Investigative or case-management systems handle such updates.
*   **Best-Fit Assignments**: A single item or entity might appear to match multiple categories. AMLTRIX typically enforces **one** main classification, with secondary tags capturing further context.

* * *

## 6\. How They Improve Modeling of ML Techniques

All six supplemental taxonomies—**Risk Types, Data Sources, Value Instruments, Services & Products, Mitigations, and Actors**—enhance ML technique modeling by:

*    **Adding Contextual Depth**: Techniques become richer when AMLTRIX points out **which** risk types they exploit, **who** typically employs them, or **which** products/instruments are involved.
*   **Guiding Detection & Prevention**: Mitigations tie back directly to techniques. Data sources clarify where to look for red flags. Services & Products define what criminals misuse. Actors show who executes it. Risk Types highlight the vulnerability dimension (e.g., product risk, channel risk).
*   **Facilitating Inter-Departmental & Inter-Organizational Communication**: A shared taxonomy cuts down on confusion—everyone references consistent terms for, say, “shell companies” or “transaction logs.”
*   **Supporting Risk Assessment**: When you know which technique hits which risk type, and which services or instruments criminals prefer, you can calibrate your institution’s **risk-based approach** more precisely.

* * *

## 7\. Conclusion

The **six supplemental taxonomies** in AMLTRIX—covering **Risk Types, Data Sources, Value Instruments, Services & Products, Mitigations,** and **Actors**—serve as **foundational building blocks** around which **techniques** (the core “how” of laundering) gain fuller meaning. They:

*   Unify references to the “**who, what, and where**” of money laundering.
*   Offer **standardized** but **flexible** frameworks to accommodate evolving threats.
*   Remain in **Beta** and **open** to community feedback, with no formal governance structure yet in place—interested parties are invited to suggest improvements or share real-world usage experiences.
*   Are **not** exhaustive or perfect, acknowledging that industry validation and iterative refinements are necessary for AMLTRIX to reach maturity.

By implementing these supplemental taxonomies alongside **techniques**, AML/CFT practitioners can achieve a more robust and **context-aware** knowledge graph—one that drives **better detection strategies**, fosters **interoperability**, and ultimately contributes to **stronger financial crime prevention** worldwide.

# Five Key AML/CFT Risk Types: A Practical Classification

Financial institutions typically classify AML/CFT vulnerabilities into product, service, transaction, customer, channel, and geographical categories in line with leading international guidance (e.g., FATF, EBA). In **AMLTRIX**, we slightly adjust this approach by consolidating products, services, and transaction activities into a single **Product Risk** category, reflecting the natural overlap in real-world usage. We also highlight **Internal Risk** to give explicit focus to operational and governance-related threats—though many frameworks would consider these under “controls” or “governance.”

Below is a concise explanation of each risk type, with an emphasis on how these categories can help map and label specific laundering techniques in everyday AML/CFT operations.

---

### 1. Product Risk

_(Combines references to products, services, and transactions)_

**Scope**

Financial offerings or transaction types that, by design or usage, can facilitate money laundering—particularly those providing anonymity, layering flexibility, or rapid cross-border flows.

**Relevant Factors for Tagging Behaviors**

- **Anonymity-Focused Features**
  - Prepaid cards with high load limits
  - Cryptocurrency services with minimal KYC
- **Complex or High-Volume Structuring**
  - Trade finance instruments, specialized derivatives
- **Rapid International Transfers**
  - Channels allowing large, quick cross-border remittances with limited checks

**Behavioral Examples**

- Splitting a large deposit into many small amounts via prepaid cards
- Layering funds across multiple jurisdictions using high-speed international remittance

---

### 2. Customer Risk

**Scope**

Aspects of a client’s profile—ownership structures, business models, or behaviors—that heighten ML or TF threats.

**Relevant Factors for Tagging Behaviors**

- **Opaque or Complex Ownership**
  - Shell companies, offshore vehicles, nominee directors
- **High-Profile or Potentially Corrupt**
  - PEPs, high-cash sectors like casinos, used-car dealerships
- **Unusual Patterns**
  - Reluctance to provide standard documentation, suspiciously large or swift transactions

**Behavioral Examples**

- Rapid changes in beneficial ownership in corporate structures
- Cash activity not aligning with the stated nature of the client’s business

---

### 3. Channel Risk

**Scope**

Potential vulnerabilities tied to how products/services are delivered or accessed—particularly remote or heavily intermediated channels.

**Relevant Factors for Tagging Behaviors**

- **Non-Face-to-Face Interactions**
  - Online-only account openings with minimal identity verification
- **Multiple Intermediaries**
  - Complex correspondent banking chains, unregulated local agents
- **Emerging and Unregulated FinTech**
  - Payment apps or crypto exchanges lacking oversight

**Behavioral Examples**

- Layering funds via digital wallets or e-payment gateways
- Creating accounts remotely with insufficient ID checks

---

### 4. Geographical Risk

**Scope**

Jurisdictional or regional factors that expose an institution to higher laundering risks, such as sanctioned territories or corruption hotspots.

**Relevant Factors for Tagging Behaviors**

- **Sanctioned or Conflict Zones**
  - Embargoed countries, war-torn regions
- **Weak Regulatory Environments**
  - Jurisdictions with limited AML controls, elevated organized crime
- **Secrecy & Offshore Havens**
  - Areas with strict banking secrecy or limited disclosure
- **Regulatory Misalignment**
  - Differences in AML/CFT standards, implementation, or enforcement—even in jurisdictions with generally well-developed legal systems—that can lead to regulatory arbitrage

**Behavioral Examples**

- Structuring fund transfers through countries with lighter AML reporting obligations to reduce scrutiny
- Using legal entities in secrecy jurisdictions to disguise beneficial ownership
- Structuring shipment routes through sanctioned territories to hide final recipients
- Leveraging mismatched regulatory regimes to shift assets with limited visibility or delay compliance actions

---

### 5. Internal Risk

**Scope**

Institutional and governance shortcomings—often recognized under “internal controls”—that enable or fail to detect illicit conduct within the bank or firm.

**Relevant Factors for Tagging Behaviors**

- **Weak Governance & Culture**
  - Insufficient board engagement, under-resourced compliance function
- **Insufficient Training & Oversight**
  - Staff unaware of key red flags, minimal internal auditing
- **Collusion or Conflicts of Interest**
  - Senior management or employees enabling suspicious transactions
- **Legacy or Fragmented Systems**
  - Outdated monitoring platforms, siloed data hindering enterprise-wide detection

**Behavioral Examples**

- Failing to escalate suspicious transactions due to staff complicity
- Neglecting AML red flags because employees lack adequate training

---

### Linking Techniques to Risk Categories

Each technique in AMLTRIX is cross-referenced with one or more of the five risk categories (Product, Customer, Channel, Geography, Internal) via an explicit relationship in the knowledge graph. This alignment clarifies _where_ and _why_ a given tactic or sub-technique might exploit a particular vulnerability in an institution. For instance, a laundering method that relies on minimal face-to-face interaction might be mapped to **Channel Risk**, while a structuring strategy leveraging complex derivative instruments would likely be linked to **Product Risk**.

By capturing these connections at the technique level, AMLTRIX enables practitioners to:

- **Pinpoint Vulnerabilities**: Understand exactly which risk dimensions (e.g., product, customer profile) a laundering method targets.
- **Improve Detection Rules**: Tailor monitoring logic to specific vulnerabilities, ensuring tighter alignment between detection policies and known adversarial tactics.
- **Enrich Analytics and Reporting**: Query which techniques predominantly exploit certain risk types, refining threat assessments and resource allocation.
- **Enhance Regulatory Oversight**: Demonstrate clear, evidence-based mappings between everyday compliance processes and the underlying AML/CFT risk framework.

In essence, correlating **techniques** with **risk categories** bridges the gap between high-level vulnerabilities and detailed illicit methods—deepening both strategic risk management and operational detection.


# Mitigations Taxonomy Design

## 1\. Introduction: What Are Mitigations?

In the context of Anti-Money Laundering (AML) **mitigations** are structured controls or measures used by financial institutions to prevent, detect, disrupt, and report illicit financial activities. They include policies, procedures, technological solutions, and other organizational practices that reduce the likelihood and impact of money laundering or other illicit financial activities.

Mitigations often **map directly** to money laundering techniques or typologies. For example, if criminals use trade-based money laundering schemes (e.g., misinvoicing or over/under-valuation of goods), a related mitigation might be _Trade Monitoring_, which specifically checks trade transactions and documentation for inconsistencies.

### Linkable With Money Laundering Techniques

In a knowledge graph, each mitigation can be **linked** to one or more documented money laundering techniques or subtechniques. This allows analysts to trace how real-world typologies—such as cash structuring, or chain peeling—can be addressed by specific controls (e.g., Cash Transaction Reporting or Blockchain Monitoring).

* * *

## 2\. Three Core Dimensions of Mitigation Taxonomy

A robust taxonomy helps compliance teams quickly find, compare, and apply relevant measures for specific risk scenarios. Here, we define **three complementary dimensions** for classifying each mitigation:

1. **Functional Category**
2. **Application Level (Tactical vs. Strategic)**
3. **Client Relationship Stage**

To avoid confusion and over-complication of the knowledge graph, we assign each mitigation to **one** primary functional category and **one** primary application level, while **client relationship stage** can be a multi-select (a single mitigation may apply to multiple or no stages).

### Why Separate These Dimensions?

*   **Functional Category** answers “_What type of control is this?_” in terms of operational focus (e.g., due diligence, monitoring, risk management).
*   **Application Level** clarifies whether the measure addresses **immediate day-to-day** concerns (tactical) or **longer-term, high-level** oversight (strategic).
*   **Client Relationship Stage** highlights **when** the mitigation is most relevant in the client lifecycle (onboarding, ongoing relationship, post-termination, etc.).

This modular approach provides a balanced view: each control’s fundamental purpose, its scope (tactical or strategic), and the points in the client journey where it applies.

* * *

## 3\. Functional Categories

Below are **groupings** of mitigations by their **primary** function. Every mitigation is assigned to **one** of these categories.

1. **Onboarding & Customer-Related Due Diligence**
    *   **Purpose:** Verifying or updating customer identity, beneficial ownership, and risk levels.
    *   **Examples:** Customer Due Diligence (CDD), Enhanced Due Diligence (EDD), Sanctions & Watchlist Screening, OSINT & External Source Verification.
2. **Transaction & Activity Monitoring & Escalation**
    *   **Purpose:** Identifying suspicious or high-risk transactions through real/near-real-time monitoring, and escalating them as necessary.
    *   **Examples:** Transaction Escrow Management, Cash Transaction Reporting (CTR), Trade Monitoring, Blockchain Monitoring, Suspicious Activity Reporting (SARs/STRs), Transaction Monitoring.
3. **Risk Management & Governance**
    *   **Purpose:** Enterprise-level oversight, strategic assessment, and cross-cutting frameworks that shape the organization’s risk posture.
    *   **Examples:** Enterprise-Wide Risk Assessment (EWRA), Country Risk Assessment, Independent Audit & Testing, Third-Party Risk Management, Information Sharing & Collaboration, a conscious “Do Not Mitigate” (when additional controls are deemed counterproductive).
4. **Organizational & Internal Controls**
    *   **Purpose:** Day-to-day management of internal processes, policies, data security, record-keeping, and staff escalation mechanisms.
    *   **Examples:** Quality Assurance & Control, Internal Policies and Procedures, Data Protection & Security Controls, Record-Keeping & Audit Trails, Internal Reporting Mechanisms, Designation of Nominated Officer, Access Authentication & Monitoring.
5. **Relationship Actions**
    *   **Purpose:** Direct interventions in a customer relationship to reduce or remove risk (e.g., suspending or ending the relationship).
    *   **Examples:** Service Restriction, Client Relationship Termination.
6. **People & Awareness**
    *   **Purpose:** Human-focused measures that strengthen AML knowledge, integrity, and compliance culture among staff or customers.
    *   **Examples:** Employee Background Screening, Customer Education & Awareness, Staff AML Training & Awareness.

This classification provides a quick conceptual map: Is this measure about monitoring, governance, or how we handle staff training?

* * *

## 4\. Application Level: Tactical vs. Strategic

### **Tactical Mitigations**

*   **Definition**: Short- to medium-term operational measures.
*   **Scope**: Address **immediate, day-to-day** AML/CFT requirements.
*   **Characteristics**:
    *   Often carried out by front-office staff, investigators, or compliance analysts.
    *   Targets specific patterns or behaviors (e.g., real-time transaction alerts).
    *   Can be quickly adjusted or tuned as typologies evolve.

**Examples**:

*   Transaction Monitoring (real-time detection)
*   Cash Transaction Reporting (CTR)
*   Enhanced Due Diligence (EDD)
*   Suspicious Activity Reporting (SARs/STRs)

### **Strategic Mitigations**

*   **Definition**: Long-term, higher-level organizational measures that guide the entire AML/CFT framework.
*   **Scope**: Shape **enterprise governance**, resource allocation, and overall AML/CFT culture.
*   **Characteristics**:
    *   Often steered by senior management or boards.
    *   Involves broad policy decisions (risk appetite, cross-functional coordination).
    *   Requires more planning and cross-department input, with periodic reviews.

**Examples**:

*   Enterprise-Wide Risk Assessment (EWRA)
*   Independent Audit & Testing
*   Third-Party Risk Management
*   Quality Assurance & Control

In many cases, a single mitigation might be partially tactical and partially strategic. However, _for clarity’s sake_ in a taxonomy, we **classify it by its dominant purpose**.

* * *

## 5\. Client Relationship Stages

We propose a set of client lifecycle stages that highlights **when** the mitigation is most relevant in the client lifecycle. Each stage can be assigned to a mitigation if relevant, but a mitigation can belong to **several** stages or **none** if it is an overarching measure.

1. **Not Directly Related (or Pre-Interaction)**
    *   Activities occurring **before** any direct engagement with a client or overarching and not directly related to client interactions.
    *   Examples: Setting overall AML policy frameworks, establishing acceptance criteria, market-level risk analysis.
2. **Pre-Onboarding Engagement**
    *   Initial contact with prospective clients—initial inquiries, basic risk checks, or high-level eligibility checks.
3. **Onboarding**
    *   Formal process of registering the customer, performing CDD/KYC, verifying identities, setting up accounts.
4. **Ongoing Relationship**
    *   Active, day-to-day interaction with fully onboarded clients. Involves routine transactions and periodic reviews.
5. **Post Alert**
    *   Triggered if suspicious activity or a high-risk event is detected within an ongoing relationship.
    *   Involves investigations, SAR filing, or deciding whether to continue the relationship.
6. **Post Termination**
    *   After an institution has exited the relationship. Covers record retention, any final regulatory reporting, or watch for re-entry attempts.
7. **Ad Hoc Interaction**
    *   Irregular or one-off engagements that do not follow typical onboarding or ongoing relationship patterns (e.g., a one-time transaction).
   
# Services & Products Taxonomy Design

In an Anti-Money Laundering (AML) and Counter-Terrorist Financing (CFT) context, it’s vital to understand not only the **value instruments** criminals use but also the **services and products** they exploit. While a _value instrument_—such as cash, a cryptocurrency token, or a commodity—represents a store or transfer of monetary value, a _service or product_ is an **offering** or **platform** provided by institutions or intermediaries, which facilitates how illicit funds can be **stored**, **moved**, **transformed**, or **concealed**. This section outlines a single‐dimension taxonomy for services and products, discussing **why** we chose such a framework, **how** it differs from the approach for value instruments, and **how** we accounted for overlaps or multiple interpretations.

* * *

## 1\. What Are Services & Products?

**Definition:**

> **Services and Products are the offerings and platforms provided by institutions or intermediaries that can be exploited by launderers to store, move, transform, or conceal illicit funds.**

*   **Examples of Services:** Banking (deposit, lending), legal advisory, notary services, trade finance, escrow.
*   **Examples of Products:** Specific accounts (checking, savings, trust), credit cards, insurance policies, or specialized payment instruments.

Whereas **value instruments** refer to _what_ criminals launder (e.g., cash, cryptocurrencies, securities), **services & products** refer to _how_ criminals launder, i.e., the channels or commercial offerings that enable the flow, manipulation, or disguise of value. In practice, criminals exploit:

*   **Value instruments** to **hold** and **transfer** illicit funds.
*   **Services & products** to **facilitate** or **structure** those transfers, sometimes adding layers of complexity (e.g., setting up a business bank account, using an offshore corporate service, or purchasing a life insurance product).

* * *

## 2\. Why “Services & Products” (Not Just “Services”)?

Some offerings are best viewed as _services_, such as wire transfers or trust administration, while others are _products_, like a specific type of loan or an insurance policy. By using **both terms**, we:

*   **Capture the full range** of what financial and non-financial intermediaries provide.
*   **Acknowledge the difference** between a recurring service (like ongoing corporate trust management) and a discrete financial product (like a fixed deposit account).
*   **Allow for clarity** when certain offerings are clearly a _product_ (e.g., a particular savings account) vs. a _service_ (e.g., a broader escrow arrangement).

* * *

## 3\. Single‐Dimension Taxonomy Overview

To keep the knowledge graph **manageable**, we grouped all services & products into **one** of the following categories. This helps limit complexity—each offering has a **single “home”** even though real-world usage can overlap categories.

1. **Payment, Transfer & Remittance Services**
2. **Deposit & Account Services**
3. **Lending & Credit**
4. **Corporate, Trust & Legal Services**
5. **Wealth & Investment**
6. **Trade Finance & Commerce Enablement**
7. **Insurance & Risk Management**
8. **Crypto & Digital Asset Services**
9. **Real Estate & Property Services**
10. **Gambling & Gaming**
11. **E-commerce, Marketplaces & Retail**
12. **Professional & Advisory Services**

Each category has **broad definitions** to accommodate regional differences and the many forms each service or product can take.

* * *

### Category Definitions & Illustrations

1. **Payment, Transfer & Remittance Services**
    *   **Definition:** Services that primarily handle the **movement of funds** between parties—whether domestic or cross-border.
    *   **Examples:** Wire transfers, money remittance platforms, third-party payment gateways, peer-to-peer payment systems, debit card and prepaid card services.
2. **Deposit & Account Services**
    *   **Definition:** Offerings focused on **holding funds** or valuables at financial institutions, including checking/savings accounts, trust accounts, safe deposit boxes, and specialized deposit products (e.g., student or business banking).
    *   **Examples:** Business bank accounts, personal checking, pooled client accounts, escrow accounts, remote deposit capture, Islamic banking services (with deposit-based products).
3. **Lending & Credit**
    *   **Definition:** Services and products that provide **funding or credit** to borrowers, often with repayment plus interest or fees.
    *   **Examples:** Personal loans, mortgages, credit cards, buy-now-pay-later, asset-based financing, factoring, pawnshop services.
4. **Corporate, Trust & Legal Services**
    *   **Definition:** Services that **form**, **administer**, or **manage** legal entities or specialized structures (including trust & company service providers), as well as legal or notarial functions.
    *   **Examples:** Offshore company incorporation, corporate directorship, trustee services, notary services, professional fiduciary oversight.
5. **Wealth & Investment**
    *   **Definition:** Services intended to **manage or grow** assets on behalf of clients—whether through advisory, brokerage, or structured products.
    *   **Examples:** Securities brokerage, wealth management, private banking, OTC trading (broad asset classes), investment funds, derivatives, pension management.
6. **Trade Finance & Commerce Enablement**
    *   **Definition:** Services designed to **facilitate domestic or cross-border trade**.
    *   **Examples:** Letters of credit, documentary collection, shipping/logistics (freight forwarding), supply chain financing, trade facilitation platforms.
7. **Insurance & Risk Management**
    *   **Definition:** Services offering **risk coverage**, such as life insurance, property/casualty policies, and reinsurance.
    *   **Examples:** Life insurance products (with cash value), reinsurance agreements, captive insurance, insurance-based investments.
8. **Crypto & Digital Asset Services**
    *   **Definition:** Services enabling the **exchange, custody, or creation** of digital tokens or cryptoassets.
    *   **Examples:** Cryptocurrency exchanges, digital wallets, decentralized finance (DeFi) protocols, cross-chain bridging services, P2P crypto trading platforms.
9. **Real Estate & Property Services**
    *   **Definition:** Services dealing with the **sale, management, or custody** of real or intangible property.
    *   **Examples:** Real estate agencies, property management, real estate transaction services, art custodial (if more about physical property storage than investment strategy).
10. **Gambling & Gaming**
    *   **Definition:** Services that enable **wagering or betting** with real or digital funds, whether online or offline.
    *   **Examples:** Casinos, sports betting platforms, lottery, gambling payment processing.
11. **E-commerce, Marketplaces & Retail**
    *   **Definition:** Platforms or services facilitating the **buying/selling of goods** or **crowdfunding**, often with integrated payment tools.
    *   **Examples:** Online auction sites, freelance job marketplaces, donation platforms, retail e-commerce, travel booking platforms.
12. **Professional & Advisory Services**
    *   **Definition:** General professional offerings that aren’t purely “financial,” but can still facilitate laundering—ranging from **consulting** to **mail/courier** to **virtual office**.
    *   **Examples:** Legal advisory, accounting/auditing, virtual office services, mail/courier, citizenship-by-investment consulting.

* * *

## 4\. Overlap, Ambiguities & Compromises

### Single Category Constraint

Each service/product is assigned to **one** category to limit complexity. However, many services could plausibly fit in multiple groups—for example, _Islamic Banking_ might mix deposit and lending products, or _Over-the-Counter (OTC) Trading_ might be purely crypto or multi-asset. We **chose** whichever function seemed **most central**.

### Broader, Not Strictly Regulatory Aligned

These categories don’t necessarily match any one regulator’s definitions—**jurisdictions** can treat certain activities differently. For instance, insurance-based investment products might be regulated as securities in one country but handled as standard insurance in another. By keeping definitions **broad**, we leave room to **further specify** local details when connecting these categories to _techniques_ in the knowledge graph.

### Non-Financial Services

Some included offerings (e.g., mail, courier, or virtual office services) are **not** regulated as financial services, yet remain relevant in **AML/CFT** scenarios. Criminals can abuse them to hide beneficial owners, reroute official correspondence, or maintain the illusion of local presence. From a knowledge graph perspective, capturing these potential “facilitators” is crucial.

### Limited Coverage, High-Level Definitions

We deliberately **did not** attempt to capture every sub-variant or nuance (e.g., subdividing “Islamic financing” into murabaha vs. mudarabah). Instead, we keep definitions **high-level** so they’re easier to maintain and expand upon **when** linking to specific laundering techniques.

* * *

## 5\. Linking Techniques and Mitigations

We do **not** directly connect services/products to mitigations in this framework. Instead:

1. **Techniques** (how criminals launder money) are linked to relevant **services/products** they exploit.
2. **Techniques** are also mapped to potential **mitigations**.
3. **Services** and **mitigations** thus become indirectly connected—knowing which services criminals abuse guides which mitigations an institution might deploy.

This approach keeps the knowledge graph more **scalable** and **modular**: changes to how one technique is mitigated don’t necessarily upend the entire classification of services.

* * *

## 6\. Why This Matters for AML/CFT

*   **Holistic Visibility**: By mapping all relevant services/products—both strictly financial and tangential (like corporate or real estate services)—institutions and regulators get a **bigger picture** of how illicit funds might flow.
*   **Scalable Classification**: A single, consistent taxonomy **simplifies** how these services appear in queries and visual dashboards, avoiding duplication or overshadowing.
*   **Adaptability**: As new services or products emerge (e.g., novel DeFi protocols, advanced payment processors), they can slot into existing categories or prompt the creation of new ones.
*   **Regulatory & Compliance Utility**: Even if certain services aren’t directly regulated in one jurisdiction, they can still be relevant from a compliance risk standpoint, enabling risk-based measures where necessary.

* * *

## 7\. Conclusion

This taxonomy for services & products **complements** the classification of **value instruments** in an AML/CFT knowledge graph, ensuring that analysts see both **the items criminals move (instruments)** and **the channels they exploit (services & products)**. By assigning each service/product to one **broadly defined** category—without trying to match each jurisdiction’s legal codes exactly—we attempt to strike a **balance** between **simplicity** and **comprehensive coverage**.

Crucially, the framework remains **flexible**. Each institution or regulator can refine or adapt categories (e.g., splitting out “Islamic Financing” or “Offshore Services” if local laws demand) without losing the **high-level structure** that makes the methodology consistent and scalable.

# Value Instruments Taxonomy Design

### 1\. Introduction & Purpose

In the realm of **money laundering and terrorist financing** analysis, _value instruments_ refer to any assets or vehicles—physical, digital, tangible, or intangible—that can be used to **store, transfer, or disguise value**. This includes conventional items, like cash or securities, as well as less obvious instruments, such as domain names or in-game currencies. By mapping these instruments to known laundering techniques, investigators and compliance teams can better understand **how** illicit actors move or hide funds and **which controls** might disrupt them.

### 2\. Core Categories & Definitions

A common approach is to define broad **categories** that each capture one type of instrument. For example:

1. **Fiat (Physical/Digital) & Paper-Based Payment Instruments**
    *   E.g.: Cash, checks, money orders, **digital fiat currencies**, bearer negotiable instruments
2. **Card-Based & Stored-Value Payment Instruments**
3. **Bank & Deposit Accounts**
4. **Trade & Commercial Instruments**
5. **Securities & Investment Vehicles**
6. **Commodities & High-Value Tangible Assets**
7. **Intangible/Non-Physical Property**
8. **Crypto & Other Digital Tokens**
9. **Insurance & Other Financial Contracts**

Although these categories have definitions, they are **not** strict or mutually exclusive. **Overlaps** are **accepted** as part of the design principle, acknowledging that real-world instruments often blur boundaries.

  

Below is a **table** summarizing each _group_ along with a few **examples** to illustrate what typically falls under each category.

| **Group** | **Definition** | **Typical Examples** |
| ---| ---| --- |
| **Fiat (Physical/Digital) & Paper-Based Payment Instruments** | Government-issued currencies (whether physical notes/coins or digital forms) and other tangible, negotiable payment documents that can be transferred or redeemed for face value. These instruments often circulate outside formal account-based systems. | \- Physical cash and digital fiat currency<br>\- Checks, money orders, bank drafts<br>\- Traveler’s checks<br>\- Bearer negotiable instruments<br>\- Casino chips, TITO tickets |
| **Card-Based & Stored-Value Payment Instruments** | Payment methods tied to accounts or preloaded balances, used for transactions without necessarily relying on physical paper instruments. They offer portability and broad acceptance but are typically not bearer-based. | \- Credit and debit cards<br>\- Prepaid cards<br>\- Mobile money or e-wallets<br>\- Online gambling accounts |
| **Bank & Deposit Accounts** | Financial accounts maintained at banks or other depository institutions, enabling depositing, withdrawing, transferring, and storing funds. These accounts can be demand deposits, savings, or specialized fiduciary/trust accounts. | \- Checking and savings accounts<br>\- Time deposits (fixed-term certificates)<br>\- Trust or fiduciary accounts |
| **Trade & Commercial Instruments** | Negotiable or contractual documents specifically designed to facilitate and secure trade transactions, credit relationships, or payment guarantees in commercial settings. | \- Letters of credit - Bills of exchange<br>\- Promissory notes<br>\- Trade finance instruments (e.g., shipping documentation, invoices)<br>\- Accounts receivable |
| **Securities & Investment Vehicles** | Financial instruments representing ownership, debt, or other rights in a venture or asset, generally regulated as securities or used for investment purposes. They may be traded on exchanges or in private transactions. | \- Stocks, bonds, and money market instruments - Derivatives (options, futures, swaps)<br>\- Units in mutual funds or ETFs<br>\- Real Estate Investment Trusts (REITs)<br>\- Bearer shares<br>\- Security tokens |
| **Commodities & High-Value Tangible Assets** | Physical goods with inherent value or collectible significance, often traded in specialized markets. These assets can serve as alternative stores of value, be easily transported (in some cases), and vary in liquidity. | \- Precious metals (gold, silver), gemstones - Artwork, antiquities, luxury goods<br>\- Real estate holdings<br>\- Commodity products (oil, restricted or illicit goods)<br>\- Gold certificates<br>\- Jewelry |
| **Intangible/Non-Physical Property** | Valuable rights or assets that do not have a physical form but can be bought, sold, licensed, or otherwise transferred. Regulatory treatment may vary significantly by jurisdiction. | \- Intellectual property (patents, trademarks)<br>\- Domain names & online businesses<br>\- Carbon credits & emission allowances<br>\- Trust beneficial interests |
| **Crypto & Other Digital Tokens** | Blockchain-based or purely digital tokens that may act as mediums of exchange, stores of value, utility entitlements, or proofs of ownership in virtual or decentralized environments. | \- Public ledger cryptocurrencies (Bitcoin, Ethereum)<br>\- Privacy coins (Monero)<br>\- Stablecoins (USDC, Tether)<br>\- NFTs and utility tokens<br>\- Governance tokens<br>\- In-game / loyalty points<br>\- Wrapped tokens, staked crypto assets |
| **Insurance & Other Financial Contracts** | Specialized financial agreements that provide coverage, payouts, or other contractual benefits, not typically classified as securities or deposit accounts. They can be assigned or transferred under certain conditions and add unique AML/CFT considerations. | \- Insurance policies (life, property, liability)<br>\- Other specialized contracts offering financial coverage or guaranteed payouts |

* * *

### 3\. Design Compromises & Bottom-Up Approach

This taxonomy reflects a **bottom-up** approach, meaning it was built by:

1. Listing **actual instruments** encountered in real laundering typologies,
2. Grouping them according to **common usage** and **regulatory treatments**,
3. Accepting that some instruments could appear in more than one place if we tried to be strict.

However, **to keep each instrument in exactly one place**, we choose the _best-fit_ group. This approach is **purposefully flexible**:

*   We recognize that **jurisdictional differences** can classify certain items (e.g., _carbon credits_) as securities in one region but intangible property in another.
*   We allow categories to **overlap conceptually** while assigning each item to only one group for simpler searching and filtering.

* * *

### 4\. Overlap & Non-Exclusive Definitions

Despite the single‐dimension placement, the **definition boundaries aren’t absolute**. For instance:

*   **Gold Certificates** – Some institutions treat them like “commodities” because they directly represent gold. Others treat them more like “securities” (since they represent a claim on an underlying asset).
*   **Digital Fiat Currency** – Might fit neatly with “Fiat & Paper‐Based Instruments,” or it might be considered a “CBDC” in certain jurisdictions if central banks back it in a specific manner.
*   **Bearer Shares** – They are _physically_ transferable but still represent equity; hence they often land in “Securities & Investment Vehicles.”

This **lack of strict hierarchy** is **useful** because it accommodates real‐world complexity. Financial crime analysts often just need a “primary classification” to locate items, then rely on additional _metadata_ or tags (e.g., “Is it intangible?” “Is it regulated as a security?”) to refine the search.

* * *

### 5\. Mapping Instruments to Techniques

A **core reason** for creating such a taxonomy is to see **which instruments** criminals might exploit in various laundering schemes. For example:

*   **Digital Fiat Currency** or **Digital Wallets** can be transferred simply by handing over private keys, effectively enabling peer-to-peer transfers outside typical bank rails.
*   **Art & Collectibles** can be used in complex trade-based laundering due to subjective valuations.
*   **In-game currencies** can be turned into real cash if the platform allows player-to-player trading.

By labeling each instrument with a **single primary category** but letting the definitions remain flexible, analysts can quickly see:

1. **Which category** does a technique most often exploit?
2. **Which detection or compliance controls** might apply? (e.g., enhanced KYC for digital wallets, specialized trade monitoring for art).

* * *

### 6\. Justifying Non-Traditional Items as Value Instruments

In many jurisdictions, something like a **digital gaming account** or an **online wallet** might **not** be formally recognized as a “traditional instrument.” However, **criminals can still use** these mediums to **store** or **transfer** value.

For example:

*   **Gifting a private key** for a cryptocurrency wallet
*   **Handing over a high-level online gaming account** with store credit or valuable in-game items
*   **Sharing a domain name** that has significant brand value in the black market

Hence, we **label them as value instruments** because from a money laundering perspective, they can serve the **same** function: an asset that can be bought, sold, bartered, or used to hide illicit funds.

* * *

### 7\. Jurisdictional Differences & Variable Treatments

Laws differ across countries, so the same item may be:

*   Treated as **a security** in one region,
*   Treated as **a commodity** in another,
*   Or remain **unregulated** in yet another place.

**Carbon credits** are a classic example:

*   In Country A, they might be licensed exactly like a security.
*   In Country B, they might be purely considered _intangible property rights_.
*   In Country C, they might have a special “environmental commodity” classification.

Because of these **variations**, a single, rigid classification cannot accommodate every legal environment. Our approach acknowledges that **local regulation** can shift an item’s category.

* * *

### 8\. Examples of Different Interpretations

*   **Gold Certificates**:
    *   **One institution** might put them in “Commodities” because they’re effectively _paper gold_.
    *   **Another** might see them as “Securities & Investment Vehicles,” particularly if they trade on an exchange.
    *   **A third** might store them under “Intangible Property” if the local legal system treats them as claims on gold but not strictly a commodity or security.
*   **Bearer Negotiable Instruments**:
    *   Often placed with physical payment instruments because they circulate “hand‐to‐hand.”
    *   But one could theoretically group them with “Securities,” especially if they represent short‐term debt from a reputable issuer.

These differences highlight why **no single universal classification** can capture all local nuances. However, for the **purpose of an AML/CFT knowledge graph**, the real objective is to ensure each item has **one consistent home** so users can find it, while recognizing that local legal frameworks may differ.

* * *

### 9\. Conclusion: Practical Flexibility Over Strict Hierarchies

In designing a single‐dimension taxonomy:

1. We **accept conceptual overlap** but demand each item appear **once** to avoid duplication.
2. We **maintain flexible definitions** that are _not_ mutually exclusive and do _not_ form a strict hierarchy.
3. We **acknowledge** that instruments can be used in creative ways to store or transfer value—some not traditionally seen as “financial instruments.”
4. We **remain mindful** of regional variations and potential reclassifications (like _carbon credits as securities_).

This **bottom-up** design ensures the taxonomy mirrors **real-world usage**—where criminals exploit everything from domain names to online gaming credits—while giving analysts a **practical tool** to quickly locate each instrument and link it to laundering techniques. It’s precisely because **value can hide in unexpected places** that a broad, flexible classification system is essential for effective AML/CFT intelligence.

# Data Sources Taxonomy Design

In the field of Anti-Money Laundering (AML), Counter-Terrorist Financing (CFT), and Counter-Proliferation Financing (CPF), a _data source_ is any origin or system that provides structured or unstructured information critical to detecting, assessing, or investigating potential financial crime activity. Such information feeds into detection models, risk assessments, and regulatory reporting, helping analysts and investigators identify indicators, validate red flags, and trace illicit flows of value.

When designing a taxonomy for these data sources, we chose to ensure each source fits into exactly one category—thus avoiding overlap and confusion. We have grouped data sources based on how they are most commonly used within AML/CFT/CPF processes, with the understanding that each source is assigned to the single category where it is _most likely_ to be referenced.

* * *

### 1\. Transaction & Payment Data

**Purpose:**

Captures any movement of money or digital value, whether fiat or cryptocurrency. It includes transactional details, balances, and usage logs. This category often forms the first line of defense for spotting unusual transaction patterns.

**Examples of Included Sources:**

*   Transaction logs
*   ATM usage and geolocation data
*   Records from donation platforms, online payment platforms, currency exchanges, and cryptocurrency services
*   Casino, cross-border, and prepaid card transaction data
*   Bank account data and account activity logs
*   Blockchain analytics and trading activity records

* * *

### 2\. Customer Onboarding & Identity Data

**Purpose:**

Covers records used to verify and document the identities of individuals or entities, including KYC (Know Your Customer) and due diligence information. It often includes specialized document verification systems and any centralized repositories for identity records.

**Examples of Included Sources:**

*   KYC & customer due diligence files
*   Document verification tools
*   Internal document management platforms
*   Public or aggregated identity databases

* * *

### 3\. Watchlists & Adverse Data

**Purpose:**

Centralizes data sources that help screen for high-risk or prohibited parties, such as sanctions lists, politically exposed person (PEP) lists, industry fraud alerts, and adverse media. These sources are crucial for preventing transactions with sanctioned or otherwise high-risk individuals and entities.

**Examples of Included Sources:**

*   Sanctions lists
*   PEP databases
*   Fraud data repositories
*   Adverse media and court filings

* * *

### 4\. OSINT & Communication Data

**Purpose:**

Draws on open-source intelligence (OSINT) and communication records, such as phone logs, emails, messaging apps, and social media. Investigators use these to corroborate customer information or detect suspicious narrative patterns.

**Examples of Included Sources:**

*   Publicly available websites and social media posts
*   Records of electronic communications (where permissible)

* * *

### 5\. Corporate & Ownership Data

**Purpose:**

Provides records clarifying the legal structures of companies, trusts, and other organizational entities, often revealing beneficial ownership or hidden relationships. These records are vital for unmasking shell companies or layered corporate structures.

**Examples of Included Sources:**

*   Company and beneficial ownership registries
*   Trust information and accounts
*   Licensed money service business registries
*   Real estate and other high-value asset ownership data

* * *

### 6\. Access & Security Data

**Purpose:**

Encompasses physical or digital access logs—ranging from safe deposit box records to network access logs. These help track and investigate unauthorized activity or anomalies in how systems and facilities are accessed.

**Examples of Included Sources:**

*   Safe deposit box access logs
*   System and network access logs
*   Cybersecurity event data (e.g., failed login attempts or reported account takeovers)

* * *

### 7\. Loan & Credit Data

**Purpose:**

Includes all formal lending documentation, such as loan and mortgage agreements or credit card facilities. These records clarify liabilities, repayment behaviors, and potential irregular usage of credit lines.

**Examples of Included Sources:**

*   Loan agreements
*   Credit facilities and mortgage documents

* * *

### 8\. Market & Instrument Data

**Purpose:**

Focuses on pricing, trading volume, and related metrics for various financial instruments—stocks, bonds, derivatives—as well as commodities. This data is crucial for detecting market manipulation or confirming legitimate trades.

**Examples of Included Sources:**

*   Financial instrument and securities market data
*   Commodity market data

* * *

### 9\. Customs, Border & Trade Data

**Purpose:**

Covers all import/export records, border crossings, and official trade documents. It is essential in detecting trade-based money laundering (TBML), smuggling, and hidden international flows of goods and value.

**Examples of Included Sources:**

*   Customs and border records
*   Asset seizure data
*   Trade documentation

* * *

### 10\. Legal, Regulatory & Licensing Data

**Purpose:**

Consists of official legal documentation—such as asset declarations, court filings, and professional licenses. Analysts use these to confirm individuals’ or entities’ legal standing, declared assets, and adherence to regulatory obligations.

**Examples of Included Sources:**

*   Asset declarations
*   Professional licensing and affiliation databases
*   Legal documentation
*   Country/jurisdictional risk references

* * *

### 11\. Business & Financial Records

**Purpose:**

Broad category for internal or external records that detail a business’s operations and finances. These might include tax filings, audit reports, and routine performance metrics, often analyzed to spot inconsistencies or anomalies.

**Examples of Included Sources:**

*   Contracts and invoices
*   Financial, business, and tax records
*   External or internal audit reports
*   Data on business activities or operations

* * *

### 12\. Product & Service Usage Data

**Purpose:**

Collects information on how clients interact with specific financial products or services, separate from individual transactions. Analysts can use these patterns to detect suspicious spikes in usage or product misapplication.

**Examples of Included Sources:**

*   Product and service usage dashboards
*   Aggregated metrics on customer engagement

* * *

### 13\. Employment & HR Data

**Purpose:**

Covers both internal employee records and external recruitment data. This information can reveal internal conflicts of interest, insider threats, or money-mule recruitment schemes.

**Examples of Included Sources:**

*   Job recruitment data
*   Employee records

* * *

### Principles of Category Assignment

*   **No Overlap:** Each data source belongs to _one_ primary category, preventing confusion about where it fits.
*   **Utility Focus:** Categories reflect _how_ data is most commonly used in AML/CFT/CPF processes.
*   **Bottom-Up Approach:** This taxonomy emerged from documenting varied money laundering techniques and associated behaviors. As these techniques were analyzed, clear data source patterns were identified, which then shaped the groupings.
*   **Adjustable Granularity:** If an organization requires fewer or more detailed categories, these can be merged or subdivided.
*   **Practical Usage:** Categories such as “Transaction & Payment Data” are deliberately broad to consolidate all flows of money, while specialized domains (e.g., OSINT, watchlists, corporate ownership) are grouped separately for clarity.

* * *

### Conclusion

This taxonomy provides a structured way to classify the many data sources used in AML/CFT/CPF. By organizing each source into a single logical category, investigators, analysts, and system architects can more easily navigate and apply the information. The scheme draws on a bottom-up perspective—derived from real-world investigations of financial crime techniques—and seeks to be both comprehensive and flexible. Adjustments can be made as new threats evolve or new sources become available, while still preserving the principle that every data source belongs exactly once in the taxonomy.

# Actors Taxonomy Design

**Actors taxonomy** is an integral part of the AMLTRIX framework, aimed at standardizing how diverse and multi-purpose **roles**—spanning individuals, legal entities, networks, or structures—are represented in **money laundering threat models**. By clearly defining **who** might be involved and **how**, AMLTRIX provides a consistent reference for describing, contextualizing, and explaining money laundering **techniques**.

* * *

## 1. Motivation & Background

### 1.1 Why Actors Matter

In money laundering (ML), terrorist financing (TF), and related illicit behaviors, **which actors** are involved can be just as critical as **how** illicit activities are conducted. An “actor” might be:

- A **regulated financial institution** (e.g., a licensed bank)
- A **private individual** (e.g., a cardholder, account holder, beneficial owner)
- A **criminal organization or network** (e.g., drug traffickers, terrorist financiers, professional money launderers)
- A **special-purpose entity** (e.g., a shell company, an offshore trust, or a nonprofit that can be exploited)

Often, these categories overlap in practice. A single business may be thoroughly legitimate yet unwittingly exploited by criminals, or an individual might simultaneously be a professional advisor, a nominee, or even a money mule. Consequently, AMLTRIX emphasizes a **flexible** yet **structured** approach to classifying actors, ensuring consistent labeling in a machine-readable knowledge graph.

* * *

## 2. Two-Dimensional Classification for Actors

In AMLTRIX, **actors** are categorized along two distinct dimensions:

1. A **Main Group (Functional Role)**, to indicate the actor’s primary domain or purpose.  
2. An **Actor Type (Legitimate, Illicit/Criminal, or Potentially Exploited)**, to capture the actor’s default posture or risk profile.

Each **actor archetype** in the knowledge graph is defined by exactly one **Main Group** and exactly one **Actor Type**. This structure ensures **clarity** when referencing “who” is involved in money laundering **techniques**—without overwhelming the taxonomy with duplicates or multi-category listings.

* * *

### 2.1 Main Group (Functional Role)

The **Main Group** reflects an actor’s **core function**, indicating the sort of activity, service, or organizational identity the actor typically represents. AMLTRIX recognizes seven high-level Main Groups, each capturing a broad slice of real-world actors:

1. **Financial Institutions & Services**
    - **Definition**: Regulated (or partially regulated) entities that offer deposit-taking, investment, lending, payment, money transfer, insurance, or other financial services.
    - **Real-World Examples**: Banks, credit unions, prepaid card issuers, money services businesses (MSBs), virtual asset service providers (VASPs), insurance firms, finance or leasing companies, investment brokers.
    - **Context & Vulnerabilities**:
        - May serve as **entry/exit points** for illicit funds.
        - Required to implement AML controls (KYC, CDD, transaction monitoring), but criminals may attempt to **exploit weak compliance** or use front accounts.
        - Might be unwitting facilitators (if staff lack training) or complicit enablers (if corrupt).

2. **Professional Services & Advisors**
    - **Definition**: Specialized service providers that offer consulting, legal, accounting, auditing, fiduciary, or advisory services.
    - **Real-World Examples**: Lawyers, accountants, auditors, notaries, tax advisors, corporate/trust service providers, insurance brokers, compliance consultants, real estate or investment advisers.
    - **Context & Vulnerabilities**:
        - Often handle sensitive client information (beneficial ownership, complex transactions) and can help structure deals or corporate vehicles.
        - Can be exploited if there are **gaps in due diligence** or if professionals become **willfully blind** to suspicious activities.
        - Some are officially categorized as DNFBPs (Designated Non-Financial Businesses and Professions) in certain jurisdictions.

3. **Corporate & Commercial Entities**
    - **Definition**: Private businesses formed for commercial purposes, offering products or services outside the primary scope of financial services.
    - **Real-World Examples**: Retailers, manufacturers, trading companies, shipping/logistics providers, gaming operators (e.g., casinos), precious-metals dealers, art dealers, online marketplaces.
    - **Context & Vulnerabilities**:
        - Might handle high-volume cash transactions or international supply chains—facilitating layering or trade-based money laundering.
        - Can be **legitimately operating** while still used for _falsified invoicing_, _over/under-invoicing_, or **cross-border smuggling**.
        - Some segments (casinos, dealers in precious metals/stones) have explicit AML obligations depending on jurisdiction.

4. **Government & Public Sector**
    - **Definition**: Actors in or closely affiliated with national, regional, or local government structures, including elected officials, public agencies, or state-owned enterprises.
    - **Real-World Examples**: Legislators, ministers, mayors, regulatory bodies, central banks (in their governmental capacity), government contractors, public development funds.
    - **Context & Vulnerabilities**:
        - **Politically Exposed Persons (PEPs)** fall here, presenting higher risk of bribery or corruption.
        - A public official might misuse their position to launder illicit funds (e.g., corruption proceeds) or provide cover for others.
        - Public sector organizations can be targeted for **embezzlement** or infiltration by criminal networks seeking a veneer of official legitimacy.

5. **Customers, Clients & Private Individuals**
    - **Definition**: Individual persons acting in a personal capacity (as opposed to institutional or corporate capacity).
    - **Real-World Examples**:
        - Retail bank customers, credit card holders, e-wallet users, beneficial owners, employees, high-net-worth individuals, or informal private investors.
    - **Context & Vulnerabilities**:
        - Individuals can be **money mules**, **nominees**, or unwitting participants if criminals co-opt their accounts or identities.
        - Fraudsters may use stolen identities to open multiple personal accounts.
        - Compliance teams often rely on KYC procedures to detect anomalies or unusual activity from private individuals.

6. **Criminal & Illicit Networks**
    - **Definition**: Actors or groups explicitly engaged in predicate offenses, money laundering facilitation, or direct complicity in criminal activities.
    - **Real-World Examples**: Organized crime syndicates, professional money laundering networks, drug traffickers, terrorist cells, illicit arms dealers, sanctioned entities, document forgers.
    - **Context & Vulnerabilities**:
        - Inherently outside legal frameworks, they develop specialized laundering techniques and may infiltrate legitimate actors to disguise funds.
        - Typically flagged for enhanced due diligence or outright prohibition by financial institutions.
        - Require ongoing intelligence and law enforcement cooperation to detect and disrupt.

7. **Special Purpose Entities & Structures**
    - **Definition**: Legal vehicles or organizational forms created for specific financial, asset-management, or wealth-protection goals—often leveraged for secrecy, anonymity, or complex ownership arrangements.
    - **Real-World Examples**: Shell companies, front companies, offshore trusts, private foundations, real estate investment trusts (REITs), nonprofits or charities that can be misused.
    - **Context & Vulnerabilities**:
        - May be legitimate tools for asset protection or tax planning but also widely used in layering or obfuscating beneficial ownership.
        - Minimal disclosure requirements in certain jurisdictions make them prime targets for criminals.
        - Institutions often have difficulty verifying the **ultimate beneficial owner** behind such structures.

**Choosing a Single Main Group**

A single organization can appear to fit multiple groups (e.g., a consulting firm offering regulated financial advice). AMLTRIX, however, enforces one best-fit classification—**whatever domain is most relevant to the role** the actor typically plays in money laundering. Additional details or cross-functional notes can be stored separately (e.g., via sub-tags or relationships).

* * *

### 2.2 Actor Type

Once an actor’s **Main Group** is identified, we assign its **Actor Type**—essentially signaling whether it generally operates **lawfully**, is **inherently illicit**, or stands at a higher risk of **unwitting exploitation**:

1. **Legitimate**
    - **Definition**: Actors presumed compliant with AML/CFT obligations, abiding by legal requirements, and not knowingly facilitating money laundering.
    - **Indicators**: Licensing or registration, adherence to relevant regulations, normal corporate governance, transparent beneficial ownership (if relevant).
    - **Examples**: A well-known bank, a reputable accounting firm, an established retailer operating within legal norms.

2. **Illicit / Criminal**
    - **Definition**: Actors primarily engaged in, or sanctioned for, criminal pursuits; or who exist to facilitate illicit activity.
    - **Indicators**: Known involvement in predicate crimes (e.g., drug trafficking, document forgery), blacklisted or sanctioned status, repeated involvement in suspicious transactions.
    - **Examples**: Organized crime networks, fraudulent shell entities set up explicitly for laundering, sanctioned individuals or cartels.

3. **Potentially Exploited**
    - **Definition**: Actors that might be used (knowingly or not) by criminals to launder funds, yet are not inherently criminal.
    - **Indicators**: High-volume cash activity, complex or opaque ownership, location in weak regulatory environments, minimal oversight or AML controls.
    - **Examples**: Cash-intensive businesses (restaurants, casinos in some jurisdictions), offshore entities with limited transparency, nonprofits lacking strong financial governance.

**Why This Matters**

- **Legitimate** vs. **Illicit** helps separate routine, fully compliant activity from clear wrongdoing.  
- **Potentially Exploited** captures that gray zone where actual complicity isn’t confirmed, but the structural features or lack of oversight expose the entity to higher ML risk.

* * *

## 3. Methodological Rationale

### 3.1 Bridging High-Level & Operational Perspectives

**Legal vs. Operational Definitions**

Regulatory frameworks (FATF, EU Directives, etc.) provide categories like “DNFBPs” or “Financial Institutions,” while frontline AML practitioners deal with more granular terms like “shell companies,” “import/export firms,” and “professional enablers.” AMLTRIX merges these two perspectives, offering a single reference that is both **regulator-friendly** and **operationally relevant**.

**Single Assignment, Multiple Details**

By allocating each actor to one Main Group, AMLTRIX simplifies queries (e.g., “Show all Corporate & Commercial Entities flagged as Potentially Exploited”). More specific details (e.g., “licensed for trust services,” “has personal bank account,” “shares board members with X”) can be stored in an institution’s own extended data, without cluttering the core actor classification.

**Conceptual Actors vs. Real Entities**

Labels like “Shell or Front Company” or “Professional Money Launderer” are **archetypal**. Determining if a real-world business or individual actually fits that role depends on investigative findings. AMLTRIX only defines the **typological category**—the real-life assignment is performed by analysts or investigators.

### 3.2 Linking Actors to Techniques

AMLTRIX focuses on **who** enables or performs **which** laundering techniques. For instance, a “Shell or Front Company” (in “Special Purpose Entities & Structures,” often “Potentially Exploited”) can map to the technique “Use of shell companies.” This helps compliance teams or investigators see how particular types of actors typically facilitate illicit flows.

* * *

## 4. Common Pitfalls & Edge Cases

### 4.1 Staff vs. Institution

- **Institution**: e.g., “Bank ABC” → Main Group: “Financial Institutions & Services,” typically “Legitimate”  
- **Individual Staff**: e.g., “John Doe, bank teller” → Main Group: “Customers, Clients & Private Individuals,” typically “Legitimate” (unless proven complicit)

### 4.2 Outright Criminal Roles

Certain actors are inherently illicit, such as “Drug Trafficker” or “Document Forger.” They map to “Criminal & Illicit Networks” with Actor Type = “Illicit/Criminal.”

### 4.3 Special Purpose Vehicles

“Shell or Front Company,” “Offshore Entity,” “Private Interest Foundation,” or “Nonprofit with lax controls” often go to “Special Purpose Entities & Structures” as “Potentially Exploited.” They are not necessarily criminal by default; they are simply known to pose higher ML risk.

### 4.4 PEPs & Public Officials

“Politically Exposed Persons (PEPs)” usually go in “Government & Public Sector,” Actor Type = “Legitimate,” although corruption cases could shift them to “Illicit/Criminal.”

### 4.5 Sanctioned vs. Criminal

AMLTRIX generally classifies “Sanctioned Entity or Individual” as “Criminal & Illicit Networks” because dealing with a sanctioned party is effectively an illicit activity from a compliance standpoint.

* * *

## 5. One Real Entity, Multiple Potential Labels

### 5.1 Role-Centric vs. Entity-Centric

A single real-world individual or company can hold **several** AMLTRIX roles:

- A **lawyer** who is also a **nominee** for beneficial ownership in a client’s company and possibly even a **money mule** if she knowingly transfers illicit funds.

AMLTRIX is **role-centric**: “Lawyer,” “Nominee,” “Money Mule” each get one Main Group + one Actor Type. A compliance system, meanwhile, typically takes an **entity-centric** approach—“Alice Smith” might appear in all three roles simultaneously, depending on her behavior or level of complicity.

### 5.2 Practical Implications

- The same real-world person or organization can match multiple AMLTRIX archetypes as new evidence arises.  
- Each role archetype focuses on a distinct set of vulnerabilities or methods criminals might exploit.

* * *

## 6. Threat Modeling vs. Case Investigations

### 6.1 Static vs. Dynamic Classification

- **Threat Modeling**: AMLTRIX sets broad definitions for “Potentially Exploited,” “Illicit,” or “Legitimate” as typical risk profiles, not final judgments.  
- **Case Investigations**: Real-world evidence may shift an entity’s classification from “Legitimate” to “Illicit/Criminal,” or confirm it as “Potentially Exploited,” in time-stamped investigative systems. AMLTRIX remains a static reference of possible roles.

### 6.2 No Actor-to-Actor Edges in AMLTRIX

AMLTRIX does **not** model direct relationships between actors (e.g., “Tax Advisor is connected to Document Forger”). Instead, it focuses on mapping each role to the techniques they might enable or perform. Actual investigative details about co-conspirators or “social graphs” belong in separate intelligence platforms.

* * *

## 7. Maintaining the Taxonomy

### 7.1 Governance

A **taxonomy governance committee** could help maintain consistency, deciding borderline assignments (e.g., “Is a ‘Mobile Money Agent’ a Financial Institution, or a Private Individual?”). Jurisdictions may refine categories—like splitting “Professional Services” further—while preserving AMLTRIX’s core structure.

### 7.2 Intent vs. Formal Filing

“Money Mule,” “Shell Company,” or “Professional Money Launderer” reflect **functional roles** or **intent**. None are official registration statuses; they are risk-based archetypes drawn from recognized laundering typologies.

* * *

## 8. Why This Matters for AML/CFT

- **Clarity in Threat Modeling**  
  By defining who does what, AMLTRIX illuminates how each role might facilitate different money laundering techniques.

- **Enhanced Detection & Prevention**  
  Monitoring systems can incorporate the “Actor Type” dimension: “Illicit/Criminal” triggers immediate alerts, “Potentially Exploited” prompts enhanced due diligence.

- **Interoperability**  
  Consistent labeling fosters easier collaboration between financial institutions, regulators, and third-party solution providers—everyone refers to the same actor definitions.

- **Flexibility & Precision**  
  As new corporate structures, fintech products, or advanced laundering methods emerge, AMLTRIX’s high-level approach can accommodate updates without fragmenting existing data.

* * *

## 9. Concluding Observations & Recommendations

Implementing the AMLTRIX **Actors Taxonomy** supports a more unified approach to AML/CFT threat modeling:

- **Keep It Simple**  
  Seven main groups cover most scenarios. Subdivide only if absolutely needed for local conditions.

- **Assign “Legitimate” by Default**  
  Unless there is strong evidence of criminality or exploitation, treat an actor as “Legitimate.”

- **Document Borderline Cases**  
  If “Mobile Money Agent” is classified under “Customers, Clients & Private Individuals,” note why. Consistency is crucial.

- **Use AMLTRIX as a Reference, Not a Case Tool**  
  AMLTRIX’s classifications are conceptual. Actual status changes (e.g., “an entity newly proven illicit”) are recorded in investigative or compliance systems.

- **Governance and Versioning**  
  Maintain an internal process to update the taxonomy or add new actor roles, with time-stamped records to track these decisions.

By integrating this taxonomy, institutions and regulators can more systematically capture the **who** behind illicit behaviors, complementing data on **how** laundering unfolds (techniques) and supporting robust, scalable AML/CFT frameworks.

# AMLTRIX Versioning

*Effective May 2025 — supersedes all previous notes*

AMLTRIX is an open‑source adversarial‑knowledge framework that remains in **Beta**. Community feedback and ongoing research drive frequent updates. This document governs **all** aspects of AMLTRIX versioning; no other standing documents on versioning are required.

---

### 1. Beta status and release stream

* **Framework releases** follow the pattern **`1.0‑beta.#`** (e.g., `1.0‑beta.7`).
* Each increment—no matter how large or small—is treated as a **minor** update within the Beta stream; **we do not issue separate patch / hot‑fix tags while in Beta**.
* When AMLTRIX exits Beta, semantic versioning will switch to the standard **major.minor** convention (§ 2).

---

### 2. Version‑number formats

| Level                                                                                                                                    | Format                                      | Triggers                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Framework (Beta)**                                                                                                                     | `1.0‑beta.#`                               | Any public release that aggregates object‑level or structural updates.                          |
| **Framework (Post‑Beta)**                                                                                                                | `x.y`                                       | `x` (major) for architectural or conceptual shifts; `y` (minor) for incremental improvements.   |
| **Individual objects** (techniques, mitigations, value instruments, actors, products and services, data sources and their relationships) | Default **`1.0`**                           | Increments **only** if a change materially affects interpretation or operational use (see § 3). |
| **Matrix & Tactics**                                                                                                                     | Single shared version (e.g., `Matrix v1.1`) | Any addition, merge, or re‑definition of a tactic.                                              |

> **Retention policy:** Older minor Beta releases remain accessible on the version‑history page for a limited period (typically ≥ 6 months) to aid validation and roll‑backs.

---

### 3. Object‑versioning policy (May 2025)

All objects **default to** **`1.0`** and **do not increment** unless at least one of the following occurs:

* **Tactic reassignment** (techniques or sub‑techniques).
* **Reclassification** that changes the object’s conceptual role.
* **Substantive definition rewrite** that alters how the object is understood or applied.

Changes that **do not trigger** a version bump include spelling/grammar fixes, added references, clarifying notes, formatting tweaks, new or reordered relationships.

> **Deprecations:** An object may be flagged **Deprecated** in any Beta release when consensus indicates it will be removed or replaced. Deprecated objects may be removed in the very next release; a separate data extract—maintained on Github—lists each deprecated object, its replacement (if any), and the date of deprecation.

> **Backward‑compatibility expectations:** We strive to keep **object IDs** stable throughout Beta. **Field names** may be added, rearranged, or—if unavoidable—removed. Any such change is highlighted in the release notes.

---

### 4. Change management & transparency

* **Official version history:** [https://framework.amltrix.com/version-history](https://framework.amltrix.com/version-history) provides the authoritative log of all framework releases and object‑level changes.
* **GitHub commits:** every edit—large or small—is committed individually for full auditability.
* **Changelogs:** each framework release includes a concise summary of material updates and any deprecations.

---

### 5. Institutional best practices

1. **Track the latest Beta release.** Use the highest `1.0‑beta.#` tag until AMLTRIX exits Beta.
2. **Note object versions when present.** If no version is displayed, assume **`1.0`**.
3. **Review changelogs selectively.** Focus on entries that flag object‑version increments, field‑name adjustments, or deprecations that affect your tooling.
4. **Audit via GitHub or the version‑history page** when needed; these are the definitive trails for every modification.

---

### 6. Exit from Beta

Leaving Beta will be **a consensus decision** by the maintainer team and community contributors, informed by overall stability and coverage. Once announced, the framework will advance to **`1.0`** and adopt the post‑Beta semantic scheme in § 2.

---

### 7. Summary

* Releases during Beta are sequential `1.0‑beta.#` tags—no patch tags.
* Objects start at `1.0`; versions change only on material meaning shifts.
* Field names can still evolve in Beta; watch changelogs.
* The version‑history page and GitHub commits are your single sources of truth.

> **In short:** Follow the latest `1.0.beta.#`, assume objects are `1.0` unless flagged otherwise, and consult the version‑history page for meaningful shifts.