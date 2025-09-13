# ACTA DE CONSTITUCIÓN DEL PROYECTO

**Proyecto:** Sistema De Información Y Gestión Para Agencias de Viajes.  
**Fecha de elaboración:** 12/09/2025  
**Lugar:** Bogotá, Colombia  
**Repositorio:** [GitHub - Acta](https://github.com/Juan-Pablo-Castillo-Velasquez/Planeacion_de_proyectos/blob/main/acta.md)  

**Responsables principales:**  
- Juan Pablo Castillo Velásquez  
- Fernando Gutiérrez Rojas  
- John Mauricio Cortés Rincón  
- Jhojan Forero Infante  
- Brayan Estiven Torres Amortegui  

---

## 1. Antecedentes
Las agencias de viajes pequeñas y medianas dependen de métodos manuales (Excel, correos, llamadas) para gestionar clientes, paquetes y reservas.  
Esto genera duplicidad de información, errores, lentitud y pérdida de competitividad frente a plataformas digitales.

---

## 2. Problema
- Errores en reservas e itinerarios.  
- Falta de visibilidad de precios y disponibilidad en tiempo real.  
- Pérdida de confianza y clientes frente a plataformas digitales.  

---

## 3. Objetivo general
Desarrollar una plataforma web/móvil modular para gestionar clientes, reservas y paquetes turísticos, con un API de analítica en Python que genere métricas, reportes y tableros para la toma de decisiones.

---

## 4. Objetivos específicos
- Construir una gestión de bases de datos los cuales permitan ser escalable (clientes, paquetes, reservas, proveedores).  
- Diseñar módulos independientes: reservas, pagos, itinerarios, proveedores, usuarios.  
- Implementar un API en (lenguaje aún por definir) para analítica de datos (KPIs, tendencias, ventas).  
- Crear paneles dinámicos y exportables.  
- Establecer pipelines CI/CD y despliegue contenedorizado en Kubernetes.  

---

## 5. Usuarios objetivo
- Clientes viajeros (usuarios finales).  
- Agencias pequeñas/medianas (administración).  
- Proveedores turísticos (hoteles, transportes, guías).  

---

## 6. Metodología y herramientas
**Enfoque:** iterativo y modular  

**Herramientas clave:**  
- Git — control de versiones local (commits, branches, merges).  
- GitHub — repositorio remoto, pull requests, issues, CI/CD.  
- Jira — gestión ágil: historias, sprints, tableros y seguimiento.  
- Docker / Kubernetes — contenedorización y orquestación.  
- PostgreSQL (o DB relacional) — almacenamiento principal.  
- Python — API de analítica y scripts de ETL/ML básicos.  

**Flujo propuesto (Git + GitHub + Jira):**  
1. Crear historia/tarea en Jira (ej. "CRUD clientes").  
2. Abrir rama en GitHub: `feature/<tarea>` (ej. `feature/crud-clientes`).  
3. Desarrollo local con Git → commits claros y atómicos.  
4. Push a la rama remota y abrir Pull Request en GitHub.  
5. Revisiones de código (PR), pruebas automáticas (CI) y aprobación.  
6. Merge a main/develop y cerrar la tarea en Jira.  

---

## 7. Recursos y responsables

| Integrante | Rol / Responsabilidades |
|------------|-------------------------|
| Juan Pablo | Aún por definir         |
| Jhohan     | Aún por definir         |
| Brayan     | Aún por definir         |
| John       | Aún por definir         |
| Fernando   | Aún por definir         |

---

## 8. Riesgos y mitigación
**Limitaciones:** poca experiencia en pagos online y seguridad avanzada.  

**Riesgos:** retrasos por aprendizaje, incompatibilidades entre módulos, sobrecarga del equipo.  

**Mitigación:** priorizar MVP por fase, usar pagos simulados, pruebas en entornos sandbox, revisiones de seguridad antes de producción.  

---

## 9. Compromisos
Todos los integrantes se comprometen a:  
- Desarrollar y entregar los módulos asignados.  
- Documentar código y procesos en el repositorio.  
- Participar en pruebas, revisiones y reuniones de seguimiento.  
- Mantener comunicación abierta sobre bloqueos y avances.  
