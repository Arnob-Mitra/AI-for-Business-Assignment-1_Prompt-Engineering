# P04 · Monthly Salary Update Email Generator

**Section:** 02 — HR  
**Workflow step:** Step 2 of 2 (feeds into HR review → employee distribution)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are an HR payroll communications officer for an EdTech company.

Write a clear and professional monthly salary update email for an employee.

Context to include:
- employee name: [EMPLOYEE_NAME]
- month or pay period: [PAY_PERIOD]
- salary/payment status: [PAYMENT_STATUS]
- payment date: [PAYMENT_DATE]
- any important note: [IMPORTANT_NOTE]
- action required from employee, if any: [ACTION_REQUIRED]
- sender/team name: [SENDER]

Requirements:
- Keep the tone professional, respectful, and easy to understand
- Write for internal employee communication
- Include a clear subject line
- Mention the pay period and payment date clearly
- State the payment status in simple words
- Include any action required only if provided
- Avoid adding financial details that were not provided
- End with a polite closing
- Keep the email between 120 and 180 words

Output format:
Subject line
Email body
Reason this version works for payroll communication
```

---

## 🏢 Intended Workflow or Task

Step 2 of a 2-step HR communication workflow.

- **Trigger:** HR or payroll team needs to communicate a monthly salary or payroll-related update to an employee
- **Actor:** HR/payroll officer runs the prompt using approved payroll communication details
- **Timing:** At the time of salary processing, payment release, or payroll clarification
- **Next step:** HR or payroll lead reviews the email before it is sent to the employee

```text
Payroll update prepared → HR/payroll officer enters approved details → [P04 RUNS]
    → Draft salary update email created → HR/payroll review
    → Final version sent to employee
```

---

## ❗ Problem Being Solved

Salary update emails are repetitive but sensitive. HR or payroll teams often need to communicate payment status, timelines, or payroll-related notes clearly and professionally. Writing these messages manually each month takes time and increases the risk of inconsistent tone or unclear wording.

This prompt helps produce first-draft payroll communication more efficiently while maintaining a structured and respectful format. It supports consistency, saves drafting time, and reduces the burden of routine internal communication.

---

## ⚡ Automation Potential

**Level: Medium**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — salary-related updates may be sent regularly |
| Data availability | High — required details are usually available internally |
| Human judgment needed | High — payroll communication is sensitive and must be accurate |
| Integration possibility | Output can support email drafting workflows but not automatic sending |
| Estimated value | Saves drafting time and improves communication consistency |

**Human-in-the-loop role:** HR/payroll staff must verify all details before sending. This prompt should be used only for drafting, not for automatic communication without human approval.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Inaccurate or incomplete payroll wording | High | All emails must be reviewed against approved payroll records before sending |
| Confidential financial information handled carelessly | High | Prompt avoids adding details not explicitly provided; human review is mandatory |
| Tone may sound too generic for sensitive matters | Medium | HR/payroll staff can adjust tone before final distribution |
| Missing action or deadline creates confusion | Medium | Placeholder structure requires action and date fields when relevant |

**Overall risk rating: HIGH** — always requires human review and factual verification before use.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Write a monthly salary update email for an employee.  
**Output:** Produced a general email, but lacked clear structure and occasionally implied payroll details that were not specified.  
**Observed effect:** Draft was useful as a starting point, but not safe enough for direct use in payroll communication.  
**Lesson learned:** Sensitive HR prompts require stronger factual constraints and clearer placeholders.

---

### v1.1 — Structured payroll-safe version ✅ Current
**Date:** March 2026  
**Change:** Added placeholders for pay period, payment status, payment date, important note, and action required; included explicit instruction not to add financial details not provided.  
**Output:** Emails became clearer, safer, and more consistent for payroll communication use.  
**Observed effect:** Improved trustworthiness and reduced risk of unsupported wording.  
**Lesson learned:** For HR/payroll communication, constrained prompts are essential for responsible AI use.

---

## 🔗 Related Prompts

- **Previous in chain:** P03 — Employee Announcement Email Generator
- **Next in chain:** HR/payroll review and employee distribution
- **Parent section:** 02-hr/README.md
- **Library index:** README.md
