<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:172554,100:312E81&height=220&section=header&text=Rasim%20Tuzluo%C4%9Flu&fontSize=46&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Software%20that%20runs%20real%20businesses&descSize=16&descAlignY=58&descColor=A5B4FC" width="100%" alt="Rasim Tuzluoğlu — Software Developer" />

<a href="https://github.com/Rasimtuzluoglu">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=1200&color=818CF8&center=true&vCenter=true&width=640&height=40&lines=Java+%26+Spring+Boot+backend+developer;Founder+of+RasPel+Co.;Building+ERP+software+for+Turkish+SMBs;%22K%C4%B0%C3%9CBe'nin+Tek+Panosu%22" alt="Typing animation" />
</a>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Rasimtuzluoglu-181717?style=for-the-badge&logo=github)](https://github.com/Rasimtuzluoglu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/rasimtuzluoglu311/)

</div>

---

## 👋 Hi, I'm Rasim

I build the unglamorous software that keeps small businesses running: invoices, stock, receivables, payroll, the daily paperwork that usually lives in five different programs and three notebooks.

I'm a self-taught backend developer and the founder of **RasPel Co.**, where I'm building on-premise business software for Turkish SMBs (KOBİ). My bet is simple: a small business shouldn't need to juggle tools. **One dashboard, one source of truth.**

> 💡 *"KOBİ'nin Tek Panosu"*: one board for the whole business.

|  |  |
|---|---|
| 🚀 **Building now** | **RasPel ERP**, an all-in-one business management platform |
| 🧠 **Obsessed with** | Multi-tenant architecture, financial accuracy, clean data models |
| 🛠️ **Daily stack** | Java 21 · Spring Boot · PostgreSQL · Vue 3 · Docker |
| 🌱 **Leveling up** | Testing, security hardening, observability, deployment pipelines |
| 🎯 **Goal** | Ship software that a real shop owner opens every morning |

---

## 🚀 Featured Projects

### 🏢 RasPel ERP &nbsp; ![Status](https://img.shields.io/badge/status-active%20development-818CF8?style=flat-square)

> An all-in-one, Docker-based ERP for small and medium-sized businesses, built so owners never have to leave it for another program.

<table>
<tr>
<td width="50%" valign="top">

**What it covers**
- 💰 Pre-accounting, invoicing and finance
- 📦 Inventory and product catalog
- 👥 Workforce management
- 💬 Built-in team chat
- 📅 Agenda with tasks and reminders
- 🔄 Business workflows

</td>
<td width="50%" valign="top">

**How it's built**
- 🏗️ Multi-tenant architecture
- 🔐 JWT in httpOnly cookies
- 🗄️ Flyway-managed schema migrations
- 🐳 Docker + Traefik deployment
- 📈 Prometheus & Grafana monitoring
- 🛡️ GitHub Actions CI/CD with Trivy scans

</td>
</tr>
</table>

```mermaid
flowchart LR
    U["🖥️ Browser<br/>Vue 3 · PrimeVue"] -->|HTTPS| T["Traefik<br/>reverse proxy"]
    T --> A["⚙️ Spring Boot API<br/>Java 21 · JWT"]
    A --> P[("PostgreSQL 16<br/>multi-tenant data")]
    A --> R[("Redis<br/>cache")]
    A --> Q[["RabbitMQ<br/>async jobs"]]
    A -.->|metrics| M["📊 Prometheus<br/>+ Grafana"]
```

**Stack:** Java 21 · Spring Boot 3 · Vue 3 · PrimeVue · Tailwind CSS · PostgreSQL · Redis · RabbitMQ · Flyway · Docker

[**Explore the repository →**](https://github.com/Rasimtuzluoglu/raspel-erp)

---

### 💳 RasPel Fin &nbsp; ![Status](https://img.shields.io/badge/status-evolving-60A5FA?style=flat-square)

> Started as a credit card installment tracker, grew into a multi-module financial management platform.

- 🧾 Expense management and credit card installment tracking
- 🏷️ Department budgets with direct cost deduction
- ⏰ Financial reminders, delivered through a **Telegram bot** (secure token-based linking, HMAC-SHA256 verification)
- 📐 Weighted average due date (*ortalama vade*) calculator with CSV import
- 👤 Multi-user support, with Excel and PDF exports

**Stack:** Java 21 · Spring Boot 3.4 · Vaadin 24 · PostgreSQL · Flyway · Spring Security

[**Explore the repository →**](https://github.com/Rasimtuzluoglu/raspel-fin)

---

### 🎬 TheMoviA

A side project where I experiment with application development outside of the business-software world.

[**Explore the repository →**](https://github.com/Rasimtuzluoglu/TheMoviA)

&nbsp;&nbsp;🔎 *More experiments live in [all my repositories](https://github.com/Rasimtuzluoglu?tab=repositories).*

---

## 🧭 What I Care About When Building

| Principle | In practice |
|---|---|
| **Correctness first** | Money and dates are where ERP bugs hurt most, so I treat tax (KDV) and date calculations as critical paths. |
| **Tenant isolation** | One customer must never see another's data. I design for this from the first migration. |
| **Boring, reliable ops** | Versioned migrations, containerized deploys, automated scans, dashboards that tell me what's wrong before users do. |
| **Software owners can use** | If a shop owner needs a manual to issue an invoice, the design has failed. |

---

## 🗺️ What's Next

- [x] Core ERP modules: finance, inventory, workforce
- [x] Containerized deployment with CI/CD and monitoring
- [ ] 🚚 Delivery & dispatch tracking for sales and invoices
- [ ] 💬 Group chat rooms for teams
- [ ] 📅 Tasks and reminders inside the agenda module
- [ ] 📊 A more corporate dashboard with richer charts
- [ ] 🤖 An AI assistant layer on top of business data

---

## 🧰 Tech Toolbox

<div align="center">

**Backend**

<img src="https://skillicons.dev/icons?i=java,spring,hibernate" alt="Java, Spring Boot, Hibernate" />

**Frontend**

<img src="https://skillicons.dev/icons?i=vue,tailwind,javascript,html,css" alt="Vue, Tailwind CSS, JavaScript, HTML, CSS" />

**Data & Messaging**

<img src="https://skillicons.dev/icons?i=postgres,redis,rabbitmq" alt="PostgreSQL, Redis, RabbitMQ" />

**DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=docker,githubactions,grafana,prometheus,git,github,linux" alt="Docker, GitHub Actions, Grafana, Prometheus, Git, GitHub, Linux" />

</div>

---

## 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Rasimtuzluoglu&show_icons=true&hide_border=true&bg_color=0D1117&title_color=818CF8&icon_color=60A5FA&text_color=C9D1D9&rank_icon=github" alt="GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rasimtuzluoglu&layout=compact&hide_border=true&bg_color=0D1117&title_color=818CF8&text_color=C9D1D9&langs_count=6" alt="Most used programming languages" />

</div>

---

## 🤝 Let's Talk

Running a small business and tired of juggling programs? Building something similar and want to compare notes? Hiring for a Java backend role? I'd like to hear from you.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/rasimtuzluoglu311/)
[![GitHub](https://img.shields.io/badge/See_my_code-181717?style=for-the-badge&logo=github)](https://github.com/Rasimtuzluoglu)

<sub>Building, learning, and improving, one commit at a time.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:312E81,50:172554,100:0D1117&height=100&section=footer" width="100%" alt="" />

</div>
