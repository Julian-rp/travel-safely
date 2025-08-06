#  Guía de Estándares de Codificación - Proyecto Travel Safely

## 1. Reglas de nombres

- **Variables y funciones**: camelCase
  - ✅ `usuarioActivo`, `registrarRuta()`
  - ❌ `Usuario_activo`, `Registrar_ruta`

- **Clases y componentes**: PascalCase
  - ✅ `Conductor`, `ViajeFinalizado`
  - ❌ `claseconductor`, `viaje_finalizado`

- **Constantes**: MAYÚSCULAS_SEPARADAS
  - ✅ `MAX_VIAJES`, `API_URL`

- **Archivos**: kebab-case
  - ✅ `gestionar-rutas.js`, `login-page.jsx`
  - ❌ `GestiónRutas.js`, `LoginPage.jsx`

---

## 2. Comentarios y documentación interna

- Comentarios explicativos antes de funciones:

```js
// Verifica si el conductor tiene una ruta asignada
function verificarRutaAsignada() {
  ...
}
/**
 * Calcula la duración de un viaje
 * @param {string} horaInicio
 * @param {string} horaFin
 * @returns {number}
 */
##3. Estilo
Indentación de 2 espacios

Punto y coma obligatorio

Archivos con una sola responsabilidad

##4. Ejemplos aceptados y no aceptados
✔️ Aceptado	                  ❌ No aceptado
const viajes = []	           var VA = new Array()
function iniciarSesion()	   function iS()
RutaAsignada.js	               rutaASIGNADA.js
