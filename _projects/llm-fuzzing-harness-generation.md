---
layout: page
title: LLM-based Fuzzing Harness Generation
description: Generating and refining fuzzing harnesses to explore different code regions.
permalink: /projects/llm-fuzzing-harness-generation/
importance: 2
category: research
---

**Status:** Exploratory

I am interested in using LLMs to generate fuzzing drivers, also known as harnesses, for libraries and APIs. A useful harness should be able to explore various code regions, andmust do more than compile: it needs to initialize the target correctly, turn fuzzed bytes into meaningful inputs, and exercise relevant behavior.

### Goal

Explore an LLM-based workflow for generating and refining harnesses that enable a fuzzer to reach and explore different code regions, combining source code and API context with evidence from compilation and execution.

### Directions to Explore

- Infer API usage patterns and initialization requirements from source code, documentation, and examples.
- Generate harnesses that translate fuzzed input into valid API calls.
- Explore different code regions by varying API entry points, call sequences, and input handling in generated harnesses.
- Evaluate harness quality through coverage, target behavior, and reproducible bug discovery.

This direction builds on my interest in AI for software engineering and feedback-driven test generation, including my work on [Refining LLM-based Directed Test Input Generation via Runtime Value Feedback](https://arxiv.org/abs/2608.07926).
