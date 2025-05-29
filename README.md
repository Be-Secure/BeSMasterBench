# BeSMasterBench

**Open Source Security, AI Safety & Agentic Capabilities Master Benchmark**

## What is BeS Master Bench?

BeS Master Bench, a key initiative of the **Be-Secure (BeS) ecosystem**, is a comprehensive benchmarking framework. It's designed to evaluate the **Security, Accuracy, Performance, and emerging Agentic Capabilities** of open-source Large Language Models (LLMs) and AI Agentic frameworks. This initiative is provisioned on secure **BeSecure Environments** and utilizes **BeSecure Playbooks** for rigorous validation and verification of results.

Our core goal is to provide a unified and transparent platform for assessing both foundational models and complex AI agents. We achieve this by:
* Aggregating relevant datasets and methodologies from established open-source LLM benchmarks.
* Incorporating and curating leading open-source benchmarks specifically designed for AI agent evaluation.

This holistic approach allows for a comprehensive understanding of model and agent capabilities and limitations across various critical dimensions. It directly contributes to Be-Secure's mission of fostering **Trusted and Verified Open Source Software (TAVOSS)** for the AI domain.

*To understand key terms used throughout BeSMasterBench, please see our **[Project Terminology](./docs/terminology.md)**.*

## Taxonomy of Model & Agent Comparison Parameters

BeS Master Bench employs a structured taxonomy to categorize the parameters used for comparison. While a detailed breakdown will reside in our documentation, key categories include:

* **Intrinsic Parameters:** Assessing inherent model characteristics (e.g., model size, architecture, training data, computational efficiency).
* **Extrinsic Parameters:** Evaluating performance on downstream tasks and real-world applications (e.g., accuracy, generalization, robustness).
* **Domain-Specific Parameters:** Focusing on performance within particular application domains (e.g., code generation, scientific reasoning).
* **Agentic Capability Parameters (Expanding Focus):** Evaluating unique AI agent capabilities such as:
    * Planning and reasoning effectiveness.
    * Tool use proficiency and safety.
    * Multi-turn interaction coherence.
    * Autonomous decision-making quality.
    * Robustness against agent-specific threats (guided by frameworks like OWASP Agentic AI Threats).

## Our Approach to Benchmarking

BeS Master Bench provides a structured workflow for unified and context-aware AI evaluation. This generally involves benchmark aggregation, unified categorization, user selection of tests based on AI application context, standardized execution in Be-Secure environments, and contextual weighting for meaningful risk scores.

* Learn more about our detailed methodology for **[LLM Evaluation within BeSBench](./docs/llm/approach.md)**.
* Our specific approach for **[Agentic AI Testing](./docs/agentic/README.md)** builds upon these principles, tailored for agentic complexities.
* For details on scoring and weighting (initially for LLMs, being extended for agents), see **[Scoring and Weighting Principles](./docs/llm/scoring_weighting.md)**.

## Benchmarking Focus Areas

BeSMasterBench provides targeted evaluations for both core LLM capabilities and advanced agentic systems.

### 1. LLM Core Capabilities Benchmarking

This area focuses on the evaluation of foundational Large Language Models, leveraging datasets and methodologies from key open-source benchmarks.

* **Key LLM Benchmark Categories:**
    * **Security & Risk Benches:** Evaluating harmful content generation, safety alignment, adversarial robustness, and cybersecurity vulnerabilities (e.g., HarmBench, AILuminate, CyBench, CyberSecEval).
    * **Domain-Specific Benches:** Assessing performance in areas like code generation or specialized reasoning (e.g., BirdBench, SWEBench, BaxBench).
* *For an overview of our LLM benchmarking approach and detailed benchmark catalogs, please see the **[LLM Benchmarking Section](./docs/llm/README.md)**.*

### 2. Agentic AI Capabilities Benchmarking

Recognizing the rapid advancements in AI, BeSMasterBench is expanding to rigorously evaluate AI systems exhibiting agentic behaviors such as planning, tool use, and autonomous decision-making.

* **Focus:** Assessing agent effectiveness, safety, security, reliability, and Trust & Safety (T&S) in complex, interactive scenarios.
* **Key Aspects Tested:** General agent capabilities, planning & reasoning, multi-turn interaction, tool proficiency & safety, web navigation, embodied interaction, and robustness against agent-specific threats.
* *For an overview of our Agentic AI benchmarking approach, curated benchmark lists, and T&S testing guidance, please see the **[Agentic AI Benchmarking Section](./docs/agentic/README.md)**. Key resources include:*
    * *A curated list of **[Agentic AI Benchmarks & Testing Tools](./docs/agentic/benchmarks_tools.md)***.
    * *Guidance on **[Leveraging Datasets for Trust & Safety Testing](./docs/datasets_for_ts.md)***.

## Computation of the Open TAVOSS Score

The development and implementation of the **Open TAVOSS Score** is a key future effort on our roadmap. Our vision is for this score to be a unified and openly defined mechanism for BeS Master Bench, designed to eventually cover both foundational LLMs and complex AI Agents.

The score will aim to incorporate weighted metrics derived from evaluations across Security, Accuracy, Performance, and, critically, **Agentic Capabilities**. The specific methodologies for aggregating these diverse metrics, especially for the nuanced aspects of agentic systems, will be developed as part of this roadmap.

We are committed to transparently documenting the computation, weighting, and application of the Open TAVOSS Score as this work progresses, encouraging community understanding and contribution to ensure it becomes a valuable and trusted measure.

* *For ongoing updates and our plans, see our **[Roadmap for the Open TAVOSS Score](./docs/open_tavoss_roadmap.md)**.*

## Contributing to BeSMasterBench

We welcome community contributions to expand our curated lists of benchmarks (for both LLMs and Agents), enhance our evaluation methodologies and BeSecure Playbooks, help integrate new tools, and refine the Open TAVOSS Score.

* Please see our **[Contribution Guidelines](./CONTRIBUTING.md)** to get started.
---
