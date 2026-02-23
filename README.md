# Patient Intake Portal — Empathy to Flow

> **Branch:** `skill/empathy-flow`
> **Skills:** D5 · D6 · U1 · U2
> **Audience:** PM · UX

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 10: Patient Intake Portal |
| **Session** | Empathy to Flow |
| **Skills** | D5 · D6 · U1 · U2 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/cf5nh7hmo568mbx |
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

- IA that conflates what the patient sees with what staff sees — these are different products
- Flows that ignore the anxious first-time patient persona — push for the hardest user case
- Accessibility gaps: WCAG isn't optional in healthcare

### Facilitation Tips

- Ask: "What is Maria experiencing at this step?" (refer back to Session 1 interview) — keeps empathy concrete
- For IA: do a live card sort — write each data item on a sticky, then group them as a team
- At debrief: where does the nurse's flow and the patient's flow touch? Those are the highest-risk moments.

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-patient-intake
git checkout skill/empathy-flow
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/cf5nh7hmo568mbx
- **Miro Board:** https://miro.com/app/board/uXjVG8Qut6s%3D/

### What You'll Practice

- D5
- D6
- U1
- U2

### Your Starting State

You have:
- `session-1-output/jtbd-analysis.md` — JTBD rankings from Session 1
- `reference/hipaa-constraints.md` — key HIPAA constraints affecting UX

Your goal: empathy maps for 2 personas, IA for the portal, and flows for patient intake and staff review.

### Step by Step

**Step 1:** Build empathy maps for 2 personas: anxious first-time patient (Maria) and intake nurse (Diana).

**Step 2:** Design the IA: card sort the intake data into logical sections. What does the patient see vs. what staff sees?

**Step 3:** Sketch 3 flows: new patient first intake, returning patient update, staff viewing submitted forms.

### What Good Looks Like

Empathy maps where the "Thinks" and "Feels" quadrants reveal things the interviews hinted at but didn't say explicitly. An IA where the patient never sees clinical staff fields.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Add an accessibility audit checklist to your flow — mark every step that needs WCAG review
- Design the error states: form submission fails, patient leaves mid-form, session timeout
- Your flows feed Session 3

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
