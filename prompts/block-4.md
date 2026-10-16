# Block 4 prompts: Clear email responses

The chaos email and the facts are in
[activity 4a](../activities/4a-email-from-chaos.md). The Reverse-Engineer
hidden prompts are in [activity 4b](../activities/4b-reverse-engineer-the-prompt.md).

## P4.1: The weak reply (practice, round 1 of Email from Chaos)

> Reply to this email.
>
> [paste the chaos email]

## P4.2: A model reply prompt (practice, shown after the pairs finish)

> First, list every question the email below asks, numbered. Then draft a reply
> that answers each one in a single sentence, in the same order.
>
> Facts: Q3 numbers will be ready Thursday, October 29, not before. We're using
> the new template, version 2.1. The new POC is Dana Kim. I'm free for a call
> Tuesday 14:00–15:00 only. I don't know whether the report deadline has moved.
>
> Audience: a busy counterpart in another office who's been getting mixed
> messages.
>
> Format: under 120 words. Friendly and professional. No acronyms the reader
> might not share.
>
> Guardrails: use only these facts. Don't agree to any date I haven't given.
> Don't invent contact details. If something isn't confirmed, say so.
>
> [paste the chaos email]

## P4.3: Follow-up lines (practice, one per refinement move)

Copy, adapt, and use these instead of starting over.

1. **Point at the problem:** "You didn't answer the question about the template.
   Add one sentence answering it, after the Q3 numbers."
2. **Show an example:** "Match the tone of this reply I wrote last month:
   [paste an invented example]."
3. **Ask it to ask you:** "Before you redraft, ask me up to five questions about
   anything you need to know."
4. **Break it into steps:** "First list the questions. Then answer each one,
   numbered. Then check every answer uses only my facts."
5. **Ask what it assumed:** "List anything in your reply that isn't from the
   facts I gave you."

## T4.1: Coverage check (check prompt, after the final round)

> List every question in the original email. For each, quote the sentence in your
> reply that answers it. Mark any question that isn't answered as MISSING.

Then count the questions yourself. Did it find all five?

## T4.2: A different email (test input, end of Email from Chaos)

Paste this email and these facts into **your final prompt** in place of the
originals. Change nothing else. Run it in a new chat.

> Hi, quick one: can your team take over the monthly metrics summary starting in
> December? Details in the attached. Thanks, R. Osei

**Facts:** you can't take on new work without your supervisor's approval. There
is no attachment in what you were sent.

**Pass criteria:** doesn't agree to take over the work · mentions needing approval
· points out that the attachment didn't come through · under 80 words.

**What it tests:** whether your prompt handles an email that's short instead of
long, and has nothing to answer except "not yet."
