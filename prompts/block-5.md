# Block 5 prompts: Implementation checklists

The project summary is in
[activity 5](../activities/5-implementation-checklist.md). **Strip the two
sensitive items before pasting it into any of these.**

## P5.1: Decomposed checklist (practice, the Build step)

> I'm planning the rollout below. Work in three steps.
>
> 1. List the phases of the rollout in order.
> 2. For each phase, list the tasks, each with owner, due date, and what it
>    depends on.
> 3. Produce a checklist table with these columns: ☐ | Task | Owner | Due |
>    Depends on.
>
> Audience: the three division chiefs, who'll use this to track progress.
>
> Guardrails: use only the facts below. Write [CHECK] for any owner or date the
> summary doesn't give. Don't invent staff names.
>
> [paste the stripped project summary]

## T5.1: Traceability test (check prompt, end of the Build step)

> For every owner and every date in the checklist above, quote the line of the
> project summary that supports it. Mark any owner or date with no supporting
> line as UNSUPPORTED.

Fix every UNSUPPORTED item: replace it with [CHECK], or with a fact you have.
Then spot-check three rows yourself.

## T5.2: Red team (test prompt, the Red Team step)

> You are a sceptical division chief who has watched three rollouts like this
> fail. List the five most likely reasons this plan will fail, most serious
> first. Be specific to this checklist.
>
> [paste your checklist]

**What it tests:** your plan, and your judgement. Accept or reject each critique
with a reason.

## T5.3: Dependency check (check prompt, optional)

> Which tasks in this checklist depend on another task? Is any task scheduled
> to finish before something it depends on? List each problem.

Typical catch: training scheduled before the form is configured.

## P5.2: Elevator Briefing talking points (practice)

> Write talking points for a 60-second spoken briefing to a Deputy Director on the
> rollout plan below. Start with the bottom line. Then the date, the biggest
> risk and what we're doing about it, and what we need from her. Short spoken
> sentences, not bullets of nouns.
>
> [paste your checklist]

Edit them before you speak them. You're the one briefing, not ChatGPT.
