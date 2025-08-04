# Git Workflow – Travel Safely

## Estructura de Ramas

- `main`: rama estable.
- `develop`: rama de integración.
- `feature/*`: ramas de desarrollo de funcionalidades.

### Ejemplos:
- feature/login
- feature/rutas
- feature/notificaciones

---

## Convención de Commits

**Formato:**

`<tipo>: <mensaje corto>`

**Tipos comunes:**
- feat: nueva funcionalidad
- fix: corrección de errores
- docs: documentación
- style: formato/estilo
- refactor: reestructuración interna
- test: pruebas automatizadas
- chore: tareas generales

**Ejemplo:**

`feat: agregar validación al formulario de login`

---

##  Frecuencia de push/pull

- `push`: al finalizar una tarea o al final del día.
- `pull`: antes de iniciar trabajo o crear nuevas ramas.

---

##  Política de Pull Requests

- Solo se permite hacer `merge` hacia `develop` desde `feature/*`.
- Está prohibido hacer `push` directo a `main`.
- Todo Pull Request debe:
  - Tener descripción clara
  - Ser revisado por otro integrante antes del merge
