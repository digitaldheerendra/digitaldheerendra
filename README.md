<div align="center">

<img src="./assets/terminal.svg" alt="Dheerendra Kumar: Full-Stack Engineer, Laravel, React, React Native, real-time systems" width="100%"/>

<br/>

<a href="https://digitaldheerendra.in/"><img src="https://img.shields.io/badge/Portfolio-digitaldheerendra.in-0d1117?style=for-the-badge&logo=googlechrome&logoColor=58a6ff" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/digtaldheerendra"><img src="https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn"/></a>
<a href="https://www.instagram.com/dheerendradigital"><img src="https://img.shields.io/badge/Instagram-dheerendradigital-0d1117?style=for-the-badge&logo=instagram&logoColor=bc8cff" alt="Instagram"/></a>
<img src="https://img.shields.io/badge/Based_in-Noida,_India-0d1117?style=for-the-badge&logo=googlemaps&logoColor=3fb950" alt="Noida, India"/>

</div>

---

### `$ cat about.md`

I build products that have to work **while people are using them**: live chat, audio and video calls, per-minute wallet billing, and push notifications that ring a phone even when the app is killed. I also build web frontends that load fast.

For **9+ years** I've taken products from a blank repo to production and kept them running. I work across the whole system: database schema, API, web app, mobile app and deployment.

```yaml
engineer:
  name: Dheerendra Kumar
  role: Full-Stack Engineer (web + mobile)
  experience: 9+ years
  core: [Laravel, PHP, React, React Native, TypeScript, Node.js]
  strengths:
    - real-time systems (chat, voice/video calls, presence)
    - payment & wallet flows built to be safe against double-charging
    - performance-first websites (SSR, prerendering, Core Web Vitals)
    - debugging production issues nobody else could reproduce
  currently: building real-time consultation apps on web + Android + iOS
  open_to: freelance, contract & long-term product work
```

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
| **Portfolio & theme builds** | Custom portfolio and theme websites for clients | TypeScript · JavaScript |

<sub>Most client work lives in private repositories. Happy to walk through the code and architecture on a call.</sub>

---

### `$ which tools`

<p align="left">
  <img src="https://skillicons.dev/icons?i=php,laravel,js,ts,react,nodejs,mysql,tailwind,vite,firebase,wordpress,html,css,git,github,linux,vscode&perline=17" alt="PHP, Laravel, JavaScript, TypeScript, React, Node.js, MySQL, Tailwind, Vite, Firebase, WordPress, HTML, CSS, Git, GitHub, Linux, VS Code"/>
</p>

**Mobile:** React Native (Android & iOS) · **Real-time:** Agora RTC/RTM, Firebase Cloud Messaging · **Web perf:** SSR, static prerendering, image & font optimisation

---

### `$ cat principles.txt`

```text
1. Production is sacred    →  every change is reversible and nothing ships untested
2. Find the root cause     →  reproduce first, then fix the cause instead of the symptom
3. Measure, don't guess    →  Lighthouse, logs and profiler before any "optimisation"
4. Boring tech, sharp code →  proven tools, clean boundaries, readable diffs
5. Own the outcome         →  I stay on it until it works on the user's phone, not just on my machine
```

---

### `$ git log --graph --all`

<div align="center">

<img src="https://streak-stats.demolab.com?user=digitaldheerendra&theme=github-dark-blue&hide_border=true&border_radius=12" alt="GitHub streak" width="49%"/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=digitaldheerendra&theme=github-compact&hide_border=true&radius=12&area=true" alt="Contribution graph" width="49%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/digitaldheerendra/digitaldheerendra/output/snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/digitaldheerendra/digitaldheerendra/output/snake.svg" alt="Contribution snake animation" width="100%"/>
</picture>

</div>

---

<div align="center">

### `$ ./hire --dheerendra`

**Have a product that has to be fast, real-time and reliable?** Let's talk.

<a href="https://digitaldheerendra.in/"><img src="https://img.shields.io/badge/Start_a_project-→-3fb950?style=for-the-badge" alt="Start a project"/></a>

</div>
