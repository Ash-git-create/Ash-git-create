<h1 align="center">Ashwin Jayan</h1>
<h3 align="center">AI Engineer · Multi-Agent Systems · Applied ML</h3>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3600&pause=1200&color=E0AF68&center=true&vCenter=true&width=640&lines=Multi-agent+systems+built+to+be+run%2C+not+demoed;Cost+caps%2C+human+review+and+evals+from+day+one;Thesis%3A+tracing+error+cascades+in+shared+agent+memory" alt="Typing SVG" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/Location-Mannheim,%20Germany-24283b?style=flat&labelColor=24283b&color=e0af68" alt="location" />
<img src="https://img.shields.io/badge/Available-20%20September%202026-24283b?style=flat&labelColor=24283b&color=9ece6a" alt="available" />
<img src="https://img.shields.io/badge/Work%20rights-EU%20Blue%20Card%20eligible-24283b?style=flat&labelColor=24283b&color=9ece6a" alt="work rights" />
</p>

<p align="center">
<a href="https://www.linkedin.com/in/ashwin-j-ab0894214/"><img src="https://img.shields.io/badge/LinkedIn-24283b?style=for-the-badge&logo=linkedin&logoColor=7aa2f7" /></a>
<a href="mailto:ashwin.apps00@gmail.com"><img src="https://img.shields.io/badge/Email-24283b?style=for-the-badge&logo=gmail&logoColor=f7768e" /></a>
</p>

---

### About

- 🤖 I build **multi-agent systems** meant to be run rather than demoed, with cost caps, human-in-the-loop correction and evaluation from the start
- 🎓 **MSc Applied Data Science and Analytics**, SRH University Heidelberg, September 2026
- 🛠️ **Three years keeping production middleware alive at Capgemini** before moving into applied AI, 500+ servers, 300+ incidents a week, 99% uptime SLA
- 🔬 Thesis: how one extraction error spreads through a shared-memory multi-agent system, measured with an epidemiological SIR model
- 🇩🇪 Mannheim, Germany. 18-month post-study residence permit, no sponsorship needed

---

### Featured Builds

<table>
<tr>
<td width="50%" valign="top">

#### [SMMA-AI](https://github.com/Ash-git-create/SMMA-AI)
**Cascading Knowledge Contamination**

<img src="https://img.shields.io/badge/Python-24283b?style=flat-square&logo=python&logoColor=7aa2f7" /> <img src="https://img.shields.io/badge/Neo4j-24283b?style=flat-square&logo=neo4j&logoColor=9ece6a" /> <img src="https://img.shields.io/badge/Claude-24283b?style=flat-square&logo=anthropic&logoColor=e0af68" />

Master's thesis. A Neo4j graph of 50,000 facts that three LLM agents read from and write to. 45 controlled extraction errors across 3 types, traced over 10-step runs on 4 seeds. Finding: memory can be badly contaminated while HotpotQA exact match and FEVER veracity stay flat, so task scores hide the damage.

</td>
<td width="50%" valign="top">

#### [InvoiceGuard](https://github.com/Ash-git-create/invoiceguard)
**Multi-Agent Invoice Verification**

<img src="https://img.shields.io/badge/Python-24283b?style=flat-square&logo=python&logoColor=7aa2f7" /> <img src="https://img.shields.io/badge/OpenAI-24283b?style=flat-square&logo=openai&logoColor=9ece6a" /> <img src="https://img.shields.io/badge/Flask-24283b?style=flat-square&logo=flask&logoColor=c0caf5" /> <img src="https://img.shields.io/badge/React-24283b?style=flat-square&logo=react&logoColor=7dcfff" />

