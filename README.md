# api-usage-metrics-dashboard
Backstage plugin that visualizes API usage metrics (traffic, errors, latency) with dashboards and service-level insights. Built with React, TypeScript, GraphQL, Node.js, and Recharts.

# Backstage API Usage Metrics Dashboard

A Backstage plugin that visualizes API usage (traffic, error rate, latency) and highlights service-level insights for platform & CSE teams.

## 🎯 Why it matters
- Maps directly to Spotify CSE-style workflows: track adoption, spot regressions, guide partners with data.
- Shows portfolio-ready skills: Backstage plugin dev, React/TS, GraphQL schema, Node backend, CI/CD.

## 🧱 Tech Stack
Backstage • React • TypeScript • Node.js • GraphQL • Recharts • Yarn v1

## 🚀 Quick Start
```bash
# root
yarn install
yarn start
# open http://localhost:3000
Node 20 or 22, Yarn 1.22.x recommended.

🧩 Plugin Structure (planned)
plugins/api-usage/ – frontend (pages, cards, charts with Recharts)
packages/backend/ – proxy/router + data source integration
GraphQL schema for metrics: RequestsPerMin, ErrorRate, P95Latency

📊 Screens (coming soon)
Service list with key SLIs
Drill-down: time-series charts, filters (service, env, time range)

🔧 Configuration
.env.example with API endpoints and tokens (no secrets committed)
Line endings & editor: .gitattributes, .editorconfig
Node versions: .nvmrc (20.x LTS preferred)

🧪 CI
GitHub Actions: install → type-check → build (see .github/workflows/ci.yml)

📄 License
MIT

👤 Author
Minji Kim — Building portfolio-aligned Backstage plugins for CSE workflows.

.github/ISSUE_TEMPLATE/feature_request.md

.github/pull_request_template.md
