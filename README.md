# 🧠 SkillSense — AI Capability Navigator for Claude

> **Intent → Decision → Confidence**

SkillSense is an AI-native decision layer built on top of Claude that helps users identify the right capability — Skill, Agent, Workflow, or simple prompt — before they start building or prompting.

Built as the **Graduation Project for NextLeap PM Fellowship — Cohort 44** (April 2026).

---

## 🚀 Live Prototype

[![Live Prototype](https://img.shields.io/badge/SkillSense-Live%20Prototype-6C63FF?style=for-the-badge&logo=bolt&logoColor=white)](https://skillsense-pattern-a-tkx4.bolt.host)

---

## 🔍 The Problem

As Claude evolves beyond simple prompting, it now enables complex tasks through Skills, Agents, and Workflows. But users aren’t struggling with *what Claude can do* — they’re struggling with **deciding how to use it effectively.**

| Challenge | Impact |
|---|---|
| Can’t identify the right capability | Heavy trial-and-error |
| Don’t understand what each capability does | Wasted tokens & poor output |
| Can’t predict token cost or latency | Inefficient decisions |
| Struggle to build repeatable workflows | Low advanced-feature adoption |
| No guidance on combining capabilities | Missed potential |

> *“Users are no longer struggling with what Claude can do. They are struggling with deciding how to use it effectively.”*

---

## 📦 What’s in This Repo

| File | Description |
|---|---|
| [`NL SkillSense.pdf`](https://drive.google.com/file/d/1Ctzz3-XwvCyjXGYoO_Gde8-JeCDhISqj/view) | Final 10-slide deck (Google Drive) |

---

## 🔗 Research & Supporting Links

| Asset | Link |
|---|---|
| 📋 User Research, Interviews & Survey Data | [Notion Page](https://app.notion.com/p/User-Research-Interviews-Survey-Data-SkillSense-3534e0d023c681bc98f7d26899b21fa4) |
| 🗺️ User Flow (Figma Board) | [Figma](https://www.figma.com/board/Dgr5yNEHNWubyRlllDoKO0/SkillSense-%E2%80%94-User-Flow--styled-?node-id=0-1&p=f&t=MTFlJAODC0ucg4Kc-0) |
| 🤖 Live Prototype | [bolt.host](https://skillsense-pattern-a-tkx4.bolt.host) |
| 📄 Final Deck (PDF) | [Google Drive](https://drive.google.com/file/d/1Ctzz3-XwvCyjXGYoO_Gde8-JeCDhISqj/view) |

---

## 🎯 Chosen Capability Focus

**Skills** — SkillSense focuses on helping users understand, select, and confidently deploy Claude Skills as the entry point to advanced capability usage.

---

## 👥 User Segment

SkillSense targets **Claude Power Users & AI Builders** — developers, PMs, and knowledge workers who have moved past basic prompting but consistently underutilise advanced capabilities due to decision friction.

**Behavioural Attributes:**
- Use Claude daily but rely on trial-and-error to find the right capability
- Aware of Skills/Agents/Workflows but unsure when to apply them
- Token-cost conscious; frustrated by inefficient attempts
- Want repeatability and predictability in their AI workflows
- Build or manage AI-assisted processes for themselves or their teams

---

## 🧩 How SkillSense Works

1. **Intent Input** — User describes what they want to accomplish in natural language
2. **Capability Matching** — SkillSense analyzes intent and maps it to the best Claude capability (Skill / Agent / Workflow / Prompt)
3. **Decision Explanation** — Surfaces *why* a capability fits, with predicted token cost and latency
4. **Guided Launch** — One-click scaffold to deploy the chosen capability with confidence

---

## 🏆 MVP Feature Prioritisation

| Feature | Priority | Rationale |
|---|---|---|
| Intent → Capability Matcher | P0 — MVP Core | Directly solves the primary decision friction |
| Capability Explainer (why this works) | P0 — MVP Core | Builds confidence before execution |
| Token & Latency Estimator | P1 | High user anxiety; differentiates from docs |
| Capability Combiner Suggestions | P1 | Unlocks power-user potential |
| Reusable Workflow Library | P2 | Retention & repeatability driver |

---

## 📊 Success Metrics

| Type | Metric |
|---|---|
| **North Star** | % of users who deploy a capability within 5 minutes of intent input |
| Leading | Capability match acceptance rate |
| Leading | Time-to-first-successful-output |
| Lagging | 30-day retention of advanced capability users |
| Lagging | Token efficiency ratio (output quality / tokens consumed) |
| Guard Rail | Trial-and-error attempts per session |

---

## 💼 Business Model

| Phase | Revenue Model |
|---|---|
| V1 (Now) | Free — embedded in Claude.ai as a growth lever for advanced capability adoption |
| V2 | Team/Pro tier — saved workflow templates, team capability libraries |
| V3 | API access for enterprises building Claude-powered internal tools |

**Growth Lever:** Every user who successfully deploys an advanced capability becomes a proof point — shareable workflows drive organic adoption.

---

## 📣 Distribution Strategy

1. **Anthropic Claude.ai Integration** — Native onboarding prompt for users who have never used Skills/Agents/Workflows
2. **Developer Community (Discord + Reddit)** — Ship a public capability quiz; go viral in r/ClaudeAI and Anthropic Discord
3. **LinkedIn & PM Communities** — Case studies showing token savings and output quality gains with SkillSense-guided decisions

---

## ⚠️ Risk Factors

| Risk | Mitigation |
|---|---|
| Anthropic ships native capability guidance | Position as a deeper, personalised layer — not just docs |
| Users ignore recommendations and free-prompt anyway | Embed friction-reducing nudges, not hard gates |
| Capability taxonomy changes with Claude updates | Build on a flexible intent-mapping layer, not hardcoded rules |
| Low discovery if not natively integrated | Partner with Anthropic for beta; publish open API |

---

## 🛠️ Tech Stack

![Bolt](https://img.shields.io/badge/Bolt-6C63FF?logoColor=white)
![Claude](https://img.shields.io/badge/Claude-Anthropic-FF6B35?logoColor=white)
![Figma](https://img.shields.io/badge/Figma-Design-F24E1E?logo=figma&logoColor=white)

- **Prototype:** [Bolt.new](https://bolt.new)
- **AI / LLM:** Claude (Anthropic) — Skills capability
- **Design & Flow:** Figma
- **Research & Planning:** Notion, Jotform

---

## 👤 Author

**Siddhant Jain** — AI Product Manager · NextLeap PM Fellowship Cohort 44

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/jainsiddhant26)
[![Portfolio](https://img.shields.io/badge/NextLeap-Portfolio-orange)](https://nextleap.app/portfolio/siddhant-jain-9jxy)
