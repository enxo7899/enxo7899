# Hi, I'm Enxo 👋

Applied AI Engineer · MSc Artificial Intelligence (Distinction), City, University of London · founder of **EmSoft**, a small software and AI consultancy.

I build practical AI systems for businesses: chatbots and agents that take real actions safely, automations that remove admin work, document Q&A with sources, and the testing that proves they work. Since 2024 I've also evaluated and red-teamed frontier language models, so I care a lot about how AI systems fail and how to test for it.

## Engineering deep dives

Four projects that show how I build AI systems under the hood. Each runs live in the browser, with tests and measured results.

| Project | What it shows | Live demo |
|---|---|---|
| **[llm-gateway](https://github.com/enxo7899/llm-gateway)** | One gateway in front of several model providers: routing, fallbacks, circuit breakers, per-team budgets, caching and PII redaction. In a simulated day with outages, apps saw 0.07% errors against 2.1% for the most reliable single provider, and no personal data reached a provider. | [Open the console](https://enxo7899.github.io/llm-gateway/) |
| **[llm-eval-harness](https://github.com/enxo7899/llm-eval-harness)** | Regression testing for AI features: confidence intervals, paired significance tests, a judge measured against human ratings, and a release gate that blocks a version that gets worse for one language. | [Read the report](https://enxo7899.github.io/llm-eval-harness/) |
| **[agent-runtime](https://github.com/enxo7899/agent-runtime)** | A tool-using agent runtime built from scratch: typed tools, budgets, human approval for refunds, injection guardrails, tracing with replay. Zero unsafe actions across 1,230 evaluated runs, including runs where 30% of tool calls fail. | [Run an agent](https://enxo7899.github.io/agent-runtime/) |
| **[transformer-from-scratch](https://github.com/enxo7899/transformer-from-scratch)** | A small language model written in numpy with hand-written backpropagation and gradient checks, running in the browser with its attention visible. Perplexity 11.1 against 37.8 for a bigram baseline. | [Look inside](https://enxo7899.github.io/transformer-from-scratch/) |

## What I can build for you

| Service | Live demo | Code |
|---|---|---|
| **AI chatbot for your website and WhatsApp**: answers from your own info, books, captures leads, hands off to a person | [Try it](https://enxo7899.github.io/ai-chat-assistant/) | [ai-chat-assistant](https://github.com/enxo7899/ai-chat-assistant) |
| **AI booking agent / MCP server** with guardrails, staff approvals and an audit log | [Try it](https://enxo7899.github.io/bookings-mcp/) | [bookings-mcp](https://github.com/enxo7899/bookings-mcp) |
| **Business automation with n8n, Make or Zapier**: enquiry triage, invoice extraction, daily reports | [Live demo](https://enxo7899.github.io/n8n-business-automations/) | [n8n-business-automations](https://github.com/enxo7899/n8n-business-automations) |
| **Messy emails and spreadsheets into a clean CRM**, with measured accuracy | [Try it](https://enxo7899.github.io/inbox-to-crm/) | [inbox-to-crm](https://github.com/enxo7899/inbox-to-crm) |
| **Invoice and document extraction**: supplier PDFs into spreadsheet rows, with the maths checked | [Try it](https://enxo7899.github.io/invoice-to-sheet/) | [invoice-to-sheet](https://github.com/enxo7899/invoice-to-sheet) |
| **Chat with your documents (RAG)**: answers quote the exact paragraph, and say "I don't know" instead of guessing | [Try it](https://enxo7899.github.io/policy-qa/) | [policy-qa](https://github.com/enxo7899/policy-qa) · [evidence-desk](https://github.com/enxo7899/evidence-desk) |
| **Test and red-team your chatbot or agent** before customers find the problems | [See the report](https://enxo7899.github.io/chatbot-redteam-report/) | [chatbot-redteam-report](https://github.com/enxo7899/chatbot-redteam-report) · [support-agent-evals](https://github.com/enxo7899/support-agent-evals) · [agent-action-audit](https://github.com/enxo7899/agent-action-audit) |
| **Custom GPTs and Claude Projects for your team**: tested instructions, templates and examples | [Try it](https://enxo7899.github.io/team-prompt-library/) | [team-prompt-library](https://github.com/enxo7899/team-prompt-library) |
| **Sales forecasting in Python**, checked against a simple baseline | [Try it](https://enxo7899.github.io/sales-forecast-notebook/) | [sales-forecast-notebook](https://github.com/enxo7899/sales-forecast-notebook) |
| **Fine-tune an open-source LLM** with a proper before/after evaluation | | [pitwall-ai](https://github.com/enxo7899/pitwall-ai) |
| **Web apps and SaaS MVPs** (Next.js, Supabase) with logins and staff roles | [Try it](https://enxo7899.github.io/clinic-dashboard/) | [clinic-dashboard](https://github.com/enxo7899/clinic-dashboard) · [omaa](https://github.com/enxo7899/omaa) · [sukaj](https://github.com/enxo7899/sukaj) · [frontops-ai](https://github.com/enxo7899/frontops-ai) |
| **Business websites**: old sites rebuilt fast, phone-friendly and easy to edit | [Before and after](https://enxo7899.github.io/before-after-rebuild/) | [before-after-rebuild](https://github.com/enxo7899/before-after-rebuild) · [millocolor](https://github.com/enxo7899/millocolor) · [Sukaj Construction](https://github.com/enxo7899/Sukaj-Construction) · [black-olive-tree](https://github.com/enxo7899/black-olive-tree) |
| **Computer vision prototypes** | | [MRI_MVP](https://github.com/enxo7899/MRI_MVP) · [MVP-ChestXray](https://github.com/enxo7899/MVP-ChestXray) · [kadastra](https://github.com/enxo7899/kadastra) |

## Selected work
- **[EvidenceDesk](https://github.com/enxo7899/evidence-desk)**: document Q&A service with hybrid retrieval, cited answers, a tool-calling agent and an evaluation harness (FastAPI, PostgreSQL/pgvector, Docker, CI).
- **[MRI_MVP](https://github.com/enxo7899/MRI_MVP)**: MRI organ segmentation (TotalSegmentator / nnU-Net) with an async job queue and clinical reports, prototyped for Albania's Ministry of Health.
- **[MVP-ChestXray](https://github.com/enxo7899/MVP-ChestXray)**: chest X-ray classifier covering 18 pathologies (DenseNet-121), Dockerised.
- **[AI Artistry](https://github.com/enxo7899/AI-Artistry-Creativity-in-the-Age-of-Artificial-Intelligence)**: MSc dissertation. Music generation (LSTM / GRU / Transformer) and GPT-2 poetry, with custom evaluation metrics.
- **[evva](https://github.com/enxo7899/evva)**: generative-AI soundtracks for short-form video (Next.js, ElevenLabs / MusicGen, Vercel).

**Stack:** Python · PyTorch · Hugging Face · Claude and OpenAI APIs · MCP · RAG · FastAPI · n8n · Node.js · Next.js · TypeScript · Supabase · PostgreSQL · Docker

**Languages:** English, Albanian

📫 Enxo7899@gmail.com · [LinkedIn](https://www.linkedin.com/in/enxo-mucaj-0513a5119)
