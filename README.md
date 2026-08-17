## Connor Tessaro

CS @ Northeastern, May 2028. Currently a Software Engineer Co-op at Chewy on the Order Routing Simulation team, working on the labor and capacity planning platform behind 12 fulfillment centers — containerized ML pipelines on ECS, Terraform and Jenkins for releases, and a Next.js dashboard FC managers use to override forecasts.

Outside of that I ship products. Most of the source is private, so the links go to the live thing.

### Products

**[Ringi](https://ringi.dev)** — a Slack agent that replaces the status meeting. It DMs each stakeholder, extracts their position with an LLM, and synthesizes a brief that isolates the actual crux and commits to a recommendation. TypeScript, Slack Bolt, Gemini, Drizzle/Postgres, with Langfuse tracing on every model call.

**[Phantom AI](https://phantom.codes)** — an anonymous AI inference proxy. Pay in crypto, get an OpenAI-compatible key. Requests route through Intel TDX and NVIDIA confidential-compute enclaves, secrets load into tmpfs so they never touch disk, and token accounting stops billing the instant a client disconnects. Sanitized source: [phantom-api](https://github.com/connortessaro/phantom-api).

**Harbor** — a lending marketplace. Real-time lead routing across branching eligibility constraints, a sequential buyer waterfall with pricing floors and bid-driven retries, and fraud screening before submit.

### Public repos

- [prooflane](https://github.com/connortessaro/prooflane) — embedded Shopify app that scores orders for "item not received" chargeback risk and opens intervention cases before they hit
- [shopify-web-replicator](https://github.com/connortessaro/shopify-web-replicator) — deterministic Shopify storefront replication, exposed as an MCP server for local agent workflows
- [slr-citation-audit](https://github.com/connortessaro/slr-citation-audit) — citation coverage analysis for systematic literature reviews in the technical debt subfield
- [leagueiq](https://github.com/connortessaro/leagueiq) — rules-based post-game match impact analysis over Riot match and timeline data
- [resume-review-engine](https://github.com/connortessaro/resume-review-engine) — full-resume analysis and rewrite with structured feedback

### Stack

TypeScript, Python, Java, C++, SQL · React, Next.js, SvelteKit, Node.js, FastAPI · Postgres, Snowflake, Drizzle, XGBoost · AWS (ECS, ECR, Lambda, S3), Terraform, Docker, Jenkins

tessaro.c@northeastern.edu · [LinkedIn](https://linkedin.com/in/connortessaro)
