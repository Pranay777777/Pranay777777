# Pranay Yadagiri

**AI & Data Engineer — I build LLM systems and the data platforms that feed them.**

Computer Science graduate specialising in cyber security, currently a Data Engineer Trainee at Insight Enterprises working with Microsoft Fabric, Azure Data Factory and PySpark.

I'm drawn to the parts of a system that only show up in production: schema drift breaking a pipeline at 3am, reruns that quietly duplicate rows, LLM output nobody can trace back to a source, credentials that reach a public repo. Most of what I build is an attempt to make one of those failure modes impossible rather than unlikely.

---

### Flagship projects

**[agentic-pipeline-copilot](https://github.com/Pranay777777/agentic-pipeline-copilot)** — An English spec in; a PySpark notebook out that has been checked against the lakehouse's standards, executed in a Docker sandbox with self-correction, tested, and opened as a pull request. The agent never merges; a human does.
[Build log](https://github.com/Pranay777777/agentic-pipeline-copilot/blob/main/docs/build-log.md) · [Example pull request](https://github.com/Pranay777777/copilot-playground/pull/1)

**[evidence-grounded-resume-engine](https://github.com/Pranay777777/evidence-grounded-resume-engine)** — Résumé generation where every claim must cite a verified evidence record, and an entailment gate drops any claim its evidence doesn't support. 0 of 53 kept bullets fabricated on a hand-labelled golden set; CI fails if one gets through.
[Live demo](https://huggingface.co/spaces/7Pranay77/evidence-grounded-resume-engine) · [Build log](https://github.com/Pranay777777/evidence-grounded-resume-engine/blob/main/docs/build-log.md)

**[metadata-driven-lakehouse](https://github.com/Pranay777777/metadata-driven-lakehouse)** — Onboard a source with one control-plane row, not a new pipeline. Bronze to a Gold star schema with data contracts, schema-drift handling, PII masking and column-level lineage; 1.6M rows end to end in 10.1 s on one vCPU.
[Build log](https://github.com/Pranay777777/metadata-driven-lakehouse/blob/main/docs/build-log.md)

**[asl-realtime-inference](https://github.com/Pranay777777/asl-realtime-inference)** — Real-time ASL alphabet recognition on a plain CPU: MediaPipe hand crop and an INT8 ONNX MobileNetV2 (2.69 MB, 1.33 ms), calibrated to say "not confident" instead of guessing.
[Live demo](https://huggingface.co/spaces/7Pranay77/asl-alphabet-recognizer)

**[Neighborhood-Skill-Swap-Platform](https://github.com/Pranay777777/Neighborhood-Skill-Swap-Platform)** — React + FastAPI + Postgres skill-swap board with rotating refresh tokens, Argon2id, rate limits and a tested authorization rule for every owned object; Playwright E2E in CI.
[Live demo](https://skillswap-web-xhfs.onrender.com) (free tier: the first load can take about a minute)

### Also

- **[Metadata-Driven-Azure-Data-Engineering-Pipeline](https://github.com/Pranay777777/Metadata-Driven-Azure-Data-Engineering-Pipeline)** — Config-driven ETL on Microsoft Fabric. Onboarding a source is a metadata row, not a new pipeline. Medallion architecture with PySpark and Delta Lake.
- **[sql-datawarehouse-project](https://github.com/Pranay777777/sql-datawarehouse-project)** — SQL Server warehouse: staging through to star schema, dimensional modelling, analytical views.
- **[nyc-taxi-etl-medallion](https://github.com/Pranay777777/nyc-taxi-etl-medallion)** — Bronze/silver/gold ETL over the NYC taxi dataset with PySpark and Delta Lake.
- **[repo-template](https://github.com/Pranay777777/repo-template)** — Opinionated Python scaffold: strict typing, secret scanning over full git history, dependency auditing, ADRs, multi-stage Docker. Every project I start begins here.

### Stack

**Data** — Microsoft Fabric · Azure Data Factory · PySpark · Delta Lake · Apache Arrow · SQL Server · Postgres · Medallion architecture
**AI** — LLM agents · RAG · evals & regression gates · MCP · NLI verification · prompt-injection defence · ONNX/INT8 quantization · computer vision
**Backend** — Python · FastAPI · React · SQLAlchemy · Docker · Playwright
**Cloud** — Azure (ADLS Gen2, Azure SQL) · AZ-900 · DP-900 · DP-700
**Practice** — type-checked Python · CI/CD · secret scanning · architecture decision records

---

📍 Hyderabad, India
💼 [LinkedIn](https://linkedin.com/in/pranay-yadagiri-90bb60362) · ✉️ pranayyadagiri04@gmail.com
