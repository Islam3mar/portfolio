# Islam Omar — Portfolio

Personal portfolio of **Islam Omar**, a Back-End Developer specialized in the **.NET** ecosystem (C#, ASP.NET Core, Entity Framework Core, SQL Server).

**Live site:** [islam3mar.github.io/portfolio](https://islam3mar.github.io/portfolio/)

---

## About

I build RESTful APIs and MVC applications using Clean and Onion Architecture, with JWT authentication, caching, payments, and real-time features. I have about 2 years of freelance full-stack experience and recently completed a back-end internship at **Pioneers Solutions**, where I built an HR system and a billing system from written SRS documents. I graduated from Menofia University (Physics & Computer Science, Class 2021–2026, GPA 84%) with a back-end diploma from Route Academy.

I'm open to Back-End Developer roles in the .NET ecosystem, remote or on-site.

## Experience

- **Back-End Developer Intern (.NET MVC)**, Pioneers Solutions (Sep 2026): built the back-end of an HR system and a billing system (ASP.NET Core MVC) from a written SRS, owning features end to end under code review. Added soft delete to prevent payroll data loss, a MailKit `BackgroundService` for due-date/overdue reminders with catch-up logic, and per-client credit limits with idempotent Stripe webhooks.
- **Freelance Full-Stack Developer (Frontend & Backend)**, Remote (Oct 2024 – Present): built client applications with ASP.NET Core and JavaScript, e-commerce stores, landing pages and portfolio websites, and debugged client applications down to the root cause.

## Featured projects

| Project | Highlights | Links |
|---|---|---|
| **Bills System** | Billing and invoicing with Stripe Checkout and secure webhooks (signature verification, idempotent processing, refund/dispute handling), per-client credit limits, Arabic/English PDF invoices (QuestPDF), automated email reminders (MailKit) | [Live](https://bills.runasp.net/) · [Code](https://github.com/Islam3mar/BillsSystem) |
| **HRMS** | Arabic (RTL) HR system built from a written SRS: page-level permissions (View/Add/Edit/Delete), attendance with Excel import/export, month locking, payroll with immutable snapshots, cookie auth with BCrypt and AES encryption | [Live](https://hrmsapp.runasp.net/) · [Code](https://github.com/Islam3mar/HRMS) |
| **E-Commerce RESTful API** | Onion Architecture, JWT, Redis caching, Stripe, Specification pattern, Swagger docs | [Live API](https://splendid-commitment-production-3ff6.up.railway.app/swagger) · [Code](https://github.com/Islam3mar/ECommerceAPI) |
| **Kon Sanad** (graduation project, A+) | Role-based charity management API with 5 roles, donations, warehouse management, KPI dashboard, SignalR and Redis notifications, campaign end-date alerts, PDF reports | [Live](https://kon-sanad-whbi.vercel.app/login) · [Code](https://github.com/ahmed-samir10/GraduationProject) |
| **Gym Management System** | ASP.NET MVC, 3-tier architecture, Identity roles (Admin / Trainer / Member), session booking | [Live](https://gym-system-0.runasp.net/) · [Code](https://github.com/Islam3mar/GymSystemMVC) |

Demo logins are available on request.

## Tech stack

- **Languages:** C#, T-SQL, JavaScript (ES6), HTML5, CSS3
- **Frameworks:** ASP.NET Core, ASP.NET MVC, Web API, Entity Framework Core, LINQ, AutoMapper, FluentValidation
- **Architecture:** Clean Architecture, Onion Architecture, Repository, Unit of Work, Specification, SOLID, OOP, Dependency Injection
- **Security:** JWT, ASP.NET Identity, BCrypt, AES encryption, role-based and permission-based authorization
- **Data and integrations:** SQL Server, Redis, SignalR, Stripe, MailKit, QuestPDF, ClosedXML
- **Frontend:** Bootstrap, jQuery, responsive web design
- **Testing:** API testing (Postman, Swagger), manual testing
- **Tools:** Visual Studio, Git/GitHub, Postman, Swagger, SSMS, Azure DevOps
- **Learning:** React

## Languages

Arabic (native), English (professional working proficiency, B2)

## About this repository

This repo hosts the portfolio site itself, a single static page deployed with **GitHub Pages**.

```
portfolio/
├── index.html          # the portfolio (HTML, CSS and JS in one file, no build step)
├── Islam_Omar_CV.pdf   # CV (PDF)
└── Islam_Omar_CV.docx  # CV (Word)
```

To run it locally, open `index.html` in a browser.

## Contact

- Email: [islam3marahmed@gmail.com](mailto:islam3marahmed@gmail.com)
- LinkedIn: [linkedin.com/in/islam-omar-3ba867266](https://linkedin.com/in/islam-omar-3ba867266)
- GitHub: [github.com/Islam3mar](https://github.com/Islam3mar)
- Location: Egypt
