<!-- Source copy of the GitHub org profile README for github.com/classHuman.
     v7.1 · 2026-09-28 · rewritten under THE GOVERNANCE RULING. Edit here, then sync to the org profile repo. Never edit the copy there directly.
     Links followed by an inline WO1 comment point at classhuman.org pages that work order 1 creates. Sync only after classhuman-org ships them. -->

# classHuman AI

**AI governance and auditing research for agents and agent harnesses.**

classHuman AI LLC (Washington, USA, est. 2026) is an AI research organization. An agent is a model inside a harness: the loop, the tools and permissions, the memory, the gates, the human sign-off and the record. Agents act through that harness, so governance lives there or it doesn't live anywhere. We study it, publish the questions before the answers with sources, and build **Ag3nt24** in the open under Apache-2.0 as the research harness we test against. Agents propose. A human signs.

Run by Lawrence Jefferson II while he completes his B.S. in Artificial Intelligence.

**Veteran Owned Business, Washington WDVA #WDVACHAI26**

**Website: [classhuman.org](https://classhuman.org)**

---

## The problem we work on

An agent acts. It calls tools, changes state and spends money. Every safeguard a team claims (step limits, permissions, approvals, logs) is either built into the harness or it's a line in a policy document. The failures we study sit in the harness: a loop with no stop condition, a tool that does more than its name says, a gate that warns and continues, a sign-off no one reads, a log that misses the reason.

So the questions are concrete. Which controls stop an unsafe tool call? Can the record explain a decision without the people who made it? When does human sign-off stop being real? Can one agent audit another and find what a person would?

**One track: inherited estates.** Between 2021 and 2026 the field changed under everyone. Companies assembled AI systems as they went: prompt chains, RAG v1, a fine-tune or two, a vector store, orchestration glue, a vendor lock-in no one chose on purpose. It works, mostly. And now no one inside can explain what it does, audit it, or sign off on replacing it.

That is a legacy system. It just happens to be two years old. Authority is the bottleneck: someone has to establish what the inherited system does, sort the data underneath it, and put a human-controlled boundary between the old estate and the new one so the replacement can be signed.

---

## How we research

**Questions first.** Each research page states its question, method and measure up front.

**Measures before results.** We define how we'll measure before we run anything, and no page states a result we haven't produced. Right now every open question reads "Open. No results yet."

**Sources cited.** Every external claim links to its primary source. Frameworks are "mapped to", and a run result is evidence for a reviewer.

**Agents propose, humans sign.** Proposals pass gates. A named person signs. A failed gate denies the action, records why, and escalates. There is no "warn and continue."

Research prose and checklists are CC BY 4.0. Code is Apache-2.0.

Open to select consulting and mentorship inquiries. **Questions, ideas, contributions:** open an issue on the repo or write via [classhuman.org/contact](https://classhuman.org/contact). No forms, no trackers.

---

## Research

**[Research: governing AI agents](https://classhuman.org/research)** <!-- WO1 --> is the hub.

* [What an agent harness is](https://classhuman.org/research/agent-harness) <!-- WO1 -->: an interactive diagram of seven layers around the model. For each layer: what it does, how it fails, what an auditor asks for.
* [The harness audit checklist v0.1](https://classhuman.org/research/harness-audit) <!-- WO1 -->: seven control families, each with yes/no/unknown questions and the evidence to request. It runs in the browser, saves locally, exports Markdown and sends nothing anywhere. It's mapped to NIST AI RMF, NIST AI 600-1, ISO/IEC 42001, the EU AI Act and the OWASP Top 10 for LLM Applications.
* [Research agenda and methods](https://classhuman.org/research/agenda) <!-- WO1 -->: four open questions, each with its method and measure.

Two tracks:

* **Auditing inherited AI estates.** The 2021 to 2026 problem above, restated as audit questions. [classhuman.org/legacy](https://classhuman.org/legacy)
* **Agent-audits-agent evaluation.** A tester agent runs competence, authority and elicitation suites, graded against cited public sources. A model judge is compared with a pattern grader on the same answers, and both against a qualified human reviewer. Method only, on the [agenda page](https://classhuman.org/research/agenda) <!-- WO1 -->.

Research by Lawrence Jefferson II, B.S. in Artificial Intelligence candidate, American Military University (expected May 2028).



## Free, for anyone

No signup, email gate or tracker.

| | |
|---|---|
| **Harness audit checklist** | The seven-family checklist above, in the browser. [classhuman.org/research/harness-audit](https://classhuman.org/research/harness-audit) <!-- WO1 --> |
| **Agent skills** | The skills we use on real work, as installable `.skill` packages and plain `SKILL.md`: `legacy-modernization-scout`, `agent-gate-review`, `hot-path`, `what-did-i-agree-to`. [classhuman.org/skills](https://classhuman.org/skills) |
| **Learn** | 247 free courses, docs, lectures and certificate tracks for software engineering, AI and ML, from freeCodeCamp, W3Schools, MDN, Python Institute, Scrimba, Coursera, AWS, IBM, Google, Microsoft, Hugging Face, OpenAI, Anthropic, Harvard, MIT and more. Filterable by topic and provider. [classhuman.org/learn](https://classhuman.org/learn) |
| **ProForma** | Turns a Gen AI initiative into a 5-year cost, benefit and risk projection: payback year, ROI, NPV, IRR, peak funding. Runs in the browser, nothing leaves the device. Apache-2.0. [github.com/MenokoOG/proforma](https://github.com/MenokoOG/proforma) |
| **Asymptote** | Static Big-O estimator for Python, built for agents. Per-function complexity with confidence, evidence, and the unknowns it can't decide. [classhuman.org/asymptote](https://classhuman.org/asymptote) |
| **FINAL AUTHORITY** | A browser game about holding the line on agent decisions. [classhuman.org/play](https://classhuman.org/play) |

---

## Proof

- **In production, built for clients before classHuman AI turned to research:** [GunKustom.com](https://gunkustom.com), a full platform rebuild (NestJS + Python vendor-feed normalization, modular-monolith gateway). [PowAlert.com](https://powalert.com), MERN real-time snowfall alerts.
- **[Willow Bend](https://willow-bend.netlify.app):** a production-shaped demo where the LLM has no write path to appointments and the assistant degrades gracefully to an offline engine.
- **TACO Loop White Paper v1.0**, published July 2026: a decision-control architecture for unknown-data environments. Core law: unknown data must increase decision discipline, not model confidence. [Read it](https://classhuman.org/whitepaper-models/TACO_Loop_Whitepaper_v1_classHuman.pdf).
- **Scrimba "Portfolio of the Week"**, May 2026.

---

## What we believe

**LAHA: Love All Humans Always.**

AI should support human dignity, creativity, learning, recovery, and decision-making. That means humans in the loop, humans as final authority, accountable agents, accessibility-first design, and systems that fail closed.

---

## Team

| | |
|---|---|
| **Lawrence Jefferson II** (Menoko OG) | Founder, CEO, CTO, Architect. 24 years U.S. Army; senior backend and AI/ML engineer. [Portfolio](https://ljefferson-menoko-site.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/lawrence-jefferson-ii-46497075) · [GitHub](https://github.com/MenokoOG) |
| **Nicale Jefferson** (LuxgirlOG) | Part-Time UX/UI Designer. Co-author of Ag3nt24, TACO Loop and HADES; doctrine author of the classHuman governance framework. [LuxgirlOG](https://luxgirlog.netlify.app/) |

**Contact:** [classhuman.org/contact](https://classhuman.org/contact) · issues and PRs on [Ag3nt24-oss](https://github.com/MenokoOG/Ag3nt24-oss)

---

*classHuman AI, driven by LAHA.*
