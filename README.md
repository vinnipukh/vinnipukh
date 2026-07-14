# Hi there 👋

## 🌌 I'm Arhan 

<p align="left">
  <a href="https://vinnipukh.github.io"><img src="https://img.shields.io/badge/Portfolio-vinnipukh.github.io-0D1117?style=flat-square&logo=jekyll&logoColor=FF7B72&labelColor=1F242C&border=1" /></a>
  <a href="mailto:vinni@disroot.org"><img src="https://img.shields.io/badge/Email-vinni%40disroot.org-0D1117?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=1F242C" /></a>
  <a href="https://github.com/vinnipukh"><img src="https://img.shields.io/badge/GitHub-vinnipukh-0D1117?style=flat-square&logo=github&logoColor=C9D1D9&labelColor=1F242C" /></a>
</p>

An **Artificial Intelligence & Data Engineering** undergraduate student at Özyeğin University specializing in Aspect-Based Sentiment Analysis (ABSA), robust ETL automation pipelines, and agentic workflows.

---

### ⚡ Technical Blueprint

```mermaid
flowchart LR
    %% Definitions
    subgraph Data Extraction & Storage
        A[Retailer Websites / Scrapers] -->|Daily GitHub Actions| B[(Raw Dataset Logs)]
    end
    subgraph Processing & Imputation
        B -->|Python CLI Pipeline| C{Anomaly Filter}
        C -->|SVD / MICE Imputation| D[(TUIK-Weighted Indexes)]
    end
    subgraph Model Integration
        D -->|Feature Engineering| E[TachyonTRSA1 ABSA Dataset]
        E -->|PyTorch / GPyTorch| F[Deep Kernel Learning Model]
    end

    %% Styles for Minimalist Dark Aesthetic
    style A fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#8b949e
    style B fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#58a6ff
    style C fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#d2a8ff
    style D fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#3fb950
    style E fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#ff7b72
    style F fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#f2cc60
    
    classDef default font-family:'Courier New',monospace;
```

---

### 🛠️ Technology Stack & Armament

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white&labelColor=1F242C" />
  <!-- Data Engineering & DevOps -->
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white&labelColor=1F242C" />
  <!-- AI / ML Frameworks -->
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=1F242C" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black&labelColor=1F242C" />
</p>

---

### 📂 Featured Projects & Research

#### 1. 🧠 Aspect-Based Sentiment Analysis (ABSA) Framework
* **Description:** Developed an ABSA semi-supervised annotation framework and published a human-annotated Turkish dataset (`TachyonTRSA1`) on Hugging Face to evaluate multi-class aspects.
* **Core:** Designed custom evaluation pipelines and training log visualizations using regular expression parsers and matplotlib for diagnostic tracking.

#### 2. 📊 inflationstudymirror
* **Description:** Built a production-grade automated pipeline managing real-time price scrapers for 10+ major retail chains, run daily via GitHub Actions.
* **Core:** Developed a local Python CLI executing SVD/MICE data imputation, median-based outlier filtering, and pricing indexation weighted against official TUIK indicators.

#### 3. 🛡️ ALZHAI (TEKNOFEST Health AI App)
* **Description:** Co-developed a healthcare solution for the TEKNOFEST Artificial Intelligence in Health Competition under an agile Scrum framework.
* **Core:** Structured and normalized raw telemetry data with Pandas, while designing high-fidelity mobile wireframe flows in Balsamiq.

#### 4. 📈 Deep Kernel Learning (DKL) Optimization
* **Description:** Constructed and evaluated Gaussian Process (GP) regression models within a PyTorch and GPyTorch-backed DKL structure.
* **Core:** Implemented robust token-distribution diagnostic plots, customized loss visualizations, and numerical bounds handling for text-related optimization.

---
# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api/top-langs/?username=vinnipukh&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)


