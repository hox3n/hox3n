<!-- Replace YOUR_USERNAME with your GitHub username (Find & Replace All) -->
<!-- The Repositories table below is filled in automatically by the GitHub Action -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=180&section=header&text=ENKLID%20HOXHA&fontSize=52&fontColor=58A6FF&fontAlignY=40&desc=AI%20%2F%20ML%20Platform%20Engineer&descAlignY=60&descSize=18&descColor=8B949E&animation=fadeIn" alt="header" width="100%" />

<p>
  <img src="https://img.shields.io/badge/00_STATUS-ONLINE-39FF14?style=for-the-badge&labelColor=0d1117" alt="status" />
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=0d1117&style=for-the-badge&label=VISITORS" alt="Profile views" />
  <img src="https://img.shields.io/badge/BASE-TIRANA_%F0%9F%87%A6%F0%9F%87%B1-0d1117?style=for-the-badge" alt="Location" />
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=1&repeat=false&color=8B949E&center=true&vCenter=true&width=600&lines=root%40enklid%3A~%24+whoami" alt="terminal line" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### ABOUT

I build the infrastructure that gets machine learning out of notebooks and into production. Currently designing an **ML productization platform for a clinical remote cardiac-monitoring product** — turning MLflow-registered models into independent, tested, auditable inference microservices on GKE.

```yaml
engineer:
  role: AI / ML Platform Engineer
  based_in: Tirana, Albania
  education: BSc Computer Science — American College of Thessaloniki (3.9 GPA, High Honors)
  research: Co-founder @ KAG AI — CNNs in medicine & architecture, now LLM research
  languages: [Albanian (native), English (C2), German (A2)]
  focus: [MLOps, model-serving, RAG systems, LLM agents, data pipelines]
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### WHAT I'VE SHIPPED

<table>
<tr><td width="60px" align="center">🏗️</td><td><b>Model Productization Platform</b> — originated the architecture of a 14k-LOC Python SDK that converts MLflow models into FastAPI inference microservices, gated by a 4-step productization check (version resolve, metadata, dependency check, smoke test) with adapters for scikit-learn, XGBoost, PyTorch, TensorFlow, ONNX, and Transformers.</td></tr>
<tr><td align="center">⚡</td><td><b>CQRS Inference Runtime</b> — single, batch, and multi-model inference with a model cache, prediction audit log, and an auto-productization reconciliation loop.</td></tr>
<tr><td align="center">🔄</td><td><b>Data Integration Services</b> — CQRS transformation service (FastAPI + DataKit) with PostgreSQL → MinIO and MinIO → MinIO ETL, SQL-like Parquet filtering via DuckDB, Redis-backed async jobs, and Dapr data lineage.</td></tr>
<tr><td align="center">🫀</td><td><b>Privacy-First ECG Extractor</b> — pulls clinical device data with zero PII by design, on a clean/hexagonal architecture.</td></tr>
<tr><td align="center">📄</td><td><b>Document Intelligence & RAG</b> — OCR pipelines (PP-OCR / Tesseract) fused with LLM analysis; retrieval over enterprise documents via Milvus and Elasticsearch.</td></tr>
<tr><td align="center">🤖</td><td><b>AI Agents & Automation</b> — n8n workflows and RetellAI voice agents wired into Slack, Notion, and ClickUp via native connectors and REST APIs.</td></tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### TECH STACK

**Languages & ML**

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,js,r,pytorch,tensorflow,sklearn&perline=12" alt="Languages and ML" />
</p>

**Backend, Data & Infrastructure**

<p align="left">
  <img src="https://skillicons.dev/icons?i=fastapi,postgres,redis,elasticsearch,docker,kubernetes,gcp,git,linux&perline=12" alt="Backend and infrastructure" />
</p>

**MLOps & AI Tooling**

<p align="left">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/FastMCP-5A67D8?style=for-the-badge&logoColor=white" alt="FastMCP" />
  <img src="https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white" alt="Milvus" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO" />
  <img src="https://img.shields.io/badge/Dapr-0D2192?style=for-the-badge&logo=dapr&logoColor=white" alt="Dapr" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Airbyte-615EFF?style=for-the-badge&logo=airbyte&logoColor=white" alt="Airbyte" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white" alt="LangSmith" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### REPOSITORIES

<!-- REPOS-START -->
<sub>⏳ populated automatically by the GitHub Action below on first run</sub>
<!-- REPOS-END -->

<sub>💡 This table is rewritten automatically by <code>.github/workflows/update-readme.yml</code>, which pulls every public, non-fork repo from the GitHub API (newest activity first) — nothing to type in by hand, refreshed every 5 hours.</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### LIVE ACTIVITY

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg" />
  <img alt="a snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

</div>

<sub>💡 A snake game generated from your real contribution graph — built by the second workflow below (<code>generate-snake.yml</code>) and refreshed every 5 hours.</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### GITHUB STATS

<div align="center">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&icon_color=58A6FF&title_color=58A6FF" alt="GitHub stats" />
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true&langs_count=10&title_color=58A6FF" alt="Top languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=github-dark-blue&hide_border=true&ring=58A6FF&fire=58A6FF" alt="GitHub streak" />
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### TROPHY CASE

<div align="center">
  <img src="https://github-profile-trophy-liard-delta.vercel.app/?username=YOUR_USERNAME&theme=darkhub&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" alt="GitHub trophies" />
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

### RESEARCH & HIGHLIGHTS

- 🎓 **Thesis:** *Classification of Architectural Styles in Images with Historical and Geographical Attribution* — a computer vision project ([code](https://github.com/YOUR_USERNAME/THESIS_REPO)).
- 🧪 **KAG AI:** co-founded an AI research group spanning Kosovo, Albania, and Greece; authored articles on CNNs in medicine and architectural design, currently researching LLMs.
- 👥 Former core member of the **Google Developers Club**, American College of Thessaloniki.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:58A6FF,100:0d1117&height=3&width=100%" width="100%" />

<div align="center">

### CONNECT

<a href="https://linkedin.com/in/enklid-hoxha"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:hox.enklid@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="KAG_AI_LINK"><img src="https://img.shields.io/badge/KAG_AI-58A6FF?style=for-the-badge&logo=googlescholar&logoColor=white" alt="KAG AI" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer" alt="footer" width="100%" />

</div>
