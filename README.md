# JobForcast

AI-assisted business operating system for **Richmond Slate Repair**, a specialty historic roofing company in Richmond, VA.

Built by Wyatt Ramsey using AI as a technical co-builder to replace a manual spreadsheet-based business model.

## What It Does

- **Pipeline management** — 700+ jobs across all deal stages, real-time status
- **Financial dashboard** — Revenue, AR aging, cash flow (live QuickBooks data)
- **Client CRM** — 1,100+ contacts with full communication history
- **Job scheduling** — Calendar view with appointment management
- **Proposals** — Generate, send via email/SMS, and track acceptance
- **Job map** — Geocoded job locations across Greater Richmond
- **SMS messaging** — Two-way Twilio integration with TCPA opt-out compliance
- **Marketing analytics** — Lead source ROI, close rate by rep

## Architecture

| Layer | Technology |
|---|---|
| Frontend | Static SPA hosted on S3 + CloudFront |
| API | AWS API Gateway + Lambda (Node.js 22, ES Modules) |
| Database | PostgreSQL on Amazon RDS |
| Auth | JWT with bcrypt |

## Integrations

- **QuickBooks Online** — AR, invoices, payments, P&L (read-only)
- **Stripe** — Payment history and reconciliation
- **Twilio** — SMS send/receive with TCPA compliance
- **CompanyCam** — Job site photo sync (28,000+ photos)
- **DripJobs CRM** — Lead and appointment data

## Key Metrics (as of 2026)

- $588K revenue in 2024, $645K active pipeline (52 jobs)
- 84% close rate on qualified estimates
- 1,100+ client contacts
- 28,000+ job site photos indexed

## Live App

[app.jobforcast.com](https://app.jobforcast.com)

---

*Built with AI-assisted development. Wyatt directed architecture, product decisions, copy, and UX — AI handled code generation and implementation.*
