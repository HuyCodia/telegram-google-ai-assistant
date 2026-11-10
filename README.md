# Telegram Google AI Assistant

An AI-powered Telegram assistant built with **n8n**, integrating **Gmail** and **Google Calendar** to manage emails and calendar events using natural language and voice messages.

## Overview

This project connects Telegram with Google's productivity services through an AI-powered assistant. Users can interact with the assistant via text messages or voice messages to access email and calendar functionality.

The automation is built using n8n and combines AI processing, API integrations and workflow automation.

## Features

- **Telegram Integration** – Interact with the assistant directly through Telegram.
- **Gmail Integration** – Access and manage email-related tasks.
- **Google Calendar Integration** – Retrieve and manage calendar events.
- **Voice Message Processing** – Convert voice messages into text for further processing.
- **AI-powered Interaction** – Understand natural language requests and process them through an AI agent.
- **Workflow Automation** – Connect multiple services in a single automated workflow.

## Technologies

- n8n
- Telegram Bot API
- Gmail API
- Google Calendar API
- AI / LLM Integration
- JSON
- Webhooks

## Workflow

1. The user sends a text or voice message through Telegram.
2. n8n receives the incoming message.
3. Voice messages are transcribed into text.
4. The AI agent interprets the user's request.
5. The assistant interacts with Gmail or Google Calendar as required.
6. The result is returned to the user through Telegram.

## Project Structure

```text
telegram-google-ai-assistant/
├── screenshots/
│   └── workflow-overview.png
├── workflow/
│   └── telegram-google-ai-assistant.json
└── README.md
```

## Setup

1. Import the workflow JSON file into n8n.
2. Configure the required Telegram credentials.
3. Connect your Gmail and Google Calendar accounts.
4. Configure the required AI model credentials.
5. Activate the workflow and start interacting through Telegram.

**Note:** API credentials and personal account information are not included in this repository. You must configure your own credentials before running the workflow.

## Purpose

This project demonstrates practical experience with workflow automation, API integrations, AI agents and natural language processing using n8n.
