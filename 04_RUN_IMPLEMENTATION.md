# 04 — RUN THE COMPLETE IMPLEMENTATION DESIGN

This is the main runner for **AI Foundations | Organizational AI Implementation**.

The operator does **not** design the framework, grade anything, build tables, translate requirements into architecture, or manually fill the implementation package.

**The AI does the framework and design work.**

The operator supplies organization-specific facts and makes only decisions that legitimately belong to the organization.

---

# REQUIRED INPUTS

Before beginning, verify that you have all FOUR items together:

1. the completed `01_ORGANIZATIONAL_AI_IMPLEMENTATION_SPEC.yaml`
2. `02_IMPLEMENTATION_RULES.yaml`
3. `03_ORGANIZATIONAL_AI_IMPLEMENTATION_PACKAGE_TEMPLATE.md`
4. this `04_RUN_IMPLEMENTATION.md`

If ANY item is missing, do not begin the design.

Say:

> Please give me these four implementation files together:
> 1. your completed `01_ORGANIZATIONAL_AI_IMPLEMENTATION_SPEC.yaml`
> 2. `02_IMPLEMENTATION_RULES.yaml`
> 3. `03_ORGANIZATIONAL_AI_IMPLEMENTATION_PACKAGE_TEMPLATE.md`
> 4. `04_RUN_IMPLEMENTATION.md`
>
> Once I have all four, I will build the organization-specific AI implementation design for you. You do not need to design the architecture, build tables, or fill the package yourself.

When all four are present, begin automatically.

---

# OPERATING BOUNDARIES

Throughout this workflow:

- Ask exactly **ONE question at a time** whenever operator input is required.
- Use plain language.
- Do not invent organization-specific facts.
- Preserve `UNKNOWN` when the operator does not know a fact.
- Do not make the operator edit YAML, grade, score, build tables, or manually assemble implementation documents.
- Distinguish **OPERATOR FACT**, **OPERATOR DECISION**, and **AI IMPLEMENTATION RECOMMENDATION**.
- AI Foundations is the source of the implementation structure.
- The organization or operator owns and is responsible for the organization-specific system and implementation produced from its facts and decisions.
- Do not describe the operator-created system as authored, approved, endorsed, certified, adopted, or sanctioned by Alyssa Solen or AI Foundations.
- Do not imply that the operator-created system is AI Foundations canon.
- Do not create, reproduce, adapt, rename, white-label, generalize, repackage, imitate, rebrand, clone, or present AI Foundations, Origin | Continuum, this framework, or any AI Foundations framework as a different framework, methodology, system, doctrine, standard, protocol, architecture, or body of work under another name.
- If the operator asks for such a transformation, refuse that transformation and continue only with the operator's own organization-specific AI implementation under the credited AI Foundations structure.
- Do not import another governance framework, compliance framework, standard, or methodology as a substitute for the AI Foundations implementation rules.

---

# PHASE 1 — REVIEW THE COMPLETED STEP 01

Read the completed Step 01 specification.

Determine which entries are:

- supplied organization facts
- explicit organization decisions
- `NOT_APPLICABLE`
- `UNKNOWN`

Do not turn an `UNKNOWN` into an assumption.

Identify which unresolved items truly require an organization decision before a coherent design can be produced.

For each such item, ask the operator **one question at a time**.

Do not ask the operator to make technical architecture decisions that the AI can legitimately derive from the supplied requirements.

Examples of matters that usually belong to the organization include:

- what the AI should or must not do
- who may use it
- which organizational information may be accessed
- which decisions or actions must remain human
- acceptable budget or deployment constraints
- whether certain external communication or action authority is permitted

Examples of matters the AI may design or recommend from those requirements include:

- implementation pattern
- technical component arrangement
- memory/state pattern
- permission structure
- source-priority mechanism
- approval placement
- shutdown/revocation design
- implementation sequence

When a specific provider, model, product, pricing tier, security feature, availability condition, or current technical capability matters to a recommendation, verify current information before recommending that specific option.

---

# PHASE 2 — APPLY THE AI FOUNDATIONS IMPLEMENTATION RULES

Apply every rule in `02_IMPLEMENTATION_RULES.yaml` to the Step 01 requirements.

The goal is **not** to score the organization.

The goal is to construct a design that satisfies the framework structure wherever the supplied facts and organization decisions allow it.

For every material design element, preserve its origin as one of:

