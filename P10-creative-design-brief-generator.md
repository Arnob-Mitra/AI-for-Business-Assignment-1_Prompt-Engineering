# P10 · Creative Design Brief Generator

**Section:** 07 — Graphics and Design  
**Workflow step:** Step 1 of 1 (supports campaign creative planning and design execution)  
**Current version:** v1.1  
**Status:** ✅ Ready for testing  
**Last updated:** March 2026

---

## 📌 Prompt Text (v1.1 — current)

```text
You are a creative strategist for the graphics and design team of an EdTech company.

Create a clear design brief for a campaign creative.

Input:
- campaign or creative title: [TITLE]
- campaign objective: [OBJECTIVE]
- target audience: [AUDIENCE]
- key message or offer: [KEY_MESSAGE]
- platform or format: [PLATFORM]
- visual tone or brand style: [VISUAL_STYLE]
- call-to-action: [CTA]
- any important notes or constraints: [NOTES]

Requirements:
- Write in a structured design-brief format
- Clearly explain what the creative needs to communicate
- State the target audience and desired response
- Mention the recommended tone and visual direction
- Include the core message and CTA
- Include any practical constraints relevant to the designer
- Keep the language clear, concise, and collaboration-friendly
- Do not invent brand claims or campaign details that were not provided

Output format:
1. Creative title
2. Objective
3. Target audience
4. Key message
5. Platform / format
6. Visual direction
7. CTA
8. Notes / constraints
9. Why this brief is useful for the design team
```

---

## 🏢 Intended Workflow or Task

This prompt supports the graphics and design team by turning campaign inputs into a clearer creative brief that can guide visual production.

- **Trigger:** A campaign concept, message direction, or marketing need has already been approved
- **Actor:** Brand marketer, creative strategist, or campaign owner runs the prompt
- **Timing:** Before a designer starts creating banners, social visuals, ad creatives, or promotional assets
- **Next step:** Designer reviews the brief and begins concept development or asset production

```text
P02 defines segment message direction → P01 creates caption directions → [P10 RUNS]
    → Design brief created → Graphics/design team produces creative assets
```

---

## ❗ Problem Being Solved

Design teams often receive incomplete or inconsistent creative requests. A marketer may know the campaign goal and message, but the brief shared with the designer may miss important context such as the audience, CTA, platform, or visual direction. This leads to delays, rework, and misalignment between strategy and creative execution.

This prompt helps standardize creative briefing so that design teams receive clearer instructions. It improves collaboration between marketing and design and reduces the effort needed to convert campaign ideas into workable design tasks.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|-----------|------------|
| Repetitiveness | High — creative briefs are needed repeatedly for campaigns and assets |
| Data availability | High — campaign inputs are usually available from marketing planning |
| Human judgment needed | Medium — final creative direction still needs team review |
| Integration possibility | Output can support task management tools, design briefs, and approval workflows |
| Estimated value | Saves briefing time and improves creative alignment |

**Human-in-the-loop role:** Marketers and designers should review the brief together before execution to confirm brand fit, feasibility, and design priorities.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|-------|------------|
| Brief is too generic for complex campaigns | Medium | Add stronger campaign context and design constraints when needed |
| Visual direction is too vague | Medium | Include brand style, examples, and asset purpose in the input |
| Creative claims or details are assumed | Medium | Prompt explicitly avoids inventing information not provided |
| Brief is followed without creative discussion | Low to Medium | Use the output as a starting point, not a replacement for team collaboration |

**Overall risk rating: MEDIUM** — strong for briefing support, but still needs human discussion and approval.

---

## 🔄 Version History

### v1.0 — Initial draft
**Date:** March 2026  
**Prompt:** Write a design brief for a campaign creative.  
**Output:** Produced a simple brief, but it was too general and often missed platform context, audience detail, or execution constraints.  
**Observed effect:** Useful for idea capture, but not strong enough for direct design handoff.  
**Lesson learned:** Design prompts need structured fields so creative teams receive practical, execution-ready information.

---

### v1.1 — Structured creative briefing version ✅ Current
**Date:** March 2026  
**Change:** Added inputs for audience, key message, platform, visual tone, CTA, and constraints; required a structured brief output.  
**Output:** Briefs became clearer, more useful for designers, and better aligned with campaign planning.  
**Observed effect:** Improved collaboration between marketing and design, with less rework at the briefing stage.  
**Lesson learned:** Structured AI briefs are most useful when they translate campaign thinking into practical design instructions.

---

## 🔗 Related Prompts

- **Upstream prompts:** P02 — Segment-Specific Messaging Strategy Generator; P01 — Social Media Caption Generator
- **Related workflow:** Campaign creative development, design handoff, asset production
- **Parent section:** 07-graphics-and-design/README.md
- **Library index:** README.md
