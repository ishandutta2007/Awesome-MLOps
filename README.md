# 🚀 Awesome MLOps <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a><a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

> 🌟 A curated directory of top **MLOps Platforms**, Experiment Tracking tools, Model Registries, Pipeline Orchestrators, and End-to-End Machine Learning Lifecycle Management solutions.

<p align="center">
  <img src="assets/banner.svg" alt="Awesome MLOps Banner" width="100%" />
</p>

## 📌 Top MLOps Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Experiment Tracking, Model Registry, Pipeline Orchestration, Model Deployment, Monitoring & End-to-End ML Lifecycle Management*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **MLOps (Machine Learning Operations)**. These tools help AI and data science teams track experiments, version data and models, orchestrate machine learning pipelines, register and deploy models, monitor model drift in production, and manage the full ML and LLMOps lifecycle from research to scalable deployment.

**Examples** include Weights & Biases, Comet ML, ClearML, Neptune.ai, MLflow, Domino Data Lab, DataRobot, SageMaker, Vertex AI, and Azure ML (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted experiment tracking, model registries, pipeline frameworks, and end-to-end MLOps platforms — ideal for ML engineers, platform engineers, and organizations seeking transparent, vendor-independent software supply chain and AI lifecycle control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📋 Table of Contents
- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)

## ☁️ SaaS/Hosted Platforms

