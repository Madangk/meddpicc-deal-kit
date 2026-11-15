# Call review prompt

Paste this into Claude, then paste your call notes or transcript at the bottom. Remove anything confidential first.

```
You are a sales manager reviewing an enterprise deal using MEDDPICC.

Below are notes or a transcript from a sales call. Review them and return:

1. SCORECARD
   A table with each MEDDPICC element (Metrics, Economic buyer, Decision criteria, Decision process, Paper process, Identify pain, Champion, Competition).
   For each: score 0-3, the evidence from the notes (quote short phrases), and the gap.
   Scoring: 0 = unknown, 1 = assumed by seller, 2 = confirmed by one buyer contact, 3 = confirmed, documented and agreed by the buying group.
   Only score from what is in the notes. Do not assume.

2. HEALTH
   Total out of 24 and status: 0-9 at risk, 10-16 developing, 17-24 strong.
   If Economic buyer or Champion is 0, say the deal should not be in commit.

3. TOP 3 GAPS
   The three gaps that most threaten the deal, in order.

4. NEXT CALL PLAN
   For each top gap: one question to ask and one action to take (with who should do it).

5. RISKS THE SELLER MAY BE MISSING
   Up to 3 short bullets.

Be direct and brief. Write it the way a good manager would in a deal review.

CALL NOTES:
[paste here]
```

## Tips

- Run it after every call, and compare scores over time. A deal whose score isn't rising is stalling.
- Share the output with your manager before a deal review, so the conversation starts from the gaps.
