<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Hi%2C%20I'm%20SmileyBoy&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=AI%20%26%20Software%20Engineer%20%E2%80%A2%20LLMs%20%E2%80%A2%20RAG%20%E2%80%A2%20Python%20%E2%80%A2%20AWS&descAlignY=60&descSize=16&animation=fadeIn" width="100%" alt="SmileyBoy" />

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2C9FD8&center=true&vCenter=true&width=640&lines=I+take+AI+ideas+from+prototype+to+production.;LLM+pipelines+%E2%80%A2+RAG+%E2%80%A2+agents+%E2%80%A2+integrations;Shipped+a+tool+used+by+7%2C500%2B+people.;Daily+driver%3A+Claude+Code+%F0%9F%A4%96" alt="Typing SVG" /></a>

<a href="https://forgeoforigin.com"><img src="https://img.shields.io/badge/Live%20project-forgeoforigin.com-FF6B35?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Forge of Origin" /></a>
<img src="https://img.shields.io/badge/Discord-smileyboy-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: smileyboy" />
<a href="https://ko-fi.com/smileyboyy"><img src="https://img.shields.io/badge/Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi" /></a>

<img src="https://komarev.com/ghpvc/?username=smileyboy321&label=Profile%20views&color=2c5364&style=flat" alt="Profile views" />

</div>

---

## 👋 About me

Engineer from 🇪🇪 **Estonia** who likes turning AI ideas into things people actually use. I spent 3.5 years as a technical project manager on a B2B SaaS product, working from architecture to AWS deployment. Now I build AI-powered tools end to end in **Python**.

- 🧠 **LLM apps in practice:** prompting, **RAG**, multi-step agent pipelines, tool calling and output guardrails
- 🔌 **Integrations:** REST APIs, ATS APIs (Greenhouse / Lever / Ashby), the Gmail API, scrapers, scheduled pipelines
- 💸 **Right-sizing models:** small local models for bulk work, larger ones only where quality matters, and cloud APIs when they're worth the cost
- 🛡️ **Security mindset:** credential rotation, infra monitoring with alerting, and servers that don't trust the client
- 🚀 **Production experience:** [Forge of Origin](https://forgeoforigin.com) serves **7,500+ users** across **49+ releases**
- 🤖 I build with **Claude Code** every day, from prototype through debugging to shipping

---

## 🤖 AI projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎯 JobHunt: LLM job pipeline</h3>
      <p>An autonomous pipeline that discovers roles across 10+ job boards and ATS APIs, scores fit with an LLM, drafts tailored CVs and cover letters, and syncs replies from Gmail on a schedule.</p>
      <ul>
        <li>Multi-agent flow: <b>analyse → tailor → humanise → cover letter</b></li>
        <li><b>Model tiers:</b> 3B for bulk scoring, 7B/14B for anything that goes out</li>
        <li><b>Hallucination guardrail:</b> a second model fact-checks every answer against the source CV, and failures are blocked</li>
      </ul>
      <sub><b>Python · Ollama (Qwen 2.5) · Claude API · Playwright · Gmail API</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>⚖️ Estonian Law RAG Assistant</h3>
      <p>Question answering over Estonian legislation: ~1,000 official legal PDFs are chunked, embedded and stored in a vector DB, and answers are grounded in the retrieved passages.</p>
      <ul>
        <li>PDF ingestion → chunking → <b>ChromaDB</b> retrieval</li>
        <li><b>Claude</b> answers questions in plain language</li>
      </ul>
      <sub><b>Python · ChromaDB · Claude API · Prompt engineering</b></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧩 Local AI Agent</h3>
      <p>A self-hosted coding and research agent with its own tool-calling loop (files, shell, web search) and a local RAG knowledge base. It runs on a local GPU and can fall back to a cloud model.</p>
      <sub><b>Python · asyncio · Ollama · TF-IDF retrieval</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>🎨 Generative AI Pipelines</h3>
      <p>Generates game art with <b>Stable Diffusion XL</b> on a local GPU, using prompts built from the game's own data, plus <b>Whisper</b> speech-to-text for meeting transcripts and subtitles.</p>
      <sub><b>Python · PyTorch · SDXL · Whisper</b></sub>
    </td>
  </tr>
</table>

## 🛠️ Other things I've built

| Project | What it is | Stack |
|---|---|---|
| ⚔️ **[Forge of Origin](https://forgeoforigin.com)** | Character build planner for an MMORPG: 36 classes, skill trees, a progression simulator, build sharing. **7,500+ users, 49+ releases** | JS · Supabase (Postgres, RLS) · Cloudflare Workers · CI/CD |
| 🛰️ **Ring Zero** | Android roguelite with a **server-authoritative** backend: the server replays each run deterministically and signs tokens with HMAC, so it never trusts client results | Godot · Python · SQLite |
| 🎥 **FormFrame** | Frame-by-frame sports video analysis app: VFR-safe frame stepping, drawing tools, side-by-side compare | Kotlin · Jetpack Compose · CameraX · Media3 |
| 🎬 **[slowmo-fix](https://github.com/SmileyBoy321/slowmo-fix)** | Fixes slow-motion videos that play at normal speed (Qualcomm CamX bug). No root needed | Python · Android |

---

## 🧰 Tech stack

<div align="center">

**AI & Languages**<br/>
<img src="https://skillicons.dev/icons?i=python,js,kotlin,pytorch&theme=dark" alt="Languages" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" height="48" alt="Claude" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" height="48" alt="Ollama" />

**Cloud, Data & Infra**<br/>
<img src="https://skillicons.dev/icons?i=aws,docker,linux,cloudflare,supabase,postgres,sqlite,githubactions&theme=dark" alt="Cloud and infra" />

**Delivery**<br/>
<img src="https://skillicons.dev/icons?i=git,postman,figma&theme=dark" alt="Tools" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" height="48" alt="Jira" />
<img src="https://img.shields.io/badge/Scrum-6DB33F?style=for-the-badge&logo=scrumalliance&logoColor=white" height="48" alt="Scrum" />

</div>

---

## 💼 Experience

<details open>
<summary><b>Technical Project Manager</b>, B2B HR/staffing SaaS · <i>2022 – 2026</i></summary>
<br/>

- Took the product through its full lifecycle, from Figma prototypes to production on AWS, with a cross-functional team
- Rebuilt the AWS infrastructure and Docker architecture for better reliability and lower cost
- Built security monitoring for Docker, SSH, EC2 and CPU with real-time Discord alerts, and rotated all legacy credentials
- Ran sprints and backlog in Jira, and did API testing (Postman) and QA before each release
</details>

<details>
<summary><b>Customer Operations & Scrum Master</b>, Car rental SaaS · <i>2020 – 2021</i></summary>
<br/>

- Ran sprints for the backend and frontend teams, resolved 500+ integration tickets, and monitored production with Zabbix
</details>

<details>
<summary><b>IT Specialist</b> · <i>2018</i></summary>
<br/>

- Automated Linux administration with Python and Bash
</details>

<sub>🎓 IT Systems Administration (vocational) · IT Systems Junior Specialist, EQF Level 4</sub>

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="" />
