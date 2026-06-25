## André Ahlert

Staff Product Engineer and Architect for AI infrastructure and developer experience. Go and Python, with TypeScript and Rust where the work demands it. I ship small, focused, self-contained software, while mentoring fellow engineers.

### Featured

[**Kilnx**](https://github.com/kilnx-org/kilnx) is an htmx-native backend language. A full compiler pipeline in Go (~19K LOC) with SQL-aware static type inference, security analyzer, query optimizer, and LSP server. The runtime ships embedded SQLite, RBAC, WebSockets, and background jobs. Compiles a full web app to a single ~15MB binary. Apache 2.0.

**[Tessera](https://github.com/andreahlert/tessera)** is a miniature control plane in Rust. Schedules workloads across a fleet of nodes with declarative reconciliation, control/data plane split, and an explicit workload state machine. Built on Dropshot.

**[Provero](https://github.com/provero-org/provero)** is a declarative data quality engine on PyPI. One check definition runs across PostgreSQL, DuckDB, and SQLite. 16 check types, SodaCL import, dbt test export. Continuous monitoring mode with CLI and YAML workflow.

[**Sprite-Warden**](https://github.com/andreahlert/sprite-warden) is a capability-bound microVM orchestrator for single-session agents. Signed passports bound to VM lifecycle, atomic revocation on migration, full capability-use trace. Part of an agent safety stack with [Belltower](https://github.com/andreahlert/belltower) (hypermedia coordination kernel for multi-agent workflows) and [Cordon](https://github.com/andreahlert/cordon) (capability-based containment).

[**htmx-devtools**](https://github.com/atoolz/htmx-devtools) is a Chrome DevTools panel for debugging htmx apps: request inspection, swap monitoring, event tracing. Sibling project **[htmx-vscode-toolkit](https://github.com/atoolz/htmx-vscode-toolkit)** ships IntelliSense, hover docs, validation, and snippets for htmx across 20+ template languages.

### Currently shipping

[**AToolZ**](https://github.com/atoolz) is a developer tooling collective covering CLIs ([picocrawl](https://github.com/atoolz/picocrawl), [terraxi](https://github.com/atoolz/terraxi), [turnis](https://github.com/atoolz/turnis), [tabra](https://github.com/atoolz/tabra), [telvar](https://github.com/atoolz/telvar)), MCP servers ([flyte-mcp](https://github.com/atoolz/flyte-mcp)), LSP servers ([kitty-lsp-toolkit](https://github.com/atoolz/kitty-lsp-toolkit)), and AI agent tooling ([scope-guard](https://github.com/atoolz/scope-guard), [oss-kb](https://github.com/atoolz/oss-kb)).

[**PostCLI**](https://github.com/postcli) is publishing tools for humans and AI agents. Each platform ships as a CLI and an MCP server in the same codebase, so terminals and coding agents drive the same backend ([substack](https://github.com/postcli/substack), [slack](https://github.com/postcli/slack), [hackernews](https://github.com/postcli/hackernews)).

### Writing

[Daily Punch List](https://dailypunchlist.substack.com/), [substack.com/@ahlert](https://substack.com/@ahlert).

### Open source

Contributor at [Apache Airflow](https://github.com/apache/airflow), [Backstage](https://github.com/backstage/backstage), [Burr](https://github.com/DAGWorks-Inc/burr), [Flyte SDK](https://github.com/flyteorg/flyte-sdk), [Jenkins](https://github.com/jenkinsci), [htmx](https://github.com/bigskysoftware/htmx), and [_hyperscript](https://github.com/bigskysoftware/_hyperscript).

Plugin maintainer of [Jenkins Authorize Project](https://github.com/jenkinsci/authorize-project-plugin) and the [Backstage N8N community plugin](https://github.com/backstage/community-plugins/tree/main/workspaces/n8n).

### Production track record

Backend, data infrastructure, and developer tooling for finance, energy, oil and gas, retail, and manufacturing. 2M+ daily transactions on Go services with p99 cut 60%. 50K events per second from industrial telemetry. Dashboards from 12s to 180ms. ERP migrations from 3 days to 6 hours. Multi-tenant APIs sustaining p99 90ms across 40+ tenants at 3K QPS.

### Stack

Go, Python, TypeScript, Rust, SQL. PostgreSQL, SQLite, DuckDB, Redis. Kubernetes, Docker, bare-metal Linux, AWS. LSP, MCP, compiler design.

### Reach me

[LinkedIn](https://linkedin.com/in/ahlert), andre@aex.partners.
