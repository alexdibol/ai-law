**Practical Legal Applications of Generative AI (AI LAW)**  
Alejandro Reynoso — Chief Scientist, DEFI CAPITAL RESEARCH; External Lecturer, Judge Business School Cambridge

**What this repository contains**  
This repository supports the book **Practical Legal Applications of Generative AI**, an educational, governance-first guide for **U.S. legal practice**. It is designed to help practicing lawyers build a clear mental model of what generative AI can do today, where it fails, and how to use it safely with professional responsibility constraints.

Contents:
- **Book (PDF)**: published as a versioned GitHub Release (see the Releases section of this repository).  
- **Companion notebooks (Colab-ready)**: `notebooks/chapter_1.ipynb`, `notebooks/chapter_2.ipynb`, `notebooks/chapter_3.ipynb`, `notebooks/chapter_4.ipynb`, `notebooks/chapter_5.ipynb`

**Who this is for**  
- U.S.-based practicing lawyers and legal professionals  
- Readers with minimal AI background who want practical workflows, not hype  
- Teams building policies, templates, and controlled processes for AI-assisted legal work

**The book’s core idea: a five-level maturity ladder**  
This book treats generative AI not as “legal authority,” but as a tool whose usefulness depends on **disciplined workflows, verification, and accountability**. It presents a five-level maturity ladder that progresses from individual assistance to organization-grade operations:

- **Level 1 — Chatbots**: supervised drafting and client communication support  
- **Level 2 — Reasoners**: structured issue spotting, IRAC-style analysis, argument mapping  
- **Level 3 — Agents**: multi-step workflows under human approval gates (human-in-the-loop)  
- **Level 4 — Innovators**: reusable assets such as playbooks, clause libraries, checklists, and adversarial tests  
- **Level 5 — Organizations**: an end-to-end operating model where a team can routinely explain what was produced and how—redacted inputs, prompts/roles, risks flagged, verification tasks, and sign-off responsibility

**What makes this “governance-first” (and why that matters in law)**  
The focus is professional defensibility. Each chapter emphasizes controls that make AI outputs safer to review and harder to misuse:
- Strict separation of **generation vs verification**  
- Explicit labeling of **facts provided vs assumptions vs open questions**  
- Zero-tolerance posture toward **invented authority** (no fabricated citations, cases, statutes, or rules)  
- Governance-native artifacts that make work replayable and auditable: **run manifests, prompt logs, risk logs, verification checklists, deliverables bundles, and sign-off records**

**Recurring mini-cases used across all chapters**  
To keep learning concrete, every level is demonstrated using the same four mini-cases:
- **Criminal**  
- **Regulatory / Administrative**  
- **International**  
- **Teaching / Academia**  

This structure makes the progression visible: as capability increases, risk increases, and controls must scale accordingly. Each chapter ends with a **minimum standard checklist** that can be adopted immediately in real practice settings.

**How to use the notebooks**  
Each notebook is designed to be run in Google Colab and to generate audit-ready artifacts (manifests, logs, structured deliverables). Open a notebook in Colab by using the pattern below:

Colab link format:  
`https://colab.research.google.com/github/alexdibol/ai-law/blob/main/notebooks/<FILE>.ipynb`

Examples:
- `notebooks/chapter_1.ipynb`  
- `notebooks/chapter_2.ipynb`  
- `notebooks/chapter_3.ipynb`  
- `notebooks/chapter_4.ipynb`  
- `notebooks/chapter_5.ipynb`

**Important note (read carefully)**  
This repository and book are **educational materials**. They are **not legal advice**. Human lawyer review is required for any reliance-bearing use. Confidentiality, privilege, competence, supervision, candor, and client communication obligations apply at every step. Do not paste sensitive client information into external model prompts; use redaction and “minimum necessary” inputs by default.

**Repository structure**  
- `notebooks/` — Companion Colab notebooks (chapter_1 … chapter_5)  
- `docs/` — Landing page (optional, for GitHub Pages)  
- Releases — Versioned PDF book editions and optional bundles

**Suggested citation**  
Alejandro Reynoso, *Practical Legal Applications of Generative AI (AI LAW)*, companion notebooks repository, GitHub.
