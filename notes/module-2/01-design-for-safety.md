# Design for Safety

> **Source:** `Module 2/Design for Safety Module II.pdf` (Lecture 03), pages 1–27 · `Module 2/Lecture Notes Module II EPP.pdf`, pages 2–5 · **Syllabus:** Selected Functions of Engineering

## Key points

- **Safety** is the condition of being protected from harm, danger or injury. In engineering it means designing systems, processes and products so that risk to **human life, property and the environment** is minimized during **both normal operation and failure conditions**.
- **Design for Safety** is a planned, disciplined and systematic approach applied across the **entire life cycle** of a system — not a check performed at the end.
- Three governing principles: **start early**, **learn from past deficiencies**, and **apply engineering *and* management techniques**.
- Three safety analysis tools: **FMEA**, **FTA** and **HAZOP**. The deck develops FMEA in full.
- **RPN = Severity × Occurrence × Detection** ranks which failure modes get fixed first.
- Professional codes (e.g. NSPE) require engineers to *"hold paramount the safety, health, and welfare of the public."*

---

## 1. What safety means in engineering

**Safety** is the condition of being protected from harm, danger or injury. In engineering, safety refers to the practice of designing systems, processes and products in a way that **minimizes risk to human life, property and the environment during both normal operation and failure conditions**.

**Design for Safety** is defined three ways in the source deck, each adding an angle:

- The application of **principles, criteria and techniques of engineering and management** to optimize all aspects of security within the constraints of **operational efficiency, time and cost**, in all phases of the life cycle of a system.
- The **professional responsibility of engineers** to identify, evaluate, and eliminate or minimize risks to human health, safety and the environment throughout the design process of any system, product or infrastructure.
- A **planned, disciplined and systematic approach** to prevent or reduce accidents or unwanted events throughout the life cycle of a system.

**Origin.** Design for Safety first gained importance in the **1950s**, especially through the **United States Air Force**, after it concluded that a process based on **trial and error and continuous improvement** in the design and fabrication of planes would never be viable. From this development was born the well-known **MIL-STD-882** standard, which is still in force today.

## 2. The three basic principles

| # | Principle | Why |
|---|---|---|
| **1** | **Security begins in the early stages** of design, development, testing and design reviews. | It is essential to establish **hazard identification processes** that can be controlled by applying changes or improvements to the design. The sooner the system and its security weaknesses are analysed, the **easier, faster and cheaper** the change implementation will be. |
| **2** | It is necessary to **learn from the deficiencies of previous designs** to avoid their recurrence. | If we do not apply the lessons learned in previous designs (*lessons learned*, or **REX — return of experience**), our design will never advance, since it will always start from the same starting point. |
| **3** | Security requires the application of **engineering and management techniques** to control hazards in a system. | A security programme must be planned for and implemented so that **security analyses are integrated with other factors that impact management decisions**. |

## 3. Key considerations in design for safety

| Consideration | What it requires |
|---|---|
| **Risk assessment** | Identify potential hazards and risks associated with the product or environment. Conduct thorough risk assessments to evaluate possible dangers and their consequences. |
| **User training and education** | If a product or system requires user interaction, provide clear and comprehensive training and education materials to ensure proper use. |
| **Ergonomics** | Create products and environments that are comfortable, efficient and user-friendly, reducing the risk of musculoskeletal disorders and discomfort. |
| **Redundancy and fail-safes** | Implement redundancy and fail-safe mechanisms in critical systems to prevent catastrophic failures. These systems should still function safely if a primary system fails. |
| **Accessibility** | Ensure products and environments are accessible to people of all abilities, including those with disabilities. Compliance with accessibility standards is essential. |
| **Material selection** | Choose materials that are safe for both users and the environment. Ensure materials do not release harmful chemicals or pose a threat in a fire or other emergency. |
| **Human–machine interface (HMI)** | For digital interfaces and machinery, the HMI should be intuitive, with clear instructions and safeguards to prevent user errors. |
| **Product lifecycle considerations** | Safety must be considered not only during design but throughout the entire lifecycle — manufacturing, use and disposal. |

### Core safety design concepts

| Concept | Meaning |
|---|---|
| **Fail-safe design** | Systems default to a safe condition in the event of a malfunction — e.g. train brakes automatically engage if the signal is lost. |
| **Inherent safety** | Designing systems so they are safe **without relying on additional protective layers** — e.g. using less toxic materials. |
| **Safety factors** | Components are designed with **higher load capacities than expected**, accounting for unknowns — usually **1.5× to 4×** the estimated load. |
| **Safety lifecycle** | Following procedures such as risk identification, hazard assessment, mitigation planning and monitoring over the product's life. |

