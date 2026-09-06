<h1 align="center">Hi, I'm Sanket Singh 👋</h1>

<p align="center">
  <strong>Backend Engineer · AI Engineer · Distributed Systems</strong>
</p>

<p align="center">
  Building scalable APIs, resilient backend systems, and AI-powered products.
</p>

<p align="center">
  <a href="https://github.com/sanketsingh001">GitHub</a>
  ·
  <a href="https://www.linkedin.com/">LinkedIn</a>
</p>

---

## 👨‍💻 About Me

I'm a **Backend Engineer** working on high-throughput financial APIs and distributed systems.

My core engineering experience is around **C#/.NET, PostgreSQL, SQL Server, Redis, REST APIs, cloud infrastructure, Kubernetes, and observability**. Outside of production backend engineering, I build AI systems involving **LLMs, RAG, speech processing, real-time voice agents, privacy infrastructure, and AI-powered applications**.

I like building systems that are not just functional, but **reliable, observable, secure, and scalable**.

My current interests sit at the intersection of:

**Backend Engineering × Distributed Systems × Cloud × AI**

---

## 🚀 Featured Engineering Work

<table>
<tr>

<td width="50%" valign="top">

<h3>🎙️ Voicer AI</h3>

<p><strong>Private Project</strong></p>

<p>
An AI-powered voice calling platform that conducts automated conversations
for HR interviews, customer service, sales, and custom scenarios.
</p>

<p>
The system combines a web dashboard with a FastAPI backend and real-time
LiveKit voice agents, connecting speech recognition, LLM reasoning,
text-to-speech, telephony and post-call evaluation into a single workflow.
</p>

<p><strong>Highlights</strong></p>

<ul>
<li>Real-time voice conversations</li>
<li>Outbound SIP / VoIP calling</li>
<li>Whisper / Groq speech recognition</li>
<li>Azure OpenAI / GPT-based conversation engine</li>
<li>Azure / OpenAI TTS</li>
<li>Scenario-aware AI interview engine</li>
<li>Automated call evaluation and scoring</li>
<li>Dockerized backend and frontend</li>
</ul>

<p><strong>Python · FastAPI · LiveKit · Whisper · Azure OpenAI · SIP · React · Docker</strong></p>

</td>

<td width="50%" valign="top">

<h3>🛡️ SecureRedact / FintechGuard.Pii</h3>

<p>
<a href="https://github.com/sanketsingh001/SecureRedact">Open Source</a>
</p>

<p>
A high-throughput <strong>.NET 10</strong> PII detection, masking and
reversible tokenization engine designed for deeply nested fintech JSON payloads.
</p>

<p><strong>Highlights</strong></p>

<ul>
<li>Streaming JSON processing with Utf8JsonReader / Utf8JsonWriter</li>
<li>Algorithmic PII detection without relying on JSON key names</li>
<li>Aadhaar, PAN, GSTIN, IFSC, UPI, cards, IBAN, SSN, email and phone detection</li>
<li>Format-preserving reversible tokenization</li>
<li>AES-256-GCM authenticated encryption</li>
<li>ASP.NET Core middleware integration</li>
<li>LLM privacy proxy for masking PII before sending prompts to AI providers</li>
<li>Published as a NuGet package</li>
</ul>

<p><strong>C# · .NET 10 · AES-256-GCM · ASP.NET Core · JSON Streaming · NuGet</strong></p>

</td>

</tr>

<tr>

<td width="50%" valign="top">

<h3>🧠 Whisper Fine-Tuning Data Preparation Portal</h3>

<p>
<a href="https://github.com/sanketsingh001/FineTuning-Portal">GitHub Repository</a>
</p>

<p>
A data preparation platform for building high-quality speech datasets
for Whisper ASR fine-tuning, with a focus on Indian call-center audio.
</p>

<p><strong>Pipeline</strong></p>

<p>
<code>Upload → Resample → VAD → Chunk → Transcribe → Diarize → Review → Export</code>
</p>

<p><strong>Highlights</strong></p>

<ul>
<li>16 kHz mono audio normalization</li>
<li>Voice activity detection and automatic chunking</li>
<li>Whisper-based transcription</li>
<li>Speaker diarization</li>
<li>Human review and transcript correction workflow</li>
<li>Hugging Face-compatible dataset export</li>
<li>Background processing with Celery</li>
<li>Object storage through MinIO</li>
</ul>

<p><strong>Python · FastAPI · Celery · PostgreSQL · Redis · MinIO · Docker · Whisper · Hugging Face</strong></p>

</td>

<td width="50%" valign="top">

<h3>💰 Crown Capital</h3>

<p><strong>Private Project</strong></p>

<p>
A full-stack finance and creator-commerce platform designed around
products, advisory services, research content and customer operations.
</p>

<p><strong>Highlights</strong></p>

