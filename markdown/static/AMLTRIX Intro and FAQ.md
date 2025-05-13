
### **What is AMLTRIX?**

**AMLTRIX** is an **open-source knowledge base** of adversarial tactics and techniques, derived from the collective observations of the AML/CFT community. Rather than simply listing static rules, AMLTRIX focuses on **how** adversaries operate—highlighting the variety of ways criminals interact with financial institutions throughout their **illicit financial lifecycle**.

### **Key Concepts**

**1\. Tactics**

Represent the _“why”_ behind an adversary’s actions (e.g., “Placement,” “Asset Protection”). Each tactic reflects a **stage** or **objective** in the kill-chain.

**2\. Techniques**

Show the _“how”_—the **methods** criminals use to accomplish each tactic (e.g., “Structuring deposits,” “Creating shell companies”). Techniques break down the **practical approaches** launderers adopt.

**3\. Indicators**

Identify **observable signs** that a particular technique may be in use (often called “red flags” or “risk indicators”). By spotting these patterns or anomalies, financial institutions can more effectively detect suspicious behavior.

**4\. Mitigations**

Outline the **defensive measures** designed to **disrupt** or **diminish** an adversary’s effectiveness. Each mitigation ties to one or more techniques, showing how compliance teams might thwart them.

**Supporting Contexts**

*   **Actors**: archetypal Individuals or organizations (e.g., criminals, facilitators, employees, organizations).
*   **Services & Products**: The offerings criminals might exploit (e.g., payment apps, trade finance services).
*   **Value Instruments**: The _mediums_ used to store or transfer funds (e.g., cash, crypto, securities).

By **systematically** mapping these roles and instruments, AMLTRIX helps practitioners spot vulnerabilities faster and tailor **preventative** controls.

### **How to Use AMLTRIX**

*   **Investigate Suspicious Activities**: AMLTRIX’s indicators guide analysts to identify patterns suggesting specific adversarial techniques.
*   **Enrich Threat Intelligence**: By providing a **common language** for describing and labelling illicit behaviors, AMLTRIX helps structure and compare threat data from different sources.
*   **Map Existing AML Rules**: Align your existing controls or scenario rules to known adversarial techniques, refining detection coverage.
*   **Staff Training**: Use AMLTRIX as an up-to-date reference so new AML team members quickly learn about emerging threats and typical money laundering methods.

### ❌ **How** **_Not_** **to Use AMLTRIX**

*   **Not a Checklist**: Money laundering is **evolving**. AMLTRIX isn’t meant for ticking off items as “done” or claiming “100% coverage.” Focus on your **most relevant** risks instead of pursuing every possible tactic.
*   **NOT Legal Advice:** AMLTRIX is a knowledge base — **not** a substitute for legal, regulatory, or compliance counsel. Always consult legal or regulatory experts when making critical decisions.
*   **Not Exhaustive**: Adversaries continually innovate. AMLTRIX documents observed methods, but criminals may use **unlisted** approaches.
*   **Not a Replacement for Risk-Based Thinking**: Each organization’s risk profile differs. AMLTRIX’s categories and techniques are guidelines—you must assess which ones truly matter in your context.
*   **Not One-Size-Fits-All**: Not every tactic or technique will apply to your institution. Focus on what’s relevant to your specific risk environment.
*   **Don’t Rely On It Alone**: Combine AMLTRIX with other sources: your own intelligence, regulatory guidance, and contextual expertise.

### **Why a Risk-Based Approach?**

Financial crime threats, new technologies, and criminals’ adaptability demand a **risk-based** strategy—no single set of controls is universal. AMLTRIX is **scalable and modular**:

1. **Identify your organization’s highest-impact threats.**
2. **Select relevant AMLTRIX tactics and techniques** to focus on, ignoring those that don’t apply.
3. **Scale** your monitoring and KYC measures proportionally, balancing legitimate business needs against potential vulnerabilities.

### **Community & Next Steps**

AMLTRIX grows through **community feedback** and collaborative insights. Join the discussion—share techniques you’ve seen in the wild, offer new indicators, or propose clarifications:

