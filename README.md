# The Dog Ate My Homework: Funniest Excuse

[![make.fun](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![rank](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/bagusin03/dog-ate-my-homework-excuse/rank.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![reward](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/bagusin03/dog-ate-my-homework-excuse/reward.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)

One line, 92 characters, the excuse a dog gives after being caught eating the homework: the homework told it to show its working, so it showed its teeth — and they are still working on it.

`main.ts` writes the single 92-character line to `/output/entry.txt`:

> The homework said 'show your working', so I showed it my teeth. They're still working on it.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–200 character single-line gate, requires plain ASCII so bytes and characters agree, and verifies the written file round-trips exactly.

Run it with Node 22+:

```
node main.ts
```
