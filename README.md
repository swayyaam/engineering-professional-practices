# Engineering Professional Practice — EX40003

Markdown notes, sample questions and the lesson plan for **Engineering Professional Practice**, 7th semester, KIIT.

The notes are distilled from the lecture decks and the Module II lecture notes: each concept is defined **once**, in the file where it fits best, and other files link to it rather than repeat it.

| | |
|---|---|
| **Course code** | EX40003 |
| **Course coordinator** | Dr. Pruthwiraj Sahu |
| **Course faculty** (CS-32 & CS-33) | Dr. Ram Kumar Kesharwani |
| **Academic session** | Autumn Semester 2026–27 |
| **Contact hours** | 2 hours/week (LTP: 2-0-0), 2 credits |

---

## Contents

| Path | What it is |
|---|---|
| [`notes/`](notes/) | The notes, one folder per module — 12 files, ~2,100 lines |
| [`exams/`](exams/) | The faculty's sample question papers, plus a worked question bank for Module II |
| [`lesson-plan.md`](lesson-plan.md) | Full syllabus, course outcomes, books, assessment scheme and lecture-by-lecture plan, transcribed from the course handout |
| [`README.md`](README.md) | This file |
| [`.gitignore`](.gitignore) | Keeps the raw lecture decks and editor cruft out of the repository |

---

## Notes

### Module 1 — Engineering and Engineer

| # | Note | Covers |
|---|---|---|
| 1 | [Engineering as a Discipline and a Profession](notes/module-1/01-engineering-as-a-discipline-and-a-profession.md) | Definition, the discipline and its six components, the profession and its six elements, licensing in India and the US, discipline vs. profession comparison |
| 2 | [Attributes and Functions of a Practicing Engineer](notes/module-1/02-attributes-and-functions-of-a-practicing-engineer.md) | Who a practicing engineer is, six key + four additional attributes, the four core functions |
| 3 | [Engineer as Problem Solver, Designer and Change Agent](notes/module-1/03-engineer-as-problem-solver-designer-and-change-agent.md) | Engineering Method vs. Scientific Method, the design process, the six aspects of the engineer as change agent |

### Module 2 — Selected Functions of Engineering

| # | Note | Covers |
|---|---|---|
| 1 | [Design for Safety](notes/module-2/01-design-for-safety.md) | Definitions and origin (MIL-STD-882), three principles, key considerations, hardware/software/cyber-physical safety, FMEA in full with RPN and a worked table, the risk matrix, regulatory bodies, Chernobyl/Challenger/Hyatt Regency |
| 2 | [Design for Reliability](notes/module-2/02-design-for-reliability.md) | Definition, quality vs. reliability, reliability across the life cycle, six design techniques, MTTF/MTBF/MTTR/λ/R(t), ALT/HALT/burn-in/ESS, ECU and smartphone-battery cases |
| 3 | [Quality Management](notes/module-2/03-quality-management.md) | Crosby, Juran and Garvin's five categories, Garvin's eight dimensions, QC vs. QA, ISO 9001, TQM, Six Sigma with DMAIC and DMADV |
| 4 | [Productivity](notes/module-2/04-productivity.md) | Production vs. productivity, efficiency vs. effectiveness, partial/total-factor/total productivity, deflating to a base year, partial-productivity trade-offs, service productivity, Lean/JIT/work study |
| 5 | [Quality and Productivity Tools](notes/module-2/05-quality-and-productivity-tools.md) | The seven basic quality tools plus the eleven-tool catalogue (Pareto, Ishikawa, control charts, 5S, VSM, benchmarking, Poka-Yoke, SPC, FMEA, Kaizen, DMAIC), Toyota Production System, implementation barriers, Industry 4.0 trends |
| 6 | [Problem Complexity, Uncertainty, Risk and Ambiguity](notes/module-2/06-problem-complexity-uncertainty-risk-and-ambiguity.md) | The CURA factors and how they compound, aleatory vs. epistemic uncertainty, Risk = P × C, six management frameworks incl. ISO 31000, 737 MAX / Fukushima / Mars Climate Orbiter, Industry 4.0 and urban transport worked cases |
| 7 | [Project Management](notes/module-2/07-project-management.md) | Definitions, the five life-cycle phases, the triple constraint, PMBOK knowledge areas, methodologies, Gantt/WBS/EVM, Delhi Metro / Airbus A380 / TCS, challenges, certifications |
| 8 | [Managerial Functions in Engineering](notes/module-2/08-managerial-functions.md) | Planning (strategic/tactical/operational), organizing, motivating with Maslow/Herzberg/McGregor, accounting; Bengaluru Metro, Toyota and ISRO cases |
| 9 | [Costing and Accounting](notes/module-2/09-costing-and-accounting.md) | Cost and cost drivers along the value chain, fixed vs. variable cost, CVP analysis, break-even and contribution margin, worked example, margin of safety, cost-structure changes, automation, sales-mix analysis, cost-behaviour patterns |

