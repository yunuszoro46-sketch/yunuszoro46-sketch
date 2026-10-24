<!-- Profile README for github.com/yunuszoro46-sketch. All custom visuals are SVGs in ./assets (see assets/*.svg). -->

<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Yunus Been Hashem — Aspiring Software Engineer, AI and Full-Stack Development. CSE at University of Asia Pacific, Dhaka." />
</p>

<h1 align="center">Yunus Been Hashem</h1>

<p align="center">
  <b>Aspiring Software Engineer · AI &amp; Full-Stack Development</b><br/>
  CSE undergraduate at University of Asia Pacific, Dhaka. I build practical, tested software for real local problems.
</p>

<p align="center">
  <code>[✓] based in Dhaka (UTC+6)</code>&nbsp;
  <code>[✓] 2× hackathon champion</code>&nbsp;
  <code>[✓] open to internships</code>
</p>

<p align="center">
  <a href="#featured-projects"><img src="./assets/btn-projects.svg" height="44" alt="$ ls ~/projects — jump to featured projects" /></a>&nbsp;&nbsp;
  <a href="#contact"><img src="./assets/btn-contact.svg" height="44" alt="./contact --hire — jump to contact" /></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yunus-been-hashem-7632b3444/">LinkedIn</a> ·
  <a href="https://github.com/yunuszoro46-sketch">GitHub</a> ·
  <a href="#featured-projects">Projects</a> ·
  <a href="#achievements">Achievements</a> ·
  <a href="#contact">Contact</a>
</p>

<br/>

<img src="./assets/prompt-whoami.svg" height="26" alt="yunus@uap:~$ neofetch" />

<img src="./assets/neofetch.svg" width="100%" alt="neofetch card: Yunus Been Hashem, Aspiring Software Engineer. CSE at University of Asia Pacific, Dhaka (UTC+6). Focus: AI-powered apps and full-stack. Stack: TypeScript, Java, C++, Python. Tools: Node.js, React, Next.js, SQLite, Git. 2× hackathon champion, 1× rising star. Open to internships and hackathon teams." />

<img src="./assets/prompt-about.svg" height="26" alt="yunus@uap:~$ cat about.md" />

## About Me

I'm a Computer Science and Engineering undergraduate at the **University of Asia Pacific (UAP)** in Dhaka. I like software that solves a specific problem for specific people: event registration for a student club, generator schedules during load-shedding, routes and fares for Dhaka commuters.

Most of what I've built started at a hackathon. The format suits me: a fixed deadline, a real brief, and a working demo at the end. Lately I've focused on **AI-powered applications**, with one rule I try to keep: the core logic should be deterministic and tested, and the model should add value on top of it rather than hold the system up. I use AI coding tools in my workflow and check their output with automated tests.

Alongside projects, I'm strengthening my computer science fundamentals — data structures and algorithms in C++, and core concepts in Java — because I want to write software that stays maintainable after the demo.

<img src="./assets/prompt-achievements.svg" height="26" alt="yunus@uap:~$ cat achievements.log" />

## Achievements

| Result | Competition | Details |
|---|---|---|
| **Champion** (1st place) | 9th DRMC International Tech Carnival 2026 — AI Web Development segment | Organized by DRMC IT Club · Project: [Smart Club Operations](https://github.com/yunuszoro46-sketch/9th-DRMC-International-Tech-Carnival-2026-) |
| **Champion** | UAP HackApex Intra Hackathon | Project: [StayOn](https://github.com/yunuszoro46-sketch/HackApex-Intra-Hackathon) (team) |
| **Rising Star** | Mini Hackathon Contest, Dev Fusion — May 2026 | Software &amp; Hardware Club, CSE-UAP · Team "The Beta Testers" |

Also built for: 3rd IAIT National IT Fest Hackathon (INIF 2026) — [DhakaPath](https://github.com/yunuszoro46-sketch/DhakaPath) · HackOberfest Hack Day Dhaka — [TeamMate](https://github.com/yunuszoro46-sketch/HackOberfest-Hack-Day-Dhaka)

<img src="./assets/prompt-projects.svg" height="26" alt="yunus@uap:~$ ls -la ~/projects  # 4 selected" />

## Featured Projects

<a href="https://github.com/yunuszoro46-sketch/9th-DRMC-International-Tech-Carnival-2026-"><img src="./assets/project-smart-club.svg" width="100%" alt="smart-club-ops — event platform for student clubs with a registration form builder, server-enforced rules and revocable QR digital passes. Champion project, AI Web Development, 9th DRMC International Tech Carnival 2026. React, Vite, Node.js, SQLite, JWT." /></a>

**Smart Club Operations Platform** — [source](https://github.com/yunuszoro46-sketch/9th-DRMC-International-Tech-Carnival-2026-) · [live demo](https://nineth-drmc-international-tech-carnival.onrender.com/)

<details>
<summary>Key features</summary>

- Event discovery with search and club/category filters; registration without an account
- Organizer console with a registration form builder, approval flow, archiving and a live dashboard
- Server-enforced rules: deadlines, seat limits, duplicate prevention; QR digital passes that can be revoked
- Organizer sign-in exchanges a shared key for a short-lived JWT
- "Tech Guide" assistant answers from live event data; an OpenAI-compatible model is optional and off by default
- **Stack:** React 19 · Vite · Node.js (native HTTP, layered services/repositories) · SQLite (`node:sqlite`)

</details>

<a href="https://github.com/yunuszoro46-sketch/HackApex-Intra-Hackathon"><img src="./assets/project-stayon.svg" width="100%" alt="stayon — generator rosters for load-shedding days: a provably optimal schedule under capacity and diesel limits, with a reason for every shop left dark. Team project, UAP HackApex. JavaScript, Node.js." /></a>

**StayOn** — [source](https://github.com/yunuszoro46-sketch/HackApex-Intra-Hackathon) · [live demo](https://hackapex-intra-hackathon-6d7w.onrender.com/)

<details>
<summary>Key features</summary>

- Computes a roster that is proven optimal within the rules: never overloads the generator, never exceeds the diesel budget, always powers mandatory loads (e.g. a pharmacy fridge)
- Gives a reason with real numbers for every shop left dark
- When no roster can satisfy every rule, reports which rule fails and by how much
- 39 automated tests, including a comparison against a brute-force solver on 300 random markets; zero dependencies
- **Stack:** JavaScript · Node.js · Node test runner

</details>

<a href="https://github.com/yunuszoro46-sketch/DhakaPath"><img src="./assets/project-dhakapath.svg" width="100%" alt="dhakapath — route, fare and street-alert assistant for Dhaka commuters; a transit graph decides routes and fares and it works without an AI key. Team project, INIF 2026. Node.js, vanilla JavaScript, Leaflet." /></a>

**DhakaPath** — [source](https://github.com/yunuszoro46-sketch/DhakaPath) · [live demo](https://threerd-iait-national-it-fest-hackathon.onrender.com/)

<details>
<summary>Key features</summary>

- The network graph decides routes, fares and alerts; AI only interprets messages and phrases explanations — everything works without an AI key
- Bus and MRT-6 fares follow published official rates; rickshaw and CNG fares are clearly labelled as estimates
- Monsoon mode for heavy-rain disruptions, full Bangla interface, admin CMS for alerts
- 96 automated tests; one Node.js process, no database, no required dependencies
- **Stack:** Node.js · vanilla JavaScript (ES modules) · Leaflet · optional Gemini / Groq

</details>

<a href="https://github.com/yunuszoro46-sketch/HackOberfest-Hack-Day-Dhaka"><img src="./assets/project-teammate.svg" width="100%" alt="teammate — a supervisor for AI coding agents: AI critic council, human sign-off, a compiled build prompt with acceptance tests, then verification of the agent's report. HackOberfest Hack Day Dhaka. Next.js, TypeScript, Gemini API, Playwright." /></a>

**TeamMate** — [source](https://github.com/yunuszoro46-sketch/HackOberfest-Hack-Day-Dhaka) · [live demo](https://hackoberfest-hack-day-dhaka-1.onrender.com/)

<details>
<summary>Key features</summary>

- Five fixed questions, a "council" of three AI critics and live competitor search
- Architecture options, a human sign-off step, then a compiled build prompt with acceptance tests
- Verifies a coding agent's report against each acceptance criterion and writes the fix-up prompt
- Every generated field is editable and lockable, with a provenance badge; runs in a mock mode without an API key
- **Stack:** Next.js · TypeScript · Tailwind CSS · Gemini API · Tavily search · Vitest · Playwright

</details>

<sub>Demos run on free hosting tiers; the first load after a quiet period can take up to a minute.</sub>

<img src="./assets/prompt-stack.svg" height="26" alt="yunus@uap:~$ cat stack.txt  # used in real projects" />

## Tech Stack

<img src="./assets/stack.svg" width="100%" alt="Tech stack. Languages: Java, C++, Python, TypeScript, JavaScript. Frontend: React, Next.js, Vite, Tailwind, HTML/CSS. Backend: Node.js, REST APIs, SQLite. AI: Gemini API, OpenAI-compatible APIs, Groq, Tavily. Testing: Vitest, Playwright, node:test. Tools: Git, GitHub, Linux, VS Code, Render, Vercel. Learning: DSA, Java fundamentals, system design, agent tooling." />

<img src="./assets/prompt-learning.svg" height="26" alt="yunus@uap:~$ git log --oneline learning/" />

## Currently Learning

- **Data structures and algorithms** — competitive programming practice in C++ ([ICPC-PRACTICE](https://github.com/yunuszoro46-sketch/ICPC-PRACTICE))
- **Java and computer science fundamentals** — OOP, core Java, systems design basics
- **Full-stack application development** — cleaner architecture, testing and deployment
- **AI-powered software and developer tooling** — reliable LLM integration and agent workflows

<img src="./assets/prompt-activity.svg" height="26" alt="yunus@uap:~$ gh stats" />

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yunuszoro46-sketch&show_icons=true&hide_border=true&hide_rank=true&bg_color=00000000&title_color=10b981&icon_color=10b981&text_color=8b949e&count_private=true&disable_animations=true" height="160" alt="GitHub statistics for yunuszoro46-sketch" />
</p>

<p align="center"><sub>The full contribution graph is shown below this README on the profile page.</sub></p>

<img src="./assets/prompt-contact.svg" height="26" alt="yunus@uap:~$ ./contact --hire" />

## Contact

<a href="https://www.linkedin.com/in/yunus-been-hashem-7632b3444/"><img src="./assets/contact.svg" width="100%" alt="Let's build something together. Open to internships, collaborations and hackathon teams. Opens LinkedIn." /></a>

<p align="center">
  <a href="https://www.linkedin.com/in/yunus-been-hashem-7632b3444/"><code>→ linkedin/yunus-been-hashem</code></a>&nbsp;
  <a href="https://github.com/yunuszoro46-sketch"><code>→ github/yunuszoro46-sketch</code></a>&nbsp;
  <a href="#featured-projects"><code>→ ~/projects</code></a>
</p>

<br/>

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="// There is no spoon. There is only the next problem to solve. — © 2026 Yunus Been Hashem, built in the terminal, shipped with tests." />
</p>