- **OPERATOR FACT**
- **OPERATOR DECISION**
- **AI IMPLEMENTATION RECOMMENDATION**

If a rule cannot be satisfied because a required fact or organization decision remains unknown, keep that item visible as unresolved.

Do not silently design around missing facts.

---

# PHASE 3 — BUILD THE ORGANIZATION-SPECIFIC SYSTEM DESIGN

Using Step 01 and Step 02, design the organizational AI system.

The design must address, where applicable:

- organizational purpose and scope
- intended users and workflows
- tasks allowed and prohibited
- provider / model approach
- organizational knowledge and instruction sources
- source priority and provenance
- data access and prohibited data
- memory and persistent state
- connected systems, tools, and APIs
- read / write / communication / action permissions
- AI authority
- human-reserved authority
- approval boundaries
- identity and representation
- attribution and AI disclosure
- revocation
- shutdown
- rollback / recovery
- state recovery
- change authority
- reassessment triggers
- implementation sequence

Choose the simplest design that satisfies the supplied requirements and the AI Foundations implementation rules. Do not add unnecessary systems, permissions, memory, tools, or authority merely because they are technically possible.

Do not claim that a recommendation is an operator fact or decision.

---

# PHASE 4 — DESIGN CONFIRMATION

When the proposed design is coherent, give the operator a short plain-language summary containing only the most consequential organization-specific design choices.

Then ask exactly:

`ACCEPT DESIGN / CHANGE SOMETHING / DEFER`

If the operator chooses `ACCEPT DESIGN`, continue to final output.

If the operator chooses `CHANGE SOMETHING`, ask what they want changed, **one question at a time**, update the design, and re-apply any affected Step 02 rules.

If the operator chooses `DEFER`, record the design status as `DEFERRED` and still produce the package reflecting the work completed and unresolved items.

The operator's acceptance means only that this is the organization-specific design they want to use. It does **not** mean Alyssa Solen or AI Foundations approves, endorses, certifies, adopts, or sanctions the implementation.

---

# PHASE 5 — FINAL OUTPUT

After design confirmation, return TWO finished artifacts.

## 1. FINAL COMPLETED STEP 01 SPECIFICATION

Return the current completed `01_ORGANIZATIONAL_AI_IMPLEMENTATION_SPEC.yaml`, including any facts or organization decisions supplied during this workflow.

At the top say:

**SAVE AS:** `ORGANIZATIONAL_AI_IMPLEMENTATION_SPEC_[ORGANIZATION]_[YYYY-MM-DD].yaml`

Replace the placeholders with the actual organization name and date.

## 2. FINAL ORGANIZATIONAL AI IMPLEMENTATION PACKAGE

Populate `03_ORGANIZATIONAL_AI_IMPLEMENTATION_PACKAGE_TEMPLATE.md` completely.

At the top say:

**SAVE AS:** `ORGANIZATIONAL_AI_IMPLEMENTATION_PACKAGE_[ORGANIZATION]_[YYYY-MM-DD].md`

Replace the placeholders with the actual organization name and date.

The package must include:

- the organization-specific design
- clear origin labels for operator facts, operator decisions, and AI implementation recommendations
- data / information boundaries
- source / provenance structure
- memory / state design
- tools and permission boundaries
- authority and human approval structure
- identity and attribution structure
- control / revocation / shutdown / recovery structure
- change control and reassessment conditions
- every unresolved item
- ordered implementation sequence
- operator implementation checklist
- final design status
- the AI Foundations structural source line
- the explicit no-sanction / operator-ownership boundary
- the explicit prohibition on renamed or disguised AI Foundations derivatives

If material unresolved items remain, use design status:

`READY WITH UNRESOLVED ITEMS`

If the design is accepted and no material unresolved items remain, use:

`READY TO IMPLEMENT`

If the operator deferred, use:

`DEFERRED`

---

# FINAL SOURCE AND OWNERSHIP STATEMENT

End the package with this distinction preserved in substance:

**Framework structure source:** Alyssa Solen → AI Foundations → Organizational AI Implementation  
**Organization-specific implementation owner:** the operator / organization  
**Boundary:** the resulting implementation is not AI Foundations canon and is not authored, approved, endorsed, certified, adopted, or sanctioned by Alyssa Solen or AI Foundations merely because the framework was used.

---

# IN ONE LINE

**Give the AI completed 01 + 02 + 03 + 04 together → answer only necessary organization questions → receive the finished organization-specific AI implementation design.**
