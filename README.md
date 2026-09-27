<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
    <img alt="Akshit Dhiman — Software Engineer" src="./assets/banner-light.svg" width="100%">
  </picture>
</p>

<p align="center">
  <sub>Software engineer at <b>Wise</b> &nbsp;·&nbsp; Bengaluru, India &nbsp;·&nbsp; <a href="mailto:akshithdh@gmail.com">akshithdh@gmail.com</a></sub>
</p>

<br>

I work on distributed systems, real-time infrastructure, and the automation layer in between.

Most of what I build lives in the gap where the naive version works fine on your laptop and falls over under load or with three users instead of one — state that has to stay consistent, work that has to finish without supervision, and interfaces that stay honest while all of it happens underneath.

I'm more interested in the parts people skip: the retry that actually retries, the migration that doesn't lock the table, the error message that tells you what to do next.

---

## how I think about problems

**Concurrency that doesn't lie.** WebRTC mesh topologies, signaling servers, TURN fallback for when the network gives up. Designed around eventual consistency instead of the illusion of immediate consistency.

**Pipelines that finish on their own.** Dependency graphs where execution order is *derived* rather than hardcoded. Independent work runs in parallel, failures stay isolated, and every run is replayable after the fact.

**Keeping models in a small box.** AI features where the probabilistic part is deliberately narrow — read the label, find the SKU — and deterministic code does the deciding. Narrower surface, easier to test, easier to trust, far easier to debug at 2am.

**Interfaces that stay responsive.** Optimistic updates, delta sync instead of full re-renders, and a real loading state for every state.

---

## stack

<table>
<tr>
<td valign="top" width="50%">

**Languages**
<sub>TypeScript · JavaScript · Python · SQL · Bash</sub>

**Frontend**
<sub>React · Next.js · Monaco · Tailwind</sub>

</td>
<td valign="top" width="50%">

**Real-time &amp; backend**
<sub>Node.js · WebRTC · Socket.IO · WebSockets · coturn (TURN) · REST · PostgreSQL · Redis</sub>

**Infrastructure**
<sub>Docker · GitHub Actions · Nginx · Vercel</sub>

</td>
</tr>
</table>

---

## repositories worth a look

| | repository | what it demonstrates |
|---|---|---|
| **01** | [**Weaave**](https://github.com/akshithdh/Weaave) | A dependency graph where execution order is resolved at runtime, independent nodes are scheduled in parallel, and each run persists enough state to explain itself. |
| **02** | [**PackCheck**](https://github.com/akshithdh/PackCheck) | Perception delegated to a vision model, the verdict left to deterministic rules — then reconciling every label against a packing list and calling the result. |

---

## currently

```text
day job       rules & decisioning for customer due diligence @ Wise
building      AI workflow orchestration, realtime collaboration
sharpening    distributed systems, system design, the parts of C++ I keep avoiding
leetcode      1986 — top 2% · peak contest rank 193 / 29,215
```

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

<p align="center"><sub>Happy to talk about hard distributed problems, or to review PRs on anything in the stack above.</sub></p>
