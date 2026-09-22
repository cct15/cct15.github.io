---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /research.html
---

My work sits where automated search meets evaluation. A searcher that can propose ten thousand hypotheses a day turns the problem inside out: generation stops being the bottleneck, and almost everything that looks significant is an artifact of the search that found it. The questions below are the ones I am actually working on.

## Evaluation under search pressure

How do you design a validator with enough statistical power that surviving it means something?

- **Held-out data as a budget.** Treating unseen windows as a depletable resource with a quota ledger, rather than a test set that quietly gets reused until it means nothing. A window that has been opened is scored once and never returned to the search.
- **Zero-alpha calibration.** Running the full pipeline over panels known to contain no signal, to measure how much apparent performance the pipeline manufactures on its own. That number is the floor any real result has to clear.
- **Scoring the scorer.** Keeping an answer book of candidates that once passed and later failed, and grading every new check by what it catches and what it lets through. A check that cannot catch a known historical failure does not get added.

## What may evolve, and what must not

A self-improving research system needs an explicit boundary. The search may rewrite its own operators, priors and representations. The judge, the data-access layer and the statistical conventions have to stay fixed, versioned and outside the system's reach — otherwise the system optimizes the examiner instead of the answer. I am interested in where that line belongs and how it fails when it is drawn in the wrong place.

## Where language models actually help

Hypothesis generation, literature grounding and implementation — under a hard publication-date cutoff, so a model cannot cite results that postdate the problem it was asked to solve. Not evaluation. The asymmetry is the point: a model that both proposes and judges converges on being convincing rather than on being right.

## Transfer across markets

Models pooled across asset classes and venues, and the question of how much predictive power survives a market the model has never seen. My working position is that measurement methods transfer and numbers do not — noise scale, decay half-life and health bands have to be re-estimated per market before any cross-market claim is admissible.

## Market microstructure

What is genuinely predictable at sub-second horizons, what is predictable only at the moment a decision is made, and where the boundary sits between an edge and a faster way to lose.
