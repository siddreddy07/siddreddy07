<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,40:1E1B4B,75:4C1D95,100:0E7490&height=260&section=header&text=SIDDHARTH%20REDDY&fontSize=56&fontColor=FFFFFF&fontAlignY=36&desc=BACKEND%20%C2%B7%20FULL%20STACK%20%C2%B7%20AI%20ENGINEERING&descSize=16&descAlignY=58&descColor=A5B4FC&animation=twinkling" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3200&pause=900&color=A5B4FC&center=true&vCenter=true&width=700&height=40&lines=%3E+Building+things+that+actually+work.;%3E+Backend-first.+Full-stack+when+it+counts.;%3E+RAG+pipelines+%C2%B7+agents+%C2%B7+developer+tools.;%3E+Turning+ideas+into+shipped+products." alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://siddharth-portfolio-delta.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-6D28D9?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/n-siddharth-reddy/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/siddreddy07"><img src="https://img.shields.io/badge/GITHUB-0F172A?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://bsdk.siddharthreddy627.workers.dev/"><img src="https://img.shields.io/badge/LIVE_PROJECT-0E7490?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4C1D95,50:6D28D9,100:0E7490&height=2" width="100%" />

<br/>

## ◈ &nbsp;TRANSMISSION

> **I build backends that hold up, and the products that sit on top of them.**

I'm a backend-first full-stack developer. I like the part of a product you don't see: API design, data retrieval, queues, caching, and the reliability work that keeps it all running. Lately that means **LLM applications, RAG pipelines and agentic workflows**, shipped as real products rather than demos.

<table>
<tr>
<td width="50%" valign="top">

**▸ Currently**
- Shipping independent products
- Building RAG + tool-calling systems
- Designing SDKs other developers can drop in

</td>
<td width="50%" valign="top">

**▸ Principles**
- Learn by implementation
- Solve real engineering problems
- Ship, then iterate

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4C1D95,50:6D28D9,100:0E7490&height=2" width="100%" />

<br/>

## ◈ &nbsp;STACK

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,nodejs,express,react,nextjs,tailwind,html,css&theme=dark&perline=9" />
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma,docker,aws,git,github,vercel,postman,vite&theme=dark&perline=11" />

</div>

<br/>

| Layer | What I work with |
|:--|:--|
| **Backend** | `Node.js` · `Express` · `REST` · `JWT` · `OAuth` · `RBAC` · `WebSockets` · `Streaming` · `BullMQ` |
| **Frontend** | `React` · `Next.js` · `Tailwind CSS` · `shadcn/ui` |
| **Data** | `PostgreSQL` · `MongoDB` · `Redis` · `Prisma` · `Drizzle ORM` · `Vector DBs` |
| **AI** | `RAG` · `Embeddings` · `Vector Search` · `AI Agents` · `Tool Calling` · `Vercel AI SDK` · `LangChain` |
| **Ship** | `Docker` · `AWS` · `Vercel` · `GitHub` · `pnpm` · `Postman` |

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4C1D95,50:6D28D9,100:0E7490&height=2" width="100%" />

<br/>

## ◈ &nbsp;FLAGSHIP

<div align="center">

# ⚡ BSDK

### The chat SDK for AI-native websites

*An embeddable AI chat widget that answers visitor questions from a site's own content.*

<br/>

<a href="https://bsdk.siddharthreddy627.workers.dev/"><img src="https://img.shields.io/badge/VIEW_LIVE-6D28D9?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>
<a href="https://bsdk.siddharthreddy627.workers.dev/try"><img src="https://img.shields.io/badge/TRY_THE_PLAYGROUND-0E7490?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</div>

