# Personas - Translate Persona Insight Into Product Strategy


---

Role:
Act like a senior product leader who aligns user personas to roadmap decisions.

Objective:
Identify exactly 3 high-impact product or feature priorities grounded in persona insights that close unmet needs and move core business metrics (revenue, retention, NPS). This prompt is for ChatGPT in the browser.

Inputs (paste below between ---):
--- 
Personas (names, JTBD, segments):
Top pain points (with evidence):
Behavior/usage analytics (events, cohorts, funnels):
Qualitative insights (interview quotes/themes):
Business goals & guardrails (targets, time horizon, constraints):
Tech/ops constraints (feasibility, dependencies):
---

Process (follow strictly):
1) Synthesize: Cluster unmet needs per persona; validate each with quantitative (analytics) and qualitative (interviews) evidence. Flag sample size or bias risks.
2) Impact model: For each need, estimate path to value (how fixing the need changes a user behavior that drives revenue/retention/NPS). State the causal link.
3) Ideate tightly: Propose one crisp feature concept per top need (not “nice-to-have”). Describe primary user action, success state, and minimal scope (v1).
4) KPI mapping: For each concept, define 2–3 measurable KPIs with formulas, baselines (if provided), and target deltas tied to business outcomes.
5) Effort & risk: Assign rough effort (S/M/L), key dependencies, and top risks/assumptions; include how to de-risk (experiment or prototype).
6) Prioritize: Use a weighted scorecard (Impact x Confidence ÷ Effort). Show the score inputs and final ranking. Pick the top 3 only.
7) Output: Produce exactly three priorities in the specified format.

Output format (use this template; no preambles):
1) Priority title
   Persona(s) and unmet need:
   Feature concept (v1 scope in one sentence):
   Rationale (evidence: analytics + quotes):
   Business outcome linkage:
   KPIs (name, formula, baseline → target):
   Effort & risks (with mitigation):
   Next step (experiment/MVP and timeline):

2) Priority title
   [repeat template]

3) Priority title
   [repeat template]

Constraints:
- Limit to 3 priorities. Avoid speculative ideas and generic statements.
- Be specific, concise, and unambiguous; prefer clarity over creativity.
- If evidence is missing, state “Evidence gap” and propose how to validate.

Reasoning:
Map persona need → feature concept → business outcome → KPI plan → prioritization.

Self-check before finalizing:
- Are all claims tied to evidence or flagged as gaps?
- Are KPIs measurable and outcome-aligned?
- Did you include only three priorities?

Take a deep breath and work on this problem step-by-step.
