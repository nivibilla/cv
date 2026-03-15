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

Applied ML Scientist / AI Engineer with a Master's in Data Science and extensive experience designing and shipping AI systems at scale. Specialised in building end-to-end agentic workflows, optimising large language model inference for production, and developing multimodal search engines serving 50M+ monthly users. Proven track record of taking research from prototype to production — including two patents, a NAACL 2025 publication, multiple hackathon wins, and measurable business impact across Expedia, VRBO, and Hotels.com. Core expertise spans agentic orchestration & tooling, applied research (finetuning / reinforcement learning), and ML system design.

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

Applied Science role, Prototyping, ML System Design, Orchestration APIs, and live/batch deployments while also leading research initiatives.

**Aggregated Content Embeddings Semantic Search (ACES)**

Architected and built the ACES engine — a generalised backbone service for agentic RAG systems, natural language informed destination/property recommendations and contextual personalisation, all solved through a single interface. Designed to function as a truth layer for a more AI-Native travel search product.

*   Built a multimodal retrieval system over 500M+ embeddings (text, image, structured attributes) acrossExpedia, VRBO, and Hotels.com, with ruthless latency optimisation to meet a <50ms budget for image and review ranking.
*   Multimodal Hierarchical Embeddings (Patented) for efficient graph-like traversal of 500M+ embeddings enabling destination discovery, property selection & ranking, and personalisation.
*   Designed for low-latency retrieval to power AI Shopping, Ranking, and Content Generation features across the platform.
*   Architected and built a unified orchestration interface that integrates semantic retrieval of content across ranking services and agents.
*   Designed and implemented simulated search & ranking environments for training and evaluating agents with RL.

**Agents**
*   **Property Expert** - A question answering chatbot that uses the aforementioned ACES architecture to retrieve context related to the user's question, reason across many sources like reviews, images, geo data, activities etc to best answer the users question.
*   **Property Ground Truth Validation** - A moderation agent, that takes any piece of information of unknown source about a property and using the ACES engine to fetch all relevant ground truth that we know as a host. Reason and bucket the data for use or quarantine. Reducing hallucinated content to be shown to the user and automating the verification of scraped property content.
*   **Trip/Itinerary Planner** - Again, using the aggregate content. Developing a long-horizon, end-to-end multi-agent travel planner optimised for complex reasoning, discovery, and itinerary building.

**Research**
*   **Hallucination Quantification** - Research on faithfulness evaluation in LLM generated content. Accepted at [NAACL](https://aclanthology.org/2025.findings-naacl.433/)
*   **[TravelBench](https://arxiv.org/abs/2510.02719)**, a domain-specific benchmark for low resource domains like LLM use in the travel domain.
*   WIP - Hierarchical Embeddings for efficient discovery, search & ranking through natural language.
*   WIP - TravelBench V2 - Rewrite of V1 as RL Environments, for simulated training and evaluation of travel domain tasks in a unified framework.
---

### **AI Engineer (GIG)** • Expedia Group (Legal & Corporate Affairs)
*London, UK | January 2026 – March 2026 | Internal Rotation (50%)*

**Contract Intelligence**
*   Replaced a fully manual, months-long legal review process for 1M+ legacy hand-scanned PDF contracts with an agentic pipeline (multimodal LLMs + embedding models) that intelligently routes straightforward contracts through automated processing and flags complex ones for human review — reducing legal risk exposure and cutting processing time from months to days.
*   End-to-end ownership of prototyping, batch Flyte pipeline deployments, and langgraph + FastAPI orchestration.

**Agentic Legal Workflows**

Built an "IP Research Agent assessments and automated contract drafting/Q&A, with a focus on high compliance and explainability. Using swarms of research agents to capture a breadth of information related to patentability assessments.

---

### **Machine Learning Scientist II** • Expedia Group
*London, UK | August 2022 – January 2025*

Traveller Voice & Content Team: combined applied engineering and research using large language and multimodal models across Expedia, VRBO, and Hotels.com.

**Review Summarisation Suite**

Led end-to-end development of a large-scale RAG-style summarisation platform processing 100M+ reviews across millions of properties — expanding from amenity-level summaries to 100+ topic categories across all three brands, improving traveller trust metrics and delivering $500K+ gross profit uplift annually.

*   Amenity Review Summarisation (ARS): Built the initial pipeline using a deconstructed offline RAG-like system over 50M+ reviews, fine-tuning an in-house Mistral 7B model with qlora adapters for aspect-based sentiment analysis, topic segmentation and summarisation that outperformed GPT-4 across accuracy, hallucination and style/tone metrics
*   Finetuning for domain adaption, especially tone, style that prompting alone could not solve.
*   Uplift of 500K of annualised GP
*   Refactored into a generalised REview CAtegorical snippet, SEntiment, summarisation capability (RECASE)

**Affinity Scoring**

Reusing the above mentioned RECASE data product, auto tagged properties with custom affinities that powered downstream recommendations, causing an uplift of annualised $5.4M GP

**Neighbourhood Descriptions**

*   Built a distributed Spark pipeline to collect Wikipedia data and generat descriptions with LLMs
*   $10k uplift

**LLM Optimisation & Infrastructure**
*   Achieved a 20x inference speedup over native PyTorch by adopting vLLM, and a further 5x throughput improvement over Spark by migrating to Ray for disaggregated CPU/GPU computing — minimising GPU idle time across multi-node, multi-GPU pipelines and cutting batch runtimes from days to hours.
*   Served as the primary point of contact between the Traveller Voice & Content team and the ML Platform team, enabling internal LLM hosting across notebooks, evaluation, and pipeline migration from Databricks.
*   Applied Reinforcement Learning with verifiable rewards for domain adaptation and quality improvement.

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

*Two further papers in preparation on multimodal hierarchical embeddings and multivector representations for hotel retrieval and ranking.*

---

## PATENTS

**Review Summarisation at Expedia Group**
Provisional patent awarded September 2024 — large-scale RAG-style review summarisation system. *Shared with Rajesh Gupta.*

**Personalised Themed Selection for Enhanced Search (Hierarchical Embeddings)**
Provisional patent awarded August 2025 — multimodal hierarchical embeddings for efficient hotel retrieval and ranking. *With Xiaonan Jing and Olivier Roncalez.*

---

## HACKATHONS & AWARDS

**Global Hackathon 2024 — 1st Place (Global Winner)**
*"Can You Hear the LLM?"* — A multilingual voice-to-voice assistant designed to empower travellers with disabilities and break language barriers.

**Traveller Native Hackathon 2024 — 2nd Place (Global)**
*"LLMs at the Edge"* — Edge device LLM inference on a user's mobile.

**Global Hackathon 2023 — 3rd Place (EMEA)**
*"EIMAGEN"* — Used gaussian splatting 3D reconstruction algorithms to reconstruct a room from video/images.

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
