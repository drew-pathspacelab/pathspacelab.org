---
layout: single
title: "About"
permalink: /about/
excerpt: "Who runs Pathspace Lab, how to read the site, and what's on the bench right now."
author_profile: true
---

I'm Drew Tilley, a quantitative researcher who trained as a biophysicist. <span style="color: var(--brand-primary);">**Pathspace Lab**</span> is my independent research practice, and this site is its lab notebook: the experiments, the code behind them, and the essays where I work out what the results mean.

<section class="psl-section" markdown="1">

## Background

I was not always interested in finance. In graduate school I studied stochastic processes in biophysical systems. Whether tracking molecules or interpreting noisy experimental data, the challenge was always the same: understand systems that rarely behave exactly the way we expect.

Later I built equity risk models: factor decompositions, covariance estimates, optimizers. The models were rigorous and the backtests were convincing, but every one of them rested on a single realized history, and I never found a satisfying way to ask how much that mattered. Pathspace Lab is where I finally get to ask. The longer version is in [Beyond the Realized Path](/writing/beyond-the-realized-path/).

</section>

<section class="psl-section psl-section--alt" markdown="1">

## How to read this site

**[Research](/research/)** holds numbered artifacts. Each one asks a single narrow question, holds everything else fixed, and reports what happened, including the methods, the diagnostics, and the limitations. Results that turn out fragile or inconclusive get published too.

**[Writing](/writing/)** holds essays that sit between the artifacts. They're less technical: what the last result seemed to say, and why the next experiment is shaped the way it is.

If you're starting from zero, read them in order: [Beyond the Realized Path](/writing/beyond-the-realized-path/), then [Artifact 01](/research/artifact-01/), then [Walking in the Dark](/writing/walking-in-the-dark/).

</section>

<section class="psl-section" markdown="1">

## How I work

- **Perturb before inventing.** I start by resampling what's already in the data, such as block bootstraps or alternative orderings, before adding any new assumptions about how markets behave.
- **One change at a time.** Each artifact varies one thing, so any difference in the results has a clear source.
- **Show the work.** The code is [open](https://github.com/drew-pathspacelab/time-path-fragility), the figures are reproducible, and the limitations are written down next to the findings.

Pathspace Lab is also an experiment in independent research. I believe some of the most interesting questions emerge outside traditional organizational boundaries, where curiosity can set the agenda instead of quarterly priorities.

</section>

<section class="psl-section psl-section--alt" markdown="1">

## On the bench

*Updated October 2026*

Artifact 02 is in progress. It asks how the regression underneath a risk model should remember the past, evenly or with fading weight, and how hard it should react to extreme days. After that, Artifact 03 asks whether a model can tell a stitched-together history from the real one.

</section>

<section class="psl-section" markdown="1">

## Get in touch

If these questions interest you, I'd welcome the chance to connect, collaborate, or simply trade ideas.

[Contact →](/contact.html){: .psl-card-link }

</section>
