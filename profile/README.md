# Arcane

![Arcane Hero](https://arcanetracing.com/img/landing_hero_illustration.png)

**OpenTelemetry-Native Observability for AI Systems.**

[**arcanetracing.com**](https://arcanetracing.com) · [**Documentation**](https://arcanetracing.com/docs/intro) · [**Get Started Free**](https://arcanetracing.com/docs/intro) · [**Contact**](mailto:contact@arcanetracing.com)

[![PyPI arcane-sdk](https://img.shields.io/pypi/v/arcane-sdk?label=pypi%20arcane-sdk)](https://pypi.org/project/arcane-sdk/) [![npm arcane-sdk](https://img.shields.io/npm/v/arcane-sdk?label=npm%20arcane-sdk)](https://www.npmjs.com/package/arcane-sdk) [![Docker Pulls](https://img.shields.io/docker/pulls/arcanetracing/arcane?label=docker%20pulls)](https://hub.docker.com/u/arcanetracing)

---

Arcane brings GenAI observability and evaluation on top of OpenTelemetry-compatible backends. Use any tracing backend that exports OTEL and get LLM and agent tracing, datasets, annotations, scores, and auditability — **without vendor lock-in**.

## ✨ Core Features

### Trace Explorations
![Trace Explorations](https://arcanetracing.com/img/view_trace.png)
Deep-dive into every request with high-fidelity, ultra-fast trace reconstruction.

### Conversation View
![Conversation View](https://arcanetracing.com/img/view_conversation.png)
Reconstruct full user conversations across multiple traces and sessions for perfect context.

### Native OpenTelemetry Events
![OpenTelemetry Events](https://arcanetracing.com/img/otel_events.png)
Arcane supports OpenTelemetry events out of the box to track your application's events.

### Business Entities Identification
![Business Entities](https://arcanetracing.com/img/entities.png)
Automatically map raw telemetry to business concepts like Models, Agents, and Guardrails.

### Evaluations
![Evaluations](https://arcanetracing.com/img/view_evaluations.png)
Quantify quality with RAGAS, custom metrics, and pre-computed statistics. Compare results across experiments.

### Experiments
![Experiments](https://arcanetracing.com/img/view_experiments.png)
Optimize performance by running prompt versions over curated datasets. Execute batch runs to find the best variations.

### Scores & Prompt Lifecycle
![Scores & Prompts](https://arcanetracing.com/img/scores_and_prompts.png)
Define proprietary metrics and manage prompt versions with a complete audit trail.

### Annotations
![Annotations](https://arcanetracing.com/img/annotations.png)
Human-in-the-loop feedback directly on traces and conversation snippets.

### Dataset Management
![Dataset Management](https://arcanetracing.com/img/dataset.png)
Curate datasets with an advanced trace-level builder for fine-tuning and regression testing.

## 📦 Natively Integrated with Your Ecosystem

Arcane works seamlessly with OTel-native tools. No vendor lock-in, just pure observability.

<img src="https://arcanetracing.com/img/custom-api.png" width="32" height="32" alt="Custom API" /> <img src="https://arcanetracing.com/img/jaeger.png" width="32" height="32" alt="Jaeger" /> <img src="https://arcanetracing.com/img/tempo.png" width="32" height="32" alt="Tempo" /> <img src="https://arcanetracing.com/img/clickhouse.svg" width="32" height="32" alt="ClickHouse" />

| Integration | Description |
|-------------|-------------|
| **Custom API** | Any backend that exposes traces in OpenTelemetry format. |
| **Jaeger** | Mature tracing backend. Works with OTLP and multiple storage backends. |
| **Tempo** | Grafana's tracing backend. Great for large volumes and TraceQL queries. |
| **ClickHouse** | Columnar database for analytics and large-scale deployments. |

[Explore Integrations →](https://arcanetracing.com/docs/configure-first/organisation/datasources)

## 🏗️ Architecture Overview

Arcane is built on OpenTelemetry and connects to your existing trace backends (Tempo, Jaeger, ClickHouse) without storing traces itself. The platform consists of a frontend, backend API, and worker services that query your backends and run evaluations.

[Learn about the architecture →](https://arcanetracing.com/docs/architecture)

## 🚀 Learn to Deploy

Deploy Arcane with Docker Compose using pre-built images. Choose from base, Tempo, Jaeger, or ClickHouse variants with RabbitMQ or Kafka. Configure your data sources, set environment variables, and run the stack locally or in production.

[Deployment documentation →](https://arcanetracing.com/docs/deployment)

## 🚀 Quick Start

1. **Create an account** at [arcanetracing.com](https://arcanetracing.com/docs/intro)
2. **Configure a data source** — Connect Tempo, Jaeger, ClickHouse, or your Custom API
3. **Start tracing** — Instrument your app with OpenTelemetry and see traces in Arcane

See the [documentation](https://arcanetracing.com/docs/intro) for detailed setup guides.

## 📂 Repositories

| Repository | Description |
|------------|-------------|
| [arcane-backend](https://github.com/ArcaneTracing/arcane-backend) | Core backend service (TypeScript) |
| [arcane-frontend](https://github.com/ArcaneTracing/arcane-frontend) | Web application (TypeScript) |
| [arcane-worker](https://github.com/ArcaneTracing/arcane-worker) | Background worker (Python) |
| [arcane-sdks](https://github.com/ArcaneTracing/arcane-sdks) | SDKs for instrumentation (Python) |
| [arcane-deployment](https://github.com/ArcaneTracing/arcane-deployment) | Deployment configurations |

## 💭 Support

- **Documentation** — [arcanetracing.com/docs](https://arcanetracing.com/docs/intro)
- **Contact** — [contact@arcanetracing.com](mailto:contact@arcanetracing.com)
- **GitHub** — [github.com/ArcaneTracing](https://github.com/ArcaneTracing)

## Built on Open Standards. Ready for Production.

Get started for free or schedule a demo to see how Arcane can transform your GenAI observability.

[**Start Free Now**](https://arcanetracing.com/docs/intro) · [**Star on GitHub**](https://github.com/ArcaneTracing)
