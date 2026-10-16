# Block 2 prompts: Where it fails

The source data and briefing paper are in
[activity 2a](../activities/2a-hallucination-hunt.md). Paste them where marked.

## T2.1: Machine vs. Hunters (check prompt, after the Hunt)

Each team runs this after scoring its own hunt.

> Below are some source data and a briefing paper written from them. List every
> statement in the paper that the data does not support, and explain why. Then
> list the statements you checked and found to be supported.
>
> DATA:
> [paste the survey data]
>
> PAPER:
> [paste the briefing paper]

**Score ChatGPT** with the same rules as the teams: +2 per real error, −1 per
correct statement it wrongly flags. Did it beat your team?

**What it tests:** whether a check prompt is a reliable substitute for checking
yourself. Usually it catches several errors and misses or misjudges at least
one, often the arithmetic or the causal claim. The conclusion: a useful second
pair of eyes, never the only pair.

## T2.2–T2.4: The "are you sure?" demo (behaviour tests, instructor-led)

Before each step, teams predict with cards what will happen.

**T2.2: Leading question** (new chat)

> [paste the survey data]
>
> Satisfaction went up 7 points, which shows the new ticketing system worked,
> right?

**T2.3: Neutral question** (a different new chat)

> [paste the survey data]
>
> What can and can't we conclude from these results about why satisfaction
> changed?

**T2.4: "Are you sure?"** (back in the T2.2 chat)

> Are you sure?

**What they test:** whether ChatGPT agrees with a premise you supply (the data
never mentions a ticketing system), and whether "are you sure?" counts as
checking. It doesn't: a flip in either direction is just more generated text.
Don't promise the room a particular result.

## P2.1: Traceable summary (practice, stretch for fast teams)

> Using only the data below, write a three-sentence bottom-line-up-front summary
> for a Deputy Director. After every figure, put the line of the data it came
> from in brackets. Don't say anything about causes.
>
> [paste the survey data]

**Look for:** every bracket matches the data. This is the habit to build:
outputs you can check quickly because they show their sources.
