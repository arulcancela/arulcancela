<h1 align="center">Hola, soy Raúl</h1>

<h3 align="center">AI-Augmented Engineer &amp; Cloud Automation Architect</h3>

<p align="center">
  <em>Más de una década de experiencia · Arquitectura Cloud &amp; Google Workspace · Automatización Enterprise con GAM y Python</em>
</p>

<p align="center">
  No programo desde cero: <strong>orquesto IA para diseñar y construir soluciones enterprise, validando cada resultado con rigor</strong>.
</p>

<p align="center">
  <a href="https://arulcancela.github.io/"><img src="https://img.shields.io/badge/Portfolio-arulcancela.github.io-1f2933?logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/arulcancela/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://arulcancela.github.io/CV_Raul_Cancela_ES.pdf"><img src="https://img.shields.io/badge/CV%20(ES)-PDF-red?logo=adobeacrobatreader&logoColor=white" alt="CV Español"></a>
  <a href="https://arulcancela.github.io/CV_Raul_Cancela_EN.pdf"><img src="https://img.shields.io/badge/CV%20(EN)-PDF-blue?logo=adobeacrobatreader&logoColor=white" alt="CV English"></a>
</p>

---

## En qué creo

Llevo más de una década diseñando infraestructuras cloud, migrando empresas a Google Workspace y automatizando procesos a escala. Hoy trabajo en la intersección de tres pilares:

- **Google Workspace & Cloud a escala enterprise** → identidad, gobierno, seguridad, coexistencia M365/Workspace, GAM.
- **Automatización robusta con Python** → transformar tareas operativas críticas en herramientas CLI, APIs y flujos reproducibles.
- **Ingeniería aumentada con IA** → formulación analítica del problema, arquitectura desacoplada y orquestación de IA (Gemini, Claude, DeepSeek) con **validación continua mediante tests automatizados**.

Mi valor no radica en picar código repetitivo, sino en **resolver el problema correcto con una arquitectura que aguanta en producción**.

---

## Proyectos destacados (Portfolio Verificable)

### 1. [workspace-tenant-auditor](https://github.com/arulcancela/workspace-tenant-auditor)

> Audita la configuración de seguridad y cumplimiento de un tenant de Google Workspace, ejecutando 12 comprobaciones críticas y generando informes ejecutivos en HTML/PDF/JSON priorizados por severidad.

[![CI](https://github.com/arulcancela/workspace-tenant-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/arulcancela/workspace-tenant-auditor/actions)
![Python](https://img.shields.io/badge/python-3.11%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

| | |
|---|---|
| **Stack** | Python 3.11+ · Admin SDK · Reports API · Jinja2 · WeasyPrint · Typer |
| **Seguridad** | Service Account con Domain-Wide Delegation (mínimo privilegio: solo lectura) |
| **Calidad** | 60+ tests automatizados · 78% cobertura · CI con GitHub Actions · Docker |
| **Modos** | Modo demostración sin credenciales · informes ejecutivos HTML/PDF/JSON |

**[Ver repositorio](https://github.com/arulcancela/workspace-tenant-auditor)** · **[Explicación sin jerga](https://github.com/arulcancela/workspace-tenant-auditor/blob/main/EXPLAINER.md)** · **[Arquitectura](https://github.com/arulcancela/workspace-tenant-auditor/blob/main/ARCHITECTURE.md)**

---

### 2. [agente-deepseek](https://github.com/arulcancela/agente-deepseek)

> Agente de administración autónoma de Linux en lenguaje natural, con diseño seguro por defecto: clasifica acciones, bloquea comandos destructivos y valida comandos encadenados.

- **Stack:** Python · DeepSeek API · Rich · Pytest · GitHub Actions CI.
- **Seguridad:** Módulo propio con lista negra y parser que previene inyecciones de comandos peligrosos (`ls && rm -rf /` bloqueado).
- **Calidad:** 18 tests automatizados en CI.

**[Ver repositorio](https://github.com/arulcancela/agente-deepseek)**

---

### 3. [agente-escritor](https://github.com/arulcancela/agente-escritor)

> Pipeline multi-agente en Python que investiga en la web, redacta, evalúa y refina documentos técnicos de forma autónoma con RAG y exportación a PDF/DOCX.

- **Stack:** Python · LLMs (DeepSeek) · RAG · Streamlit · SQLite.
- **Flujo:** Pipeline por etapas (`INGEST` → `RESEARCH` → `WRITE` → `REVIEW` → `REFINE` → `FINALIZE`).

**[Ver repositorio](https://github.com/arulcancela/agente-escritor)**

---

### 4. [linkedin-job-hunter](https://github.com/arulcancela/linkedin-job-hunter)

> Sistema automatizado que busca ofertas de empleo, las evalúa cuantitativamente contra un perfil profesional mediante un LLM (fit score 0-100) y genera cartas de presentación personalizadas con alertas a Notion y Telegram.

- **Stack:** Python · Pydantic · Gemini / DeepSeek API · Notion API · Telegram Bot.
- **Calidad:** 16 tests automatizados con CI y validación de anonimización de datos.

**[Ver repositorio](https://github.com/arulcancela/linkedin-job-hunter)**

---

### 5. [url-shortener](https://github.com/arulcancela/url-shortener)

> Acortador de URLs full-stack con analíticas de clics en tiempo real, códigos QR y rate limiting distribuido. Desplegado en producción.

- **Stack:** Next.js 14 · TypeScript · Prisma · PostgreSQL · NextAuth · Vercel · Playwright.
- **Calidad:** 41 tests unitarios + tests end-to-end (E2E) con Playwright y CI.

**[Ver repositorio](https://github.com/arulcancela/url-shortener)**

---

## Stack y tecnologías

<p>
  <img src="https://img.shields.io/badge/Google%20Workspace-4285F4?logo=googleworkspace&logoColor=white" alt="Google Workspace">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/GAM-5A5A5A?logo=google&logoColor=white" alt="GAM">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
</p>

`Google Workspace` · `GAM` · `Python` · `Admin SDK` · `Reports API` · `Service Accounts` · `DWD / OAuth2` · `Coexistencia M365/Google` · `Docker` · `CI/CD` · `LLMs (Gemini, Claude, DeepSeek)` · `Ollama` · `Next.js` · `TypeScript`

---

## Estado actual & Disponibilidad

- **Disponibilidad:** **Inmediata**. Abierto a roles en **Arquitectura Cloud**, **Google Workspace Enterprise**, **Automatización con Python / GAM** y **Entornos Aumentados con IA** (Remoto prioritario o híbrido en Madrid).
- Profundizando en herramientas de auditoría, gobernanza y postura de seguridad cloud.
- Explorando flujos de agentes autónomos y desarrollo con IA validado iterativamente.

---

## Contacto

<p>
  <a href="https://arulcancela.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-arulcancela.github.io-1f2933?logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/arulcancela/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:arulcancela@gmail.com">
    <img src="https://img.shields.io/badge/Email-arulcancela%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email">
  </a>
</p>
