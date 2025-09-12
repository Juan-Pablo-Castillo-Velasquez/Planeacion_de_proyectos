# 📑 Acta de Constitución del Proyecto

**Proyecto:** Plataforma de Gestión y Reservas para Agencia de Viajes  
**Fecha de elaboración:** 12/09/2025  
**Lugar:** Bogotá, Colombia  
**Repositorio:** https://github.com/Juan-Pablo-Castillo-Velasquez/Planeacion_de_proyectos  
**Responsable principal:** Juan Pablo Castillo

---

## 🧾 1. Antecedentes

Las agencias de viajes pequeñas y medianas dependen de métodos manuales (Excel, correos, llamadas) para gestionar clientes, paquetes y reservas. Esto causa duplicidad, errores, lentitud y pérdida de competitividad frente a plataformas digitales.  

Este proyecto propone una **plataforma modular** que digitalice procesos y ofrezca una experiencia ágil y confiable.

---

## ❗ 2. Problema

- Errores en reservas e itinerarios.  
- Falta de visibilidad de precios y disponibilidad en tiempo real.  
- Pérdida de confianza y clientes frente a plataformas digitales.

---

## 🎯 3. Objetivo general

Desarrollar una plataforma web/móvil modular para gestionar clientes, reservas y paquetes turísticos, con un **API de analítica en Python** que genere métricas, reportes y tableros para la toma de decisiones.

---

## 🎯 4. Objetivos específicos

- Construir un CRUD base escalable (clientes, paquetes, reservas, proveedores).  
- Diseñar módulos independientes: reservas, pagos, itinerarios, proveedores, usuarios.  
- Implementar un **API en Python** para analítica de datos (KPIs, tendencias, ventas).  
- Crear paneles dinámicos y exportables.  
- Establecer pipelines CI/CD y despliegue contenedorizado en Kubernetes.

---

## 🧭 5. Alcance

| Incluye ✅ | No incluye (etapa inicial) ❌ |
|---|---|
| Backend modular (Express + TypeScript) | Pasarelas de pago en producción |
| Frontend (React + TypeScript) | Cumplimiento PCI-DSS/GDPR avanzado |
| API de analítica (Python) | |
| Reportes y dashboards | |
| Docker, Kubernetes, CI/CD | |

---

## 👥 6. Usuarios objetivo

- **Clientes viajeros** (usuarios finales).  
- **Agencias pequeñas/medianas** (administración).  
- **Proveedores turísticos** (hoteles, transportes, guías).

---

## 📦 7. Entregables

1. CRUD modular (clientes, paquetes, reservas).  
2. API de analítica en Python conectada a DB.  
3. Panel administrativo con gráficas y reportes.  
4. Módulo de proveedores e itinerarios.  
5. Integraciones con APIs externas (mapas, clima, pagos simulados).  
6. Contenedores Docker + manifiestos Kubernetes básicos.  
7. Pipelines CI/CD (GitHub Actions / GitLab CI).  
8. Documentación técnica y manual de usuario.

---

## 🗓️ 8. Plan por fases (cronograma tentativo)

| Fase | Objetivo | Duración estimada |
|---|---|---:|
| Fase 1 | CRUD modular (clientes, paquetes, reservas) | 4 semanas |
| Fase 2 | Módulo de reservas con comprobantes y reportes | 4 semanas |
| Fase 3 | API de analítica en Python + panel de métricas | 6 semanas |
| Fase 4 | Itinerarios, roles, notificaciones | 6 semanas |
| Fase 5 | Integración externas y despliegue en Kubernetes | 6–8 semanas |

> *Duraciones estimadas. Ajustar según disponibilidad y prioridad.*

---

## 🛠️ 9. Metodología y herramientas

Enfoque: **iterativo y modular** (Scrum / Kanban según necesidad).  

### Herramientas clave

- **Git** — control de versiones local (commits, branches, merges).  
- **GitHub** — repositorio remoto, pull requests, issues, GitHub Actions (CI/CD).  
- **Jira** — gestión ágil: historias, sprints, tableros y seguimiento.  
- **Docker / Kubernetes** — contenedorización y orquestación.  
- **MySQL** (o DB relacional) — almacenamiento principal.  
- **Python** — API de analítica y scripts de ETL/ML básicos.

### Flujo propuesto (Git + GitHub + Jira)

1. Crear historia/tarea en **Jira** (ej. "CRUD clientes").  
2. Abrir rama en **GitHub**: `feature/<tarea>` (ej. `feature/crud-clientes`).  
3. Desarrollo local con **Git** → commits claros y atómicos.  
4. Push a la rama remota y abrir **Pull Request** en GitHub.  
5. Revisiones de código (PR), pruebas automáticas (CI) y aprobación.  
6. Merge a `main`/`develop` y cerrar la tarea en **Jira**.

---

## 🧑‍🤝‍🧑 10. Recursos y responsables

| Integrante | Rol / Responsabilidades |
|---|---|
| Juan Pablo Castillo | Responsable principal — Backend (Express/TS), API Python, despliegue |
| Jhohan | Frontend — React (TS) + UI/UX |
| Brayan | DevOps — Docker, Kubernetes, CI/CD pipelines |
| Jhon | QA — Testing automatizado, revisión y documentación |
| Fernando | Integraciones — APIs externas y módulos adicionales |

**Recursos técnicos:** GitHub, MySQL, Docker, Kubernetes (staging), entorno CI (Actions/GitLab CI), Jira/Trello.

---

## ⚠️ 11. Riesgos y mitigación

- **Limitaciones:** poca experiencia en pagos online y seguridad avanzada.  
- **Riesgos:** retrasos por aprendizaje, incompatibilidades entre módulos, sobrecarga del equipo.  
- **Mitigación:** priorizar MVP por fase, usar pagos simulados, pruebas en entornos sandbox, revisiones de seguridad antes de producción.

---

## ✅ 12. Compromisos

Todos los integrantes se comprometen a:

- Desarrollar y entregar los módulos asignados.  
- Documentar código y procesos en el repositorio.  
- Participar en pruebas, revisiones y reuniones de seguimiento.  
- Mantener comunicación abierta sobre bloqueos y avances.

---

## ✍️ 13. Firmas de aprobación

| Nombre | Rol | Firma |
|---|---|---|
| Juan Pablo Castillo | Responsable principal | __________ |
| Jhohan | Integrante | __________ |
| Brayan | Integrante | __________ |
| Jhon | Integrante | __________ |
| Fernando | Integrante | __________ |

---

*Documento preparado para subir a `ACTA.md` en el repositorio.*