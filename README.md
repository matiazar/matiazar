## Hi, I'm Matias Azar

**Full-stack developer and tech lead, focused on Laravel.** 25+ years building web platforms, the last four leading a team of 5+ developers. Based in Tucumán, Argentina, working with clients across Latin America and the US.

- Led a development team at **SimplifyVMS** (2022-2026): task planning, code review, merges and deploys on a large PHP codebase; built a CSV data-import pipeline processed through RabbitMQ queues.
- **Freelance** for digital agencies and direct clients since 2002: 200+ delivered projects, from e-commerce and CMS/CRM to APIs and mobile apps.
- Today I build my own SaaS products and custom systems for businesses (stock control, process automation, booking, logistics).

### Public repositories

| Repo | What it shows |
|------|---------------|
| [**booking-api**](https://github.com/matiazar/booking-api) | Laravel REST API with the architecture I use in production: Form Requests, Services, DTOs, domain exceptions, after-commit events, admin error reporting, and Pest tests that enforce the architecture rules. |
| [**meta-post-scheduler**](https://github.com/matiazar/meta-post-scheduler) | Self-hosted panel to schedule image posts to Facebook, Instagram and Threads through Meta's official APIs. NestJS + Next.js monorepo, a BullMQ worker that publishes on schedule with retries and email alerts, Cloudflare R2 for media, optional Claude copy suggestions, and a one-command Docker setup. |

### Recent work (private code)

Client and product code lives in private repositories. Happy to walk through any of it in a call.

- **Kalendox** - my own multi-client SaaS for appointment booking, live in production.
- **Envíos Box** - my SaaS for logistics companies, the multi-client version of the Logística La Veloz system.
- **MercadoScanner** - warehouse app that scans MercadoLibre and Tienda Nube shipping labels to verify orders before dispatch. Laravel + Flutter.
- **Logística La Veloz** - driver app for pickups and deliveries with live tracking and automatic commission calculation. Flutter + Firebase.
- **Malka** - booking portal for an aesthetics center: services, professionals, available slots, online payment and reminders. Laravel + MySQL.
- **DonarHoy.com** - donation platform for nonprofit campaigns: multi-currency, multiple payment methods, sponsors and statistics. Laravel + MySQL.

### How I work

- **Spec before code.** Every project starts with a technical spec and an estimate, and the open questions go to the client before development, not halfway through it.
- **Thin controllers.** Validation in Form Requests, business logic in Services, reusable from controllers, jobs and commands.
- **Fail loudly.** Domain exceptions for business rules, transactions for multi-step writes, and unexpected errors reported to the admin.
- **AI as a team, with review.** I run multi-agent workflows with Claude Code (specs, design systems, implementation, review), with the same code-review standards I applied leading a human team.

### My AI development workflow

I built my own Claude Code plugin (private) that encodes how I take a project from brief to delivery:

1. **Spec** - evaluates the client brief, lists what's clear, ambiguous and risky, writes plain-language questions for the client, then the technical spec with an effort estimate. No code yet.
2. **Init** - for new projects: closes the gaps in the spec, decides the stack, scaffolds, and builds one module per stage with a traceable progress log.
3. **Dev** - for existing codebases: surgical changes to the requested module only, respecting the project's own architecture, with tests per module.
4. **Review** - picks the review depth by risk: none for trivial edits, code review for normal changes, code + security review for auth, payments and user input.

The shared rules are the ones I'd ask of any team: no push or history rewrite without approval, every design decision must surface at least one blind spot, debug from evidence not guesses, the simplest solution that works, thin controllers, and errors that fail loudly and reach the admin.

### Stack

**Backend:** PHP, Laravel, Yii, Node.js / NestJS (learning), TypeScript (learning) · **Frontend:** JavaScript, Next.js (learning), Tailwind, Astro · **Mobile:** Flutter · **Data:** MySQL, PostgreSQL, SQLite, Redis, Firebase, Prisma · **Infra:** RabbitMQ, BullMQ, queues, Docker, Cloudflare R2, Git, GitHub Actions · **Integrations:** Mercado Libre, Mercado Pago, Tienda Nube, PayPal, Stripe, WhatsApp API, Claude API, Meta Graph API (Facebook, Instagram), Threads API, Google Calendar, Google Meet, Google OAuth, Firebase Cloud Messaging, ARCA (electronic invoicing), Correo Argentino, Andreani, OCA · **AI tooling:** Claude Code, GitHub Copilot, Antigravity

### Contact

[LinkedIn](https://www.linkedin.com/in/matiazar)

<sub>Hablo español (nativo) e inglés técnico.</sub>
