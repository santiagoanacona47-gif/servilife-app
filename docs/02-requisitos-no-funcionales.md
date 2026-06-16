# Requisitos no funcionales - ServiLife App

## Introducción

Este documento define los requisitos no funcionales de ServiLife App, una aplicación académica orientada al monitoreo de inventario de una droguería mediante la importación de archivos Excel.

Los requisitos no funcionales describen las características de calidad que debe cumplir el sistema, como usabilidad, seguridad, rendimiento, mantenibilidad, escalabilidad y claridad visual.

---

## RNF01 - Usabilidad

La aplicación debe ser sencilla, clara y fácil de usar para usuarios sin conocimientos técnicos avanzados.

### Descripción

El sistema debe permitir que un administrador o empleado de droguería pueda navegar por los módulos principales sin dificultad.

### Criterio de cumplimiento

El usuario debe identificar fácilmente las secciones principales: Inicio, Importar, Inventario, Alertas, Reportes y Configuración.

---

## RNF02 - Claridad visual

La interfaz debe presentar la información de forma ordenada, limpia y comprensible.

### Descripción

Los datos del inventario, alertas y reportes deben mostrarse de manera visualmente clara, evitando saturar la pantalla con información innecesaria.

### Criterio de cumplimiento

El sistema debe usar títulos, tarjetas, tablas, colores de alerta y botones de forma coherente.

---

## RNF03 - Diseño responsive

La aplicación debe adaptarse a diferentes tamaños de pantalla.

### Descripción

El sistema debe visualizarse correctamente en computadores y, en una fase posterior, ajustarse a pantallas más pequeñas como tablets o celulares.

### Criterio de cumplimiento

La barra de navegación y los módulos principales deben conservar su funcionalidad en diferentes resoluciones.

---

## RNF04 - Rendimiento

La aplicación debe procesar archivos Excel pequeños o medianos en un tiempo razonable.

### Descripción

El sistema debe permitir importar inventarios sin bloqueos prolongados ni fallos inesperados.

### Criterio de cumplimiento

La carga de archivos debe responder adecuadamente para inventarios propios de una droguería pequeña o mediana.

---

## RNF05 - Seguridad básica

El sistema debe contar con mecanismos básicos de control de acceso.

### Descripción

El acceso a los módulos internos debe estar protegido mediante autenticación de usuario.

### Criterio de cumplimiento

El usuario debe iniciar sesión antes de acceder a funcionalidades internas como inventario, alertas, reportes o configuración.

---

## RNF06 - Mantenibilidad

El código debe estar organizado de forma clara para facilitar futuras modificaciones.

### Descripción

La estructura del proyecto debe permitir que Santiago, Johan o el equipo de apoyo técnico puedan revisar, mejorar y ampliar el sistema sin perder el control del código.

### Criterio de cumplimiento

El proyecto debe usar nombres claros, separación de responsabilidades y documentación básica.

---

## RNF07 - Escalabilidad

El sistema debe permitir agregar nuevas funcionalidades en el futuro.

### Descripción

Aunque la primera versión será un prototipo funcional básico, el diseño debe permitir agregar posteriormente módulos más completos, como reportes avanzados, roles de usuario o integración con base de datos.

### Criterio de cumplimiento

La estructura del proyecto no debe limitarse a una sola pantalla desordenada, sino permitir crecimiento modular.

---

## RNF08 - Trazabilidad

El sistema debe permitir identificar cuándo se actualizó la información del inventario.

### Descripción

Cada importación de inventario debe estar asociada a una fecha o registro de actualización.

### Criterio de cumplimiento

El sistema debe mostrar o almacenar la fecha de la última importación realizada.

---

## RNF09 - Confiabilidad

La aplicación debe evitar procesar información incorrecta sin advertir al usuario.

### Descripción

Si el archivo Excel contiene errores, columnas faltantes, datos inválidos o valores incoherentes, el sistema debe informar el problema antes de continuar.

### Criterio de cumplimiento

El sistema debe mostrar mensajes de validación claros ante errores de importación.

---

## RNF10 - Compatibilidad

El sistema debe funcionar correctamente en navegadores modernos.

### Descripción

La aplicación debe poder visualizarse en navegadores como Google Chrome, Microsoft Edge o equivalentes.

### Criterio de cumplimiento

El prototipo debe cargar correctamente desde el navegador y mostrar los estilos de Bootstrap sin errores visibles.

---

## RNF11 - Accesibilidad básica

La interfaz debe aplicar buenas prácticas básicas de accesibilidad.

### Descripción

Los botones, formularios y enlaces deben ser comprensibles para el usuario y tener textos claros.

### Criterio de cumplimiento

Los elementos interactivos deben tener nombres entendibles y los formularios deben indicar claramente qué información se espera.

---

## RNF12 - Documentación

El proyecto debe contar con documentación técnica básica.

### Descripción

La documentación debe explicar el contexto del proyecto, requisitos, prototipo, decisiones técnicas, avances y el uso de guías internas de desarrollo.

### Criterio de cumplimiento

La carpeta docs debe contener archivos organizados para orientar el desarrollo y facilitar la entrega de evidencias SENA.

---

## RNF13 - Trabajo colaborativo

El proyecto debe permitir el trabajo conjunto entre Santiago Anacona Jurado y Johan León.

### Descripción

Durante el desarrollo se podrán dejar comentarios temporales en el código para orientar tareas, dudas o revisiones del equipo.

### Criterio de cumplimiento

Los comentarios temporales deben ser profesionales, claros y útiles. Antes de entregar evidencias, deben revisarse, limpiarse o convertirse en comentarios técnicos.

---

## RNF14 - Control de versiones

El proyecto debe gestionarse mediante Git y GitHub.

### Descripción

Los cambios deben guardarse mediante commits claros, organizados y relacionados con avances específicos.

### Criterio de cumplimiento

El repositorio debe registrar cambios importantes como documentación, prototipo, correcciones y nuevas funcionalidades.

---

## RNF15 - Coherencia con el alcance

El sistema debe mantenerse dentro del alcance definido para ServiLife App.

### Descripción

La aplicación debe enfocarse en monitoreo de inventario, importación de Excel, alertas y reportes básicos.

### Criterio de cumplimiento

No se deben implementar módulos de ventas completas, facturación, caja registradora, POS o software contable en esta fase.
