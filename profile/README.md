# classHuman AI

**Modern agents on legacy systems. No rip-and-replace.**

classHuman AI LLC is a Generative AI Software Engineering, Development & Research company (Washington, USA, est. 2026). We specialize in **legacy modernization** — putting modern AI agents and workflows onto stacks you cannot switch off, one slice at a time, with the lights on.

We also build custom agents and agentic systems, and the control layer that decides what an agent is allowed to do before it does it.

Humans always keep final authority.

**WDVA Certified Veteran Owned Business · #WDVACHAI26**

**Website: [classhuman.org](https://classhuman.org)**

---

## What we do

**The hard part of legacy work is the seam.** Not the translation — compilers, transpilers and now LLMs can all produce plausible target-language code. The hard part is the boundary between the system you cannot break and the modern stack you want to reach it from.

That is where we build. **Protocol droids** — adapter agents fluent in the legacy system's formats and protocols on one side, and a modern agentic stack on the other. They let new agents read, write and act on legacy systems safely, behind a human-approved boundary.

The qualifying question is not *"do you run COBOL?"* It is **"do you have a system you're afraid to change?"**

| Engagement | What you get |
|---|---|
| **Legacy modernization** | Modern agents on a stack you cannot switch off. The migration pattern is chosen from your system's evidence — never prescribed. Reversible, traceable, evidenced at every step. |
| **Agents & agentic systems** | Custom agents and multi-agent systems on modern platforms and open-source frameworks. You keep your tooling, your cloud, and your exit options. |
| **The control layer** | The part most agent projects skip: registration, validation, revocation, escalation, human-in-the-loop. Fail-closed by construction — every uncertainty resolves to deny. |
| **Enabling your team** | If you would rather own the capability than rent it, we equip your engineers to keep going without us. You own the system, not a retainer. |

[Start an engagement →](https://classhuman.org/services)

---

## We read the system first, then pick the pattern

There is no single right way to modernize a legacy system, and any shop that tells you otherwise is selling you their habit.

Some systems want to be grown around. Some want a seam and a swap. Some want to be run in parallel until the evidence is in. A few are genuinely better off rewritten — and we will say so, even though it is the smaller engagement.

The working set, roughly least to most invasive, and most real engagements use several at once:

`Lift and shift` · `Replatform` · `Strangler fig` · `Branch by abstraction` · `Parallel run` · `Shadow traffic` · `Canary & phased rollout` · `Event interception` · `Anti-corruption layer` · `Encapsulation / facade` · `A straight rewrite, when that is honestly cheapest` · `Protocol-droid interfaces`

**Where it lands is yours to pick.** Cloud, on-premise, or entirely on hardware you own. Modernizing does not have to mean moving your data into someone else's data center.

[How we do it →](https://classhuman.org/legacy)

---

## The control layer — five gates

An agent that can only read is a demo. The moment it can write, spend, or send, it needs five answers:

| Gate | The question it answers |
|---|---|
| **Registration** | Is this agent known? |
| **Validation** | Is this action legitimate, checked before it happens? |
| **Revocation** | Can authority be withdrawn, right now? |
| **Escalation** | What happens when confidence is low? |
| **Human-in-the-loop** | Is final authority actually held by a person? |

Fail-closed throughout: a failed gate denies the action, records the refusal, and escalates to a named human. There is no "warn and continue" — a warning nobody blocks on is a log line.

---

## How we build

Our primary framework for custom and production agent builds is **[Strands Agents](https://strandsagents.com)** — the open-source, model-driven agent SDK. It keeps builds portable across model providers, observable in production, and governable by the five gates. Work runs spec-first with **[GitHub Spec Kit](https://github.com/github/spec-kit)**.

We work with all foundation and frontier models on the platforms your team already runs:

| Vendor | Tooling |
|---|---|
| **AWS** | Amazon Bedrock · SageMaker · Kiro |
| **Google** | Google AI Studio |
| **IBM** | watsonx |
| **Microsoft** | Microsoft Agent Framework |

Platform-agnostic by design — your stack, your cloud, your exit options.

---

## Free agent skills

The skills we use on real engagements, published for anyone to install and run — no signup, no email gate, no tracker.

| Skill | What it does |
|---|---|
| **legacy-modernization-scout** | Maps a legacy system before anyone commits to a rewrite: inventories surfaces, finds facade seams, designs adapters, ranks slices by value against reversibility. Every finding carries a confidence mark; the report leads with an Unknowns register. |
| **agent-gate-review** | Reviews an agent against the five gates. Each rated from the code path, not the design doc, and every gap gets a concrete failure scenario. |

Available as installable `.skill` packages and as plain `SKILL.md`: **[classhuman.org/skills](https://classhuman.org/skills)**

Also free: **[FINAL AUTHORITY](https://classhuman.org/play)**, a browser game about holding the line on agent decisions, and **[Asymptote](https://classhuman.org/asymptote)**, a static Big-O estimator for Python built for agents.

---

## Ag3nt24 — our product

**An agentic framework built for legacy modernization.** Twenty-four agent personas governed by a deterministic integrity kernel. You instantiate the ones a mission needs, configure them to the domain, and they do the work.

*Intelligence is flexible. Authority is stable.*

- **The 24 are templates.** Persona, stance, duty and failure mode come from the template. Domain knowledge comes from the client. That is the unit of delivery.
- **The kernel is the floor.** Agents propose; they do not act unilaterally. Proposals pass the gates, verdicts merge into a **Decision Certificate**, a human signs, and only then does state change.
- **Deterministic.** The gate kernel is compiled COBOL operating on slot indices. Same input, same verdict, every time — no sampling, no drift.
- **Provable.** Append-only audit ledger, signed certificates, evidence hashes on every verdict. No agent carries ledger-write authority.

**Ag3nt24 is not yet available outside classHuman AI tooling.** We are running real builds underneath it first. We will publish the measures we hold it to before we publish results — no benchmark claims without a benchmark.

---

## Research

Our research line **is** Ag3nt24 and the legacy modernization problem it exists to solve: what legacy owners actually need, and the metrics we hold ourselves to before release. [See the research →](https://classhuman.org/research)

**TACO Loop** is a separate, earlier decision-control architecture for unknown-data environments — *Take In Unknowns → Assess and Align → Choose Correctly → Operate and Observe Outcome.* Core law: *unknown data must increase decision discipline, not model confidence.* White Paper v1.0 published July 2026. **It remains unproven research and stays out of client builds.**

---

## Proof

- **In production:** [GunKustom.com](https://gunkustom.com) — full platform rebuild, NestJS + Python vendor-feed normalization, modular-monolith gateway. [PowAlert.com](https://powalert.com) — MERN real-time snowfall alerts. Both built as OKO Forge LLC, now classHuman AI LLC.
- **[Willow Bend](https://willow-bend.netlify.app)** — a production-shaped demo where the LLM has no write path to appointments, and the assistant degrades gracefully to an offline engine.
- **TACO Loop White Paper v1.0** — published July 2026.
- **Scrimba "Portfolio of the Week"** — May 2026.

---

## What we believe

**LAHA — Love All Humans Always.**

AI should support human dignity, creativity, learning, recovery, and decision-making. That means humans in the loop, humans as final authority, accountable agents, accessibility-first design, and systems that fail closed instead of failing loud.

---

## Team

| | |
|---|---|
| **Lawrence Jefferson II** (Menoko OG) | Founder, CEO, CTO, Architect. 24 years U.S. Army; senior backend and full-stack engineer; AI systems builder. [Portfolio](https://ljefferson-menoko-site.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/lawrence-jefferson-ii-46497075) · [GitHub](https://github.com/MenokoOG) |
| **Nicale Jefferson** (LuxgirlOG) | Part-Time UX/UI Designer. Co-author of Ag3nt24, TACO Loop and HADES; author of the classHuman governance framework. [LuxgirlOG](https://luxgirlog.netlify.app/) |

**Contact:** [classhuman.org/contact](https://classhuman.org/contact) — no forms, no trackers, just email.

---

*classHuman AI — driven by LAHA.*
