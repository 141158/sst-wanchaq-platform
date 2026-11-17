# Sistema Web y Móvil para la Gestión, Acreditación Geolocalizada e Impacto Sostenible de Capacitaciones en SST — Municipalidad Distrital de Wanchaq

[![Metodología](https://img.shields.io/badge/Metodolog%C3%ADa-SCRUM-0052CC?logo=jira)](https://sstcuscowanchaq.atlassian.net)
[![Backend](https://img.shields.io/badge/Backend-Node.js%20%2F%20NestJS-E0234E?logo=nestjs)](https://nestjs.com/)
[![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript%20%2B%20Tailwind-61DAFB?logo=react)](https://react.dev/)
[![Mobile](https://img.shields.io/badge/Mobile-Flutter%20%2B%20Dart-02569B?logo=flutter)](https://flutter.dev/)
[![Database](https://img.shields.io/badge/DB-PostgreSQL%20%2B%20MongoDB-336791?logo=postgresql)](https://www.postgresql.org/)

Plataforma integral web y móvil diseñada para gestionar, monitorear y certificar las capacitaciones obligatorias de **Seguridad y Salud en el Trabajo (Ley N° 29783 y R.M. 050-2013-TR)** del personal operativo de la **Municipalidad Distrital de Wanchaq (Cusco)**, incorporando control de asistencia en campo mediante **código QR dinámico + geolocalización (geocerca GPS)**, certificación digital verificable y métricas de impacto sostenible en estricto cumplimiento de la **Ley de Protección de Datos Personales (Ley N° 29733 - LPDP)**.

---

## 📋 Datos Académicos

- **Curso:** Ingeniería de Software I
- **Universidad:** Universidad Nacional de San Antonio Abad del Cusco (UNSAAC)
- **Caso de Estudio:** Personal Operativo y de Obras Públicas — Municipalidad Distrital de Wanchaq (Cusco)
- **Tablero Scrum (Jira):** [sstcuscowanchaq.atlassian.net](https://sstcuscowanchaq.atlassian.net)

---

## 👥 Equipo Scrum

| Integrante | Código | Rol Scrum | Responsabilidad Principal |
| :--- | :---: | :--- | :--- |
| **Cesar Andersson Saire Hancco** | `141158` | **Scrum Master** | Facilitación de ceremonias Scrum, gestión de impedimentos, cumplimiento de DoD y aspectos ético-legales (LPDP). |
| **Andy Yoseph Quispe Huanca** | `221949` | **Product Owner** | Gestión y priorización del Product Backlog, criterios de aceptación y alineamiento con normativa SST (Ley 29783). |
| **Abelardo Ttito Quispe** | `192430` | **Developer 1 (Fullstack / Lead Backend)** | Arquitectura REST API en Node.js (NestJS), modelado PostgreSQL/MongoDB, seguridad JWT y generación de certificados PDF/QR. |
| **Jean Marco Pacha Quispe** | `164246` | **Developer 2 (Mobile / Frontend)** | Desarrollo de aplicación móvil en Flutter (escaneo QR y geolocalización GPS) e interfaz web en React + TypeScript + Tailwind CSS. |

---

## 🏗️ Stack Tecnológico

- **Backend:** Node.js (NestJS) + TypeScript (REST API)
- **Frontend Web:** React + TypeScript + Tailwind CSS
- **Aplicación Móvil:** Dart + Flutter (Android / iOS)
- **Bases de Datos:**
  - **PostgreSQL:** Datos relacionales (usuarios, roles, sedes georreferenciadas, cursos SST, sesiones, asistencias y certificados).
  - **MongoDB:** Logs inmutables de auditoría LPDP, intentos de validación GPS y analítica de evaluaciones.
- **Gestión y Colaboración:** Jira Software (Scrum integrado con GitHub), GitHub, Figma, Discord/WhatsApp.

---

## 🧩 Estructura de Módulos (Épicas en Jira)

1. **EP-1 (`SCRUM-5`):** Gestión de Usuarios, Roles y Zonas Operativas (Wanchaq) + Cumplimiento LPDP.
2. **EP-2 (`SCRUM-6`):** Catálogo de Capacitaciones SST (Ley 29783) y Materiales.
3. **EP-3 (`SCRUM-7`):** Monitoreo, Control de Asistencia Móvil, QR Dinámico y Geolocalización.
4. **EP-4 (`SCRUM-8`):** Aplicación Móvil para Personal Operativo (Capacitandos).
5. **EP-5 (`SCRUM-9`):** Sistema de Evaluaciones Automatizadas, Alertas y Certificación PDF/QR.
6. **EP-6 (`SCRUM-10`):** Analítica, Cumplimiento SUNAFIL (R.M. 050-2013-TR) e Impacto Sostenible.

---

## 📁 Estructura del Repositorio

```text
sst-wanchaq-platform/
├── docs/
│   ├── Entrega_1_SST_Wanchaq.md   # Documentación Parcial (Cap. I y Bosquejo Cap. II)
│   ├── Entrega_1_SST_Wanchaq.tex  # Informe en LaTeX listo para Overleaf (sin carátula)
│   └── imagenes/                  # Capturas oficiales de Jira y GitHub (Entrega Nro. 1)
├── backend/                       # (Próximo en Sprint 1-2) API REST Node.js (NestJS)
├── web/                           # (Próximo en Sprint 1-2) Plataforma Web React + TS + Tailwind
├── mobile/                        # (Próximo en Sprint 2) Aplicación Móvil Flutter
├── .gitignore
└── README.md
```

---

## 📅 Cronograma de Entregables

- **Entrega Nro. 1 (Semana 2):** Documentación Parcial — Capítulo I (Datos Generales) y Bosquejo del Capítulo II (Product Backlog inicial priorizado en Jira, Plan de Sprints y Definition of Done con LPDP). ✅ *En curso*
- **Entrega Nro. 2 (Semana 6):** Documentación ampliada (Cap. I, II mejorado y Bosquejo del III) + Sistema funcional al 50% (Autenticación, Gestión de Cursos/Usuarios y App Móvil con marcado QR/GPS).
- **Entrega Nro. 3 (Semana 16):** Informe Final Completo (Capítulos I al VII), código fuente completo y sistema desplegado al 100% en Cloud.
