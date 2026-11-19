# Multi-Agent Internship Application Assistant

A three-agent AI workflow built using n8n and Google Gemini that automates internship application drafting, reviewing, and refinement. It focuses on creating relevant, professional, and factually accurate applications without inventing candidate information.

## How It Works

The workflow uses three AI agents:

1. **Drafting Agent:** Generates an internship application based on the job description and candidate information.
2. **Critique Agent:** Reviews the draft for relevance, clarity, specificity, and unsupported claims.
3. **Revision Agent:** Uses the critique to produce an improved final application while preserving factual accuracy.

## Tech Stack

- n8n
- Google Gemini
- AI Agents
- Prompt Engineering

## Workflow

Chat Trigger → Drafting Agent → Critique Agent → Revision Agent

Each agent uses a separate Google Gemini Chat Model connection.

## Setup

1. Download the workflow JSON from the `workflow` folder.
2. Open your n8n instance.
3. Import the JSON workflow.
4. Configure your Google Gemini credentials for all three model nodes.
5. Test the workflow using a job description and candidate information.

## Important Note

The generated applications should be reviewed by the candidate before submission. The workflow is designed to avoid unsupported claims and fabricated qualifications.

## Project Status

Working prototype tested using n8n Cloud and Google Gemini.
