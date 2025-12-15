# Dashboard de Vehículos 2024 - Power BI

**Contenidos / Contents:**
- [Español](#spanish-version)
- [English](#english-version)

## Spanish version

## Objetivo
Analizar la composición del parque de vehículos en España y su antigüedad, permitiendo comparar resultados por comunidad autónoma, provincia y municipio.

## Fuente de los datos
Los datos han sido obtenidos en formato `EXCEL` a través de la web oficial de la [DGT](https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Datos-municipales-informacion-general-2024/).  
Contienen información sobre:
- La composición del parque de vehículos en España
- La antigüedad de los vehículos
- El censo de conductores
- La cantidad de vehículos por Comunidad Autónoma, provincia y municipio
- La distribución de vehículos según los distintos tipos de distintivos ambientales
- El total de vehículos y su clasificación por tipo

Año de referencia: **2024**.

## Descripción
Dashboard interactivo desarrollado en Power BI para analizar los vehículos registrados actualmente en el territorio español.

## Visualizaciones
- **Gráfico de barras horizontales**: Número total de vehículos por Comunidad Autónoma  
- **Gráfico de barras verticales**: Antigüedad promedio por tipo de vehículo  
- **Gráfico de tarta**: Distribución de tipos de vehículos  
- **Gráfico de donut**: Distribución de distintivos ambientales  
- **Gráfico de barras verticales**: Distribución de tipo de combustible  
- **Segmentadores**: Comunidad Autónoma, provincia y municipio  

## Herramientas utilizadas
- Power BI Desktop
- DAX
- Excel

## Vista del dashboard
![Dashboard](images/dashboard_screenshot.png)

## Archivos
- `data/`: dataset utilizado  
- `docs/`: paleta de colores utilizada para el dashboard  
- `images/`: capturas de pantalla del dashboard  
- `.gitignore`  
- `README.md`: Contenido del proyecto  
- `vehiculos_españa_dashboard.pbit`: plantilla del dashboard **sin datos**  
- `vehiculos_españa_dashboard.pbix`: versión completa del dashboard lista para abrir (1,6 MB, datos públicos)

## Cómo abrir el dashboard
1. Descargar la versión completa (`vehiculos_españa_dashboard.pbix`) para ver el dashboard directamente con datos incluidos, o descargar la plantilla (`vehiculos_españa_dashboard.pbit`) si deseas reutilizarla.
2. Abrir el archivo con Power BI Desktop.
3. Si abres la plantilla `.pbit`, es necesario tener los archivos de datos en la carpeta `data/` y conectar Power BI a ellos para que los visuales se carguen correctamente.

## Notas
- Los valores mostrados corresponden a promedios y totales agregados.  
- El análisis depende de la calidad y actualización de los datos publicados por la DGT.

---

## English Version


## Vehicle Dashboard 2024 - Power BI

## Objective
Analyze the composition of the vehicle fleet in Spain and its age, allowing comparisons by autonomous community, province, and municipality.

## Data Source
The data was obtained in `EXCEL` format from the official [DGT website](https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Datos-municipales-informacion-general-2024/).  
It contains information about:
- The composition of the vehicle fleet in Spain
- Vehicle age
- Driver census
- Number of vehicles by autonomous community, province, and municipality
- Distribution of vehicles according to different types of environmental badges
- Total number of vehicles and their classification by type

Reference year: **2024**.

## Description
Interactive dashboard developed in Power BI to analyze the currently registered vehicles in Spain.

## Visualizations
- **Horizontal bar chart**: Total number of vehicles by autonomous community  
- **Vertical bar chart**: Average vehicle age by type  
- **Pie chart**: Distribution of vehicle types  
- **Donut chart**: Distribution of environmental badges  
- **Vertical bar chart**: Distribution by fuel type  
- **Slicers**: Autonomous community, province, and municipality  

## Tools Used
- Power BI Desktop
- DAX
- Excel

## Dashboard Preview
![Dashboard](images/dashboard_screenshot_en.png)

> **Note:** The dashboard interface is in Spanish. The screenshot above has been translated into English for presentation purposes only. All visualizations and labels within Power BI are in Spanish.



## Files
- `data/`: dataset used  
- `docs/`: color palette used in the dashboard  
- `images/`: dashboard screenshots  
- `.gitignore`  
- `README.md`: project content  
- `vehiculos_españa_dashboard.pbit`: dashboard template **without data**  
- `vehiculos_españa_dashboard.pbix`: full dashboard version ready to open (1.6 MB, public data)

## How to Open the Dashboard
1. Download the full version (`vehiculos_españa_dashboard.pbix`) to view the dashboard directly with data included, or download the template (`vehiculos_españa_dashboard.pbit`) if you want to reuse it.  
2. Open the file with Power BI Desktop.  
3. If you open the `.pbit` template, you need to have the data files in the `data/` folder and connect Power BI to them so that the visuals load correctly.

## Notes
- The values shown correspond to averages and aggregated totals.  
- The analysis depends on the quality and update of the data published by the DGT.