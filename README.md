<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
    <img alt="Akshit Dhiman — Software Engineer" src="./assets/banner-light.svg" width="100%">
  </picture>
</p>

<p align="center">
  <sub>Bengaluru, India &nbsp;·&nbsp; <a href="mailto:akshithdh@gmail.com">akshithdh@gmail.com</a> &nbsp;·&nbsp; <a href="#projects">Projects</a> &nbsp;·&nbsp; <a href="#stack">Stack</a></sub>
</p>

<br>

Software engineer. B.Tech Computer Science (2026).

I build data pipelines and validation systems in Python, and real-time product features in TypeScript. Most of my work sits in rule-driven systems — high-volume structured data, exception analysis, and the automation that removes the manual step.

---

<a name="projects"></a>

## projects

<table>
<tr><td valign="top" width="18%">

**Weaave**
<sub>Next.js · TypeScript · Gemini API · Trigger.dev · Prisma · PostgreSQL</sub>

</td><td valign="top">

Visual DAG workflow orchestrator. Nodes are placed on a canvas and validated for types and cycles, then executed by a parallel engine that resolves dependencies topologically and offloads Gemini multimodal and FFmpeg work to cloud workers.
Every node records its input, output, and duration in a PostgreSQL-backed run history, and failures propagate a skip signal downstream instead of stalling the run.
<sub>Unit and integration tests on node execution and API contracts.</sub>

</td></tr>
<tr><td valign="top">

**PairLane**
<sub>Next.js · Node.js · Express · Socket.IO · WebRTC · Monaco · MongoDB</sub>

</td><td valign="top">

Browser-based collaborative coding rooms: shared workspaces, live cursors, presence, drawing overlays, and mesh video calls.
Editor sync was reworked from full-document replacement to operation-based Monaco delta edits over Socket.IO, which cut payload size and holds sub-30ms sync latency. WebRTC full-mesh signaling with a self-hosted coturn TURN fallback for restrictive networks.
<sub>Unit tests over editor-sync and signaling logic.</sub>

</td></tr>
<tr><td valign="top">

**Job Agent**
<sub>Python · SQLite · Ollama · AsyncIO</sub>

</td><td valign="top">

Automated job search engine. Parses company career pages, isolates openings, and ranks them using four configurable match and opportunity-scoring parameters. Local LLMs through Ollama compile tailored application profiles and recruiter outreach drafts from user data — no data leaves the machine.

</td></tr>
</table>

---

<a name="stack"></a>

## stack

<table>
<tr>
<td valign="top" width="50%">

**Languages**
<sub>C++ · Java · Python · JavaScript · TypeScript · SQL</sub>

**Backend &amp; real-time**
<sub>Node.js · Express · REST · WebSockets · Socket.IO · WebRTC · coturn</sub>

**Frontend**
<sub>Next.js · React · Monaco · Tailwind · HTML · CSS</sub>

</td>
<td valign="top" width="50%">

**Data**
<sub>PostgreSQL · MongoDB Atlas · SQLite</sub>

**Testing**
<sub>Jest · Pytest · unit &amp; integration testing</sub>

**Infrastructure**
<sub>Linux · Nginx · PM2 · Vercel · GitHub Actions · Docker</sub>

**Core CS**
<sub>Data structures &amp; algorithms · distributed systems · operating systems · computer networks</sub>

</td>
</tr>
</table>

---

## currently

- LeetCode **1986** — top ~2% globally, 620+ problems solved. Weekly Contest 476: **193 / 29,215** (top 0.66%)
- Building agent pipelines and real-time collaboration tooling
- **Open to full-time software engineering roles**

---

<p align="center">
  <a href="https://github.com/akshithdh">GitHub</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://leetcode.com/akshitxd">LeetCode</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/akshitxdhiman/">LinkedIn</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:akshithdh@gmail.com">Email</a>
</p>
