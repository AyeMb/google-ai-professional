# Project 07: AI-Powered Research Summaries

**Course:** Google AI Professional Certificate — Course 3: AI for Research and Insights  
**Lab:** Build with AI — Research Summaries  
**Primary Tool:** Google NotebookLM  
**Supporting Tools:** Google AI Studio (audio transcription), ChatGPT (critical evaluation)  
**Status:** Completed — Research Summaries Lab

## Project Overview

I used Google NotebookLM to synthesize public technical documentation on Retrieval-Augmented Generation (RAG), AI-assisted customer support, and responsible AI risk management. I then explored a hypothetical IT help desk application, generated a research mind map and an Audio Overview, and critically evaluated the AI-generated explanations.

The objective was to practice source-grounded research, technical communication, and independent evaluation of generative AI outputs—not to build or deploy a RAG application.

## Research Sources

The NotebookLM notebook contained four sources. Sources confirmed from my research workflow:

1. [Google Cloud — Generative AI customer support architecture](https://docs.cloud.google.com/architecture/genai-customer-support)
2. [Google Cloud — Retrieval-Augmented Generation](https://cloud.google.com/use-cases/retrieval-augmented-generation)
3. [NIST — Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (AI 600-1)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)

The mind map also identified the **NIST AI Risk Management Framework** as a fourth source; its exact notebook URL has not yet been recorded here. All research sources were publicly available technical references, not Per Scholas course materials.

## Methodology

### 1. Source-Based Summary

Uploaded the technical sources to NotebookLM and generated a comparative executive summary of RAG-based customer support architecture and NIST generative AI risks.

### 2. Applied IT Support Research

Asked NotebookLM to explain how RAG might support troubleshooting a computer that cannot connect to Wi-Fi. The resulting workflow described retrieving relevant network and device documentation, generating a suggested troubleshooting response, checking security and accuracy risks, and escalating uncertain cases to a human technician.

**This Wi-Fi workflow was hypothetical, not a deployed or tested help desk system.**

### 3. Research Mind Map

Generated and expanded a NotebookLM mind map with four major branches:

- Customer Support Architecture
- Retrieval-Augmented Generation
- NIST Generative AI Risks
- NIST Risk Management Framework

The map organized technical components, retrieval steps, potential failure modes, and governance practices. It did not independently verify the underlying claims.

### 4. Audio Overview and Transcription

Generated the NotebookLM Audio Overview **“Why Open-Book AI Still Confabulates.”** Used Google AI Studio to produce a transcript and then used ChatGPT to assist with a critical review of the transcript.

### 5. Critical Evaluation

Identified claims that required qualification:

- RAG can retrieve more recent documents but does **not** guarantee the retrieved information is current.
- Token costs depend on architecture and context size; RAG does **not** guarantee cost savings.
- Describing language models as merely “next-word predictors” is an oversimplification of their capabilities.
- Sensitive information can leak through retrieval, access-control failures, prompts, and model behavior—not only memorized training data.
- Environmental comparisons require a defined workload and supporting measurements.

The generated text did not preserve visible source-citation markers in the excerpts reviewed, so citation-level verification remains an important limitation.

## Findings

RAG can help an IT support assistant retrieve relevant technical information before producing guidance. However, source retrieval alone does not guarantee accuracy, security, or appropriateness for a specific user's device or environment.

Human technicians should verify the applicability of instructions, check permissions and sensitive data exposure, and escalate high-impact or uncertain actions.

## Skills Demonstrated

- Source-grounded AI research
- Research summarization and synthesis
- Prompt engineering
- RAG architecture literacy
- Hypothetical IT troubleshooting workflow analysis
- Knowledge visualization
- AI audio transcription workflow
- Critical evaluation of AI-generated claims
- Cybersecurity and privacy awareness
- Responsible AI documentation

## Project Files

| File | Description |
|---|---|
| [README.md](README.md) | Project scope, workflow, findings, and reflection |
| [prompts.md](prompts.md) | Documented NotebookLM and transcription prompts |
| [results.md](results.md) | Research outputs, audio review, and technical limitations |

### Expanded Research Mind Map

![NotebookLM-generated research mind map](mbeche-ayieta-NotebookLM%20Mind%20Map.png)

*AI-generated visualization created in Google NotebookLM. The image must be uploaded to this project folder for the preview to render.*

## Reflection

This exercise showed me that an AI-generated explanation can sound authoritative while still overstating what a technology guarantees. In IT support, I would use AI to accelerate research, but I would confirm recommendations against official documentation and the actual device, operating system, and error before applying them.

## Limitations

This is an AI-assisted research and documentation project. I did not implement RAG, benchmark a customer support system, or independently validate every cited claim. The mind map and Audio Overview were generated by NotebookLM; the technical evaluation was assisted by ChatGPT.

## Project Outcome

**Completed — Google AI Professional Certificate, Course 3: AI for Research and Insights.**

The research summary, applied scenario, mind map, Audio Overview, transcription, and initial critical evaluation are complete. Further source-by-source verification and uploading the mind map image remain optional documentation improvements.
