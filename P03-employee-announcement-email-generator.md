# P03 · Employee Announcement Email Generator

**Section:** 02 — HR  
**Workflow step:** Step 1 of 2 (feeds into manager review → staff distribution)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are an HR communications officer for an EdTech company.

Write a professional internal announcement email for employees.

Context to include:
- announcement topic: [TOPIC]
- purpose of the announcement: [PURPOSE]
- target staff group: [AUDIENCE]
- effective date or timeline: [DATE_OR_TIMELINE]
- action required from staff: [ACTION_REQUIRED]
- sender/team name: [SENDER]

Requirements:
- Keep the tone professional, clear, supportive, and concise
- Write for internal staff communication, not external marketing
- Include a clear subject line
- Start with a short introduction explaining the announcement
- Explain what is changing or being communicated
- Mention the timeline or effective date clearly
- State any action staff need to take
- End with a polite closing
- Keep the email between 150 and 220 words
- Do not include information that is not provided

Output format:
Subject line
Email body
Reason this version works for internal communication
```

---

## 🏢 Intended Workflow or Task

Step 1 of a 2-step HR communication workflow.

- **Trigger:** HR or operations team needs to communicate an internal update to staff
- **Actor:** HR officer or admin staff member runs the prompt
- **Timing:** When a policy reminder, operational update, deadline notice, or company announcement needs to be distributed
- **Next step:** Manager or HR lead reviews the draft before email distribution

```text
HR update identified → HR officer enters details → [P03 RUNS]
    → Draft internal email created → HR/manager reviews
    → Final version sent to staff
```

---

## ❗ Problem Being Solved

Internal announcements are necessary but repetitive. HR teams often need to draft professional messages for staff updates, deadlines, process changes, policy reminders, or event notices. Writing these emails manually each time takes time and can lead to inconsistency in tone, structure, and clarity.

This prompt helps HR staff create clear first-draft announcement emails more efficiently, reducing repetitive writing effort while supporting a more consistent internal communication style.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — internal updates happen frequently |
| Data availability | High — HR usually has the needed factual details |
| Human judgment needed | Medium — draft must still be reviewed before sending |
| Integration possibility | Output can be copied directly into email workflows |
| Estimated value | Saves drafting time and improves consistency of internal communication |

**Human-in-the-loop role:** HR or a manager should review all emails before sending, especially where policy wording, deadlines, or employee expectations are involved.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Email includes vague or incomplete instructions | Medium | Prompt requires action, timeline, and purpose fields |
| Tone feels too generic or robotic | Low to Medium | Human review and light editing before distribution |
| Missing context leads to unclear communication | Medium | Prompt includes placeholders to ensure key facts are entered |
| Sensitive policy language handled poorly | Medium | Final review by HR/manager required before sending |

**Overall risk rating: MEDIUM** — safe for first-draft internal communication, but final review is required.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Write an internal announcement email for staff about [TOPIC].  
**Output:** Produced usable email text, but lacked structure, sometimes missed timelines, and did not consistently include staff actions.  
**Observed effect:** Helped reduce drafting time, but required too much manual correction.  
**Lesson learned:** Internal communication prompts need stronger structure and explicit placeholders to produce reliable outputs.

---

### v1.1 — Structured HR communication version ✅ Current
**Date:** March 2026  
**Change:** Added placeholders for purpose, audience, date, action, and sender; included tone, length, and format requirements.  
**Output:** Emails became clearer, more complete, and easier to review before sending.  
**Observed effect:** Improved consistency and reduced editing effort.  
**Lesson learned:** Placeholder-driven prompts are more reliable for internal operational communication than broad open-ended prompts.

---

## 🔗 Related Prompts

- **Next in chain:** Manager review / final staff distribution
- **Related prompt:** P04 — Monthly Salary Update Email Generator
- **Parent section:** 02-hr/README.md
- **Library index:** README.md
