# Block 2: Where it fails

Status: draft
Time: 9:45–10:45 (60 min) · Talk 23 / do 37
Outcomes: LO1, LO4

## Purpose

This audience does research and analysis, so the failures that matter most to
them are wrong numbers, invented sources, and claims about cause that the
evidence doesn't support. They hunt for all three in a ChatGPT-written briefing
paper, competitively.

## Outline

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–12 | Failure modes for analysts | Talk | Table below. One example each, from a real-looking analytic product. Ask after each: *have you seen this in a colleague's draft?* |
| 12–35 | **Hallucination Hunt** | Teams | [Activity 2a](../activities/2a-hallucination-hunt.md). A ChatGPT briefing paper against its source data. Points for real errors, a penalty for false accusations |
| 35–41 | Hunt debrief | Room | Scores to the board. Which error did nobody find? Which correct statement got wrongly accused, and why? |
| 41–49 | **Two Truths and an AI** | Teams | [Activity 2b](../activities/2b-two-truths-and-an-ai.md). Three lightning rounds; teams pick the fabrication with A/B/C cards |
| 49–57 | **The "are you sure?" demo** | Live demo, room predicts | See below |
| 57–60 | Bridge | Instructor | *"Most of these problems start with what the prompt left out. After the break we fix the prompt."* |

## Failure modes for analysts (12 min)

| Failure | What it looks like in your work | What you do |
| --- | --- | --- |
| Invented sources | A report, author, or statistic that doesn't exist, or exists but doesn't say that | Find the source yourself, every time |
| Changed numbers | 1,240 becomes 1,420; percentages and percentage points confused | Check every figure against the data |
| Wrong arithmetic | "Fell by more than half" when it fell by 29% | Recompute anything that matters |
| Overclaiming cause | "This shows the new system caused the improvement" | Ask: what does the evidence actually support? |
| Drift in summaries | The top finding quietly becomes a different finding | Compare the summary to the source, line by line |
| Agreeing with you | You suggest a conclusion; it supports it | Ask neutral questions |
| Out of date | Last year's guidance described as current | Give it the current text |

## The "are you sure?" demo (8 min)

Run live in the learners' ChatGPT. Before each step, teams predict with cards
what will happen.

1. Paste the survey source data from activity 2a. Ask a **leading** question:
   *"Satisfaction went up 7 points, which shows the new ticketing system worked,
   right?"* (The data never mentions a ticketing system.)
2. In a **new chat**, same data, **neutral** question: *"What can and can't we
   conclude from these results about why satisfaction changed?"*
3. Back in the first chat, ask: *"Are you sure?"*

Discuss: the leading question often gets agreement; the neutral one usually gets
a more careful answer; "are you sure?" can make it flip either way, and flipping
isn't checking. **Never promise the room a particular result.** If the outputs
don't show the effect, say so; that variability is itself the point.

## Materials

- Activity 2a handout (source data and briefing paper), one per learner
- Activity 2b rounds on slides or cards
- A/B/C voting cards; scoreboard

## Check for understanding

Every team finds at least four of the six planted errors in the hunt. If most
teams miss the arithmetic error, add two minutes on recomputing claims.

## If you're behind

Cut 1 in [../schedule.md](../schedule.md): Two Truths drops to one round.
**Never cut the Hunt.**
