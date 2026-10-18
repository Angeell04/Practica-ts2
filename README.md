# Listado de Cohetes

Aplicación web interactiva desarrollada en **TypeScript** que consume una API de lanzamientos de cohetes, permitiendo explorar misiones, realizar búsquedas, aplicar filtros y gestionar una lista de favoritos.

**Demo en producción:** [bespoke-biscochitos-80da3a.netlify.app](https://bespoke-biscochitos-80da3a.netlify.app)

---

## Funcionalidades

- **Carga asíncrona:** Renderizado dinámico de los lanzamientos obtenidos mediante `fetch`/`async-await`.
- **Buscador en tiempo real:** Filtrado instantáneo de cohetes según se escribe en el campo de texto.
- **Filtro por estado:** Menú desplegable para visualizar misiones *Exitosas*, *Fallidas*, *Pendientes* o *Todas*.
- **Cálculo de estadísticas:** Muestra el porcentaje de éxito, total de misiones, número de aciertos y fallos calculados con `reduce`.
- **Gestión de favoritos:**
  - Marcar y desmarcar misiones como favoritas mediante delegación de eventos.
  - Persistencia de los favoritos en el navegador con `localStorage`.
  - Botón para alternar la vista entre **"⭐ Mis favoritos"** y **"🏠 Ver todos"**.

