# Dashboard de Vehículos 2024 - Power BI

**Contenidos / Contents:**
- [Español](#spanish-version)
- [English](#english-version)

## Spanish version

### [Dashboard interactivo](https://app.powerbi.com/view?r=eyJrIjoiYjgxYzFmNWMtMmM2NS00MjMwLWI4OTktYWI5M2Q4OTViODg3IiwidCI6IjMxNjUxZjMwLWUwZTktNDMxYy04YzVlLWY1YzQ5MTMwZjY2MiIsImMiOjh9)

Este proyecto analiza el parque de vehículos en España en **2024** con el objetivo de extraer insights estratégicos sobre distribución territorial, composición por tipo de vehículo, envejecimiento del parque y grado de electrificación.

## Impacto del análisis:
Este dashboard permite:
- Detectar desequilibrios territoriales en el parque automovilístico.
- Evaluar el ritmo real de transición hacia movilidad sostenible.
- Identificar el envejecimiento estructural del parque español.
- Servir como base para análisis predictivos o estudios de política pública.

## Objetivos
- Analizar la distribución del parque automovilístico por Comunidad Autónoma.
- Evaluar la composición por tipo de vehículo.
- Medir el grado de electrificación del parque.
- Estudiar la edad media de los vehículos y sus implicaciones.
- Construir un dashboard interactivo que permita explorar los datos de forma intuitiva.

## Fuente de los datos
Los datos han sido obtenidos en formato `EXCEL` a través de la web oficial de la [DGT](https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Datos-municipales-informacion-general-2024/).  
Contienen información sobre:
- La composición del parque de vehículos en España
- La antigüedad de los vehículos
- El censo de conductores
- La cantidad de vehículos por Comunidad Autónoma, provincia y municipio
- La distribución de vehículos según los distintos tipos de distintivos ambientales
- El total de vehículos y su clasificación por tipo

## Visualizaciones
- **KPIs**: Nº total de vehículos, nº total de conductores, porcentaje de vehículos electrficados, vehículos por habitante, edad media total de vehiculos
- **Gráfico de barras horizontales**: Número total de vehículos por Comunidad Autónoma  
- **Gráfico de barras verticales**: Antigüedad promedio por tipo de vehículo  
- **Gráfico de barra horizontal apilada**: Distribución de tipos de vehículos  
- **Gráfico de tarta**: Distribución de distintivos ambientales  
- **Gráfico de barras verticales**: Distribución de tipo de combustible  
- **Segmentadores**: Comunidad Autónoma, provincia y municipio

## Metodología
- Limpieza y estandarización de nombres geográficos.
- Modelado relacional en Power BI.
- Creación de medidas DAX para agregaciones y KPIs.

## Insights Clave

- El 69% del parque está compuesto por turismos, lo que confirma un modelo de movilidad centrado en vehículo privado ligero.
- La electrificación (<1%) muestra una adopción todavía marginal, lejos de los objetivos europeos de descarbonización.
- La edad media superior a 15 años indica un parque envejecido, con impacto potencial en emisiones y seguridad vial.
- Andalucía, Cataluña y Madrid concentran el mayor volumen absoluto de vehículos.

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

## Notas
- Los valores mostrados corresponden a promedios y totales agregados.  
- El análisis depende de la calidad y actualización de los datos publicados por la DGT.

---

## English Version

### [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjgxYzFmNWMtMmM2NS00MjMwLWI4OTktYWI5M2Q4OTViODg3IiwidCI6IjMxNjUxZjMwLWUwZTktNDMxYy04YzVlLWY1YzQ5MTMwZjY2MiIsImMiOjh9)

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

## Notes
- The values shown correspond to averages and aggregated totals.  
- The analysis depends on the quality and update of the data published by the DGT.
