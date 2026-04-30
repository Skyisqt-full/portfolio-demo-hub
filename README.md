# Portfolio Demo Hub

Интерактивная витрина коммерческих демо-проектов. Это не резюме-страница, а будущий control room: заказчик выбирает стек или бизнес-задачу, открывает live demo, видит demo flow, архитектуру и фрагменты кода.

## Product idea

Portfolio Demo Hub должен показывать, что разработчик умеет быстро собирать продукты под бизнес:

- CRM и pipeline workflows.
- Админки и dashboards.
- Mobile apps на Flutter.
- WordPress/WooCommerce plugins.
- Bitrix24 и 1C-Bitrix integrations.
- Realtime systems, WebSocket, telemetry.
- Payments, webhooks, notifications.
- AI/support automation.

## Planned UX

- Filters by stack: TypeScript, Flutter, PHP, WordPress, Bitrix24, 1C-Bitrix, Python, Go, Java/Kotlin, .NET.
- Filters by business task: CRM, payments, delivery, booking, personal account, admin panel, realtime, integrations, AI.
- Project cards with screenshots, status, stack, business problem and GitHub link.
- Case-study mode for flagship projects.
- Code viewer: clicking a UI area shows the related code fragment and GitHub path.
- Demo timeline: user action -> API request -> webhook -> background job -> dashboard update.

## First-wave projects

| Project | Role |
| --- | --- |
| `web-scada-showcase` | Flagship realtime industrial dashboard. |
| `route-ops` | Flutter logistics/mobile workflow. |
| `avito-ws-bridge` | Realtime integration bridge. |
| `DnsConf` | Java automation utility. |
| `wp-woocommerce-delivery-slots` | Planned WordPress/WooCommerce plugin. |
| `bitrix24-lead-sync-app` | Planned Bitrix24 CRM integration. |

## What is mocked

This repository starts as a portfolio shell. Until live demos are connected:

- Payment providers are represented as sandbox/mock flows.
- CRM/CMS integrations use demo credentials or local mock endpoints.
- Screenshots and demo data must not contain client names, production domains or private credentials.

## Local run

The implementation will be added as a Next.js app in the next step.

```powershell
pnpm install
pnpm dev
```

## English short version

Portfolio Demo Hub is an interactive showcase for commercial prototypes: live demos, project filters, architecture notes and code highlights. The goal is to prove practical delivery capability, not just list repositories.

