# Raúl Cabezas Martínez

**Senior Platform / DevSecOps Engineer → AI Infrastructure & MLOps**

9+ years designing secure platforms for mission-critical, regulated environments (defense sector). Currently building the Kubernetes-native AI/MLOps layer on top of that platform engineering foundation — experiment tracking, model registries, distributed training, LLM serving, and the governance that lets ML teams move fast without breaking compliance.

📍 Madrid, Spain · 🎓 MSc in AI & Deep Learning (in progress) · 🔐 Background in DevSecOps & software supply chain security

---

### What I actually do

- **Platform engineering** — internal Kubernetes platforms (Helm, ArgoCD/GitOps, Terraform, Ansible) that give product and ML teams self-service, standardized deployment paths.
- **Software supply chain security** — SBOM generation, artifact signing (Cosign/Sigstore), SAST/DAST/SCA gates, and full traceability from source to running workload, applied across Rust, Python, Java, C/C++ and .NET stacks.
- **AI/MLOps infrastructure** — Kubernetes-based platforms integrating MLflow, JupyterHub, MinIO, KubeRay and OpenMetadata for experimentation, model lifecycle management and metadata governance.
- **Observability** — Prometheus/Grafana/Loki/Mimir stacks, plus LLM-specific metrics (TTFT, TPOT, token throughput) for inference workloads.

### 🔭 Featured projects

| Project | What it shows |
|---|---|
| [`k8s-llmops-inference-platform`](https://github.com/raulcmz/k8s-llmops-inference-platform) | LLM inference gateway on Kubernetes (FastAPI, Ollama/vLLM adapters), with Prometheus metrics, an offline quality-eval harness, a baseline-vs-candidate promotion gate, and CI on every change. Platform-engineering patterns applied to LLM serving. |
| [`cybersec-mlops-pipeline`](https://github.com/raulcmz/cybersec-mlops-pipeline) | Master's thesis project: end-to-end MLOps pipeline for network anomaly detection (Isolation Forest), orchestrated with Prefect, versioned in MinIO, audited in PostgreSQL, running as Kubernetes Jobs on RKE2. |
| [`mlflow-k8s-ml-pipeline`](https://github.com/raulcmz/mlflow-k8s-ml-pipeline) | End-to-end MLOps platform (MLflow, MinIO, FastAPI, Docker, Kubernetes) for training, registering and serving a churn-prediction model, with a stable `champion` alias for serving. |
| [`llm-prompt-evals`](https://github.com/raulcmz/llm-prompt-evals) | Prompt engineering and evaluation for real-world healthcare and finance use cases, focused on small local models, structured outputs and reproducible benchmarks. |
| [`ai-platform-notes`](https://raulcmz.github.io/ai-platform-notes/) | Public, versioned knowledge base (MkDocs) on ML infrastructure, MLOps, data engineering and DevSecOps-for-ML — written while building the projects above. |

### 🌱 Open source contributions

- [`kellnr/kellnr`](https://github.com/kellnr/kellnr) — [merged fix](https://github.com/kellnr/kellnr/pull/1080) for an OAuth2 callback URL bug (`origin.path` normalization) that broke OIDC login when deploying behind an ingress with a root path.

### 🧰 Core stack

**Containers & Platform** `Kubernetes` `Docker` `Helm` `ArgoCD` `GitOps`
**IaC & Automation** `Terraform` `Ansible` `GitLab CI/CD` `Jenkins` `Python` `Bash`
**Supply chain security** `SAST` `DAST` `SCA` `SBOM` `Cosign` `SonarQube` `Snyk` `OWASP ZAP` `Harbor` `Vault`
**Observability** `Prometheus` `Grafana` `Loki` `Mimir`
**AI Infra / MLOps** `MLflow` `Prefect` `JupyterHub` `MinIO` `KubeRay` `OpenMetadata` `FastAPI` `PostgreSQL`

### 📜 Certifications

`AWS Certified Solutions Architect` · `KCNA` · `CompTIA Security+` · `CompTIA CySA+` · `eCPPT` · `eWPT` · `eJPTv2` · `Microsoft AI-900`

### 📈 Currently

- Finishing an MSc in AI & Deep Learning while shipping the projects above in production-style patterns (tests, CI, promotion gates).
- Also studying Psychology part-time — it feeds directly into how I think about human-in-the-loop evaluation, model failure modes and building AI systems people actually trust.

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/ra%C3%BAl-mart%C3%ADnez-975b5968) · rcabezasmartinez@gmail.com
