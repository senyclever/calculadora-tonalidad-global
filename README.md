# 🎼 Calculadora de Tonalidad Global

> Analiza la tonalidad de tus beats, canciones y sesiones musicales trabajando con Sonic Visualiser.  
> Calcula la escala dominante, visualiza familias armónicas, detecta modulaciones y genera informes listos para compartir.

![Portada](docs/screenshots/01-portada.png)

[Aquí agrego una imagen de portada: parte de la calculadora, con una sesión ya cargada, mostrando familias armónicas, mapa de modulaciones y resultado global.]

---

## 🚀 ¿Qué hace esta calculadora?

La **Calculadora de Tonalidad Global** es una herramienta **offline**, sin dependencias y pensada para:

- 🎧 Productores musicales
- 🎹 Compositores
- 🎛️ DJs
- 🥁 Beatmakers
- 🎚️ Ingenieros creativos
- 📚 Estudiantes de teoría musical

Su objetivo es ayudarte a responder una pregunta muy común:

> ¿En qué tonalidad está realmente esta canción?

Pero no solo eso: también te muestra cómo esa tonalidad evoluciona en el tiempo.

---

## ✨ Características principales

- ✅ Funciona completamente **offline**.
- ✅ Un solo archivo HTML.
- ✅ Sin instalación.
- ✅ Sin dependencias externas.
- ✅ Compatible con Sonic Visualiser.
- ✅ Importación de archivos CSV.
- ✅ Soporte para pegar CSV directamente.
- ✅ Soporte para arrastrar y soltar archivos CSV.
- ✅ Análisis de tonalidades individuales.
- ✅ Análisis de familias armónicas relativas.
- ✅ Mapa visual de modulaciones.
- ✅ Refuerzo de inicio y cierre.
- ✅ Resultados con código Camelot.
- ✅ Notas de la escala ganadora.
- ✅ Leyenda de tiempos para capítulos de YouTube.
- ✅ Exportación de informe en TXT.
- ✅ Exportación/importación de historial en JSON.
- ✅ Interfaz oscura, clara y pensada para flujo de trabajo musical.

---

## 🖥️ Capturas de pantalla

### 📥 Importación desde Sonic Visualiser

Puedes pegar el contenido del CSV, importar el archivo o arrastrarlo directamente.

![Importar CSV](docs/screenshots/02-importar-csv.png)

[Aquí agrego una imagen de la tarjeta “Importar CSV de Sonic Visualiser”.]

---

### ⏱️ Ventana de duración total del audio

Al importar un CSV, la calculadora solicita la duración exacta del audio para calcular correctamente el último segmento.

![Duración total](docs/screenshots/03-modal-duracion.png)

[Aquí agrego una imagen del modal de duración total con horas, minutos y segundos. (Utiliza Sonic Visualiser arrastrando la linea vertical (Playhead) al final del audio)]

---

### 🎛️ Entrada de datos

Nombre de sesión, unidad, BPM, compás, carácter y refuerzo.

![Entrada de datos](docs/screenshots/04-entrada-datos.png)

[Aquí agrego una imagen de la tarjeta “Entrada de datos” con una sesión cargada.]

---

### 🍩 Distribución de escalas

Cada tonalidad aparece representada según su presencia temporal.

![Distribución de escalas](docs/screenshots/05-distribucion-escalas.png)

[Aquí agrego una imagen del gráfico de dona y la leyenda de distribución de escalas.]

---

### 🧬 Familias armónicas

Las familias agrupan tonalidades relativas que comparten las mismas notas.

![Familias armónicas](docs/screenshots/06-familias.png)

[Aquí agrego una imagen de la sección “Familias armónicas”.]

---

### 🗺️ Mapa de modulaciones

Una barra temporal muestra los cambios de tonalidad a lo largo del tema.

![Mapa de modulaciones](docs/screenshots/07-mapa-modulaciones.png)

[Aquí agrego una imagen del mapa de modulaciones con varios colores, agrupando las familias armónicas.]

---

### 🏆 Resultado global

La calculadora entrega la tonalidad principal, su familia, compatibilidad Camelot y las notas de la escala.

![Resultado global](docs/screenshots/08-resultado-global.png)

[Aquí agrego una imagen del resultado global con una tonalidad ganadora.]

---

### ⚖️ Refuerzo de inicio y cierre

El refuerzo permite dar más peso a las secciones de apertura y cierre del tema.

![Refuerzo](docs/screenshots/09-refuerzo.png)

[Aquí agrego una imagen como ejemplo del refuerzo activado, mostrando ventana y peso extra.]

---

### 💾 Historial

Puedes guardar sesiones, exportarlas e importarlas.

![Historial](docs/screenshots/10-historial.png)

[Aquí agrego una imagen de la tarjeta “Historial” con sesiones guardadas.]

---

### 📄 Informe generado y Descargar ".txt" de la Guía de uso.

El informe incluye resultado global, distribución, segmentos, notas y leyenda de tiempos. También puedes descargar una guía mas detallada sobre el uso completo de la calculadora de tonalidad global.

![Informe](docs/screenshots/11-informe.png)

[Aquí agrego una imagen de un informe TXT abierto o copiado.]

---

## 🧠 ¿Por qué esta herramienta?

Muchos detectores automáticos dan una sola tonalidad para toda la canción.

Pero la música real no siempre funciona así.

Una canción puede:

- empezar en una tonalidad,
- modular hacia otra,
- alternar entre relativo mayor y menor,
- tener secciones ambiguas,
- confirmar la tonalidad recién en el cierre.

Esta calculadora no te obliga a confiar en una sola respuesta automática.

Te permite trabajar con segmentos temporales y entender el comportamiento armónico del tema completo.

---

## 📦 Instalación

No necesita instalación.

### Opción 1 — Uso local

1. Descarga el archivo `index.html`.
2. Ábrelo con tu navegador.
3. Listo.

Funciona en:

- Windows
- macOS
- Linux
- Android
- iOS

Mientras el navegador sea relativamente moderno, debería funcionar correctamente.

---

### Opción 2 — Usar online con GitHub Pages

Si este repositorio está publicado con GitHub Pages, puedes usarlo directamente desde el navegador.

Botón sugerido:

```text
Usar online
