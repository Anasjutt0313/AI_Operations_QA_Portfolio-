# AI Operations — Intelligent workspace (QA Portfolio)

QA documentation for an AI-powered multi-role operations platform 
covering User, Staff, and Admin dashboards, RAG pipeline, Voice AI, 
and n8n workflow automation.

## Project Overview

- **Type:** AI Operations Hub (multi-role)
- **Roles Tested:** User, Staff, Admin
- **Test Approach:** Manual + AI/RAG evaluation + Voice AI testing
- **Total Test Cases:** 1,274
- **Total Test Scenarios:** 142
- **RAG Test Cases:** 32
- **Voice AI Test Cases:** 100
- **Defects Reported:** 6

## Deliverables

| Document | Description |
|---|---|
| [Requirement Analysis Report](docs/Requirement_Analysis_Report.docx) | SRS-based analysis |
| [Test Plan](docs/Test_Plan.docx) | Scope, strategy, entry/exit criteria |
| [Test Scenarios](sheets/Test_Scenarios.xlsx) | 142 scenarios across 16 modules |
| [Test Cases](sheets/Test_Cases.xlsx) | 1,274 test cases (module-wise) |
| [RAG Test Cases](sheets/RAG_Test_Cases.xlsx) | Section 6.3 template — 32 cases |
| [Voice AI Test Cases](sheets/Voice_AI_Test_Cases.xlsx) | Section 6.4 template — 100 cases |
| [Bug Reports](docs/Bug_Reports.docx) | 6 defects with stage-level attribution |
| [QA Summary Report](docs/QA_Summary_Report.docx) | Final test summary |
| [n8n Workflow](n8n/Week5_CV_Screening_Pipeline.json) | CV screening automation |

## Skills Demonstrated

- Manual Testing (Functional, Negative, Boundary, E2E, UI)
- RAG Pipeline Testing (retrieval relevance, groundedness, citation correctness)
- Voice AI Testing (STT/TTS accuracy, tool calls, latency, failure injection)
- Stage-level Failure Attribution (ingestion → chunking → retrieval → context → generation → post-processing)
- Role-based Access Control (User / Staff / Admin)
- n8n Workflow Testing
- API Testing (Postman)
- Cross-browser & Responsive Testing

## Key Findings

- **1 RAG observability blocker** (BUG-004) — retrieved chunk content not exposed via API
- **2 Voice AI tool-execution failures** (BUG-005, BUG-006) — `create_task` not firing
- **3 UI defects** in Chat, Sidebar, and Knowledge Base
- **Voice AI LLM latency** averaged 8.9 seconds per turn (90% of total latency)

## Author

**Hafiz Anas Ali**
SQA Engineer | Manual + Playwright Automation
[LinkedIn](https://linkedin.com/in/hafiz-anas-ali-a52092304) · [GitHub](https://github.com/Anasjutt0313)
