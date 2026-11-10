# Devansh Choudhary

Software engineer building backend systems in **C#, ASP.NET Core and SQL Server**, plus **Python/FastAPI** services. Since Aug 2025 at a B2B fintech product company: payments, bank integrations and reconciliation. B.Tech, IIT (BHU) Varanasi, 2025.

[Portfolio](https://devansh-1007.github.io) · [LinkedIn](https://www.linkedin.com/in/devansh-choudhary1007)

## Work highlights

My work code is private; these are the systems I built there.

- **Partner REST API:** scoped API keys, sliding-window rate limiting (600 requests/min per key), idempotency keys, webhooks with retry, and an OpenAPI contract enforced by a test.
- **Bank API integrations** designed so a payment is never sent twice or left stranded: write before send, idempotency keys, unknown outcomes resolved by querying the bank.
- **Statement reconciliation** for SWIFT MT940/MT942 and ISO 20022 camt formats, and payment approval controls with row locking against concurrent approvals.
- **Python/FastAPI AI service** (resume parsing, match scoring, JD generation) live in production.

## Projects

- **[loglet](https://github.com/Devansh-1007/loglet):** Kafka-style message broker in dependency-free Java. Segmented append-only log, sparse offset index, CRC32C crash recovery, single-threaded NIO event loop, zero-copy reads. 720K records/s produce, 1.01M/s consume, 21 tests.
- **[CertifyAI](https://github.com/Devansh-1007/Certificate_Generator):** live multi-tenant SaaS ([certifyai-app.vercel.app](https://certifyai-app.vercel.app)). An LLM agent designs certificate templates from natural language, gated by a 30-prompt eval harness in GitHub Actions CI; HMAC-signed QR verification; 91 pytest tests.
- **[pwsh-setup](https://github.com/Devansh-1007/pwsh-setup):** portable PowerShell 7 and Windows Terminal dev setup with one idempotent installer.

## Stack

C# · .NET · ASP.NET Core · SQL Server · Dapper · Python · FastAPI · Flask · Java · React · TypeScript · Docker · GitHub Actions · Git
