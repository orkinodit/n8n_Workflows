# Orkinodit Workflows for n8n

This repository contains ready-to-use n8n workflow JSON files designed for seamless integration with the Orkinodit mobile app. Each workflow is optimized for webhook-based automation, allowing you to trigger actions directly from the app.

## Overview

These workflows help you quickly set up automation for:

Receiving messages or voice input from Orkinodit

Sending responses back to the app

Executing tasks on external services (email, APIs, databases, AI models, etc.)

Testing Orkinodit’s webhook features without building workflows from scratch

All workflows follow n8n’s standard JSON export format.

## How to Use
1. Import Workflow Into n8n

  * Open your n8n instance.

  * Go to Workflows → Import from File.

  * Select any JSON file from the /workflows folder.

  * Review nodes and update keys/secrets where needed.

  * Activate the workflow.

2. Connect to Orkinodit App

  * Open Orkinodit on your device.

  * Go to the Connections page, create a new connection.

  * Paste the Webhook URL from your imported n8n workflow.
    
  * activate Connection.

  * Test using text or voice—workflow will process input automatically.


Processes a message with an AI model (OpenAI / LM Studio / local model) and sends the result back to Orkinodit.

(Add descriptions for any other workflows you include.)

## Requirements

n8n (self-hosted or cloud)

Webhook access (public URL required)

Any API keys used by specific workflows

## Notes

Update any credentials (API keys, tokens) before activating workflows.

You can customize nodes to match your automation use-case.
