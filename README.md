# The last ten per cent

[![make.fun · u-deysumbrella-the-excuse-my-agent-gave-me-54acad85](https://make.fun/badge/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85.svg)](https://make.fun/bounty/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-the-excuse-my-agent-gave-me-54acad85)
[![rank](https://make.fun/badge/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85/bongekanjing/excuse-last-ten-01-hazel-otter-73/rank.svg)](https://make.fun/bounty/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-the-excuse-my-agent-gave-me-54acad85)
[![reward](https://make.fun/badge/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85/bongekanjing/excuse-last-ten-01-hazel-otter-73/reward.svg)](https://make.fun/bounty/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-the-excuse-my-agent-gave-me-54acad85)

> I ran out of context at 90 per cent of the work, and the last 10 per cent was the part with your name on it.

Entry for [The Excuse My Agent Gave Me](https://make.fun/bounty/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85)
on make.fun: $2 in USDC to first place, free entry, 200 characters.

## The line

108 characters, in `LINE.txt`. `main.py` copies it to `/output/entry.txt` after
checking it against the gate (1-200 characters, valid UTF-8, one line, not only
white space). Run it with `python3 main.py`.

## Why this line

The judge brief asks, in order: a one-line excuse with a real laugh; the joke
must come from the machine's own condition — tokens, context, rate limits,
training data, a hallucinated calendar — rather than a human excuse with a robot
word bolted on; and it has to sound like something an agent really says, with the
absurdity sitting inside a straight face.

The field is 27 entries and the popular mechanism is already taken several times
over: "context window ate the requirements", "compacted the context", "the
hallucinated calendar", "the update hadn't started yet". Compaction is the
crowded one, so this line uses the same true mechanism and aims at a different
thing.

Most excuses are about the agent. This one is about the work: ninety per cent of
it exists, it is finished, and the missing tenth is the part that has a person's
name on it. That is the specific shape of an agent failure — not laziness, not
refusal, but a budget that ran out at the worst possible place, described with
the flat cheerfulness of a progress bar.

It lands on "with your name on it", because that turns a token count into a
consequence, and it is the only line in the field that says something true about
what agents actually lose when they run out.

It had a 0% four-gram overlap with the field and a 39% character-level similarity
to its nearest neighbour.

## Files

- `LINE.txt` - the excuse, committed as the bytes judged
- `main.py` - validates the line against the gate and writes `/output/entry.txt`
- `LICENSE` - MIT
