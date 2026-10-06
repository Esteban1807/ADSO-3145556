# Informe 1 — Commits en el repositorio de documentación y en los repositorios de tu equipo

**Periodo:** del 25 de agosto al 30 de septiembre de 2026 (hora Colombia, UTC-5)
**Repositorio principal de la ficha:** https://github.com/code-sena/ADSO-3145556

| Campo | Valor |
|---|---|
| Aprendiz | Juan Esteban Ome Esquivel |
| Usuario de GitHub | Esteban1807 |
| Ficha | ADSO-3145556 |
| Proyecto (equipo) | save-your-water (Cuida Tu Agua) |
| Prefijo de los repositorios del equipo | sy-water |
| Correo(s) con el que haces commit | juanome43@gmail.com |
| Fecha de elaboración | 2026-10-06 |

## 1. Resumen

| Repositorio | Enlace | Commits |
|---|---|---|
| `sy-water-docs` | https://github.com/code-sena/sy-water-docs | 23 |
| `sy-water-api` | https://github.com/code-sena/sy-water-api | 0 |
| `sy-water-app` | https://github.com/code-sena/sy-water-app | 0 |
| `sy-water-db` | https://github.com/code-sena/sy-water-db | 0 |
| `sy-water-worker` | https://github.com/code-sena/sy-water-worker | 0 |
| **Total** | | **23** |

## 2. Repositorio de documentación

- **Repositorio:** `sy-water-docs`
- **Enlace:** https://github.com/code-sena/sy-water-docs
- **Total de commits en el periodo:** 23
- **Qué hice (2 a 3 líneas):** Llené la documentación del proyecto sobre el scaffold de gobernanza: contexto, modelo de dominio (bounded contexts, entidades y eventos), arquitectura y ADRs, producto, requisitos y modelos de datos (DDL T-SQL y evaluación de normalización 3FN). Agregué los mockups de las pantallas de autenticación y alineé épicas e historias de usuario con el Product Backlog v2.0.

