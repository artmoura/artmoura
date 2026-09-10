<h1 align="center">Arthur Moura</h1>

<p align="center">
  <b>Senior Software Engineer &amp; Tech Lead</b><br>
  <sub>Vinhedo, Brazil · Founder of Trykat</sub>
</p>

<p align="center">
  <i>I replace legacy systems that companies can't afford to turn off.</i><br>
  <sub>Ten years building the software that runs the operation — ERP, logistics and fiscal — and the AWS infrastructure underneath it.</sub>
</p>

<p align="center">
  <a href="https://artmoura.com"><img src="https://img.shields.io/badge/artmoura.com-006A9C?style=for-the-badge&logo=astro&logoColor=white" alt="Site"></a>
  <a href="https://linkedin.com/in/artmoura"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:arthurjm95@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<br>

## 🏗️ What I'm building

I lead engineering for a retail group of four companies — **12 stores, 5 distribution
centers and a factory** on one platform.

| System | Scale |
| :--- | :--- |
| **[ERP](https://artmoura.com/#cases)** replacing a 25-year-old legacy | Rails 8.1 · PostgreSQL · Next.js — 64 models, 143 migrations, 178 specs |
| **[Logistics & shipping](https://artmoura.com/#cases)** | ~20k orders/month · offline-first Flutter app for drivers and pickers |
| **[Partner platform](https://artmoura.com/#cases)** | 7,000+ architects · 99.9% uptime · idempotent async rewards |
| **Serverless integration** | Python on Lambda · DynamoDB single-table · keeps legacy and new in sync |

The legacy isn't being migrated — it's replaced module by module, with the operation
online and no maintenance window.

The hard part was never the CRUD. It's Brazilian tax law: NF-e and NFC-e issuing, SEFAZ
integration, digital certificates, DANFE, tax rules across NCM, CEST, CFOP and ICMS, plus
CNAB bank files for billing.

The ERP also ships with the new VAT model alongside the current one — Brazil's tax reform
is coming, and a system that doesn't follow it simply stops issuing invoices.

<br>

## 🛠️ Stack

<p align="center"><b>Backend</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=rails" width="44" alt="Rails"><br><sub><b>Rails</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=ruby" width="44" alt="Ruby"><br><sub><b>Ruby</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=python" width="44" alt="Python"><br><sub><b>Python</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=postgres" width="44" alt="Postgres"><br><sub><b>PostgreSQL</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=redis" width="44" alt="Redis"><br><sub><b>Redis</b></sub></td>
</tr></table>

<p align="center"><b>Frontend &amp; Mobile</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=ts" width="44" alt="TypeScript"><br><sub><b>TypeScript</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=react" width="44" alt="React"><br><sub><b>React</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=nextjs" width="44" alt="Next.js"><br><sub><b>Next.js</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=tailwind" width="44" alt="Tailwind"><br><sub><b>Tailwind</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=flutter" width="44" alt="Flutter"><br><sub><b>Flutter</b></sub></td>
</tr></table>

<p align="center"><b>Infrastructure</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=aws" width="44" alt="AWS"><br><sub><b>AWS</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=docker" width="44" alt="Docker"><br><sub><b>Docker</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=githubactions" width="44" alt="Actions"><br><sub><b>GH Actions</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=git" width="44" alt="Git"><br><sub><b>Git</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=linux" width="44" alt="Linux"><br><sub><b>Linux</b></sub></td>
</tr></table>

<p align="center">
  <sub>On AWS: ECS, ECR, Lambda, DynamoDB, SNS and S3 — an environment I designed and built<br>
  myself, with continuous deploy and Slack notifications at every stage. No separate infra team.</sub>
</p>

<br>

## 🧭 How I work

I go to the operation floor and watch someone use the system before designing anything.
Requirements are usually wrong until you see the workaround people invented to survive the
old software.

Nothing ships without a rollback path. When the system you're replacing is the one paying
the bills, "we'll fix it tomorrow" is not a plan.

Multi-tenant from day one: a single identity and permission layer serves group, company and
branch — four businesses on one codebase instead of four systems to maintain.

Boring technology, tested. Rails and Postgres solve more problems than the stack of the
month, and RSpec catches what code review misses.

<br>

## 📊 Last 12 months

<p align="center">
  <sub>Most of my work lives in private repositories, so the graph doesn't tell the story:</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Commits-2%2C140-006A9C?style=for-the-badge" alt="2140 commits">
  <img src="https://img.shields.io/badge/Days_with_code-232-006A9C?style=for-the-badge" alt="232 days">
  <img src="https://img.shields.io/badge/Per_active_day-~9_commits-006A9C?style=for-the-badge" alt="9 commits per day">
  <img src="https://img.shields.io/badge/Repositories-11-006A9C?style=for-the-badge" alt="11 repositories">
</p>

<p align="center"><sub>Measured in September 2026</sub></p>

<br>

## 💬 Let's talk

I work with companies across Brazil. If your system is old and nobody can tell you whether
it survives the next year, that diagnosis is what I do.

<p align="center">
  <a href="https://artmoura.com"><img src="https://img.shields.io/badge/See%20the%20cases%20at%20artmoura.com-006A9C?style=for-the-badge&logo=astro&logoColor=white" alt="Cases"></a>
</p>

<br>

---

<details>
<summary><b>🇧🇷 Ler em português</b></summary>

<br>

<p align="center">
  <b>Engenheiro de Software Sênior &amp; Tech Lead</b><br>
  <sub>Vinhedo, SP · Fundador da Trykat</sub>
</p>

<p align="center">
  <i>Substituo sistemas legados que a empresa não pode desligar.</i><br>
  <sub>Dez anos construindo o software que roda a operação — ERP, logística e fiscal — e a infraestrutura AWS embaixo dele.</sub>
</p>

### 🏗️ O que eu construo

Lidero a engenharia de um grupo de varejo com quatro empresas — **12 lojas, 5 centros de
distribuição e uma fábrica** na mesma plataforma.

| Sistema | Escala |
| :--- | :--- |
| **[ERP](https://artmoura.com/#cases)** substituindo um legado de 25 anos | Rails 8.1 · PostgreSQL · Next.js — 64 modelos, 143 migrations, 178 specs |
| **[Logística e expedição](https://artmoura.com/#cases)** | ~20 mil pedidos/mês · app Flutter offline-first para motoristas e separadores |
| **[Plataforma de parceiros](https://artmoura.com/#cases)** | 7.000+ arquitetos · 99,9% de disponibilidade · recompensas assíncronas idempotentes |
| **Integração serverless** | Python em Lambda · DynamoDB single-table · mantém legado e novo em sincronia |

O legado não está sendo migrado — está sendo substituído por partes, com a operação no ar
e sem janela de parada.

A parte difícil nunca foi o CRUD: é o fiscal brasileiro. NF-e e NFC-e, integração com a
SEFAZ, certificado digital, DANFE, tributação de NCM, CEST, CFOP e ICMS, além de CNAB
para cobrança.

E o ERP já nasce com o modelo de IVA no lugar, ao lado da tributação atual — porque
sistema que não acompanhar a reforma tributária simplesmente para de emitir nota.

<br>

### 🛠️ Stack

<p align="center"><b>Backend</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=rails" width="44" alt="Rails"><br><sub><b>Rails</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=ruby" width="44" alt="Ruby"><br><sub><b>Ruby</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=python" width="44" alt="Python"><br><sub><b>Python</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=postgres" width="44" alt="Postgres"><br><sub><b>PostgreSQL</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=redis" width="44" alt="Redis"><br><sub><b>Redis</b></sub></td>
</tr></table>

<p align="center"><b>Frontend &amp; Mobile</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=ts" width="44" alt="TypeScript"><br><sub><b>TypeScript</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=react" width="44" alt="React"><br><sub><b>React</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=nextjs" width="44" alt="Next.js"><br><sub><b>Next.js</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=tailwind" width="44" alt="Tailwind"><br><sub><b>Tailwind</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=flutter" width="44" alt="Flutter"><br><sub><b>Flutter</b></sub></td>
</tr></table>

<p align="center"><b>Infraestrutura</b></p>

<table align="center"><tr>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=aws" width="44" alt="AWS"><br><sub><b>AWS</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=docker" width="44" alt="Docker"><br><sub><b>Docker</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=githubactions" width="44" alt="Actions"><br><sub><b>GH Actions</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=git" width="44" alt="Git"><br><sub><b>Git</b></sub></td>
  <td align="center" width="88"><img src="https://skillicons.dev/icons?i=linux" width="44" alt="Linux"><br><sub><b>Linux</b></sub></td>
</tr></table>

<p align="center">
  <sub>Na AWS: ECS, ECR, Lambda, DynamoDB, SNS e S3 — ambiente desenhado e montado por mim,<br>
  com deploy contínuo e aviso no Slack em cada etapa. Sem time de infra separado.</sub>
</p>

<br>

### 🧭 Como eu trabalho

Vou até o chão da operação ver alguém usar o sistema antes de desenhar qualquer coisa.
Requisito quase sempre está errado até você ver a gambiarra que a pessoa inventou para
sobreviver ao software velho.

Nada sobe sem caminho de volta. Quando o sistema que você está substituindo é o que paga
as contas, "amanhã a gente arruma" não é plano.

Multiempresa desde o primeiro dia: uma camada única de identidade e permissão serve grupo,
empresa e filial — quatro negócios sobre uma base, em vez de quatro sistemas para manter.

Tecnologia chata, testada. Rails e Postgres resolvem mais problema que a stack do mês, e
RSpec pega o que code review deixa passar.

<br>

### 📊 Últimos 12 meses

<p align="center">
  <sub>Quase todo o meu trabalho está em repositório privado, então o gráfico não conta a história:</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Commits-2.140-006A9C?style=for-the-badge" alt="2140 commits">
  <img src="https://img.shields.io/badge/Dias_com_c%C3%B3digo-232-006A9C?style=for-the-badge" alt="232 dias">
  <img src="https://img.shields.io/badge/Por_dia_ativo-~9_commits-006A9C?style=for-the-badge" alt="9 commits por dia">
  <img src="https://img.shields.io/badge/Reposit%C3%B3rios-11-006A9C?style=for-the-badge" alt="11 repositorios">
</p>

<p align="center"><sub>Levantado em setembro de 2026</sub></p>

<br>

### 💬 Vamos conversar

Atendo empresas em todo o Brasil. Se o seu sistema é antigo e ninguém sabe dizer se ele
aguenta o próximo ano, esse é o diagnóstico que eu faço.

<p align="center">
  <a href="https://artmoura.com"><img src="https://img.shields.io/badge/Ver%20os%20cases%20em%20artmoura.com-006A9C?style=for-the-badge&logo=astro&logoColor=white" alt="Cases"></a>
</p>

<br>

---

</details>
