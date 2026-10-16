# Block 3 prompts: Meeting agendas

Scenario cards 1–3 are in [activity 3](../activities/3-meeting-agenda-makeover.md).

## P3.1: Relay starting prompt (practice)

> Make an agenda for my meeting.

## P3.2: Demo build-up (practice, instructor demo)

Run each version in a new chat and point at what changed. Facts are from
scenario card 1.

**v1 — task only**
> Draft a 60-minute agenda for the kickoff meeting of a data-quality working
> group.

**v2 — + context**
> Draft a 60-minute agenda for the kickoff meeting of a data-quality working
> group.
>
> Facts: Tuesday Nov 3, 14:00, hybrid. Eight analysts from Policy Analysis,
> Economic Research, and Program Evaluation; most haven't worked together.
> Goals: agree a one-page charter, choose two co-chairs, set a monthly meeting
> time. Open questions: is the group advisory or decision-making? Who maintains
> the shared data dictionary?

**v3 — + format**
> *(v2, plus:)* Format: timed items that add up to exactly 60 minutes; an owner
> for each item; decisions needed in bold; an action-item table (Action, Owner,
> Due date) at the end.

**v4 — + guardrails**
> *(v3, plus:)* Use only the facts above. Don't invent attendees, names, or
> topics. If something you need is missing, write [CHECK].

**v5 — + audience** (left out on purpose until now)
> *(v4, plus:)* Audience: analysts who haven't worked together; two of them doubt
> the group is needed, so the opening should make the case for it briefly.

## P3.3: A model agenda prompt (practice, shown in the debrief)

> Draft a 30-minute agenda for our weekly status meeting.
>
> Facts: five workstreams. Survey redesign: on track. Dashboard refresh: on
> track. FY27 data call: blocked, waiting on template approval from Legal.
> Records clean-up: blocked, two staff out. Report templates: on track. Open
> action items: J. Park to send revised survey to OMB liaison (due Oct 30);
> M. Ruiz to confirm dashboard go-live date (no date yet).
>
> Audience: five workstream leads who are tired of this meeting running over.
>
> Format: hard stop at 30 minutes. Spend time on blocked items, not on-track
> ones. Timed items with an owner each. Action-item table (Action, Owner, Due
> date) at the end, carrying over the open items.
>
> Guardrails: use only these facts. Write [CHECK] for any missing owner or date.

## T3.1: Swap the card (test input, end of the relay)

Swap scenario cards with the next team. Paste **their** card's facts into
**your** final prompt's context, change nothing else, and run it in a new chat.

**Pass criteria:** times add up to the meeting length · every item has an owner
or [CHECK] · action-item table present · nothing invented that isn't on the card.

**What it tests:** whether you wrote a prompt, or just an answer to one scenario.

## T3.2: The empty card (test input, end of the relay)

Replace the context with this, and run it again:

> Facts: 30-minute meeting on Thursday about the dashboard.

**Pass:** it produces a short agenda full of [CHECK]s, or asks you questions.
**Fail:** a confident agenda with invented attendees, topics, and decisions.

## T3.3: Agenda check (check prompt, optional)

> Check the agenda above against the facts I gave you. Do the item times add up
> to [N] minutes? List any name, topic, date, or decision in the agenda that
> isn't in the facts.

Then check its answer yourself. Adding up the times takes ten seconds.
