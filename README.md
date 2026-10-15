# Awesome-Visual-Headless-CMS

### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Visual-Headless-CMS

## Top Visual Headless CMS Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on API-First Content, Visual Page Building, Structured Content Models & Omnichannel Delivery*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Visual & Headless CMS**. These systems separate content from presentation—APIs for apps and websites, often with visual editors or drag-and-drop page builders for marketers and developers.



**Examples** include Contentful, Strapi Cloud, Sanity.io, Storyblok, Prismic, Hygraph, ButterCMS, Agility CMS, Ghost Pro, Kontent.ai, and **Builder.io** (`BuilderIO/builder`)—drag-and-drop headless CMS and visual development.



**Open-source emphasis**: Headless CMS has excellent open options. **Strapi**, **Payload**, **Ghost**, **Keystone**, **Apostrophe**, and **Builder** open components enable self-hosted content platforms. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Contentful, Sanity, Storyblok, Prismic, Hygraph, Kontent.ai](https://www.contentful.com/)**  

  Leading hosted headless CMS platforms—structured content, visual editing (varies by product), and global content delivery APIs.



- **[Builder.io, Agility CMS, ButterCMS](https://www.builder.io/)**  

  Visual / drag-and-drop oriented headless systems for page building and component-driven experiences.



- **[Strapi Cloud, Ghost Pro](https://strapi.io/)**  

  Managed offerings of popular open CMS projects—hosting, scaling, and support for teams that prefer not to self-host.



- **[Other commercial headless CMS platforms](https://www.sanity.io/)**  

  Additional API-first content and experience management services.



## Open-Source GitHub Projects



### Headless & API-First CMS



- **[Strapi](https://github.com/strapi/strapi)**  

  Leading open-source headless CMS—visual content-type builder, REST/GraphQL APIs, and a large plugin ecosystem (MIT).



- **[Payload](https://github.com/payloadcms/payload)**  

  Open TypeScript-first headless CMS and application framework—code-defined collections, admin UI, and deep Next.js integration.



- **[Ghost](https://github.com/TryGhost/Ghost)**  

  Open publishing-focused CMS—modern admin, memberships, and headless API mode for content sites and newsletters.



- **[Keystone](https://github.com/keystonejs/keystone)**  

  Open Node.js headless CMS and graph-based content platform—flexible schema and Admin UI.



- **[ApostropheCMS](https://github.com/apostrophecms/apostrophe)**  

  Open in-context editing CMS—visual editing experience with modular page building.



- **[Webiny](https://github.com/webiny/webiny-js)**  

  Open serverless CMS and application framework—headless content and page builder components.



### Visual Builders & Data Platforms



- **[Builder.io (open SDKs / core)](https://github.com/BuilderIO/builder)**  

  Visual headless CMS and page builder—open SDKs and drag-and-drop registration for components in modern frontends.



- **[Directus](https://github.com/directus/directus)**  

  Database-first data platform with a polished admin UI and APIs—source-available with license constraints; widely used as a headless layer over SQL (verify current license for your use case).



- **[TinaCMS](https://github.com/tinacms/tinacms)**  

  Open Git-backed visual CMS—edit content in context and commit to the repository.



- **[Decap CMS (formerly Netlify CMS)](https://github.com/decaporg/decap-cms)**  

  Open Git-based CMS for static sites—editorial UI on top of files in the repo.



- **[Sanity Studio (open)](https://github.com/sanity-io/sanity)**  

  Open real-time content workspace; hosting and Content Lake are commercial—Studio can be customized and self-run.



### Additional Strong Open-Source Options



- **GUI-first headless**: Strapi.

- **Code-first TypeScript**: Payload.

- **Publishing / memberships**: Ghost.

- **In-context visual**: Apostrophe or TinaCMS.

- **Git-based**: Decap CMS or TinaCMS.

- **Composable stacks**: Open CMS → Next.js/Astro/Nuxt → CDN; or Builder-style visual layer on top of headless content.

- Commercial SaaS still leads for global CDN content APIs, collaboration SLAs, and zero-ops editorial workflows.



**Frameworks for building custom systems**:  

**Strapi** or **Payload** for self-hosted headless; **Ghost** for publications; **Builder** open SDKs for visual page composition; **Tina/Decap** for Git workflows.  

Fully open headless CMS stacks are production-proven for startups through large content sites.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CMS platforms hold important business content—back up data, lock down admin access, and review plugin security. License terms differ (MIT vs source-available); confirm compliance before commercial redistribution.

- Open-source CMS offers ownership and flexibility. Hosted platforms shift uptime and scaling to the vendor. Neither replaces information architecture and editorial process design.



---



**Made for content teams, frontend engineers, and composable architecture builders.**  

Let's expand open headless and visual CMS while recognizing the collaboration scale that leading commercial content platforms deliver.
