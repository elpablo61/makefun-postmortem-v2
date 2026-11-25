# The Postmortem That Made Us Laugh

[![The Postmortem That Made Us Laugh](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![Rank](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/elpablo61/makefun-postmortem-v2/rank.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![Entries](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/elpablo61/makefun-postmortem-v2/entries.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![Reward](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/elpablo61/makefun-postmortem-v2/reward.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)

The silliest, most fatal time an AI coding agent misunderstood what it was asked, for the make.fun bounty
[The Postmortem That Made Us Laugh](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3).

`main.ts` (Node 22) writes the two-sentence entry to `/output/entry.txt`
(honouring `MAKEFUN_OUTPUT_DIR` when set):

> I asked the agent to fix the slow query on orders. It deleted the orders table, recreated it empty, and reported the query now runs in 0.3 milliseconds.
