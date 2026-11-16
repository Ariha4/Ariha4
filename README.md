# Ariha Shah

**Math-CS + Cognitive Science (ML & Neural Computation) @ UC San Diego · ML, neurotech, and backend systems · Digital Technology AWS Intern @ United Airlines**

I build data pipelines, ML systems, and the tooling around them, usually starting from a real workflow that someone was doing by hand. I'm finishing dual B.S. degrees at UC San Diego in Mathematics-Computer Science and Cognitive Science with a Specialization in Machine Learning and Neural Computation, graduating March 2027.

Most of my work sits where software meets the brain: signal processing for lab audio, EEG decoding, and tracking the brain-computer interface industry. I've been fascinated by BCIs for about five years, and building for that field is where I want to spend my career.

## What I work on

- **Applied AI:** retrieval-augmented generation, LLM evaluation benchmarks, LoRA fine-tuning and quantization for on-device inference
- **Signal processing and neural data:** audio event detection, EEG preprocessing (MNE), cross-subject transfer learning
- **Backend and systems:** raw TCP/UDP networking, mutual TLS, Python ETL pipelines, Postgres with row-level security
- **Engineering practice:** pytest suites, GitHub Actions CI, Docker, Prometheus/Grafana observability, test-first security fixes

## Highlights

- **United Airlines (Digital Technology AWS Intern, 2026):** Built ATLAS end to end, an agentic RAG platform that turns project documents and meeting transcripts into structured requirements, with an 18-question evaluation benchmark (83%). Presented the prototype to executive stakeholders. Also QA'd the HELIOS held-seat API by cross-checking SQL results against API requests. *(Proprietary, not on GitHub.)*
- **United Airlines (Data Analyst Intern, 2025):** Built a Power BI dashboard and walked a director through it; led the team's daily standup.
- **Neural Crossroads Research Lab:** Built and open-sourced an ultrasonic vocalization detection pipeline that replaced fully manual review of hours-long recordings. Used by 5 lab members to rate 25 sessions; now supports live streaming audio.
- **Moores Cancer Center:** Wrote a Python ETL pipeline reconciling REDCap specimen records against FreezerWorks storage exports for the biobank.
- **UC San Diego:** Instructional Apprentice for Python courses.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [LANCast](https://github.com/Ariha4/lancast) | LAN peer discovery and file transfer on raw sockets, with hand-rolled framing, mutual TLS, per-peer permissions, and a written threat model | Python, TCP/UDP, TLS 1.3, pytest, Docker, CI |
| [BCI Industry Intelligence](https://github.com/Ariha4/bci-industry-intelligence) | Market-intelligence dashboard for the BCI space, refreshed weekly from the ClinicalTrials.gov API | Python, React, TypeScript, GitHub Actions, Docker |
| [USV Vocalization Pipeline](https://github.com/Ariha4/usv-vocalization-pipeline) | Detects rodent ultrasonic vocalizations and aligns behavioral events to the audio timeline | Python, SciPy, pytest, CI |
| [edge-trial-extractor](https://github.com/Ariha4/edge-trial-extractor) | LoRA fine-tune of Qwen2.5-0.5B to extract structured facts from neurotech trials, quantized to 8- and 4-bit and benchmarked on a laptop CPU | PyTorch, LoRA, llama.cpp |
| [Daily Brain Game](https://github.com/Ariha4/daily-brain-game) | One shared brain challenge a day with streaks and a live friends leaderboard; game rules enforced in the database | SwiftUI, Supabase, Postgres RLS, Cloudflare Workers |
| [Coastal Shield](https://github.com/Ariha4/coastal-shield) | Harmful algal bloom risk forecasting for the California coast (team project; I built the modeling and dashboard layers and the observability stack) | XGBoost, SHAP, Streamlit, Prometheus, Grafana |
| [Cross-Subject Neural Decoding](https://github.com/Ariha4/COGS189_TransferLearning) | EEG transfer learning (team project; I ran the EEGNet leave-one-subject-out baseline, built the MNE preprocessing, and implemented Riemannian Alignment) | PyTorch, MNE |

## Tools

Python · Java · C++ · TypeScript · SQL · PyTorch · scikit-learn · XGBoost · React · SwiftUI · PostgreSQL · Supabase · Docker · GitHub Actions · Prometheus · Grafana · Power BI · Azure DevOps · Linux

## Contact

[LinkedIn](https://www.linkedin.com/in/ariha-shah04)
