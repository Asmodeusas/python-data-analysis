# Bienvenidos al Análisis del DataFrame Oficinas de Correos y Estaciones de Metro

Análisis geoespacial de oficinas de Correos y estaciones de Metro de Madrid usando Python, Pandas y Folium.

## Descripción

Este script carga un dataset de *oficinas de Correos* desde una fuente JSON pública y un archivo *GeoJSON* de estaciones de Metro de Madrid para facilitar su análisis y visualización.
Después, limpia y transforma los datos para obtener columnas más legibles, coordenadas numéricas y etiquetas útiles para el mapa.
Por último, genera un HTML interactivo donde se pueden comprobar las oficinas de Correos y las estaciones de Metro mediante *marcadores*, *capas* y *toggles por línea*.

## Funcionalidades

- Carga de datos de oficinas de Correos desde una URL en formato JSON.
- Carga de estaciones de Metro desde un archivo GeoJSON.
- Normalización de datos JSON con Pandas.
- Renombrado de columnas para hacerlas más legibles.
- Limpieza de horarios, direcciones y estaciones cercanas.
- Conversión de latitud y longitud a valores numéricos.
- Creación de marcadores personalizados para oficinas de Correos y estaciones de Metro.
- Asignación de colores según la línea de Metro.
- Creación de capas separadas para Correos y Metro.
- Toggle por líneas de Metro para mostrar u ocultar estaciones concretas.
- Generación de un mapa interactivo en HTML con Folium.

# Welcome to the Post Offices and Metro Stations DataFrame Analysis

Geospatial analysis of post offices and Madrid metro stations using Python, Pandas, and Folium.

## Description

This script loads a dataset of *post offices* from a public JSON source and a *GeoJSON* file containing Madrid metro stations to support analysis and visualization.
It then cleans and transforms the data to produce more readable columns, numeric coordinates, and useful labels for the map.
Finally, it generates an interactive HTML file where post offices and metro stations can be explored through *markers*, *layers*, and *line-based toggles*.

## Features

- Loading post office data from a JSON URL.
- Loading metro station data from a GeoJSON file.
- Normalizing JSON data with Pandas.
- Renaming columns for better readability.
- Cleaning schedules, addresses, and nearby station fields.
- Converting latitude and longitude into numeric values.
- Creating custom markers for post offices and metro stations.
- Assigning colors based on metro line.
- Creating separate layers for post offices and metro stations.
- Adding metro line toggles to show or hide specific stations.
- Generating an interactive HTML map with Folium.