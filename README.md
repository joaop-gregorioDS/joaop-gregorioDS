# João Paulo Gregório de Souza

**Engenheiro de Software na [Vortex Software](https://vortexsoftware.tech/)**  
São Paulo, SP · [LinkedIn](https://www.linkedin.com/in/joaop-gregorio/) · [E-mail](mailto:joaop.gregorio@outlook.com) · [vortexsoftware.tech](https://vortexsoftware.tech/)

---

### Sobre mim

Engenheiro de Software com foco em sistemas de missão crítica, arquiteturas orientadas a eventos, consistência transacional estrita e ecossistemas corporativos multiplataforma. Atuo na concepção, modelagem e entrega técnica de produtos de software na **[Vortex Software](https://vortexsoftware.tech/)**, aplicando padrões de engenharia para atender a requisitos rigorosos de segurança, integridade de dados e desempenho.

Minha trajetória de **14 anos na CPTM** em operação técnica e supervisão de sistemas metroviários consolidou uma forte cultura de engenharia: disciplina operacional, análise de causa-raiz de falhas, conformidade procedimental e resiliência em ambientes onde paradas e inconsistências são inaceitáveis. Essa vivência fundamenta a forma como projeto software para cenários corporativos e licitações públicas de alta exigência técnica.

---

### Stack Tecnológica & Competências

> *"Tecnologia como meio. Resultado como objetivo. A stack é escolhida de acordo com requisitos de segurança, manutenção, desempenho, integração e custo."* — [Vortex Software](https://vortexsoftware.tech/)

| Domínio | Tecnologias Carro-Chefe |
| :--- | :--- |
| **Backend & Arquitetura (Core)** | **C#**, **.NET 10 / ASP.NET Core**, **Entity Framework Core**, **Clean Architecture & DDD**, Design de APIs RESTful / Minimal APIs, Padrão Transactional Outbox |
| **Bancos de Dados & Mensageria** | **PostgreSQL 16/18** (ACID, transações e *advisory locks*), **Redis 7** (cache e pub/sub), **RabbitMQ** (event-driven e dead-letter exchange) |
| **Mobile & Clientes Nativos** | **Kotlin & Jetpack Compose** (Android), **Swift & SwiftUI** (iOS), **Rust (Tauri 2)** (Desktop multiplataforma) |
| **Frontend Web** | **React 19**, **Next.js** (App Router / SSR), **TypeScript**, Tailwind CSS, Lightweight Charts (TradingView) |
| **Infraestrutura & DevOps** | **Docker & Containers**, **Nginx Gateway & Reverse Proxy**, **Linux & VPS Hosting**, CI/CD, Let's Encrypt / TLS |
| **Engenharia Financeira & Dados** | Precisão decimal exata ($10^{-28}$), *Double-Entry Bookkeeping* (partidas dobradas), conformidade FEFO, gestão de risco pré-trade |

---

## 🏆 Projetos em Destaque — Vortex Labs

Projetos de engenharia de ponta a ponta desenvolvidos para demonstrar capacidade técnica real em cenários corporativos complexos:

### 1. [Vortex Bank](https://github.com/joaop-gregorioDS/vortex-bank)
**Core Bancário Digital Unificado & Monorepo Multiplataforma**  
Solução financeira corporativa de alta fidelidade com motor transacional, livro-razão contábil (*double-entry bookkeeping*) e consistência ACID.
* **Stack:** C#, .NET 10, ASP.NET Core, EF Core, PostgreSQL 16, Redis 7, React 19, TypeScript, Kotlin (Android), Swift (iOS).
* **Diferenciais:** Arquitetura omnicanal compartilhando a mesma API real, rastreabilidade auditável, autenticação segura e concorrência bancária.
* **Status:** 🌐 Em produção na VPS: [bank.vortexsoftware.tech/app](https://bank.vortexsoftware.tech/app)

---

### 2. [Vortex Trading Terminal](https://github.com/joaop-gregorioDS/vortex-trading-terminal)
**Terminal Financeiro Profissional & Paper Trading da B3**  
Mesa de operações simulada para ativos da B3 (Ações como PETR4/VALE3 e minicontratos futuros WIN/WDO) com precisão matemática absoluta.
* **Stack:** C#, .NET 10 LTS, ASP.NET Core Minimal APIs, EF Core, PostgreSQL 18 (schema `trading`), Next.js 16, React 19, Lightweight Charts.
* **Diferenciais:** Aritmética decimal estrita ($10^{-28}$ sem ponto flutuante), motor de risco pré-trade, execução FIFO sem look-ahead, apurador de Day Trade e **mais de 2.260 testes automatizados** com 100% de aprovação.
* **Status:** 🌐 Em produção na VPS: [trading.vortexsoftware.tech](https://trading.vortexsoftware.tech)

---

### 3. [Vortex Farma](https://github.com/joaop-gregorioDS/vortex-farma)
**Farmácia Digital & Gestão Operacional de Varejo Conectado**  
Plataforma que conecta a experiência de compra do consumidor ao gerenciamento de estoque, lotes e validade do varejo farmacêutico.
* **Stack:** C#, .NET 10, ASP.NET Core Minimal APIs, EF Core 10, PostgreSQL 16, Redis 7, RabbitMQ, Next.js 16, React 19.
* **Diferenciais:** Algoritmo FEFO (*First Expired, First Out*), reserva temporária de 20 minutos, *Transactional Outbox* para publicação assíncrona, bloqueios de quarentena e controle de concorrência por *advisory locks*.
* **Status:** 🌐 Em produção na VPS: [farma.vortexsoftware.tech](https://farma.vortexsoftware.tech)

---

### 4. [B3 TradingCore (API)](https://github.com/joaop-gregorioDS/b3-trading-core)
**Motor de Pós-Negociação e Liquidação Financeira**  
API de alto desempenho focada no processamento de ordens, clearing e ciclo de vida pós-trade no padrão da bolsa brasileira.
* **Stack:** C#, .NET 8, ASP.NET Core, Entity Framework Core, PostgreSQL, Redis, RabbitMQ, Docker Compose.
* **Diferenciais:** Arquitetura limpa em camadas, mensageria assíncrona com RabbitMQ, cache de cotações com Redis e pipeline de liquidação desacoplado.

---

### 5. [BankCore Fintech](https://github.com/joaop-gregorioDS/bankcore-fintech)
**Web Banking Corporativo & Clientes Multiplataforma Nativos**  
Plataforma bancária corporativa demonstrativa com serviços de autenticação, transações, Pix interno, extrato e clientes nativos.
* **Stack:** Python (FastAPI), PostgreSQL, Redis, JavaScript, Tauri 2, Kotlin (Jetpack Compose) e Swift (SwiftUI).
* **Status:** 🌐 Em produção na VPS: [bankcore.vortexsoftware.tech](https://bankcore.vortexsoftware.tech)

---

## 📦 Projetos Complementares

| Projeto | Descrição | Tecnologias | Distribuição / Acesso |
| :--- | :--- | :--- | :--- |
| **[Vortex Software](https://github.com/joaop-gregorioDS/vortex-software)** | Site institucional e portal da empresa de software. | React, TypeScript, Tailwind CSS, Nginx | [vortexsoftware.tech](https://vortexsoftware.tech/) |
| **[Neon Video Downloader](https://github.com/joaop-gregorioDS/neon-video-downloader)** | Ferramenta desktop local de alta performance para download de mídias públicas. | Tauri 2, Rust, React, TypeScript, ffmpeg | [GitHub Releases](https://github.com/joaop-gregorioDS/neon-video-downloader/releases) |
| **[JP Moda Minimalista](https://github.com/joaop-gregorioDS/jp-moda-minimalista)** | E-commerce demonstrativo com API e aplicativos mobile nativos. | Next.js, React, Express, MongoDB, Kotlin, SwiftUI | Vercel / Render |
| **[Vision DTC Dashboard](https://github.com/joaop-gregorioDS/vision-ecommerce-dashboard)** | Painel de métricas analíticas e telemetria de e-commerce (CAC, LTV, AOV, Meta CAPI). | React, TypeScript, Vite, Tailwind CSS, Recharts | Vercel |
| **[Gregório Restaurantes](https://github.com/joaop-gregorioDS/gregorio-restaurantes)** | Aplicação de delivery com cardápio digital, carrinho e controle de pedidos. | Node.js, Express, MongoDB, HTML5, CSS3 | Vercel / Render |
| **[Plataforma Macaúba](https://github.com/joaop-gregorioDS/macauba-plataforma)** | Dossiê web interativo e simulador de bioeconomia, SAF, biocombustíveis e carbono. | HTML5 Canvas, JavaScript, CSS3 | Vercel |

---

## 📬 Contato & Canais Institucionais

* **Empresa:** [Vortex Software (vortexsoftware.tech)](https://vortexsoftware.tech/)
* **LinkedIn:** [linkedin.com/in/joaop-gregorio](https://www.linkedin.com/in/joaop-gregorio/)
* **E-mail:** [joaop.gregorio@outlook.com](mailto:joaop.gregorio@outlook.com)
* **GitHub:** [github.com/joaop-gregorioDS](https://github.com/joaop-gregorioDS)
