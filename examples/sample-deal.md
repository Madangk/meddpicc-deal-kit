# Sample deal: Northwind Payments (fictional)

> All names, companies and numbers are made up to show how the kit works.

## Call notes (after second discovery call)

> Spoke with Priya (Head of Data Eng). Merchant dashboards take 8 to 12 seconds to load at peak, and merchants are complaining. Goal is under 2 seconds before the SEA launch in Q2. Current warehouse bill up ~40% this year. She reports to the CTO, Arjun, who "has to approve anything over budget". Comparing us with staying on the current warehouse and tuning it. Wants a POC on their own data. Not sure about the security review process; "IT handles that". Said she'd set up time with Arjun after the POC.

## Call review output (from the prompt)

| Element | Score | Evidence | Gap |
|---|---|---|---|
| Metrics | 2 | "8-12 sec today, under 2 sec target" | Cost metric not agreed |
| Economic buyer | 1 | CTO named, "approves over budget" | Not met |
| Decision criteria | 1 | Wants POC on own data | Criteria not written down |
| Decision process | 1 | POC, then CTO | Steps and dates unclear |
| Paper process | 0 | "IT handles that" | Unknown |
| Identify pain | 3 | Merchant complaints, SEA launch deadline | None |
| Champion | 2 | Priya shares info, offered CTO meeting | Not yet tested |
| Competition | 2 | Status quo plus tuning | Need win plan versus "tune what we have" |
| **Total** | **12/24** | Developing | |

**Top 3 gaps**
1. **Economic buyer.** Meet Arjun *before* the POC, not after, to agree what success means to him.
2. **Paper process.** Find out the security review steps now, since they can take longer than the POC.
3. **Decision criteria.** Write down the POC success criteria with Priya and get Arjun to agree.

**Next call plan**
- Ask Priya: *"Could we get 20 minutes with Arjun this week to confirm the POC goals?"* (tests the champion)
- Ask Priya to introduce IT security. Send our security pack in advance.
- Draft the mutual action plan with the Q2 SEA launch as the target date.

## Two weeks later

The CTO meeting happened, the success criteria were signed off, and the security review was started in parallel with the POC. The score rose to **18/24 (strong)**, and the deal moved to commit with a dated mutual action plan.
