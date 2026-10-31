<div align="center">

<img src="assets/banner.svg" alt="Lead Desk" width="100%"/>

<br/>

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/> <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>

<br/>

<img src="https://img.shields.io/badge/Status-Active%20development-success?style=flat-square" alt="status"/>
<img src="https://img.shields.io/badge/Source-Private%20(commercial)-lightgrey?style=flat-square" alt="source"/>

**[Request a live demo](https://rootocloud.com) · [Hire me](mailto:faizan.developer9200@gmail.com) · [More projects](https://github.com/MuhammadFaizan73)**

</div>

---

## 📌 Overview

Lead Desk is the human side of an AI lead-response system. n8n workflows capture and qualify leads and write to Supabase; this dashboard shows agents who needs a reply, the full conversation and response performance — multi-tenant with row-level security and magic-link login.

## ✨ Key Features

### Agents
- 'Needs you' queue: awaiting contact, hot leads and AI drafts
- Full conversation view per lead
- One-click 'I've texted them' tracking

### Managers
- All-leads overview
- Response-time performance metrics

### Platform
- Supabase Auth with magic links
- Tenant isolation with Row-Level Security
- Realtime updates on leads

## 🏗️ Architecture

```mermaid
flowchart LR
  L[Lead sources] --> N8[n8n Workflows<br/>capture · qualify · draft]
  N8 --> SB[(Supabase<br/>Postgres + RLS)]
  SB --> LD[Lead Desk<br/>Next.js]
  LD -->|agent actions| SB
```

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | Next.js · TypeScript · Tailwind CSS |
| **Backend** | Supabase (Postgres, Auth, Realtime, RLS) |
| **Automation** | n8n workflows |
| **Messaging** | SMS via workflow layer |

<!-- SCREENSHOTS -->
<!-- /SCREENSHOTS -->

## 🔒 About the Source Code

This is a **commercial / client project**, so the source code is kept in a private repository.
This page documents what the system does and how it is built.

- 🎥 **Live walkthrough** — available on request
- 💼 **Want something similar for your business?** I build custom versions of this for clients.

## 👨‍💻 Author

**Muhammad Faizan** — Founder, [Rootocloud](https://rootocloud.com)
AI agents & automation · Web & mobile apps · Custom software

[![Website](https://img.shields.io/badge/rootocloud.com-0B1220?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rootocloud.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizan.developer9200@gmail.com)

<div align="center"><sub>© Muhammad Faizan. All rights reserved.</sub></div>
