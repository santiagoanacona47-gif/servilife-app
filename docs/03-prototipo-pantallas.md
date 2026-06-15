# Prototipo de pantallas - ServiLife App

## Introducción

Este documento describe las pantallas principales definidas para el prototipo de ServiLife App.

El prototipo representa la estructura visual inicial de la aplicación y sirve como base para el desarrollo progresivo del sistema. En esta fase, el objetivo principal es construir una interfaz clara, organizada y alineada con los requisitos del proyecto.

ServiLife App está orientada al monitoreo de inventario de una droguería mediante archivos Excel exportados desde un sistema externo.

---

## Pantallas principales del sistema

El prototipo inicial contempla las siguientes pantallas:

* Login.
* Inicio.
* Importar.
* Inventario.
* Alertas.
* Reportes.
* Configuración.

---

## Pantalla Login

### Objetivo

Permitir que el usuario ingrese al sistema mediante credenciales de acceso.

### Descripción

La pantalla Login será el punto de entrada al sistema. Permitirá que el usuario se autentique antes de acceder a los módulos internos de ServiLife App.

### Elementos esperados

* Nombre o logo de ServiLife App.
* Campo para usuario o correo.
* Campo para contraseña.
* Botón de ingreso.
* Mensaje de error en caso de credenciales incorrectas.

### Actor principal

Administrador o empleado.

---

## Pantalla Inicio

### Objetivo

Presentar un resumen general del estado del inventario monitoreado.

### Descripción

La pantalla Inicio funcionará como dashboard principal. Mostrará información resumida sobre productos monitoreados, alertas activas, productos críticos y última importación realizada.

### Elementos esperados

* Tarjeta de productos monitoreados.
* Tarjeta de alertas activas.
* Tarjeta de productos críticos.
* Información de la última importación.
* Accesos rápidos a módulos principales.

### Actor principal

Administrador o empleado.

---

## Pantalla Importar

### Objetivo

Permitir la carga de archivos Excel provenientes del sistema externo de la droguería.

### Descripción

La pantalla Importar permitirá seleccionar un archivo Excel para alimentar o actualizar la información del inventario monitoreado.

### Elementos esperados

* Botón o campo para seleccionar archivo.
* Indicación del formato permitido.
* Mensaje de archivo cargado correctamente.
* Mensaje de error si el archivo no cumple la estructura esperada.
* Resumen de productos procesados.

### Actor principal

Administrador.

---

## Pantalla Inventario

### Objetivo

Permitir la consulta de productos registrados en el inventario.

### Descripción

La pantalla Inventario mostrará los productos cargados en el sistema, junto con información clave para el monitoreo.

### Elementos esperados

* Tabla de productos.
* Código del producto.
* Nombre del producto.
* Lote.
* Proveedor.
* Stock actual.
* Stock mínimo.
* Fecha de vencimiento.
* Estado del producto.
* Filtros de búsqueda.

### Actor principal

Administrador o empleado.

---

## Pantalla Alertas

### Objetivo

Mostrar productos que requieren atención por bajo stock o vencimiento próximo.

### Descripción

La pantalla Alertas centralizará los productos críticos detectados por el sistema. Permitirá al usuario identificar rápidamente qué productos deben revisarse.

### Elementos esperados

* Lista o tabla de alertas.
* Tipo de alerta.
* Producto relacionado.
* Stock actual.
* Stock mínimo.
* Fecha de vencimiento.
* Estado de la alerta.
* Indicadores visuales por prioridad.

### Actor principal

Administrador o empleado.

---

## Pantalla Reportes

### Objetivo

Presentar reportes básicos relacionados con el inventario y las alertas.

### Descripción

La pantalla Reportes permitirá visualizar información útil para la toma de decisiones, como productos en bajo stock, productos próximos a vencer y cantidad de alertas activas.

### Elementos esperados

* Reporte de productos en bajo stock.
* Reporte de productos próximos a vencer.
* Resumen de alertas generadas.
* Estadísticas básicas del inventario.
* Posibilidad futura de exportar información.

### Actor principal

Administrador.

---

## Pantalla Configuración

### Objetivo

Permitir la administración de parámetros básicos del sistema.

### Descripción

La pantalla Configuración permitirá definir criterios de monitoreo y ajustes generales del sistema.

### Elementos esperados

* Configuración de stock mínimo.
* Configuración de días de anticipación para vencimientos.
* Administración básica de usuarios.
* Parámetros de alertas.
* Criterios de monitoreo.

### Actor principal

Administrador.

---

## Navegación principal

La aplicación debe contar con una navegación clara hacia los módulos principales:

* Inicio.
* Importar.
* Inventario.
* Alertas.
* Reportes.
* Configuración.

En el prototipo actual, esta navegación se está construyendo inicialmente mediante una barra superior usando Bootstrap y el tema Bootswatch Flatly.

---

## Estado actual del prototipo

El prototipo inicial se encuentra en el archivo:

index.html

Actualmente incluye:

* Barra de navegación principal.
* Nombre de la aplicación.
* Descripción general del sistema.
* Botón de ingreso.
* Estructura inicial usando Bootstrap.

Este prototipo todavía corresponde a una fase visual inicial. Las funcionalidades reales, como importación de Excel, validación de datos, generación de alertas y reportes, serán desarrolladas progresivamente.

---

## Criterio de evolución

El prototipo debe evolucionar de forma ordenada:

1. Construir estructura visual base.
2. Agregar navegación entre módulos.
3. Crear secciones principales.
4. Incorporar formularios y tablas.
5. Agregar lógica de importación de Excel.
6. Agregar validaciones.
7. Generar alertas.
8. Crear reportes básicos.
9. Documentar cada avance.

---

## Observaciones para el equipo

Santiago Anacona Jurado y Johan León podrán dejar comentarios temporales dentro del código para coordinar el desarrollo.

Los comentarios deben ser claros, técnicos y profesionales.

Antes de entregar evidencias, los comentarios temporales deberán revisarse, eliminarse o convertirse en comentarios técnicos útiles.
