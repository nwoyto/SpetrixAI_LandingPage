# Spectrix AI

**Spectrix AI** is an AI-powered analytics platform that helps business owners and operators understand, visualize, and act on their data. Through a natural language interface and advanced visualization tools, users can explore complex data without writing code or relying on technical teams.

Built for simplicity, Spectrix turns raw inputs into meaningful insights—then goes further, offering suggestions and actions that directly improve business outcomes.

**Note User Sarah and Bright Day Bakery are fictional entities for demo purposes.**

---
<img width="1448" alt="Screenshot 2025-05-10 at 12 42 09 AM" src="https://github.com/user-attachments/assets/8efda27c-3215-40e6-b53e-67b223d36474" />


<img width="1439" alt="Screenshot 2025-05-10 at 12 39 02 AM" src="https://github.com/user-attachments/assets/ebf870c0-206b-48dd-9426-ceebd7f130f1" />


<img width="1448" alt="Screenshot 2025-05-10 at 12 46 10 AM" src="https://github.com/user-attachments/assets/26d1aa74-471e-4eed-a18e-87f6159a1a7b" />


## Vision

Spectrix AI is more than an analytics dashboard—it is the foundation of a fully agentic decision support system.

Our long-term goal is to evolve into an intelligent agent that:

- Understands user intent through natural language conversations
- Identifies meaningful patterns and generates contextual insights
- Proactively suggests strategic or operational actions to improve KPIs
- Enables one-click automation to implement those recommendations

We believe the future of analytics lies not in visualizing data, but in taking action based on what the data reveals.

---

## Features

### Available Now

- Chat-based natural language query engine
- Auto-generated dashboards, summaries, and visualizations
- Upload and connect data from:
  - Google Sheets
  - Salesforce, HubSpot (OAuth integrations)
  - CSV, Excel, PDF, Word
  - SQL databases
- Persistent memory across sessions for conversational context
- Interactive charts built with Recharts and Plotly

### Coming Soon

- Multi-step reasoning agents powered by LangChain and Bedrock
- Automated insight generation and pattern detection
- Actionable recommendations based on current performance
- One-click automations (e.g., CRM updates, email alerts, ad budget adjustments)
- Forecasting and anomaly detection

---

## Tech Stack

- **Frontend**: React (SPA), Tailwind CSS, Shadcn UI
- **Backend**: Node.js & FastAPI (microservices)
- **AI/LLM**: OpenAI, Anthropic Claude, Amazon Bedrock
- **Agent Framework**: LangChain
- **Database**: PostgreSQL, Redis, Pinecone (for vector memory)
- **Deployment**: AWS Lambda, API Gateway, S3, CloudFront

---

## Getting Started

```bash
git clone https://github.com/your-org/spectrix-ai.git
cd spectrix-ai
pnpm install
pnpm dev
