# AI Job Hunter Assistant 🤖

An AI-powered automation workflow that discovers jobs, filters relevant roles, scores fit using a local LLM, generates cover letters, and sends instant alerts.

## Features

- Automated job discovery from APIs
- Python / AI role filtering
- Duplicate listing detection
- AI-based resume-job fit scoring
- Auto-generated cover letters
- Telegram notifications
- Google Sheets tracking

## Tech Stack

- n8n
- Ollama
- Google Sheets
- Telegram Bot
- HTTP APIs
- SQL Logic

## Workflow

Schedule Trigger → Fetch Jobs → Split Items → Filter Jobs → Remove Duplicates → AI Score → Generate Cover Letter → Telegram Alert → Save to Sheet


## Setup

1. Install n8n
2. Install Ollama
3. Import workflow.json
4. Configure Telegram + Google credentials
5. Run workflow

## Future Roadmap (V2)

- Multi-source job aggregation
- Resume parser
- Skill gap analytics
- Dashboard
- Auto-apply workflows

## Author

Anubhav Sharma
