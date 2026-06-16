# Contexto del proyecto ServiLife App

## Información general

ServiLife App es una aplicación académica desarrollada para el programa Análisis y Desarrollo de Software del SENA.

El proyecto se enfoca en construir un sistema de monitoreo de inventario para una droguería, usando como fuente principal archivos Excel exportados desde un sistema externo.

El sistema no busca reemplazar por completo el software actual de la droguería. Su propósito es servir como una herramienta complementaria para consultar inventario, identificar productos críticos, generar alertas y facilitar la toma de decisiones.

## Problema identificado

La droguería necesita mejorar el seguimiento de su inventario, especialmente en aspectos como:

- Productos con bajo stock.
- Productos próximos a vencer.
- Consulta rápida de existencias.
- Visualización de productos críticos.
- Seguimiento de alertas.
- Generación de reportes básicos.

Cuando estos procesos no se monitorean correctamente, pueden generarse problemas como desabastecimiento, pérdida de productos por vencimiento, dificultad para tomar decisiones y menor eficiencia operativa.

## Objetivo general

Construir una aplicación web que permita monitorear el inventario de una droguería mediante la importación de archivos Excel, consulta de productos, generación de alertas de bajo stock, seguimiento de vencimientos y reportes básicos.

## Objetivos específicos

- Crear una interfaz inicial para el sistema ServiLife App.
- Permitir la importación de inventario desde archivos Excel.
- Visualizar productos registrados en el inventario.
- Identificar productos con stock bajo.
- Identificar productos próximos a vencer.
- Mostrar alertas activas.
- Generar reportes básicos del estado del inventario.
- Documentar los avances técnicos como evidencia SENA.

## Usuarios principales

### Administrador

Usuario encargado de configurar parámetros del sistema, revisar reportes, importar archivos y supervisar el inventario.

### Vendedor o empleado

Usuario encargado de consultar productos, revisar existencias y verificar alertas relacionadas con stock o vencimientos.

### Sistema

Actor interno encargado de procesar los datos importados, comparar stock actual contra stock mínimo y generar alertas.

## Alcance del sistema

El sistema ServiLife App debe incluir los siguientes módulos:

- Login.
- Inicio o dashboard.
- Importar inventario desde Excel.
- Inventario.
- Alertas.
- Reportes.
- Configuración.

## Fuera del alcance

ServiLife App no debe convertirse en:

- Sistema completo de ventas.
- Sistema de facturación.
- Caja registradora.
- Punto de venta POS.
- Software contable.
- Sistema de compras completo.

El enfoque principal es el monitoreo de inventario a partir de información importada.

## Prototipo inicial

El prototipo inicial se está construyendo con HTML y Bootstrap, usando el tema Bootswatch Flatly.

Actualmente el archivo principal es:

index.html

Este archivo contiene la primera estructura visual de la aplicación, incluyendo barra de navegación, presentación inicial y acceso a módulos principales.

## Módulos definidos

### Login

Permite al usuario autenticarse en el sistema.

### Inicio

Presenta un resumen general del inventario, alertas activas, productos críticos y estadísticas básicas.

### Importar

Permite cargar archivos Excel provenientes del sistema externo de la droguería.

### Inventario

Permite consultar productos registrados, stock actual, stock mínimo, proveedor, lote y fecha de vencimiento.

### Alertas

Muestra productos con bajo stock o vencimiento próximo.

### Reportes

Permite visualizar información estadística y reportes básicos del inventario.

### Configuración

Permite administrar parámetros del sistema, usuarios y criterios de monitoreo.

## Criterio de trabajo en equipo

El proyecto es desarrollado por Santiago Anacona Jurado y Johan León.

Durante la construcción del prototipo se permiten comentarios temporales en el código para orientar el trabajo en equipo. Estos comentarios deben ser profesionales, claros y útiles.

Antes de entregar evidencias, los comentarios temporales deben limpiarse o convertirse en comentarios técnicos.

## Prioridad actual

La prioridad actual es fortalecer el prototipo visual, organizar la documentación del proyecto y preparar el repositorio para la revisión técnica y la entrega de evidencias académicas del SENA.

Archivo: docs/01-requisitos-funcionales.md