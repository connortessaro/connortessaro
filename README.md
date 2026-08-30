# Connor Tessaro

CS @ Northeastern '28 · Software Engineer Co-op @ Chewy · Boston, MA

[ringi.dev](https://ringi.dev) · [phantom.codes](https://phantom.codes) · [LinkedIn](https://linkedin.com/in/connortessaro) · tessaro.c@northeastern.edu

---

### Open source

**[prisma/orm](https://github.com/prisma/orm)** (47K stars)

DateTime fields returned `Invalid Date` for `unixepoch-ms` timestamps read through the
`better-sqlite3` driver adapter. [#29274](https://github.com/prisma/orm/pull/29274) fixes
the conversion and adds a regression test, closing
[#28890](https://github.com/prisma/orm/issues/28890).
[#29269](https://github.com/prisma/orm/pull/29269) closed
[#5509](https://github.com/prisma/orm/issues/5509), which had been open since February 2021.

---

### Building

**[Ringi](https://ringi.dev)** · `TypeScript` `Slack Bolt` `Gemini 2.5 Flash` `Drizzle` `PostgreSQL`

A Slack agent for async team decisions. It fans out DMs to each stakeholder, drives every
thread through a typed state machine, then synthesizes the positions into one brief with a
committed recommendation. Every LLM call carries Langfuse tracing for cost, latency, and
quality regressions. I benchmarked four models across Gemini, Claude, and GPT on a
fixture-graded eval harness before picking the one that writes the synthesis. 390+ tests,
3-package monorepo.

**[Phantom AI](https://phantom.codes)** · `Python` `FastAPI` `SQLCipher` `Docker`

A privacy-preserving inference gateway. Requests route through Intel TDX and NVIDIA
confidential-compute enclaves. SQLCipher encrypts data at rest, tmpfs keeps secrets in RAM
so credentials never reach disk, and token accounting stops metering the moment a client
disconnects.

**[Omni](https://github.com/connortessaro/omni)** · `Tauri v2` `Rust` `React 19`

A local-first AI desktop assistant. A HUD overlay opens anywhere with `⌘ + \`, local Ollama
models are discovered at startup, and nothing leaves the machine: keys and chats sit in
SQLite, with no telemetry and no license server. Forked from
[Pluely](https://github.com/iamsrikanthnani/pluely), GPL-3.0.

**[Kizuki](https://github.com/connortessaro/kizuki)** · `JavaScript` `MCP`

An agent-neutral intelligence layer over local workspace data. Git-tracked, MCP-native.

**[Arc](https://github.com/connortessaro/arc)** · `TypeScript`

An operator shell for orchestrating coding work. Forked from
[openclaw](https://github.com/openclaw/openclaw).

---

### Also

- **[prooflane](https://github.com/connortessaro/prooflane)** scores Shopify orders for item-not-received chargeback risk.
- **[leagueiq](https://github.com/connortessaro/leagueiq)** analyzes post-game match impact from Riot match data.
- **[shopify-web-replicator](https://github.com/connortessaro/shopify-web-replicator)** replicates storefronts deterministically, exposed as a native MCP tool.

---

### Working with

`TypeScript` `Python` `Rust` `Go` `SQL`
`React` `Next.js` `SvelteKit` `FastAPI` `Tauri`
`AWS (ECS, ECR, S3)` `Docker` `Terraform` `Jenkins`
`PostgreSQL` `Snowflake` `XGBoost` `Langfuse`
