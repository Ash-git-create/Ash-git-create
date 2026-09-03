<div align="center">

# Ashwin Jayan

### AI Engineer - Multi-Agent Systems and Applied ML

📍 Mannheim, Germany &nbsp;·&nbsp; 🎓 MSc Applied Data Science and Analytics, SRH Heidelberg (September 2026)

🟢 Available from 20 September 2026. Non-EU national on an 18-month post-study residence permit, eligible for an EU Blue Card.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwin-j-ab0894214/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ashwin.apps00@gmail.com)

</div>

---

### About

I spent three years keeping production middleware alive at Capgemini before moving into applied AI. Now I build multi-agent systems meant to be run rather than demoed, with cost caps, human-in-the-loop correction and evaluation built in from the start. My master's thesis traces how a single extraction error spreads through a shared-memory multi-agent system, adapting epidemiological SIR models to measure how fast bad facts move through a knowledge graph.

### Featured Builds

<table>
<tr>
<td width="50%" valign="top">

**[SMMA-AI](https://github.com/Ash-git-create/SMMA-AI)** - Cascading Knowledge Contamination
`Python` `Neo4j` `Mistral Nemo 12B` `Llama 3.1 8B` `Claude`

Master's thesis, submitting September 2026. A Neo4j graph of 50,000 facts that three LLM agents read from and write to. 45 controlled extraction errors across 3 error types, traced over 10-step runs on 4 random seeds. Finding: memory can be badly contaminated while HotpotQA exact match and FEVER veracity stay flat, so task scores hide the damage.

</td>
<td width="50%" valign="top">

**[InvoiceGuard](https://github.com/Ash-git-create/invoicegaurd)** - Multi-Agent Invoice Verification
`Python` `OpenAI API` `Flask` `SQLite` `React`

Eight agents read invoices in seven formats including OCR, then run service, anomaly and vendor-pattern checks in parallel before a decision agent rules. gpt-4o-mini for the structured calls, gpt-4o only where conflicting flags need reconciling. Token use logged per agent behind a cumulative hard stop, holding a typical invoice to 0.003 to 0.008 dollars. Audit log made immutable with database triggers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Compass](https://github.com/Ash-git-create/Compass)** - Demand-Planning Copilot
`Python` `Claude API` `DuckDB` `Streamlit` `Plotly`

Five deterministic signal agents read order books, stock cover, campaigns and financials, then one Claude call per decision weighs the evidence into a proposed override with a written rationale. Built in three days for a hackathon. Across 23 planning cycles of anonymised industrial demand data (68,126 item-months), planner overrides cut weighted error from 19.2% to 15.0%.

</td>
<td width="50%" valign="top">

**[Interpretable Demand Forecasting](https://github.com/Ash-git-create/interpretable-demand-forecasting-in-retail)** - Promotion-Aware Retail Forecasting
`Python` `LightGBM` `SHAP` `M5`

LightGBM against a seasonal-naive baseline on M5, scored inside a 365-day promotion-focused window because the standard 28-day holdout held too few promotion rows to be stable. On 32,378 promotion rows, MAE 0.9268 against the baseline's 1.4284. Exact TreeSHAP for regime-level attribution.

</td>
</tr>
</table>

Also: **[Cyber Risk Pipeline](https://github.com/Ash-git-create/cyber-risk-pipeline)**, NVD, CISA KEV and AlienVault OTX feeds scored in BigQuery with dbt, which ran hourly on GitHub Actions for 597 successful builds. **[LLM Audit Workbench](https://github.com/Ash-git-create/LLM_Audit_Workbench)**, a local harness for versioning prompts, scoring outputs and reviewing what gets flagged.

### Stack

**AI and agents** &nbsp; `Claude API` `OpenAI API` `Multi-agent pipelines` `RAG` `Neo4j knowledge graphs` `Vector search` `Prompt engineering` `Token budgeting and cost caps` `Human-in-the-loop review`

**Data** &nbsp; `Python` `SQL` `DuckDB` `MySQL` `SQLite` `Neo4j` `dbt` `BigQuery` `GCP` `LightGBM` `SHAP`

**Engineering** &nbsp; `Git` `GitHub Actions` `pytest` `Docker` `Streamlit` `Flask` `Pydantic`
