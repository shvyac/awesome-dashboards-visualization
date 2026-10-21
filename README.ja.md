# Awesome Dashboards & Visualization（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

**Grafana のような**オープンソースのダッシュボード・可視化ツールを集めたキュレーションリスト。監視・オブザーバビリティ、BI・データ探索、コードで作るダッシュボード、チャートライブラリ、ノーコードデータベースに分けて紹介します。

⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。

## 目次

- [オブザーバビリティ・監視ダッシュボード](#オブザーバビリティ監視ダッシュボード)
- [BI・データ探索](#biデータ探索)
- [コードで作るダッシュボード・データアプリ](#コードで作るダッシュボードデータアプリ)
- [チャートライブラリ](#チャートライブラリ)
- [ノーコードデータベース・スプレッドシート UI](#ノーコードデータベーススプレッドシート-ui)
- [アーカイブ・非アクティブ](#アーカイブ非アクティブ)
- [関連リスト](#関連リスト)
- [コントリビュート](#コントリビュート)
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

---

## オブザーバビリティ・監視ダッシュボード

メトリクス・ログ・トレース向けの Grafana 型ダッシュボード。

- [Grafana](https://grafana.com/) ![GitHub stars](https://img.shields.io/github/stars/grafana/grafana?style=flat&label=%E2%AD%90) - 比較の基準。Prometheus、Loki、Elasticsearch、InfluxDB、Postgres など多数のデータソースを組み合わせて可視化できるダッシュボード。 ([GitHub](https://github.com/grafana/grafana))
- [Perses](https://perses.dev/) ![GitHub stars](https://img.shields.io/github/stars/perses/perses?style=flat&label=%E2%AD%90) - CNCF Sandbox のダッシュボードツール。Dashboard-as-Code に対応（Prometheus、Tempo、Loki、Pyroscope）。 ([GitHub](https://github.com/perses/perses))
- [Netdata](https://www.netdata.cloud/) ![GitHub stars](https://img.shields.io/github/stars/netdata/netdata?style=flat&label=%E2%AD%90) - 設定不要で毎秒更新のリアルタイム監視。ダッシュボードと機械学習による異常検知を内蔵。 ([GitHub](https://github.com/netdata/netdata))
- [SigNoz](https://signoz.io/) ![GitHub stars](https://img.shields.io/github/stars/SigNoz/signoz?style=flat&label=%E2%AD%90) - OpenTelemetry ネイティブ。ログ・メトリクス・トレースを1つの UI で扱える（APM、ダッシュボード、アラート）。 ([GitHub](https://github.com/SigNoz/signoz))
- [OpenObserve](https://openobserve.ai/) ![GitHub stars](https://img.shields.io/github/stars/openobserve/openobserve?style=flat&label=%E2%AD%90) - シングルバイナリのオブザーバビリティ基盤（ログ・メトリクス・トレース・RUM）。ダッシュボード内蔵で Datadog／Splunk／Elastic の代替。 ([GitHub](https://github.com/openobserve/openobserve))
- [Kibana](https://www.elastic.co/kibana) ![GitHub stars](https://img.shields.io/github/stars/elastic/kibana?style=flat&label=%E2%AD%90) - Elasticsearch のデータ向け可視化・ダッシュボード。 ([GitHub](https://github.com/elastic/kibana))
- [OpenSearch Dashboards](https://docs.opensearch.org/latest/dashboards/) ![GitHub stars](https://img.shields.io/github/stars/opensearch-project/OpenSearch-Dashboards?style=flat&label=%E2%AD%90) - OpenSearch 用のオープンソース可視化 UI（Kibana から派生した Apache 2.0 版）。 ([GitHub](https://github.com/opensearch-project/OpenSearch-Dashboards))
- [HyperDX](https://www.hyperdx.io/) ![GitHub stars](https://img.shields.io/github/stars/hyperdxio/hyperdx?style=flat&label=%E2%AD%90) - ClickHouse と OpenTelemetry ベースのオブザーバビリティ。ログ・メトリクス・トレース・セッションリプレイ・ダッシュボード。現在は ClickHouse 傘下。 ([GitHub](https://github.com/hyperdxio/hyperdx))
- [Coroot](https://coroot.com/) ![GitHub stars](https://img.shields.io/github/stars/coroot/coroot?style=flat&label=%E2%AD%90) - eBPF ベースの APM。定義済みダッシュボード、SLO アラート、AI による根本原因分析。 ([GitHub](https://github.com/coroot/coroot))
- [Apache SkyWalking](https://skywalking.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/skywalking?style=flat&label=%E2%AD%90) - トポロジーマップとダッシュボードを備えた APM・分散トレーシング。 ([GitHub](https://github.com/apache/skywalking))
- [Apache HertzBeat](https://hertzbeat.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/hertzbeat?style=flat&label=%E2%AD%90) - エージェント不要のリアルタイム監視。ダッシュボード、アラート、ステータスページ付き。 ([GitHub](https://github.com/apache/hertzbeat))
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) ![GitHub stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat&label=%E2%AD%90) - セルフホストの死活監視。見やすいダッシュボードと公開ステータスページ。

---

## BI・データ探索

DB に接続し、SQL かクリック操作でグラフを作ってダッシュボードを共有するツール。

- [Apache Superset](https://superset.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/superset?style=flat&label=%E2%AD%90) - 本格的なオープンソース BI。SQL Lab、40 種類以上のチャート、主要 SQL DB 向けダッシュボード。 ([GitHub](https://github.com/apache/superset))
- [Metabase](https://www.metabase.com/) ![GitHub stars](https://img.shields.io/github/stars/metabase/metabase?style=flat&label=%E2%AD%90) - 使いやすさ重視の BI と埋め込み分析。SQL を書かない人向けのクエリビルダー付き。 ([GitHub](https://github.com/metabase/metabase))
- [Redash](https://redash.io/) ![GitHub stars](https://img.shields.io/github/stars/getredash/redash?style=flat&label=%E2%AD%90) - SQL を書いて結果を可視化し、共有ダッシュボードにまとめる。 ([GitHub](https://github.com/getredash/redash))
- [DataEase](https://dataease.io/) ![GitHub stars](https://img.shields.io/github/stars/dataease/dataease?style=flat&label=%E2%AD%90) - Tableau の代替を目指すオープンソース BI（ECharts ベース、中国で普及）。 ([GitHub](https://github.com/dataease/dataease))
- [Lightdash](https://www.lightdash.com/) ![GitHub stars](https://img.shields.io/github/stars/lightdash/lightdash?style=flat&label=%E2%AD%90) - dbt プロジェクトの上に構築する BI。メトリクスをコードで定義。 ([GitHub](https://github.com/lightdash/lightdash))
- [Rill](https://www.rilldata.com/) ![GitHub stars](https://img.shields.io/github/stars/rilldata/rill?style=flat&label=%E2%AD%90) - DuckDB／ClickHouse で動く高速 BI。ダッシュボードをコードで定義。 ([GitHub](https://github.com/rilldata/rill))
- [Chartbrew](https://chartbrew.com/) ![GitHub stars](https://img.shields.io/github/stars/chartbrew/chartbrew?style=flat&label=%E2%AD%90) - API、SQL、NoSQL DB からライブダッシュボードやレポートを作成。 ([GitHub](https://github.com/chartbrew/chartbrew))

---

## コードで作るダッシュボード・データアプリ

GUI ではなく Python・SQL・Markdown でダッシュボードを作るフレームワーク。

- [Streamlit](https://streamlit.io/) ![GitHub stars](https://img.shields.io/github/stars/streamlit/streamlit?style=flat&label=%E2%AD%90) - Python スクリプトを数分で共有可能なデータアプリにする（Snowflake 傘下）。 ([GitHub](https://github.com/streamlit/streamlit))
- [Dash](https://dash.plotly.com/) ![GitHub stars](https://img.shields.io/github/stars/plotly/dash?style=flat&label=%E2%AD%90) - Plotly.js と React ベースの Python 分析ダッシュボードフレームワーク。 ([GitHub](https://github.com/plotly/dash))
- [Vizro](https://vizro.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/mckinsey/vizro?style=flat&label=%E2%AD%90) - McKinsey 製のローコードツールキット。設定ファイルで Dash ベースのダッシュボードを作成。 ([GitHub](https://github.com/mckinsey/vizro))
- [H2O Wave](https://wave.h2o.ai/) ![GitHub stars](https://img.shields.io/github/stars/h2oai/wave?style=flat&label=%E2%AD%90) - Python または R だけでリアルタイム Web アプリとダッシュボードを作成。 ([GitHub](https://github.com/h2oai/wave))
- [Evidence](https://evidence.dev/) ![GitHub stars](https://img.shields.io/github/stars/evidence-dev/evidence?style=flat&label=%E2%AD%90) - BI-as-code。SQL と Markdown でレポートやダッシュボードを作る。 ([GitHub](https://github.com/evidence-dev/evidence))
- [Observable Framework](https://observablehq.github.io/framework/) ![GitHub stars](https://img.shields.io/github/stars/observablehq/framework?style=flat&label=%E2%AD%90) - データアプリ・ダッシュボード向けの静的サイトジェネレーター（フロントは JavaScript、データ取得は任意の言語）。 ([GitHub](https://github.com/observablehq/framework))
- [Briefer](https://briefer.cloud/) ![GitHub stars](https://img.shields.io/github/stars/briefercloud/briefer?style=flat&label=%E2%AD%90) - Notion 風のノートブックとダッシュボードを一体化（SQL＋Python）。 ([GitHub](https://github.com/briefercloud/briefer))

---

## チャートライブラリ

独自の可視化を作るための部品。

- [D3.js](https://d3js.org/) ![GitHub stars](https://img.shields.io/github/stars/d3/d3?style=flat&label=%E2%AD%90) - SVG、Canvas、HTML で自由な可視化を作るための低レベルな基盤。 ([GitHub](https://github.com/d3/d3))
- [Apache ECharts](https://echarts.apache.org/) ![GitHub stars](https://img.shields.io/github/stars/apache/echarts?style=flat&label=%E2%AD%90) - 豊富なチャート種類を持つ高機能なインタラクティブチャートライブラリ。 ([GitHub](https://github.com/apache/echarts))
- [Chart.js](https://www.chartjs.org/) ![GitHub stars](https://img.shields.io/github/stars/chartjs/Chart.js?style=flat&label=%E2%AD%90) - シンプルで軽量な HTML5 Canvas チャート。 ([GitHub](https://github.com/chartjs/Chart.js))
- [Plotly.js](https://plotly.com/javascript/) ![GitHub stars](https://img.shields.io/github/stars/plotly/plotly.js?style=flat&label=%E2%AD%90) - Plotly と Dash の中核となるチャートライブラリ。大量データには WebGL を使用。 ([GitHub](https://github.com/plotly/plotly.js))
- [Plotly.py](https://plotly.com/python/) ![GitHub stars](https://img.shields.io/github/stars/plotly/plotly.py?style=flat&label=%E2%AD%90) - Python・Jupyter 向けインタラクティブグラフライブラリ。 ([GitHub](https://github.com/plotly/plotly.py))
- [Recharts](https://recharts.github.io/) ![GitHub stars](https://img.shields.io/github/stars/recharts/recharts?style=flat&label=%E2%AD%90) - D3 ベースの React 用チャートコンポーネント。 ([GitHub](https://github.com/recharts/recharts))
- [Vega-Lite](https://vega.github.io/vega-lite/) ![GitHub stars](https://img.shields.io/github/stars/vega/vega-lite?style=flat&label=%E2%AD%90) - インタラクティブなグラフを簡潔な JSON 文法で記述。 ([GitHub](https://github.com/vega/vega-lite))

---

## ノーコードデータベース・スプレッドシート UI

データベースのテーブルをスプレッドシート感覚で閲覧・編集できるツール。ビュー、フォーム、自動生成 API に加え、AI アシスタントからデータを検索・更新できる MCP サーバーを備えるものが増えている。

- [NocoDB](https://nocodb.com/) ![GitHub stars](https://img.shields.io/github/stars/nocodb/nocodb?style=flat&label=%E2%AD%90) - 新規または既存の PostgreSQL / MySQL / SQL Server をスプレッドシート UI で扱える。グリッド・フォーム・カンバン・カレンダー・ガントのビュー、ダッシュボード、REST API、MCP サーバーを内蔵（Community Edition はレコード操作ツールのみ）。 ([GitHub](https://github.com/nocodb/nocodb))
- [Baserow](https://baserow.io/) ![GitHub stars](https://img.shields.io/github/stars/baserow/baserow?style=flat&label=%E2%AD%90) - PostgreSQL ベースのオープンソース Airtable 代替。アプリビルダー、オートメーション、ダッシュボード、MCP サーバーを内蔵。 ([GitHub](https://github.com/baserow/baserow))
- [Teable](https://teable.ai/) ![GitHub stars](https://img.shields.io/github/stars/teableio/teable?style=flat&label=%E2%AD%90) - 大規模テーブルに強い PostgreSQL ネイティブの「AI スプレッドシート」。AI エージェントとアプリビルダー付き。 ([GitHub](https://github.com/teableio/teable))
- [NocoBase](https://www.nocobase.com/) ![GitHub stars](https://img.shields.io/github/stars/nocobase/nocobase?style=flat&label=%E2%AD%90) - 手元のデータ上に業務システム（CRM・ERP・社内ツール）を組み立てる、プラグイン型の AI + ノーコード基盤。 ([GitHub](https://github.com/nocobase/nocobase))
- [Directus](https://directus.io/) ![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=flat&label=%E2%AD%90) - 任意の SQL データベースから REST / GraphQL API と管理画面（Insights ダッシュボード付き）を即座に生成。 ([GitHub](https://github.com/directus/directus))
- [Grist](https://www.getgrist.com/) ![GitHub stars](https://img.shields.io/github/stars/gristlabs/grist-core?style=flat&label=%E2%AD%90) - Python 数式、連動ウィジェット、チャートを備えたリレーショナル・スプレッドシート。grist-core でセルフホスト可能。 ([GitHub](https://github.com/gristlabs/grist-core))
- [APITable](https://apitable.com/) ![GitHub stars](https://img.shields.io/github/stars/apitable/apitable?style=flat&label=%E2%AD%90) - API 指向のコラボレーション型データベース。ビューを埋め込み可能（ホスト版は AITable.ai）。 ([GitHub](https://github.com/apitable/apitable))

---

## アーカイブ・非アクティブ

参考として残しているが、メンテナンスは終了。

- [Hygieia](https://github.com/hygieia/hygieia) ![GitHub stars](https://img.shields.io/github/stars/hygieia/hygieia?style=flat&label=%E2%AD%90) - Capital One 製の DevOps パイプラインダッシュボード（アーカイブ済み）。

---

## 関連リスト

- [hal9ai/awesome-dataviz](https://github.com/hal9ai/awesome-dataviz) ![GitHub stars](https://img.shields.io/github/stars/hal9ai/awesome-dataviz?style=flat&label=%E2%AD%90) - データ可視化ライブラリとリソース。
- [thenaturalist/awesome-business-intelligence](https://github.com/thenaturalist/awesome-business-intelligence) ![GitHub stars](https://img.shields.io/github/stars/thenaturalist/awesome-business-intelligence?style=flat&label=%E2%AD%90) - BI ツール。
- [adriannovegil/awesome-observability](https://github.com/adriannovegil/awesome-observability) ![GitHub stars](https://img.shields.io/github/stars/adriannovegil/awesome-observability?style=flat&label=%E2%AD%90) - オブザーバビリティのツールとリソース。
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) ![GitHub stars](https://img.shields.io/github/stars/awesome-selfhosted/awesome-selfhosted?style=flat&label=%E2%AD%90) - セルフホスト可能なソフトウェア全般。
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - Awesome リストのメタリスト。

---

## コントリビュート

追加・リンク切れ修正・カテゴリ提案などのプルリクエストを歓迎します。

**公式／プロジェクトの恒久的な URL**、短い説明、活発にメンテナンスされているオープンソースプロジェクトを優先してください。GitHub プロジェクトには ⭐ バッジを付け、アーカイブ済みのものは注記してください。可能なら `README.md` と `README.ja.md` の両方を更新してください。

---

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

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
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
