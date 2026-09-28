<div align="center">

<img src="./assets/terminal.svg" alt="Dheerendra Kumar: Full-Stack and AI Engineer. Laravel, React, React Native, WordPress, AI chatbots and automation" width="100%"/>

<br/>

<a href="https://digitaldheerendra.in/"><img src="https://img.shields.io/badge/Portfolio-digitaldheerendra.in-0d1117?style=for-the-badge&logo=googlechrome&logoColor=58a6ff" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/digtaldheerendra"><img src="https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn"/></a>
<a href="https://www.instagram.com/dheerendradigital"><img src="https://img.shields.io/badge/Instagram-dheerendradigital-0d1117?style=for-the-badge&logo=instagram&logoColor=bc8cff" alt="Instagram"/></a>
<img src="https://img.shields.io/badge/Based_in-Noida,_India-0d1117?style=for-the-badge&logo=googlemaps&logoColor=3fb950" alt="Noida, India"/>

</div>

---

### `$ cat about.md`

I'm a **Full-Stack & AI Engineer** with **9+ years** of shipping production software in **Laravel, React, React Native and WordPress**. I now add AI to those products: chatbots that answer from a business's own data, automations that take repetitive work off a team, and LLM features inside apps people already use.

I also build the difficult real-time parts: live chat, voice and video calls, per-minute wallet billing, and push notifications that still ring when the app is killed. I usually own the whole system, from database schema and API to web app, mobile app and deployment.

```yaml
engineer:
  name: Dheerendra Kumar
  role: Full-Stack & AI Engineer (web · mobile · AI)
  experience: 9+ years
  core_stack: [Laravel, React, React Native, WordPress]
  ai:
    chatbots: website, WhatsApp & in-app assistants trained on your own data
    automation: lead handling, support triage, document & data extraction, reporting
    integration: OpenAI, Claude & Gemini APIs inside Laravel, React, mobile & WordPress
  also_strong_in:
    - real-time systems (chat, voice/video calls, presence)
    - payment & wallet flows built to be safe against double-charging
    - performance-first websites (SSR, prerendering, Core Web Vitals)
  open_to: freelance, contract & long-term product work
```

---

### `$ ls ~/stack`

<img src="./assets/stack.svg" alt="Laravel: APIs, queues, payments, LLM and RAG backends. React: web apps, SSR sites, streaming AI chat UIs. React Native: Android and iOS apps, Agora calls, FCM, in-app AI assistants. WordPress: custom themes and plugins, WooCommerce, AI chat and content plugins. AI layer across all of them: chatbots, AI automation, LLM integration, RAG on your own data." width="100%"/>

---

### `$ ./ai --explain` — what I build with AI

<table>
<tr>
<td width="33%" valign="top">

#### 🤖 AI Chatbots
Website, **WhatsApp** and in-app bots that answer from **your own content**: docs, products, FAQs, policies. They capture leads, book appointments and hand the conversation to a human when needed.

</td>
<td width="33%" valign="top">

#### ⚡ AI Automation
Workflows that remove repetitive work. For example: classify and route incoming leads and emails, extract data from PDFs and forms, draft replies, sync CRMs and sheets, and send daily reports.

</td>
<td width="33%" valign="top">

#### 🧩 AI Integration
LLM features inside **existing** products: smart search, summaries, content generation, recommendations and assistants in Laravel, React, React Native and WordPress apps.

</td>
</tr>
</table>

**How a production AI chatbot is wired:**

```mermaid
flowchart LR
    U["👤 Customer<br/>Website · WhatsApp · App"] --> API["⚙️ Laravel API<br/>auth · rate limits · logs"]
    API --> R["🔎 Retrieval<br/>vector search on business data"]
    R --> LLM["🧠 LLM<br/>OpenAI · Claude · Gemini"]
    LLM --> T{"Needs an action?"}
    T -- "yes" --> A["🛠️ Tools<br/>book · CRM · order status"]
    T -- "no" --> U
    A --> U
    LLM -. "low confidence" .-> H["🙋 Human handoff"]
```

What separates a demo from a real product: grounding answers in real data so the bot doesn't make things up, guardrails, cost and token limits, conversation logs, and a clean handoff to a human.

---

### `$ tree ~/architecture` — how I ship a real-time app

