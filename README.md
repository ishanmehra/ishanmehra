<div align="center">

<img src="./assets/banner.svg" alt="Ishan Mehra — Backend Engineer, event-driven systems and AI/LLM pipelines" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&pause=1100&color=00D9FF&center=true&vCenter=true&width=760&lines=Sole+backend+engineer+at+Edzy+%E2%80%94+architecture+to+deployment;Node.js+%C2%B7+BullMQ+%C2%B7+Redis+%C2%B7+MongoDB+%C2%B7+AWS;Hierarchical+LLM+content+pipelines+at+1%2C500%2B+content+types;Event-driven+campaign+automation+%E2%80%94+9%2C700%2B+messages%2Fmonth;Apple+Pay+webhooks+%C2%B7+WebSocket+duels+%C2%B7+RAG+chatbots)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-mehra1)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/ishanmehraa)
[![Email](https://img.shields.io/badge/ishanmehra04%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ishanmehra04@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=ishanmehra&style=for-the-badge&color=00d9ff&label=VIEWS)](https://github.com/ishanmehra)

</div>

---

## Systems I own in production

I'm the only backend engineer at **[Edzy](https://edzy.in)**, working directly with the founder on architecture. Everything below is live, and I built it end to end — design, implementation, deployment, monitoring.

<table>
<tr>
<td width="50%" valign="top">

### Prompt Rendering Template System
`Node.js` · `BullMQ` · `multi-model LLM` · `MongoDB`

A hierarchical AI content pipeline covering **1,500+ educational content types** across exam, subject, book, chapter and topic levels.

Templates accept multiple `referenceId`s; at execution, the relevant data is fetched on the fly and injected to produce a fully populated prompt instance. A queue scanner watches the `shouldGenerate` flag and dispatches ready prompts automatically, so generation stays decoupled from whatever triggered it.

Generated worksheets and revision guides flow back through a dedicated ingestion endpoint — a fully autonomous loop.

</td>
<td width="50%" valign="top">

### Boop — campaign automation platform
`Node.js` · `BullMQ` · `Redis` · `event-driven`

Reusable communication platform across **SMS, Email, Push, Telegram and Discord**.

**50+ campaigns/day · 9,700+ message instances/month · 900+ unique users · 89% delivery success**

Distributed job queue and scheduler handling both relative and absolute time triggers, a dynamic template engine for real-time variable injection, and event-driven hooks on badges, competitions, joins and status transitions. Internal dashboard tracks delivery, failure reasons, retry counts and error patterns.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Apple Pay integration
`Node.js` · `webhooks` · `subscriptions`

Webhook event processing that captures and validates the full payment lifecycle, persists subscriptions, and keeps user entitlements in sync across Edzy's backend.

</td>
<td width="50%" valign="top">

### Multi-model LLM layer
`configurable model selection` · `concurrent processing`

A model-selection layer sitting in front of several LLM providers, with a dedicated processing queue issuing concurrent calls for high-throughput generation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Chatbots — WhatsApp + in-app
`LLM integration` · `RAG` · `context pipelines`

Two scoped assistants for study-related help, so students get curriculum-specific answers without leaving their workflow.

</td>
<td width="50%" valign="top">

### Chrome Extension backend
`YouTube transcription` · `context windows`

A YouTube-to-Edzy mapping engine that reads the active video and surfaces relevant content items, plus context-aware chat that uses the transcript and extracted metadata as the LLM context window for video-grounded answers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### SEO & data intelligence pipeline
`CommonCrawl` · `Search Console API` · `JSON-LD`

CommonCrawl analysis to map competitor backlink profiles and find link-building opportunities, wired to Google Search Console for keyword and failing-URL data — driving structured-metadata and URL-slug strategy.

</td>
<td width="50%" valign="top">

### Real-time duel engine
`WebSockets` · `synchronised state`

Multiplayer academic duels with synchronised game state, session and participant tracking, and live updates for everyone watching.

</td>
</tr>
</table>

---

## How I think about systems

```typescript
const ishan = {
  role:     "Backend Developer @ Edzy",
  since:    "Sep 2025",
  based:    "New Delhi / Gurugram, India",
  openTo:   ["Backend roles in Czech Republic", "Gurugram / Noida / Delhi NCR"],
  relocate: "Open to relocation · EU Blue Card eligible",

  stack: {
    runtime:   ["Node.js", "Express.js", "TypeScript"],
    queues:    ["BullMQ", "Redis"],
    databases: ["MongoDB", "PostgreSQL", "MySQL"],
    infra:     ["AWS EC2", "PM2", "GitHub Actions CI/CD"],
    ai:        ["multi-model LLM integration", "prompt engineering", "RAG pipelines"],
    protocols: ["REST", "WebSockets", "Webhooks"],
    auth:      ["JWT", "RBAC"],
  },

  principles: [
    "Own the system, not the ticket",
    "Queues over direct calls — decouple by default",
    "Design for failure first, then for throughput",
    "If you can't see it fail, you haven't shipped it",
  ],
} as const;
```

---

## Stack

**Runtime & language**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Queues, cache & events**

![BullMQ](https://img.shields.io/badge/BullMQ-FF3333?style=flat-square&logo=redis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks-2B037A?style=flat-square&logo=webhooks&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square&logo=amazondynamodb&logoColor=white)

**AI & LLM**

![LLM Integration](https://img.shields.io/badge/Multi--model_LLM-412991?style=flat-square&logo=openai&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-00A67E?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-8A2BE2?style=flat-square&logo=langchain&logoColor=white)

**Infra & tooling**

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Bruno](https://img.shields.io/badge/Bruno-F4AA41?style=flat-square&logo=bruno&logoColor=black)

**Auth & payments**

![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-4B5563?style=flat-square&logo=auth0&logoColor=white)
![Apple Pay](https://img.shields.io/badge/Apple_Pay-000000?style=flat-square&logo=applepay&logoColor=white)

---

## Experience

**Backend Developer** — Edzy, Gurugram · `Sep 2025 – Present`
Sole backend developer in a cross-functional team, collaborating directly with the founder on system design, architecture decisions and feature-level infrastructure planning. Deployments automated with GitHub Actions; services run on AWS EC2 under PM2 for zero-downtime restarts. Applied database indexing and query optimisation as the systems above scaled.

**Backend Software Development Intern** — Novostack Pvt. Ltd., Noida · `Oct 2024 – Feb 2025`
Built RESTful APIs across several client projects in Node.js and Express, including a FinTech admin dashboard covering transactions, analytics and role-based access control. Cut API response times **20%** through query optimisation, indexing and caching. Implemented JWT auth with role-based authorisation and shipped **3 production systems** on schedule.

---

## Projects

**[Zagio](https://github.com/ishanmehra/zagio)** — anonymous group chat
`Node.js` · `Express.js` · `MongoDB Atlas` · `Cloudinary` · `JWT`
Privacy-focused chat platform with JWT authentication, role-based access and real-time group messaging. Anonymous by design, with no cross-user identity leakage.

**[Book Review Platform](https://github.com/ishanmehra/book-review)** — read-heavy API
`Node.js` · `PostgreSQL` · `Sequelize` · `Redis`
APIs for browsing, reviewing and rating books, with a Redis caching layer built for read-heavy access patterns.

---

## Education & certifications

**B.Tech, Computer Science** — Dr. A. P. J. Abdul Kalam Technical University, Ghaziabad · `2021 – 2025`
Graduated First Division. Focus on data structures, algorithms and backend architecture.

![Google Data Analytics](https://img.shields.io/badge/Google-Data_Analytics-4285F4?style=flat-square&logo=google&logoColor=white)
![Deloitte](https://img.shields.io/badge/Deloitte-Data_Analytics_Simulation-86BC25?style=flat-square&logo=deloitte&logoColor=white)
![Infosys](https://img.shields.io/badge/Infosys-Python_%26_OOP-007CC3?style=flat-square&logo=infosys&logoColor=white)
![Rubicon](https://img.shields.io/badge/Rubicon-Professional_Communication-6E44FF?style=flat-square)

---

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ishanmehra&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs?username=ishanmehra&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=00d9ff" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=ishanmehra&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00d9ff&fire=ffb347&currStreakLabel=00d9ff" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ishanmehra&theme=react-dark&hide_border=true&area=true&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ffb347" />

</div>

---

## Open to work

Actively looking for backend engineering roles in the **Czech Republic**, and strong opportunities across **Gurugram, Noida and Delhi NCR**.

What I bring: Node.js and event-driven architecture in production, AI/LLM pipelines that run unattended, and the track record of owning backend infrastructure solo from day one.

[![Email](https://img.shields.io/badge/Email-ishanmehra04@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ishanmehra04@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-mehra1)

<div align="center">

<br/>

<sub>Distributed systems, tight deadlines, zero hand-holding — that's where I work best.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,50:0e4d6e,100:0d1117&height=90&section=footer" width="100%" />

</div>
