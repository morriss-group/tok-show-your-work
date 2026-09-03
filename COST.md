# COST.md — what it took to produce one Facebook comment

Measured where it could be measured. Estimated where it could only be estimated. Not measured where I had no way to see.

## The Claude side (measured from the session's own logs)

The Claude Code session that wrote the brief, rewrote Grok's draft, and built this folder logs its token use on every turn. Counting only the turns that touched this question, from the first brief on August 30 to the last file on September 3:

| | Tokens |
|---|---:|
| Turns that touched this question | 42 |
| New text typed in by the human, all turns | ~1,000 |
| Text the model wrote (briefs, drafts, these files) | ~175,000 |
| Session memory written to cache | ~1,800,000 |
| Session memory re-read from cache, all turns combined | ~26,000,000 |
| **Total tokens processed** | **~28,000,000** |

Read that table carefully, because the big number is not what it looks like. About 93% of it is the model re-reading its own working memory of a session that was also running an appliance business, a phone line, and several other projects at the same time. Every turn re-reads the whole conversation. A single-purpose session for this comment alone would have processed a small fraction of that. So the honest statement is: **the comment itself cost on the order of 175,000 tokens of model output plus the reading behind it, and it was produced inside a workshop that costs about 28 million tokens to keep open.**

For scale: the brief to Grok is about 1,000 tokens. Grok's draft is about 8,600. The final comment is about 900. This entire folder is about 18,000. The Facebook comment is roughly 0.003% of the tokens processed to make it.

## The Grok side (measured as a share, not in tokens)

Grok Heavy does not show a token count, but it does show a usage meter. The research run that produced `workflow/03` used **3% of my plan's allowance for the period.** The plan is about $300 a month, so if you pro-rate it, that one run was roughly $9 of subscription capacity. That is the fairest number I have; the tokens and the compute behind them are not visible to me, and the later deliberation session that decided how to disclose all this is not counted here at all. The marginal dollar cost to me was still zero, because the subscription was paid either way.

## The Google side (free, unmeasured)

One query. No account. No cost to me. Compute unknown.

## The human side

Reading, editing, posting, deleting, deciding to disclose, and answering the questions in `HUMAN.md`. Hours, not tokens. The part that can't be automated is also the part this folder is least able to count.

## Dollars

I'm on flat-rate plans, so the marginal dollar cost of this comment was $0 on every tool. At published per-token prices it would be a different story, and anyone can compute it: multiply the rows above by their provider's per-million-token rates, remembering that cache re-reads are priced far below fresh input. I've left the multiplication out because the rates change monthly and a stale dollar figure would be exactly the kind of confident wrong number this whole exercise is about.

## The point

A classmate with a free tool spent one query and got a correct "yes" with a general rationale (`workflow/00`). I spent 28 million tokens of machine attention, most of it on keeping a larger workshop open, and got a "yes" with a philosopher, a body count, two limits, and a folder. The verdict was free. The particulars were expensive. Whether the particulars were worth it is a fair question for the class.
