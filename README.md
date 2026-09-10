<div align="center">

# N Siddharth Reddy

### I build software that can understand, automate, and act.

Backend engineer working across **AI infrastructure, agents, automation, and developer tools.**

Currently building **BSDK** — giving any website its own AI brain.

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat-square\&logo=vercel\&logoColor=white)](https://siddharth-portfolio-delta.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/n-siddharth-reddy/)
[![GitHub](https://img.shields.io/badge/GitHub-111111?style=flat-square\&logo=github\&logoColor=white)](https://github.com/siddreddy07)

</div>

<br/>

---

## `01` / What I'm building now

<table>
<tr>
<td width="65%" valign="top">

### BSDK

**An embeddable AI layer for the web.**

The idea is simple:

> Give a website its data, connect an AI model, drop in the SDK —
> and the website gets an AI assistant that actually understands it.

I'm building the system around the widget too: document ingestion, parsing, embeddings, vector search, configurable AI providers, streaming responses, bot configuration and managed infrastructure.

This is less about putting another chat bubble on a page.

It's about building the infrastructure behind one.

</td>
<td width="35%" valign="top">

```txt
Website
   │
   ▼
┌─────────────┐
│    BSDK     │
├─────────────┤
│ Context     │
│ Retrieval   │
│ Streaming   │
│ AI Runtime  │
└──────┬──────┘
       │
       ▼
 Website AI
```

</td>
</tr>
</table>

`TypeScript` · `Node.js` · `React` · `MongoDB` · `Pinecone` · `Cohere` · `LlamaIndex` · `SSE`

---

## `02` / Things I've shipped

<table>
<tr>
<td width="50%" valign="top">

### ◈ Auto Browse

**Visual AI browser automation.**

Build workflows from nodes like `open`, `act`, `extract`, `observe`, `agent` and `send-email`, then run them as background jobs against real browser sessions.

Includes collaborative workflow editing, execution state, per-node outputs and browser session replay.

**Built with**

`Next.js` `Stagehand` `Browserbase`
`Trigger.dev` `Neon` `Drizzle` `Liveblocks`

[Live ↗](https://auto-browse-seven.vercel.app/) · [Source ↗](https://github.com/siddreddy07/auto-browse)

</td>

<td width="50%" valign="top">

### ◈ dbSmash

**Natural language → database setup.**

Describe the data your application needs and turn it into database schemas and generated code instead of starting from a blank file.

Built both the visual web experience and a CLI published to npm.

**Built with**

`Node.js` `React` `AI` `Code Generation`

[npm ↗](https://www.npmjs.com/package/dbsmash)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ◈ InboxValid MCP

**Email verification exposed as an MCP tool.**

A small MCP server that lets agents verify emails through a structured `verify_email` tool with MX, disposable-domain and retry handling.

`Node.js` `TypeScript` `MCP`

[Source ↗](https://github.com/siddreddy07/InboxValid-MCP-Server)

</td>

<td width="50%" valign="top">

### ◈ Personal AI Agent

**RAG + tools + realtime interaction.**

Built an agent architecture around document ingestion, vector retrieval, tool execution, background jobs and streamed responses.

`Vercel AI SDK` `Qdrant` `BullMQ`
`PostgreSQL` `SSE` `React Native`

</td>
</tr>
</table>

---

## `03` / The kind of engineering I like

```text
                          ┌─────────────────┐
                          │      IDEA       │
                          └────────┬────────┘
                                   │
                    ┌──────────────▼──────────────┐
                    │       PRODUCT SYSTEM        │
                    └──────────────┬──────────────┘
                                   │
           ┌───────────────────────┼───────────────────────┐
           │                       │                       │
           ▼                       ▼                       ▼
      BACKEND                 AI SYSTEMS              REALTIME
   APIs · Auth             RAG · Agents           SSE · Sockets
   Queues · Jobs           Tool Calling           Collaboration
   Databases               Embeddings             Event Streams
           │                       │                       │
           └───────────────────────┼───────────────────────┘
                                   ▼
                              SHIP IT.
```

I gravitate toward projects where the interesting part isn't only the interface.

It's the machinery underneath it — **APIs, workers, queues, data pipelines, retrieval, tools, streaming, state and all the failure cases between them.**

---

## `04` / My toolbox

<table>
<tr>
<td><b>Runtime</b></td>
<td>

`Node.js` · `TypeScript` · `JavaScript`

</td>
</tr>

<tr>
<td><b>Backend</b></td>
<td>

`Express` · `REST` · `JWT` · `OAuth` · `Socket.io` · `SSE` · `BullMQ`

</td>
</tr>

<tr>
<td><b>Data</b></td>
<td>

`PostgreSQL` · `MongoDB` · `Redis` · `Neon` · `Drizzle` · `Prisma`

</td>
</tr>

<tr>
<td><b>AI</b></td>
<td>

`Vercel AI SDK` · `LangChain` · `Gemini` · `Groq` · `RAG` · `Qdrant` · `Pinecone` · `Cohere`

</td>
</tr>

<tr>
<td><b>Web</b></td>
<td>

`React` · `Next.js` · `Tailwind CSS` · `shadcn/ui`

</td>
</tr>

<tr>
<td><b>Systems</b></td>
<td>

`Docker` · `AWS EC2` · `Vercel` · `Trigger.dev` · `Browserbase` · `Liveblocks`

</td>
</tr>
</table>

---

## `05` / How I got here

```text
2024
 │
 ├── Backend Developer Intern · reaidy.io
 │
2025
 │
 ├── B.Tech CSE · Andhra University
 ├── MERN Stack Developer Intern · TEN
 ├── dbSmash
 │      └── Web + npm CLI
 │
2026
 │
 ├── Personal AI Agent
 ├── Collaborative Editor
 ├── Auto Browse
 ├── InboxValid MCP
 │
 └── BSDK                              ← now
```

A lot of these projects started the same way:

**“I wonder if I can build that.”**

Then the prototype needed auth.

Then a database.

Then queues.

Then streaming.

Then retries.

And suddenly it was a product.

---

## `06` / A little GitHub telemetry

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=siddreddy07&show_icons=true&hide_border=true&bg_color=00000000&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=siddreddy07&hide_border=true&background=00000000&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" />

</div>

---

<div align="center">

### I'm looking for the place where I can build the next hard thing.

Backend · AI Engineering · Developer Tools · Automation

I'm a **2025 Computer Science graduate from Andhra University**, currently based in India and looking for my first full-time engineering role.

<br/>

[**GitHub**](https://github.com/siddreddy07) · [**Portfolio**](https://siddharth-portfolio-delta.vercel.app/) · [**LinkedIn**](https://www.linkedin.com/in/n-siddharth-reddy/)

<br/>

<sub>build → break → understand → rebuild → ship</sub>

</div>
