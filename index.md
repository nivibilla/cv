---
layout: cv
title: Srinivas Billa's CV
---

***

# SRINIVAS BILLA

**Email:** nivibilla@gmail.com
**LinkedIn:** [linkedin.com/in/srinivasbilla](https://linkedin.com/in/srinivasbilla)

---

## PROFESSIONAL SUMMARY

Applied ML Scientist / AI Engineer with a Master's in Data Science and extensive experience designing and shipping AI systems at scale. Specialised in building end-to-end agentic workflows, optimising large language model inference for production, and developing multimodal search engines serving 50M+ monthly users. Proven track record of taking research from prototype to production — including two patents, a NAACL 2025 publication, and measurable business impact. Core expertise spans agentic orchestration & tooling, applied research (finetuning / reinforcement learning), and ML system design.

---

## TECHNICAL SKILLS

**Languages & Frameworks**
Python • PyTorch • PySpark • Ray • Flyte

**Generative AI & LLMs**
vLLM / sglang / TensorRT-LLM • langchain / langgraph • TRL / prime-rl

---

## PROFESSIONAL EXPERIENCE

### **Applied ML Scientist / AI Engineer III** • Expedia Group
*London, UK | January 2025 – Present*

Transitioned to a full-stack Applied Science role, focusing on ML System Design, Orchestrator APIs, and live/batch deployments while leading research initiatives.

**Aggregated Content Embeddings Semantic Search (ACES)**

Architected and built the ACES engine — the backbone for "Property Expert," a grounded, multi-turn agentic RAG system designed to function as a truth layer for hotel and vacation rental queries.

*   Built a multimodal retrieval system over 500M+ embeddings (text, image, structured attributes) serving 50M+ monthly Expedia visitors, with ruthless latency optimisation to meet a <50ms budget for image and review ranking.
*   Multimodal Hierarchical Embeddings (Patented) for efficient graph-like traversal of 500M+ embeddings enabling destination discovery, property selection & ranking, and personalisation.
*   Designed for low-latency retrieval to power AI Shopping, Ranking, and Content Generation features across the platform.
*   Architected and built an orchestration interface (MCP, CodeAct) to allow LLMs to interact directly with the search engine.

**Trip Planner Agent**

Developing a long-horizon, end-to-end multi-agent travel planner optimised for complex reasoning, discovery, and itinerary building, reusing the ACES engine.

**Hallucination Quantification**

Research on faithfulness evaluation in GenAI; work accepted at NAACL 2025. Developed TravelBench, a domain-specific benchmark for travel tasks.

---

### **AI Engineer (GIG)** • Expedia Group (Legal & Corporate Affairs)
*London, UK | January 2026 – Present | Internal Rotation (50%)*

**Contract Intelligence**
*   Replaced a fully manual, months-long legal review process for 1M+ legacy hand-scanned PDF contracts with an agentic pipeline (multimodal LLMs + embedding models) that intelligently routes straightforward contracts through automated processing and flags complex ones for human review — reducing legal risk exposure and cutting processing time from months to days.
*   End-to-end ownership of prototyping, batch Flyte pipeline deployments, and langgraph + FastAPI orchestration.

**Agentic Legal Workflows**

Built an "IP Research Agent" for patentability assessments and automated contract drafting/Q&A, with a focus on high compliance and explainability.

---

### **Machine Learning Scientist II** • Expedia Group
*London, UK | August 2022 – January 2025*

Traveller Voice & Content Team: combined applied engineering and research using large language and multimodal models.

**Review Summarisation System (Patented)**

Led the development of a large-scale RAG-style offline summarisation system processing 100M+ reviews across millions of properties, improving traveller trust metrics and delivering £500K+ gross profit uplift annually.

**LLM Optimisation & Finetuning**
*   Finetuned a 7B model with QLoRA to outperform GPT-4 on aspect-based sentiment analysis, topic segmentation, and summarisation — achieving domain adaptation for Expedia's style and tone that prompting alone could not reach.
*   Applied Reinforcement Learning with verifiable rewards for further domain adaptation and quality improvement.

**Infrastructure & Deployment**
*   Achieved a 20x inference speedup over native PyTorch by adopting vLLM, and a further 5x throughput improvement over Spark by migrating to Ray for disaggregated CPU/GPU computing — minimising GPU idle time across multi-node, multi-GPU pipelines.
*   Contributed to and adopted frameworks including vLLM and SGLang to create cost-effective large-scale batch pipelines.

---

### **Machine Learning Scientist Intern** • Expedia Group
*London, UK | Summer 2021*

*   Conducted a model review on an image ranking model for hero image personalisation.
*   Identified model biases and recommended architecture changes that improved both performance and efficiency.

---

## PUBLICATIONS

**On A Scale From 1 to 5: Quantifying Hallucination in Faithfulness Evaluation**
Accepted at the Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2025)

**TravelBench: Exploring LLM Performance in Low-Resource Domains**
arXiv release

**Multimodal Hierarchical Embeddings for Efficient Hotel Retrieval and Ranking**
In Preparation

**PDP-2-Vec: Multimodal, Multivector Embeddings for Contextual Selection and Ranking**
In Preparation

---

## EDUCATION

### **MSci Data Science** • University of Warwick
*United Kingdom | 2018 – 2022*
*Accredited by the Royal Statistical Society*

**Thesis:** "Using Reinforcement Learning Approaches to Trading" — investigated algorithmic trading strategies, using quantitative analysis to compare LSTM-based algorithms against traditional rule-based methods.

---

## PREVIOUS EXPERIENCE

**Product Manager Intern** • Crypcentra | *August 2020 – October 2020*

**Summer Intern** • Euroclear | *August 2018*

---
*CV Last Updated: February 2026*
