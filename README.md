# AMLTRIX® Data Exports

## What is AMLTRIX?

**AMLTRIX®** is an open, community-driven knowledge graph and taxonomy for adversarial behaviors in financial crimes. It systematically breaks down money laundering and related illicit activities into clear **tactics**, **techniques**, and **indicators**, providing a unified reference that helps financial institutions, regulators, and compliance professionals detect, mitigate, and understand criminal tactics more efficiently.

Developed by [AMLYZE](https://amlyze.com)—a RegTech provider—AMLTRIX addresses the lack of standardized definitions in the AML/CFT space, transforming complex regulatory guidance into practical detection and prevention strategies.

Learn more: [AMLTRIX Design Methodology](https://framework.amltrix.com/design-methodology)

---

## Repository Contents

This repository provides AMLTRIX data exports structured by **release version** and **file format**:

```
amltrix-data/
├─ stix/
│  ├─ amltrix-ml-latest.json
│  ├─ amltrix-ml-1.0-beta.1.json
│  └─ ...
├─ csv/
│  ├─ amltrix-ml-actors-latest.csv
│  ├─ amltrix-ml-techniques-latest.csv
│  ├─ amltrix-ml-tactics-latest.csv
│  └─ ...
├─ xlsx/
│  ├─ amltrix-ml-latest.xlsx
│  ├─ amltrix-ml-1.0-beta.1.xlsx
│  └─ ...
├─ navigator/
│  ├─ amltrix-ml-latest-layer.json
│  ├─ amltrix-ml-1.0-beta.1-layer.json
│  └─ ...
├─ LICENSE.txt
├─ NOTICE.txt
└─ README.md
```

### Formats Explained

- **STIX 2.1 JSON** (`stix/`): Ideal for threat intelligence platforms and programmatic ingestion.
- **CSV Files** (`csv/`): For quick reference or integration into data analysis workflows.
- **Excel Workbooks** (`xlsx/`): User-friendly format containing multiple sheets and an overview Matrix tab.
- **Navigator Layers** (`navigator/`): Directly usable in [AMLTRIX Navigator](https://navigator.amltrix.com) for interactive visualization and planning.

---

## Versioning

AMLTRIX is currently **in Beta**, undergoing frequent updates. Versions follow this format: `v1.0-beta.#`.

- **Latest files** always marked as `-latest`.
- Historical versions retained for consistent referencing and comparison.

View full version history and changelogs: [AMLTRIX Version History](https://framework.amltrix.com/version-history)

---

## How to Use AMLTRIX Data

AMLTRIX data includes:

- **Tactics**: High-level adversarial objectives (e.g., Placement, Layering).
- **Techniques & Sub-techniques**: Methods used to achieve tactics.
- **Indicators**: Observable red flags or risk signs.
- **Mitigations**: Defensive strategies and controls.
- **Actors**: Adversarial personas.
- **Relationships**: Links between AMLTRIX objects (e.g., Tactics → Techniques).

Use these structured files to support threat intelligence, detection & investigation, AI model training, or AML/CFT training activities.

---

## Licensing and Terms

- AMLTRIX content is open-licensed, based on Creative Commons principles. You are free to use, adapt, and distribute AMLTRIX data, including commercially, provided you **clearly attribute AMLTRIX**.
- Derivative works must retain the open license terms.
- AMLTRIX content is provided **"as is," without warranties** of any kind.

**Attribution guidelines:**
- **Digital:** Mention AMLTRIX with a visible hyperlink.
- **Print:** Include AMLTRIX in footnotes or bibliography.
- **Software:** Reference AMLTRIX clearly in documentation or about sections.

Full license details: [AMLTRIX License](https://framework.amltrix.com/license)  
Complete terms of use: [AMLTRIX Terms of Use](https://framework.amltrix.com/termsofuse)

---

## Contributing and Feedback

Your contributions and suggestions are welcome!

- Visit the [Contribute Page](https://framework.amltrix.com/contribution) to propose new content or improvements.
- Join community discussions and updates on our [Discord server](https://discord.gg/z4syvQX7).
- For general questions or feedback, contact us at [info@amltrix.com](mailto:info@amltrix.com).

---

**Thank you for helping AMLTRIX enhance global AML/CFT defenses!**