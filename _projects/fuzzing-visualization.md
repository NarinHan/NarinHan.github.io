---
layout: page
title: Fuzzing Visualization
description: Understanding fuzzing campaigns through coverage, corpus, and execution data.
permalink: /projects/fuzzing-visualization/
importance: 1
category: research
---

**Status:** Exploratory

I am interested in making the behavior of fuzzing campaigns easier to inspect and understand. Coverage numbers summarize progress, but they do not fully explain how a fuzzer explores a program or why exploration stalls.

### Goal

Build a visualization tool that connects fuzzing progress with the underlying execution behavior, helping developers and researchers investigate search strategies and understand how inputs lead to new coverage or crashes.

### Directions to Explore

- Track coverage growth and newly discovered execution paths over time.
- Show how the seed corpus evolves and which inputs contribute to exploration.
- Inspect crash discoveries alongside the inputs and execution paths that trigger them.
- Compare fuzzing strategies using their campaign traces.

This project connects my interests in fuzzing, software testing, and program analysis.
