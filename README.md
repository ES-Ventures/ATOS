# AI Task Operating Standard (ATOS)

**Developed by ES Ventures LLC**
*Copyright © 2026 ES Ventures LLC. All Rights Reserved.*

---

## What Is ATOS?

The AI Task Operating Standard (ATOS) is a universal methodology for applying structured, expert-quality AI task execution to any domain of work. It gives individuals and organizations a repeatable operating standard for approaching any task with AI — replacing trial-and-error with a proven discipline that works on day one and builds genuine AI fluency over time.

ATOS is built on four components — **Persona, Audience, Task, and Guardrails (PATG)** — and executes through a structured three-phase process:

1. **Phase 1 — Information Gathering:** The framework collects and organizes the user's input into the four PATG components, then runs a lightweight Persona Screen that catches plainly broken Persona–Task pairings before any work is invested.
2. **Phase 2 — Task Elevation:** Task weight is assessed and expert-level gap analysis identifies what is missing, unclear, or risky — one question at a time — until the full PATG picture is refined.
3. **Phase 3 — Output Generation:** Final Persona Calibration runs a rigorous, task-weight-aware three-check sequence (Misalignment → Upgrade Opportunity → Downgrade Risk) against the completed PATG, and the validated components are then assembled into a cohesive, expert-quality deliverable.

The framework's analytical machinery runs invisibly in the background. The user is only interrupted at Decision Gates — points where their judgment is genuinely required — and holds final authority at every one of them.

---

## ATOS Core — The Foundational Document

**ATOS Core** is the foundational document of the standard and the canonical reference for all ATOS implementations. It contains the complete architecture, design principles, phase specifications, gate language, and research foundation. Every ATOS application — such as ATOS: Prompt Builder — is built against a stated version of ATOS Core.

**Current version:** [ATOS_Core_v3_0.md](./ATOS_Core_v3_0.md)

> *Note: As of v3.0, the foundational document is named **ATOS Core** (formerly "ATOS Framework Context"). Versions v2.6 and earlier carry the legacy name.*

### Version History

| Version | Date | Notes |
|---------|------|-------|
| v3.0 | July 2026 | Major release. Persona evaluation split across two surfaces: a lightweight Persona Screen at Phase 1 and a rigorous, task-weight-aware Final Persona Calibration (three-check sequence: Misalignment → Upgrade Opportunity → Downgrade Risk) at Phase 3, run against the completed, gap-refined PATG. Consolidates the v2.6 Persona Alignment Evaluation, Knowledge-Intensive Heavy Task Gate, and Heavy Task Protocol Part 1 into those surfaces. Adds sequential per-Persona screening and calibration for multi-Persona tasks, the Calibration Re-Run and Loop-Back Rules, and standardized flag and override language for every calibration gate. Document renamed to ATOS Core. Validated at 73/73 (STABLE) across three smoke-test cycles. |
| v2.6 | June 2026 | Patch release — three S1 blocking findings from the v2.5 final stability smoke test resolved. Gate 1 firing condition stated explicitly (A5 equivalent; primary fix). Phase 1 slot collection order rule added (A5). Self-reference bare-verb ambiguity threshold clarified (A6). Transparency Gate / Confirmation Gate sequencing note added (A7). |
| v2.5 | June 2026 | Minor revision — three Additional Findings from the v2.4 audit incorporated: Persona elevation cap precision clarifications (A2); self-reference new artifact handoff signal rule (A3); multi-Persona Phase 1 alignment evaluation procedure (A4). Finding A1 deferred. |
| v2.4 | June 2026 | S1 patch release — seven blocking specification gaps resolved. Architecture unchanged. |
| v2.3 | June 2026 | Streamlined distribution edition. Research Foundation and References retained. |

---

## How to Use This Repository

**For AI implementations:** Point your AI to this repository. It will read this README, locate the current ATOS Core document, and use `https://github.com/ES-Ventures/ATOS` as the canonical link in the ATOS Context Preamble on external handoffs.

**For human implementers:** Read the full ATOS Core document linked above. The document is self-contained — it includes all architecture, rules, gate language, worked examples, and the research foundation.

**For external handoffs:** When ATOS-produced output is shared outside the originating chat or project, a short-form ATOS header is prepended to the deliverable. That header references this repository so the receiving party can access the full framework context.

---

## License and Usage

This repository and all contents are proprietary to ES Ventures LLC.

**All Rights Reserved.** Unauthorized copying, modification, redistribution, or creation of derivative works is prohibited without explicit written permission from ES Ventures LLC.

This is the canonical ATOS repository. All authorized ATOS implementations reference this repository. Forks or modified versions are not authorized for distribution without explicit permission.

For licensing inquiries: [licensing@unbreakablestone.com](mailto:licensing@unbreakablestone.com)

---

*AI Task Operating Standard (ATOS) — ES Ventures LLC*
*https://github.com/ES-Ventures/ATOS*
