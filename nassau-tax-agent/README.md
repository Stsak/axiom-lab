# Nassau County Tax Grievance Agent

This project is an agentic workflow designed to automate the process of preparing a property tax grievance for Nassau County, NY. It uses a team of specialized AI agents, orchestrated by LangGraph, to handle intake, data gathering, and document generation.

## Core Technologies
- **Orchestration:** LangGraph
- **LLM Framework:** LangChain
- **Observability:** LangSmith

## Agentic Workflow
The system uses a "Digital Paralegal" model, where agents perform automated tasks and present the results to a human for final review and filing. The key agents are:
1.  **Intake Agent:** Manages client communication.
2.  **Data-Fetcher Agent:** Gathers property data and comparable sales.
3.  **Document-Generator Agent:** Fills out official ARC forms.
4.  **Case-Manager Agent:** The central orchestrator that manages the state of each case.
