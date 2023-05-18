# Element - Semaforo

## Description
Mostrar la lista de automobiles disponibles en el mes del cliente ELEMENT


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)

## Installation
Dentro del servidor en el path
~ clientes/element/semaforo


## Usage
1. El formato del documento esta en la hoja "element-export-2" del documento:
https://docs.google.com/spreadsheets/d/1-LZuwpPj5F6EDKAp4A3UbcgnbovlGto5/edit?usp=sharing&ouid=106737367809996682406&rtpof=true&sd=true

La columna LUJO, tiene formula, esa información no lo provee el archivo original.

2. Una vez que se tiene la información, descargar como CSV y abrir la pagina: 
https://csvjson.com/csv2json

3. Subir el CSV o copiar la información.
La configuración para genear el archivo JSON es:
Separator: Auto-dectect
✓ Parse Numbers
✓ Parse JSON
output: Array

4. Descargar el archivo JSON y colocarlo en la carpeta data
Puede cambiarse el nombre, pero dentro del codigo modificarlo.

