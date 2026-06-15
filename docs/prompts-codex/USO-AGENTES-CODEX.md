# Uso de agentes Codex - ServiLife App

Este documento explica cómo usar los agentes definidos para orientar a Codex durante el desarrollo de ServiLife App.

## Ruta del proyecto

Código real de la aplicación:

C:\Users\santi\Documents\GitHub\servilife-app

Carpeta de orientación y evidencias:

C:\Users\santi\OneDrive\Orden GPT\ServiLife App

## Regla principal

Codex debe trabajar sobre la carpeta del código real:

C:\Users\santi\Documents\GitHub\servilife-app

La carpeta de OneDrive se usará para guardar evidencias, documentos, capturas, respaldos y material de orientación.

## Agentes disponibles

### Arquitecto

Archivo:

docs/prompts-codex/arquitecto.md

Uso:

Lee AGENTS.md y docs/prompts-codex/arquitecto.md. Revisa la estructura actual del proyecto. No escribas código todavía. Indícame si la estructura es adecuada para escalar ServiLife App y qué carpetas o módulos recomiendas crear después.

### Reviewer Senior

Archivo:

docs/prompts-codex/reviewer-senior.md

Uso:

Lee AGENTS.md y luego usa el rol definido en docs/prompts-codex/reviewer-senior.md para revisar index.html. No modifiques código todavía. Dame diagnóstico con hallazgos críticos, importantes y mejoras opcionales.

### QA Tester

Archivo:

docs/prompts-codex/qa-tester.md

Uso:

Lee AGENTS.md y docs/prompts-codex/qa-tester.md. Propón casos de prueba para el prototipo actual y para el futuro módulo de importación de Excel. Incluye casos normales, casos límite, errores esperados y validaciones necesarias.

### Tutor

Archivo:

docs/prompts-codex/tutor.md

Uso:

Lee AGENTS.md y docs/prompts-codex/tutor.md. Explícame cómo funciona el archivo index.html por bloques. Quiero entender la barra de navegación, Bootstrap, las clases principales y cómo se conecta con el prototipo de ServiLife App.

### Documentador SENA

Archivo:

docs/prompts-codex/documentador-sena.md

Uso:

Lee AGENTS.md y docs/prompts-codex/documentador-sena.md. Con base en el estado actual del proyecto, redacta una bitácora técnica del avance realizado. Diferencia entre prototipo visual y funcionalidad implementada.

### Git Coach

Archivo:

docs/prompts-codex/git-coach.md

Uso:

Lee AGENTS.md y docs/prompts-codex/git-coach.md. Revisa los cambios actuales del repositorio. Sugiere qué archivos incluir en el commit, qué mensaje de commit usar y si conviene separar los cambios en varios commits.

## Flujo recomendado de trabajo

1. Santiago o Johan hacen un cambio pequeño.
2. Guardan los archivos.
3. Piden revisión a Codex usando el agente correspondiente.
4. Codex entrega diagnóstico.
5. Se aplican solo los cambios aprobados.
6. Se prueba en navegador.
7. Se documenta el avance.
8. Se hace commit en Git.

## Comentarios temporales en el código

Se permiten comentarios temporales para trabajo en equipo, siempre que sean profesionales.

Ejemplo correcto:

<!-- TODO Equipo: revisar comportamiento responsive del menú de navegación en pantallas pequeñas. -->

Ejemplo correcto:

<!-- NOTA Equipo: esta opción representa el módulo de inventario definido en el prototipo GA5. -->

Evitar comentarios informales como:

<!-- Pana no entiendo cómo funciona esta barra -->

Antes de entregar evidencia, los comentarios temporales deben limpiarse o convertirse en comentarios técnicos.

## Alcance que Codex debe respetar

ServiLife App debe enfocarse en:

- Login.
- Inicio / dashboard.
- Importar inventario desde Excel.
- Inventario.
- Alertas.
- Reportes.
- Configuración.

No debe convertirse en:

- Sistema completo de ventas.
- Facturación.
- Caja registradora.
- POS.
- Software contable.

## Prioridad actual

La prioridad actual es fortalecer el prototipo inicial y documentar correctamente el proyecto antes de avanzar a funcionalidades más complejas.

Orden sugerido:

1. Llenar documentación base en docs/.
2. Revisar index.html con Reviewer Senior.
3. Mejorar comentarios del equipo.
4. Crear bitácora del primer avance.
5. Hacer commit inicial de documentación y prototipo.
6. Luego avanzar al diseño de módulos reales.