| Product | Description | Company Size (Valuation) | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure Machine Learning](https://azure.microsoft.com/en-us/products/machine-learning)** | Microsoft’s enterprise MLOps platform integrated with the Azure ecosystem for experiment tracking, pipelines, deployment, and responsible AI tooling. | ~$3T (Microsoft) | Starts at $0.018/hour (compute) | $200 in free credits for 30 days |
| **[Google Vertex AI](https://cloud.google.com/vertex-ai)** | Unified Google Cloud platform for the entire ML lifecycle, including training, pipelines, model registry, and prediction services. | ~$2T (Alphabet) | Starts at $0.015/hour (compute) | $300 in free credits for 90 days |
| **[Amazon SageMaker](https://aws.amazon.com/sagemaker/)** | Fully managed AWS service for building, training, tuning, deploying, and monitoring machine learning models at scale. | ~$1.8T (Amazon) | Starts at $0.05/hour (ml.t3.medium) | 250 hours/month of ml.t3.medium for the first 2 months |
| **[MLflow (Managed / Databricks)](https://mlflow.org/)** | Widely adopted open-source MLOps framework (with commercial managed offerings) providing experiment tracking, model registry, packaging, and deployment capabilities. | ~$43B (Databricks) | Starts at $0.07/DBU | 500,000 logged models/experiment |
| **[DataRobot](https://www.datarobot.com/)** | Automated machine learning and MLOps platform focused on end-to-end model development, deployment, and governance. | ~$6.3B | Starts at ~$250/month | 30-day free trial (caps: 15 vector DBs, 1000 LLM calls) |
| **[Weights & Biases (W&B)](https://wandb.ai/)** | Industry-standard platform for experiment tracking, visualization, model management, and collaborative ML/LLM workflows with strong developer experience and Weave for LLM observability. | ~$1.25B | Starts at $50/user/month | 5GB storage, 100GB artifact storage |
| **[Domino Data Lab](https://www.dominodatalab.com/)** | Enterprise data science platform offering governed notebooks, reproducibility, model management, and collaboration for regulated and large-scale environments. | ~$100M+ Revenue | Starts at ~$100/user/month | 14-day free trial |
| **[ClearML](https://clear.ml/)** | End-to-end open-core MLOps platform covering experiment management, orchestration, data management, and deployment with strong automation and DevOps integration. | Series B | Starts at $15/user/month | 3 users, 100GB storage, 1M API calls/mo |
| **[Comet ML](https://www.comet.com/)** | Experiment tracking, model management, and LLM evaluation platform popular with teams needing rich reporting and both traditional ML and generative AI support. | Series B | Starts at $49/user/month | Free for individual use, core tracking limits apply |
| **[Neptune.ai](https://neptune.ai/)** | Lightweight yet powerful experiment tracking and metadata store focused on scalability, collaboration, and detailed run comparison. | Series A | Starts at $45/month | 5 users, limited active projects |

## 💻 Open-Source GitHub Projects

- **[Apache Airflow](https://github.com/apache/airflow)** [![Stars](https://img.shields.io/github/stars/apache/airflow?style=social&color=white)](https://github.com/apache/airflow/stargazers)  
  Industry-standard programmatic platform for authoring, scheduling, and monitoring scalable data and ML pipelines.

- **[MLflow](https://github.com/mlflow/mlflow)** [![Stars](https://img.shields.io/github/stars/mlflow/mlflow?style=social&color=white)](https://github.com/mlflow/mlflow/stargazers)  
  The leading open-source MLOps platform for experiment tracking, model packaging, model registry, evaluation, and deployment — now extended for LLMs and agents.

- **[Prefect](https://github.com/PrefectHQ/prefect)** [![Stars](https://img.shields.io/github/stars/PrefectHQ/prefect?style=social&color=white)](https://github.com/PrefectHQ/prefect/stargazers)  
  Modern workflow orchestration framework designed for data engineering and data science, featuring python-native syntax and dynamic DAG generation.

- **[Kubeflow](https://github.com/kubeflow/kubeflow)** [![Stars](https://img.shields.io/github/stars/kubeflow/kubeflow?style=social&color=white)](https://github.com/kubeflow/kubeflow/stargazers)  
  Kubernetes-native open-source ML toolkit for pipelines, training operators, notebooks, and model serving (with KServe).

- **[DVC (Data Version Control)](https://github.com/iterative/dvc)** [![Stars](https://img.shields.io/github/stars/iterative/dvc?style=social&color=white)](https://github.com/iterative/dvc/stargazers)  
  Git-based version control system for ML projects that tracks data, models, and pipelines for reproducibility.

- **[Dagster](https://github.com/dagster-io/dagster)** [![Stars](https://img.shields.io/github/stars/dagster-io/dagster?style=social&color=white)](https://github.com/dagster-io/dagster/stargazers)  
  A data orchestrator for machine learning, analytics, and ETL built for software engineers, enabling testable and maintainable data applications.

- **[Kedro](https://github.com/kedro-org/kedro)** [![Stars](https://img.shields.io/github/stars/kedro-org/kedro?style=social&color=white)](https://github.com/kedro-org/kedro/stargazers)  
  Open-source Python framework that applies software engineering best practices to data and ML pipelines for maintainability and reproducibility.

- **[Metaflow](https://github.com/Netflix/metaflow)** [![Stars](https://img.shields.io/github/stars/Netflix/metaflow?style=social&color=white)](https://github.com/Netflix/metaflow/stargazers)  
  Human-centric open-source framework (originated at Netflix) for building and managing real-life data science and ML projects.

- **[BentoML](https://github.com/bentoml/BentoML)** [![Stars](https://img.shields.io/github/stars/bentoml/BentoML?style=social&color=white)](https://github.com/bentoml/BentoML/stargazers)  
  Open-source platform for building, shipping, and scaling AI applications with standardized model packaging and serving.

- **[Flyte](https://github.com/flyteorg/flyte)** [![Stars](https://img.shields.io/github/stars/flyteorg/flyte?style=social&color=white)](https://github.com/flyteorg/flyte/stargazers)  
  Scalable and highly concurrent workflow automation platform for machine learning and data processing, native to Kubernetes.

- **[Evidently](https://github.com/evidentlyai/evidently)** [![Stars](https://img.shields.io/github/stars/evidentlyai/evidently?style=social&color=white)](https://github.com/evidentlyai/evidently/stargazers)  
  Open-source tools for data and model monitoring, drift detection, and evaluation in production.

- **[ClearML (Open Source core)](https://github.com/allegroai/clearml)** [![Stars](https://img.shields.io/github/stars/allegroai/clearml?style=social&color=white)](https://github.com/allegroai/clearml/stargazers)  
  Open-source components of the ClearML platform for experiment management, orchestration, and automation.

- **[Langfuse](https://github.com/langfuse/langfuse)** [![Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers)  
  Open source LLM engineering platform focusing on tracing, prompt management, and evaluations for AI applications.

- **[Aim](https://github.com/aimhubio/aim)** [![Stars](https://img.shields.io/github/stars/aimhubio/aim?style=social&color=white)](https://github.com/aimhubio/aim/stargazers)  
  Easy-to-use and super performant open-source experiment tracker designed for handling large amounts of ML logging.

- **[Seldon Core / KServe](https://github.com/SeldonIO/seldon-core)** [![Stars](https://img.shields.io/github/stars/SeldonIO/seldon-core?style=social&color=white)](https://github.com/SeldonIO/seldon-core/stargazers)  
  Open-source frameworks for deploying, managing, and monitoring machine learning models on Kubernetes.

- **[ZenML](https://github.com/zenml-io/zenml)** [![Stars](https://img.shields.io/github/stars/zenml-io/zenml?style=social&color=white)](https://github.com/zenml-io/zenml/stargazers)  
  Extensible open-source MLOps framework for creating portable, production-ready pipelines that work across many tools and clouds.

- **[Polyaxon](https://github.com/polyaxon/polyaxon)** [![Stars](https://img.shields.io/github/stars/polyaxon/polyaxon?style=social&color=white)](https://github.com/polyaxon/polyaxon/stargazers)  
  Platform for reproducing and managing the whole life cycle of machine learning and deep learning applications.

- **[CML (Continuous Machine Learning)](https://github.com/iterative/cml)** [![Stars](https://img.shields.io/github/stars/iterative/cml?style=social&color=white)](https://github.com/iterative/cml/stargazers)  
  Open-source library for bringing CI/CD to machine learning workflows, integrating with GitHub Actions and GitLab CI.

## 🤝 How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

⭐ Star the repo if you find it useful!

## ⚠️ Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- MLOps involves model artifacts, data, and often sensitive business logic. Self-hosted open-source stacks require robust security, access control, reproducibility practices, and infrastructure expertise.
- Always validate models and monitoring in production environments according to your organization’s risk and compliance requirements.

## 📈 Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-MLOps&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-MLOps&type=date&legend=top-left)

---
**Made for ML engineers, data scientists, MLOps practitioners, and teams building reliable, reproducible machine learning systems.**
Let's make MLOps more open, reproducible, and production-ready.
