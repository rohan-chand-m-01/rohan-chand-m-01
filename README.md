<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=39FF14&center=true&vCenter=true&width=600&lines=I+build+things+that+scale.;Java+ecosystem+architect.;Quantum+PQC+implementation+specialist.;Multi-agent.+Multi-cloud.+No+mercy." alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rohan-chand-m-01&label=SYSTEM+ACCESSES&color=39ff14&style=flat-square" alt="visitor counter" />
</p>

<p align="center">
  <code>> engineering intelligence at the intersection of AI, fintech, and IoT</code>
</p>

---

### DYNAMIC STATS GRID

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=rohan-chand-m-01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&text_color=00bfff&icon_color=39ff14" alt="GitHub Stats" /></td>
    <td><img src="https://github-readme-streak-stats.herokuapp.com/?user=rohan-chand-m-01&theme=tokyonight&hide_border=true&background=0d1117&ring=39ff14&fire=39ff14&currStreakLabel=39ff14" alt="GitHub Streak" /></td>
  </tr>
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rohan-chand-m-01&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&text_color=00bfff&hide=html,css" alt="Top Languages" /></td>
    <td><img src="https://github-profile-trophy.vercel.app/?username=rohan-chand-m-01&theme=darkhub&no-bg=true&column=6" alt="Trophy Rack" /></td>
  </tr>
</table>

---

### SNAKE CONTRIBUTION GRAPH

<p align="center">
  <img src="https://raw.githubusercontent.com/rohan-chand-m-01/rohan-chand-m-01/output/github-contribution-grid-snake-dark.svg" alt="Snake Animation" />
</p>

---

### ACTIVITY HEATMAP

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rohan-chand-m-01&theme=github-compact&bg_color=0d1117&line=00bfff&color=39ff14&hide_border=true" alt="Activity Graph" />
</p>

---

### PROJECTS — OPERATOR DOSSIER FORMAT

[CLASSIFIED — LEVEL 3]
CODENAME: AUSTERE-VAULT
MISSION: Secure distributed ledger implementation utilizing Lattice-based Post-Quantum Cryptography (PQC).
STACK: ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=39ff14) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=39ff14) ![Cryptography](https://img.shields.io/badge/PQC-0d1117?style=flat-square&color=39ff14)
STATUS: DEPLOYED
---

[CLASSIFIED — LEVEL 2]
CODENAME: NEURAL-STREAM
MISSION: High-throughput real-time IoT sensor telemetry analysis using Kafka and Java Vert.x.
STACK: ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=39ff14) ![Apache Kafka](https://img.shields.io/badge/Kafka-0d1117?style=flat-square&logo=apachekafka&logoColor=39ff14) ![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=39ff14)
STATUS: ACTIVE
---

[CLASSIFIED — LEVEL 1]
CODENAME: QUANTUM-BRIDGE
MISSION: Benchmarking tool for NIST-standardized PQC algorithms across hybrid cloud environments.
STACK: ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=39ff14) ![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=39ff14) ![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonaws&logoColor=39ff14)
STATUS: ARCHIVED
---

### ACHIEVEMENTS — WAR RECORD

```text
+----------------------------------+--------+------+
| EVENT                            | RESULT | YEAR |
+----------------------------------+--------+------+
| GLOBAL JAVA CHALLENGE            | RANK 1 | 2024 |
| QUANTUM SECURITY SYMPOSIUM       | LEAD   | 2025 |
| FINTECH SCALING INNOVATION       | FINAL  | 2023 |
+----------------------------------+--------+------+
```

---

### SKILLS MATRIX — RADAR STYLE

```text
AI/ML Systems     [##########] 95%
Backend (Java/SB) [#########-] 88%
Quantum PQC       [########--] 82%
DevOps/Infra      [#######---] 72%
Data Engineering  [######----] 60%
```

---

### GITHUB METRICS

![Commits](https://img.shields.io/badge/Commits_This_Year-582-0d1117?style=flat-square&labelColor=0d1117&color=39ff14)
![Issues](https://img.shields.io/badge/Open_Issues-14-0d1117?style=flat-square&labelColor=0d1117&color=39ff14)
![PRs](https://img.shields.io/badge/PRs_Merged-89-0d1117?style=flat-square&labelColor=0d1117&color=39ff14)
![Stars](https://img.shields.io/badge/Stars_Earned-127-0d1117?style=flat-square&labelColor=0d1117&color=39ff14)
![Followers](https://img.shields.io/badge/Followers-42-0d1117?style=flat-square&labelColor=0d1117&color=39ff14)

---

### FOOTER — SYSTEM SIGNATURE

```text
> SYSTEM: rohan.dev v2.0.26
> STATUS: online
> LAST COMMIT: [https://img.shields.io/github/last-commit/rohan-chand-m-01/rohan-chand-m-01?style=flat-square&labelColor=0d1117&color=39ff14]
> UPTIME: since 2004
> "the system doesn't sleep."
```

---

### SYSTEM CONFIGURATION: SNAKE GENERATOR

To enable the animated contribution snake, create `.github/workflows/snake.yml`:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches:
    - main

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3

      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to Output Branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
