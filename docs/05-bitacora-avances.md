# Bitácora de avances - ServiLife App

## Introducción

Este documento registra los avances realizados durante el desarrollo de ServiLife App.

La bitácora permite llevar control del progreso técnico del proyecto, documentar cambios importantes, identificar dificultades y dejar evidencia clara para el proceso formativo del SENA.

---

## Información del proyecto

### Nombre del proyecto

ServiLife App

### Programa de formación

Análisis y Desarrollo de Software - SENA

### Aprendices

* Santiago Anacona Jurado.
* Johan León.

### Objetivo del sistema

Construir una aplicación web para monitorear inventario de una droguería mediante la importación de archivos Excel, consulta de productos, generación de alertas de bajo stock, seguimiento de vencimientos y reportes básicos.

---

## Avance 01 - Organización inicial del repositorio y documentación

### Fecha

15 de junio de 2026

### Objetivo del avance

Organizar la estructura inicial del proyecto para separar el código, la documentación técnica y las evidencias académicas del SENA.

### Actividades realizadas

* Se identificó la carpeta real del proyecto.
* Se definió la carpeta principal del código.
* Se creó la carpeta docs.
* Se creó la carpeta docs/evidencias-sena.
* Se crearon documentos base para contexto, requisitos, prototipo, decisiones técnicas y bitácora.

### Archivos creados o modificados

* docs/00-contexto-proyecto.md
* docs/01-requisitos-funcionales.md
* docs/02-requisitos-no-funcionales.md
* docs/03-prototipo-pantallas.md
* docs/04-decisiones-tecnicas.md
* docs/05-bitacora-avances.md

### Resultado obtenido

El proyecto cuenta con una estructura documental organizada que facilita el trabajo colaborativo, la trazabilidad de los avances y la preparación de evidencias académicas del SENA.

### Estado

Completado.

---

## Avance 02 - Definición del alcance y criterios de desarrollo

### Fecha

15 de junio de 2026

### Objetivo del avance

Definir criterios básicos para orientar el desarrollo del proyecto, mantener el alcance controlado y facilitar la revisión técnica del prototipo.

### Actividades realizadas

* Se definió el alcance permitido de ServiLife App.
* Se aclaró que el sistema no debe convertirse en ventas, facturación, caja registradora ni POS.
* Se definieron reglas para el uso de comentarios temporales en el código.
* Se establecieron criterios para diferenciar prototipo visual y funcionalidad real.
* Se organizaron lineamientos básicos para documentar avances técnicos.

### Archivos creados o modificados

* docs/00-contexto-proyecto.md
* docs/02-requisitos-no-funcionales.md
* docs/04-decisiones-tecnicas.md
* docs/05-bitacora-avances.md

### Resultado obtenido

El proyecto cuenta con criterios claros para orientar el desarrollo, controlar el alcance, mantener una estructura ordenada y facilitar la revisión técnica durante la construcción del prototipo.

### Estado

Completado.

---

## Avance 03 - Documentación del contexto y requisitos

### Fecha

15 de junio de 2026

### Objetivo del avance

Documentar el contexto del proyecto, los requisitos funcionales, los requisitos no funcionales y las pantallas principales del prototipo.

### Actividades realizadas

* Se redactó el contexto general de ServiLife App.
* Se definió el problema que busca resolver el sistema.
* Se documentaron los requisitos funcionales.
* Se documentaron los requisitos no funcionales.
* Se describieron las pantallas principales del prototipo.
* Se registraron las decisiones técnicas iniciales.

### Archivos creados o modificados

* docs/00-contexto-proyecto.md
* docs/01-requisitos-funcionales.md
* docs/02-requisitos-no-funcionales.md
* docs/03-prototipo-pantallas.md
* docs/04-decisiones-tecnicas.md

### Resultado obtenido

El proyecto cuenta con documentación base para orientar el desarrollo técnico y justificar las decisiones tomadas durante la construcción del prototipo.

### Estado

Completado.

---

## Avance 04 - Prototipo visual inicial

### Fecha

15 de junio de 2026

### Objetivo del avance

Construir una primera versión visual de ServiLife App usando HTML, Bootstrap y el tema Bootswatch Flatly.

### Actividades realizadas

* Se creó una estructura inicial en index.html.
* Se agregó una barra de navegación.
* Se agregó el nombre del sistema.
* Se agregó una descripción general de la aplicación.
* Se agregó un botón de ingreso.
* Se configuró Bootstrap mediante CDN.
* Se aplicó el tema Bootswatch Flatly.

### Archivos creados o modificados

* index.html

### Resultado obtenido

Se cuenta con un prototipo visual inicial que representa la primera pantalla de ServiLife App y sirve como base para continuar el desarrollo de módulos como Inicio, Importar, Inventario, Alertas, Reportes y Configuración.

### Estado

En progreso.

### Observaciones

El prototipo aún no cuenta con lógica real de importación de Excel, validación de datos, generación de alertas ni reportes. Actualmente corresponde a una fase visual inicial.

---

## Avance 05 - Trabajo colaborativo con comentarios temporales

### Fecha

15 de junio de 2026

### Objetivo del avance

Permitir que Santiago y Johan puedan coordinarse durante el desarrollo mediante comentarios temporales dentro del código.

### Actividades realizadas

* Se definió que los comentarios temporales son permitidos durante la fase de desarrollo.
* Se estableció que dichos comentarios deben ser profesionales y útiles.
* Se aclaró que antes de entregar evidencias deben eliminarse o convertirse en comentarios técnicos.

### Ejemplo de comentario permitido

<!-- TODO Equipo: revisar comportamiento responsive del menú de navegación. -->

### Ejemplo de comentario no recomendado

<!-- Pana no entiendo cómo funciona esto. -->

### Resultado obtenido

El equipo cuenta con una regla clara para dejar pistas internas durante el desarrollo sin afectar la presentación profesional del proyecto.

### Estado

Completado.

---

## Próximos avances sugeridos

### Avance pendiente 01 - Revisión de index.html

Revisar el archivo index.html para identificar posibles mejoras en estructura, comentarios, organización visual y uso de Bootstrap.

---

### Avance pendiente 02 - Explicación técnica del prototipo

Documentar el funcionamiento del archivo index.html por bloques, incluyendo la barra de navegación, el uso de Bootstrap, las clases principales y su relación con el prototipo de ServiLife App.

---

### Avance pendiente 03 - Mejorar estructura visual

Agregar secciones visuales para:

* Inicio.
* Importar.
* Inventario.
* Alertas.
* Reportes.
* Configuración.

---

### Avance pendiente 04 - Preparar control de versiones

Revisar los cambios actuales del repositorio, seleccionar los archivos que deben incluirse y registrar un commit claro relacionado con la documentación visible del proyecto.

---

## Notas generales

* La bitácora debe actualizarse después de cada avance importante.
* No se deben registrar funcionalidades que aún no estén implementadas.
* Se debe diferenciar entre prototipo visual y funcionalidad real.
* Cada avance debe poder explicarse y defenderse ante el instructor.
