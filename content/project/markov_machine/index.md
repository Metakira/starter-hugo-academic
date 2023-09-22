---
title: Markov_Machine
subtitle: A Drum machine that uses markov chains
date: 2023-09-06T15:25:57.971Z
summary: A Drum machine that uses Markov chains to predict the next output
draft: false
featured: false
tags:
  - music
categories:
  - personal
links:
  - icon_pack: fab
    icon: github
    name: Code
    url: https://github.com/georgevpp-code/Markov-chain-Drum-machine
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: A work of art showing the probability space of a markov chain
---
*A Markov chain or Markov process is **a stochastic model describing a sequence of possible events in which the probability of each event depends only on the state attained in the previous event**. Informally, this may be thought of as, "What happens next depends only on the state of affairs now."*

I patched this natively in PureData. The machine alternates between linear standard states and Markov states. The kicks, snares and hihats are synthesized within PD so no need to bring in samples