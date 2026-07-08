<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=30&pause=900&color=6366F1&center=true&vCenter=true&width=760&lines=Ol%C3%A1%2C+eu+sou+Dener+Schmidt+%F0%9F%91%8B;Full+Stack+Developer;.NET+%2B+Angular+%2B+MongoDB;ERP+Enterprise+%7C+Fiscal+%7C+Integra%C3%A7%C3%B5es" alt="Typing SVG" />

<br/>

### Desenvolvedor Full Stack focado em **ERP enterprise**, **integrações fiscais** e **produtos SaaS**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devdenerarturschmidt@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Dener-schmidt-dev)

<br/>

![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</div>

---

<table>
<tr>
<td width="50%">

### 🚀 Sobre mim

Trabalho com evolução de sistemas **ERP de grande escala**, atuando em módulos de vendas, fiscal, financeiro, estoque, e-commerce, APIs e serviços em background.

Tenho foco em entregar soluções com **baixo risco de regressão**, reaproveitando padrões existentes e mantendo código simples, performático e sustentável.

</td>
<td width="50%">

```typescript
const dener = {
  role: "Full Stack Developer",
  stack: [".NET", "Angular", "MongoDB"],
  focus: ["ERP", "Fiscal", "SaaS", "Integrações"],
  mindset: ["Clean Code", "Performance", "Baixo risco"],
  current: "Construindo soluções que escalam negócios"
};
```

</td>
</tr>
</table>

---

## ⚡ Visão rápida

<div align="center">

| 🧩 Área | 💼 Experiência |
|:--|:--|
| **ERP Enterprise** | Vendas, financeiro, fiscal, estoque, PDV e relatórios |
| **Fiscal** | NF-e, NFC-e, NFS-e, MDF-e, CT-e, SPED e ACBr |
| **Front-end** | Angular, TypeScript, telas CRUD, dashboards e autocompletes |
| **Back-end** | APIs REST, services, repositories, jobs, MongoDB e integrações |
| **Infra/Deploy** | GitHub Actions, AWS S3, CloudFront, ambientes de homologação/produção |

</div>

---

## 🧠 Arquitetura na prática

<details open>
<summary><b>✨ Fluxo principal que aplico no dia a dia</b></summary>

<br/>

```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "background": "#0d1117",
    "primaryColor": "#111827",
    "primaryTextColor": "#f8fafc",
    "primaryBorderColor": "#6366f1",
    "lineColor": "#60a5fa",
    "secondaryColor": "#020617",
    "tertiaryColor": "#0f172a",
    "fontFamily": "Fira Code, Segoe UI, Arial"
  }
}}%%

flowchart LR
    FE["🅰️ Angular V3<br/><small>BaseList · BaseEdit · ApiService</small>"]
    API["⚙️ ASP.NET Core API<br/><small>Controllers · DTOs · Auth</small>"]
    SRV["🧩 Service Layer<br/><small>Regras · Validações · Logs</small>"]

    DB[("🍃 MongoDB<br/><small>Índices reais</small>")]
    CACHE["⚡ Redis / Cache"]
    CLOUD["☁️ AWS S3 + CloudFront"]
    FISCAL["📄 Fiscal / ACBr<br/><small>NF-e · NFS-e · MDF-e</small>"]

    FE ==>|"REST / SignalR"| API
    API ==>|"DTOs"| SRV

    SRV --> DB
    SRV --> CACHE
    SRV --> CLOUD
    SRV --> FISCAL

    classDef front fill:#0f172a,stroke:#38bdf8,color:#e0f2fe,stroke-width:3px;
    classDef api fill:#111827,stroke:#8b5cf6,color:#ede9fe,stroke-width:3px;
    classDef service fill:#052e2b,stroke:#22c55e,color:#dcfce7,stroke-width:3px;
    classDef data fill:#052e16,stroke:#22c55e,color:#bbf7d0,stroke-width:3px;
    classDef cache fill:#3b0764,stroke:#c084fc,color:#f3e8ff,stroke-width:3px;
    classDef cloud fill:#431407,stroke:#f97316,color:#ffedd5,stroke-width:3px;
    classDef fiscal fill:#500724,stroke:#ec4899,color:#fce7f3,stroke-width:3px;

    class FE front;
    class API api;
    class SRV service;
    class DB data;
    class CACHE cache;
    class CLOUD cloud;
    class FISCAL fiscal;

    linkStyle 0 stroke:#38bdf8,stroke-width:3px;
    linkStyle 1 stroke:#8b5cf6,stroke-width:3px;
    linkStyle 2 stroke:#22c55e,stroke-width:2px;
    linkStyle 3 stroke:#c084fc,stroke-width:2px;
    linkStyle 4 stroke:#f97316,stroke-width:2px;
    linkStyle 5 stroke:#ec4899,stroke-width:2px;
```

</details>

<details>
<summary><b>⚙️ Padrões técnicos</b></summary>

<br/>

| Padrão | Como aplico |
|:--|:--|
| **Controller → Service → Repository** | Separação clara de responsabilidades |
| **DTOs dedicados** | Request/response sem acoplar entidade |
| **Regra no backend** | Front-end não decide regra crítica |
| **Componentes base** | Reaproveitamento e consistência visual |
| **Code review severo** | Foco em regressão, performance e manutenção |
| **MongoDB consciente** | Índices alinhados aos filtros reais da tela |

</details>

---

## 🛠️ Stack principal

<div align="center">

<img src="https://skillicons.dev/icons?i=dotnet,cs,angular,ts,js,html,css,sass,mongodb,redis,docker,aws,git,github,githubactions,visualstudio,vscode" />

</div>

<details>
<summary><b>Ver stack por categoria</b></summary>

<br/>

| Categoria | Tecnologias |
|:--|:--|
| **Backend** | .NET 8, ASP.NET Core, C#, REST APIs, gRPC, SignalR, xUnit |
| **Frontend** | Angular, TypeScript, RxJS, SCSS, Bootstrap, ECharts |
| **Banco/Cache** | MongoDB, Redis |
| **Cloud/Deploy** | AWS S3, CloudFront, GitHub Actions |
| **Domínio** | ERP, Fiscal, ACBr, Mercado Livre, Pagarme, OAuth2 |

</details>

---

## 👾 Minhas contribuições

<div align="center">

<!-- Gerado automaticamente pela action abozanona/pacman-contribution-graph -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man comendo o gráfico de contribuições do GitHub" src="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph.svg">
</picture>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Dener-schmidt-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dener-schmidt-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=Dener-schmidt-dev&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>

</div>

---

## 📌 Projetos e domínios

<details open>
<summary><b>Áreas onde mais atuo</b></summary>

<br/>

| Projeto/Domínio | O que envolve |
|:--|:--|
| 🔧 **Sistema ERP** | Plataforma de gestão empresarial com vendas, fiscal, financeiro e estoque |
| 🛒 **E-commerce Integrator** | Sincronização com marketplaces, estoque, pedidos e anúncios |
| 📄 **Emissão Fiscal** | NF-e, NFS-e, MDF-e, integrações ACBr e conformidade fiscal |
| 🤖 **Módulos com IA** | Recursos inteligentes aplicados ao produto e atendimento |
| 🚀 **Deploy e Infra** | Homologação, produção, CDN, storage, APIs e monitoramento |

</details>

---

<div align="center">

### Vamos construir algo incrível?

Estou aberto para networking, colaborações e conversas sobre **ERP**, **SaaS**, **arquitetura**, **fiscal** e **produtos digitais**.

[![Email](https://img.shields.io/badge/Enviar_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devdenerarturschmidt@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Conectar_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-LINKEDIN)

<br/>

> Código limpo não é luxo — é o que permite escalar um ERP sem quebrar centenas de telas.

<br/>

<img src="https://komarev.com/ghpvc/?username=Dener-schmidt-dev&color=6366F1&style=flat-square" alt="Profile views"/>

</div>
