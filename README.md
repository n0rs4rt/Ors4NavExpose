# Ors4Nav-Expose

![Ors4Nav-Expose Banner](https://github.com/n0rs4rt/Ors4NavExpose/blob/703bc049c1903ac73f4603ec40d4e5643cd849af/assets/barner.jpg)

---

Actualmente funciona en un entorno de consola, siendo una solución ligera, rápida y funcional.

En futuras versiones se implementará una interfaz gráfica, mejorando la usabilidad y ampliando sus capacidades.
Ors4Nav-Expose es una herramienta enfocada en la extracción y análisis automatizado de información generada en navegadores web.

Permite identificar actividad de navegación, históricos detallados, datos asociados a cuentas, marcadores, descargas, cuentas de usuarios, registros vinculados a procesos de compra, métodos de pago utilizados y mucho mas, presentando la información de forma estructurada para su análisis.

La herramienta genera automáticamente una base de datos local en  con toda la información extraída y permite exportar los datos a formatos como SQLite, CSV, JSON y PDF, facilitando su revisión y análisis.
El reporte en PDF muestra un resumen de los resultados obtenidos, mientras que los formatos estructurados están pensados para análisis más detallados.

Todo el desarrollo está orientado a investigación y análisis OSINT, aplicando técnicas y procesos alineados estrictamente a los límites y alcances permitidos por el marco legal.

[ Descargar última versión](https://github.com/n0rs4rt/Ors4NavExpose/releases/download/V1.0/ORS4-NavExpose.zip)

---

# Navegadores soportados

- Google Chrome  
- Microsoft Edge  
- Brave  
- Opera  
- Mozilla Firefox  

---

## Funcionalidades principales

La herramienta permite extraer información y exportarla en múltiples formatos:

- JSON  
- CSV  
- SQLite  

Los datos se crean y se organizan automáticamente para facilitar su análisis.

---

## Tipos de datos extraídos

### Historial de navegación

- Perfiles asociados a cada usuario  
- URLs visitadas  
- Nombre de la página  
- Fecha de última visita  
- Número de veces accedidas  
- Registros de escritura manual en navegador (autocompletado)
  
---

escargas

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

### Favoritos

- Nombre del marcador  
- URL  
- Fecha de creación  
- Fecha de última utilización  

---

### Cuentas de usuario

- URL asociada  
- Nombre de usuario  
- Fecha de creación  
- Fecha de modificación  
- Fecha de último acceso  
- Número de veces que se ha utilizado (logins)

---

### Tarjetas almacenadas

Información parcial por seguridad:

- Nombre de la tarjeta  
- Usuario asociado  
- Mes de expiración  
- Año de expiración  

---

### Tarjetas sincronizadas

- Nombre de la tarjeta  
- Últimos 4 dígitos  
- Mes de expiración  
- Año  
- Red bancaria (Visa, MasterCard, etc.)  
- Descripción del producto  
- Imagen de referencia  

---

### Extensiones instaladas (Mozilla Firefox)

- Extensiones instaladas  
- Nombre  
- Descripción  
- Fecha de instalación  
- Fecha de actualización  

> Nota: Actualmente en Firefox no inclui los historiales de descarga ni cuentas de usuario.

---

## Reporte PDF

La herramienta genera automáticamente un reporte en PDF.

Este reporte contiene un resumen general de la información obtenida, presentado de forma clara y profesional.

---

## Estructura de salida

Los datos exportados se organizan en una carpeta con el nombre del equipo.

Incluye:

- Archivos estructurados por navegador  
- Bases de datos SQLite  
- Archivos JSON y CSV  
- Reporte PDF  

---

## Ejemplos

### Inicio
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/d3931d590246b080f6d32edd6065d10866cc6720/assets/ORS4-NavExpose.png)

### Resumen General
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/7a1de73e2887874657e2ea70edd8799ccbf9aab8/assets/ORS4-NavExpose0.png)

### Resumen General
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/7a1de73e2887874657e2ea70edd8799ccbf9aab8/assets/ORS4-NavExpose1.png)

### Historial Descarga
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/7a1de73e2887874657e2ea70edd8799ccbf9aab8/assets/historial_descargas.png)

### Historial
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/7a1de73e2887874657e2ea70edd8799ccbf9aab8/assets/historial.png)

### Reporte PDF
![Ors4Nav-Expose](https://github.com/n0rs4rt/Ors4NavExpose/blob/7a1de73e2887874657e2ea70edd8799ccbf9aab8/assets/reporte.png)

---

# Notas sobre los datos

En las bases de datos generadas, algunas columnas como:

- ID  
- Perfil  
- Nombre del perfil  
- Email asociado  
- Usuario  

pueden aparecer repetidas en múltiples registros.

Esto es completamente normal.

Estos valores se utilizan para identificar a qué perfil pertenece cada dato extraído, permitiendo mantener la relación entre la información procesada y el usuario correspondiente.

---

## Alcance y consideraciones

Este proyecto está orientado a **fines de investigación, análisis y estudio de información digital**.

Su diseño busca alcanzar un alto nivel de análisis dentro de los márgenes legales, sin exceder ni comprometer límites técnicos o normativos.

La herramienta está pensada para profesionales del área de seguridad, análisis **OSINT** y entornos de investigación controlados.

---

### Detección por antivirus

En algunos casos, ciertos antivirus pueden detectar la herramienta como una posible amenaza.

Esto puede deberse a que el programa interactúa con información interna del sistema y de los navegadores, lo cual puede ser interpretado como comportamiento sospechoso.

Sin embargo, se trata de un **falso positivo**, y la herramienta puede utilizarse con normalidad en entornos controlados.

---

### Ejecución y posibles errores

En caso de que se presenten errores al ejecutarla, se recomienda:

- Ejecutar como administrador  
- Verificar permisos del sistema  
- Reportar cualquier fallo encontrado  

Recuerda que esta es una versión inicial.

Durante las pruebas realizadas en diferentes equipos no se han detectado errores.

---
