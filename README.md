### Systems that run real businesses

I own and operate a remodeling company and a tech firm. Everything here is a clean, public version of something I built first to run my own companies, with my own payroll depending on it.

**Start here:** [operator-stack](https://github.com/midcityhandyman/operator-stack) maps how two small service companies run on AI agents, and links to every repo below.

**AI agents with a human in charge**

- [send-gate](https://github.com/midcityhandyman/send-gate): no agent message leaves without a human approving the exact text
- [brain-boot-mcp](https://github.com/midcityhandyman/brain-boot-mcp): MCP server that hands an agent its rules, corrections and due items at session start
- [agent-eval-harness](https://github.com/midcityhandyman/agent-eval-harness): golden-set evals with a CI regression gate
- [correction-distiller](https://github.com/midcityhandyman/correction-distiller): turns human corrections into rules that wait for approval

**Leads, calls and messaging**

- [ai-receptionist-starter](https://github.com/midcityhandyman/ai-receptionist-starter): voice receptionist for home services
- [speed-to-lead](https://github.com/midcityhandyman/speed-to-lead): first reply to a new lead in under 60 seconds
- [missed-call-textback](https://github.com/midcityhandyman/missed-call-textback): one text back, with quiet hours and opt-out

**Automation and CRM**

- [n8n-workflow-library](https://github.com/midcityhandyman/n8n-workflow-library): ten production-grade workflows with error paths
- [webhook-reliability-kit](https://github.com/midcityhandyman/webhook-reliability-kit): idempotency, retries and an outbox, proven by a chaos test
- [crm-migration-kit](https://github.com/midcityhandyman/crm-migration-kit): dedupe, map and validate a CRM move

**Data and backend**

- [supabase-rls-cookbook](https://github.com/midcityhandyman/supabase-rls-cookbook): row level security patterns with tests
- [agent-memory-supabase](https://github.com/midcityhandyman/agent-memory-supabase): agent memory on Postgres with hybrid recall

**Construction and field operations**

- [remodel-estimator](https://github.com/midcityhandyman/remodel-estimator): scope in, takeoff and priced estimate out
- [job-costing](https://github.com/midcityhandyman/job-costing): estimate against actuals by trade
- [scope-of-work-generator](https://github.com/midcityhandyman/scope-of-work-generator): trade-by-trade scopes for bathroom, kitchen and basement remodels

Every repo runs offline on fake data, has tests, and has CI. Integrations with outside services ship with a mock so you can try them without keys.

Available for hire on Upwork: AI agents, automation, CRM builds and operations systems for service businesses.

