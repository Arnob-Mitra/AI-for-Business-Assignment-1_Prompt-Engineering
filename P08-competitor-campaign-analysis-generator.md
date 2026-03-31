# P08 · Competitor Campaign Analysis Generator

**Section:** 05 — Strategy  
**Workflow step:** Step 1 of 1 (supports competitor review, market positioning, and campaign planning)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a strategy analyst for an EdTech company.

Analyze competitor campaign information and turn it into a structured strategic summary.

Input:
- competitor name: [COMPETITOR_NAME]
- campaign details, ad copy, offer, landing page notes, or promotion summary: [CAMPAIGN_DATA]
- product or course category: [CATEGORY]
- purpose of analysis: [ANALYSIS_OBJECTIVE]

Requirements:
- Summarize the competitor’s main campaign angle
- Identify the value proposition being emphasized
- Explain the likely target audience
- Highlight key promotional tactics or offer strategy
- Identify possible strengths in the campaign
- Identify possible weaknesses or gaps
- Suggest 2 to 3 strategic takeaways for our EdTech business
- Use clear business language
- Do not invent information not present in the input

Output format:
1. Executive summary
2. Main campaign angle
3. Value proposition
4. Likely target audience
5. Strengths
6. Weaknesses / gaps
7. Strategic takeaways
8. Why this analysis is useful for the strategy team
```

---

## 🏢 Intended Workflow or Task

This prompt supports strategy work by helping the team review competitor campaigns in a more structured way. It can be used when the business wants to understand how competitors position their offers, what messaging they emphasize, and where market opportunities may exist.

- **Trigger:** Strategy or leadership team wants to review a competitor campaign
- **Actor:** Strategy analyst, marketing lead, or business analyst runs the prompt
- **Timing:** During campaign planning, market review, or strategic discussion
- **Next step:** Findings may support messaging decisions, market positioning, or campaign direction

```text
Competitor campaign collected → Strategy analyst enters campaign details → [P08 RUNS]
    → Structured analysis created → Team reviews key takeaways
    → Strategic positioning or campaign decisions follow
```

---

## ❗ Problem Being Solved

Competitor campaigns often contain useful signals about audience targeting, offer design, message framing, and market positioning. However, competitor information is usually collected in an unstructured way, such as screenshots, ad copy notes, landing page summaries, or informal observations. This makes it harder to extract insights consistently and compare campaigns effectively.

This prompt helps turn unstructured competitor information into a clearer strategic summary. It supports faster analysis, better discussion quality, and more consistent market review.

---

## ⚡ Automation Potential

**Level: Medium**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | Medium — competitor analysis is recurring but not constant |
| Data availability | Medium — depends on how much campaign evidence is collected |
| Human judgment needed | High — strategic interpretation must be reviewed carefully |
| Integration possibility | Output can support market review docs, planning decks, and internal discussions |
| Estimated value | Saves analysis time and improves consistency of competitor review |

**Human-in-the-loop role:** Strategy and marketing leaders should validate all interpretations before acting on them. This prompt supports strategic thinking, but does not replace market research or executive judgment.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Competitor intent is over-interpreted from limited evidence | Medium | Use only collected input and validate against real market observations |
| Weak or incomplete campaign data reduces quality | Medium | Treat the output as a draft analysis, not a final conclusion |
| Strategic takeaways are too generic | Medium | Add clearer analysis objectives and stronger source material |
| Unsupported assumptions appear in the output | Medium | Prompt explicitly instructs the model not to invent information |

**Overall risk rating: MEDIUM** — useful for structured strategic review, but must be checked before decision-making.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Analyze a competitor campaign and summarize the key points.  
**Output:** Produced a broad overview, but lacked strategic structure and did not separate strengths, weaknesses, and takeaways clearly enough.  
**Observed effect:** Helpful for quick notes, but not strong enough for management discussion.  
**Lesson learned:** Strategy prompts need a more explicit analytical structure to become useful for business decisions.

---

### v1.1 — Structured competitor analysis version ✅ Current
**Date:** March 2026  
**Change:** Added input fields, clear analysis categories, value proposition focus, strengths/weaknesses structure, and strategic takeaway section.  
**Output:** Analysis became more useful for internal strategy discussion and campaign comparison.  
**Observed effect:** Improved clarity and reduced manual effort in organizing competitor insights.  
**Lesson learned:** Strategy prompts work best when they convert raw market observations into a consistent discussion format.

---

## 🔗 Related Prompts

- **Related workflow:** Market review, positioning discussion, campaign planning
- **Can support:** P02 — Segment-Specific Messaging Strategy Generator
- **Can influence:** P01 — Social Media Caption Generator and P10 — Creative Design Brief Generator
- **Parent section:** 05-strategy/README.md
- **Library index:** README.md
