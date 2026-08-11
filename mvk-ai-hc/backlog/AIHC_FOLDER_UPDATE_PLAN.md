# AIHC Folder-Wise Update Plan

## Purpose

This document records the first discussion with the current Scrum/agent team for
the AIHC staging source:

`C:\git\health\hc_google_drive\AIHC`

The goal is to improve the documentation one folder at a time so it is stronger
for:

- Client demo
- Client interview
- Remote-work profile
- Enterprise technical discussion
- Product Owner and delivery-management positioning

This is a staging plan only. Main profile pages should not be updated until the
staging version is reviewed and approved.

## Scrum / Agent Team Discussion

| Agent / Role | Discussion Point | Recommendation | State |
|---|---|---|---|
| Product Owner Agent | The profile needs to show business value, not only technology. | Add clearer outcome, user value, persona value, and roadmap language. | Acknowledged |
| Documentation Agent | Current pages are strong technically but need more client-demo framing. | Add management summaries, demo talking points, and status clarity. | Acknowledged |
| Architecture Agent | The solution already has a strong layered architecture story. | Strengthen architecture decision language and explain safety/guardrails as enterprise value. | Acknowledged |
| Backend API Agent | ASP.NET Core, Identity, EF Core, and MAPI are documented separately. | Connect backend pages to one integrated platform story. | Acknowledged |
| Frontend UI Agent | Angular persona pages exist. | Add clearer Doctor/Patient/Admin demo journey and interview talking points. | Acknowledged |
| AI/LLM Agent | Semantic Kernel and Ollama are documented. | Explain model orchestration, local LLM choice, and persona model direction in business terms. | Acknowledged |
| Data Engineering Agent | PySpark and SQL Server are documented. | Explain synthetic healthcare data, schema grounding, and why reliable data matters. | Acknowledged |
| QA/Test Agent | Playwright section exists. | Present testing as delivery maturity and client confidence, not only automation. | Acknowledged |
| DevOps Agent | Azure DevOps Boards documentation exists. | Add delivery traceability and staged backlog management language. | Acknowledged |
| VIGILE Concept Owner | VIGILE should be treated as a real implementation testimonial, not a claim of invention. | Create a dedicated testimonial/case-study section after wording is approved. | Acknowledged |

## Folder-Wise Update Plan

| Order | Folder / File Area | Current Purpose | Proposed Update | Business / Demo Value | Suggested Owner Agent | Status |
|---:|---|---|---|---|---|---|
| 1 | `backlog/` | Planning and staging notes. | Maintain VIGILE concept backlog and this folder-wise update plan. | Keeps review controlled before touching public pages. | Product Owner Agent + Documentation Agent | In progress |
| 2 | `about_project/hcs_home.html` | Main project overview. | Add a concise client-demo framing section: what problem it solves, what is proven, what is in progress, and why it matters. | First impression for recruiters, clients, and interviewers. | Documentation Agent + Product Owner Agent | Done |
| 3 | `ts/01_technology_stack_v1.html` | Technology navigation hub. | Add a delivery/operating-model card or section after the wording is approved. | Shows both technical breadth and delivery maturity. | Documentation Agent + Architecture Agent | Done |
| 4 | `devops/gd_azuredevops/` | Azure DevOps Boards and local-first workflow. | Strengthen language around traceability, backlog discipline, Basic-process reality, and staging-before-sync. | Useful for delivery managers and enterprise clients. | DevOps Agent + Product Owner Agent | Started |
| 5 | `api/gd_aspnetcore/` | Backend framework documentation. | Add integrated API-platform summary and client-demo talking points. | Shows backend ownership and scalable API design. | Backend API Agent | Planned |
| 6 | `api/gd_identity/` | JWT identity and authentication. | Explain why role/persona identity matters for Doctor/Patient/Admin flows. | Shows security and access-control thinking. | Backend API Agent + Architecture Agent | Planned |
| 7 | `api/gd_semantickernel/` | AI orchestration documentation. | Clarify orchestration value: persona-aware routing, separation of prompt/model/tool concerns. | Shows AI architecture maturity. | AI/LLM Agent + Architecture Agent | Planned |
| 8 | `api/gd_ollama/` | Local LLM runtime and persona models. | Explain why local model experimentation matters and how it supports controlled AI development. | Good interview story for AI engineering depth. | AI/LLM Agent | Planned |
| 9 | `data/gd_sqlserver/` | SQL Server, query guardrail, persona/LLM schema. | Highlight safe query execution, allow-lists, read-only access, and grounded answers. | Strongest trust/safety story for healthcare AI. | Data Engineering Agent + Architecture Agent | Planned |
| 10 | `api/gd_cosmosdb/` | Planned vector/RAG store. | Keep honest design-stage language; avoid implying it is implemented. | Shows roadmap discipline and avoids over-claiming. | Architecture Agent + Data Engineering Agent | Planned |
| 11 | `bigdata/gd_pyspark/` | Synthetic healthcare data ingestion/profiling. | Connect PySpark work to data readiness and demo dataset quality. | Shows data engineering credibility. | Data Engineering Agent | Planned |
| 12 | `ui/gd_angular/` | Angular persona-specific UI. | Add demo journey language for Doctor, Patient, and future Admin flows. | Makes demo easier to present to clients. | Frontend UI Agent | Planned |
| 13 | `qa/gd_playwright/` | Playwright testing. | Present testing as release confidence, persona coverage, and regression control. | Shows professional delivery quality. | QA/Test Agent | Started |
| 14 | Future `delivery/` or `vigile/` section | Not present yet. | Create after name/positioning approval: VIGILE real implementation testimonial. | Differentiates profile with a real agent-driven delivery case study. | VIGILE Concept Owner + Documentation Agent | Waiting discussion |

## Recommended Update Sequence

1. Keep refining `backlog/` until the message is approved.
2. Update `about_project/hcs_home.html` first because it is the main project story.
3. Update `ts/01_technology_stack_v1.html` so the new delivery/testimonial section is discoverable.
4. Update DevOps and QA pages next because they prove delivery maturity.
5. Update API, AI, data, and UI pages folder by folder.
6. Create a separate VIGILE/testimonial section only after naming and wording are finalized.

## VIGILE Positioning Decision

Current recommendation:

Use VIGILE as a **real implementation testimonial**, not as a claim that a new
global methodology was invented.

Preferred wording:

> VIGILE is my real implementation testimonial of agent-driven delivery: a
> practical record of how I used a virtual agent team and vibe-coding-inspired
> workflow to plan, build, document, test, and evolve Healthcare Co-Pilot Studio.

Avoid:

> VIGILE is a completely new methodology that no one has done before.

## Current State

| Item | State |
|---|---|
| Source path reviewed | Done |
| Scrum/agent team discussion captured | Done |
| Folder-wise update plan created | Done |
| Public HTML changes | Started |
| Next action | Continue folder-wise updates with DevOps and QA pages |
