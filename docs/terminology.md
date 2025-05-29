# BeSBench Terminology

Understanding the terms used in BeSBench is key to leveraging the framework effectively.

## AI Safety
Focuses on preventing unintended harm *from* AI systems by ensuring they operate reliably, predictably, fairly, and align with human values. Addresses risks from the AI's own outputs, behaviors, or failures.

## AI Security
Focuses on protecting AI systems, data, and infrastructure *from* intentional threats, unauthorized access, or malicious manipulation. Addresses vulnerabilities exploitable by adversaries (Confidentiality, Integrity, Availability).

## Intrinsic Assessment
Evaluates inherent properties, vulnerabilities, biases, or behaviors **of the AI model itself** or its direct input/output handling, regardless of specific downstream tasks.
*Examples: Prompt injection susceptibility, inherent toxicity generation, training data leakage.*

## Extrinsic Assessment
Evaluates the AI system's **performance on specific downstream tasks** or risks arising from its **integration into a larger context**.
*Examples: Effectiveness as a hacking agent (task), vulnerability in a code interpreter integration (context), code generation accuracy on specific problems (task).*

## BeSBench
A utility within the Be-Secure (BeS) ecosystem that aggregates AI assessment benchmarks, providing a unified interface for selection, execution, and context-aware scoring.

## Be-Secure (BeS)
An open-source ecosystem project focused on strengthening the security posture of open-source software and components through tools, environments, playbooks, and community collaboration.

## Category (in BeSBench Taxonomy)
A standardized grouping of tests within the BeSBench framework based on the primary risk area (e.g., `Physical Hazards`, `Prompt Injection`, `Secure Code Generation`). Classified by `Domain` (Safety/Security/Both/Other) and `Assessment Type` (Intrinsic/Extrinsic).

## Use Case Profile
A predefined configuration representing a typical AI application deployment scenario (e.g., "Public Chatbot", "Code Generation Assistant"). Used in BeSBench to automatically apply relevant **Weighting** to different risk categories.

## Weighting
The process of assigning importance values (weights) to different risk categories based on the selected **Use Case Profile**. This ensures the final **Scoring** reflects the criticality of risks for a specific application context.

## Normalization
The necessary step of converting raw scores/results from different benchmarks (which use varied scales and metrics) onto a common, standardized scale (e.g., 0-1 risk score) before weighting and aggregation can occur.

## Scoring
The process of combining normalized test results with use-case specific weights to produce an overall assessment score or risk level (e.g., Low/Medium/High). (Roadmap: Formalized via Open TAVOSS Score).