## 4. Factors of design for safety by domain

**1. Hardware safety**
- **Electrical protection** — designing circuits to avoid short circuits, overheating and electrical fires (e.g. fuses, thermal cutoffs).
- **EMI shielding** — preventing electromagnetic interference that can disrupt system function or harm users.
- **Safe power supply design** — ensuring stable voltage and isolation to avoid shocks or component damage.
- **Redundant components** — backup components to maintain safety if primary ones fail (e.g. dual power supplies in servers).

**2. Software safety**
- **Safe coding practices** — preventing buffer overflows, race conditions or memory leaks that can crash systems or cause unsafe behaviour.
- **Exception handling** — the software handles unexpected situations (e.g. sensor failure in a robot) without dangerous results.
- **Real-Time Operating Systems (RTOS)** — used in critical applications such as medical devices or automotive ECUs to ensure time-bound and predictable behaviour.
- **Fail-safe defaults** — systems default to a safe state when errors are detected (e.g. stopping a robot arm on sensor failure).

**3. Cyber-physical safety**
- **Secure communication** — preventing unauthorized control over connected systems (e.g. hacked pacemakers or industrial PLCs).
- **Sensor validation** — cross-verifying sensor inputs to prevent erroneous data leading to unsafe actions.
- **User interface design** — preventing accidental input or misinterpretation (e.g. clear alerts, confirmation for critical actions).

## 5. Safety analysis tools

1. **Failure Mode and Effects Analysis (FMEA)**
2. **Fault Tree Analysis (FTA)**
3. **Hazard and Operability Study (HAZOP)**

