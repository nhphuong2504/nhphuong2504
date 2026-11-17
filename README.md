<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Phuong%20Nguyen&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Data%20Science%20%C2%B7%20Data%20Engineering%20%C2%B7%20Applied%20AI&descSize=18&descAlignY=58" width="100%" alt="Phuong Nguyen" />

🎓 **M.S. Computer Engineering** @ Iowa State University (expected May 2027)<br/>
**B.S. Computer Science**, top 2% of graduating class · 1st place, Software Design competition

I build ML systems and data pipelines that hold up in production, with reliable data and honest evaluation.

<a href="https://www.linkedin.com/in/nhphuong2504"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:nhphuong@iastate.edu"><img src="https://img.shields.io/badge/Email-C8102E?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://tournova.app"><img src="https://img.shields.io/badge/Tournova-2c5364?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Tournova" /></a>

</div>

<br/>

## 💼 Experience

<table>
<tr>
<td width="50%" valign="top">

### 🚜 Data Scientist Intern · Tractor Zoom
<sub>May 2026 – Aug 2026 · West Des Moines, IA</sub>

- Built a cost-sensitive text-classification pipeline, **still in production**, that raised automated listing decisions from **9.5% → 80.5%** (~76K listings/month, est. **$36K/year** saved).
- Automated training, evaluation and champion–challenger promotion with MLflow, Databricks and GitHub Actions; calibrated thresholds auto-reject at **99.7% precision**.
- Raised 15-class equipment-schema accuracy from **78.7% → 91.7%** by combining multi-image predictions (DINOv3, ViT) with text.

</td>
<td width="50%" valign="top">

### ☀️ Research Assistant · Iowa State University
<sub>Jun 2025 – Present · Ames, IA</sub>

- Found an **11% measurement bias** in a DOE-funded agrivoltaics experiment; a treatment-blind filter cut residual bias to **0.6%** and reversed 3 crop-effect conclusions before publication.
- Benchmarked anomaly detectors on synthetic clipping; the chosen detector has run unchanged for 8 months under 200+ regression tests.
- Built the idempotent ELT pipeline behind quarterly DOE and Alliant Energy reporting (see Solar Telemetry Pipeline below).

</td>
</tr>
</table>

<br/>

## 🚀 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 📉 [Churn Targeting & LLM Agent](https://github.com/nhphuong2504/AI-assistant-ver-2)

Budget-constrained customer targeting on 392K transactions, served through FastAPI and a conversational agent.

- At a 20% contact budget, reached **54%** of revenue from later-churned customers vs. 35% for spend ranking (**+19 pp**).
- 18 leakage-free features, time-based validation: **0.83 AUC**.
- 8-tool LangGraph agent with read-only text-to-SQL scored **92.5%** on a 40-question benchmark.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**[Watch the demo →](https://youtu.be/t083cHw5GV4)**

</td>
<td width="50%" valign="top">

### ⚡ [Solar Telemetry Pipeline](https://github.com/nhphuong2504/solar-telemetry-pipeline)

From monthly inverter CSVs to traceable power records and energy estimates, with explicit data coverage and source lineage.

- Processes **19.25 million input-power records** across 19 monthly scopes.
- All 28.9M source cells matched on an independent re-check.
- Reruns of unchanged months take **24s instead of 394s**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🏸 [Tournova](https://github.com/nhphuong2504/shuttle-scheduler)

A badminton tournament operations app that brings registration, draws, court scheduling and live scoring into one workflow, with dedicated workflows for organisers, moderators and participants, backed by database access controls and unit, integration and browser tests.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TanStack](https://img.shields.io/badge/TanStack_Start-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
&nbsp; **[Visit Tournova →](https://tournova.app)**

</td>
</tr>
</table>

<br/>

## 🛠️ Toolbox

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,sklearn,pytorch,tensorflow,postgres,aws,docker,terraform,githubactions,fastapi,ts,react,supabase,cloudflare&perline=14" alt="Tech stack" />
</p>

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangChain%20%2F%20LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2C5364?style=flat-square)
![Causal inference](https://img.shields.io/badge/Causal_inference-2C5364?style=flat-square)
![Survival analysis](https://img.shields.io/badge/Survival_analysis-2C5364?style=flat-square)

<br/>

## 💡 What I care about

Reliable data, clear evaluation, and systems that remain useful beyond a notebook. My work connects applied ML, data engineering and practical software development.

**Away from the keyboard:** 🏸 badminton · ⚽ Arsenal · 🍜 sharing Vietnamese food and culture.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt="" />
