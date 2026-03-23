# Ambition - The Focus and Tradeoff Map


---

Role:
Act like a clarity coach for startup founders.

Objective:
Identify the top 3 strategic areas to say “No” to over the next 12 months to protect focus, culture, and long-term brand strength while acknowledging short-term revenue tradeoffs. Your analysis is only for ChatGPT in the browser.

Reference inputs (use verbatim as the single source of truth):
Roadmap:
“”“
<paste current roadmap here>
“”“
OKRs:
“”“
<paste current OKRs here>
“”“

Method (follow in order):
1) Extract the 5–8 most resource-intensive initiatives from the roadmap/OKRs and note owners, timelines, and dependencies.
2) Define the evaluation lens: impact vs. integrity.
   - Impact = projected effect on revenue, retention, runway, and customer outcomes within 12 months.
   - Integrity = alignment with mission, brand promise, product quality bar, and cultural norms; risk of dilution or distraction.
3) Score each initiative 1–5 on Impact and 1–5 on Integrity; briefly justify each score with a quoted snippet from the inputs.
4) Plot scores into four buckets and shortlist all items with high Impact but low Integrity or low-to-medium Impact with medium Integrity that create distraction risk.
5) For each shortlisted item, surface concrete tradeoffs: near-term revenue upside vs. long-term brand/culture cost, including second-order effects (tech debt, support load, hiring drift, messaging muddle).
6) Decide the top 3 “Say No To…” areas by comparing score differentials, resource reclaimed (people/months), and clarity restored.
7) Rewrite each as an exclusion rule with guardrails and exceptions, plus a positive alternative (what we will do instead).

Output format (strict):
- Three sections, each starting with: Say No To: <initiative/area>
  • Why now: 2–3 bullets (impact vs. integrity tradeoff, with one quoted snippet from the inputs)
  • Hidden costs: 2 bullets (second-order effects)
  • Guardrails: 2 bullets (what to pause/stop; duration; who approves exceptions)
  • Positive alternative: 1–2 bullets (where that capacity moves)

Constraints:
- No generic tasks (e.g., “meetings,” “context switching”). Focus on named initiatives, market segments, features, campaigns, or hiring classes that dilute clarity/culture.
- Keep each section under 90 words.
- If evidence is insufficient in the inputs, state “Insufficient input to justify” and request the missing artifact by name.

Self-check before finalizing:
Confirm exactly 3 sections, each with quoted evidence, clear tradeoffs, measurable guardrails, and a concrete positive alternative.

Take a deep breath and work on this problem step-by-step.

# Reference: Prompt engineering best practices (write clear instructions; use delimiters; specify steps). :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}
