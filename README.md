# 📍 PuntoCampus — Mercado Estudiantil Universitario

Plataforma digital interactiva diseñada para conectar a estudiantes emprendedores con la comunidad universitaria, permitiéndoles exhibir su catálogo de productos (comida, postres, botanas, papelería) e indicar en qué punto exacto del campus y en qué horario se encuentran entregando en tiempo real.

---

## 🎯 Visión y Propósito del Proyecto

En el entorno universitario, cientos de estudiantes comercializan productos para sustentar sus estudios personales y académicos. Sin embargo, la difusión suele estar dispersa en estados efímeros de WhatsApp o grupos masivos desorganizados. 

PuntoCampus centraliza la oferta y resuelve la logística dentro del campus:
- Catálogo centralizado: Búsqueda rápida por categorías (comida, repostería, snacks, accesorios).
- Ubicación en el campus: Información transparente del punto de entrega (edificio, piso, cafetería, áreas verdes) y ventana de horario.
- Contacto directo: Comunicación inmediata con el vendedor vía enlace directo a WhatsApp.

---

## 👥 Equipo y Roles por Fortalezas (Teoría Y de McGregor)

El equipo opera bajo la Teoría Y de McGregor[cite: 1]: confiamos en la autonomía, el compromiso y las fortalezas de cada miembro, sin microgestión[cite: 1]:

| Rol | Responsable | Área de Enfoque |
| :--- | :--- | :--- |
| Technical Lead | [Angel Guzman] | Arquitectura frontend/backend, control de versiones y revisión de código. |
| UI/UX Designer | [Zuriel Valencia] | Identidad gráfica, diseño de marca y prototipo navegable en Figma. |
| Process & Automation Manager | [Rodrigo Zamacona] | Gestión en Notion/Trello, automatizaciones con Make.com y canal #kudos[cite: 1]. |
| QA, Deployment & Metrics Lead | [Jorge Aviles] | Monitoreo en UptimeRobot, dashboard de métricas en Looker Studio y pruebas[cite: 1]. |

---

## 🛡️ Flujo de Trabajo y Seguridad (Factores de Higiene de Herzberg)

Para garantizar un entorno de trabajo seguro, ordenado y libre de fricciones técnicas (Factores de Higiene de Herzberg)[cite: 1], queda estrictamente prohibido hacer commits directos a la rama principal (main). Todo cambio sigue el flujo de Pull Requests:

### 1. Convención de Ramas (Git Branching)
Crea una rama específica a partir de main con un prefijo descriptivo:
- feature/nombre-de-la-funcionalidad (para nuevas características o pantallas)
- fix/descripcion-del-error (para corrección de bugs)
- docs/actualizacion-documentacion (para cambios en README o guías)

Ejemplo de creación de rama:
git checkout -b feature/mapa-ubicacion-campus

### 2. Flujo de Solicitud de Cambios (Pull Requests)
- Realiza commits claros y concisos siguiendo el estándar:
  - feat: agregar mapa interactivo con pines de edificios
  - fix: corregir enlace roto del botón de contacto

- Sube la rama a GitHub:
  git push origin feature/mapa-ubicacion-campus

- Abre un Pull Request (PR) hacia la rama main en GitHub.
- Revisión obligatoria: El PR debe ser revisado y aprobado por al menos un compañero de equipo (Peer Review) antes de poder fusionarse (merge)[cite: 1].
- Tras la aprobación, se realiza el Merge y se elimina la rama secundaria para mantener limpio el repositorio.

---

## ⚙️ Stack de Herramientas Digitales y Automatizaciones

- Gestión y Visión: Notion (Workspace, matriz de roles y tablero Kanban).
- Diseño y Prototipado: Figma (Wireframes interactivos de PuntoCampus).
- Control de Versiones: GitHub (Flujo de Pull Requests y protección de rama main)[cite: 1].
- Automatización de Reconocimiento: Make.com (Dispara un mensaje de celebración en Discord al mover tareas a Done)[cite: 1].
- Monitoreo & Métricas: UptimeRobot (Disponibilidad de la web) / Google Looker Studio (Progreso de tareas)[cite: 1].
- Cultura de Equipo: Discord (Canal #kudos para reconocimientos genuinos entre integrantes)[cite: 1].

---


