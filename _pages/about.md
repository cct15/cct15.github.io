---
permalink: /
title: "Curtis Chen (Chutian)"
excerpt: "Co-founder of Quanta Edge: trading infrastructure where agents search for strategies and for the low-latency hardware that executes them."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro" markdown="1">

![Curtis Chen](/images/profile.jpeg){: .headshot}

<div class="intro-text" markdown="1">

Strategies are about to become free, and so is the silicon that runs them. What a trading firm will still own is its judge, the protocol that decides what is real, and the right to act on it fast. I am building that firm.
{: .lede}

Email: [cchencs@connect.ust.hk](mailto:cchencs@connect.ust.hk)

</div>
</div>

## Now

**Quanta Edge** (co-founder). A trading-infrastructure firm: strategy production and the low-latency stack beneath it, built on high-frequency hardware and on agents that accelerate research on both strategies and chip design. We trade our own book on that infrastructure and provide it as a service.

The testbed is a live high-frequency trading operation with the research engine wired into it:

- **Strategy production.** Agents generate and test candidate strategies on market data, under a frozen evaluation protocol they cannot modify. Unseen data is rationed like a budget: every read is logged, and an opened window never returns to the search. What survives goes live, and its realised PnL is tied back to the backtest that authorised it.
- **Low-latency hardware.** Execution runs on FPGAs. The design behind it, from the source down to how it is laid out on the device, is searched the same way, and judged by what the real device does: whether it closes timing, and the latency it actually delivers.

I am also a PhD candidate at HKUST.

## Open problems

[More on the research page.](/research/)

- **Validators that carry information.** A check we can trust when a candidate's evidence is the same size as the search's own noise.
- **What may evolve, and what must not.** The search may rewrite itself; the judge and the data layer must not. How do you tell, from inside, that the line was crossed?
- **When the judge is expensive.** In markets the scarce input is unseen data; in hardware it is a full build that meets timing. How much of judgement can be learned, and how much has to be measured again?

## Join us

We are hiring an **HFT trader**, an **AI researcher** and a **Chief Scientist**. If one of the problems above reads like yours, especially if you disagree with it, write to me.

[Write to me](mailto:cchencs@connect.ust.hk){: .btn .btn--primary}

## Background

Columbia (M.S. Computer Science) · Peking University (Economics) · Tsinghua (Engineering Physics). Previously AI research at Megvii and reinforcement-learning trading at Graphen. [CV](/cv/)
