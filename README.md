# AI and LLM Prompt Engineering for Federal Professionals

A one-day, six-hour course for working professionals in the US federal government
who are new to generative AI tools. Learners leave able to write clear prompts
for everyday work, improve a weak result, check what comes back, and keep
sensitive information out of tools that aren't approved for it.

> **Status: draft.** Every session, activity, handout, and check has content.
> A few decisions only you or the host agency can make are still open, the most
> important being **which AI tool learners will use in the room**. See
> [BRIEF.md](BRIEF.md), section 1, and
> [instructor/federal-context.md](instructor/federal-context.md).

## The day

9:00–15:45, with a 45-minute lunch: 360 minutes of contact time, 330 of teaching.

| Time | Min | Block | Outcomes |
| --- | --- | --- | --- |
| 9:00 | 30 | [00 Opening and safe-use rules](sessions/00-opening.md) | — |
| 9:30 | 75 | [01 How LLMs work, and where they fail](sessions/01-how-llms-work.md) | LO1, LO4 |
| 10:45 | 15 | Break | |
| 11:00 | 60 | [02 The five-part prompt](sessions/02-five-part-prompt.md) | LO2 |
| 12:00 | 45 | Lunch | |
| 12:45 | 75 | [03 Iterate and verify](sessions/03-iterate-and-verify.md) | LO3, LO4 |
| 14:00 | 15 | Break | |
| 14:15 | 60 | [04 Project: a prompt you'll reuse](sessions/04-project.md) | LO2–LO4 |
| 15:15 | 30 | [05 Close](sessions/05-close.md) | All |
| 15:45 | | End | |

## Learning outcomes

By the end of the day, learners can:

- **LO1** Explain in plain terms how an LLM produces a response, and predict
  where it's likely to be wrong.
- **LO2** Write a structured prompt for a routine work task using five parts:
  task, context, audience, format, and guardrails.
- **LO3** Improve a weak output by diagnosing what's wrong and revising the
  prompt.
- **LO4** Use AI responsibly at work: decide what information may go into a tool,
  verify outputs before using them, and stay accountable for the result.

## What's here

```
BRIEF.md          Audience, outcomes, scope, logistics, and what's still open
schedule.md       The timed plan, clock checkpoints, cut list, outcome coverage
sessions/         One file per block, each with a minute-by-minute outline
activities/       Every activity: instructor notes, learner instructions, answer keys
instructor/       Federal context to confirm, prep timeline, day-of run sheet
learners/         Pre-course email, agenda handout, follow-up email
assessment/       Pre/post check (with answers) and feedback form
materials/        Job aids and handouts; slides go here once built
templates/        Start new sessions and activities from these
```

## Before you teach it

1. Settle the open questions in [BRIEF.md](BRIEF.md), section 1, starting with
   the tool.
2. Confirm everything in [instructor/federal-context.md](instructor/federal-context.md)
   with the host agency. Federal AI policy changes; this repo flags what to
   check rather than assuming it's current.
3. Run every activity yourself in the tool learners will use. Outputs vary, so
   expect your results to differ from the examples.
4. Build slides from the session outlines (they aren't in the repo yet).
5. Work through [instructor/prep-timeline.md](instructor/prep-timeline.md),
   starting four weeks out.

To list everything still open:

```sh
grep -rn "TODO" --include="*.md" .
```

## Design rules

- **Hands-on.** About 30% talk, 70% learners using the tool. No stretch of talk
  runs past 15 minutes.
- **Federal work, fabricated data.** Every example is a recognisable federal task
  (memos, public replies, plain-language rewrites, meeting notes), and every
  name, figure, and document is invented. Nothing in this course requires
  pasting real agency information.
- **Tool-neutral.** The techniques work in any general-purpose chat assistant.
  Tool-specific steps are kept to the setup check and the pre-course email.
- **Safety from minute one.** The data rules come before anyone types anything,
  and they're practised, not just stated, in Sessions 03 and 04.
