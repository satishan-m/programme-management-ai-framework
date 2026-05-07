# The Monday Morning Memo

## Format Specification and Illustrative Example

---

## What It Is

The Monday Morning Memo is the Programme Director's primary weekly intelligence briefing.

It is a structured, one-page document delivered at the start of each working week. It is produced by the Intelligence Layer's Narrative Constructor from the Orchestrator Agent's integrated programme narrative. Every section carries a reasoning summary and a confidence signal — High, Medium, or Low — so the Programme Director always knows the weight to place on any given output, and why.

The Memo is accompanied by a conversational briefing session in which the Programme Director interrogates any element in depth, pushes back on the Orchestrator's prioritisation, and adds contextual knowledge that enriches the Programme Narrative.

Its purpose is not to update. It is to direct the Programme Director's attention toward what matters most in the coming week, and to surface the decisions that require their judgement before those decisions become urgent.

---

## Format Specification

### Section One: Programme Health

**Purpose.** An immediate, integrated assessment of the programme's current health across its five primary dimensions.

**Content.** A RAG assessment — Red, Amber, or Green — for each of five dimensions: Schedule, Cost, Quality, Risk, and Adoption Readiness. Each assessment is accompanied by a one-sentence explanatory narrative — the single most important reason the dimension has received its current rating. A change indicator shows whether each dimension's status has improved, remained stable, or deteriorated since the previous Memo.

**Length.** Five lines. One per dimension.

---

### Section Two: This Week's Critical Items

**Purpose.** The three to five items that require the Programme Director's direct attention during the coming week, ranked by urgency.

**Content.** Each critical item is described in two sentences: the first stating what the item is, the second stating what action or decision is required from the Programme Director and by when. No item appears in this section without a specific action or decision attached to it.

**Length.** Maximum five items. Maximum two sentences per item.

---

### Section Three: Key Risks and Issues

**Purpose.** A current picture of the top active risks requiring attention, with their mitigation status.

**Content.** The top three active risks, each presented across four fields: the risk description in one sentence; the current likelihood and impact assessment; the primary mitigating action and its owner; and the risk's trajectory — whether it is increasing, stable, or decreasing.

---

### Section Four: Dependency Watch

**Purpose.** Every dependency at risk of not being met within the coming fortnight, with its downstream consequence if it slips.

**Content.** Each at-risk dependency presented across three fields: the dependency description; the current status and the specific reason it is assessed as at risk; and the downstream consequence — which workstream or milestone is affected and the lead time available for effective intervention.

---

### Section Five: Team Pulse

**Purpose.** The Business Change Agent's qualitative read on team sentiment and adoption readiness.

**Content.** A brief narrative — three to five sentences — summarising the assessment across the programme's primary workstreams and operational stakeholder groups. The narrative distinguishes explicitly between evidence-based signals and conversational signals, with appropriate confidence levels for each.

---

### Section Six: Decisions Required

**Purpose.** Every item awaiting the Programme Director's judgement, with the context needed to make each decision.

**Content.** Each decision presented across three fields: the decision required — stated as a specific question requiring a specific answer; the intelligence basis — a brief summary of the evidence underpinning the decision; and the decision window — the date by which the decision is needed and the consequence of delay. Where the Intelligence Layer has identified a preferred option, it is stated as a recommendation, clearly labelled as such.

---

## Illustrative Example

The following is a Monday Morning Memo for a large-scale ERP implementation at a mid-sized manufacturing organisation, twelve weeks into delivery and approximately six months from planned go-live.

---

**MONDAY MORNING MEMO**
Programme: Apex ERP Implementation | Week 12 | Overall confidence: Medium

---

**Programme Health**

| Dimension | Status | Change | Summary |
|-----------|--------|--------|---------|
| Schedule | Amber | Deteriorating | Integration workstream running seven days behind plan; recovery plan under review |
| Cost | Green | Stable | Expenditure tracking within 3% of budget; no material variances forecast |
| Quality | Amber | Stable | Defect rate within tolerance; two severity-two defects open beyond SLA |
| Risk | Red | Deteriorating | Three risks escalated to high this week; data migration risk now critical |
| Adoption Readiness | Amber | Stable | Training completion at 61% against 75% target; finance team behind schedule |

