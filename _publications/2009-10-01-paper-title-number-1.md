---
title: "Attention Eclipse: Manipulating Attention to Bypass LLM Safety-Alignment"
collection: publications
category: manuscripts
permalink: /publication/2025-10-01-attention-eclipse
excerpt: "We introduce the first attention-manipulation jailbreak, demonstrating how targeted attention perturbations can bypass safety alignment in large language models with high success and low cost."
date: 2025-10-01
venue: "EMNLP"
paperurl: "https://aclanthology.org/2025.emnlp-main.842/"        # add PDF link when available
slidesurl: ""       # optional
bibtexurl: ""       # optional
---

We propose **Attention Eclipse**, the first jailbreak technique that directly manipulates attention mechanisms to bypass safety alignment in large language models. Our method achieves a **91.2% attack success rate on LLaMA-2**, reduces generation cost by **66%**, and demonstrates strong **cross-model transferability**.

This work reveals a previously unexplored vulnerability at the architectural level of LLMs and highlights the critical role of attention in model alignment and safety. Our findings suggest that alignment defenses must consider internal attention dynamics rather than relying solely on surface-level prompt filtering.
