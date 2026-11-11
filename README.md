# Hi, I'm Iverson 👋

**Senior Front-End Engineer — Angular & TypeScript** · 17 years building web and mobile products for banking and financial services.

I design and ship large Angular applications for regulated environments: customer financial-health platforms, anti-money-laundering (AML) tooling and vehicle-financing systems for European and Brazilian banks.

## What I do

- **Angular at scale** — standalone components, Signals, zoneless change detection, lazy-loaded feature architecture, typed reactive forms.
- **Framework migrations** — led upgrades across major versions (Angular 2 → 14, 12 → 14, 14 → 18) on live banking products without freezing feature work.
- **Auth & security** — JWT access/refresh flows, HTTP interceptors, role-based guards, SSO integration.
- **Mobile** — Ionic + Capacitor; ~50 apps published to the stores, offline-first with background sync.
- **Delivery** — CI/CD with GitHub Actions, Tailwind CSS design systems, unit + e2e testing (Vitest, Jest, Playwright).
- **AI-assisted engineering** — my own workflow combining Claude / Copilot with Playwright to reproduce, triage and document bugs faster.

## Tech stack

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=flat&logo=ionic&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat&logo=capacitor&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## Featured projects

### [Ledgerly — Angular enterprise showcase](https://github.com/iverson-viana/angular-enterprise-showcase)

**[Live demo](https://ledgerly-eda.pages.dev)** · a B2B banking dashboard that shows how I structure a production-grade Angular app.

- **Angular 22, the modern way:** standalone, zoneless, signals end to end (`httpResource`, `linkedSignal`), typed Signal Forms.
- **Real-world features:** JWT auth with silent refresh, role-based access, server-paginated tables with state in the URL, a 10,000-row virtualized feed, a create/edit form with masks, checksums and async validation.
- **Accessibility as a requirement:** WCAG 2.2 AA checked by `axe` in CI, Lighthouse accessibility 100.
- **Tested and gated:** 161 unit and 21 e2e tests, 90% coverage enforced. Lint → unit → build → e2e must pass before every Cloudflare Pages deploy.
- **EN / PT-BR at runtime** with compile-time-checked message keys, plus dark mode.

More coming: an AML transaction-monitoring UI, an AI-assisted bug-triage workflow and an Angular migration toolkit.