| Commit ID | Fecha y hora | Mensaje |
|---|---|---|
| [a4eb126](https://github.com/code-sena/sy-water-docs/commit/a4eb126) | 2026-08-31 13:50 | fix(docs): governance correction, requirements and product |
| [6d2909d](https://github.com/code-sena/sy-water-docs/commit/6d2909d) | 2026-09-08 13:55 | feat(context): fill project context with Cuida Tu Agua domain info |
| [c3e196d](https://github.com/code-sena/sy-water-docs/commit/c3e196d) | 2026-09-08 14:23 | feat(domain): fill domain model with bounded contexts, entities, and events |
| [9640ec1](https://github.com/code-sena/sy-water-docs/commit/9640ec1) | 2026-09-08 14:35 | fix(docs): update to single shared database with schema-per-service |
| [5373d19](https://github.com/code-sena/sy-water-docs/commit/5373d19) | 2026-09-08 14:52 | feat(architecture): fill architecture overview, patterns, and ADRs |
| [9da87b0](https://github.com/code-sena/sy-water-docs/commit/9da87b0) | 2026-09-08 15:31 | feat(data): fill data models with T-SQL DDL for all 6 schema |
| [540e775](https://github.com/code-sena/sy-water-docs/commit/540e775) | 2026-09-10 12:27 | feat(product, requirements): fill product definition and requirements sections |
| [382cc93](https://github.com/code-sena/sy-water-docs/commit/382cc93) | 2026-09-12 22:13 | feat(docs): adopt 11 bounded contexts model across all documentation |
| [0f0fc8b](https://github.com/code-sena/sy-water-docs/commit/0f0fc8b) | 2026-09-15 17:21 | refactor(docs): align documentation 00-06 with DBML v5.0 data model |
| [73ed441](https://github.com/code-sena/sy-water-docs/commit/73ed441) | 2026-09-15 17:29 | docs(add): added landing mockup |
| [332414d](https://github.com/code-sena/sy-water-docs/commit/332414d) | 2026-09-15 17:32 | docs(add): added login screen mockup |
| [ba41c70](https://github.com/code-sena/sy-water-docs/commit/ba41c70) | 2026-09-16 12:29 | docs(add): added register screen mockup |
| [88e548f](https://github.com/code-sena/sy-water-docs/commit/88e548f) | 2026-09-16 12:31 | docs(add): added forgot password screen mockup |
| [8051850](https://github.com/code-sena/sy-water-docs/commit/8051850) | 2026-09-16 12:33 | docs(add): added verify email mockup |
| [edab7a8](https://github.com/code-sena/sy-water-docs/commit/edab7a8) | 2026-09-16 17:39 | fix(docs): normalize user story IDs to 3-digit format (HU-0XX) |
| [151f26a](https://github.com/code-sena/sy-water-docs/commit/151f26a) | 2026-09-16 22:25 | refactor: align epics with Product Backlog (16 epics, E1–E16) |
| [6100c08](https://github.com/code-sena/sy-water-docs/commit/6100c08) | 2026-09-16 23:22 | refactor: align epics (16, E1–E16) and HU-001/HU-004/HU-007 fields with the Product Backlog |
| [afedbe9](https://github.com/code-sena/sy-water-docs/commit/afedbe9) | 2026-09-17 14:45 | feat(HU-001): add phone as required field and remove identity document from registration |
| [e7c2f4f](https://github.com/code-sena/sy-water-docs/commit/e7c2f4f) | 2026-09-18 10:10 | feat: add HU-002 home registration and refine valve/auth flows |
| [1446024](https://github.com/code-sena/sy-water-docs/commit/1446024) | 2026-09-18 13:14 | refactor: restructure epics to 15-epic model and reorganize by delivery |
| [423dbb5](https://github.com/code-sena/sy-water-docs/commit/423dbb5) | 2026-09-22 13:49 | docs: add normalization-assessment.md with detailed 3NF analysis and denormalization trade-offs |
| [56cde17](https://github.com/code-sena/sy-water-docs/commit/56cde17) | 2026-09-23 03:27 | docs: align 8 documentation files with Product Backlog v2.0 — ~70 corrections across roles, HU numbering, SP totals, roadmap, traceability, and entity rules |
| [0bc4c8d](https://github.com/code-sena/sy-water-docs/commit/0bc4c8d) | 2026-09-26 01:23 | docs: add ADR-003 (single UUID PK) and ADR-004 (CO/EC market scope); update models.md with location catalog and city_id |

## 3. Repositorios del equipo

### 3.1 `sy-water-api`

- **Enlace:** https://github.com/code-sena/sy-water-api
- **Total de commits en el periodo:** 0
- **Qué hice (2 a 3 líneas):** No tengo commits en este repositorio en el periodo.

_Sin commits en el periodo._

### 3.2 `sy-water-app`

- **Enlace:** https://github.com/code-sena/sy-water-app
- **Total de commits en el periodo:** 0
- **Qué hice (2 a 3 líneas):** No tengo commits en este repositorio en el periodo.

_Sin commits en el periodo._

### 3.3 `sy-water-db`

- **Enlace:** https://github.com/code-sena/sy-water-db
- **Total de commits en el periodo:** 0
- **Qué hice (2 a 3 líneas):** No tengo commits en este repositorio en el periodo.

_Sin commits en el periodo._

### 3.4 `sy-water-worker`

- **Enlace:** https://github.com/code-sena/sy-water-worker
- **Total de commits en el periodo:** 0
- **Qué hice (2 a 3 líneas):** No tengo commits en este repositorio en el periodo.

_Sin commits en el periodo._

## 4. Verificación del aprendiz

- [x] Todos los commits listados los hice con mi cuenta (aparece mi foto de perfil en GitHub).
- [x] Incluí los commits de **todas las ramas**, no solo de `main`.
- [x] Todos los commits caen entre el 25 de agosto y el 30 de septiembre de 2026 (hora Colombia).
- [x] Cada enlace de commit abre en GitHub.
- [x] Los repositorios en los que no tengo commits quedaron en la tabla con 0.
- [x] El total de cada repositorio coincide con el número de filas de su tabla.

## 5. Observaciones

- El periodo de este informe es del 25 de agosto al 30 de septiembre de 2026, según la indicación recibida (los repositorios de equipo se crearon el 25 de agosto).
- No se cuentan dos entradas locales de `git stash` (`0b38dc6`, `b028777`) que aparecen con `git log --all` pero nunca se subieron a GitHub, ni el commit inicial del scaffold (`c5ae388`), que es del instructor.
- El desarrollo de backend, base de datos y frontend del proyecto se hizo en la organización `cuida-tu-agua` (no en `code-sena/sy-water-api`, `-app`, `-db` ni `-worker`); esos commits están en el Informe 2.

---

*Declaro que la información de este informe es veraz y que los commits listados son de mi autoría.*

**Aprendiz:** Juan Esteban Ome Esquivel  **Fecha:** 2026-10-06
