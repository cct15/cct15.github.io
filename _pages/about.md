---
permalink: /
title: "Chutian Chen (Curtis)"
excerpt: "Founder of Futuristic Group, a research lab that trades its own book; co-founder of Quanta Edge."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro" markdown="1">

![Chutian Chen](/images/profile.jpeg){: .headshot}

<div class="intro-text" markdown="1">

I am the founder of **Futuristic Group**, a research lab that trades its own book, and a co-founder of **Quanta Edge**, an ultra-low-latency trading firm. I am also a PhD candidate at the Hong Kong University of Science and Technology.
{: .lede}

Email: [cchencs@connect.ust.hk](mailto:cchencs@connect.ust.hk)

</div>
</div>

## What I have built

**Futuristic Group** (founder, 2025–). A research lab that trades its own book, running systematic strategies and on-chain market making, with tokenized real-world assets as its main line. I built the research and trading stack end to end — data infrastructure across venues, a validation framework with walk-forward testing and a pre-deployment audit, and live monitoring that ties realised PnL back to the backtest that authorised the position — and I set the standard a signal has to clear before it is allowed to trade capital.

**Quanta Edge** (co-founder, 2026–). Ultra-low-latency trading in Chinese index futures and equity markets with FPGA-based execution, and high-frequency market making for tokenized real-world assets.

Before this I worked on AI research at Megvii and on reinforcement-learning trading models at Graphen in New York. I hold degrees in Engineering Physics (Tsinghua University), Economics (Peking University) and Computer Science (M.S., Columbia University). A fuller record is on my [CV](/cv/).

## What I work on now

Research systems that search for trading strategies on their own. Futuristic's work is a self-evolving research engine: hypotheses are generated and tested automatically, while the evaluation protocol stays in human hands and the engine is not permitted to edit it. Unseen data is treated as a consumable budget — every read is logged against a quota, and a window that has been opened is never returned to the search. Strategies are the output; the engine is the asset.

Automated search makes discovery cheap and makes judgement the binding constraint. That is the research question I care about, and finance is an unusually honest place to study it: signals decay, unseen data is genuinely scarce, and being wrong is priced daily.

## Open problems

The three we are stuck on. Longer statements, and what else we work on, are on the [research](/research/) page.

**Validators that carry information.** We can measure how much performance a pipeline manufactures out of nothing. We cannot yet build a check we trust when a candidate's evidence and the search's own noise are the same size — which is most of the time.

**The line between what may evolve and what must not.** The search may rewrite its operators and priors; the judge and the data layer must not move. We know where we drew that line. We do not know how to tell, from inside the system, that it has been crossed.

**Arriving in a market you have never seen.** Methods transfer, numbers do not — every new market costs a full recalibration. How much of that can be learned rather than measured again from scratch?

## Working with us

We are looking for a researcher on the evaluation side: someone who would rather build the judge than the next signal.

The work is the protocol that decides what counts as real — how unseen data is rationed, how a check earns its place, how you separate a discovery from an artifact of the search that produced it. Almost nobody works on this, and it is what decides whether the rest of it means anything.

What we can offer is markets that price your answer daily, compute and market access that are not the binding constraint, and a team small enough that the agenda is yours to argue with.

If the problems above read like your problems — especially if your first reaction was to disagree with one — write to me.

[Write to me](mailto:cchencs@connect.ust.hk){: .btn .btn--primary}
