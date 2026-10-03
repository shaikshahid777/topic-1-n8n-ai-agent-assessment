<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=topic%201%20n8n%20ai%20agent%20assessment;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=topic-1-n8n-ai-agent-assessment&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/topic-1-n8n-ai-agent-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/topic-1-n8n-ai-agent-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment) · [🐞 Report Issue](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/issues/new) · [⭐ Star](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/topic-1-n8n-ai-agent-assessment/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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