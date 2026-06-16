# Decisiones técnicas - ServiLife App

## Introducción

Este documento registra las principales decisiones técnicas tomadas durante el desarrollo de ServiLife App.

El objetivo es dejar evidencia clara de las herramientas, tecnologías y criterios utilizados para construir el prototipo y orientar la evolución del sistema.

---

## DT01 - Uso de HTML como base inicial

### Decisión

Se decidió iniciar el prototipo usando HTML.

### Justificación

HTML permite construir rápidamente la estructura visual inicial del sistema, definir secciones principales y representar las pantallas base del proyecto sin requerir una arquitectura compleja desde el inicio.

### Aplicación en el proyecto

Actualmente el archivo principal del prototipo es:

index.html

Este archivo contiene la primera estructura visual de ServiLife App.

---

## DT02 - Uso de Bootstrap

### Decisión

Se decidió usar Bootstrap para facilitar el diseño visual y la organización de la interfaz.

### Justificación

Bootstrap permite crear componentes visuales como barras de navegación, botones, tarjetas, formularios y tablas de manera rápida y ordenada.

También ayuda a mantener una interfaz responsive y coherente.

### Aplicación en el proyecto

Bootstrap se usa inicialmente para:

* Barra de navegación.
* Botones.
* Contenedores.
* Espaciados.
* Diseño visual base.

---

## DT03 - Uso del tema Bootswatch Flatly

### Decisión

Se decidió usar el tema Bootswatch Flatly sobre Bootstrap.

### Justificación

Flatly ofrece una apariencia limpia, moderna y sencilla, adecuada para un sistema académico y administrativo como ServiLife App.

### Aplicación en el proyecto

El tema se carga desde CDN en el archivo index.html.

---

## DT04 - Uso de Git y GitHub

### Decisión

Se decidió trabajar el proyecto dentro de una carpeta administrada con Git y GitHub.

### Justificación

Git permite llevar control de versiones, registrar avances, trabajar en equipo y recuperar cambios anteriores si ocurre algún error.

GitHub facilita compartir el código con el compañero de trabajo y mantener un respaldo del proyecto.

### Aplicación en el proyecto

La carpeta principal del código es:

C:\Users\santi\Documents\GitHub\servilife-app

---

## DT05 - Separación entre código y orientación documental

### Decisión

Se decidió separar la carpeta del código real y la carpeta de orientación o evidencias.

### Justificación

Esta separación evita mezclar archivos de desarrollo con documentos de apoyo, capturas, evidencias y material del SENA.

### Aplicación en el proyecto

Código real de la aplicación:

C:\Users\santi\Documents\GitHub\servilife-app

Carpeta de orientación y evidencias:

C:\Users\santi\OneDrive\Orden GPT\ServiLife App

---

## DT06 - Creación de carpeta docs

### Decisión

Se creó una carpeta docs dentro del repositorio.

### Justificación

La carpeta docs permite organizar la documentación técnica del proyecto y facilitar que Santiago, Johan y el equipo de apoyo técnico entiendan el contexto, requisitos, prototipo y decisiones tomadas.

### Aplicación en el proyecto

La carpeta docs contiene:

* Contexto del proyecto.
* Requisitos funcionales.
* Requisitos no funcionales.
* Prototipo de pantallas.
* Decisiones técnicas.
* Bitácora de avances.
* Lineamientos básicos de desarrollo.
* Evidencias SENA.

---

## DT07 - Uso de guías internas de desarrollo

### Decisión

Se definieron guías internas de desarrollo para orientar la estructura, el alcance y la revisión técnica del proyecto.

### Justificación

Los lineamientos de desarrollo permiten mantener criterios claros sobre el alcance del sistema, la organización del código, la documentación del proyecto y el trabajo colaborativo entre los integrantes del equipo.

Esto ayuda a evitar cambios fuera del alcance, mantener una estructura ordenada y facilitar la revisión técnica durante el desarrollo.

