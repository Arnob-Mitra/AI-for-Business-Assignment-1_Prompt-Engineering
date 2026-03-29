# 📚 Prompt Library — EdTech Workflow Automation

> **Assessment 1 | Generative AI for Business**  
> Student: Arnab Mitra Utsab | Business Field: EdTech  
> Model tested on: GPT-4.1 Mini / GPT-5.4 Thinking  
> Last updated: March 2026

---

## What This Library Does

This prompt library supports workflow automation in an **EdTech organisation**. It contains **10 documented, tested, and iterated prompts** organised by the business function they support.

The library is designed for a digital education business offering services such as IELTS preparation, student support, learner communication, campaign promotion, and internal operational coordination. The prompts are intended to reduce repetitive manual work, improve communication consistency, support faster campaign execution, and help teams work more efficiently.

Each prompt entry follows the same structure:
- The exact prompt text (with placeholders where relevant)
- The workflow task it supports
- The problem it solves
- Its automation potential
- Known risks and mitigations
- Version history and test results

---

## 📂 Folder Structure

```text
prompt-library/
│
├── README.md
│
├── 01-brand-marketing/
│   ├── README.md
│   ├── P01-social-media-caption-generator.md
│   └── P02-segment-specific-messaging-strategy-generator.md
│
├── 02-hr/
│   ├── README.md
│   ├── P03-employee-announcement-email-generator.md
│   └── P04-monthly-salary-update-email-generator.md
│
├── 03-product-team/
│   ├── README.md
│   ├── P05-student-feedback-insight-summarizer.md
│   └── P06-feature-requirement-draft-generator.md
│
├── 04-digital-marketing/
│   ├── README.md
│   └── P07-push-notification-generator.md
│
├── 05-strategy/
│   ├── README.md
│   └── P08-competitor-campaign-analysis-generator.md
│
├── 06-business-intelligence/
│   ├── README.md
│   └── P09-campaign-performance-insight-generator.md
│
└── 07-graphics-and-design/
    ├── README.md
    └── P10-creative-design-brief-generator.md
```

> 💡 Folder and file names can be adjusted slightly to match your final submission style.  
> The key requirement is that the library remains clearly organised by business function.

---

## 📊 Library Summary Table

| ID | Prompt Name | Workflow | Automation Level | Risk Level | Status |
|----|-------------|----------|-----------------|------------|--------|
| P01 | Social Media Caption Generator | Brand Marketing | High | Medium | ✅ Tested |
| P02 | Segment-Specific Messaging Strategy Generator | Performance / Brand Marketing | Medium | Medium | ✅ Tested |
| P03 | Employee Announcement Email Generator | HR Communication | High | Low | 🔄 In progress |
| P04 | Monthly Salary Update Email Generator | HR Communication | Medium | High | 🔄 In progress |
| P05 | Student Feedback Insight Summarizer | Product Team | Medium | Medium | 🔄 In progress |
| P06 | Feature Requirement Draft Generator | Product Team | Medium | Medium | 🔄 In progress |
| P07 | Push Notification Generator | Digital Marketing | Very High | Medium | 🔄 In progress |
| P08 | Competitor Campaign Analysis Generator | Strategy | Medium | Medium | 🔄 In progress |
| P09 | Campaign Performance Insight Generator | Business Intelligence | High | Medium | 🔄 In progress |
| P10 | Creative Design Brief Generator | Graphics and Design | High | Low | 🔄 In progress |

**Automation levels:** Very High / High / Medium / Low  
**Risk levels:** High (always needs human review) / Medium (spot-check and approval required) / Low (can be used with light review)

---

## 🔗 Prompt Chaining Map

Some prompts in this library are designed to work in sequence. The chains below show how outputs from one prompt can support later tasks.

```text
CAMPAIGN CONTENT CHAIN
P02 (Segment Messaging Strategy) → P01 (Social Media Caption Generator) → P10 (Creative Design Brief Generator)

PRODUCT IMPROVEMENT CHAIN
P05 (Student Feedback Insight Summarizer) → P06 (Feature Requirement Draft Generator)

DIGITAL CAMPAIGN CHAIN
P02 (Segment Messaging Strategy) → P07 (Push Notification Generator) → P09 (Campaign Performance Insight Generator)
```

These prompt chains demonstrate how AI prompting can support not only isolated tasks, but also connected workflow stages across an EdTech organisation.

---

## ⚙️ Prompting Strategies Used

| Strategy | Prompts | Why chosen |
|----------|---------|------------|
| Role prompting | P01, P02, P03, P07, P10 | Defines a clear business role such as copywriter, strategist, HR officer, or design planner |
| Audience/context grounding | P01, P02, P07, P08 | Improves relevance by specifying learner segment, market context, or campaign purpose |
| Format and word limits | P01, P03, P04, P07, P10 | Makes output more production-ready and reduces editing time |
| Structured output sections | P02, P05, P06, P08, P09 | Ensures outputs are practical for planning, review, and business use |
| Risk-control constraints | P01, P02, P04, P08 | Reduces exaggerated claims, unsupported assumptions, or policy-sensitive wording |
| Iterative refinement | All | Improves quality through testing, review, and version updates |

---

## 📝 Iteration Evidence

All prompt versions are stored in this library. Each prompt file includes version notes that describe:
- what changed
- why the change was made
- what effect it had on output quality
- what was learned from testing

This version tracking shows the development of prompts from initial draft to more business-ready versions.

| Prompt | Versions | Key improvement |
|--------|----------|-----------------|
| P01 | v1.0 → v1.2 | Added audience pain points, angle-based variation, and stronger tone control |
| P02 | v1.0 → v1.1 | Shifted from general strategy framing to EdTech-specific segment planning |
| P07 | v1.0 → v1.1 | Added tighter output limits and campaign relevance for push messaging |
| P10 | v1.0 → v1.1 | Improved brief structure for easier use by designers |

---

## 📈 Business Value of the Library

This prompt library is designed to create value across multiple business functions in an EdTech organisation.

Expected benefits include:
- faster content and message generation
- more consistent communication quality
- reduced manual drafting time
- better support for audience targeting and campaign planning
- faster conversion of feedback into product insights
- improved coordination between marketing, product, BI, HR, and design teams

The prompts are intended to support staff in producing high-quality first drafts and structured planning outputs. They are not designed to replace human review or business judgment.

---

## ⚠️ Governance and Responsible Use

This library should be used with clear human oversight.

Recommended rules:
- All external-facing content should be reviewed before publishing
- Payroll, HR, and internal communication outputs should be checked for privacy and policy compliance
- Strategy and BI outputs should be validated against real business data
- Product-related prompts should support planning, not replace stakeholder discussion
- Sensitive or confidential information should not be entered into AI tools without appropriate approval

AI prompting is most effective when used as a workflow support tool, not as a fully autonomous decision-maker.

---

