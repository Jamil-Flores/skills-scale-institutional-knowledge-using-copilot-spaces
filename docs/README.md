# Documentación de Gestión de Proyectos de OctoAcme

Esta carpeta contiene los documentos centrales de los procesos de gestión de proyectos de OctoAcme. Este README actúa como índice y ofrece una visión concisa sobre cómo ejecutamos proyectos para ayudar a colaboradores y partes interesadas a encontrar la guía adecuada rápidamente.

## Resumen de los procesos de gestión de proyectos

OctoAcme emplea un ciclo ligero e iterativo que lleva el trabajo desde la Iniciación hasta la Planificación, Ejecución, Lanzamiento y Retrospectiva. Durante la Iniciación se captura la necesidad de negocio y las métricas de éxito en una one‑pager; se identifican stakeholders y se decide si pasar a Planificación. La Planificación descompone la iniciativa en ítems entregables con criterios de aceptación y una Definición de Hecho, identifica dependencias y riesgos, y produce un plan de lanzamiento con hitos claros. La Ejecución se organiza en incrementos cortos usando un tablero de proyecto y prácticas disciplinadas de PR; los lanzamientos siguen una checklist (comprobaciones previas, smoke tests, despliegue y plan de rollback).

Los flujos operativos diarios giran en torno a un tablero (Backlog → Ready → In Progress → In Review → QA → Done) y prácticas de pull request: PRs pequeños cuando es posible, descripciones con vínculo al issue y criterios de aceptación, y puertas en CI (tests, lint, escaneos de seguridad) antes de solicitar revisiones. La garantía de calidad es multicapa: tests unitarios e integrados, smoke tests end-to-end en rutas críticas, QA manual cuando es necesario y análisis de seguridad en CI. Las métricas (velocidad, burndown y las métricas de éxito definidas en la one‑pager) y los dashboards de observabilidad guían la ejecución y detectan problemas para escalar.

Los roles están definidos para reducir dependencias individuales: los Project Managers (PM) coordinan la entrega, cronogramas, riesgos y comunicaciones; los Product Managers (PdM) definen resultados y priorizan el backlog; los desarrolladores construyen, prueban y documentan; QA valida aceptación. La comunicación es intencional: daily standups para coordinación táctica, reuniones semanales de entrega para revisar progresos y riesgos, demos por incremento y actualizaciones mensuales a stakeholders. La gestión de riesgos se formaliza con un risk register (ID, impacto, probabilidad, propietario, mitigación, estado) y rutas de escalado; las retrospectivas tras sprints, lanzamientos o incidentes convierten aprendizajes en acciones rastreables.

## Índice de documentos del proceso

- [Resumen de Gestión de Proyectos](./octoacme-project-management-overview.md)
- [Guía de Iniciación de Proyectos](./octoacme-project-initiation.md)
- [Planificación de Proyectos](./octoacme-project-planning.md)
- [Ejecución y Seguimiento](./octoacme-execution-and-tracking.md)
- [Riesgos y Comunicación](./octoacme-risks-and-communication.md)
- [Guía de Lanzamiento y Despliegue](./octoacme-release-and-deployment.md)
- [Retrospectiva y Mejora Continua](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles y Personas](./octoacme-roles-and-personas.md)

## Cómo usar esta carpeta

- Vincula este README desde repositorios de proyecto y desde Copilot Spaces para hacer los procesos fácilmente localizables.
- Mantén cada documento enfocado; usa este README como índice y página de aterrizaje.
- Para proponer cambios, utiliza la plantilla ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml".

## Ubicación propuesta

- docs/README.md
