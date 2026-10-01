
# 📍 PuntoCampus — Mercado Estudiantil Universitario

Plataforma digital interactiva diseñada para conectar a estudiantes emprendedores con la comunidad universitaria, permitiéndoles exhibir su catálogo de productos (comida, postres, botanas, papelería) e indicar en qué punto exacto del campus y en qué horario se encuentran entregando en tiempo real.

---

## 🎯 Visión y Propósito del Proyecto

En el entorno universitario, cientos de estudiantes comercializan productos para sustentar sus estudios personales y académicos. Sin embargo, la difusión suele estar dispersa en estados efímeros de WhatsApp o grupos masivos desorganizados. 

**PuntoCampus** centraliza la oferta y resuelve la logística dentro del campus:
- **Catálogo centralizado:** Búsqueda rápida por categorías (comida, repostería, snacks, accesorios).
- **Ubicación en el campus:** Información transparente del punto de entrega (edificio, piso, cafetería, áreas verdes) y ventana de horario.
- **Contacto directo:** Comunicación inmediata con el vendedor vía enlace directo a WhatsApp.

---

## 👥 Equipo y Roles por Fortalezas 

El equipo opera bajo la **Teoría Y de McGregor**: confiamos en la autonomía, el compromiso y las fortalezas de cada miembro, sin microgestión:

| Rol | Responsable | Área de Enfoque |
| :--- | :--- | :--- |
| **Technical Lead** | *Zuriel Valencia* | Arquitectura frontend/backend, control de versiones y revisión de código. |
| **UI/UX Designer** | *Zuriel Valencia* | Identidad gráfica, diseño de marca y prototipo navegable en Figma. |
| **Process & Automation Manager** | *Angel Guzman* | Gestión en Notion/Trello, automatizaciones con Make.com y canal `#kudos`. |
| **QA, Deployment & Metrics Lead** | *Jorge Aviles* | Monitoreo en UptimeRobot, dashboard de métricas en Looker Studio y pruebas. |

---

## 🛡️ Flujo de Trabajo y Seguridad (Factores de Higiene de Herzberg)

Para garantizar un entorno de trabajo seguro, ordenado y libre de fricciones técnicas (**Factores de Higiene de Herzberg**), **queda estrictamente prohibido hacer commits directos a la rama principal (`main`)**. Todo cambio sigue el flujo de Pull Requests:

### 1. Convención de Ramas (*Git Branching*)
Crea una rama específica a partir de `main` con un prefijo descriptivo:
- `feature/nombre-de-la-funcionalidad` (para nuevas características o pantallas)
- `fix/descripcion-del-error` (para corrección de bugs)
- `docs/actualizacion-documentacion` (para cambios en README o guías)

```bash
# Ejemplo:
git checkout -b feature/mapa-ubicacion-campus

