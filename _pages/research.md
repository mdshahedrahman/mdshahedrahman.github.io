---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
body_class: homepage research-page
excerpt: "AI supply-chain security, model provenance, agent security, and trustworthy edge AI."
---

<div class="research-intro" markdown="1">
<p class="research-eyebrow">Security &amp; trustworthiness of AI systems</p>

My research asks how we can make AI systems **traceable, auditable, and secure** as they are developed, adapted, and deployed. I focus on **AI supply-chain security**, **model provenance**, and **vulnerability propagation** across base models and their derivatives.

Modern AI is rarely built from scratch. Models are fine-tuned, quantized, merged, extended with adapters, and deployed inside autonomous agents. I use **graph-based methods, static analysis, and large-scale empirical evaluation** to understand these relationships and how security risks travel through them. My work also explores agent security and trustworthy, resource-efficient edge AI.

<p class="research-resources"><a href="{{ '/publications/' | relative_url }}">Publications &amp; manuscripts <span aria-hidden="true">&rarr;</span></a> <a href="{{ '/files/CV_Academic_Shahed.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">CV <span aria-hidden="true">&rarr;</span></a></p>
</div>

<nav class="research-nav" aria-label="Research themes">
<a href="#supply-chain"><span aria-hidden="true">01</span> AI supply chain</a>
<a href="#vulnerability-propagation"><span aria-hidden="true">02</span> Vulnerability propagation</a>
<a href="#agent-security"><span aria-hidden="true">03</span> Agentic AI security</a>
<a href="#edge-ai"><span aria-hidden="true">04</span> Edge AI</a>
<a href="#applied-security"><span aria-hidden="true">05</span> Applied security</a>
</nav>

<section class="research-area" aria-labelledby="supply-chain" markdown="1">
<p class="research-number" aria-hidden="true">01</p>

## AI Supply-Chain Security and Model Provenance {#supply-chain}

Open model hubs such as *Hugging Face* now host millions of models. Each one may derive from a base model through *fine-tuning*, *adapters*, *quantization*, or *merging*, and depend on datasets and code from many sources. These relationships form a large and largely undocumented **AI supply chain**. Lineage declarations are often missing, incomplete, or inconsistent, which makes it hard to answer basic security questions: *Where did this model come from? What does it inherit? Who is affected when an upstream model is found to be unsafe?*

My research models this ecosystem as a graph and develops methods to **characterize**, **audit**, and **recover** model provenance at scale. Selected projects are outlined below.

<article class="research-project" markdown="1">
### HuggingGraph: Understanding the Supply Chain of LLM Ecosystem

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">ACM CIKM 2025</a>

- Built a heterogeneous graph of the Hugging Face LLM ecosystem with **402,654 entities** and **462,524 relationships**, capturing model derivation, fine-tuning, adapters, quantization, merging, and dataset dependencies.
- Analyzed ecosystem structure, connectivity, and provenance gaps to enable graph-based AI supply-chain analysis.
- Released public graph datasets, documentation, and a companion repository to support reproducibility.
</article>

<article class="research-project" markdown="1">
### ProvCode: Static Auditing of Provenance Carryover for Hugging Face Models

<span class="research-status">Under review, ICSE 2027</span>

- Developed static-analysis methods to check whether model repositories and their source code preserve upstream provenance claims.
- Examined inconsistencies between *declared* and *code-derived* lineage across roughly **75,000 Hugging Face models**.
</article>

<article class="research-project" markdown="1">
### ChainInfer: Graph-Based Model Provenance Inference

<span class="research-status">Under review, WWW</span>

- Investigates recovery of *missing* model-to-model lineage relationships using graph topology, repository metadata, and learned representations.
- Aims to reconstruct hidden upstream dependencies that model cards and metadata fail to declare.
</article>

<article class="research-project" markdown="1">
### Large-Scale Model Lineage Analysis

<span class="research-status">Ongoing</span>

- Extended data collection and dependency extraction to about **three million Hugging Face model records**, studying missing, incomplete, and nonstandard lineage declarations across the broader ecosystem.
</article>

</section>

<section class="research-area" aria-labelledby="vulnerability-propagation" markdown="1">
<p class="research-number" aria-hidden="true">02</p>

## Vulnerability Propagation Across Model Derivatives {#vulnerability-propagation}

If a base model behaves unsafely, do its descendants inherit that behavior? Supply-chain security depends on understanding how **vulnerabilities propagate** through adaptation. This line of work runs controlled, large-scale experiments to measure whether security weaknesses persist, weaken, or amplify as models are fine-tuned, adapted, and compressed.

<article class="research-project" markdown="1">
### VulChain: AI Supply-Chain Vulnerability Propagation

