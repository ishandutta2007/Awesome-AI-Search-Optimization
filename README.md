# Awesome AI Search Optimization (GEO & LLMO) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated directory of leading SaaS platforms, open-source developer tooling, specifications (`llms.txt`), and evaluation frameworks for **Generative Engine Optimization (GEO)**, **Large Language Model Optimization (LLMO)**, and **AI Answer Engine Visibility (AEO)**.

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-AI-Search-Optimization?style=flat-square)](https://github.com/ishandutta2007/Awesome-AI-Search-Optimization/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ishandutta2007/Awesome-AI-Search-Optimization?style=flat-square)](https://github.com/ishandutta2007/Awesome-AI-Search-Optimization/network/members)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 📌 Overview

As internet discovery shifts toward conversational answer engines (**ChatGPT Search**, **Perplexity**, **Google AI Overviews**, **Claude**, and **Microsoft Copilot**), traditional SEO is evolving into **Generative Engine Optimization (GEO)** and **LLM Optimization (LLMO)**. 

This repository tracks the emerging tech stack powering AI search visibility:
- **SaaS Intelligence Platforms**: Continuous prompt tracking, citation share-of-voice, AI crawler bot monitoring, and brand sentiment analytics.
- **Open-Source Toolkits**: Self-hosted AI search engines, headless web scrapers optimized for LLM token ingestion, prompt-testing harnesses, and automated `llms.txt` generators.
- **Structured Protocols**: Modern standards (e.g. `/llms.txt`, `JSON-LD`) ensuring AI crawlers parse factual, citation-ready brand knowledge.

---

## 📑 Table of Contents

- [What is GEO & LLMO?](#what-is-geo--llmo)
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
  - [llms.txt Generators & Standards](#llmstxt-generators--standards)
  - [AI Search Simulators & RAG Retrieval](#ai-search-simulators--rag-retrieval)
  - [LLM Crawler Auditing & Markdown Scrapers](#llm-crawler-auditing--markdown-scrapers)
  - [Citation Benchmarking & Prompt Evaluation](#citation-benchmarking--prompt-evaluation)
  - [Structured Data, Technical SEO & Log Analytics](#structured-data-technical-seo--log-analytics)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## 💡 What is GEO & LLMO?

| Acronym | Full Form | Primary Focus |
|:---|:---|:---|
| **GEO** | Generative Engine Optimization | Optimizing web content and digital footprint to be cited as authoritative sources in generative AI responses. |
| **LLMO** | Large Language Model Optimization | Structuring documentation, datasets, and context (`llms.txt`) for ingestion and synthesis by LLMs. |
| **AEO** | Answer Engine Optimization | Direct question-and-answer positioning for voice assistants and conversational bots. |

---

## ☁️ SaaS / Hosted Platforms

Below is a comparison of top commercial platforms for tracking brand mentions, citation frequency, and prompt placement across generative engines.

| Product | Focus & Core Features | Supported Engines | Pricing & Plans | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|
| **[Profound](https://tryprofound.com)** | Enterprise GEO platform tracking brand mentions, citation share, bot traffic, and AI shopping placement. | ChatGPT, Perplexity, Google AI Overviews | Starter: $99/mo<br>Growth: $399/mo<br>Enterprise: Custom | 7-day free trial; paid starter tracks 50 prompts |
| **[Otterly.AI](https://otterly.ai)** | Automated prompt monitoring, link citation audits, and brand sentiment analytics. | ChatGPT, Perplexity, Gemini, Copilot | Lite: $29/mo<br>Standard: $189/mo<br>Premium: $489/mo | No free tier; entry plan covers 15 search prompts |
| **[Peec AI](https://peec.ai)** | Share-of-voice analytics, citation attribution, and competitor ranking benchmarks. | ChatGPT, Perplexity, Google AI Overviews | Starter: $95/mo<br>Pro: $245/mo<br>Advanced: $495/mo | 14-day free trial; plans scale with prompt-model combos |
| **[Scrunch AI](https://scrunchai.com)** | Enterprise Agent Experience Platform (AXP) auditing AI crawler gaps and hallucinated narratives. | ChatGPT, Perplexity, Copilot, Google AI Overviews | Core: $250/mo<br>Agency: $500/mo<br>Enterprise: Custom | Interactive demo available; Core plan covers 125 prompts / 5k responses |
| **[AthenaHQ](https://athenahq.ai)** | End-to-end GEO platform providing multi-engine visibility tracking and AI content recommendations. | ChatGPT, Perplexity, Claude, Gemini, Copilot (11 models) | Starter: $295/mo<br>Enterprise: Custom | **Free Tier available**: 300 credits across 5 engines with unlimited seats |
| **[Rankscale](https://rankscale.ai)** | Dedicated GEO visibility scoring, citation health audits, and LLM crawlability tests. | ChatGPT, Perplexity, Gemini, Claude, Copilot | Essentials: ~$20/mo (billed annually)<br>Pro: $99/mo<br>Growth: $385/mo | Free diagnostic lookup; Essentials includes 120 query credits |
| **[Attensira](https://attensira.com)** | Brand positioning intelligence and technical optimization recommendations for AI search. | ChatGPT, Perplexity, Gemini, Claude | Starter: $129/mo<br>Growth: $299/mo<br>Business: $649/mo | 7-day free trial; Starter covers 50 prompts with daily refresh |
| **[Dageno AI](https://dageno.ai)** | GEO visibility tracking combined with traditional SEO integrations (Semrush/Ahrefs) and agents. | ChatGPT, Perplexity, Google AI Overviews | Starter: $67/mo<br>Growth: $199/mo<br>Scale: $499/mo | **Free Tier available**: Free browser lookups & basic diagnostics |
| **[Geoptie](https://geoptie.com)** | On-page LLM readiness scoring, competitor citation tracking, and automated `llms.txt` generation. | ChatGPT, Perplexity, Claude, Copilot, Gemini | Starter: $49/mo<br>Professional: $99/mo<br>Enterprise: $333/mo | Free website GEO scan; Starter includes 15 daily prompts |
| **[KIME](https://kime.ai)** | AI brand presence, sentiment analysis, and source attribution monitoring across conversational bots. | ChatGPT, Perplexity, Copilot | Explorer: €99/mo (~$109)<br>Core: €399/mo<br>Enterprise: Custom | Free guided demo; Explorer tier tracks 50 prompts across 2 engines |

---

## 🛠️ Open-Source GitHub Projects

An exhaustive collection of open-source repositories for building, auditing, evaluating, and self-hosting AI search optimization workflows.

### `llms.txt` Generators & Standards

- **[`llms.txt` Specification & Tooling (`AnswerDotAI/llms-txt`)](https://github.com/AnswerDotAI/llms-txt)**  
  *License: Apache-2.0*  
  The foundational open-source standard and Python CLI/parser from Answer.AI defining `/llms.txt` and `/llms-full.txt` files so websites can serve clean, structured Markdown context to LLMs and AI search crawlers.

- **[llmstxt-generator (`mendableai/llmstxt-generator`)](https://github.com/mendableai/llmstxt-generator)**  
  *License: MIT*  
  Open-source crawler and generator built on Firecrawl that automatically crawls any target website and compiles clean, valid `llms.txt` and `llms-full.txt` files ready for AI indexers.

- **[vitepress-plugin-llms (`okineadev/vitepress-plugin-llms`)](https://github.com/okineadev/vitepress-plugin-llms)**  
  *License: MIT*  
  Build-time documentation plugin that automatically generates LLM-friendly Markdown bundles and `llms.txt` indexes for VitePress documentation sites.

- **[Docling (`docling-project/docling`)](https://github.com/DS4SD/docling)**  
  *License: MIT*  
  High-accuracy document conversion library that transforms PDFs, DOCX, and presentations into clean Markdown and JSON suitable for `llms-full.txt` context files.

- **[MarkItDown (`microsoft/markitdown`)](https://github.com/microsoft/markitdown)**  
  *License: MIT*  
  Python utility from Microsoft for converting diverse file formats (PDF, Word, Excel, PowerPoint) into clean Markdown for LLM ingestion.

---

### AI Search Simulators & RAG Retrieval

- **[Perplexica (`ItzCrazyKns/Perplexica`)](https://github.com/ItzCrazyKns/Perplexica)**  
  *License: MIT*  
  Leading open-source self-hosted AI search engine powered by SearXNG and local/cloud LLMs. Essential for reverse-engineering how RAG answer engines retrieve, rank, and cite web documents.

- **[SearXNG (`searxng/searxng`)](https://github.com/searxng/searxng)**  
  *License: AGPL-3.0*  
  Privacy-respecting open-source metasearch engine aggregating 70+ search engines with clean JSON API output; widely used as the retrieval backend for custom AI search pipelines.

- **[GPT-Researcher (`assafelovic/gpt-researcher`)](https://github.com/assafelovic/gpt-researcher)**  
  *License: Apache-2.0*  
  Autonomous agent that aggregates 20+ web sources per query to produce comprehensive reports, providing insight into citation selection and multi-source synthesis.

- **[STORM (`stanford-oval/storm`)](https://github.com/stanford-oval/storm)**  
  *License: MIT*  
  Stanford’s LLM framework for synthesizing multi-perspective, citation-grounded long-form articles from live internet search results.

---

### LLM Crawler Auditing & Markdown Scrapers

- **[Crawl4AI (`unclecode/crawl4ai`)](https://github.com/unclecode/crawl4ai)**  
  *License: Apache-2.0*  
  High-speed, open-source LLM-friendly web crawler that converts web pages into clean Markdown, chunked and prepared for AI extraction and RAG pipelines.

- **[Firecrawl (`mendableai/firecrawl`)](https://github.com/mendableai/firecrawl)**  
  *License: AGPL-3.0*  
  Web-to-Markdown crawling engine designed for LLM bots, auditing dynamic JavaScript content, and generating AI-ready sitemaps.

- **[Browser-Use (`browser-use/browser-use`)](https://github.com/browser-use/browser-use)**  
  *License: MIT*  
  Make websites accessible for AI agents via automated browser interactions, ideal for auditing interactive consumer search experiences across ChatGPT and Perplexity.

- **[Playwright (`microsoft/playwright`)](https://github.com/microsoft/playwright)**  
  *License: Apache-2.0*  
  Reliable end-to-end browser automation framework for running programmatic tests and screenshots of live answer engine interfaces.

---

### Citation Benchmarking & Prompt Evaluation

- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com/promptfoo/promptfoo)**  
  *License: MIT*  
  Test-driven evaluation CLI and harness used by technical SEOs to execute repeatable prompt matrices across ChatGPT, Perplexity, Claude, and Gemini to track brand mentions and citation URLs over time.

- **[DeepEval (`confident-ai/deepeval`)](https://github.com/confident-ai/deepeval)**  
  *License: Apache-2.0*  
  Unit-testing framework for LLMs used in GEO pipelines to evaluate hallucination rates, source faithfulness, and brand accuracy against ground-truth documentation.

- **[Ragas (`explodinggradients/ragas`)](https://github.com/explodinggradients/ragas)**  
  *License: Apache-2.0*  
  RAG evaluation framework measuring context precision, context recall, and citation faithfulness in search-augmented generation.

- **[Langfuse (`langfuse/langfuse`)](https://github.com/langfuse/langfuse)**  
  *License: Apache-2.0*  
  Open-source LLM observability platform to trace, monitor, and log model prompts, citation consistency, and latency across ongoing SEO audit experiments.

- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com/Arize-ai/phoenix)**  
  *License: ELv2*  
  AI observability platform for tracing evaluations, embedding drift, and retrieval quality in enterprise RAG systems.

---

### Structured Data, Technical SEO & Log Analytics

- **[Schema.org Vocabularies (`schemaorg/schemaorg`)](https://github.com/schemaorg/schemaorg)**  
  Structured data schema definitions (`JSON-LD`, `Microdata`) essential for knowledge graph disambiguation, entity clarity, and AI engine fact verification.

- **[SerpBear (`towfiqi/serpbear`)](https://github.com/towfiqi/serpbear)**  
  *License: MIT*  
  Self-hosted search engine position tracking application with REST APIs to correlate traditional Google rankings against AI answer engine citation frequency.

- **[SiteOne Crawler (`janreges/siteone-crawler`)](https://github.com/janreges/siteone-crawler)** & **[Greenflare (`GreenflareSEO/greenflare`)](https://github.com/GreenflareSEO/greenflare)**  
  Fast open-source crawlers for analyzing canonical declarations, status codes, and `robots.txt` directives targeting AI crawlers (`GPTBot`, `PerplexityBot`, `ClaudeBot`, `Google-Extended`).

- **[Umami (`umami-software/umami`)](https://github.com/umami-software/umami)** & **[Matomo (`matomo-org/matomo`)](https://github.com/matomo-org/matomo)**  
  Privacy-friendly analytics platforms easily configured with custom filters to track inbound referral traffic from `chatgpt.com`, `perplexity.ai`, and `claude.ai`.

---

## 🤝 How to Contribute

Contributions are warmly welcome! Help keep this ecosystem guide up-to-date:

1. **Fork** the repository.
2. Create a feature branch: `git checkout -b feature/add-new-tool`.
3. Add the project with factual details, primary documentation links, license info, and if it's a SaaS product, complete pricing details including free tier limits.
4. Keep the list sorted and cleanly formatted.
5. Submit a **Pull Request** with a concise description of the addition.

---

## ⚖️ Disclaimer

*All trademarks, logos, and brand names are the property of their respective owners. Mention of commercial products or open-source projects does not imply endorsement.*
