# Block 1: First contact

Status: draft
Time: 8:30–9:30 (60 min) · Talk 25 / do 35
Outcomes: LO1, LO4

## Purpose

Within the first quarter-hour, learners have voted, laughed, and seen ChatGPT
invent things. They know what's safe to type before they type it, and they leave
the block with an accurate one-sentence model of how ChatGPT works.

## Outline

| Min | Segment | Format | What happens |
| --- | --- | --- | --- |
| 0–4 | Welcome | Instructor | Who you are, in two sentences. Breaks at 9:30, 10:45, 14:00, 15:15; lunch at 12:00; finish 16:30. Teams are the tables; the scoreboard is on the wall |
| 4–11 | **Human or Machine?** | Teams | [Activity 1a](../activities/1a-human-or-machine.md). Two meeting agendas; one was written by ChatGPT. Teams vote with A/B cards, then argue. First points on the board |
| 11–18 | Introductions | Tables | Name, office, and one task you'd hand to a capable assistant tomorrow, on a sticky note for the goals wall. Keep it free of sensitive detail; it becomes your afternoon project |
| 18–26 | **Safe-use rules** | Instructor | [Safe-use card](../materials/handouts/safe-use-card.md). Then the room rule: *this is the public ChatGPT, so everything you paste today is invented or public* |
| 26–31 | Pre-check | Individual | [Pre/post check](../assessment/pre-post-check.md). Anonymous; "I don't know" is a good answer at 8:56 |
| 31–35 | Setup check | Individual | Everyone opens the [prompt bank](../prompts/README.md) in one tab and the public ChatGPT in another, signs in with the account they created before the day, checks the model is GPT-6, starts a new chat, and sends prompt **S1**. Then, together, the data-control settings: [TODO: per agency guidance, e.g. turn off use of chats for model training, or use temporary chats] |
| 35–47 | **Same prompt, different answers** | Individual, then tables | [Activity 1b](../activities/1b-same-prompt-different-answers.md). Everyone sends practice prompt **P1.1**; tables compare. Fast finishers run test **T1.2** (the same prompt in a second new chat) |
| 47–57 | How ChatGPT works | Talk | Talking points below. Use their outputs from 1b as the examples, not slides |
| 57–60 | Bridge | Instructor | *"If it fills gaps with plausible guesses, what happens when you ask it about data?"* Break |

## Talking points: how ChatGPT works (10 min)

Five points, each tied to something they just saw. Degree-holding analysts will
want the real mechanism, not a metaphor, so give it plainly.

1. **It predicts text.** It was trained on a very large amount of writing to
   produce likely next words. It writes something plausible; it doesn't
   retrieve an answer from a database.
2. **It knows two things:** what it learned in training, which stops at a cut-off
   date, and what's in this conversation. It doesn't know your office, your
   meetings, or last week's guidance unless you tell it. **Run behaviour test
   T1.1 live** ("What's on the agenda for my team's meeting next week?") and let
   the room see what it does with no information. [TODO: say whether web search
   is on in the public version, and what that does and doesn't change.]
3. **It varies on purpose.** That's why the table's agendas differed. Good for
   drafting, bad for facts.
4. **It fills gaps silently.** The meeting topics, times, and attendees it gave
   you weren't in your prompt. That's the root of hallucination.
5. **Its confidence tells you nothing.** It writes a wrong number as fluently as a
   right one.

The one line to leave on the whiteboard all day: **vague in, generic out;
missing facts get made up.**

## Materials

- [Block 1 prompts](../prompts/block-1.md): S1, P1.1, T1.1–T1.3
- A/B voting cards (one set per team); scoreboard on the wall
- Activity 1a handout with the pre-made ChatGPT agenda (generated in prep)
- Safe-use card, agenda handout, prompt checklist on every table
- Goals wall and sticky notes

## Check before moving on

Everyone has a working ChatGPT login and a sticky note on the goals wall, and
every table can name at least one detail ChatGPT invented in activity 1b.

## Notes

- Start on time. Latecomers join a team; *Human or Machine?* works with any
  number.
- **Never cut the safe-use rules.**
- If a login fails, pair that person with a neighbour and fix it at 9:30.