---

## Exams

### Sample question papers

The faculty's own papers, transcribed. Each question links to the note that answers it; open-ended and reflective questions are marked `—` rather than given a false pointer.

| Paper | Questions | Covers |
|---|---|---|
| [Module I — sample questions](exams/module-1-sample-questions.md) | 21 | Engineering vs. science and technology, interdisciplinary collaboration, attributes of a successful engineer, problem solving, the engineer as change agent |
| [Module II — sample questions](exams/module-2-sample-questions.md) | 25 | Safety and reliability, quality and productivity, complexity/uncertainty/risk/ambiguity, project management, managerial functions, costing and accounting |

### Question bank

| Bank | Contents | Covers |
|---|---|---|
| [Module II — question bank](exams/module-2-question-bank.md) | 73 one-mark, 9 numericals, 22 five-mark — 104 items with model answers | Design for safety, design for reliability, quality management, productivity, quality and productivity tools, CURA |

Answers are written out in full rather than linked, so the bank stands on its own for revision. It covers the confirmed portion of Module II only — project management, managerial functions and costing are in [`notes/`](notes/) but not yet in the bank.

---

## Syllabus coverage

| Chapter | Name | Lectures | Notes |
|---|---|---|---|
| **1** | Engineering and Engineer | 4 | ✅ Module 1 |
| **2** | Selected Functions of Engineering | 8 | ✅ Module 2 |
| **3** | Professional Aspects of Engineering | 8 | ❌ not yet written |
| **4** | Group Dynamics | 4 | ❌ not yet written |

> The mid-semester examination falls between Chapter 2 and Chapter 3. See [`lesson-plan.md`](lesson-plan.md) for the full topic list under each chapter.

**Two known gaps:**

1. **Chapter 3 — Professional Aspects of Engineering**: accreditation, certification and licensing; ethics and morality, ethical dilemmas, codes of ethics, professional conduct, professional societies, engineering standards; legal forms of business organizations, employment contracts, trademarks, patents, copyrights, trade secrets, professional liability, contractual agreements, environment and IT laws, and the WTO framework.
2. **Chapter 4 — Group Dynamics**: individual cognition, working in teams, interacting with stakeholders, multicultural environments, team and group communication, negotiation and conflict resolution.

No decks were supplied for either. Adding them lets these notes be extended in the same shape, as `notes/module-3/` and so on.

A smaller gap sits inside Chapter 2: the syllabus lists **"controlling"** among the managerial functions, but the Module II lecture notes replace it with **"accounting"**. Controlling is covered only indirectly, in the [Project Management](notes/module-2/07-project-management.md#4-what-project-management-entails) deck's *planning–organizing–controlling–measuring* framing.

---

## About these notes

- **Deduplicated.** Where the lecture decks and the Module II lecture notes covered the same ground — the quality/productivity introduction appears word-for-word in both, Garvin's eight dimensions in both, DMAIC in both, FMEA in three places, the five project life-cycle phases and triple constraint in both, the CURA definitions in both — the material is stated **once** and cross-linked. The eleven-tool catalogue was pulled out of the quality chapter into its own note so that quality and productivity could each be stated without repeating it.
- **Diagrams** are [Mermaid](https://mermaid.js.org/) blocks, which render on GitHub, in VS Code and in Obsidian. Break-even and margin-of-safety charts are kept as fenced ASCII, since axis figures read better that way.
- **Typos** carried in from the slides are corrected (`Crossby` → Crosby, `Safety AnalysisTools` → Safety Analysis Tools, `10.00O` → 10.00, `on leas.` → on lease). Technical claims are left as the lecturer stated them.
- **Two arithmetic slips are flagged, not silently fixed.** The productivity deck prints two expressions that do not evaluate to their own stated answers — the total-productivity line, and the deflated sales-revenue line in the base-year example. In both cases the expression and the printed answer are reproduced as the deck has them, with a note on which figure is consistent with the deck's own definitions. See [Productivity § 4](notes/module-2/04-productivity.md#worked-example--deflating-to-a-base-year).
- **Image-only slides were recovered, not skipped.** The Engineering Method vs. Scientific Method chart, the triple-constraint figure, the FMEA sample risk-assessment matrix and the five cost-behaviour-pattern graphs were all extracted from the source files and transcribed.

### Source material

The notes are derived from **nine PDF lecture decks** — two for Module 1, seven for Module 2 (including the 31-page combined Module II lecture notes) — plus the course handout and syllabus. **Those files are not in this repository** — they are course material rather than my own work, and are excluded by [`.gitignore`](.gitignore). Each note names the deck and page range it came from, so the two can be read side by side.
