# 03 Iterate and verify

Status: draft
Time: 12:45–14:00 (75 min) · Talk 15 / do 60
Outcomes: LO3, LO4

## Purpose

First outputs are rarely final. Learners practise improving a result on purpose,
checking it against the source, and deciding what should never have been pasted
in the first place.

## By the end of this session, learners can…

- Diagnose what's wrong with an output and change the prompt to fix it, keeping
  a record of what each change did (LO3).
- Catch requirements an output dropped or changed by checking it against the
  source (LO4).
- Spot sensitive information in source material before it goes into a tool or a
  document (LO4).

## Outline

**Start hands-on.** Straight after lunch is the worst time for a lecture, so the
short teaching point comes in the middle, after scenario A has given it
something to answer.

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–3 | Brief | Instructor | Scenario A on paper and screen. Show the iteration log; it's required |
| 3–28 | Scenario A | Pairs | [Plain-language rewrite](../activities/3a-plain-language-rewrite.md): a dense grant-reporting paragraph rewritten for small-business grant recipients. At least three rounds, logged |
| 28–35 | Debrief | Room | Which requirement did the tool most often drop or change? (Usually "calendar days", the 10-business-day notice, or "may" becoming "will".) What change to the prompt fixed it? |
| 35–45 | Five refinement moves | Lecture | See below |
| 45–68 | Scenario B | Tables | [Meeting notes to a BLUF memo](../activities/3b-meeting-notes-to-memo.md). No step-by-step help. The notes include a medical-leave detail and a "don't share" budget figure |
| 68–75 | Debrief | Room | *What did you take out before pasting, and what did you leave out of the memo? Why?* Then: *did the tool invent a decision that wasn't made?* |

## Talking points: five refinement moves (10 min)

Introduce each with a failure the room saw in scenario A.

1. **Point at the problem, don't start over.** "The second bullet changed
   'calendar days' to 'days'. Restore the exact wording." A specific follow-up
   beats re-running the same prompt.
2. **Show an example.** Paste one paragraph in the style you want. Examples
   control tone and format better than adjectives do.
3. **Ask it to ask you first.** "Before drafting, ask me up to five questions
   about anything you need to know." Good for tasks where you don't know what's
   missing.
4. **Break it into steps.** "First list every requirement in the source. Then
   rewrite. Then confirm each requirement appears in the rewrite." Each step can
   be checked.
5. **Ask for a self-check, then check the check.** "List anything you changed
   or removed from the source." Useful, but the tool can miss its own errors.
   You still compare against the source.

And when to **start a fresh conversation**: when it keeps repeating an earlier
mistake, or when you're switching tasks. Old context keeps steering it.

## Materials

- Scenario A and B handouts, one per learner (each includes its source text)
- Job aid from Session 02
- Slides: `materials/slides/03-iterate-and-verify.*` [TODO]

## Check for understanding

- **Scenario A:** every pair's final version keeps all eight requirements in the
  answer key, and their log shows at least one change that fixed a specific
  problem.
- **Scenario B:** collect each table's final memo (photo or paste). It should
  have no medical detail, should handle the budget figure deliberately, and
  should list the reminder-email timing as an open decision, not a made one.

## Common problems

| Problem | Response |
| --- | --- |
| Pairs re-run the same prompt hoping for better | "What exactly is wrong? Tell it that" |
| Logs are empty because they're "just trying things" | The log is the deliverable. One line per round is enough |
| Someone pastes the notes without reading them first | Exactly the habit scenario B is built to break. Make it a debrief point, kindly and without naming anyone |

## If you're behind

Cut 2 in [../schedule.md](../schedule.md): scenario B becomes take-home work.
**Still make its data point out loud**: read the medical-leave line from the
notes and ask the room whether it should go into a tool or a memo.
