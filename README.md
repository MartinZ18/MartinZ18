<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=580&lines=Backend+Developer;FastAPI+%7C+Spring+Boot+%7C+n8n;Automatizaci%C3%B3n+con+IA+y+RAG" alt="Backend Developer — FastAPI, Spring Boot, n8n, automatizacion con IA y RAG" />
</div>

<p align="center">
  Backend developer en Mendoza, Argentina 🇦🇷. Construyo APIs REST y automatizo procesos con n8n e IA.<br/>
  Me gusta agarrar un problema manual y repetitivo y sacarlo del medio.
</p>

<p align="center">
  🟢 <strong>Disponible para roles junior backend / AI automation</strong> — remoto o presencial en Mendoza
</p>

<p align="center">
  <a href="https://martinz18.github.io"><img src="https://img.shields.io/badge/Portafolio-martinz18.github.io-1B4DFF?style=for-the-badge" alt="Portafolio" /></a>
  <a href="mailto:martin.zamora004@gmail.com"><img src="https://img.shields.io/badge/Email-martin.zamora004-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/martin-zamora-3893b8295"><img src="https://img.shields.io/badge/LinkedIn-Mart%C3%ADn%20Zamora-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,java,spring,mysql,postgres,mongodb,docker,kubernetes,linux,git&theme=dark" alt="Python, FastAPI, Java, Spring, MySQL, PostgreSQL, MongoDB, Docker, Kubernetes, Linux, Git" />
</p>

- **Backend** — Python · FastAPI · Pydantic · pytest / Java 17 · Spring Boot · Spring Security · JPA · JUnit 5 · Mockito
- **Datos** — MySQL · PostgreSQL con pgvector · SQL Server · MongoDB
- **IA y automatización** — n8n · RAG con embeddings y búsqueda vectorial · Ollama (inferencia local) · Groq · Gemini
- **Infraestructura** — Docker · Kubernetes · GitHub Actions · Linux · pfSense · Active Directory
- **Integraciones** — MercadoPago · Google OAuth · Gmail API · Google Sheets · Telegram Bot API
- **Testing** — Playwright · pytest · JUnit 5 · Mockito

---

## Proyectos

### [AMICANA 2.0](https://github.com/MartinZ18/Amicana-v2.0) — en producción

Sistema de gestión académica para el Instituto Cultural Argentino Norteamericano (Mendoza), usado todos los días por alumnos y personal administrativo. Cobro de cuotas integrado con MercadoPago, calendario académico, seguimiento de progreso, auditoría de cada acción que modifica datos, y **un asistente con RAG** — embeddings de 768 dimensiones en Postgres con pgvector, recuperación por similitud coseno y respuestas restringidas al contexto recuperado. Suite de regresión de 28 casos con Playwright.

<p>
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MercadoPago-009EE3?style=flat&logo=mercadopago&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
</p>

### [RAG en producción](https://github.com/MartinZ18/rag-en-produccion) — documentación técnica

Cómo funciona por dentro el RAG de AMICANA, explicado sobre el código que efectivamente corrió: embeddings, chunking, distancia coseno, el pipeline de ingesta y el de consulta. Incluye **seis fallas reales** con su diagnóstico — entre ellas un índice `ivfflat` mal dimensionado que limitaba cada búsqueda a un solo resultado sin emitir un error. Cinco de las seis devolvían `200 OK`.

<p>
  <img src="https://img.shields.io/badge/RAG-0B7285?style=flat" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Embeddings-5A189A?style=flat" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat" />
</p>

### [Inventario EGI](https://github.com/MartinZ18/Proyecto-Inventario-EGI)

Inventario de equipamiento de laboratorio con autenticación contra Active Directory por LDAP, dos motores de datos conviviendo (SQL Server para lo transaccional, MongoDB para lo documental), desplegado en Kubernetes con 7 NetworkPolicies zero-trust, firewall pfSense y CI/CD sobre runner self-hosted.

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Active%20Directory-0078D4?style=flat&logo=microsoft&logoColor=white" />
</p>

### [n8n Email Incident Classifier](https://github.com/MartinZ18/n8n-email-incident-classifier)

Workflow que detecta incidentes técnicos reportados por Gmail, los clasifica por gravedad con un LLM local (Ollama) y notifica por Telegram solo cuando hace falta escalar. Inferencia local a propósito: el contenido de los correos no sale de la máquina y no hay costo por token.

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Gmail%20API-EA4335?style=flat&logo=gmail&logoColor=white" />
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white" />
</p>

### [Menu JPA](https://github.com/MartinZ18/Menu_Jpa_Springboot) — Spring Boot

API REST sobre una jerarquía grande de entidades (menús, recetas, ingredientes, pedidos, mesas, personal), con Spring Security y JWT, 18 archivos de tests con JUnit 5 y Mockito, y correcciones de seguridad documentadas — un IDOR y un endpoint de autenticación sin límite de intentos, ambos con test de regresión.

<p>
  <img src="https://img.shields.io/badge/Java-17-ED8B00?style=flat&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql&logoColor=white" />
</p>

---

## Cómo trabajo

- **Entiendo el proceso manual antes de automatizarlo.** n8n resuelve poco si no sé qué problema real estoy sacando del medio.
- **Escribo tests para lo que hago.** En AMICANA eso significó pasar de "funciona en mi máquina" a una suite de regresión que corre en cada cambio.
- **Ningún error se traga en silencio.** Degradar con elegancia y ocultar el error son cosas distintas: si una falla es tolerable la registro, si no lo es la propago.

---

<p align="center">
  <a href="https://martinz18.github.io">martinz18.github.io</a> ·
  <a href="mailto:martin.zamora004@gmail.com">martin.zamora004@gmail.com</a> ·
  Mendoza, Argentina
</p>
