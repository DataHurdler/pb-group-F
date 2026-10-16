# 01 How LLMs work, and where they fail

Status: draft
Time: 9:30–10:45 (75 min) · Talk 30 / do 45
Outcomes: LO1, LO4

## Purpose

Learners replace "it's a smart search engine" with an accurate picture: it
predicts plausible text from what's in the conversation. Every technique later in
the day follows from that, and so does every reason to check its work.

## By the end of this session, learners can…

- Explain why the same prompt gives different answers, and why a vague prompt
  gets invented details (LO1).
- Find fabricated or altered facts in an AI-drafted document by checking it
  against its source (LO4).

## Outline

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–10 | Hook | Individual, then tables | [Activity 1.1: Same prompt, different answers](../activities/1.1-same-prompt-different-answers.md). Everyone sends the identical vague prompt and compares results at their table |
| 10–25 | Idea 1: prediction, not lookup | Lecture | See talking points below |
| 25–35 | Debrief the hook | Room | Through the new lens: every detail it invented about "the new telework policy" was a gap in the prompt. *Vague in, generic out; missing facts get made up* |
| 35–50 | Idea 2: where it fails in federal work | Lecture | See talking points below |
| 50–68 | Activity 1.2 | Tables | [Check the memo](../activities/1.2-check-the-memo.md): an AI-drafted memo with six planted problems, checked against the facts it was given |
| 68–75 | Debrief and bridge | Room | Which problems were hardest to spot? Which would have embarrassed you if the memo went out? Bridge: *since it fills gaps, the fix is to leave fewer gaps. That's Session 02* |

## Talking points: idea 1 (15 min)

Keep it to five points, each with one example. No architecture diagrams.

1. **It predicts the next words.** It learned patterns from a huge amount of
   text and produces what's likely to come next. It's writing something
   plausible, not retrieving an answer.
2. **It only knows two things:** what it learned in training (which stops at a
   cut-off date) and what's in this conversation. It doesn't know your agency,
   your program, or last week's guidance unless you tell it. Some tools can
   search the web or read files; say which, for the tool in the room.
3. **There's built-in variation.** That's why the table got different
   announcements. Useful for drafting; a hazard for facts.
4. **When it lacks a fact, it fills the gap with something plausible.** It doesn't
   flag the gap unless you ask it to. This is what people call hallucination.
5. **It sounds equally confident whether it's right or wrong.** Fluency isn't
   accuracy.

## Talking points: idea 2 (15 min)

Name each failure, give a federal example, and say what you'd do about it.

| Failure | Federal example | What you do |
| --- | --- | --- |
| Invented citations | A CFR section or USC citation that doesn't exist, or exists but says something else | Look it up in the primary source (eCFR, govinfo) every time |
| Changed details | "30 calendar days" becomes "30 days" or "30 business days" | Compare against the source line by line |
| Invented numbers | A statistic with no source | Delete it or find a real source |
| Outdated information | Last year's guidance described as current | Give it the current text; don't ask it to remember |
| Agreeing with you | You suggest a wrong answer and it goes along | Ask neutrally; ask it what would make you wrong |
| Wrong tone or bias | Language that's inappropriate for the public or treats groups differently | Read as the recipient would |

Then the three rules that follow, which tie back to the safe-use card:

- **You're accountable** for anything you send, whoever drafted it.
- **Check against a source**, not against the tool. Asking "are you sure?" isn't
  checking.
- **What you paste matters as much as what you get back.** Follow your agency's
  rules on what may go into which tool.

## Materials

- Activity 1.1 prompt on a slide
- Activity 1.2 handout (memo and source facts), one per learner
- Slides: `materials/slides/01-how-llms-work.*` [TODO]

## Check for understanding

During activity 1.2, every table should find at least four of the six problems.
If most tables miss the date error or the "business days" change, spend two
minutes after the break on reading against the source line by line.

## Common problems

| Problem | Response |
| --- | --- |
| "Mine didn't make anything up" | Ask what it said about dates, eligibility, or who it applies to. Those were never in the prompt |
| Someone asks how neural networks work | Parking lot. One sentence: it's a very large pattern model; the details don't change how you use it |
| A learner is anxious because the tool gets things wrong | That's the right reaction. The rest of the day is about using it anyway, safely |

## If you're behind

Cut 1 in [../schedule.md](../schedule.md): tables check problems 1–4; you reveal
5 and 6.
