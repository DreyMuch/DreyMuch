<h1 align="center">Spiwe Audrey Muchemwa</h1>

<p align="center">
  <strong>AI Engineer · Speech &amp; Language AI for African Languages · ML Systems &amp; MLOps</strong>
</p>

<p align="center">
  Teaching machines to listen in our languages, and making sure they keep working once they ship.
</p>

<p align="center">
  <a href="https://dreymuchgithubio.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/spiwe-audrey-muchemwa/">LinkedIn</a> ·
  <a href="mailto:audrey.spiwe@gmail.com">Email</a> ·
  <a href="https://github.com/DreyMuch/rubatsiro">Flagship project</a>
</p>

---

## What I do

I'm an AI engineer for Africa. With the Languages Lab team I work on **Shona and Ndebele speech technology**: text-to-speech voices for IVR, speech recognition, and the evaluation harness that decides whether a new model is good enough to ship. We're now sourcing data for Igbo, Twi and French.

I didn't come to AI straight from a notebook. I started as a software developer at Telecel, then spent five years at Ecocash: leading service performance analytics for platforms used by millions of people, then working as a DevOps engineer across Ecocash, Sasai, Ecosure and Kashagi. So I care about what happens around a model as much as the model itself.

- Speech AI for low-resource African languages (TTS, STT, code-switched text)
- Model evaluation that people can trust: frozen test sets, error rates, human listening tests
- Machine learning for fintech and insurtech: churn, policy lapse, credit scoring, forecasting, anomaly detection
- LLM applications: RAG, prompt engineering, agents, fine-tuning
- MLOps and platforms: pipelines, model registries, CI/CD, monitoring, cloud

## AI architecture: idea to production

A model is the last link in a long chain. I've worked on every link, and I design systems with all of them in mind:

```text
  Build         web platforms, mobile apps and APIs
    │
  Ship          CI/CD, infrastructure as code, zero-downtime releases
    │
  Run           monitoring, incident response, root-cause analysis (ITIL)
    │
  Data          ETL pipelines, analytics tables, Airflow
    │
  Learn         classical ML  →  deep learning  →  LLMs
    │
  Evaluate      held-out sets, slices by language, confidence thresholds
    │
  Improve       model registry, drift checks, human review, retrain
```

How I work through that chain:

- **Measure before believing.** Every model gets scored on data it has never seen, broken down by the slices that matter (for speech and text that means by language), and a person makes the final call.
- **Ship the reliably good model, not the occasionally great one.** In [rubatsiro](https://github.com/DreyMuch/rubatsiro), the neural model wins on average but its worst run on Linux falls below the baseline, so production serves the baseline.
- **Keep rules where rules belong.** Priority, safety checks and escalation sit beside the model, where they're easy to read and change.
- **If it can't be monitored, rolled back and explained, it isn't finished.**

## Featured repositories

| Repository | What it shows |
| --- | --- |
| [rubatsiro](https://github.com/DreyMuch/rubatsiro) | Helpdesk ticket triage in Shona, English and the mix of both: FastAPI app, Postgres and an analytics pipeline, a baseline vs a PyTorch model, LLM-drafted replies, Docker and CI/CD |
| [mobile-money-churn](https://github.com/DreyMuch/mobile-money-churn) | Predicting which wallet customers will go quiet, scored by how many a retention team can actually reach |
| [transaction-forecasting](https://github.com/DreyMuch/transaction-forecasting) | Four-week forecasts that know about payday, Zimbabwean public holidays and tariff changes, with a rolling backtest |
| [server-metrics-anomalies](https://github.com/DreyMuch/server-metrics-anomalies) | AIOps incident detection, comparing static thresholds, seasonal z-scores and isolation forests |

The data in these repos is simulated, since customer data can't be published, but it's built to behave like the real thing. My speech work at Econet AI is internal.

## Technologies

<p>
  <img alt="Speech AI" src="https://img.shields.io/badge/Speech_AI-5B2A5E?style=flat-square">
  <img alt="NLP" src="https://img.shields.io/badge/NLP-5B2A5E?style=flat-square">
  <img alt="LLMs and RAG" src="https://img.shields.io/badge/LLMs_%26_RAG-5B2A5E?style=flat-square">
  <img alt="MLOps" src="https://img.shields.io/badge/MLOps-C8862A?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
  <img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white">
  <img alt="R" src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="Airflow" src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white">
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

## Certifications and learning

- **Certified Artificial Intelligence Engineer (CAIE™)**, USAII, 2026
- **ITIL® v5 Foundation**, PeopleCert, 2026 · **Certified Payment Security Compliance Manager**, Ampcus Cyber, 2025
- **MSc Big Data Analytics** (Merit), Chinhoyi University of Technology · **BSc (Hons) Information Systems**, Midlands State University
- Currently working through Ed Donner's AI Engineer Core Track: LLM engineering, RAG, QLoRA and agents

## Beyond the code

I run AI literacy sessions through Eco AI for teachers, church leaders and university students. Off the clock you'll find me on a basketball court or over a chess board.

---

<p align="center">
  Harare, Zimbabwe · Open to conversations about African-language AI, ML systems and MLOps
</p>
