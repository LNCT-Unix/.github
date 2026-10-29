<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Team%20Unix&fontSize=64&fontColor=ffffff&animation=fadeIn&desc=Measure.%20Plan.%20Grow.&descSize=20&descAlignY=72" alt="Team Unix banner" width="100%" />

<a href="https://github.com/LNCT-Unix/AI-Powered-Upskilling-Platform">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=6366F1&center=true&vCenter=true&width=640&lines=We+build+tools+that+show+where+you+really+stand;Adaptive+tests.+AI+roadmaps.+Real+progress." alt="Typing tagline" />
</a>

<br/>

![Sprint](https://img.shields.io/badge/Sprint%201-in%20progress-6366F1?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-12%20members-0EA5E9?style=for-the-badge)
![College](https://img.shields.io/badge/LNCT-Bhopal-F97316?style=for-the-badge)
![Programme](https://img.shields.io/badge/EPAM-CoE%20Programme-10B981?style=for-the-badge)

</div>

---

## ✨ Who we are

We are a team of 12 students from **Lakshmi Narain College of Technology, Bhopal**, building for the **EPAM CoE programme**. We like problems where good engineering meets real learners.

## 🚀 What we are building

### AI Career & Skill Roadmap Platform

Most learners choose what to study by guesswork. We replace the guesswork with three steps:

<table>
  <tr>
    <td align="center" width="33%">
      <h3>📏 Measure</h3>
      A short adaptive test finds your real level in a chosen track, in fewer than 10 questions.
    </td>
    <td align="center" width="33%">
      <h3>🧭 Plan</h3>
      An AI model turns your result and the track's skill graph into an ordered learning roadmap.
    </td>
    <td align="center" width="33%">
      <h3>📈 Track</h3>
      Follow the roadmap, mark progress, and re-test to see how far you have come.
    </td>
  </tr>
</table>

Architecture designed by Dev Sharma, technical and design lead.

### 🏗️ How it fits together

```mermaid
flowchart LR
    A["Web and mobile apps"] --> B["Spring Boot gateway<br/>auth, orgs, skill graph, test engine"]
    B --> C[("PostgreSQL")]
    B -- "private network" --> D["Node.js AI worker<br/>slow LLM jobs"]
    D --> E["LLM provider"]
```

The gateway is the only service the apps talk to. The AI worker does the slow work in the background and returns validated JSON.

## 🗺️ Roadmap

| Stage | What it covers | Status |
|---|---|---|
| **Sprint 1** | Backend skill graph and adaptive diagnostic test | 🚧 In progress |

## 🧰 Tech we use

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

## 🔝 Top repository

<div align="center">
  <a href="https://github.com/LNCT-Unix/AI-Powered-Upskilling-Platform">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=LNCT-Unix&repo=AI-Powered-Upskilling-Platform&theme=transparent&title_color=6366F1&icon_color=0EA5E9&text_color=8b949e&border_color=6366F1&show_owner=true" alt="AI-Powered-Upskilling-Platform repository card" />
  </a>
</div>

> **upskill-platform** is where the gateway, AI worker, web app, mobile app and docs live. Start here.

## 📦 Repositories

| Repository | What it is |
|---|---|
| [`upskill-platform`](https://github.com/LNCT-Unix/AI-Powered-Upskilling-Platform) | The main project: gateway, AI worker, web app, mobile app and docs |
| More coming | New repositories will be listed here as the team creates them |

## 🏆 Top contributors

The wall below updates automatically from commit history of our main repository.

<a href="https://github.com/LNCT-Unix/AI-Powered-Upskilling-Platform/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LNCT-Unix/AI-Powered-Upskilling-Platform" alt="Contributors to AI-Powered-Upskilling-Platform" />
</a>

### ⭐ Core contributors



<table>
  <tr>
    <td align="center" valign="top" width="20%">
      <a href="https://github.com/dev47929">
        <img src="https://github.com/dev47929.png?size=120" width="90" alt="Dev Sharma" /><br />
        <strong>Dev Sharma</strong>
      </a>
      <br /><br />
      <sub><strong>Technical &amp; Design Lead</strong></sub>
      <br /><br />
      <sub>Architecture, Gateway Backend, Diagnostic Engine &amp; Database Design</sub>
    </td>
    <td align="center" valign="top" width="20%">
      <a href="https://github.com/mahakshri">
        <img src="https://github.com/mahakshri.png?size=120" width="90" alt="Mahak Shrivastava" /><br />
        <strong>Mahak Shrivastava</strong>
      </a>
      <br /><br />
      <sub>System Flow Design &amp; LLM Fine-Tuning</sub>
    </td>
    <td align="center" valign="top" width="20%">
      <em>Add a teammate</em>
      <br /><br />
      <sub>Name, GitHub profile &amp; area of focus</sub>
    </td>
    <td align="center" valign="top" width="20%">
      <em>Add a teammate</em>
      <br /><br />
      <sub>Name, GitHub profile &amp; area of focus</sub>
    </td>
    <td align="center" valign="top" width="20%">
      <em>Add a teammate</em>
      <br /><br />
      <sub>Name, GitHub profile &amp; area of focus</sub>
    </td>
  </tr>
</table>



## 🤝 Contributing

We welcome fixes and ideas from teammates and mentors.

1. Read the README of the repository you want to work on.
2. Create a branch from `main`: `feature/<short-name>`.
3. Keep each pull request focused on one change.
4. Ask for at least one review before merging.

Found a problem or have an idea? Open an issue in the repository it relates to.

## 📬 Get in touch

- Issues and ideas: open an issue in the relevant repository
- Email: _add a team contact address_

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=110&section=footer" alt="" width="100%" />

<sub>Team Unix · Lakshmi Narain College of Technology, Bhopal · This profile is maintained by Dev Sharma, technical and design lead</sub>

</div>
