# Ors4Nav-Expose

![Ors4Nav-Expose Banner](https://github.com/n0rs4rt/Ors4NavExpose/blob/703bc049c1903ac73f4603ec40d4e5643cd849af/assets/barner.jpg)

---

## Proyecto en desarrollo

**Ors4Nav-Expose** Ors4Nav-Expose es una herramienta enfocada en la extracción y análisis automatizado de información generada en navegadores web.

Permite identificar actividad de navegación, históricos detallados, datos asociados a cuentas, marcadores, descargas, cuentas de usuarios, registros vinculados a procesos de compra, métodos de pago utilizados y mucho mas, presentando la información de forma estructurada para su análisis.

La herramienta genera automáticamente una base de datos local en  con toda la información extraída y permite exportar los datos a formatos como SQLite, CSV, JSON y PDF, facilitando su revisión y análisis.
El reporte en PDF muestra un resumen de los resultados obtenidos, mientras que los formatos estructurados están pensados para análisis más detallados.

Todo el desarrollo está orientado a investigación y análisis OSINT, aplicando técnicas y procesos alineados estrictamente a los límites y alcances permitidos por el marco legal.

---

# 🔍 Ors4Nav-Expose

<p align="center">
  <img src="LINK_AQUI_PORTADA" width="800">
</p>

<p align="center">
  <a href="LINK_DESCARGA">
    <img src="https://img.shields.io/badge/Descargar-Herramienta-blue?style=for-the-badge">
  </a>
</p>

---

## ⚠️ Estado del proyecto

Esta es una versión inicial de la herramienta.

Puede contener errores o comportamientos inesperados.  
Si encuentras algún problema, puedes reportarlo.

Actualmente funciona en un entorno de consola, siendo una solución ligera, rápida y funcional.

En futuras versiones se implementará una interfaz gráfica, mejorando la usabilidad y ampliando sus capacidades.

---

## 🧠 Descripción

**Ors4Nav-Expose** es una herramienta enfocada en el análisis local y la automatización de datos almacenados en navegadores web.

Permite extraer, procesar y estructurar información relevante directamente desde las bases de datos locales, facilitando su análisis posterior en diferentes formatos.

---

## 🌐 Navegadores soportados

- Google Chrome  
- Microsoft Edge  
- Brave  
- Opera  
- Mozilla Firefox  

---

## ⚙️ Funcionalidades principales

La herramienta permite extraer información y exportarla en múltiples formatos:

- JSON  
- CSV  
- SQLite  

Los datos se organizan automáticamente para facilitar su análisis.

---

## 📊 Tipos de datos extraídos

### 🔎 Historial de navegación

- Perfiles asociados a cada usuario  
- URLs visitadas  
- Nombre de la página  
- Fecha de última visita  
- Número de veces accedidas  
- Registros de escritura manual en navegador (autocompletado)

---

### 📥 Descargas

- URL de origen  
- URL directa del archivo  
- Ruta de destino  
- Nombre del archivo  
- Fecha de inicio  
- Fecha de finalización  
- Tamaño del archivo  
- Indicación de apertura desde navegador  
- Fecha de acceso al archivo desde el navegador  

---

### ⭐ Favoritos

- Nombre del marcador  
- URL  
- Fecha de creación  
- Fecha de última utilización  

---

### 👤 Cuentas de usuario

- URL asociada  
- Nombre de usuario  
- Fecha de creación  
- Fecha de modificación  
- Fecha de último acceso  
- Número de veces que se ha utilizado (logins)

---

### 💳 Tarjetas almacenadas

Información parcial por seguridad:

- Nombre de la tarjeta  
- Usuario asociado  
- Mes de expiración  
- Año de expiración  

---

### 💳 Tarjetas sincronizadas

- Nombre de la tarjeta  
- Últimos 4 dígitos  
- Mes de expiración  
- Año  
- Red bancaria (Visa, MasterCard, etc.)  
- Descripción del producto  
- Imagen de referencia  

---

### 🧩 Mozilla Firefox (datos adicionales)

- Extensiones instaladas  
- Nombre  
- Descripción  
- Fecha de instalación  
- Fecha de actualización  

> Nota: Actualmente no se incluyen historiales de descarga ni cuentas en Firefox.

---

## 📄 Reporte PDF

La herramienta genera automáticamente un reporte en PDF.

Este reporte contiene un resumen general de la información obtenida, presentado de forma clara y profesional.

---

## 🗂️ Estructura de salida

Los datos exportados se organizan en una carpeta con el nombre del equipo.

Incluye:

- Archivos estructurados por navegador  
- Bases de datos SQLite  
- Archivos JSON y CSV  
- Reporte PDF  

---

## 🖼️ Ejemplos

### Vista general
<img src="LINK_IMAGEN_RESULTADO">

### Consola
<img src="LINK_IMAGEN_CONSOLA">

### Base de datos
<img src="LINK_IMAGEN_DB">

### Reporte PDF
<img src="LINK_IMAGEN_PDF">

---

## ⚠️ Aviso importante

Esta herramienta está diseñada exclusivamente para:

- Análisis local  
- Auditoría  
- Investigación digital  

Debe utilizarse únicamente en entornos autorizados y dentro de los límites legales.

---

## 🚀 Próximas mejoras

- Interfaz gráfica  
- Nuevas funcionalidades  
- Soporte ampliado  

---

## 👨‍💻 Autor

**Ors4Tech**
---

## Alcance y consideraciones

Este proyecto está orientado a **fines de investigación, análisis y estudio de información digital**.  

Su diseño busca alcanzar el máximo nivel de análisis permitido dentro de los márgenes legales,  sin exceder ni comprometer límites técnicos o normativos.

La herramienta está pensada para profesionales del área de seguridad,  análisis **OSINT** y entornos de investigación controlados.

Más detalles y funcionalidades serán publicados en futuras actualizaciones.

---

**Proyecto en desarrollo.**

