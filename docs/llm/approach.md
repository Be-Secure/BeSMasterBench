# The BeSBench Approach

BeSBench provides a structured workflow for unified and context-aware AI evaluation:

### 1. Benchmark Aggregation
BeSBench identifies and incorporates relevant test cases, probes, and datasets from established open-source benchmarks like AILuminate, CyberSecEval3, Garak, HarmBench, and potentially others.

### 2. Unified Categorization & Classification
Tests from various sources are mapped onto a standardized BeSBench taxonomy (see [[Benchmark Catalog]]). Each category in this taxonomy is classified by:
* **Domain:** Safety, Security, Both, Other
* **Assessment Type:** Intrinsic, Extrinsic

This provides clarity on what each test evaluates.

### 3. User Selection & Configuration
Via a simple interface (the BeSBench utility):
* Users select/enter a **Use Case Profile** reflecting their AI application context.
* Guided by the classification, users select **relevant test categories or specific test cases** for evaluation. They can choose broad areas or target specific vulnerabilities.
* Users configure the target AI model/system details and execution parameters.

### 4. Contextual Weighting 
Based on the selected Use Case Profile, manual/pre-defined **weights** reflecting risk criticality for that context are automatically associated with the selected test categories.

### 5. Standardized Execution
BeSBench orchestrates the execution of the selected test cases using standardized **Be-Secure (BeS) environments and playbooks**, ensuring consistency and reproducibility.

### 6. Scoring & Reporting
* Raw results from executed tests are collected.
* Results are **normalized** onto a common scale.
* Normalized scores are combined using the context-specific **weights** to calculate meaningful risk scores (e.g., via weighted average).
* Scores are translated into risk levels (Low/Medium/High).
* *(Roadmap: This process will culminate in the Open TAVOSS Score)*.

This approach moves beyond isolated benchmark runs to provide a holistic, context-aware assessment.
