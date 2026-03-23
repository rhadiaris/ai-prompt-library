# Personas - Validate and Refresh Quarterly


---

Role:
Act like a senior growth operator and persona research lead.

Objective:
Audit all existing personas to ensure data freshness, behavioral accuracy, and strategic alignment using current internal data only (browser ChatGPT environment).

Task:
For each existing persona in your CRM/knowledge base, validate assumptions with recent quantitative and qualitative signals, decide keep/update/retire, and propose the next signal to watch.

Inputs you may use:
- CRM/opportunity data (win rate, ACV, sales cycle, last-touch date)
- Product analytics (DAU/WAU, feature adoption, cohort retention, expansion/churn)
- Marketing analytics (CTR/CVR by message, channel fit, content performance)
- Feedback sources (NPS/CSAT, interviews, tickets, reviews, sales notes)

Process (Assess → Compare → Update → Signal next review):
1) Assess: Locate the persona record; note its “last updated” field and core assumptions (jobs-to-be-done, pains, triggers, objections, channels).
2) Compare: Contrast assumptions with last 90–180 days of signals (usage, funnel, revenue, sentiment). Flag deltas that are statistically or practically significant.
3) Update: Choose action = keep (no material change), update (document revised traits/messages), or retire (merge/sunset with rationale).
4) Signal next review: Specify one measurable leading indicator to monitor (metric + source + threshold) and schedule a review date based on volatility.

Output format (Markdown table, one row per persona):
Columns = Persona | Last updated (YYYY-MM-DD) | Key change observed (≤140 chars) | Action (keep/update/retire) | Next signal to watch (metric + source + threshold) | Next review date (YYYY-MM-DD) | Owner.

Constraints & Stop Conditions:
- Limit strictly to personas that already exist in your system; do not create new personas.
- End when all existing personas are updated or retired. No extra commentary.

Quality bar & self-check before finalizing:
- Dates are ISO-formatted and current.
- “Key change” is specific, evidence-grounded, and concise.
- “Next signal” is leading, measurable, and tied to a clear threshold.
- Review cadence aligns with volatility (30/60/90 days typical).
- Reveal only the final table; keep reasoning internal.

Take a deep breath and work on this problem step-by-step.
