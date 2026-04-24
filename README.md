<div align="center">

# Yasser Fuentes

**Head of ML Modeling @ Tritemius** · **PhD in Physics** · **Madrid**

[![Blog](https://img.shields.io/badge/Blog-yassfuentes.es-FF5D01?style=flat&logo=astro&logoColor=white)](https://yassfuentes.es)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YassFuentes)
[![Newsletter](https://img.shields.io/badge/Newsletter-Buttondown-0069FF?style=flat&logoColor=white)](https://buttondown.com/yassfuentes)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-3541-7730)
[![Scholar](https://img.shields.io/badge/Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.es/citations?user=nPHiLFUAAAAJ)

*Construir para entender.*

</div>

---

Physicist turned ML engineer. Currently leading ML modeling at **Tritemius** — fine-tuned transformers for Solidity smart-contract vulnerability detection, blockchain fraud analysis, and mempool monitoring.

Before: co-founded [Translucent Datalab](https://translucentdatalab.com), an IE University spin-off processing 4M+ pages/month to map illegal online pharma markets for Fortune 500 pharma and US regulators. And before that, years firing femtosecond lasers at materials at CSIC — 12 peer-reviewed papers, ~900 citations, h-index 10.

I also [blog](https://yassfuentes.es), write poetry, play flamenco badly, and go birdwatching.

---

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
</p>

**Currently exploring:** RAG architectures · LangChain · k3s · OpenTofu · Ansible · Chezmoi · Proxmox

---

### Featured open source

| Project | What it is |
|---------|------------|
| [**obsidian-at-people**](https://github.com/backmind/obsidian-at-people) | Fuzzy `@` mentions for Obsidian. **Official community plugin** — my PR led the original author to archive his repo and endorse this fork. 8.3k+ downloads. |
| [**tutorials**](https://github.com/backmind/tutorials) | Four-layer homelab documentation series (see below). |
| [**prismfly**](https://github.com/backmind/prismfly) | Firefly III analytics: personal inflation index, lifestyle elasticity, sustainability waterfall. 10 years of hand-recorded data → interactive dashboard + LLM-ready report. |

---

### Homelab Documentation Series

Four-layer architecture for personal infrastructure → [**backmind/tutorials**](https://github.com/backmind/tutorials)

```mermaid
flowchart TB
    L3(["✅ <b>HDA-TERM</b><br/>Workstation · Windows + PowerShell"]):::done
    subgraph hardware["&nbsp;Home lab · 10Gb LAN&nbsp;"]
        direction LR
        L1(["✅ <b>HDA-NAS</b><br/>Synology DS920+ · SHR-2 · 32 TB"]):::done
        L2(["✅ <b>HDA-SERV</b><br/>Debian 12 · i7 + RTX 3080<br/>ZFS · Docker rootless · Pi-Hole"]):::done
        L4(["🚧 <b>HDA-DOCKER</b><br/>Microservices"]):::wip
        L2 --- L4
        L2 -.->|daily backup| L1
    end
    L3 -.->|SSH / Samba| hardware
    classDef done fill:#ddf4e4,stroke:#2ea043,color:#1a7f37
    classDef wip fill:#fff4d6,stroke:#d29922,color:#9e6a03
    click L1 "https://github.com/backmind/tutorials/blob/main/hda-nas.md"
    click L2 "https://github.com/backmind/tutorials/blob/main/hda-serv.md"
    click L3 "https://github.com/backmind/tutorials/blob/main/hda-term.md"
```

| Guide | Covers |
|-------|--------|
| **[HDA-NAS](https://github.com/backmind/tutorials/blob/main/hda-nas.md)** | Synology DS920+ setup, disk selection, RAID/SHR-2, hardware testing |
| **[HDA-SERV](https://github.com/backmind/tutorials/blob/main/hda-serv.md)** | Debian 12 headless: SSH hardening, ZFS, Samba, Docker rootless, CUDA, Pi-Hole |
| **[HDA-TERM](https://github.com/backmind/tutorials/blob/main/hda-term.md)** | Windows Terminal + PowerShell 7: Oh My Posh, fzf, z, UV, productivity aliases |
| **HDA-DOCKER** | Microservices stack *(in progress)* |

---

### Research & academic

| Project | Description |
|---------|-------------|
| [autoRICEWQ](https://github.com/backmind/autoRICEWQ) | Batch handler for RICEWQ hydric simulations — scales from dozens to tens of thousands of runs. **Used in 2 peer-reviewed papers.** |
| [EspeciesInvasoras-MITECO](https://github.com/backmind/EspeciesInvasoras-MITECO) | Web scraping + PDF/GIS processing of Spain's MITECO invasive species registry |

---

### Personal projects

<details>
<summary><b>📰 Feeds & scrapers</b></summary>
<br>

| Project | Description |
|---------|-------------|
| [Bird-of-the-day](https://github.com/backmind/Bird-of-the-day) | Daily bird species RSS feed and static site, self-hostable as a microservice → [live instance](https://birds.yassfuentes.es) |
| [Palabra-del-dia](https://github.com/backmind/Palabra-del-dia) | Ad-free Atom feed of daily Spanish etymology from elcastellano.org |
| [anait-games-calendar](https://github.com/backmind/anait-games-calendar) | iCal feed of weekly video game releases from AnaitGames |
| [EOM-Scraper](https://github.com/backmind/EOM-Scraper) | El Orden Mundial → Readwise Reader |

</details>

<details>
<summary><b>💻 Developer tools</b></summary>
<br>

| Project | Description |
|---------|-------------|
| [ClaudeUsage](https://github.com/backmind/ClaudeUsage) | PowerShell module to query Claude Code usage limits from the terminal |
| [PSAliasFinder](https://github.com/backmind/PSAliasFinder) | PowerShell alias discovery — suggests existing aliases when you type the verbose form. Inspired by oh-my-zsh's `alias-finder` |
| [termux-widget-git-obsidian](https://github.com/backmind/termux-widget-git-obsidian) | Termux shortcuts for git-syncing your Obsidian vault from Android |
| [domestika-downloader](https://github.com/backmind/domestika-downloader) | Fork with concurrency + H.265 transcode. PR submitted upstream |

</details>

<details>
<summary><b>💰 Personal finance</b></summary>
<br>

| Project | Description |
|---------|-------------|
| [MyWallet-to-Fireflyiii](https://github.com/backmind/MyWallet-to-Fireflyiii) | ETL from the (deceased) MyWallet Android app to Firefly III |
| [SimuladorHipoteca](https://github.com/backmind/SimuladorHipoteca) | Mortgage simulator for amortization strategy analysis |

</details>

---

<div align="center">
  <img src="github-metrics.svg" alt="Metrics" />
</div>
