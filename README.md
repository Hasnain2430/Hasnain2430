<h1 align="center">Hasnain Ibrar</h1>
<p align="center">AI Engineer — LLMs, RAG, and multi-agent systems</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hasnain-ibrar-butt/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:Hasnain2430@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Doha,_Qatar-333?style=flat-square&logo=googlemaps&logoColor=white" alt="Doha, Qatar">
  <img src="https://img.shields.io/github/followers/Hasnain2430?style=flat-square&logo=github&logoColor=white&labelColor=24292f&color=555" alt="Followers">
</p>

---

Based in **Doha, Qatar**. BS Artificial Intelligence at **FAST NUCES, Islamabad** (Dean's List). Previously AI/ML intern at **AlphaBridge**, building ETL pipelines and deploying on AWS.

I build systems where a language model does real work instead of decorating a demo: agents that coordinate, retrieval that stays honest about its sources, and small products that people actually run. Most of what I ship is Python on the AI side and Next.js on the product side.

### Stack

| | |
| --- | --- |
| **Languages** | Python · TypeScript · SQL · C++ |
| **AI / ML** | LangChain · LangGraph · Hugging Face Transformers · PyTorch · SHAP |
| **Retrieval** | Pinecone · ChromaDB · pgvector · hybrid + reranked RAG |
| **Models** | OpenAI · Groq · Gemini · Ollama (local) |
| **Backend** | FastAPI · gRPC · Next.js API routes · Postgres · Drizzle |
| **Ops** | Docker · AWS (EC2, S3, Lambda, Glue) · Vercel · n8n |

### Selected work

**[Explainable IoT Vulnerability Prediction](https://github.com/Hasnain2430/iot-vuln-explainable-ai)** — Research implementation behind a multi-task transformer that predicts CVSS severity and CWE type from vulnerability descriptions, with SHAP token attributions. SecureBERT variant reaches 0.729 ± 0.003 combined F1 over 5-fold CV on 28,902 records.

**[Secure Multi-Tenant RAG](https://github.com/Hasnain2430/Secure-Multi-Tenant-RAG-System)** — A RAG service where tenant isolation is enforced at retrieval, not in the prompt: per-tenant ACLs, PII masking, and prompt-injection detection over ChromaDB + LangChain.

**[Real-Time Airspace Copilot](https://github.com/Hasnain2430/Real-Time-Airspace-Copilot-with-Agentic-Multi-Agent-System)** — LangGraph agents watching live flight data for anomalies, wired to a FastAPI backend, a React dashboard, an MCP server, and n8n workflows.

**[CrisisSim](https://github.com/Hasnain2430/CrisisSim-Agentic-AI-for-Disaster-Management)** — Multi-agent disaster response simulation using ReAct reasoning. Fire trucks, medics, and rubble crews plan in parallel against a spreading fire and a filling hospital queue.

**[RAG Voice Agent](https://github.com/Hasnain2430/RAG-Voice-Agent)** — Ask by voice, get three grounded answers from Gemini, Kimi, and DeepSeek at once, streamed over SSE, scored and ranked against each other.

**[Handwritten Notes OCR](https://github.com/Hasnain2430/-handwritten-notes-ocr)** — Turns photos of messy lecture notes into editable `.docx` with structure intact, using a line-level DB + CRNN pipeline and a zero-text-drop policy.

### Open source

Contributor to **[grayhatdevelopers/vidxp](https://github.com/grayhatdevelopers/vidxp)** (⭐ 52) — a video indexing engine that lets agents search inside video in natural language at low token cost. Work there:

- [#158](https://github.com/grayhatdevelopers/vidxp/pull/158) — bulk indexing for many media items in one pass *(merged)*
- [#154](https://github.com/grayhatdevelopers/vidxp/pull/154) — fixed tests to compare resolved paths where the product resolves them *(merged)*
- [#155](https://github.com/grayhatdevelopers/vidxp/pull/155) — corrected the contributor test command in the docs *(open)*

Beyond that, 24 merged pull requests across team codebases — mostly real-time sports broadcast tooling and data pipelines.

### Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hasnain2430&theme=github" alt="Profile summary">
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Hasnain2430&theme=github" alt="Top languages by repo">
</p>

### Currently

Final year project **MindEase**, an AI mental health companion — plus a few personal apps I use daily: a bank-SMS-to-ledger tracker and a subscription/free-trial watcher, both Next.js on Neon Postgres.

Open to AI engineering roles and freelance work — [email](mailto:Hasnain2430@gmail.com) is fastest.
