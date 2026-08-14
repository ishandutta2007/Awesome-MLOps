# Awesome-MLOps

Markdown
Copy
## Top MLOps Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Experiment Tracking, Model Registry, Pipeline Orchestration, Model Deployment, Monitoring & End-to-End ML Lifecycle Management*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **MLOps**. These tools help teams track experiments, version data and models, orchestrate pipelines, register and deploy models, monitor performance in production, and manage the full machine learning lifecycle from research to production.

**Examples** include Weights & Biases, Comet ML, ClearML, Neptune.ai, MLflow, Domino Data Lab, DataRobot, SageMaker, Vertex AI, and Azure ML (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted experiment tracking, model registries, pipeline frameworks, and end-to-end MLOps platforms — ideal for ML engineers, data scientists, and organizations seeking transparent, vendor-independent control over the ML lifecycle.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Weights & Biases (W&B)](https://wandb.ai/)**  
  Industry-standard platform for experiment tracking, visualization, model management, and collaborative ML/LLM workflows with strong developer experience and Weave for LLM observability.

- **[Comet ML](https://www.comet.com/)**  
  Experiment tracking, model management, and LLM evaluation platform popular with teams needing rich reporting and both traditional ML and generative AI support.

- **[ClearML](https://clear.ml/)**  
  End-to-end open-core MLOps platform covering experiment management, orchestration, data management, and deployment with strong automation and DevOps integration.

- **[Neptune.ai](https://neptune.ai/)**  
  Lightweight yet powerful experiment tracking and metadata store focused on scalability, collaboration, and detailed run comparison.

- **[MLflow (Managed / Databricks)](https://mlflow.org/)**  
  Widely adopted open-source MLOps framework (with commercial managed offerings) providing experiment tracking, model registry, packaging, and deployment capabilities.

- **[Domino Data Lab](https://www.dominodatalab.com/)**  
  Enterprise data science platform offering governed notebooks, reproducibility, model management, and collaboration for regulated and large-scale environments.

- **[DataRobot](https://www.datarobot.com/)**  
  Automated machine learning and MLOps platform focused on end-to-end model development, deployment, and governance.

- **[Amazon SageMaker](https://aws.amazon.com/sagemaker/)**  
  Fully managed AWS service for building, training, tuning, deploying, and monitoring machine learning models at scale.

- **[Google Vertex AI](https://cloud.google.com/vertex-ai)**  
  Unified Google Cloud platform for the entire ML lifecycle, including training, pipelines, model registry, and prediction services.

- **[Azure Machine Learning](https://azure.microsoft.com/en-us/products/machine-learning)**  
  Microsoft’s enterprise MLOps platform integrated with the Azure ecosystem for experiment tracking, pipelines, deployment, and responsible AI tooling.

## Open-Source GitHub Projects
- **[MLflow](https://github.com/mlflow/mlflow)**  
  The leading open-source MLOps platform for experiment tracking, model packaging, model registry, evaluation, and deployment — now extended for LLMs and agents.

- **[Kubeflow](https://github.com/kubeflow/kubeflow)**  
  Kubernetes-native open-source ML toolkit for pipelines, training operators, notebooks, and model serving (with KServe).

- **[ZenML](https://github.com/zenml-io/zenml)**  
  Extensible open-source MLOps framework for creating portable, production-ready pipelines that work across many tools and clouds.

- **[ClearML (Open Source core)](https://github.com/allegroai/clearml)**  
  Open-source components of the ClearML platform for experiment management, orchestration, and automation.

- **[DVC (Data Version Control)](https://github.com/iterative/dvc)**  
  Git-based version control system for ML projects that tracks data, models, and pipelines for reproducibility.

- **[Metaflow](https://github.com/Netflix/metaflow)**  
  Human-centric open-source framework (originated at Netflix) for building and managing real-life data science and ML projects.

- **[Kedro](https://github.com/kedro-org/kedro)**  
  Open-source Python framework that applies software engineering best practices to data and ML pipelines for maintainability and reproducibility.

- **[BentoML](https://github.com/bentoml/BentoML)**  
  Open-source platform for building, shipping, and scaling AI applications with standardized model packaging and serving.

- **[Seldon Core / KServe](https://github.com/SeldonIO/seldon-core)**  
  Open-source frameworks for deploying, managing, and monitoring machine learning models on Kubernetes.

- **[Evidently / Deepchecks / other monitoring libraries](https://github.com/evidentlyai/evidently)**  
  Open-source tools for data and model monitoring, drift detection, and evaluation in production.

### Additional Strong Open-Source Options
- **Prefect**, **Dagster**, **Airflow**, and **Argo Workflows** for pipeline orchestration.
- **Flyte** for scalable, Kubernetes-native workflow orchestration.
- **Polyaxon** for experiment tracking and large-scale training management.
- **Aim** and other lightweight experiment tracking UIs.
- LLM-focused open observability stacks (Langfuse, Phoenix, etc.) that complement classic MLOps tools.
- **CML** (Continuous Machine Learning) for Git-based CI/CD of ML projects.

**Frameworks for building custom systems**: Use **MLflow** as the core experiment tracker and model registry, orchestrate pipelines with **ZenML**, **Kubeflow**, or **Kedro**, version data with **DVC**, package and serve models with **BentoML** or **KServe**, and monitor with **Evidently** or similar libraries. Deploy everything on Kubernetes or your preferred infrastructure and optionally layer local LLMs for automated analysis of experiment results and drift reports.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- MLOps involves model artifacts, data, and often sensitive business logic. Self-hosted open-source stacks require robust security, access control, reproducibility practices, and infrastructure expertise.
- Always validate models and monitoring in production environments according to your organization’s risk and compliance requirements.

---
**Made for ML engineers, data scientists, MLOps practitioners, and teams building reliable, reproducible machine learning systems.**
Let's make MLOps more open, reproducible, and production-ready.
