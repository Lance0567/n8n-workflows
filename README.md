# N8N Workflows

A collection of production-grade n8n automation workflows built by [Lance Esurena](https://github.com/lanceesurena) — covering AI automation, DevOps pipelines, and business process automation.

Each workflow lives in its own folder with a dedicated README, importable JSON, and screenshots.

---

## Workflows

| Workflow | Category | Description |
|---|---|---|
| [Voice to Email](./voice-to-email/) | AI Automation | Turns Slack voice notes into style-matched Gmail drafts |

---

## Repository Structure

```
N8N-WORKFLOWS/
├── assets/
│   └── images/
│       └── voice-to-email/
│           ├── workflow.png
│           ├── slack.png
│           └── gmail-draft.png
└── voice-to-email/
    ├── README.md
    └── slack_trigger.json
```

---

## Stack

All workflows are built on **n8n Cloud** and may integrate any combination of:

- **AI / LLM** — Google Gemini, OpenAI, Groq, Anthropic Claude
- **Communication** — Slack, Gmail, Google Chat
- **Storage** — Google Sheets, Supabase, MongoDB Atlas, PostgreSQL
- **Infrastructure** — Docker, GCP, Webhook triggers
- **Languages** — Python, JavaScript (Code nodes)

---

## Usage

Each workflow folder contains an importable `.json` file. To use any workflow:

1. Open n8n → **Workflows** → **Import**
2. Upload the `.json` file from the workflow folder
3. Follow the setup instructions in that workflow's `README.md`
4. Assign your credentials and activate

---

## License

MIT
