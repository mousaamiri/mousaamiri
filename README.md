# Mousa Amiri Motlagh

**Backend Developer — .NET / C#**
Clean Architecture · DDD · CQRS · Domain Modeling

Self-taught .NET backend developer with two years of focused, consistent practice
— building real projects with production-grade patterns.

🌐 [mousaamiri.ir](https://mousaamiri.ir)

---

## Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=nuget&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D4?style=flat-square&logo=windows&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-5A2D82?style=flat-square&logo=xunit&logoColor=white)

## Patterns & Practices

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1A1A2E?style=flat-square&logo=blueprint&logoColor=white)
![DDD](https://img.shields.io/badge/Domain_Driven_Design-6A0DAD?style=flat-square&logo=diagrams.net&logoColor=white)
![CQRS](https://img.shields.io/badge/CQRS-0A3D62?style=flat-square&logo=datadog&logoColor=white)
![Outbox Pattern](https://img.shields.io/badge/Outbox_Pattern-B7410E?style=flat-square&logo=apachekafka&logoColor=white)
![Repository Pattern](https://img.shields.io/badge/Repository_Pattern-2C6E49?style=flat-square&logo=databricks&logoColor=white)
![Unit of Work](https://img.shields.io/badge/Unit_of_Work-2C6E49?style=flat-square&logo=buffer&logoColor=white)
![Result Pattern](https://img.shields.io/badge/Result_Pattern-34495E?style=flat-square&logo=checkmarx&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-0078D4?style=flat-square&logo=windows&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-C0392B?style=flat-square&logo=testinglibrary&logoColor=white)

---

## Projects

### [Vitastic](https://github.com/mousaamiri/Vitastic) — Online Learning Platform
Backend for an online course marketplace built with ASP.NET Core 10 and tactical DDD.
Uses aggregates, domain events and the **Outbox Pattern** so a completed purchase is never
lost mid-checkout: the system recovers and reconciles itself instead of failing silently.
Four-layer solution (Domain / App / Infra / Api) plus an MVC front-end that talks to the API over HTTP.

`ASP.NET Core 10` `PostgreSQL` `EF Core` `Clean Architecture` `DDD` `CQRS` `Outbox Pattern` `Docker`

> 🚧 Work in progress — the focus is the architecture, not a shipped product.

---

### [Portfolio](https://github.com/mousaamiri/Portfolio) — Bilingual Portfolio + CMS
A bilingual (EN / FA, full RTL) portfolio site where **every** piece of content is
database-backed and editable from a JWT-secured admin panel — new projects go live
with no code change and no redeploy. Live accent-color and light/dark theming,
command palette (`⌘/Ctrl + K`), rate-limited login, and a test project per layer.

`.NET 10` `ASP.NET Core Web API` `MVC / Razor` `EF Core` `SQL Server` `JWT` `xUnit + FluentAssertions + Moq` `Clean Architecture`

🔗 Live: [mousaamiri.ir](https://mousaamiri.ir)

---

### [Wazhechin](https://github.com/mousaamiri/Wazhechin) — Library Lending System
A Persian WPF desktop app for managing book lending: inventory, members, loans and returns.
An 8-project layered solution whose core is a custom **`ModelWrapper<T>`** change-tracking
and validation system (`IsChanged` / `RejectChanges` / per-property original values) built on
`INotifyDataErrorInfo`, wired up with Generic Host DI and MahApps.Metro runtime theming.
The ViewModel layer is covered by a dedicated unit-test project.

`.NET 10` `WPF` `MVVM` `SQL Server` `EF Core 10` `MahApps.Metro` `CommunityToolkit.Mvvm` `TDD` `Repository + UnitOfWork`

📦 Ready-to-run build available in [Releases](https://github.com/mousaamiri/Wazhechin/releases)

---

### [DotNet Performance Lab](https://github.com/mousaamiri/DotNet-Performance-Lab) — Performance Experiments
A set of small, isolated projects that each implement one performance technique by hand,
measure its real impact and document the numbers: `IMemoryCache`, Cache-Aside, Redis
distributed caching, cache stampede, response/output caching, Gzip & Brotli compression,
async pitfalls (`Task` vs `ValueTask`) and formal BenchmarkDotNet runs.

`C#` `.NET` `Redis` `BenchmarkDotNet` `Docker`

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mousaamiri&show_icons=true&theme=default&hide_border=true&cache_seconds=86400)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mousaamiri&layout=compact&theme=default&hide_border=true&cache_seconds=86400)

---

## Contact

[![Website](https://img.shields.io/badge/mousaamiri.ir-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://mousaamiri.ir)
[![Email](https://img.shields.io/badge/mousa.amiri.dev@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mousa.amiri.dev@gmail.com)
