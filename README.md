<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,45:6D28D9,100:0891B2&height=220&section=header&text=Aniruddha%20Chaudhari&fontSize=44&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Full-stack%20developer%20%E2%80%A2%20AI%20systems%20%E2%80%A2%20Products%20%E2%80%A2%20Experiments&descAlignY=58&descSize=16" alt="Aniruddha Chaudhari" />

### I build products that sit somewhere between **useful**, **technical**, and **slightly over-engineered**.

[**Portfolio**](https://aniruddhadev.in/) · [**LinkedIn**](https://linkedin.com/in/aniruddha2704) · [**LeetCode**](https://leetcode.com/aniruddha-chaudhari)

</div>

<br/>

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Product Engineering

Web and mobile products with real users, real state and the boring-but-important infrastructure around them.

**React · Next.js · React Native · Node.js**

</td>
<td width="33%" valign="top">

### 🧠 AI Systems

Agents, memory, RAG, structured data pipelines and AI features that do more than wrap a chat endpoint.

**Gemini · AI SDK · Vector Search · Agents**

</td>
<td width="33%" valign="top">

### 🧪 Experiments

Games, real-time systems, browser APIs, scraping, automation and whatever rabbit hole looks interesting next.

**Phaser · WebSockets · Docker · PostgreSQL**

</td>
</tr>
</table>

# 🚀 Featured work

## 01 — VantageZero

> **Hardware buildability intelligence:** how many units can we actually build today, and which component stops us?

<table>
<tr>
<td width="58%" valign="top">

Vantage watches public distributor and manufacturer pages for **stock, incoming quantity, lead time, price breaks and lifecycle status**.

The interesting part is not scraping the page — it is deciding whether the data can be trusted when the page changes.

- **5 custom collectors** across **3 regions**
- source-specific normalization into one canonical schema
- Zod validation before observations are written
- self-healing collectors with **identity, shape, continuity and collision gates**
- scheduled collection through GitHub Actions
- buildability, bottleneck and cross-supplier pricing views

**Stack**  
`Next.js` `TypeScript` `PostgreSQL` `Bright Data` `Zod`

[**Live app ↗**](https://vantagezero.vercel.app) · [**Repository ↗**](https://github.com/aniruddha-chaudhari/vantagezero)

</td>
<td width="42%" valign="top">

### Data flow

```mermaid
graph TD
    A[Supplier pages] --> B[Collectors]
    B --> C[Normalize]
    C --> D[Validate]
    D -->|valid| E[(PostgreSQL)]
    D -->|broken| F[Heal loop]
    F --> G[4 safety gates]
    G --> B
```

</td>
</tr>
</table>

---

<table>
<tr>
<td width="50%" valign="top">

## 02 — 🌌 Nebulax

### Pixel arcade universe

A retro browser arcade built around a strong visual identity rather than a generic game menu.

Includes multiple playable experiences:

- **BattleDeck**
- **Quizzy**
- **Skatepark Dash**
- **WodBlitz**

The UI mixes pixel-art styling, space imagery, parallax motion and interactive transitions.

**Stack**  
`Next.js` `React` `Phaser` `Framer Motion` `Tailwind CSS`

[**Repository ↗**](https://github.com/aniruddha-chaudhari/nebulax)

</td>
<td width="50%" valign="top">

## 03 — ✦ Gem AI

### Conversational AI with memory

A Gemini-powered chat application built as a complete product rather than a stateless demo.

- Google authentication
- persisted chat history
- streaming AI responses
- **per-user long-term memory**
- memory inspection and deletion
- responsive dark UI

**Stack**  
`Next.js` `React` `TypeScript` `Gemini` `Neon` `Prisma` `Supermemory`

[**Live app ↗**](https://gemai.aniruddhadev.in) · [**Repository ↗**](https://github.com/aniruddha-chaudhari/gemai)

</td>
</tr>
</table>

# 🧰 Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,python,postgres,mongodb,docker,git,github,tailwind&perline=12" alt="Tech stack" />

</div>

<br/>

| Area | Things I reach for |
|---|---|
| **Frontend** | TypeScript, React, Next.js, React Native, Tailwind CSS |
| **Backend** | Node.js, Express, Python, REST APIs, real-time systems |
| **Data** | PostgreSQL, MongoDB, Supabase, Neon, vector databases |
| **AI** | Gemini, Vercel AI SDK, agents, RAG, embeddings, memory |
| **Infra / tools** | Docker, GitHub Actions, Git, Cloudflare, scraping pipelines |

# 📈 GitHub activity

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aniruddha-chaudhari&theme=github_dark" alt="GitHub contribution summary" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=aniruddha-chaudhari&theme=github-compact&hide_border=true&area=true" alt="GitHub activity graph" />

</div>

# 🌐 Find me elsewhere

<div align="center">

[**aniruddhadev.in**](https://aniruddhadev.in/) · [**LinkedIn**](https://linkedin.com/in/aniruddha2704) · [**LeetCode**](https://leetcode.com/aniruddha-chaudhari) · [**Kaggle**](https://kaggle.com/aniruddhachaudhari27)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,55:6D28D9,100:111827&height=110&section=footer" alt="footer" />

</div>
