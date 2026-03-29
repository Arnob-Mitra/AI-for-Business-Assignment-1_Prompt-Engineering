# P01 · Social Media Caption Generator

**Section:** 01 — Brand Marketing  
**Workflow step:** Step 1 of 3 (feeds from segment messaging strategy → into creative brief development)  
**Current version:** v1.1  
**Status:** ✅ Tested  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a senior brand marketing copywriter for an EdTech company in South Asia.

Generate 5 high-quality Facebook and Instagram captions promoting an IELTS preparation course for students who want to study abroad.

Audience profile:
- Age: 17–25
- Students from Bangladesh or similar South Asian markets
- Concerned about IELTS score, confidence, and admission preparation
- Want affordable, practical, and supportive learning help

Requirements:
- Each caption must be 45–65 words
- Tone: motivating, clear, trustworthy, youth-friendly
- Include one strong but natural CTA
- Mention one learner pain point and one hopeful outcome
- Do not use fake urgency or unrealistic claims
- Avoid repetitive wording across options

Output format for each option:
- Caption
- Headline
- CTA
- Why this version may appeal to the target audience
```

---

## 🏢 Intended Workflow or Task

Step 1 of a 3-prompt brand marketing chain.

- **Trigger:** Brand marketing team needs campaign-ready social media copy for an IELTS preparation course
- **Actor:** Brand marketer or content executive runs the prompt to generate first-draft caption options
- **Timing:** During campaign content development for Facebook and Instagram
- **Next step:** Selected message direction can feed into creative briefing and design execution

```text
P02 (Segment Messaging Strategy) defines message direction → [P01 RUNS]
    → Caption options reviewed by marketer
    → Selected direction feeds into P10 (Creative Design Brief Generator)
```

---

## ❗ Problem Being Solved

Brand marketing teams often spend too much time drafting multiple caption options for the same campaign. In an EdTech business, social media content needs to be persuasive, student-friendly, and consistent with brand tone. Writing from scratch for every campaign slows down execution and creates inconsistency across platforms.

This prompt helps generate structured first-draft captions more quickly, allowing the team to focus more on campaign selection, refinement, and final approval rather than starting from a blank page.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — social campaign captions are created frequently |
| Data availability | High — campaign offer, target audience, and tone are usually known |
| Human judgment needed | Medium — copy must still be reviewed for brand fit and quality |
| Integration possibility | Output can directly support campaign planning, scheduling, and content approval |
| Estimated value | Reduces ideation time and increases speed of content production |

**Human-in-the-loop role:** A marketer should review all caption options before publishing. AI generates first drafts, but final selection, editing, and approval remain human responsibilities.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Captions become repetitive across options | Medium | Prompt includes variation requirement and output review before use |
| Messaging may not fully match brand voice | Medium | Human editing required before publishing |
| Audience assumptions may be too broad | Medium | Prompt uses a defined learner profile, but should be refined further when needed |
| Over-promotional wording or weak realism | Medium | Explicit instruction added to avoid fake urgency and unrealistic claims |

**Overall risk rating: MEDIUM** — suitable for first-draft automation, but final publishing always requires review.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Basic social media caption generator for IELTS promotion  
**Output:** Captions were clear and professional, but too generic. The options sounded similar and lacked strong audience specificity.  
**Observed effect:** Useful as a starting point, but not strong enough for direct business use.  
**Lesson learned:** Campaign prompts need clearer audience context, stronger constraints, and more realistic brand guidance.

---

### v1.1 — Audience profile and quality constraints added ✅ Current
**Date:** March 2026  
**Change:** Added South Asian learner context, affordability concern, tone requirements, CTA guidance, pain point + hopeful outcome requirement, and an instruction to avoid repetitive wording.  
**Output:** Captions became more relevant, more targeted, and more useful for real campaign drafting.  
**Observed effect:** Improved audience fit and stronger variation across caption options, with better business relevance.  
**Lesson learned:** Audience detail and output constraints significantly improve the quality of promotional copy prompts.

---

## 🧪 Test Result Summary

The prompt generated five structured caption options, each with a headline, CTA, and short explanation of audience appeal. The outputs addressed common learner pain points such as low confidence, exam stress, unclear preparation strategy, and affordability concerns. The result was suitable for first-draft campaign ideation, although human review would still be required for final brand alignment and publication.

---

## 🔗 Related Prompts

- **Previous in chain:** P02 — Segment-Specific Messaging Strategy Generator
- **Next in chain:** P10 — Creative Design Brief Generator
- **Parent section:** 01-brand-marketing/README.md
- **Library index:** README.md
