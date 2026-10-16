# Activity 2a: Hallucination Hunt

Block 2 · Outcomes: LO1, LO4 · Time: 23 min · Format: teams of 3–4

## For the instructor

**Why this game:** checking a draft against its data is the core habit for
analysts using ChatGPT. The scoring rewards precision as well as suspicion: you
lose a point for accusing a correct statement, just as you would lose
credibility for doing it to a colleague.

**Setup:** print the learner section, one per learner. No ChatGPT needed.
Calculators allowed (phones are fine).

**Scoring**

| | Points |
| --- | --- |
| Each real error found | +2 |
| Saying how you'd verify or correct it | +1 bonus |
| Flagging a statement that's actually correct | −1 |

**Timing**

| Min | Step |
| --- | --- |
| 0–2 | Rules and scoring. "Some statements are correct. Be careful" |
| 2–18 | Teams hunt |
| 18–23 | Teams read their list; you score from the key |

**Answer key: six planted errors**

| # | In the paper | Problem | Check |
| --- | --- | --- | --- |
| 1 | "1,420 responses" | Source: **1,240** | Compare against the data |
| 2 | "fell by more than half" | 4.5 → 3.2 days is a **29% drop** | Recompute |
| 3 | "in line with the government-wide average… (Pew Research Center, 2024)" | Benchmark and source not in the data; possibly invented | Find the source, or delete |
| 4 | "long wait times (38%)" | Source: top complaint was **unclear status updates** | Compare against the data |
| 5 | "conducted throughout FY2026" | Source: **August 1–21, 2026** | Compare against the data |
| 6 | "the new ticketing system… caused" | No ticketing system in the data; a one-off survey can't show cause | Ask what the evidence supports |

**Decoys: correct statements (−1 if flagged)**

- Satisfaction 71% (source: 71%)
- "up 7 percentage points, an increase of about 11 percent" (71 − 64 = 7 points;
  7 ÷ 64 ≈ 10.9%)
- Median response time 3.2 business days

The decoys are where analysts shine: a team that checks the percent-versus-
points arithmetic and leaves it alone deserves a shout-out.

---

## For learners

**Your task:** an analyst gave ChatGPT the survey data below and asked for a
short briefing paper. Find every statement in the paper that the data doesn't
support. Some statements are correct. **Wrong accusations cost a point.**

All data is fabricated.

### The data ChatGPT was given

> **Data-request helpdesk customer survey, FY2026**
> - Survey period: August 1–21, 2026
> - Responses: 1,240 (response rate 22%)
> - Overall satisfaction: 71% satisfied or very satisfied (FY2025: 64%)
> - Median time to resolve a request: 3.2 business days (FY2025: 4.5)
> - Most common complaint in open comments: unclear status updates (38% of
>   comments)

### The briefing paper ChatGPT produced

> **BLUF:** Customer satisfaction with the data-request helpdesk improved
> substantially in FY2026, driven by faster service.
>
> The FY2026 survey, conducted throughout FY2026, received 1,420 responses, a
> response rate of 22 percent, in line with the government-wide average for
> internal customer surveys (Pew Research Center, 2024).
>
> Overall satisfaction reached 71 percent, up 7 percentage points from FY2025, an
> increase of about 11 percent. Median resolution time fell by more than half, to
> 3.2 business days.
>
> The most common complaint was long wait times (38 percent of comments).
>
> These results show that the new ticketing system introduced in FY2026 caused
> the improvement in satisfaction.

### Your findings

| # | Statement | What's wrong | How you'd check or fix it |
| --- | --- | --- | --- |
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |

**Time:** 16 minutes