### Aplicación en el proyecto

Los lineamientos se usan como referencia para revisar avances, validar decisiones técnicas, documentar cambios y mantener coherencia con los requisitos definidos.

---

## DT08 - Organización de roles de apoyo técnico

### Decisión

Se definieron áreas de revisión técnica para orientar diferentes aspectos del desarrollo del proyecto.

### Justificación

Separar la revisión por áreas permite evaluar el proyecto de forma más ordenada. Cada área se enfoca en una necesidad específica, como arquitectura, revisión de código, pruebas, documentación o control de versiones.

### Roles definidos

* Arquitectura del software
* Revisión téctica del código.
* Pruebas y validaciones.
* Documentador SENA.
* Control de versiones

### Aplicación en el proyecto

Estos roles sirven como referencia interna para organizar revisiones, mejorar la calidad del código, planear pruebas y documentar los avances del proyecto.
---

## DT09 - Uso de comentarios temporales para trabajo en equipo

### Decisión

Se permite dejar comentarios temporales dentro del código durante la fase de construcción.

### Justificación

El proyecto es desarrollado por Santiago Anacona Jurado y Johan León, por lo que algunos comentarios pueden servir como guía, recordatorio o coordinación técnica.

### Criterio de uso

Los comentarios deben ser profesionales, claros y útiles.

Ejemplo correcto:

<!-- TODO Equipo: revisar comportamiento responsive del menú de navegación. -->

Ejemplo incorrecto:

<!-- Pana no entiendo cómo funciona esto. -->

### Aplicación en el proyecto

Antes de entregar evidencias, los comentarios temporales deben eliminarse o convertirse en comentarios técnicos.

---

## DT10 - Mantener el alcance limitado al monitoreo de inventario

### Decisión

Se decidió que ServiLife App no será un sistema completo de ventas ni facturación.

### Justificación

El objetivo académico y funcional del proyecto es construir una herramienta de monitoreo de inventario, no reemplazar totalmente el sistema actual de la droguería.

Ampliar el alcance hacia ventas, facturación o POS puede volver el proyecto demasiado grande para esta fase.

### Fuera del alcance

No se desarrollará en esta fase:

* Facturación.
* Sistema completo de ventas.
* Caja registradora.
* POS.
* Software contable.
* Pagos en línea.

---

## DT11 - Desarrollo progresivo por módulos

### Decisión

Se decidió avanzar de forma progresiva por módulos.

### Justificación

Desarrollar por módulos permite controlar mejor el avance, detectar errores a tiempo y generar evidencias técnicas organizadas.

### Orden sugerido

1. Login.
2. Inicio o dashboard.
3. Importar inventario desde Excel.
4. Inventario.
5. Alertas.
6. Reportes.
7. Configuración.

---

## DT12 - Diferenciar prototipo visual de funcionalidad real

### Decisión

Se decidió documentar claramente cuándo una parte corresponde a prototipo visual y cuándo corresponde a funcionalidad real.

### Justificación

Esto evita presentar como funcional algo que todavía solo es visual. También permite avanzar de forma honesta y defendible ante el instructor.

### Aplicación en el proyecto

El archivo index.html representa actualmente un prototipo visual inicial. La lógica real de importación, validación, alertas y reportes será desarrollada progresivamente.

---

## DT13 - Prioridad actual

La prioridad actual del proyecto es:

* Organizar la documentación.
* Fortalecer el prototipo visual.
* Preparar el repositorio para revisión técnica y trabajo colaborativo.
* Mejorar la colaboración entre Santiago y Johan.
* Dejar una base clara para el desarrollo posterior de módulos reales.

---

## Observación final

Las decisiones técnicas registradas en este documento pueden actualizarse a medida que el proyecto evolucione.

Si más adelante se incorpora JavaScript, una base de datos, React, Node.js u otra tecnología, deberá registrarse una nueva decisión técnica con su respectiva justificación.
