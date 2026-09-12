---
layout: page
title: Peeling Back the Layers
description: undergraduate thesis — application- and packet-level characterization of ChatGPT inference
img:
importance: 1
category: research
---

**Undergraduate thesis, Princeton University (2025–2026)**
Advised by Prof. Jennifer Rexford and Dr. Hossein Valavi.

End-to-end TLS encryption hides what large-language-model services are doing on the wire. This thesis characterizes the network behavior of ChatGPT purely from the outside, without any access to the provider's datacenter, by analyzing standard browser and packet-level traces.

- Developed a two-layer measurement methodology that combines HTTP Archive (HAR) traces with packet captures (PCAP) to characterize ChatGPT's network behavior from outside the datacenter.
- Built a request classification pipeline and flow identification procedure that decomposes ChatGPT sessions into startup, conversation-turn, and streaming-inference phases across HTTP/2, HTTP/3/QUIC, WebSocket, and SSE.
- Extended the methodology to campus-scale measurement in collaboration with Princeton's Office of Information Technology, analyzing aggregate LLM traffic trends on Princeton's network (July 2025–March 2026) to study the growth and operational footprint of generative AI services on enterprise networks.
- Presented the work to Princeton OIT leadership, where the findings are informing ongoing campus network monitoring and LLM usage analysis.
