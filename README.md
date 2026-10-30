<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:8957e5&height=190&section=header&text=Arturo%20Orea&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Junior%20Backend%20Developer&descSize=20&descAlignY=58" alt="Arturo Orea, Junior Backend Developer" width="100%" />

<a href="https://github.com/arturooreaf">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=Node.js+%C2%B7+TypeScript+%C2%B7+PostgreSQL;Building+e-prescription+APIs+in+healthcare;GDPR-compliant+by+design;Tests+ship+with+the+code" alt="Node.js · TypeScript · PostgreSQL" />
</a>

Madrid, Spain · Dual vocational training student (DAM) · Backend developer at a healthtech company

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arturo--orea-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/arturo-orea)
[![Email](https://img.shields.io/badge/Email-aoreaf@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aoreaf@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=arturooreaf&color=8957e5&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## About me

I build **REST APIs in a regulated environment**: an **e-prescription platform** for the healthcare sector, where health data is a special category under the **GDPR** and every technical decision has legal consequences.

I combine work with a Higher Vocational Degree in **Multiplatform Application Development** (DAM, Colegio Retamar, 2025–2027). I'm looking to keep growing as a backend developer on real, demanding projects.

## What I'm working on

**Backend Developer · Healthtech company, Madrid** (07/2026 – present)

- **Full authentication system:** doctor sign-up, login, revocable **JWT** sessions, **TOTP** two-factor authentication and password recovery.
- **Per-doctor data isolation:** no doctor can access another doctor's patients. It's a legal requirement, not a design preference.
- **CIMA integration** (Spanish Agency of Medicines) to sync the national drug catalog.
- **CGCOM integration** (General Council of Medical Associations) to verify each doctor's license to practice, with **RS512**-signed tokens and auditing of every response in the database.
- Identified **seven regulatory validation requirements** missing from the project specification, before reaching the certification phase.

## Featured project

### [clinica-api](https://github.com/arturooreaf/clinica-api)

[![CI](https://github.com/arturooreaf/clinica-api/actions/workflows/ci.yml/badge.svg)](https://github.com/arturooreaf/clinica-api/actions/workflows/ci.yml)

REST API for a clinic (patients, appointments and authentication), built the way I work professionally.

- **Layered architecture:** routes → controller → service → repository, organized by domain module.
- **Per-user data ownership:** a user can never read or modify another user's patients.
- **Integration tests against a real PostgreSQL**, run in CI on every push with a Postgres service container.
- **Production-ready setup:** multi-stage Docker image, versioned migrations, structured logging, rate limiting and OpenAPI docs.

`TypeScript` `Express 5` `PostgreSQL` `JWT` `bcrypt` `Jest` `Supertest` `Docker` `GitHub Actions`

## More projects

| Project | What it is | Stack |
|---|---|---|
| [**CRUD-Practice**](https://github.com/arturooreaf/CRUD-Practice) | Full-stack patient management with schema validation and one-command startup | Express · TypeScript · Prisma · Zod · Next.js · PostgreSQL · Docker Compose |
| [**gamelog**](https://github.com/arturooreaf/gamelog) | REST API to track your video game collection, built around the repository pattern, with unit-tested domain rules | Java 21 · Spring Boot · JUnit 5 |
| [**DAM2**](https://github.com/arturooreaf/DAM2) | Coursework from the second year of DAM | Java · JavaFX · PHP · React Native · Python · Odoo |

## Tech stack

**Working with**

<p>
  <img src="https://skillicons.dev/icons?i=ts,nodejs,express,postgres,jest,docker,gitlab,git&theme=dark" alt="TypeScript, Node.js, Express, PostgreSQL, Jest, Docker, GitLab CI, Git" />
</p>

**Familiar with**

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,js,prisma,nextjs&theme=dark" alt="Java, Spring Boot, JavaScript, Prisma, Next.js" />
</p>

Also: SQL, Swagger / OpenAPI, JWT, Zod.

**Learning**

<p>
  <img src="https://skillicons.dev/icons?i=php,py&theme=dark" alt="PHP, Python" />
</p>

## How I work

- **Tests ship with the code**, not afterwards if there's time left.
- **Tickets and peer review:** I work with Linear and merge requests reviewed by a senior developer.
- **Commits in English** following [Conventional Commits](https://www.conventionalcommits.org/).
- **Secure by default:** hashed passwords, parameterized queries, rate limiting and secrets kept out of the code.
- **Reviewable code:** linting, automatic formatting and type checking before every delivery.

## Languages

Spanish (native) · English (B1)

## GitHub activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=arturooreaf&show_icons=true&hide_rank=true&hide_border=true&theme=tokyonight&bg_color=00000000&count_private=true" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arturooreaf&layout=compact&hide_border=true&theme=tokyonight&bg_color=00000000&langs_count=6&hide=powershell,shell,batchfile" alt="Top languages" height="165" />

<img src="https://streak-stats.demolab.com?user=arturooreaf&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/arturooreaf/arturooreaf/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/arturooreaf/arturooreaf/output/github-snake.svg" alt="Snake eating my contribution graph" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:8957e5&height=110&section=footer" alt="" width="100%" />