---

**This Week's Critical Items**

1. Data migration risk requires a Programme Director decision by Wednesday. The data migration workstream has identified a legacy data quality issue affecting approximately 340,000 customer records. Three options have been modelled — see Decisions Required below. A decision is required by Wednesday to protect the integration milestone on 14th March.

2. Supplier Nexus Tech has not confirmed the API integration dependency due last Friday. The Dependency Agent has flagged this as a critical path risk. The Programme Director should contact the Nexus Tech delivery lead directly today — agent outreach has received no response in five working days.

3. Finance team adoption readiness is the lowest across all workstreams, with go-live 22 weeks away. The Business Change Agent's assessment indicates low confidence and awareness in the finance team. A targeted intervention plan is required this week.

---

**Key Risks and Issues**

**Risk 1 — Data Migration Quality** (Red, High likelihood, High impact)
Legacy customer data contains approximately 340,000 records with quality issues incompatible with ERP data standards. Owner: Data Migration Lead. Mitigation: Three options modelled — see Decisions Required. Trajectory: Increasing — scope of issue larger than initially assessed. Confidence: High.

**Risk 2 — Integration Workstream Schedule Slippage** (Amber, Medium likelihood, High impact)
Current velocity indicates the integration milestone is at risk by seven to ten days. Owner: Integration Lead. Mitigation: Recovery plan being developed, including potential deferral of two non-critical integration points. Trajectory: Stable. Confidence: Medium — Nexus Tech data incomplete.

**Risk 3 — Finance Team Adoption Readiness** (Amber, Medium likelihood, Medium impact)
Training completion at 47% against 75% target; conversational assessment indicates low system confidence. Owner: Head of Finance Change. Mitigation: Targeted intervention plan required. Trajectory: Deteriorating — completion rate declining week-on-week for three consecutive weeks. Confidence: Medium.

---

**Dependency Watch**

**Dependency 1 — Nexus Tech API Integration Confirmation** (Overdue)
Nexus Tech was required to confirm API integration specifications by last Friday. Confirmation has not been received. Downstream consequence: integration build cannot begin; each additional day of delay increases the risk to the 14th March milestone. Confidence: High.

**Dependency 2 — Finance Data Extract from Legacy System** (Due: Friday 14th March)
Current completion stands at 34% against a 60% target for this stage. At risk because finance team resource has been diverted to month-end close. Downstream consequence: if delayed beyond 14th March, the data migration milestone of 28th March is at risk. Confidence: Medium.

---

**Team Pulse**

The programme team's overall sentiment remains constructively engaged, with the integration and testing workstreams showing high confidence following last week's successful system configuration sign-off. The primary concern is the finance team, where the Business Change Agent's conversational interactions indicate genuine anxiety about system readiness — two change champions have privately indicated that their confidence in advocating for the system among colleagues is lower than it was a month ago. Training completion data confirms the concern. Supply chain and operations teams remain on track. Supplier team sentiment is more difficult to assess this week given the Nexus Tech communication gap. Confidence: Medium overall. High for internal teams. Low for Nexus Tech — insufficient conversational data this week.

---

**Decisions Required**

**Decision 1 — Data Migration Approach** (Required by Wednesday 12th March)

Option A: Cleanse all 340,000 affected records before go-live. Estimated effort: six weeks additional resource. Impact: go-live moves from September to October.

Option B: Cleanse the 87,000 records in the critical customer segment before go-live; migrate the remaining 253,000 with a defined post-go-live cleansing programme. Estimated effort: two weeks additional resource. Impact: go-live date protected.

Option C: Proceed with current data, applying automated validation rules at point of entry. Estimated effort: three days development. Impact: go-live fully protected; elevated operational support required in first three months.

Planning Agent recommendation: Option B — protects the go-live date whilst addressing the highest-risk data segment before cutover.

Risk Agent note: Option C carries a medium-high risk of operational incidents in the first three months.

Confidence: High on options analysis. Medium on effort estimates — based on Data Migration Lead input, not independently verified.

---

*The Monday Morning Memo is one output of the Agentic Programme Management Framework's Intelligence Layer. For the full framework specification, see the complete whitepaper in this repository.*