```mermaid
flowchart LR
    U["📱 React Native app<br/>🌐 React web app"] -- "REST / JSON" --> API["⚙️ Laravel API"]
    API --> DB[("🗄️ Database")]
    API --> W["💰 Wallet<br/>per-minute billing"]
    U <-- "voice · video · chat" --> RTC["📡 Agora RTC / RTM"]
    API -- "token + session" --> RTC
    API -- "FCM high-priority push" --> N["🔔 Incoming-call screen<br/>works on lock screen & killed app"]
    N --> U
```

Most of the hard work is in the edge cases: dropped networks mid-call, wallet balance running out during a session, duplicate webhooks, Android background limits, and notifications that must ring even when the app is closed.

---

### `$ ls ~/shipped`

| Project | What it is | Stack |
|---|---|---|
| **Astrology consultation platform** | Paid chat, audio & video consultations with live wallet deduction, incoming-call UI and admin panel | Laravel · React · React Native · Agora · FCM |
| **Exam portal** | Online exams, question banks, results and admin management | PHP |
| **LPG agency system** | Management software for an LPG distribution agency | TypeScript |
| **Service-business websites** | SEO-first, prerendered React sites that score high on Core Web Vitals | React · Vite · SSR |
| **WordPress builds** | Custom themes, plugins and business websites for clients | WordPress · PHP |

<sub>Most client work lives in private repositories. Happy to walk through the code and architecture on a call.</sub>

---

### `$ which tools`

<p align="left">
  <img src="https://skillicons.dev/icons?i=laravel,php,react,wordpress,js,ts,nodejs,mysql,tailwind,vite,firebase,html,css,git,github,linux,vscode&perline=17" alt="Laravel, PHP, React, WordPress, JavaScript, TypeScript, Node.js, MySQL, Tailwind, Vite, Firebase, HTML, CSS, Git, GitHub, Linux, VS Code"/>
</p>

**AI & automation**

<img src="https://img.shields.io/badge/OpenAI_API-0d1117?style=for-the-badge&logoColor=white" alt="OpenAI API"/>
<img src="https://img.shields.io/badge/Claude_API-0d1117?style=for-the-badge&logo=anthropic&logoColor=d97757" alt="Claude API"/>
<img src="https://img.shields.io/badge/Gemini-0d1117?style=for-the-badge&logo=googlegemini&logoColor=8e75b2" alt="Gemini"/>
<img src="https://img.shields.io/badge/LangChain-0d1117?style=for-the-badge&logo=langchain&logoColor=3fb950" alt="LangChain"/>
<img src="https://img.shields.io/badge/n8n-0d1117?style=for-the-badge&logo=n8n&logoColor=ea4b71" alt="n8n"/>
<img src="https://img.shields.io/badge/Make-0d1117?style=for-the-badge&logo=make&logoColor=bc8cff" alt="Make"/>
<img src="https://img.shields.io/badge/Zapier-0d1117?style=for-the-badge&logo=zapier&logoColor=ff4f00" alt="Zapier"/>
<img src="https://img.shields.io/badge/WhatsApp_API-0d1117?style=for-the-badge&logo=whatsapp&logoColor=25d366" alt="WhatsApp Business API"/>

**Mobile:** React Native (Android & iOS) · **Real-time:** Agora RTC/RTM, Firebase Cloud Messaging · **Web perf:** SSR, static prerendering, image & font optimisation

---

### `$ cat principles.txt`

```text
1. Production is sacred    →  every change is reversible and nothing ships untested
2. Find the root cause     →  reproduce first, then fix the cause instead of the symptom
3. Measure, don't guess    →  Lighthouse, logs and profiler before any "optimisation"
4. AI with guardrails      →  grounded in real data, logged, cost-capped, with a human fallback
5. Own the outcome         →  I stay on it until it works on the user's phone, not just on my machine
```

---

### `$ git log --graph --all`

<div align="center">

<img src="https://streak-stats.demolab.com?user=digitaldheerendra&theme=github-dark-blue&hide_border=true&border_radius=12" alt="GitHub streak" width="70%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/digitaldheerendra/digitaldheerendra/output/snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/digitaldheerendra/digitaldheerendra/output/snake.svg" alt="Contribution snake animation" width="100%"/>
</picture>

</div>

---

<div align="center">

### `$ ./hire --dheerendra`

**Need an AI chatbot, an automation, or a product that has to be fast and reliable?** Let's talk.

<a href="https://digitaldheerendra.in/"><img src="https://img.shields.io/badge/Start_a_project-→-3fb950?style=for-the-badge" alt="Start a project"/></a>

</div>
