
<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Ol%C3%A1%2C+eu+sou+Dener+Schmidt+%F0%9F%91%8B;Desenvolvedor+Full+Stack;Especialista+em+ERP+%26+Sistemas+Enterprise" alt="Typing SVG" />

<br/>

**Desenvolvedor de software focado em sistemas ERP de grande escala, integrações fiscais e produtos digitais de alto impacto.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devdenerarturschmidt@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Dener-schmidt-dev)

</div>

---

## Sobre mim

Sou **Desenvolvedor Full Stack** com experiência na construção e evolução de **plataformas ERP enterprise** — sistemas complexos que atendem vendas, fiscal, financeiro, estoque, e-commerce e integrações com marketplaces.

Trabalho diariamente com **arquitetura em camadas**, **APIs REST**, **front-end Angular**, **MongoDB** e **serviços distribuídos**, entregando features críticas de negócio com foco em **qualidade**, **performance** e **manutenibilidade**.

```typescript
const dener = {
  role: "Full Stack Developer",
  location: "Brasil",
  focus: ["ERP", "Fiscal", "E-commerce", "Integrações"],
  principles: ["Clean Architecture", "DTOs", "Testes", "Code Review"],
  currentlyLearning: ["IA aplicada a produto", "Otimização MongoDB", ".NET 8"],
  funFact: "Já trabalhei em telas que herdam de uma mesma BaseList — centenas delas 😄"
};
```

---

## O que eu construo

Trabalho em um ecossistema completo de software empresarial, cobrindo desde a interface do usuário até emissão fiscal e sincronização com marketplaces:

| Domínio | O que faço |
|:--------|:-----------|
| **Vendas & PDV** | Fluxos de venda, ponto de venda, impressões e agrupamentos |
| **Fiscal** | NF-e, NFC-e, NFS-e, MDF-e, CT-e, SPED e integração ACBr |
| **Financeiro** | Lançamentos, boletos, carnês, conciliação OFX |
| **Estoque** | Movimentações, depósitos, gestor de preços |
| **E-commerce** | Integrações Mercado Livre, sincronização de estoque/vendas |
| **APIs & Serviços** | REST, gRPC, SignalR, jobs em background, cache |
| **Front-end** | +280 telas CRUD, relatórios, autocompletes e dashboards |

---

## Stack & Ferramentas

### Backend
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5D?style=flat-square&logo=grpc&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=flat-square&logo=apache-echarts&logoColor=white)

### Integrações & Domínio
![REST API](https://img.shields.io/badge/REST_API-FF6B35?style=flat-square&logo=swagger&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat-square&logo=auth0&logoColor=white)
![NF-e](https://img.shields.io/badge/NF--e_%2F_NFS--e-Fiscal-green?style=flat-square)
![Mercado Livre](https://img.shields.io/badge/Mercado_Livre-FFE600?style=flat-square&logo=mercadopago&logoColor=black)
![Pagarme](https://img.shields.io/badge/Pagarme-65A300?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## Arquitetura que aplico no dia a dia

```
┌─────────────────────────────────────────────────────────────┐
│                    Angular (BorlanV3)                       │
│   BaseList · BaseEdit · BaseReport · ApiService · Utils     │
└──────────────────────────┬──────────────────────────────────┘
                           │ REST / SignalR
┌──────────────────────────▼──────────────────────────────────┐
│              ASP.NET Core API (V1 / V2 / IA)                │
│         Controller → Service → Repository → MongoDB         │
└──────────────────────────┬──────────────────────────────────┘
                           │
        ┌──────────────────┼──────────────────┐
        ▼                  ▼                  ▼
   ┌─────────┐       ┌───────────┐      ┌────────────┐
   │  Redis  │       │  AWS S3   │      │  gRPC Svcs │
   │  Cache  │       │ CloudFront│      │ Background │
   └─────────┘       └───────────┘      └────────────┘
```

**Padrões que sigo:**
- Separação clara: **Controller → Service → Repository**
- **DTOs** dedicados para request e response
- Regras de negócio **sempre no backend**
- Front-end com **componentes base reutilizáveis** (DRY em escala)
- **Code review** com severidade e foco em regressão
- **Índices MongoDB** alinhados aos filtros de produção

---

## Destaques técnicos

- **Monorepo enterprise** com 100+ projetos .NET e front-end Angular multi-módulo
- **+280 telas** compartilhando bases (`BaseList`, `BaseEdit`, `BaseReport`)
- **Emissão fiscal** integrada via ACBr (NF-e, NFS-e, MDF-e, NFCom)
- **E-commerce integrator** com sincronização de estoque e vendas
- **Deploy** em CDN (S3 + CloudFront) com pipelines de homologação e produção
- **Serviços assíncronos**: notificações, auditoria, indexação MongoDB, certificados digitais
- **IA aplicada** em módulos de produto (`ERP.IA`, `API.IA`)

---

## 👾 Minhas contribuições (Pac-Man)

<!-- Gerado automaticamente pela action abozanona/pacman-contribution-graph -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man comendo o gráfico de contribuições do GitHub" src="https://raw.githubusercontent.com/Dener-schmidt-dev/Dener-schmidt-dev/output/pacman-contribution-graph.svg">
</picture>

---

## GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Dener-schmidt-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dener-schmidt-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=Dener-schmidt-dev&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>

</div>

---

## Projetos em destaque

<!-- Ajuste com seus repositórios públicos ou pins do GitHub -->

| Projeto | Descrição |
|:--------|:----------|
| 🔧 **Sistema ERP** | Plataforma full stack de gestão empresarial — vendas, fiscal, financeiro e estoque |
| 🛒 **E-commerce Integrator** | Sincronização com marketplaces (Mercado Livre e outros) |
| 📄 **Emissão Fiscal** | NF-e, NFS-e, MDF-e com ACBr e conformidade SEFAZ |
| 🤖 **Módulo IA** | Features de inteligência artificial integradas ao ERP |

---

## Vamos conversar?

Estou aberto a colaborações, networking e oportunidades em **desenvolvimento enterprise**, **integrações fiscais** e **produtos SaaS**.

<div align="center">

[![Email](https://img.shields.io/badge/📧_devdenerarturschmidt@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devdenerarturschmidt@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-LINKEDIN)

<br/>

*"Código limpo não é luxo — é o que permite escalar um ERP sem quebrar centenas de telas."*

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Dener-schmidt-dev&color=6366F1&style=flat-square" alt="Profile views"/>
</div>
