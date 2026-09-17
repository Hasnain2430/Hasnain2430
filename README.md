<h1 align="center">Hasnain Ibrar</h1>
<p align="center"><b>Software Engineer</b> — full-stack · applied AI · Doha, Qatar</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hasnain-ibrar-butt/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:Hasnain2430@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I build web products end to end and make the AI parts inside them reliable enough to ship.

That usually means React or Next.js on the front, Node or FastAPI behind it, Postgres underneath, and a lot of time spent on the parts that decide whether it survives real use: generated SQL that gets checked before it runs, retrieval with real access control, safety logic that doesn't depend on the model behaving, and queries that were slow until someone profiled them.

BS in Artificial Intelligence, FAST NUCES.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
</p>

### Open source

**[grayhatdevelopers/vidxp](https://github.com/grayhatdevelopers/vidxp)** — a video indexing engine that lets agents search inside video in natural language. I contributed [bulk indexing for large media sets](https://github.com/grayhatdevelopers/vidxp/pull/158) and [path-resolution test fixes](https://github.com/grayhatdevelopers/vidxp/pull/154).

### Projects

| | What it does | Built with |
| --- | --- | --- |
| **MindEase** | Bilingual Urdu/English mental health companion with text and voice chat. Screening results feed into the conversation, and crisis handling runs on rules rather than trusting the model. Led development on a 3-person team. | Next.js · Django · pgvector |
| **[Secure Multi-Tenant RAG](https://github.com/Hasnain2430/Secure-Multi-Tenant-RAG-System)** | Separate groups query private knowledge bases. Isolation is enforced at retrieval, not in the prompt, with ACLs, PII masking and injection detection. A red team suite of 10 attack prompts treats any leak as a failed test. | Flask · ChromaDB · Groq |
| **[IoT Vulnerability XAI](https://github.com/Hasnain2430/iot-vuln-explainable-ai)** | Predicts CVSS severity and CWE type from vulnerability text, with SHAP token attributions showing which words drove each prediction. 0.729 F1 across 28,902 records. | SecureBERT · PyTorch · SHAP |
| **[Story2Audio](https://github.com/Hasnain2430/Story2Audio_Microservice)** | A prompt becomes a narrated story with cloned voices. gRPC service defined in protobuf, with a REST proxy in front for clients that don't speak gRPC. | gRPC · Protobuf · XTTS |