<br/>

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1E1B4B','primaryTextColor':'#E0E7FF','primaryBorderColor':'#6D28D9','lineColor':'#22D3EE','secondaryColor':'#0E7490','tertiaryColor':'#020617','fontFamily':'monospace'}}}%%
flowchart LR
    V([Visitor]) --> W["Chat Widget<br/>React 19 · Tailwind 4 · shadcn/ui"]
    W -- streaming --> S["Server Runtime<br/>Express 5 · tool orchestration"]
    S --> R["Retrieval"]
    R --> P[("Pinecone<br/>vector search")]
    S --> M{{"Model Router<br/>Groq · Gemini · OpenAI · Anthropic"}}
    D["Site content"] --> I["Ingestion<br/>chunk → Cohere embeddings"]
    I --> P
```

<table>
<tr>
<td width="50%" valign="top">

**▸ Architecture**

| | |
|:--|:--|
| Monorepo | pnpm + Turborepo |
| UI SDK | React 19, Tailwind 4, shadcn/ui |
| Runtime | Streaming, retrieval, tools |
| Knowledge | Ingestion, chunking, embeddings |
| Vectors | Pinecone + Cohere |
| Models | Groq, Gemini, OpenAI, Anthropic |
| API | Express 5 + MongoDB |

</td>
<td width="50%" valign="top">

**▸ What I built**
- An embeddable chat experience
- A streaming backend runtime
- Document retrieval over a site's own knowledge
- Tool integration across multiple model providers
- Clean package split: UI, server runtime, CLI, playground
- Compatibility with Vercel AI SDK models

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0E7490,50:6D28D9,100:4C1D95&height=2" width="100%" />

<br/>

<div align="center">

# 🔍 Intelligent Log Analyzer

### Fewer alerts. Better alerts.

*Base14 Product Engineer take-home assignment*

<a href="https://github.com/siddreddy07/Intelligent-log-analyzer"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-0F172A?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

<br/>

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1E1B4B','primaryTextColor':'#E0E7FF','primaryBorderColor':'#6D28D9','lineColor':'#22D3EE','fontFamily':'monospace'}}}%%
flowchart LR
    L["Raw logs<br/>multiple formats"] --> P["Parser<br/>TypeScript"]
    P --> D["Pattern + error-rate<br/>detection"]
    D --> G["Grouping<br/>dedup + correlation"]
    G --> A["Alerts<br/>probable cause + evidence"]
```

A log analysis and alert generation system that finds meaningful patterns in application logs and cuts alert noise.

- **Parse** multiple log formats with TypeScript
- **Detect** patterns and error-rate spikes across configurable windows and thresholds
- **Correlate** related findings into incidents
- **Reduce noise** through grouping and deduplication
- **Explain** every alert with probable causes and supporting evidence

`Node.js` · `TypeScript` · `Express` · `YAML`

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4C1D95,50:6D28D9,100:0E7490&height=2" width="100%" />

<br/>

## ◈ &nbsp;EXPLORING

| Area | Focus |
|:--|:--|
| 🛠 **Backend Engineering** | API architecture, scalability, queues, caching |
| 🤖 **AI Engineering** | RAG, agent workflows, tool orchestration |
| 🗄 **Data Systems** | Redis, PostgreSQL, MongoDB, vector search |
| 📦 **Developer Experience** | SDKs, reusable packages, CLI tooling |
| 🧭 **System Design** | Reliability, observability, distributed workflows |

<br/>

<div align="center">

<a href="https://github.com/siddreddy07"><img src="https://img.shields.io/badge/GitHub-siddreddy07-0F172A?style=for-the-badge&logo=github" /></a>
<a href="https://www.linkedin.com/in/n-siddharth-reddy/"><img src="https://img.shields.io/badge/LinkedIn-Siddharth_Reddy-0A66C2?style=for-the-badge&logo=linkedin" /></a>
<a href="https://siddharth-portfolio-delta.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-My_Work-6D28D9?style=for-the-badge&logo=vercel" /></a>

<br/><br/>

**`Curiosity  →  Code  →  Experiments  →  Better Systems`**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0E7490,40:4C1D95,75:1E1B4B,100:020617&height=140&section=footer&animation=twinkling" width="100%" />

</div>
