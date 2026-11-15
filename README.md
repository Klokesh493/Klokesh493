<h1 align="center">Lokesh Reddy</h1>
<h3 align="center">Site Reliability Engineer · Cloud Platforms · DevSecOps · AI for Operations</h3>
<p align="center">I build tools that help responders investigate incidents, recover services, and make safer release decisions.</p>
<p align="center">
  <a href="https://klokesh493.github.io/lokesh-kalluru-portfolio/"><img alt="Portfolio — Open site" src="https://img.shields.io/badge/PORTFOLIO-OPEN_SITE-0758B8?style=for-the-badge&amp;labelColor=18253B"></a>
  <a href="https://klokesh493.github.io/lokesh-kalluru-portfolio/#work"><img alt="Projects — View work" src="https://img.shields.io/badge/PROJECTS-VIEW_WORK-B73524?style=for-the-badge&amp;labelColor=18253B"></a>
  <a href="https://klokesh493.github.io/lokesh-kalluru-portfolio/#labs"><img alt="AI labs — Explore" src="https://img.shields.io/badge/AI_LABS-EXPLORE-08716C?style=for-the-badge&amp;labelColor=18253B"></a>
</p>

## Selected Work

| Project | What you can verify |
| --- | --- |
| [SRE Incident Investigation Agent](https://github.com/Klokesh493/llm-sre-incident-investigation-agent) | Turn synthetic SLO and change evidence into a cited paging recommendation. Route incomplete evidence to an operator for review. [Captured model run](https://github.com/Klokesh493/llm-sre-incident-investigation-agent/blob/main/examples/live-report.json) |
| [SRE Error Budget Control Plane](https://github.com/Klokesh493/sre-error-budget-control-plane) | Replay SLO burn and test how Alertmanager routes page and ticket alerts and inhibits duplicate notifications. [Routing drill](https://github.com/Klokesh493/sre-error-budget-control-plane/blob/main/docs/RUNBOOK.md#verify-alertmanager-routing) |
| [Release Evidence Pipeline](https://github.com/Klokesh493/release-evidence-pipeline) | Reproduce an approved release and an incident hold using evidence from four SRE, AWS recovery, Azure ML, and on-call labs. [Release replay](https://github.com/Klokesh493/release-evidence-pipeline#run-the-demo) |
| [AWS Event Recovery Platform](https://github.com/Klokesh493/aws-event-recovery-platform) | Retry only failed SQS records, preserve idempotent receipts, and exercise the dead-letter recovery path locally. [Recovery drill](https://github.com/Klokesh493/aws-event-recovery-platform#run-the-demo) |
| [Kubernetes Node Drain Planner](https://github.com/Klokesh493/kubernetes-node-drain-planner) | Check workload replicas, disruption budgets, and critical pods before planning a node drain. [Run the planner](https://github.com/Klokesh493/kubernetes-node-drain-planner#run-the-project) |
| [Azure ML Endpoint Release Lab](https://github.com/Klokesh493/azure-ml-endpoint-release-lab) | Train a classifier, verify holdout quality and the model artifact, then replay the Azure ML scoring contract locally. [Scoring demo](https://github.com/Klokesh493/azure-ml-endpoint-release-lab#run-the-demo) |

## AI Agent Labs

The labs use a local Qwen model to select read-only evidence probes. Each report records the input evidence and the resulting policy decision on synthetic data.

| Lab | What you can verify |
| --- | --- |
| [Dependency Remediation](https://github.com/Klokesh493/ai-dependency-remediation-agent) | Review an advisory and identify a candidate update outside the affected version range. The report records whether it qualifies for testing. [Model report](https://github.com/Klokesh493/ai-dependency-remediation-agent/blob/main/examples/live-report.json) |
| [AI Release Regression](https://github.com/Klokesh493/ai-release-regression-agent) | Use evaluation evidence to recommend a release decision. Critical regressions, unsupported citations, and token overruns trigger a hold. [Model report](https://github.com/Klokesh493/ai-release-regression-agent/blob/main/examples/live-report.json) |
| [Model Drift Investigation](https://github.com/Klokesh493/ai-model-drift-investigation-agent) | Investigate drift with feature shift, label quality, and freshness evidence before proposing a follow-up. [Model report](https://github.com/Klokesh493/ai-model-drift-investigation-agent/blob/main/examples/live-report.json) |
| [Support Knowledge](https://github.com/Klokesh493/ai-support-knowledge-agent) | Return a cited support excerpt from the appropriate tenant or escalate with the reason recorded. [Model report](https://github.com/Klokesh493/ai-support-knowledge-agent/blob/main/examples/live-report.json) |

## Professional Summary

I focus on the decisions engineers make during incidents and changes. My projects turn SLOs into routing decisions, evaluate rollout and recovery evidence, and give responders a cited next step. The repositories document how to run each demo, test failure cases, and understand the limits of the result.

## Tech Stack

### DevOps and CI/CD

[![DevOps](https://img.shields.io/badge/DevOps-0969DA?style=for-the-badge)](https://github.com/Klokesh493/traffic-shift-canary-scorecard) [![CI/CD](https://img.shields.io/badge/CI%2FCD-0969DA?style=for-the-badge)](https://docs.github.com/actions) [![Jenkins](https://img.shields.io/badge/Jenkins-B63730?style=for-the-badge&logo=jenkins&logoColor=white)](https://www.jenkins.io/doc/) [![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1665C1?style=for-the-badge&logo=githubactions&logoColor=white)](https://docs.github.com/actions)

### Cloud, Platform, and Security

[![Kubernetes](https://img.shields.io/badge/Kubernetes-2758C9?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/docs/) [![Docker](https://img.shields.io/badge/Docker-1471B9?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/) [![Terraform](https://img.shields.io/badge/Terraform-6540A4?style=for-the-badge&logo=terraform&logoColor=white)](https://developer.hashicorp.com/terraform/docs) [![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)](https://docs.aws.amazon.com/) [![DevSecOps](https://img.shields.io/badge/DevSecOps-343C50?style=for-the-badge)](https://github.com/Klokesh493/immutable-backup-policy-auditor)

### DevSecOps Tooling

[![Trivy](https://img.shields.io/badge/Trivy-A64808?style=for-the-badge&logo=trivy&logoColor=white)](https://trivy.dev/docs/) [![Gitleaks](https://img.shields.io/badge/Gitleaks-9C343B?style=for-the-badge)](https://github.com/gitleaks/gitleaks) [![HashiCorp Vault](https://img.shields.io/badge/HashiCorp_Vault-242C39?style=for-the-badge&logo=vault&logoColor=white)](https://developer.hashicorp.com/vault/docs) [![Checkov](https://img.shields.io/badge/Checkov-4D45A7?style=for-the-badge)](https://www.checkov.io/) [![Sigstore Cosign](https://img.shields.io/badge/Sigstore_Cosign-116A60?style=for-the-badge&logo=sigstore&logoColor=white)](https://docs.sigstore.dev/cosign/)

Tool references for container scanning, secret detection, secrets management, infrastructure policy, and artifact signing. For a portfolio example, see the [Immutable Backup Policy Auditor](https://github.com/Klokesh493/immutable-backup-policy-auditor).

### Monitoring, SRE, and On-call

[![SRE](https://img.shields.io/badge/SRE-111827?style=for-the-badge)](https://github.com/Klokesh493/ai-incident-correlation-engine) [![Splunk](https://img.shields.io/badge/Splunk-171717?style=for-the-badge&logo=splunk&logoColor=white)](https://github.com/Klokesh493/splunk-alert-triage) [![Prometheus](https://img.shields.io/badge/Prometheus-B94027?style=for-the-badge&logo=prometheus&logoColor=white)](https://prometheus.io/docs/) [![Grafana](https://img.shields.io/badge/Grafana-A6470F?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.com/docs/) [![PagerDuty](https://img.shields.io/badge/PagerDuty-067448?style=for-the-badge&logo=pagerduty&logoColor=white)](https://github.com/Klokesh493/on-call-rotation-lab) [![On-call Rotation](https://img.shields.io/badge/On-call_Rotation-394860?style=for-the-badge)](https://github.com/Klokesh493/on-call-rotation-lab) [![24/7 Support](https://img.shields.io/badge/24x7_Support-394860?style=for-the-badge)](https://github.com/Klokesh493/on-call-rotation-lab) [![Alert Operations](https://img.shields.io/badge/Alert_Operations-394860?style=for-the-badge)](https://github.com/Klokesh493/ai-incident-correlation-engine)

### Streaming, AI, and ML

[![Kafka](https://img.shields.io/badge/Kafka-252B36?style=for-the-badge&logo=apachekafka&logoColor=white)](https://github.com/Klokesh493/kafka-consumer-lag-slo-guard) [![Flink](https://img.shields.io/badge/Flink-A91C59?style=for-the-badge&logo=apacheflink&logoColor=white)](https://flink.apache.org/) [![Python](https://img.shields.io/badge/Python-306998?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/) [![MLOps](https://img.shields.io/badge/MLOps-623BA5?style=for-the-badge)](https://github.com/Klokesh493/model-serving-canary-analyzer) [![AI Agents](https://img.shields.io/badge/AI_Agents-087F72?style=for-the-badge)](https://klokesh493.github.io/lokesh-kalluru-portfolio/#labs)

### Service and Support Domains

[![SaaS](https://img.shields.io/badge/SaaS-126079?style=for-the-badge)](#professional-summary)

SaaS means Software as a Service.

## More Engineering Work

- [Splunk Alert Triage](https://github.com/Klokesh493/splunk-alert-triage) · Deduplicate exported alerts and prioritize on-call review.
- [Kafka Consumer Lag SLO Guard](https://github.com/Klokesh493/kafka-consumer-lag-slo-guard) · Estimate catch-up time against a freshness objective.
- [On-call Rotation Lab](https://github.com/Klokesh493/on-call-rotation-lab) · Simulate coverage, acknowledgment deadlines, and escalation.
- [Multi-Region Failover Planner](https://github.com/Klokesh493/multi-region-failover-planner) · Evaluate target health, capacity, and replication lag.

## Currently Learning

- Evaluating agent decisions when telemetry is incomplete, conflicting, or stale.
- Diagnosing Kafka consumer lag and recovering safely across partitions.
- Comparing model candidates with reproducible scoring and drift evidence.

## What I Bring

- **Incident readiness** · On-call coverage, clear escalations, and evidence that a responder can reproduce.
- **Platform operations** · Kubernetes maintenance checks, release holds, and recovery drills.
- **AI-assisted workflows** · Cited evidence, escalation paths, and operational decisions reviewable by an engineer.

## Connect

[Portfolio](https://klokesh493.github.io/lokesh-kalluru-portfolio/) · [GitHub activity](https://github.com/Klokesh493#js-contribution-activity) · [All repositories](https://github.com/Klokesh493?tab=repositories)

<details>
<summary>About this profile repository</summary>

## Business problem

Reviewers need a direct route from the profile to runnable engineering work and its verification evidence.

## What I built

This repository is the source of my GitHub Overview. I organized the README around selected SRE and platform projects, then linked each entry to the public repository so reviewers can see the code, an example, and its verification evidence. GitHub renders the Markdown and HTML, and Shields.io supplies the navigation badges.

## Project walkthrough

```mermaid
flowchart LR
    A["GitHub profile visit"]
    B["Profile README and flagship project table"]
    C["Choose what to explore"]
    D["Portfolio homepage"]
    E["Featured public repository"]
    A --> B --> C
    C --> D
    C --> E
```

[Architecture and data flow](docs/ARCHITECTURE.md) · [Business problem, demo, and verification](docs/CASE_STUDY.md)

## Run the project

Open the public GitHub profile, then follow a featured project link or the portfolio button.

Read the [architecture](docs/ARCHITECTURE.md) and [walkthrough](docs/CASE_STUDY.md) for the source path and verification scope.

[Development and review](docs/DEVELOPMENT.md)

## Runbook

[Run, verify, and troubleshoot this project](docs/RUNBOOK.md)

</details>

[Skills and verification](docs/ENGINEERING_NOTES.md)