> The source deck names all three but develops only FMEA. FTA is referenced again in [Design for Reliability](02-design-for-reliability.md#9-summary) as a tool for identifying and mitigating failure risks.

### 5.1 FMEA — overview

**Also called:** potential failure mode and effects analysis; failure modes, effects and criticality analysis (**FMECA**).

FMEA, developed by the **U.S. military in the 1940s**, is a **systematic, step-by-step approach to identify and prioritize possible failures** in a design, manufacturing or assembly process, product, or service. It is a common risk analysis tool, and its goal is proactive: to **mitigate or eliminate potential failures**.

- **"Failure mode"** — the way, or mode, in which something might fail. Failures are any errors or defects, especially those that affect the customer, and can be **potential or actual**.
- **"Effects analysis"** — studying the **consequences** of those failures.

Failures are prioritized according to **how serious their consequences are, how frequently they occur, and how easily they can be detected**. FMEA also **documents current knowledge and actions** about the risks of failures for use in continuous improvement.

**Variants and timing.** FMEA can be used during design (**DFMEA**) to prevent failures, and later for process control (**PFMEA**), as well as before and during ongoing operations. Ideally it begins during the **earliest conceptual stages of design** and continues throughout the life of the product or service — it has **bigger leverage and impact in the early stages**, when changes are less costly to implement.

**In short, FMEA:**
- is a systematic method for evaluating systems or processes;
- identifies **how and where** a system might fail;
- analyzes the **effects** of these failures;
- **prioritizes actions** to minimize or eliminate risk.

### 5.2 When to use FMEA

FMEA is used when a process, product or service is being **designed, redesigned or evaluated**. It is also used:

- After **quality function deployment (QFD)**
- When an existing process, product or service is being **applied in a new way**
- **Before developing control plans** for a new or modified process
- When **improvement goals are planned** for an existing process, product or service
- When **analyzing failures** of an existing process, product or service

### 5.3 Steps in FMEA

| Step | Action |
|---|---|
| **1. Build a team** | Assemble a multidisciplinary, cross-functional team with diverse knowledge about the process, product or service, as well as customer needs — typically representatives from design, manufacturing, quality, testing, reliability, maintenance, purchasing (and suppliers), sales, marketing (and customers), and customer service. |
| **2. Set the scope** | Define the FMEA's scope. Is it for concept, system, design, process or service? What are the boundaries? How detailed should it be? Use **flowcharts** to identify the scope and ensure every team member understands it. |
| **3. Identify information** | Fill in the identifying information at the top of the FMEA form. |
| **4. Set scope functions** | Identify the functions of your scope: *"What is the purpose of this system, design, process or service? What do our customers expect it to do?"* Name it with a **verb followed by a noun**. Usually the scope can be broken into subsystems, items, parts, assemblies or process steps, each with its own function. |
| **5. Identify failure potential** | For each function, identify the ways failure could happen — brainstorm. These are **potential failure modes**. This is **the most important activity in FMEA**. If necessary, rewrite the function with more detail to ensure the failure modes show a loss of that function. |
| **6. Identify consequences** | For each failure mode, identify the consequences on the system, related systems, process, product, service, customer or regulations. These are **potential failure effects**. Ask: *"What does the customer experience because of this failure?"* |
| **7. Rate severity** | Determine how serious each effect is — the **severity (S)** rating, usually on a scale of **1 to 10**: one is insignificant, 10 is catastrophic. If a failure mode has more than one effect, record only the **highest** severity rating for that failure mode. |
| **8. Determine root causes** | For each failure mode, determine all the potential root causes. Use tools classified as FMEA Template and How-To-Use documentation to aid these efforts. |

### 5.4 Key elements and the RPN

| Element | Meaning |
|---|---|
| **Failure mode** | How a component or process can fail |
| **Effect** | Consequence of the failure |
| **Cause** | Root cause of the failure |
| **Severity (S)** | Impact on the system or user |
| **Occurrence (O)** | Likelihood of the failure happening |
| **Detection (D)** | Ability to detect the failure before it reaches the user |
| **RPN** | **Risk Priority Number = S × O × D** |

**Worked example:**

- Severity = 9 (severe injury possible)
- Occurrence = 3 (failure occurs occasionally)
- Detection = 2 (easy to detect before failure)

→ **RPN = 9 × 3 × 2 = 54**

### 5.5 Worked FMEA — laptop power management

**System under analysis:** laptop power management.
**Objective:** ensure reliable switching between battery and AC power, proper charging, and shutdown during overheat or low-battery conditions.

| Failure mode | Effect of failure | S | O | D | RPN | Recommended action |
|---|---|---|---|---|---|---|
| Battery does not charge | Battery drain, laptop shutdown | 8 | 4 | 3 | **96** | Check charging IC and firmware |
| Overheating sensor fails | No shutdown on overheating | 9 | 3 | 2 | **54** | Add redundant thermal sensors |
| Power source switching fails | No transition from battery to AC | 7 | 3 | 3 | **63** | Improve switching circuit design |
| Battery percentage misread | Unexpected shutdown | 6 | 5 | 4 | **120** | Calibrate battery level sensing logic |
| OS does not trigger hibernate | Data loss in low-battery condition | 9 | 2 | 3 | **54** | Improve power management software |
| Adapter detection error | Charging disabled unnecessarily | 6 | 3 | 2 | **36** | Add redundant adapter detection logic |

> Note that the **highest RPN (120)** belongs to a *moderate*-severity failure — a misread battery percentage — because it is both frequent and hard to detect. This is exactly what RPN is for: it re-ranks by combined risk rather than by severity alone.

### 5.6 Objectives and benefits

**Objectives**
- Increase product **reliability** and customer **safety**.
- Reduce **warranty costs** and field failures.
- Identify potential **weak points early** in design or process.
- Create a **knowledge base** for future improvements.

**Benefits**
- Reduces risk **proactively**
- Improves reliability and quality
- Saves cost by addressing issues **early**
- Documents organizational knowledge
- Supports compliance with standards (**ISO 9001, IATF 16949**)

### 5.7 Limitations

The FMEA method does have shortfalls:

- The **one-size-fits-all format** can be inefficient, which leads to ineffectiveness.
- **Lack of return on investment (ROI) assessment** over actions amplifies the deficiency.
- In many cases a **lack of data** also amplifies the deficiency, making the three-dimensioned risk assessment difficult and unreliable, which erodes ROI.

Even with these challenges, FMEA remains a powerful method for identifying and mitigating potential risks, ultimately leading to improved reliability, safety and quality. One approach to counteract these issues is to follow a **simpler risk analysis and assessment** — the risk matrix below.

### 5.8 Sample risk assessment matrix

> The deck presents this as an image, offered as the simpler alternative to full FMEA. The table below is **transcribed directly from that slide image**.

Rating = Probability × Severity.

| Probability ↓ / Severity → | Critical: 3 | Moderate: 2 | Marginal: 1 |
|---|---|---|---|
| **Probable: 3** | 🟥 High — 9 | 🟥 High — 6 | 🟨 Medium — 3 |
| **Occasional: 2** | 🟥 High — 6 | 🟨 Medium — 4 | 🟩 Low — 2 |
| **Improbable: 1** | 🟨 Medium — 3 | 🟩 Low — 2 | 🟩 Low — 1 |

> This is the same product rule as the RPN, reduced from three dimensions to two — probability and severity, with detection dropped.

### 5.9 FMEA in real-life applications

| Sector | Applied to |
|---|---|
| **Automotive** | Airbags, brakes, steering systems |
| **Aerospace** | Flight control systems; assessing risk in aircraft hydraulic systems |
| **Healthcare** | Medical devices |
| **Manufacturing** | Production line equipment |
| **Software** | Embedded control systems; preventing faults in embedded system designs |

## 6. Regulatory and ethical framework

Regulatory bodies provide frameworks to ensure engineering designs meet required safety and reliability standards.

| Body | Scope |
|---|---|
| **ISO** (International Organization for Standardization) | International standards such as **ISO 45001** for occupational health and safety and **ISO 31000** for risk management. |
| **OSHA** (Occupational Safety and Health Administration, USA) | Sets workplace safety standards and guidelines. |
| **IEC** (International Electrotechnical Commission) | Publishes standards for electrical, electronic and related technologies. |
| **ASME** (American Society of Mechanical Engineers) | Provides safety codes, especially for pressure vessels and boilers (e.g. **ASME BPVC**). |
| **BIS** (Bureau of Indian Standards) | India's national standards body, responsible for developing safety standards across engineering domains. |
| **NFPA** (National Fire Protection Association) | Creates fire safety codes used in industrial plant design. |
| **CDSCO** (Central Drugs Standard Control Organization, India) | Governs safety in medical device design. |

**Ethical principles.** According to professional codes (e.g. the **NSPE Code of Ethics**), engineers are required to *"hold paramount the safety, health, and welfare of the public."*

> **ISO 31000** reappears as the reference risk management process in [Problem Complexity, Uncertainty, Risk and Ambiguity](06-problem-complexity-uncertainty-risk-and-ambiguity.md#43-risk-management-process-iso-31000).

## 7. Case studies

### Chernobyl Nuclear Disaster (1986)

**Issue:** the nuclear power plant explosion in the Soviet Union resulted from **poor design, inadequate operator training, and lack of safety systems**.

**Lessons learned:**
- Importance of transparent safety standards
- Redundant cooling systems
- Real-time emergency protocols

**Reform:** stricter international nuclear regulatory controls (**IAEA**) were enforced post-Chernobyl.

### Challenger Space Shuttle Disaster (1986)

**Issue:** a faulty **O-ring** in the right booster failed in cold weather, leading to shuttle breakup **73 seconds after launch**.

**Root cause:** pressure from management to launch **despite safety concerns raised by engineers**.

**Lessons learned:**
- Engineers must **speak up and document risks**.
- Reliability testing **under all operational conditions** is crucial.
- Communication between technical and managerial teams is vital.

### Hyatt Regency Walkway Collapse (1981)

**Issue:** the walkways in a hotel collapsed due to a **design change in the hanger rod connections that doubled the load on a connector**. **114 people died.**

**Cause:** miscommunication between design and fabrication teams; poor design review process.

**Lessons learned:**
- Rigor in peer-review and approval stages
- Calculations must be **re-verified when design changes are made**
- Independent verification and safety auditing are essential

## 8. Integrating safety and reliability into design

A combined approach includes:

- **Design reviews** — multidisciplinary teams evaluate safety and reliability implications of designs.
- **Simulation and modelling** — software tools to predict behaviour under stress and simulate failure modes.
- **Testing protocols** — accelerated life testing, shock testing, fatigue testing, etc.
- **User training and manuals** — clear operational guidelines reduce chances of misuse and failure.

## 9. Summary

Designing for safety is not merely a technical requirement — it is a **moral and professional obligation**. As systems grow more complex, the emphasis on these attributes grows stronger. Real-world disasters underscore the need for engineers to adopt a **proactive** approach, guided by standards, regulations, ethics and human concern.

Future engineers must consider not only *"Can we build it?"* but also:

- ✓ *"Should we?"*
- ✓ *"Will it be safe?"*
- ✓ *"Will it last?"*

> The last of those three questions is the subject of [Design for Reliability](02-design-for-reliability.md).
