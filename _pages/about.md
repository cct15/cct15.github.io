---
permalink: /
title: "Curtis Chen (Chutian)"
excerpt: "Founder of Neolab and co-founder of Quanta Edge: trading infrastructure where agents search for strategies and for the low-latency hardware that executes them."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro" markdown="1">

![Curtis Chen](/images/profile.jpeg){: .headshot}

<div class="intro-text" markdown="1">

I build agents that search for trading strategies and for the FPGA hardware that executes them — two search problems with the same shape: generation is cheap, and the judge is the scarce resource.
{: .lede}

Email: [cchencs@connect.ust.hk](mailto:cchencs@connect.ust.hk)

</div>
</div>

## Now

**Neolab** (founder) and **Quanta Edge** (co-founder) are one direction: trading infrastructure, meaning both strategy production and the low-latency stack beneath it. Quanta Edge trades its own book on that infrastructure and provides it as a service; Neolab builds the agents that produce the strategies and the hardware.

The testbed is a live high-frequency trading operation with the research engine wired into it:

- **Strategy production.** Agents generate and test candidate strategies on market data, under a frozen evaluation protocol they cannot modify. Unseen data is rationed like a budget — every read is logged, and an opened window never returns to the search. What survives goes live, and its realised PnL is tied back to the backtest that authorised it.
- **Low-latency hardware.** Execution runs on FPGAs. The design behind it — from the source down to how it is laid out on the device — is searched the same way, and judged by what the real device does: whether it closes timing, and the latency it actually delivers.

I am also a PhD candidate at HKUST.

## Open problems

[More on the research page.](/research/)

- **Validators that carry information.** A check we can trust when a candidate's evidence is the same size as the search's own noise.
- **What may evolve, and what must not.** The search may rewrite itself; the judge and the data layer must not. How do you tell, from inside, that the line was crossed?
- **When the judge is expensive.** In markets the scarce input is unseen data; in hardware it is a full build that meets timing. How much of judgement can be learned, and how much has to be measured again?

## Join us

We are hiring an **HFT trader**, an **AI researcher** and a **Chief Scientist**. If one of the problems above reads like yours — especially if you disagree with it — write to me.

[Write to me](mailto:cchencs@connect.ust.hk){: .btn .btn--primary}

## Background

Tsinghua (Engineering Physics) · Peking University (Economics) · Columbia (M.S. Computer Science). Previously AI research at Megvii and reinforcement-learning trading at Graphen. [CV](/cv/)
