

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Generate Consensus Answers with Multiple AI Models & Peer Review System

Advanced n8n automation for Generate Consensus Answers with Multiple AI Models & Peer Review System.

## Overview
- Category: Engineering, AI Summarization
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Bring together top AI models for smarter answers! AI Council provides multi-model consensus, peer review, and final synthesis for robust, bias-free results. Learn more.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.lmChatOpenRouter`
- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.