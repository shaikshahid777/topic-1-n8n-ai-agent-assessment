# Topic 1 – Setting Up the n8n Advanced AI Agent Environment

## Overview

This repository contains the deliverables for Topic 1 of the n8n AI Agent assessment.

The assessment demonstrates how to configure a secure n8n AI Agent environment, connect an OpenAI chat model, execute a chat request, and validate the execution using n8n execution/debugging information.

## Workflow

```text
When Chat Message Received → AI Agent
                               ↓
                        OpenAI Chat Model
```

## Configuration

- **AI Provider:** OpenAI
- **Model:** GPT-4.1
- **Temperature:** 0.0
- **Max Tokens:** 500
- **AI Agent System Message:** `You are a helpful assistant.`
- **Workflow Status:** Active / Published

## Test Prompt

```text
Hello, please introduce yourself in exactly one sentence.
```

The workflow was executed successfully and returned a one-sentence response.

## Validation

Execution/debugger information was reviewed to verify successful execution and token usage. The recorded test used approximately **43 total tokens**.

## Credential Security

The OpenAI credential is managed through n8n's credential system. API keys and other secrets must not be hard-coded into the workflow, screenshots, documentation, or this public repository.

## Repository Contents

- `workflow/` – exported n8n workflow JSON
- `screenshots/` – workflow, configuration, and execution evidence
- `documentation/` – assessment documentation PDF

## Assessment Deliverables

- Loom/YouTube demonstration video
- Public GitHub repository
- n8n workflow JSON export
- Workflow and execution screenshots
- Workflow documentation PDF

## Demo Video

Loom demonstration: https://www.loom.com/share/57903f39f21f4fdfb22e18ce8f67bca3

## Notes

This repository is intended as submission evidence for Topic 1. The workflow export references the n8n-managed credential by name and does not include the actual API key.