*   **Discuss**: Engage with AMLTRIX Community on our Discord server, [apply here](https://discord.gg/z4syvQX7).
*   **Stay Informed**: Find the latest updates on AMLTRIX framework website.
*   **Contribute**: Suggest new or revised techniques and share your experiences.
*   **Get More Details**: For further reading on our methodology, see our [Methodology page](https://framework.amltrix.com/design-methodology)

  

By combining industry knowledge with a structured adversarial model, AMLTRIX aims to **empower** AML practitioners with a richer understanding of the **how** and **why** behind financial crime—leading to stronger, more adaptive defenses.

---

# FAQ

## **General**

### **What is AMLTRIX?**
**AMLTRIX** is an open, community-driven knowledge graph and taxonomy for adversarial behaviors in financial crimes. It breaks down money laundering and related illicit activities into clear “tactics,” “techniques,” and “indicators,” providing a unified reference that helps financial institutions, regulators, and compliance professionals detect, mitigate, and understand criminal tactics more efficiently.

### **Why did AMLYZE develop AMLTRIX?**
AMLYZE—an advanced RegTech provider—noticed that financial institutions often struggled to operationalize high-level reports from FATF, MONEYVAL, or other authorities. Each institution ended up reinventing detection logic, lacking shared standards for describing adversarial methods. **AMLTRIX** addresses this gap by offering a structured, open framework that transforms complex regulatory guidance into practical detection and prevention strategies.

### **Who can benefit from AMLTRIX?**
Anyone in the financial crime ecosystem—banks, fintechs, law enforcement, regulators, academics—can leverage AMLTRIX to unify AML language, reduce duplicative efforts, and share knowledge on adversarial tactics and potential risk indicators. Whether you are a data scientist building new AI detection models or a compliance officer investigating suspicious activities, AMLTRIX can help guide your processes.

### **How often is AMLTRIX updated?**
AMLYZE aims to keep AMLTRIX **continuously evolving**. Large content refreshes may happen a few times a year, supplemented by smaller community-driven updates whenever contributors propose new or refined tactics, techniques, or indicators. Check our public channels for announcements, or visit the Community Portal for updates.

---

## **Using AMLTRIX**

### **How can I use AMLTRIX in my organization?**
AMLTRIX supports multiple use cases:
- **Threat Intelligence**: Identifying known laundering methods and tracking emerging ones.  
- **Detection & Investigation**: Linking real-world data (e.g., transaction logs) to red flags (“indicators”) within AMLTRIX to flag suspicious activity.  
- **AI & Analytics**: Providing a consistent reference to train machine-learning models or advanced analytics.  
- **Training & Onboarding**: Equipping AML staff with standardized definitions of tactics and techniques.

For a step-by-step guide on adopting AMLTRIX, see our **[Get Started](http://framework.amltrix.com/get-started)** page.

### **What are “tactics” in AMLTRIX?**
**Tactics** represent the **“why”** of an adversarial action—criminals’ high-level objectives, such as “Placement” or “Concealment Mechanisms.” They serve as broad categories that group multiple **techniques** used to achieve each specific goal.

### **What are “techniques” and “sub-techniques”?**
- A **Technique** defines **“how”** an adversary achieves a particular tactic, e.g., “Structuring deposits” for layering or “Using shell entities” for concealment.  
- **Sub-techniques** are more specialized behaviors at a **lower level of abstraction**. For instance, an offshore shell vs. a domestic shelf company might be defined as separate sub-techniques under “Shell Entities.”

### **What are “indicators” in AMLTRIX?**
**Indicators** (risk indicators or red flags) are **observable signs** suggesting a specific technique is in use. They help obliged entities spot suspicious patterns, enabling more targeted investigations of high-risk accounts, transactions, or relationships.

### **What are “mitigations”?**
**Mitigations** are **defensive strategies** or controls designed to disrupt or reduce the effectiveness of adversarial techniques. Examples might include enhanced due diligence checks, transaction monitoring rules, or specialized employee training.

### **Where does AMLTRIX get its information from?**
AMLTRIX primarily relies on **publicly available** threat intelligence and official reports. We synthesize common patterns or newly observed illicit tactics, combining them into an accessible knowledge graph. For details, see **[The Design and Philosophy of AMLTRIX](https://framework.amltrix.com/design-methodology)**.

---

## **Contributing**

### **How can I contribute content to AMLTRIX?**
Check out our **[Contribute](https://framework.amltrix.com/contribution)** page, which guides you in submitting new or revised tactics, techniques, indicators, or references. Once submitted, AMLTRIX moderators review, refine if necessary, and integrate your contribution. If approved, you’ll be credited unless you request anonymity.

### **I noticed a missing threat—what should I do?**
We welcome community input. If you see a money laundering behavior not covered by AMLTRIX, simply reach out or propose an addition through the **[Contribute](https://framework.amltrix.com/contribution)** page. Our goal is for AMLTRIX to remain as current and comprehensive as possible.

### **Can I remain anonymous as a contributor?**
Yes. If you’d rather not be publicly credited for your content, just let us know in your submission. Otherwise, we typically acknowledge contributors by name or nickname.

---

## **4. Licensing & Legal**

### **Which license applies to AMLTRIX content?**
All **Licensed Content** published by AMLYZE in AMLTRIX is covered under a license **based on Creative Commons principles**. It allows worldwide, royalty-free, non-exclusive rights to reproduce, distribute, and adapt AMLTRIX content, even commercially, provided you **give appropriate attribution**.

### **Do I need to keep my Derivative Works open-licensed too?**
No. The license allows you to reuse, modify, and redistribute AMLTRIX content (including derivative works) without requiring you to open-license your derivative content. However, you must provide appropriate attribution to AMLTRIX and may not falsely imply endorsement.

You are encouraged—but not legally obligated—to make your derivative works public or open. The AMLTRIX license does not include a "ShareAlike" or "copyleft" clause (such as those found in some Creative Commons licenses like CC BY-SA).

### **Are there warranties for AMLTRIX content?**
No. AMLTRIX is provided **“as is,” without warranties** of any kind (see the Disclaimer of Warranties section). The Licensor is not liable for direct or indirect damages arising from the use or misuse of AMLTRIX.

### **How do I ensure proper attribution?**
- **Digital**: Visible mention + hyperlink to AMLTRIX  
- **Print**: Footnote or bibliography entry referencing AMLTRIX  
- **Software**: Note in documentation, code comments, or “About” menu  
- **Multimedia**: Credit in captions, descriptions, or closing credits  
The key is to avoid implying AMLTRIX endorses your project or product without separate written permission.

---

## **Branding & Trademark**

### **How should I reference “AMLTRIX” or use its logo?**
- **Trademark Note**: AMLTRIX® is a registered trademark of AMLYZE. Use “AMLTRIX®” in your initial reference, and “AMLTRIX” in subsequent mentions.  
- **No Alterations**: Don’t modify, abbreviate, or hyphenate the name. Avoid using “AMLTRIX” in your product/service titles or company name without explicit permission.
- **Endorsement**: You may not imply AMLTRIX endorses your product or service unless you have explicit written consent from AMLYZE.

---

## **Staying Up to Date**

### **How do I follow AMLTRIX updates?**
- **LinkedIn**: Follow [AMLTRIX](https://www.linkedin.com/company/amltrix/) for announcements and news.  
- **Discord Community**: Join for real-time discussions: https://discord.gg/z4syvQX7
- **Website Updates**: Check the homepage for the latest version or read the “[Changelog](https://framework.amltrix.com/version-history)” if posted.
- **GitHub Data Releases**: Follow our public GitHub repository for new data-set releases.

### **Who should I contact for support or additional questions?**
Email us at **info@amltrix.com**. We appreciate all feedback—whether it’s bug reports, missing content, or suggestions for new features. Use **contribute@amltrix.com** if you wish to share your contributions.

---

**Still Have Questions?**  
Feel free to reach out to us at info@amltrix.com or join our [Discord community](https://discord.gg/z4syvQX7) for live discussions. We look forward to evolving AMLTRIX with the help of the entire AML/CFT community.

# About Us

**AMLTRIX** was conceived and designed by the [**AMLYZE**](https://amlyze.com) team—a collective of AML technology specialists dedicated to fighting financial crime through innovative solutions. Headquartered in Vilnius, Lithuania, AMLYZE provides advanced AML compliance and financial crime prevention technologies, combining deep industry expertise with cutting-edge data analytics.

While developing its own AML solutions, the AMLYZE team observed how many institutions struggled with siloed knowledge about money laundering threats. High-level regulatory typologies often failed to translate into effective detection logic or operational processes, causing repeated reinventions of similar rules and procedures. It became clear that the industry needed a more structured, community-driven framework—one that captures adversarial tactics and techniques in a format that’s machine-readable for automated monitoring systems and also human-readable for investigators.

Drawing inspiration from the successful MITRE ATT&CK® model in cybersecurity, **AMLTRIX** emerged as an **open-source, community-driven adversarial knowledge framework**. By documenting common laundering behaviors and mapping them to potential risk controls, AMLTRIX helps institutions rapidly adapt to emerging threats, promotes collaboration, and lowers barriers to advanced financial crime detection.

---

## Team Contributions

Led by **Evaldas Kazlauskas**, Product Owner at AMLYZE, the following individuals contributed their expertise and insights to shape AMLTRIX:

- **Sandra Morkūnienė**, Product Analyst at AMLYZE  
- **Eglė Kontautaitė**, AML/CFT Expert at AMLYZE  
- **Tomas Stanulionis**, AML/CFT Expert at AMLYZE  
- **Gabrielius Erikas Bilkštys**, CEO at AMLYZE  
- **Alexandre Pinot**, Head of Innovation & Strategy at AMLYZE  
- **Paulius Čiulada**, Chief Marketing & Communications Officer at AMLYZE  
- **Tadas Češkevičius**, Anti-Money Laundering Technology Consultant at AMLYZE  
- **Mindaugas Petrauskas**, Head of Financial Crime Prevention at AMLYZE  
- **Aleksandr Lazutkin**, Chief Product Owner at AMLYZE  
- **Jekaterina Govina**, Head of Partnerships & Regulatory Affairs at AMLYZE
- **Gediminas Radikas**, Chief Technology Officer at AMLYZE

Their combined efforts ensured AMLTRIX remained robust, adaptable, and aligned with the evolving demands of the AML community.

---

## Collaboration & Community Involvement

Collaboration is central to AMLTRIX. As a living repository of adversarial behaviors, it evolves through community feedback, shared research, and transparent discussions. Financial institutions, regulatory professionals, data scientists, and other subject matter experts are invited to contribute new content, propose use cases, and offer perspectives that enhance the framework.

For those interested in exploring collaboration or contributing to the project, please contact us at [**info@amltrix.com**](mailto:info@amltrix.com).

---

## Special Thanks

Our gratitude goes to the [**Innovation Sandbox Programme**](https://www.centralbank.ie/regulation/innovation-hub/innovation-sandbox-programme) at the **Central Bank of Ireland**, whose forward-thinking initiatives have provided valuable opportunities for pioneering efforts such as AMLTRIX.

# Contributions and Community

AMLTRIX is continually evolving through the active engagement and insights of the AML/CFT community. We welcome contributions that refine, extend, or enhance the information in the framework, ensuring it remains accurate, relevant, and comprehensive.

If you have knowledge about additional adversarial techniques, variations on existing techniques, case studies, illustrative examples, or other relevant insights, we would greatly appreciate your input.

---

## Ways You Can Contribute

### 1. **New Techniques and Sub-Techniques**
If you've identified behaviors or methods used by adversaries that aren't yet captured in AMLTRIX, please share:
- A clear description of the behavior.
- Contextual examples of how the technique has been observed in practice.
- Supporting references or documentation, if available.

### 2. **Variations or Updates to Existing Techniques**
Help us refine existing content by providing:
- Clarifications, corrections, or additional details for current techniques.
- Real-world examples demonstrating technique variations.
- Updated insights into detection or mitigation strategies.

### 3. **Financial Crime Intelligence**
We are interested in compiling practical, procedural examples of techniques that can help illustrate how they occur in real-world scenarios. Contributions could include:
- Documented case studies showing technique usage.
- Data-driven examples or aggregate data illustrating financial crime trends.
- Insights from investigative reports, regulatory alerts, or institutional observations.

### 4. **Methodology and Taxonomy Suggestions**
We actively welcome feedback on the AMLTRIX methodology, taxonomy, and design choices. Contributions could include:
- Constructive critiques or validations of our methodology.
- Suggestions for improvements or modifications to the taxonomy.
- General insights or perspectives on AML/CFT threat modeling.

### 5. **Website and Content Corrections**
Found an error or typo on the AMLTRIX website? Let us know:
- Provide the specific URL of the page.
- Briefly describe the error (typo, formatting issue, broken link, etc.).

---

## How to Submit Your Contribution

You can easily submit your contributions by:
- Filling out our dedicated [Contribution Form](https://framework.amltrix.com/contribution/create), or
- Emailing your contribution directly to [contributions@amltrix.com](mailto:contributions@amltrix.com).

For real-time discussions, feedback, or preliminary discussions about your contributions, join our community Discord server: [AMLTRIX Discord](https://discord.gg/z4syvQX7).

Please note that due to the volume of submissions, it might take some time for us to respond. We encourage you to familiarize yourself with our [Methodology page](https://framework.amltrix.com/methodology) to better understand our framework's principles and approach.

---

## Contributors

We greatly appreciate the valuable insights from our community members. Contributors who provide meaningful additions, enhancements, or intelligence that enrich AMLTRIX may be acknowledged publicly, with your consent.

If you prefer your contribution to remain anonymous, please indicate this clearly when submitting your material.

Thank you for helping strengthen AMLTRIX and the global fight against financial crime!