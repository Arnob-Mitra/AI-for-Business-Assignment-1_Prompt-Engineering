# P05 · Student Feedback Insight Summarizer

**Section:** 03 — Product Team  
**Workflow step:** Step 1 of 2 (feeds into feature planning → requirement drafting)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a product analyst for an EdTech company.

Summarize student feedback into clear product insights for the product team.

Input:
- feedback source: [SOURCE]
- feedback text, comments, survey responses, or support issues: [FEEDBACK_DATA]
- product area or feature being reviewed: [PRODUCT_AREA]
- objective of analysis: [OBJECTIVE]

Requirements:
- Group the feedback into 3 to 5 major themes
- Identify the most common pain points or needs
- Highlight any repeated complaints, requests, or positive signals
- Distinguish between usability issues, content issues, technical issues, and feature requests where possible
- Use concise, business-friendly language
- Do not invent feedback that is not present in the input
- Keep the summary practical for product review discussions

Output format:
1. Executive summary
2. Key themes
3. Most common pain points
4. Opportunities or suggested focus areas
5. Why this insight summary is useful for the product team
```

---

## 🏢 Intended Workflow or Task

Step 1 of a 2-step product workflow.

- **Trigger:** Product team receives student feedback from surveys, app reviews, support logs, or internal reports
- **Actor:** Product analyst, product manager, or operations team member runs the prompt
- **Timing:** During product review, sprint planning, or issue prioritization
- **Next step:** Output feeds into feature discussion and requirement drafting

```text
Feedback collected from students → Product analyst enters feedback data → [P05 RUNS]
    → Insight summary created → Team reviews themes
    → P06 (Feature Requirement Draft Generator) may be used next
```

---

## ❗ Problem Being Solved

Student feedback is valuable, but it is often scattered across survey results, support messages, comments, and informal reports. Reviewing this information manually is slow and makes it harder for product teams to identify recurring issues, user pain points, or improvement opportunities in a timely way.

This prompt helps the team convert raw feedback into structured insights more quickly. It supports faster review, better prioritization discussions, and improved collaboration between product, support, and operations teams.

---

## ⚡ Automation Potential

**Level: Medium**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — feedback summarization is needed regularly |
| Data availability | Medium to High — depends on access to student feedback sources |
| Human judgment needed | High — prioritization and interpretation still require product judgment |
| Integration possibility | Output can support sprint planning, review meetings, and documentation |
| Estimated value | Saves review time and improves visibility of recurring user issues |

**Human-in-the-loop role:** Product teams must verify themes against the actual feedback and use business judgment before deciding priorities or roadmap changes.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Important nuance in raw feedback gets oversimplified | Medium | Review original comments when making decisions |
| Model misclassifies issues or feature requests | Medium | Validate output during product review meetings |
| Rare but important complaints are hidden by theme grouping | Medium | Use AI summary as a starting point, not the only analysis |
| Unsupported insights added beyond source feedback | Medium | Prompt explicitly instructs the model not to invent feedback |

**Overall risk rating: MEDIUM** — useful for summarization support, but should not replace direct review of user feedback.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Summarize student feedback for the product team.  
**Output:** Produced a readable summary, but lacked structure and did not separate themes clearly enough for product discussions.  
**Observed effect:** Helpful for a quick overview, but not strong enough for prioritization or sprint planning.  
**Lesson learned:** Product prompts need structured outputs and clearer insight categories to support team decisions.

---

### v1.1 — Structured insight summary version ✅ Current
**Date:** March 2026  
**Change:** Added input fields, explicit theme grouping, pain point identification, issue categorization, and opportunity framing.  
**Output:** Summaries became clearer, more actionable, and better suited to product discussions.  
**Observed effect:** Improved usefulness for product review and follow-up requirement drafting.  
**Lesson learned:** Structured product prompts create more actionable outputs than broad summarization prompts.

---

## 🔗 Related Prompts

- **Next in chain:** P06 — Feature Requirement Draft Generator
- **Related workflow:** Product review, sprint planning, issue prioritization
- **Parent section:** 03-product-team/README.md
- **Library index:** README.md
