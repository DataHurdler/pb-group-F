# Block 5: Implementation checklists: build, red-team, brief

Status: draft
Time: 14:15–15:15 (60 min) · Talk 5 / do 55
Outcomes: LO2, LO3, LO4

## Purpose

The third target task brings everything together. Teams decide what not to
paste, break a project into a checklist, have ChatGPT attack their plan, judge
which attacks are fair, and then brief the result standing up, which is the
day's link to the briefings these learners give for a living.

## Outline

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–5 | Brief | Instructor | The [project summary](../activities/5-implementation-checklist.md). First instruction: **read it before you paste anything** |
| 5–10 | **Strip** | Teams | Mark everything in the summary that shouldn't go into ChatGPT, and say why. Two items should get caught. Points for each, with a reason |
| 10–25 | **Build** | Teams | Practice prompt **P5.1**: phases first, then tasks with owner, due date, and dependency, then the checklist. [CHECK] for anything missing. Then the traceability test **T5.1**: fix every UNSUPPORTED owner or date |
| 25–38 | **Red Team** | Teams | Test prompt **T5.2**: ChatGPT plays a sceptical division chief and lists the five most likely reasons the plan fails. Teams **accept or reject each critique with a reason**, then update the checklist |
| 38–52 | **Elevator Briefing** | One volunteer per team | Practice prompt **P5.2** drafts 60-second BLUF talking points; the volunteer edits them and briefs **you, playing the Deputy Director**, standing up. You ask one hard question. The clearest briefing gets points |
| 52–60 | Debrief | Room | *What did you strip, and why? Which red-team critique was wrong? Did the talking points prepare your briefer for the question?* |

All prompts for this block: [../prompts/block-5.md](../prompts/block-5.md).

## Strip: there's no grey area today

Learners are using the **public** version of ChatGPT, which isn't approved for
any non-public agency information. Both flagged items (the vendor quote and the
unannounced merger) must come out before anything is pasted. Make the general
rule explicit: *if it isn't needed for the task, it doesn't go in; and in the
public version, only public or invented information goes in at all.*

## Why the Red Team step matters

ChatGPT's critiques are a mix of sharp, generic, and wrong. Deciding which is
which is the judgement these learners already use on colleagues' drafts, now
applied to a machine. A team that accepts all five critiques uncritically has
missed the point. Say so, kindly.

## Playing the Deputy Director

Stay in role and keep it light. Good hard questions:

- "What's the one thing most likely to slip, and what are you doing about it?"
- "Who owns this if it goes wrong?"
- "What do you need from me?"

The briefer can say "I'll get back to you"; that's a legitimate answer. Points
go for clarity, not for having every answer.

## Materials

- Activity 5 handout: project summary, checklist format, red-team prompt
- Highlighters for the strip step
- Scoreboard

## Check for understanding

Every team catches both sensitive items in the strip step, and its final
checklist has owners, dates, and [CHECK] flags rather than invented details.

## If you're behind

Cut 3 in [../schedule.md](../schedule.md): briefings from two volunteer teams.
**Never cut the strip step.**
