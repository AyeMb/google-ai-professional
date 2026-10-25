# Project 07 — Research Results and Critical Evaluation

## 1. Research Summary

NotebookLM generated an executive summary comparing Google Cloud's customer support architecture with NIST generative AI risk management.

**Topics covered:** knowledge retrieval, grounding, solution generation, hallucination/confabulation, prompt injection, data poisoning, privacy, and human oversight.

**Evaluation:** Useful synthesis and organization, but the excerpts retained for this portfolio did not show individual NotebookLM citation markers. Specific source claims should be checked against the original documents.

## 2. Applied RAG Troubleshooting Scenario

**Scenario:** A computer cannot connect to Wi-Fi.

**NotebookLM's hypothetical workflow:**

1. Receive the support question.
2. Retrieve relevant Wi-Fi, driver, router, and device documentation.
3. Use retrieved material as context for generating troubleshooting guidance.
4. Check whether the guidance fits the user's device and environment.
5. Have a technician verify or escalate uncertain, risky, or disruptive steps.

**Risks identified:** incorrect or outdated documents, confabulation, fabricated citations, prompt injection, data poisoning, personally identifiable information exposure, and over-reliance on generated advice.

**Boundary:** This is a conceptual workflow, not a functioning RAG application or tested fix.

## 3. NotebookLM Mind Map

The expanded map organized research under four branches:

- **Customer Support Architecture:** knowledge retriever, solution generator, GKE, Gemini API, Cloud Storage.
- **RAG:** preprocessing and retrieval, grounded generation, semantic search, re-ranking.
- **NIST Generative AI Risks:** confabulation, bias, security, information integrity, privacy-related concerns.
- **NIST AI RMF:** Govern, Map, Measure, Manage.

**Strengths:** Clear organization and useful overview of technical components and risks.

**Limitations:** Did not show a complete Wi-Fi troubleshooting sequence, explicit risk-to-control relationships, or individual source citations in the exported view.

## 4. Audio Overview

**Generated in:** Google NotebookLM  
**Title:** Why Open-Book AI Still Confabulates  
**Transcribed with:** Google AI Studio  
**Transcript reviewed with:** ChatGPT

The approximately five-minute recording used an “open-book test” analogy to explain RAG, confabulation, privacy risk, automation bias, governance, and environmental impact.

### Technical Claim Review

| Approx. time | Claim in the recording | Evaluation |
|---|---|---|
| 01:07 | Retrieved information is “always fresh.” | Too strong: the source documents or index may be outdated. |
| 01:07 | RAG “drastically” reduces token costs. | Not guaranteed; depends on retrieval, prompt size, and system design. |
| 02:07 | Models are prediction engines, “not reasoning engines.” | Oversimplifies how language models can perform reasoning tasks. |
| 03:08 | Privacy risk arises from memorized training data. | Incomplete; retrieved content, access controls, and prompts also create exposure risks. |
| 04:14 | Generative tasks are substantially more energy intensive than traditional computing. | Requires defined workloads, measurements, and supporting evidence. |

### What Worked

The audio communicated the basic RAG workflow clearly and emphasized that correct retrieved material does not guarantee a correct generated answer. It also introduced automation bias, a practical concern for IT support technicians.

### What Needed Improvement

The recording sometimes treated conditional benefits as guarantees. It also simplified model behavior and offered broad environmental claims without quantitative context.

**Assessment:** Educationally useful, but not sufficient as a stand-alone technical reference. Its claims require source verification.

## 5. Practical IT Support Takeaway

Before using AI-generated troubleshooting advice, I would check the manufacturer's official documentation, confirm the device and operating system, verify the actual error, and evaluate whether the proposed steps could expose data or disrupt service. I would escalate uncertain or high-impact actions rather than relying solely on a polished AI response.

## 6. Evidence and Verification Limits

- The audio review is based on the transcript supplied from Google AI Studio, not an independent word-by-word audio audit.
- The provided excerpts did not preserve inline NotebookLM citation markers.
- The mind map showed four sources, but the fourth source's exact URL was not recorded.
- No RAG application was built or benchmarked.
- No quantitative efficiency, accuracy, or environmental performance claims were independently tested.