Eight agents read invoices in seven formats including OCR, run three checks in parallel, then a decision agent rules. gpt-4o-mini for structured calls, gpt-4o only where conflicting flags need reconciling. Per-agent token accounting behind a hard spend cap. Audit log made immutable with database triggers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Compass](https://github.com/Ash-git-create/Compass)
**Demand-Planning Copilot**

<img src="https://img.shields.io/badge/Python-24283b?style=flat-square&logo=python&logoColor=7aa2f7" /> <img src="https://img.shields.io/badge/Claude-24283b?style=flat-square&logo=anthropic&logoColor=e0af68" /> <img src="https://img.shields.io/badge/DuckDB-24283b?style=flat-square&logo=duckdb&logoColor=e0af68" /> <img src="https://img.shields.io/badge/Streamlit-24283b?style=flat-square&logo=streamlit&logoColor=f7768e" />

Five deterministic signal agents read order books, stock cover, campaigns and financials, then one Claude call weighs the evidence into a proposed override with a written rationale. Built in three days. Across 23 planning cycles of anonymised industrial demand data (68,126 item-months), planner overrides cut weighted error from 19.2% to 15.0%.

</td>
<td width="50%" valign="top">

#### [Interpretable Demand Forecasting](https://github.com/Ash-git-create/interpretable-demand-forecasting-in-retail)
**Promotion-Aware Retail Forecasting**

<img src="https://img.shields.io/badge/Python-24283b?style=flat-square&logo=python&logoColor=7aa2f7" /> <img src="https://img.shields.io/badge/LightGBM-24283b?style=flat-square&logo=lightgbm&logoColor=9ece6a" /> <img src="https://img.shields.io/badge/SHAP-24283b?style=flat-square&logo=python&logoColor=bb9af7" />

LightGBM against a seasonal-naive baseline on M5, scored inside a 365-day promotion-focused window because the standard 28-day holdout held too few promotion rows to be stable. On 32,378 promotion rows, MAE 0.9268 against the baseline's 1.4284. Exact TreeSHAP for regime-level attribution.

</td>
</tr>
</table>

<p align="center">
<a href="https://github.com/Ash-git-create/cyber-risk-pipeline"><b>Cyber Risk Pipeline</b></a> · NVD, CISA KEV and OTX feeds scored in BigQuery with dbt, 597 successful hourly builds &nbsp;&nbsp;|&nbsp;&nbsp;
<a href="https://github.com/Ash-git-create/LLM_Audit_Workbench"><b>LLM Audit Workbench</b></a> · prompt versioning, evaluation and a review queue for flagged outputs
</p>

---

### Tech Stack

**AI and Agents**
<p>
<img src="https://img.shields.io/badge/Claude%20API-24283b?style=for-the-badge&logo=anthropic&logoColor=e0af68" />
<img src="https://img.shields.io/badge/OpenAI%20API-24283b?style=for-the-badge&logo=openai&logoColor=9ece6a" />
<img src="https://img.shields.io/badge/Neo4j-24283b?style=for-the-badge&logo=neo4j&logoColor=9ece6a" />
<img src="https://img.shields.io/badge/Mistral-24283b?style=for-the-badge&logo=mistralai&logoColor=ff9e64" />
<img src="https://img.shields.io/badge/Groq-24283b?style=for-the-badge&logo=groq&logoColor=f7768e" />
<img src="https://img.shields.io/badge/Hugging%20Face-24283b?style=for-the-badge&logo=huggingface&logoColor=e0af68" />
</p>

**Languages and Data**
<p>
<img src="https://img.shields.io/badge/Python-24283b?style=for-the-badge&logo=python&logoColor=7aa2f7" />
<img src="https://img.shields.io/badge/SQL-24283b?style=for-the-badge&logo=postgresql&logoColor=7dcfff" />
<img src="https://img.shields.io/badge/DuckDB-24283b?style=for-the-badge&logo=duckdb&logoColor=e0af68" />
<img src="https://img.shields.io/badge/MySQL-24283b?style=for-the-badge&logo=mysql&logoColor=7dcfff" />
<img src="https://img.shields.io/badge/SQLite-24283b?style=for-the-badge&logo=sqlite&logoColor=7dcfff" />
<img src="https://img.shields.io/badge/BigQuery-24283b?style=for-the-badge&logo=googlebigquery&logoColor=7aa2f7" />
<img src="https://img.shields.io/badge/dbt-24283b?style=for-the-badge&logo=dbt&logoColor=ff9e64" />
<img src="https://img.shields.io/badge/LightGBM-24283b?style=for-the-badge&logo=lightgbm&logoColor=9ece6a" />
</p>

**Platform and Tooling**
<p>
<img src="https://img.shields.io/badge/Google%20Cloud-24283b?style=for-the-badge&logo=googlecloud&logoColor=7aa2f7" />
<img src="https://img.shields.io/badge/Docker-24283b?style=for-the-badge&logo=docker&logoColor=7aa2f7" />
<img src="https://img.shields.io/badge/GitHub%20Actions-24283b?style=for-the-badge&logo=githubactions&logoColor=7aa2f7" />
<img src="https://img.shields.io/badge/pytest-24283b?style=for-the-badge&logo=pytest&logoColor=9ece6a" />
<img src="https://img.shields.io/badge/Streamlit-24283b?style=for-the-badge&logo=streamlit&logoColor=f7768e" />
<img src="https://img.shields.io/badge/Flask-24283b?style=for-the-badge&logo=flask&logoColor=c0caf5" />
<img src="https://img.shields.io/badge/Pydantic-24283b?style=for-the-badge&logo=pydantic&logoColor=f7768e" />
</p>

---

### Certifications

- Building LLM Applications with Prompt Engineering — NVIDIA, November 2025
- Fundamentals of Deep Learning — NVIDIA, October 2025

---

### Activity

<p align="center">
<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Ash-git-create&bg_color=00000000&color=e0af68&line=7aa2f7&point=c0caf5&area=true&hide_border=true" alt="activity graph" />
</p>

<p align="center"><i>Ship the agent, cap the spend, measure what it actually changed.</i></p>