<span class="research-status">Manuscript Revision in Progress</span>

- Designed controlled empirical evaluations to test whether unsafe behaviors, including **package hallucination** and **insecure URL generation**, persist through fine-tuning, adapter-based adaptation, and quantization.
- Measured vulnerability persistence using matched prompts and validated detectors across base models and their derivatives.
</article>

<article class="research-project" markdown="1">
### ChronoResolve: Retrospective Artifact Resolution for Model Lineage

<span class="research-status">Research in Progress</span>

- Investigates the identification of *historical upstream artifacts* a model was derived from, using file hashes, configurations, weight signatures, and temporal evidence.
- Aims to reduce lineage ambiguity to support **reproducible provenance** and **security auditing**.
</article>

</section>

<section class="research-area" aria-labelledby="agent-security" markdown="1">
<p class="research-number" aria-hidden="true">03</p>

## Agentic and Multi-Agent AI Security {#agent-security}

LLMs are increasingly deployed as **autonomous agents** that call tools, process multimodal inputs, and collaborate with other agents. This creates new attack surfaces: a single injected prompt can cross trust boundaries, spread between agents, and trigger unsafe real-world actions. My research builds systematic tools to **expose** these failures and **defend** against them at runtime.

<article class="research-project" markdown="1">
### AgentFuzz: Trace-Level Fuzzing for Prompt Spillover in LLM Multi-Agent Systems

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">IEEE ICMLA 2026</a>

- Developed a trace-level fuzzing framework to study how adversarial prompts *spill over* across interacting LLM agents.
- Evaluated attack propagation across communication topologies, injection channels, and verification configurations to characterize security failures in multi-agent workflows.
</article>

<article class="research-project" markdown="1">
### DiscoAct: Securing Autonomous Multimodal LLM Agents Against Cross-Modal Trust Flattening

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">IEEE ICTAI 2026 · Accepted, to appear</a>

- Developed a **model-agnostic runtime verification framework** that combines symbolic policy validation, cross-modal consistency checking, and knowledge–environment alignment.
- Evaluated it on **240 adversarial scenarios** across three LLM backbones, preventing **94.2% of unsafe actions**.
</article>

</section>

<section class="research-area" aria-labelledby="edge-ai" markdown="1">
<p class="research-number" aria-hidden="true">04</p>

## Trustworthy and Resource-Efficient Edge AI {#edge-ai}

Deploying AI on edge devices means working with tight compute budgets and often low-quality inputs. This work develops **lightweight, semantic-guided learning** methods that keep visual recognition robust and reliable under these constraints.

<article class="research-project" markdown="1">
### LiteAugNet: Lightweight Semantic-Guided Augmentation for Edge-Level Image Classification

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">ICPR 2026</a>

- A lightweight semantic-guided augmentation network that improves low-resolution image classification while respecting the compute limits of edge environments.
</article>

<article class="research-project" markdown="1">
### SEGA-Net: LLM-Guided Semantic-Enhanced GAN Augmentation for Low-Resolution Image Classification

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">IEEE AIxDKE 2026</a>

- Combines LLM-guided semantic augmentation with generative image synthesis to improve low-resolution visual recognition.
</article>

<article class="research-project" markdown="1">
### LiteAdapt: Adaptive Semantic Augmentation for Resource-Constrained Edge Environments

<span class="research-status">Journal Manuscript in Preparation</span>

- Extends semantic-guided augmentation with reliability-aware sample weighting, adaptive verification, and dynamic resource allocation.
</article>

<article class="research-project" markdown="1">
### SEGA-COM: Semantic-Reliability-Aware Generative Communication and Energy Allocation

<span class="research-status">Under review, ICC 2027</span>

- Brings semantic-reliability awareness to generative communication and energy allocation.
</article>

</section>

<section class="research-area" aria-labelledby="applied-security" markdown="1">
<p class="research-number" aria-hidden="true">05</p>

## Applied Security Research {#applied-security}

Alongside AI security, I work on practical vulnerability assessment for high-performance and containerized infrastructure.

<article class="research-project" markdown="1">
### Beyond CVSS: Context-Aware Exploitability Assessment of Vulnerabilities in HPC Containers

<a class="research-status research-status--published" href="{{ '/publications/' | relative_url }}">IEEE Cloud Summit 2026</a>

- Assesses vulnerability exploitability in HPC containers using deployment context, going beyond generic CVSS severity scores.
</article>

</section>

<div class="research-closing" markdown="1">
Interested in research on AI provenance, supply-chain security, or secure agents? [Get in touch]({{ '/contact/' | relative_url }}).
</div>
