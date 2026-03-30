# P06 · Feature Requirement Draft Generator

**Section:** 03 — Product Team  
**Workflow step:** Step 2 of 2 (feeds from feedback insight summary → into product review and prioritization)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a product manager for an EdTech company.

Create a first-draft feature requirement document based on the product insight summary provided.

Input:
- feature idea or issue title: [FEATURE_TITLE]
- related product area: [PRODUCT_AREA]
- product insight summary or user feedback summary: [INSIGHT_SUMMARY]
- business or user objective: [OBJECTIVE]
- target users: [TARGET_USERS]

Requirements:
- Write in a structured product-document style
- Clearly explain the user problem
- Describe the proposed feature or improvement
- State the expected user benefit
- State the expected business value
- Include key assumptions or dependencies
- Include possible risks or open questions
- Keep the draft practical for product team discussion
- Do not invent technical details that were not provided

Output format:
1. Feature title
2. Problem statement
3. Proposed feature / improvement
4. Target users
5. Expected user benefit
6. Expected business value
7. Assumptions / dependencies
8. Risks / open questions
9. Why this draft is useful for the product team
```

---

## 🏢 Intended Workflow or Task

Step 2 of a 2-step product workflow.

- **Trigger:** Product team identifies a recurring issue, opportunity, or requested improvement from student feedback
- **Actor:** Product manager, product analyst, or business analyst runs the prompt
- **Timing:** During early feature planning, backlog discussion, or sprint preparation
- **Next step:** Draft is reviewed, refined, and prioritized by the product team

```text
P05 (Student Feedback Insight Summarizer) identifies patterns → [P06 RUNS]
    → Feature requirement draft created → Product team reviews
    → Prioritization and planning discussion follows
```

---

## ❗ Problem Being Solved

Turning user feedback into a structured feature draft takes time and often depends on how clearly the problem has been documented. Product teams may recognize a recurring issue, but still need to translate it into a usable requirement draft that explains the user need, business value, assumptions, and risks.

This prompt helps bridge the gap between raw insights and feature planning. It makes early-stage product discussion faster and more structured by producing a consistent first draft that the team can review and refine.

---

## ⚡ Automation Potential

**Level: Medium**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | Medium — requirement drafting happens regularly but not at the same volume as messaging tasks |
| Data availability | Medium — depends on the quality of insight summaries and problem framing |
| Human judgment needed | High — product prioritization and feasibility decisions require human review |
| Integration possibility | Output can support backlog notes, requirement drafts, and product review documents |
| Estimated value | Saves planning time and improves consistency of early-stage requirement documentation |

**Human-in-the-loop role:** Product managers and stakeholders must review the draft before any roadmap, prioritization, or implementation decision is made.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Draft includes assumptions not validated by product data | Medium | Review assumptions during product planning discussion |
| Business value is overstated | Medium | Compare the draft against actual business priorities and evidence |
| Missing technical or operational constraints | Medium | Use prompt output only as a first draft, not a final requirement |
| User problem is framed too broadly | Medium | Provide stronger insight summaries and objective details in the input |

**Overall risk rating: MEDIUM** — useful for drafting and discussion support, but not a replacement for formal product requirement review.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Write a feature requirement draft based on feedback.  
**Output:** Produced a general idea summary, but lacked enough structure for real product planning.  
**Observed effect:** Useful for brainstorming, but not detailed enough for review meetings.  
**Lesson learned:** Product requirement prompts need explicit sections such as problem, user benefit, business value, and risks.

---

### v1.1 — Structured product requirement version ✅ Current
**Date:** March 2026  
**Change:** Added input fields, structured document sections, and explicit requirements for user benefit, business value, assumptions, and open questions.  
**Output:** Drafts became clearer, more discussion-ready, and more useful for backlog and prioritization conversations.  
**Observed effect:** Improved consistency and reduced manual effort in early requirement drafting.  
**Lesson learned:** Structured prompt outputs are more valuable for product teams than open-ended summarization.

---

## 🔗 Related Prompts

- **Previous in chain:** P05 — Student Feedback Insight Summarizer
- **Next in chain:** Product review, backlog prioritization, and feature planning
- **Parent section:** 03-product-team/README.md
- **Library index:** README.md
