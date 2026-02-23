# Patient Intake Portal — Problem Framing to JTBD

> **Branch:** `skill/problem-jtbd`
> **Skills:** D1 · D2 · D4 · R1
> **Audience:** PM · UX

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 10: Patient Intake Portal |
| **Session** | Problem Framing to JTBD |
| **Skills** | D1 · D2 · D4 · R1 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/6krs1bo2ojijvks |
| **Miro Board** | https://miro.com/app/board/uXjVG8Qut6s%3D/ |

### Session Timing

| Time | Activity |
|------|----------|
| 0:00–0:15 | Concept framing — open the Gamma slide deck and walk through each slide |
| 0:15–0:30 | Orient to Miro board + this starting state |
| 0:30–1:05 | Step 1 exercise (Miro — Context frame) |
| 1:05–1:25 | Step 2 exercise (Miro — Exercise frame) |
| 1:25–1:30 | Step 3 wrap-up |
| 1:30–1:50 | Debrief — use Miro Debrief frame prompts |
| 1:50–2:00 | Extension brief — point to Extension Zone in Miro |

### What to Watch For

- Stakeholder maps that only include direct users — compliance and legal are stakeholders too
- Problem statements that describe symptoms ("forms are slow") not root causes
- JTBD statements that are really feature requests in disguise

### Facilitation Tips

- For problem statements: "Why does that matter? And why does THAT matter?" — go 3 levels deep
- Stakeholder map: "Who could block this project if they didn't approve it?" — surfaces hidden stakeholders
- At debrief: rank the JTBDs by frequency × severity. Which one surprises the group most?

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-patient-intake
git checkout skill/problem-jtbd
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/6krs1bo2ojijvks
- **Miro Board:** https://miro.com/app/board/uXjVG8Qut6s%3D/

### What You'll Practice

- D1
- D2
- D4
- R1

### Your Starting State

You have:
- `research/stakeholder-interviews.md` — 6 interviews (patients, nurses, admin staff)
- `research/current-intake-form.md` — description of the current paper form

Your goal: map stakeholders, write a 3-level problem statement, and rank 5 JTBDs.

### Step by Step

**Step 1:** Map all stakeholders: primary users, secondary users, system owners, compliance stakeholders. Identify the "real" customer vs. the "paying" customer.

**Step 2:** Write a 3-level problem statement: "The root cause is ____, which means ____, which means ____."

**Step 3:** Extract 5 JTBDs from the interviews. Rank by frequency × severity. Which one is the must-solve?

### What Good Looks Like

A stakeholder map that includes at least one stakeholder nobody initially mentioned. A problem statement that makes the group say "yes, that's the real issue."

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Design 3 interview questions specifically targeting the highest-ranked JTBD
- Research one HIPAA constraint that would affect your top feature idea
- Your stakeholder map and JTBD analysis feed Session 2

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
