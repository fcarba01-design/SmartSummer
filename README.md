# ☀️ Verano Sebastián 6º Primaria — Sistema de 90 Minutos

Nueva versión optimizada del entorno de aprendizaje interactivo para preparar el paso a 6º de Primaria, estructurado en bloques de tiempo estrictos y control diario por firmas.

## ⏱️ Estructura Diaria Obligatoria (90 Minutos Totales)
Cada jornada de estudio se divide cronológicamente en las siguientes etapas consecutivas:
1. **15 Minutos de Lectura**: Lectura libre de un libro seleccionado con tareas offline de comprensión en cuaderno.
2. **30 Minutos de Estudio de Contenidos**: Bloque enfocado a materias troncales con una pregunta clave con validación digital interactiva.
3. **30 Minutos de Prácticas**: Ejercicios prácticos (Matemáticas ABN, Lengua, etc.) resueltos físicamente y comprobados por clave.
4. **15 Minutos para Elaboración de Mini Proyectos**: Bloque creativo enfocado a manualidades, bocetos, música y planes activos.

## 🔒 Sistema de Bloqueo y Control de Misión (Padres)
- **Orden cronológico estricto**: Sebastián no puede avanzar a jornadas posteriores ni saltarse bloques. El estado se almacena de forma persistente en el dispositivo (`localStorage`).
- **Verificación Física y Firma**: Al terminar las 4 fases diarias (digitales y físicas), se habilita el bloque de autorización. Los padres deben introducir la palabra clave para validar y desbloquear de forma automática el siguiente día.

## 🛠️ Archivos del Repositorio
- `index.html` -> Interfaz HUD y lógica interactiva de validación por fases con bloqueo y firma.
- `tareas.json` -> Base de datos estructurada con el itinerario cronológico de 10 días lectivos.
- `style.css` -> Estilos de respaldo y compatibilidad.

## 🚀 Despliegue Local o Producción
Para abrirlo de forma segura en tu navegador evitando bloqueos CORS de archivos locales:
1. Abre la terminal en esta carpeta.
2. Ejecuta: `python3 -m http.server 8000`
3. Entra en tu navegador a: `http://localhost:8000`
4. También puedes subirlo a un repositorio de GitHub y activar **GitHub Pages** desde la sección *Settings > Pages*.

---
*Proyecto educativo enfocado en hábitos saludables, autonomía guiada y gamificación estival.*
