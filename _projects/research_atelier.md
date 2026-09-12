---
layout: page
title: Research Atelier
description: an AI-native research workspace — TreeHacks 2026, Stanford
img:
importance: 1
category: side projects
---

**TreeHacks 2026, Stanford University (Spring 2026)**

Research Atelier is an end-to-end research platform that brings paper discovery, semantic understanding, and one-click reproducibility into one place.

- Papers are ingested from arXiv, chunked, and indexed with Elasticsearch and Jina embeddings for passage-level retrieval-augmented generation (RAG).
- Referenced GitHub repositories are deployed into Modal sandboxes and bootstrapped by Claude Code, so a paper's code can be run right away.
- I implemented the retrieval and agent layer (Elastic Agent Builder with a tool-use loop over GPT-4o-mini and `semantic_text` indexing) and the Modal sandbox execution pipeline, with pre-warming to minimize cold-start latency.
