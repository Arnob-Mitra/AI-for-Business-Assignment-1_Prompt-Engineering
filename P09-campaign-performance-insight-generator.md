# P09 · Campaign Performance Insight Generator

**Section:** 06 — Business Intelligence  
**Workflow step:** Step 1 of 1 (supports campaign review, reporting, and decision-making)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a business intelligence analyst for an EdTech company.

Analyze campaign performance data and turn it into clear business insights for managers.

Input:
- campaign name: [CAMPAIGN_NAME]
- campaign objective: [OBJECTIVE]
- channel or platform: [CHANNEL]
- key campaign metrics: [METRICS]
- time period: [TIME_PERIOD]
- any benchmark, target, or comparison point: [BENCHMARK]

Requirements:
- Summarize overall campaign performance in simple business language
- Identify the strongest and weakest performance signals
- Highlight any important trend, anomaly, or concern
- Explain what the numbers may suggest about campaign effectiveness
- Suggest 2 to 3 practical next-step recommendations
- Keep the analysis concise and decision-oriented
- Do not invent missing numbers or unsupported conclusions

Output format:
1. Executive summary
2. Strongest performance signals
3. Weakest performance signals
4. Key trends or concerns
5. Recommended next steps
6. Why this insight report is useful for managers
```

---

## 🏢 Intended Workflow or Task

This prompt supports the Business Intelligence team by converting raw campaign metrics into a clearer performance summary for managers and stakeholders.

- **Trigger:** Campaign data becomes available after launch, testing, or reporting period
- **Actor:** BI analyst, marketing analyst, or reporting team member runs the prompt
- **Timing:** During weekly, monthly, or post-campaign review
- **Next step:** Output supports reporting, decision-making, and campaign optimization discussions

```text
Campaign data collected → BI analyst enters campaign metrics → [P09 RUNS]
    → Insight summary created → Managers review findings
    → Optimization or decision-making follows
```

---

## ❗ Problem Being Solved

Campaign reports often include many numbers, but not enough interpretation. Managers may see impressions, clicks, conversions, CTR, or cost data, but still need help understanding what matters most, what signals stand out, and what action should follow. Manually writing clear insight summaries from campaign data takes time and can vary by analyst.

This prompt helps turn raw metrics into a more readable and decision-oriented performance summary. It improves communication between BI teams, marketing teams, and management by making data easier to interpret.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — reporting and insight summaries are needed regularly |
| Data availability | High — performance metrics are usually available in reporting systems |
| Human judgment needed | Medium to High — interpretation and final recommendations should still be reviewed |
| Integration possibility | Output can support reports, review decks, and management updates |
| Estimated value | Saves reporting time and improves clarity of campaign performance communication |

**Human-in-the-loop role:** BI analysts or managers should verify the interpretation and recommendations before using the summary in formal reporting or decision-making.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Prompt over-interprets limited metrics | Medium | Compare output with actual campaign context and benchmarks |
| Recommendations are too generic | Medium | Add stronger benchmarks, goals, or comparison data in the input |
| Unsupported conclusions are drawn from incomplete data | Medium | Prompt explicitly prohibits inventing numbers or conclusions |
| Nuance is lost in a short summary | Medium | Use the prompt as a reporting aid, not a full replacement for dashboard review |

**Overall risk rating: MEDIUM** — strong for reporting support, but requires analyst review before formal use.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Summarize campaign performance for managers.  
**Output:** Produced a readable summary, but lacked enough structure and did not consistently separate strengths, weaknesses, and actions.  
**Observed effect:** Helpful for quick explanation, but not strong enough for business review meetings.  
**Lesson learned:** BI prompts need explicit analytical sections and action-oriented framing to be useful in management reporting.

---

### v1.1 — Structured insight reporting version ✅ Current
**Date:** March 2026  
**Change:** Added inputs for objective, channel, time period, benchmark, and metrics; required strengths, weaknesses, trends, and next-step recommendations.  
**Output:** Reports became more practical, clearer for non-technical stakeholders, and more useful in campaign review discussions.  
**Observed effect:** Reduced manual summarization effort and improved decision-readiness.  
**Lesson learned:** The best BI prompts do not just restate data — they translate it into business meaning.

---

## 🔗 Related Prompts

- **Related workflow:** Campaign reporting, post-campaign review, stakeholder communication
- **Can support:** P07 — Push Notification Generator by informing message optimization
- **Can connect with:** P02 — Segment-Specific Messaging Strategy Generator for future campaign refinement
- **Parent section:** 06-business-intelligence/README.md
- **Library index:** README.md
