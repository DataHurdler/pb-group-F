# AI and LLM Prompt Engineering for Federal Professionals

A one-day course with six hours of instruction for US federal employees who are
new to ChatGPT, using the public version running GPT-6. The learners are degree-holding professionals whose work is
research, analysis, report writing, and briefings. They leave able to use
ChatGPT for three everyday tasks: **a meeting agenda with action items, a project
implementation checklist, and a clear reply to a confusing email.** They'll also
know how to test a prompt before relying on it, check what comes back, and
what never to paste in.

> **Status: draft.** Every block, activity, prompt, handout, and check has
> content. Open items are in [BRIEF.md](BRIEF.md), section 1. The most important:
> **confirm the host agency permits the public ChatGPT** on the devices and
> network in the room, and confirm that "open source" meant the public version
> rather than a locally run open-weight model.

## The day

8:30–16:30: six hours of instruction, a one-hour lunch, and four 15-minute
breaks. Six 60-minute blocks, and no PowerPoint lectures: most of the screen time
is ChatGPT, live.

| Time | Block | Hands-on centrepiece | Outcomes |
| --- | --- | --- | --- |
| 8:30 | [1 First contact](sessions/01-first-contact.md) | *Human or Machine?* · same prompt, different answers · "what do you know?" test | LO1, LO4 |
| 9:30 | Break | | |
| 9:45 | [2 Where it fails](sessions/02-where-it-fails.md) | *Hallucination Hunt* · *Machine vs. Hunters* · *Two Truths and an AI* | LO1, LO4 |
| 10:45 | Break | | |
| 11:00 | [3 Meeting agendas: the five-part prompt](sessions/03-meeting-agendas.md) | *Worst Prompt Contest* · *Prompt Makeover Relay* · swap-card and empty-card tests | LO2, LO3 |
| 12:00 | Lunch | | |
| 13:00 | [4 Clear email responses: iterate](sessions/04-clear-email-responses.md) | *Email from Chaos* · coverage and different-email tests · *Reverse-Engineer the Prompt* | LO3 |
| 14:00 | Break | | |
| 14:15 | [5 Implementation checklists: build, red-team, brief](sessions/05-implementation-checklists.md) | Traceability test · *Red Team* · *Elevator Briefing* | LO2–LO4 |
| 15:15 | Break | | |
| 15:30 | [6 Your prompt card and close](sessions/06-prompt-card-and-close.md) | Prompt card tested on normal, messy, and missing-information inputs · gallery walk | All |
| 16:30 | End | | |

## Practice and test prompts

Every prompt the course uses is in the [prompt bank](prompts/README.md), ready to
copy: **practice prompts** (P) build a skill, often as weak/strong pairs; **test
prompts** (T) check an output, show how ChatGPT behaves, or test whether a
learner's prompt survives a messy or incomplete input. Each of Blocks 2–6 ends
its main activity with a test, so by Block 6 learners have tested prompts five
times before being taught the method by name. There's also a ten-prompt
[take-home set](prompts/take-home.md) for the week after.

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
- **LO3** Improve and test a prompt: targeted follow-ups instead of starting
  over, and checks on normal, messy, and missing-information inputs.
- **LO4** Use ChatGPT responsibly at work: decide what information may go in,
  verify outputs before using them, and stay accountable for the result.

## What's here

```
BRIEF.md          Audience, outcomes, scope, logistics, and what's still open
schedule.md       Timed plan, checkpoints, cut list, outcome coverage
sessions/         One file per 60-minute block, minute by minute
activities/       Every game and exercise: instructor notes, learner handout, answer key
prompts/          Prompt bank: practice and test prompts by block, test packs, take-home set
instructor/       Engagement playbook, federal context to confirm, prep timeline, run sheet
learners/         Pre-course email, agenda handout, follow-up email
assessment/       Pre/post check (with answers) and feedback form
materials/        Job aids and print list; slides go here once built
templates/        Start new sessions and activities from these
```

## Before you teach it

1. Settle the open questions in [BRIEF.md](BRIEF.md), permission for the public
   ChatGPT first.
2. Confirm [instructor/federal-context.md](instructor/federal-context.md) with
   the host agency.
3. **Generate the pre-made outputs** for *Human or Machine?* and
   *Reverse-Engineer the Prompt* in the public ChatGPT (see
   [instructor/prep-timeline.md](instructor/prep-timeline.md)).
4. Run every prompt in the bank yourself. ChatGPT's answers vary, so expect
   differences from the examples.
5. Put the prompt bank somewhere learners can open it and copy from it.
6. Build the few slides you need (see the slide budget in the engagement
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
- **Test, don't trust.** Every main activity ends by testing the output or the
  prompt. The habit matters more than any single technique.
- **Safety from minute one.** Public ChatGPT means invented or public
  information only. The rule comes before anyone types, and is practised in
  Block 5, not just stated.
