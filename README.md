# Portfolio Demo Hub

Интерактивная витрина бизнес-проектов и коммерческих showcase-версий. Это не статичная страница-резюме, а рабочий центр портфолио: заказчик выбирает стек или бизнес-задачу, открывает проект, смотрит сценарий, архитектуру, live demo и связанные фрагменты кода.

## Идея продукта

Portfolio Demo Hub должен показывать, что разработчик умеет собирать полноценные бизнес-системы:

- CRM и pipeline workflows.
- Админки и dashboard.
- Мобильные приложения на Flutter.
- WordPress/WooCommerce plugins.
- Интеграции с Битрикс24 и 1C-Битрикс.
- Realtime systems, WebSocket, telemetry.
- Платежи, webhooks, уведомления.
- AI/support automation.
- Backend services, parsers, bots, integration bridges.

## Планируемый интерфейс

- Фильтры по стеку: TypeScript, Flutter, PHP, WordPress, Битрикс24, 1C-Битрикс, Python, Go, Java/Kotlin, .NET.
- Фильтры по бизнес-задаче: CRM, оплаты, доставка, бронирование, личный кабинет, админка, realtime, интеграции, AI.
- Карточки проектов: задача бизнеса, стек, статус, скриншоты, GitHub, demo flow.
- Case study для флагманских проектов.
- Code viewer: выбор части интерфейса показывает связанный фрагмент кода и путь в GitHub.
- Timeline сценария: действие пользователя -> API request -> webhook -> background job -> обновление dashboard.

## Первая волна проектов

| Проект | Роль |
| --- | --- |
| `web-scada-showcase` | Флагманская realtime-система для industrial dashboard. |
| `route-ops` | Flutter-система для логистики и выездных заявок. |
| `avito-ws-bridge` | Realtime integration bridge для сообщений. |
| `DnsConf` | Java automation utility для DNS-конфигураций. |
| `wp-woocommerce-delivery-slots` | Планируемый WordPress/WooCommerce plugin. |
| `bitrix24-lead-sync-app` | Планируемая интеграция с Битрикс24 CRM. |

## Что является демонстрационным

- Оплаты показываются через sandbox или локальные mock handlers.
- CRM/CMS-интеграции используют тестовые порталы, demo fixtures или mock endpoints.
- Скриншоты и данные не содержат клиентских имен, production-доменов и приватных доступов.

## Локальный запуск

Реализация сайта будет добавлена следующим этапом.

```powershell
pnpm install
pnpm dev
```

## English short version

Portfolio Demo Hub is an interactive portfolio center for business systems: project filters, live demos, case studies, architecture notes and code highlights.

