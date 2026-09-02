# Frederick Akam

Software engineer in Kaduna, Nigeria (UTC+1). Ten years in software, the last four building production web platforms end to end, usually as the only developer: schema, backend, interface, deployment, and the operational tooling around them.

Most of my repositories here are private because the code is commercial or belongs to a client. The systems themselves are live, so the quickest way to check the work is to open one.

Available for remote contract and full-time work. **akamfrederick@gmail.com**

---

## Live systems

### [PropInfo](https://propinfo.com.au)
Multi-tenant SaaS for Australian buyer's agents. Generates pre-purchase property assessments with the Claude API against comparable sales, computes state-specific stamp duty and lenders mortgage insurance, projects thirty years of yield, cash flow and depreciation, and tracks a client from first enquiry to settlement. Role-based access across shared agency workspaces.

`Next.js` `TypeScript` `Supabase` `Postgres` `Claude API`

### [ProForge](https://proforge.com.au)
AI phone receptionist for Australian trade businesses. Answers in an Australian voice at any hour, qualifies the caller, books the job into the calendar, texts a confirmation, follows up quotes, and routes genuine emergencies straight to the operator. Operators run the business from a separate dashboard app.

`Next.js` `TypeScript` `Supabase` `n8n` `Twilio` `Vapi`

### [iventicks](https://eventicket-psi.vercel.app)
Event ticketing across 95 server-side endpoints. Payments, fraud detection on purchase patterns, refunds, bulk event cancellation with money owed back to hundreds of holders at once, organiser payouts, data export, and a live check-in stream with offline sync. Installable as a PWA, because the person scanning at the gate is on a phone with bad signal.

`Next.js` `TypeScript` `Supabase` `Postgres`

### [Strategic Buys](https://strategicbuys.com.au)
Property advisory homepage built as a six-scene scroll-scrubbed film. Adjacent scenes cross-dissolve on frame-locked seams so the take never cuts. Separate mobile encodes, poster stills carrying first paint, and server-rendered markup: every word exists in the HTML before JavaScript runs.

`Next.js` `TypeScript` `Lenis` `scroll-scrubbed video`

### [Asprey Lawyers](https://aspreylawyers.com)
Commercial and criminal firm in Melbourne, shipping in six languages (English, Hindi, Punjabi, Urdu, French, Vietnamese). Practice areas open in place rather than throwing the reader to a new page. Review evidence pulled through from Google.

`Next.js 15` `React 19` `TypeScript` `Tailwind v4` `Framer Motion` `Lenis`

### [Nikunj](https://nikunj.com.au)
Commercial home for an Australian racing driver moving into Toyota 86 development. Every career fact is client-editable through an embedded studio, so the record stays current without a developer. Partnership enquiries land in a database rather than an inbox.

`Next.js` `TypeScript` `Sanity CMS` `Supabase` `GA4`

### [NVRGVP](https://nvrgvp.org)
Content-led cause site structured for search and sharing, with provider logic that resolves by country so the right information reaches the right visitor.

`Next.js` `TypeScript`

### ChargeCore
Charge point management for off-grid solar EV charging, built on a CitrineOS fork for markets where the grid is the problem rather than the solution. OCPP, metering, session billing and tariff logic against solar supply. Private, in build.

`OCPP` `CitrineOS` `Postgres`

---

## Public code

### [plan-gate](https://github.com/Fredons/plan-gate)
A safety gate for AI-generated training plans. The model owns judgement, tested deterministic code owns the numbers, and only the code can publish. Runs with no API key by replaying fixtures. The README documents where my own first version broke and why: I was handing the repair agent a diagnosis instead of the arithmetic, so it trimmed 20% when the maths needed 58%.

### [access-audit](https://github.com/Fredons/access-audit)
Headless WCAG 2.1 and 2.2 AA scanner on Playwright and axe-core. Produces dated, hash-verified evidence records rather than a score, fingerprints accessibility overlay vendors by script signature, and separates automated findings from what genuinely needs manual screen reader assessment.

### [frederick-portfolio](https://github.com/Fredons/frederick-portfolio)
One static page, a scroll-driven corridor of live systems. 272 KB, no framework, no build step.

---

## Practice

**Languages.** TypeScript, JavaScript, Python, SQL, C++

**Interface.** Next.js (App Router), React, Tailwind, Framer Motion, Lenis

**Data.** Postgres, Supabase, PostGIS, SQLite, Sanity, REST design, multi-tenant schema

**AI.** Claude API, Claude Agent SDK, agentic tooling, tool and function definitions, prompt and eval design, voice AI (Vapi, Twilio), n8n

**Infrastructure.** Vercel, self-hosted Hetzner, Docker, CI/CD, observability

**Quality.** Playwright, axe-core, WCAG 2.2 AA, Core Web Vitals, code review

---

Kaduna, Nigeria (UTC+1) · [frederickakam.vercel.app](https://frederickakam.vercel.app) · akamfrederick@gmail.com
