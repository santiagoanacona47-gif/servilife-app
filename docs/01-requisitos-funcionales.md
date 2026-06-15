# Requisitos funcionales - ServiLife App

## Introducción

Este documento define los requisitos funcionales de ServiLife App, una aplicación académica orientada al monitoreo de inventario de una droguería mediante la importación de archivos Excel provenientes de un sistema externo.

Los requisitos funcionales describen las acciones, módulos y comportamientos que el sistema debe permitir al usuario.

## RF01 - Iniciar sesión

El sistema debe permitir que el usuario ingrese mediante credenciales de acceso.

### Descripción

El usuario debe poder acceder al sistema usando un formulario de inicio de sesión.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario autenticado puede ingresar al sistema y visualizar los módulos principales.

---

## RF02 - Visualizar pantalla de inicio

El sistema debe mostrar una pantalla inicial o dashboard con información general del inventario.

### Descripción

La pantalla de inicio debe presentar un resumen del estado del sistema, incluyendo alertas activas, productos críticos y estadísticas básicas.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario puede ver un resumen general del inventario monitoreado.

---

## RF03 - Importar inventario desde Excel

El sistema debe permitir cargar un archivo Excel exportado desde el sistema externo de la droguería.

### Descripción

El usuario podrá seleccionar un archivo Excel para actualizar o registrar información del inventario monitoreado.

### Actor principal

Administrador.

### Resultado esperado

El sistema recibe el archivo y queda preparado para procesar la información del inventario.

---

## RF04 - Validar archivo Excel

El sistema debe validar que el archivo Excel tenga una estructura correcta antes de procesarlo.

### Descripción

El sistema debe comprobar que el archivo contenga las columnas necesarias, como código, nombre del producto, lote, proveedor, fecha de vencimiento, stock actual y stock mínimo.

### Actor principal

Sistema.

### Resultado esperado

Si el archivo es correcto, puede procesarse. Si contiene errores, el sistema debe informar al usuario.

---

## RF05 - Consultar inventario

El sistema debe permitir consultar los productos registrados en el inventario.

### Descripción

El usuario podrá visualizar productos con información como nombre, código, lote, proveedor, stock actual, stock mínimo y fecha de vencimiento.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario puede revisar el estado del inventario de forma clara y organizada.

---

## RF06 - Buscar productos

El sistema debe permitir buscar productos dentro del inventario.

### Descripción

El usuario podrá buscar productos por nombre, código, proveedor o lote.

### Actor principal

Administrador o empleado.

### Resultado esperado

El sistema muestra los productos que coinciden con el criterio de búsqueda.

---

## RF07 - Filtrar productos

El sistema debe permitir filtrar productos según su estado.

### Descripción

El usuario podrá filtrar productos por bajo stock, vencimiento próximo o estado crítico.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario puede identificar rápidamente productos que requieren atención.

---

## RF08 - Generar alertas de bajo stock

El sistema debe generar alertas cuando un producto tenga stock actual menor o igual al stock mínimo definido.

### Descripción

El sistema comparará el stock actual de cada producto con su stock mínimo. Si el producto está por debajo o igual al mínimo, se generará una alerta.

### Actor principal

Sistema.

### Resultado esperado

El sistema identifica productos con bajo stock y los muestra en el módulo de alertas.

---

## RF09 - Generar alertas por vencimiento próximo

El sistema debe generar alertas para productos próximos a vencer.

### Descripción

El sistema debe revisar las fechas de vencimiento de los productos y marcar aquellos que estén cerca de su fecha límite.

### Actor principal

Sistema.

### Resultado esperado

El usuario puede identificar productos que deben revisarse antes de su vencimiento.

---

## RF10 - Gestionar alertas

El sistema debe permitir visualizar y gestionar las alertas generadas.

### Descripción

El usuario podrá consultar las alertas activas relacionadas con bajo stock o vencimiento próximo.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario puede hacer seguimiento a los productos críticos.

---

## RF11 - Visualizar reportes básicos

El sistema debe permitir visualizar reportes básicos relacionados con el inventario.

### Descripción

Los reportes podrán mostrar información sobre productos en bajo stock, productos próximos a vencer, cantidad total de productos monitoreados y alertas activas.

### Actor principal

Administrador.

### Resultado esperado

El administrador puede consultar información útil para la toma de decisiones.

---

## RF12 - Configurar parámetros de monitoreo

El sistema debe permitir configurar criterios básicos de monitoreo.

### Descripción

El usuario administrador podrá ajustar parámetros como stock mínimo, criterios de alerta y días de anticipación para vencimientos.

### Actor principal

Administrador.

### Resultado esperado

El sistema aplica los criterios definidos para generar alertas.

---

## RF13 - Visualizar navegación principal

El sistema debe mostrar un menú principal con acceso a los módulos definidos.

### Descripción

La aplicación debe permitir navegar entre las secciones principales: Inicio, Importar, Inventario, Alertas, Reportes y Configuración.

### Actor principal

Administrador o empleado.

### Resultado esperado

El usuario puede desplazarse fácilmente entre los módulos principales del sistema.

---

## RF14 - Mostrar mensajes de error o validación

El sistema debe mostrar mensajes claros cuando ocurra un error o una validación falle.

### Descripción

Cuando un archivo no sea válido, falten datos, existan columnas incorrectas o se presenten errores de carga, el sistema debe informar al usuario.

### Actor principal

Sistema.

### Resultado esperado

El usuario comprende el problema y puede corregirlo.

---

## RF15 - Registrar fecha de importación

El sistema debe registrar o mostrar la fecha de la última importación de inventario.

### Descripción

Cada vez que se cargue un archivo Excel, el sistema debe permitir identificar cuándo se realizó la importación.

### Actor principal

Sistema.

### Resultado esperado

El usuario puede conocer la última actualización del inventario.

---

## Funcionalidades fuera del alcance

ServiLife App no debe incluir en esta fase:

* Facturación.
* Ventas completas.
* Caja registradora.
* Punto de venta POS.
* Software contable.
* Gestión completa de compras.
* Pagos en línea.

El sistema se enfoca exclusivamente en el monitoreo de inventario a partir de información importada.