<ul>
<li>Public product and content experience</li>
<li>Customer account and portal flows</li>
<li>Admin operating system for products, leads, orders and content</li>
<li>Affiliate partner tracking and payout workflows</li>
<li>Supabase-backed data model</li>
<li>Authentication and protected application routes</li>
<li>Checkout and payment integration architecture</li>
<li>Analytics and finance-oriented UI</li>
</ul>

<p><strong>Angular · TypeScript · Supabase · PostgreSQL · RxJS · Chart.js · Playwright</strong></p>

</td>

</tr>

<tr>

<td width="50%" valign="top">

<h3>🏠 GuestDeck</h3>

<p><strong>Private Project</strong></p>

<p>
A product-focused web platform built as a modern PWA, combining
customer-facing workflows with authentication, storage, analytics,
payments and AI capabilities.
</p>

<p><strong>Highlights</strong></p>

<ul>
<li>Next.js application architecture</li>
<li>Supabase authentication and data layer</li>
<li>Progressive Web App support</li>
<li>Payment integration</li>
<li>Error monitoring with Sentry</li>
<li>Product analytics</li>
<li>Interactive onboarding and UI workflows</li>
<li>Groq-powered AI integration</li>
</ul>

<p><strong>Next.js · React · TypeScript · Supabase · PostgreSQL · Groq · Sentry · PWA</strong></p>

</td>

<td width="50%" valign="top">

<h3>⚡ Distributed Redis Circuit Breaker</h3>

<p>
<a href="https://github.com/sanketsingh001/CircuitBreaker.Redis.Distributed">
GitHub Repository
</a>
</p>

<p>
A distributed circuit-breaker library for .NET services that coordinates
failure state through Redis across multiple service instances.
</p>

<p>
Built to explore resilience patterns used in distributed systems,
including failure isolation, shared state and graceful recovery.
</p>

<p><strong>C# · .NET · Redis · Distributed Systems · Resilience · NuGet</strong></p>

</td>

</tr>
</table>

---

## 🧩 Production Engineering

My professional work focuses heavily on backend and platform engineering:

- High-throughput financial APIs and middleware
- Distributed service integrations
- PostgreSQL schema and SQL optimization
- Stored procedures and database functions
- Redis caching and distributed coordination
- Webhooks and asynchronous workflows
- API authentication and authorization
- AWS EKS / Kubernetes deployments
- Cloud migrations and production infrastructure
- OpenTelemetry, tracing and observability
- Failure handling, resilience and production debugging

---

## 🛠️ Tech Stack

### Backend

`C#` · `.NET 8/10` · `ASP.NET Core` · `Python` · `FastAPI` · `Java` · `Spring Boot` · `REST APIs`

### Databases & Data

`PostgreSQL` · `SQL Server` · `Redis` · `Supabase` · `SQL` · `Database Design`

### Cloud & Infrastructure

`AWS` · `Azure` · `Kubernetes` · `EKS` · `Docker` · `OpenTelemetry` · `CloudWatch`

### AI & ML

`LLMs` · `RAG` · `AI Agents` · `Whisper` · `Speech AI` · `Azure OpenAI` · `OpenAI` · `Hugging Face` · `Vector Search`

### Frontend

`Angular` · `React` · `TypeScript` · `JavaScript`

---

## 🧠 What I'm Exploring

```text
Distributed Systems
System Design
Advanced .NET
PostgreSQL Internals
Kubernetes & Cloud Architecture
LLM Systems
RAG
AI Agents
Real-Time Voice AI
AI + Backend Infrastructure
High-Scale API Design
```

---

## 🔭 Things I Like Building

I'm especially interested in engineering projects where software and infrastructure meet.

**Reliable APIs**

Designing services that continue behaving correctly when dependencies fail,
traffic spikes, or distributed state becomes complicated.

**AI Infrastructure**

Turning LLMs and AI models into actual systems with APIs, storage,
evaluation, observability and production workflows around them.

**Developer Platforms**

Building internal tools and infrastructure that make complex engineering
work simpler, safer and faster.

**Security & Privacy**

Exploring practical ways to protect sensitive data while still allowing
modern systems and AI applications to use it.

---

## 📈 GitHub Activity

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=sanketsingh001&show_icons=true&hide_border=true&theme=transparent"
    alt="Sanket's GitHub stats"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=sanketsingh001&hide_border=true&theme=transparent"
    alt="GitHub streak"
  />
</p>

---

## 🤝 Connect

I'm interested in **backend engineering, distributed systems, AI infrastructure,
developer platforms, and building products around real-world problems**.
<p align="center"> <a href="mailto:singhsanket97@gmail.com">📧 Email</a> · <a href="https://www.linkedin.com/">LinkedIn</a> · <a href="https://github.com/sanketsingh001">GitHub</a> </p>
<p align="center">
  <strong>Build systems. Understand the internals. Make them better.</strong>
</p>
