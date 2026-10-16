# AI and LLM Prompt Engineering for Federal Professionals

A one-day course with six hours of instruction for US federal employees who are
new to ChatGPT. The learners are degree-holding professionals whose work is
research, analysis, report writing, and briefings. They leave able to use
ChatGPT for three everyday tasks: **a meeting agenda with action items, a project
implementation checklist, and a clear reply to a confusing email.** They'll also
know how to check what comes back, and what never to paste in.

> **Status: draft.** Every block, activity, handout, and check has content. Open
> items are in [BRIEF.md](BRIEF.md), section 1. The most important is **which
> version of ChatGPT** learners will use, and what information their agency has
> approved it for.

## The day

8:30–16:30: six hours of instruction, a one-hour lunch, and four 15-minute
breaks. Six 60-minute blocks, and no PowerPoint lectures: most of the screen time
is ChatGPT, live.

| Time | Block | Hands-on centrepiece | Outcomes |
| --- | --- | --- | --- |
| 8:30 | [1 First contact](sessions/01-first-contact.md) | *Human or Machine?* · same prompt, different answers | LO1, LO4 |
| 9:30 | Break | | |
| 9:45 | [2 Where it fails](sessions/02-where-it-fails.md) | *Hallucination Hunt* · *Two Truths and an AI* | LO1, LO4 |
| 10:45 | Break | | |
| 11:00 | [3 Meeting agendas: the five-part prompt](sessions/03-meeting-agendas.md) | *Worst Prompt Contest* · *Prompt Makeover Relay* | LO2 |
| 12:00 | Lunch | | |
| 13:00 | [4 Clear email responses: iterate](sessions/04-clear-email-responses.md) | *Email from Chaos* · *Reverse-Engineer the Prompt* | LO3 |
| 14:00 | Break | | |
| 14:15 | [5 Implementation checklists: build, red-team, brief](sessions/05-implementation-checklists.md) | *Red Team* · *Elevator Briefing* | LO2–LO4 |
| 15:15 | Break | | |
| 15:30 | [6 Your prompt card and close](sessions/06-prompt-card-and-close.md) | Prompt card · gallery walk | All |
| 16:30 | End | | |

Timing, clock checkpoints, and what to cut if you run long:
[schedule.md](schedule.md). How the games run, the team scoreboard, supplies,
and more ideas: [instructor/engagement-playbook.md](instructor/engagement-playbook.md).

## Learning outcomes

By the end of the day, learners can:

- **LO1** Explain in plain terms how ChatGPT produces a response, and predict
  where it's likely to be wrong.
- **LO2** Write a structured prompt (task, context, audience, format,
  guardrails) for a meeting agenda, an implementation checklist, or an email
  response.
- **LO3** Improve a weak output with targeted follow-ups instead of starting over.
- **LO4** Use ChatGPT responsibly at work: decide what information may go in,
  verify outputs before using them, and stay accountable for the result.

## What's here

```
BRIEF.md          Audience, outcomes, scope, logistics, and what's still open
schedule.md       Timed plan, checkpoints, cut list, outcome coverage
sessions/         One file per 60-minute block, minute by minute
activities/       Every game and exercise: instructor notes, learner handout, answer key
instructor/       Engagement playbook, federal context to confirm, prep timeline, run sheet
learners/         Pre-course email, agenda handout, follow-up email
assessment/       Pre/post check (with answers) and feedback form
materials/        Job aids and print list; slides go here once built
templates/        Start new sessions and activities from these
```

## Before you teach it

1. Settle the open questions in [BRIEF.md](BRIEF.md), the ChatGPT version first.
2. Confirm [instructor/federal-context.md](instructor/federal-context.md) with
   the host agency.
3. **Generate the pre-made outputs** for *Human or Machine?* and
   *Reverse-Engineer the Prompt* in the learners' version of ChatGPT (see
   [instructor/prep-timeline.md](instructor/prep-timeline.md)).
4. Run every activity yourself. ChatGPT's answers vary, so expect differences
   from the examples.
5. Build the few slides you need (see the slide budget in the engagement
   playbook).

To list everything still open: `grep -rn "TODO" --include="*.md" .`

## Design rules

- **No death by PowerPoint.** About a quarter of the day is talk (26%), and no talk
  segment runs past 12 minutes. Every block opens with something learners do,
  not a slide of objectives.
- **Their work, invented data.** Every example is a task these learners do
  (agendas, checklists, emails, analysis, briefings), and every name, figure,
  and document is fabricated.
- **Play with a point.** Each game teaches one thing, and the debrief says what.
  A team scoreboard runs all day.
- **Safety from minute one.** Data rules come before anyone types, and are
  practised in Blocks 2 and 5, not just stated.
