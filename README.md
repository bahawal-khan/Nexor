<div align="center">

# ✦ Nexor AI

**One connected AI assistant — research, documents, images, voice, and memory in a single conversation.**

🔗 **Live:** [nexor-ai.khanova.tech](https://nexor-ai.khanova.tech)

</div>

---

## What is this?

Nexor AI is a full-stack, production-deployed AI assistant I built end-to-end — not a wrapper around a single API call, but a complete product: authentication, per-user data isolation, usage limits, safety guardrails, and a polished interface, all designed and shipped by one person.

The idea: stop juggling a different tool for every AI task. One chat that researches, reads your files, sees your images, listens to your voice, and remembers your context across conversations.

## Features

- 🔍 **Live web research** — searches the web, Wikipedia, arXiv, and YouTube on its own when a question needs current information
- 📄 **Document Q&A** — upload a PDF or Word file and ask questions about it directly
- 🖼️ **Vision + image generation** — understands photos you send, and generates new images on request
- 🎙️ **Voice input** — speak instead of type
- 🧠 **Long-term memory** — remembers durable facts and preferences across *different* conversations, not just within one
- 📑 **PDF / Word generation** — turns any answer into a downloadable, formatted document
- 🔐 **Passwordless login** — email one-time-code sign-in, no passwords stored anywhere
- 👥 **Full multi-user isolation** — every account's chats, files, and memory are completely private
- 🛡️ **Safety layer** — an input moderation model screens messages before they reach the main model, on top of daily usage quotas and rate limiting for abuse prevention
- ⚡ **Smart model routing** — simple messages get a faster, lighter model; complex reasoning automatically routes to the larger one
- 📱 Fully responsive, installable as a mobile app (PWA)

## Tech stack

**Backend:** Python, FastAPI, LangGraph, PostgreSQL + pgvector, Groq (LLM inference)
**Frontend:** React, Vite
**Infra:** Self-hosted on a VPS, Nginx, systemd

## Why the code isn't public

This repo is private because Nexor AI is a **live product with real users and real data** — publishing the source would mean publishing implementation details of its authentication, rate-limiting, and abuse-prevention systems alongside it, which isn't a trade-off worth making for a running service.

I'm glad to walk through the architecture, specific implementation decisions, or share read-only access on request — reach out below.

## About

Built by **Bahawal Khan**.

- 📧 [khanbahawal2004@gmail.com](mailto:khanbahawal2004@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/bahawal-khan-9b1124313)
- 💻 [GitHub](https://github.com/bahawal-khan)

---

<div align="center">
<sub>© 2026 Nexor AI</sub>
</div>
