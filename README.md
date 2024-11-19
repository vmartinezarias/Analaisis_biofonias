# R Notebook para Análisis de Grupos Taxonómicos en Bioacústica

**Versión del Código**: 3.0  
**Fecha**: 2024-11-01  
**Autor**: Víctor M. Martínez-Arias  
**Grupo de Investigación**: Grupo Herpetológico de Antioquia (GHA)  
**Contacto**: vmanuel.martinez@udea.edu.co  

Este proyecto presenta herramientas para analizar patrones acústicos en bioacústica, enfocados en grupos taxonómicos. Incluye funciones para visualización, análisis de diversidad y generación de matrices para análisis de clúster.

---

## Tabla de Contenido

1. [Descripción](#descripción)
2. [Requisitos](#requisitos)
3. [Instalación](#instalación)
4. [Uso](#uso)
    - [Carga de Datos](#carga-de-datos)
    - [Eventos por Cobertura](#eventos-por-cobertura)
    - [Preparar Datos para Curvas de Diversidad](#preparar-datos-para-curvas-de-diversidad)
    - [Construcción de Curvas de Diversidad](#construcción-de-curvas-de-diversidad)
    - [Construcción de Matrices para Análisis de Clúster](#construcción-de-matrices-para-análisis-de-clúster)
    - [Análisis de Clúster](#análisis-de-clúster)
5. [Exportación](#exportación)
6. [Licencia](#licencia)

---

## Descripción

El propósito principal de este proyecto es analizar la actividad acústica de eventos biológicos en distintos tipos de cobertura y sitios de estudio. Se incluyen herramientas para:

- Visualizar patrones de diversidad de especies/sonotipos
- Calcular índices de diversidad de Hill utilizando el estimador Chao2.
- Construir matrices de presencia/ausencia para análisis de clúster.
- Generar dendrogramas para visualizar relaciones entre coberturas o sitios.

---

## Requisitos

Este proyecto requiere R (versión 4.0 o superior). Es necesario asegurarse de tener instalados los siguientes paquetes antes de comenzar:

```r
required_packages <- c(
  "shiny", "readxl", "ggplot2", "dplyr", "lubridate", "stringr",
  "tidyr", "vegan", "cluster", "iNEXT", "openxlsx", "writexl", "ggdendro"
)





Contacto
Para preguntas o problemas, contacta a:
Víctor M. Martínez-Arias
Grupo Herpetológico de Antioquia
Correo: vmanuel.martinez@udea.edu.co
