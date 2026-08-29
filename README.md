# 📊 Automatización de Data Entry y ETL: Web Scraping a Google Sheets

Este proyecto demuestra una solución completa de automatización *End-to-End (ETL)* diseñada para optimizar los procesos de carga de datos de un negocio. Convierte un proceso manual de 4 horas en una ejecución automática de menos de 10 segundos.

## 🛠️ Tecnologías Utilizadas
* *Python* (Lenguaje principal)
* *BeautifulSoup & Requests* (Web Scraping y evasión de bloqueos)
* *API de Google Sheets & Gspread* (Carga automática a la nube)
* *Gspread Formatting* (Diseño automatizado de hojas de cálculo, filtros y auto-ajuste)

## 🔄 El Proceso ETL (Paso a Paso)
1. *Extracción (E):* El script emula un navegador real, evade bloqueos de servidores e ingresa a una tienda de productos para extraer nombres y precios en tiempo real.
2. *Transformación (T):* Se realiza una limpieza de strings eliminando caracteres especiales, se parsea el texto a datos numéricos y se calcula la conversión automática de moneda extranjera a Pesos Argentinos (ARS) aplicando formatos regionales.
3. *Carga (L):* Los datos limpios se inyectan en Google Sheets, aplicando de manera automática un diseño profesional con encabezados destacados, auto-ajuste de ancho de columnas y filtros interactivos listos para el cliente.

## 📈 Impacto en el Negocio
* *Eficiencia:* Reducción del tiempo operativo a cero.
* *Precisión:* Eliminación del 100% de los errores humanos por tipeo manual.
* *Accesibilidad:* Reporte actualizado en la nube disponible al instante en dispositivos móviles.
