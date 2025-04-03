---
layout: post
title:  "Model Context Protocol (MCP)"
date:   2025-04-03 09:42 +0000
---

# Motivations

The purpose of this document is to guide Data Scientists on using [Anthropic’s Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) (MCP) for LLM-based applications. While the protocol is relatively old for the AI space, having being released in November 2024, the infrastructure changes required are reasonably large and far from complete.

When first researching the MCP, I found most existing documentation was targeted at software developers with the relevant domain knowledge in protocols and abstraction layers. This document is aimed at Data Scientists (/developers) who, like myself, do not have this knowledge but want to gain a working understanding of the MCP. As models have become more complex, so have the business requests placed upon the applications they power. 

Retrieval-Augmented Generation (RAG) pipelines are becoming a tool of the past. Applications integrated with live context from a wider range of sources are becoming the new normal, and the demand to build these tools increasingly falls not just on sophisticated software teams, but also on willing developers and model builders.

