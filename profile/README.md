## Fractal Techware

**Tested, production-ready configs for observability, Kubernetes and n8n.** Every artifact ships with automated tests, not just YAML that looks right.

### Free docs

- [Prometheus alert runbooks](https://fractal-techware.github.io/runbooks/): 165 alerts, what they mean and what to check first
- [Guides](https://fractal-techware.github.io/guides/): working, tested OpenTelemetry Collector and Kyverno configs explained, plus [testing alert rules with promtool](https://fractal-techware.github.io/guides/testing-prometheus-alert-rules-promtool/)

### Free & open source (MIT)

| Repo | What you get |
|---|---|
| **Observability & SRE** | |
| [prometheus-alert-rules](https://github.com/Fractal-Techware/prometheus-alert-rules) | Prometheus alerts for Kubernetes & node_exporter, each with promtool unit tests and a runbook |
| [opentelemetry-collector-recipes](https://github.com/Fractal-Techware/opentelemetry-collector-recipes) | OpenTelemetry Collector configs, validated against a pinned contrib release |
| [grafana-dashboards](https://github.com/Fractal-Techware/grafana-dashboards) | Grafana dashboards for node_exporter & Kubernetes namespaces and pods |
| [slo-as-code](https://github.com/Fractal-Techware/slo-as-code) | SLOs in YAML to Prometheus multi-window burn-rate alerts, with promtool timing tests |
| [vps-observability-stack](https://github.com/Fractal-Techware/vps-observability-stack) | Prometheus + Grafana behind automatic HTTPS on one VPS, generated credentials, hardened containers |
| **Kubernetes** | |
| [kubernetes-hardening-baseline](https://github.com/Fractal-Techware/kubernetes-hardening-baseline) | Pod Security, default-deny NetworkPolicies and Kyverno policies with CLI tests |
| [helm-production-chart](https://github.com/Fractal-Techware/helm-production-chart) | Helm chart for a stateless HTTP service with restricted Pod Security defaults and a strict values schema |
| **n8n automation** | |
| [n8n-production-compose](https://github.com/Fractal-Techware/n8n-production-compose) | Hardened Docker Compose for self-hosting n8n: external task runner, Postgres, Caddy HTTPS, generated secrets |
| [n8n-incident-triage-workflow](https://github.com/Fractal-Techware/n8n-incident-triage-workflow) | Turns an Alertmanager alert group into one triaged chat message, with a fallback when the LLM fails |
| [n8n-github-pr-summary](https://github.com/Fractal-Techware/n8n-github-pr-summary) | Summarises a GitHub pull request with an LLM and posts one comment, HMAC-verified |

### Free dashboards on grafana.com

Import by ID in Grafana (**Dashboards → New → Import**):
[Infrastructure Overview](https://grafana.com/grafana/dashboards/25798/) `25798` ·
[Kubernetes Namespaces & Pods](https://grafana.com/grafana/dashboards/25799/) `25799` ·
[VPS Host](https://grafana.com/grafana/dashboards/25835/) `25835` ·
[n8n Production Overview](https://grafana.com/grafana/dashboards/25836/) `25836`

### Full packs

| Pack | Starter | Pro | Studio |
|---|---:|---:|---:|
| **Observability & SRE** | | | |
| [Prometheus Alert Rules & Runbooks](https://store.fractaltechware.com/l/prometheus-alert-rules-pack?utm_source=github&utm_medium=org-profile) — 179 alerts, 364 tests | $19 | $49 | $99 |
| [OpenTelemetry Collector Recipes](https://store.fractaltechware.com/l/otel-collector-recipes?utm_source=github&utm_medium=org-profile) — 16 recipes, tail sampling, PII redaction | $19 | $49 | $99 |
| [Grafana Dashboard Pack](https://store.fractaltechware.com/l/grafana-dashboard-pack?utm_source=github&utm_medium=org-profile) — 13 dashboards, Terraform, Helm | $9 | $39 | $79 |
| [SLO-as-Code Kit](https://store.fractaltechware.com/l/slo-as-code-kit?utm_source=github&utm_medium=org-profile) — 21 SLI templates, 123 burn-rate timing scenarios | $19 | $49 | $99 |
| [Single-VPS Observability Stack](https://store.fractaltechware.com/l/vps-observability-stack?utm_source=github&utm_medium=org-profile) — adds Loki, Tempo, Alloy, Alertmanager, tested backup and restore | $19 | $49 | $99 |
| **Kubernetes** | | | |
| [Kubernetes Hardening Baseline Kit](https://store.fractaltechware.com/l/k8s-hardening-kit?utm_source=github&utm_medium=org-profile) — 21 Kyverno policies, audit CLI | $19 | $49 | $99 |
| [Production Helm Chart Kit](https://store.fractaltechware.com/l/helm-production-chart?utm_source=github&utm_medium=org-profile) — app + library charts, 266 helm-unittest runs | $19 | $49 | $99 |
| **n8n automation** | | | |
| [n8n Production Self-Hosting Kit](https://store.fractaltechware.com/l/n8n-production-kit?utm_source=github&utm_medium=org-profile) — queue mode, backups, alerts, Grafana dashboard, Helm chart | $19 | $49 | $99 |
| [n8n AI Incident Triage Workflows](https://store.fractaltechware.com/l/n8n-incident-triage-workflows?utm_source=github&utm_medium=org-profile) — up to 16 workflows: Alertmanager, Grafana, PagerDuty, Loki, postmortems | $19 | $49 | $99 |
| [n8n AI Workflows for GitHub](https://store.fractaltechware.com/l/n8n-github-ai-workflows?utm_source=github&utm_medium=org-profile) — up to 18 workflows: PR summaries, release notes, CI failure explainer | $19 | $49 | $99 |

### Bundles (Pro tier of each pack)

| Bundle | Includes | Price |
|---|---|---:|
| [SRE Observability Bundle](https://store.fractaltechware.com/l/sre-observability-bundle?utm_source=github&utm_medium=org-profile) | Prometheus Alert Rules, OpenTelemetry Recipes, Kubernetes Hardening, Grafana Dashboards | $129 ~~$186~~ |
| [Kubernetes Delivery Bundle](https://store.fractaltechware.com/l/kubernetes-delivery-bundle?utm_source=github&utm_medium=org-profile) | Production Helm Chart, Kubernetes Hardening, Prometheus Alert Rules | $99 ~~$147~~ |
| [n8n Automation Bundle](https://store.fractaltechware.com/l/n8n-automation-bundle?utm_source=github&utm_medium=org-profile) | n8n Self-Hosting Kit, AI Incident Triage, AI Workflows for GitHub | $99 ~~$147~~ |

All products: [store.fractaltechware.com](https://store.fractaltechware.com/?utm_source=github&utm_medium=org-profile)
