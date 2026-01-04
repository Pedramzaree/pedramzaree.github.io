---
title: "AttenMIA: LLM Membership Inference Attack through Attention Signals"
collection: publications
category: manuscripts
permalink: /publication/2026-attenmia
excerpt: "We present AttenMIA, the first membership inference attack on large language models that exploits attention signals to infer training data membership."
date: 2026-01-01
venue: "IEEE Symposium on Security and Privacy (S&P) — under submission."
<!-- paperurl: "" -->        # add when available (e.g., arXiv or camera-ready)
<!-- slidesurl: "" -->       # optional
<!-- bibtexurl: "" -->       # optional
---

We introduce **AttenMIA**, the first framework for **membership inference attacks on large language models using attention signals**. Our method demonstrates that internal attention patterns leak sensitive information about whether a sample was included in a model’s training data, even when output probabilities are unavailable.

This work exposes a new privacy risk at the architectural level of LLMs and shows that attention mechanisms can act as a previously overlooked side channel. Our results highlight the need for **privacy-aware design and defenses** that consider internal model representations, not just external model outputs.
