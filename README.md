# Awesome Dashboards & Visualization

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of open-source dashboard and data-visualization tools **like Grafana** — observability and monitoring, BI and data exploration, dashboards as code, charting libraries, and no-code databases.

⭐ badges show live GitHub star counts (via shields.io); release badges show the date of the latest GitHub release (YYYY/MM/DD, as of the last refresh); last-commit badges show live commit activity (via shields.io).

## Contents

- [Observability & monitoring dashboards](#observability--monitoring-dashboards)
- [BI & data exploration](#bi--data-exploration)
- [Dashboards as code & data apps](#dashboards-as-code--data-apps)
- [Charting libraries](#charting-libraries)
- [No-code databases & spreadsheet UIs](#no-code-databases--spreadsheet-uis)
- [Archived / inactive](#archived--inactive)
- [Related lists](#related-lists)
- [Contributing](#contributing)
- [shvyac's awesome lists](#shvyacs-awesome-lists)

---

## Observability & monitoring dashboards

Grafana-style dashboards for metrics, logs, and traces.

- [Grafana](https://grafana.com/) ![GitHub stars](https://img.shields.io/github/stars/grafana/grafana?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F27-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/grafana/grafana?style=flat) - The reference point: composable dashboards over Prometheus, Loki, Elasticsearch, InfluxDB, Postgres, and many more data sources. ([GitHub](https://github.com/grafana/grafana))
- [Perses](https://perses.dev/) ![GitHub stars](https://img.shields.io/github/stars/perses/perses?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F21-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/perses/perses?style=flat) - CNCF sandbox dashboard tool with dashboards-as-code (Prometheus, Tempo, Loki, Pyroscope). ([GitHub](https://github.com/perses/perses))
- [Netdata](https://www.netdata.cloud/) ![GitHub stars](https://img.shields.io/github/stars/netdata/netdata?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F23-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/netdata/netdata?style=flat) - Zero-config, per-second real-time monitoring with built-in dashboards and ML anomaly detection. ([GitHub](https://github.com/netdata/netdata))
- [SigNoz](https://signoz.io/) ![GitHub stars](https://img.shields.io/github/stars/SigNoz/signoz?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/SigNoz/signoz?style=flat) - OpenTelemetry-native platform for logs, metrics, and traces in one UI (APM, dashboards, alerts), plus a SigNoz MCP server for AI agents. ([GitHub](https://github.com/SigNoz/signoz))
- [OpenObserve](https://openobserve.ai/) ![GitHub stars](https://img.shields.io/github/stars/openobserve/openobserve?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F20-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/openobserve/openobserve?style=flat) - Single-binary observability platform (logs, metrics, traces, RUM) with built-in dashboards; Datadog / Splunk / Elastic alternative. ([GitHub](https://github.com/openobserve/openobserve))
- [Kibana](https://www.elastic.co/kibana) ![GitHub stars](https://img.shields.io/github/stars/elastic/kibana?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F06-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/elastic/kibana?style=flat) - Visualization and dashboards for Elasticsearch data. ([GitHub](https://github.com/elastic/kibana))
- [OpenSearch Dashboards](https://docs.opensearch.org/latest/dashboards/) ![GitHub stars](https://img.shields.io/github/stars/opensearch-project/OpenSearch-Dashboards?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F12-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/opensearch-project/OpenSearch-Dashboards?style=flat) - Open-source visualization UI for OpenSearch (Apache 2.0 fork of Kibana). ([GitHub](https://github.com/opensearch-project/OpenSearch-Dashboards))
- [HyperDX](https://www.hyperdx.io/) ![GitHub stars](https://img.shields.io/github/stars/hyperdxio/hyperdx?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F01-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/hyperdxio/hyperdx?style=flat) - ClickHouse + OpenTelemetry observability: logs, metrics, traces, session replay, and dashboards. Now part of ClickHouse. ([GitHub](https://github.com/hyperdxio/hyperdx))
- [Uptrace](https://uptrace.dev/) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/uptrace/uptrace?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/uptrace/uptrace?style=flat) - OpenTelemetry-native APM on ClickHouse: traces, metrics, and logs with dashboards and alerts; self-hosted or cloud. ([GitHub](https://github.com/uptrace/uptrace))
- [Coroot](https://coroot.com/) ![GitHub stars](https://img.shields.io/github/stars/coroot/coroot?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F30-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/coroot/coroot?style=flat) - eBPF-based APM with predefined dashboards, SLO alerting, and AI root-cause analysis. ([GitHub](https://github.com/coroot/coroot))
- [Apache SkyWalking](https://skywalking.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/skywalking?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F08%2F28-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/apache/skywalking?style=flat) - APM and distributed tracing with topology maps and dashboards. ([GitHub](https://github.com/apache/skywalking))
- [Apache HertzBeat](https://hertzbeat.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/hertzbeat?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F13-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/apache/hertzbeat?style=flat) - Agentless real-time monitoring with dashboards, alerting, and status pages. ([GitHub](https://github.com/apache/hertzbeat))
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) ![GitHub stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F31-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/louislam/uptime-kuma?style=flat) - Self-hosted uptime monitoring with a clean dashboard and public status pages.

---

## BI & data exploration

Connect a database, write SQL or point-and-click, and share dashboards.

- [Apache Superset](https://superset.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/superset?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F05%2F13-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/apache/superset?style=flat) - Full-featured open-source BI: SQL Lab, 40+ chart types, and dashboards over most SQL databases. ([GitHub](https://github.com/apache/superset))
- [Metabase](https://www.metabase.com/) ![GitHub stars](https://img.shields.io/github/stars/metabase/metabase?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F30-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/metabase/metabase?style=flat) - Easy-to-use BI and embedded analytics; question builder for non-SQL users. ([GitHub](https://github.com/metabase/metabase))
- [Redash](https://redash.io/) ![GitHub stars](https://img.shields.io/github/stars/getredash/redash?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F24-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/getredash/redash?style=flat) - Write SQL queries, visualize results, and assemble shareable dashboards. ([GitHub](https://github.com/getredash/redash))
- [DataEase](https://dataease.io/) ![GitHub stars](https://img.shields.io/github/stars/dataease/dataease?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/dataease/dataease?style=flat) - Open-source BI positioned as a Tableau alternative (ECharts-based, popular in China). ([GitHub](https://github.com/dataease/dataease))
- [Lightdash](https://www.lightdash.com/) ![GitHub stars](https://img.shields.io/github/stars/lightdash/lightdash?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F31-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/lightdash/lightdash?style=flat) - Agentic BI on top of your dbt project; metrics defined in code, with AI agents for self-serve analytics. ([GitHub](https://github.com/lightdash/lightdash))
- [Rill](https://www.rilldata.com/) ![GitHub stars](https://img.shields.io/github/stars/rilldata/rill?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/rilldata/rill?style=flat) - Fast DuckDB / ClickHouse-powered BI dashboards defined as code, built for both humans and AI agents. ([GitHub](https://github.com/rilldata/rill))
- [Wren AI](https://getwren.ai/) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/Canner/WrenAI?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F30-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/Canner/WrenAI?style=flat) - GenBI agent: natural-language questions to governed SQL, charts, and dashboards over 20+ data sources via a semantic/context layer, with MCP access. ([GitHub](https://github.com/Canner/WrenAI))
- [Chartbrew](https://chartbrew.com/) ![GitHub stars](https://img.shields.io/github/stars/chartbrew/chartbrew?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F20-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/chartbrew/chartbrew?style=flat) - Live dashboards and client reports from APIs, SQL, and NoSQL databases. ([GitHub](https://github.com/chartbrew/chartbrew))

---

## Dashboards as code & data apps

Build dashboards with Python, SQL, or Markdown instead of a GUI.

- [Streamlit](https://streamlit.io/) ![GitHub stars](https://img.shields.io/github/stars/streamlit/streamlit?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F21-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/streamlit/streamlit?style=flat) - Turn Python scripts into shareable data apps in minutes (part of Snowflake). ([GitHub](https://github.com/streamlit/streamlit))
- [Dash](https://dash.plotly.com/) ![GitHub stars](https://img.shields.io/github/stars/plotly/dash?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/plotly/dash?style=flat) - Python framework for analytical dashboards built on Plotly.js and React. ([GitHub](https://github.com/plotly/dash))
- [Panel](https://panel.holoviz.org/) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/holoviz/panel?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F23-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/holoviz/panel?style=flat) - HoloViz data-exploration and web-app framework for Python; dashboards from Bokeh, Plotly, Matplotlib, and Jupyter notebooks. ([GitHub](https://github.com/holoviz/panel))
- [Vizro](https://vizro.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/mckinsey/vizro?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F20-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/mckinsey/vizro?style=flat) - Low-code toolkit (by McKinsey) for Dash-based dashboards via config; reached v1.0 in 2026. ([GitHub](https://github.com/mckinsey/vizro))
- [H2O Wave](https://wave.h2o.ai/) ![GitHub stars](https://img.shields.io/github/stars/h2oai/wave?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/h2oai/wave?style=flat) - Realtime web apps and dashboards in pure Python or R. ([GitHub](https://github.com/h2oai/wave))
- [Evidence](https://evidence.dev/) ![GitHub stars](https://img.shields.io/github/stars/evidence-dev/evidence?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F02%2F06-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/evidence-dev/evidence?style=flat) - BI as code: reports and dashboards from SQL + Markdown. ([GitHub](https://github.com/evidence-dev/evidence))
- [Observable Framework](https://observablehq.github.io/framework/) ![GitHub stars](https://img.shields.io/github/stars/observablehq/framework?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F03%2F02-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/observablehq/framework?style=flat) - Static-site generator for data apps and dashboards (JavaScript front end, any-language data loaders). ([GitHub](https://github.com/observablehq/framework))
- [Briefer](https://briefer.cloud/) ![GitHub stars](https://img.shields.io/github/stars/briefercloud/briefer?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/briefercloud/briefer?style=flat) - Notion-like notebooks and dashboards in one place (SQL + Python). ([GitHub](https://github.com/briefercloud/briefer))

---

## Charting libraries

Building blocks for custom visualizations.

- [D3.js](https://d3js.org/) ![GitHub stars](https://img.shields.io/github/stars/d3/d3?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2024%2F03%2F12-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/d3/d3?style=flat) - The low-level foundation for bespoke data visualization with SVG, Canvas, and HTML. ([GitHub](https://github.com/d3/d3))
- [Apache ECharts](https://echarts.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/echarts?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F05%2F19-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/apache/echarts?style=flat) - Powerful interactive charting library with a huge chart catalog. ([GitHub](https://github.com/apache/echarts))
- [Chart.js](https://www.chartjs.org/) ![GitHub stars](https://img.shields.io/github/stars/chartjs/Chart.js?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/chartjs/Chart.js?style=flat) - Simple, lightweight HTML5 canvas charts. ([GitHub](https://github.com/chartjs/Chart.js))
- [uPlot](https://github.com/leeoniya/uPlot) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/leeoniya/uPlot?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2025%2F03%2F14-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/leeoniya/uPlot?style=flat) - Small, very fast Canvas chart for time series, lines, areas, OHLC, and bars; handles large datasets with a tiny footprint.
- [Plotly.js](https://plotly.com/javascript/) ![GitHub stars](https://img.shields.io/github/stars/plotly/plotly.js?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/plotly/plotly.js?style=flat) - Interactive charting library behind Plotly and Dash; WebGL for large data. ([GitHub](https://github.com/plotly/plotly.js))
- [Plotly.py](https://plotly.com/python/) ![GitHub stars](https://img.shields.io/github/stars/plotly/plotly.py?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F15-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/plotly/plotly.py?style=flat) - Interactive graphing library for Python and Jupyter. ([GitHub](https://github.com/plotly/plotly.py))
- [Recharts](https://recharts.github.io/) ![GitHub stars](https://img.shields.io/github/stars/recharts/recharts?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F07%2F25-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/recharts/recharts?style=flat) - Composable chart components for React, built on D3. ([GitHub](https://github.com/recharts/recharts))
- [Vega-Lite](https://vega.github.io/vega-lite/) ![GitHub stars](https://img.shields.io/github/stars/vega/vega-lite?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F08-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/vega/vega-lite?style=flat) - Concise JSON grammar of interactive graphics. ([GitHub](https://github.com/vega/vega-lite))

---

## No-code databases & spreadsheet UIs

Browse and edit database tables in a spreadsheet-like UI, with views, forms, auto-generated APIs, and increasingly an MCP server so AI assistants can query and update the data.

- [NocoDB](https://nocodb.com/) ![GitHub stars](https://img.shields.io/github/stars/nocodb/nocodb?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/nocodb/nocodb?style=flat) - Spreadsheet UI over new or existing PostgreSQL / MySQL / SQL Server databases; grid, form, kanban, calendar and Gantt views, dashboards, REST APIs, and a built-in MCP server (record tools in the Community Edition). ([GitHub](https://github.com/nocodb/nocodb))
- [Baserow](https://baserow.io/) ![GitHub stars](https://img.shields.io/github/stars/baserow/baserow?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F13-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/baserow/baserow?style=flat) - Open-source Airtable alternative on PostgreSQL with an application builder, automations, dashboards, and a built-in MCP server. ([GitHub](https://github.com/baserow/baserow))
- [Teable](https://teable.ai/) ![GitHub stars](https://img.shields.io/github/stars/teableio/teable?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F01-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/teableio/teable?style=flat) - PostgreSQL-native "AI spreadsheet" built for large tables, with an AI agent and app builder. ([GitHub](https://github.com/teableio/teable))
- [NocoBase](https://www.nocobase.com/) ![GitHub stars](https://img.shields.io/github/stars/nocobase/nocobase?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F31-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/nocobase/nocobase?style=flat) - Plugin-based AI + no-code platform for building business systems (CRM, ERP, internal tools) on your data. ([GitHub](https://github.com/nocobase/nocobase))
- [Directus](https://directus.io/) ![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F27-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/directus/directus?style=flat) - Turns any SQL database into instant REST/GraphQL APIs plus an admin app with insights dashboards. ([GitHub](https://github.com/directus/directus))
- [Grist](https://www.getgrist.com/) ![GitHub stars](https://img.shields.io/github/stars/gristlabs/grist-core?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F29-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/gristlabs/grist-core?style=flat) - Relational spreadsheet with Python formulas, linked widgets, and charts; self-hostable grist-core. ([GitHub](https://github.com/gristlabs/grist-core))
- [APITable](https://apitable.com/) ![GitHub stars](https://img.shields.io/github/stars/apitable/apitable?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F06-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/apitable/apitable?style=flat) - API-oriented collaborative database with embeddable views (AITable.ai is the hosted service). ([GitHub](https://github.com/apitable/apitable))

---

## Archived / inactive

Kept for reference; no longer maintained.

- [Hygieia](https://github.com/hygieia/hygieia) ![GitHub stars](https://img.shields.io/github/stars/hygieia/hygieia?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2019%2F09%2F09-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/hygieia/hygieia?style=flat) - Capital One's DevOps pipeline dashboard (archived).

---

## Related lists

- [hal9ai/awesome-dataviz](https://github.com/hal9ai/awesome-dataviz) ![GitHub stars](https://img.shields.io/github/stars/hal9ai/awesome-dataviz?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/hal9ai/awesome-dataviz?style=flat) - Data visualization libraries and resources.
- [thenaturalist/awesome-business-intelligence](https://github.com/thenaturalist/awesome-business-intelligence) ![GitHub stars](https://img.shields.io/github/stars/thenaturalist/awesome-business-intelligence?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/thenaturalist/awesome-business-intelligence?style=flat) - BI tools.
- [adriannovegil/awesome-observability](https://github.com/adriannovegil/awesome-observability) ![GitHub stars](https://img.shields.io/github/stars/adriannovegil/awesome-observability?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/adriannovegil/awesome-observability?style=flat) - Observability tools and resources.
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) ![GitHub stars](https://img.shields.io/github/stars/awesome-selfhosted/awesome-selfhosted?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2023%2F08%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/awesome-selfhosted/awesome-selfhosted?style=flat) - Self-hosted software in general.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sindresorhus/awesome?style=flat) - The Awesome meta-list.

---

## Contributing

Contributions welcome — open a pull request to add a tool, fix a broken link, or suggest a category.

Prefer **durable official / project URLs**, short blurbs, and actively maintained open-source projects. Add a ⭐ star badge for GitHub projects and note when a project is archived. Update both `README.md` and `README.ja.md` when you can.

---

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-mcp-ai](https://github.com/shvyac/awesome-mcp-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-mcp-ai?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-quantum](https://github.com/shvyac/awesome-quantum) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-quantum?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
