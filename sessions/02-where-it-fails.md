# Block 2: Where it fails

Status: draft
Time: 9:45–10:45 (60 min) · Talk 21 / do 39
Outcomes: LO1, LO4

## Purpose

This audience does research and analysis, so the failures that matter most to
them are wrong numbers, invented sources, and claims about cause that the
evidence doesn't support. They hunt for all three in a ChatGPT-written briefing
paper, competitively, and then find out whether ChatGPT could have caught them
itself.

## Outline

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–12 | Failure modes for analysts | Talk | Table below. One example each, from a real-looking analytic product. Ask after each: *have you seen this in a colleague's draft?* |
| 12–35 | **Hallucination Hunt** | Teams | [Activity 2a](../activities/2a-hallucination-hunt.md). A ChatGPT briefing paper against its source data. Points for real errors, a penalty for false accusations |
| 35–40 | Hunt debrief | Room | Scores to the board. Which error did nobody find? Which correct statement got wrongly accused, and why? |
| 40–45 | **Machine vs. Hunters** | Teams | Test prompt **T2.1**: each team asks ChatGPT to find the errors in the same paper, then scores it by the same rules. *Did it beat you?* |
| 45–51 | **Two Truths and an AI** | Teams | [Activity 2b](../activities/2b-two-truths-and-an-ai.md). Three two-minute rounds; teams pick the fabrication with A/B/C cards |
| 51–57 | **The "are you sure?" demo** | Live demo, room predicts | Behaviour tests **T2.2–T2.4**. See below |
| 57–60 | Bridge | Instructor | *"Most of these problems start with what the prompt left out. After the break we fix the prompt."* |

All prompts for this block: [../prompts/block-2.md](../prompts/block-2.md).

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

## Machine vs. Hunters: what to draw out (5 min)

ChatGPT usually catches several of the planted errors and misses or misjudges at
least one, often the arithmetic or the causal claim. Sometimes it flags a correct
statement. Whatever happens, the conclusion is the same: **a check prompt is a
useful second pair of eyes, never the only pair.** If it scores higher than a
team, say so with good humour, and ask whether the team would have trusted its
answer without having done the hunt first.

## The "are you sure?" demo (6 min)

Run live in the public ChatGPT. Before each step, teams predict with cards.

1. **T2.2**, new chat: the survey data plus a **leading** question that assumes
   a ticketing system the data never mentions.
2. **T2.3**, a different new chat: same data, **neutral** question.
3. **T2.4**, back in the first chat: *"Are you sure?"*

Discuss: the leading question often gets agreement; the neutral one usually gets
a more careful answer; "are you sure?" can make it flip either way, and flipping
isn't checking. **Never promise the room a particular result.** If the outputs
don't show the effect, say so; that variability is itself the point.

## Materials

- Activity 2a handout (source data and briefing paper), one per learner
- [Block 2 prompts](../prompts/block-2.md), open digitally: T2.1–T2.4, P2.1 for
  fast teams
- Activity 2b rounds on slides or cards
- A/B/C voting cards; scoreboard

## Check for understanding

Every team finds at least four of the six planted errors in the Hunt, and can say
in one sentence why T2.1 doesn't replace checking yourself.

## If you're behind

Cut 1 in [../schedule.md](../schedule.md): Two Truths drops to one round.
**Never cut the Hunt or Machine vs. Hunters.**
