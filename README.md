📡 Análisis de Penetración de Internet en Argentina
📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar la penetración del servicio de internet en Argentina, utilizando datos del Ente Nacional de Comunicaciones (ENACOM). Se busca evaluar el acceso a internet en los hogares, identificar tendencias en la adopción de tecnologías y medir el impacto del crecimiento en la conectividad a nivel provincial.

A través de un dashboard interactivo en Power BI, se presentan insights clave que permitirán a una empresa de telecomunicaciones optimizar su estrategia, mejorar su calidad de servicio y expandir su cobertura en las regiones con mayor potencial.

📊 Objetivos del Proyecto
✔ Analizar la penetración de internet en los hogares argentinos por provincia.
✔ Identificar el crecimiento de accesos y su relación con la adopción de diferentes tecnologías.
✔ Evaluar la calidad del servicio a través de la velocidad promedio de conexión.
✔ Medir los ingresos generados por el servicio de internet y su impacto en la rentabilidad.
✔ Presentar un dashboard interactivo en Power BI que facilite la toma de decisiones.

📂 Estructura del Repositorio
📁 datasets/ → Contiene los archivos procesados utilizados en el análisis.
📁 notebooks/ → Análisis Exploratorio de Datos (EDA) en Python.
📁 powerbi/ → Archivo .pbix con el Dashboard en Power BI.
📁 images/ → Capturas de las visualizaciones principales del dashboard.
📄 README.md → Descripción del proyecto.
📄 dashboard_documentation.md → Explicación del modelo de datos en Power BI.

📜 Fuentes de Datos
Los datos utilizados provienen del Ente Nacional de Comunicaciones (ENACOM) y están estructurados en los siguientes archivos:

1️⃣ Datos Clave para el Análisis
📄 Penetracion-hogares.csv → Nivel de acceso a internet por cada 100 hogares.
📄 Accesos Por Tecnología.csv → Distribución de accesos por tipo de tecnología (ADSL, Fibra, Wireless, etc.).
📄 Velocidad % por prov.csv → Velocidad media de conexión en cada provincia.
📄 Ingresos.csv → Ingresos generados por los servicios de internet.
📄 Mapa Conectividad.csv → Información geográfica sobre cobertura de internet.
2️⃣ Datos Complementarios
📄 Accesos_tecnologia_localidad.csv → Accesos a nivel de localidad.
📄 Penetracion-totales.csv → Penetración de internet a nivel nacional.
📈 KPIs Analizados
En el Dashboard se presentan métricas clave para evaluar la evolución del acceso a internet en Argentina.

✔ KPI 1: Aumento del 2% en accesos por cada 100 hogares

Fórmula:
DAX
Copiar
Editar
KPI_Crecimiento = ((Nuevo Acceso - Acceso Actual) / Acceso Actual) * 100
Visualización: Tarjeta KPI y gráfico de barras comparando el acceso actual con la meta del 2%.
✔ KPI 2: Distribución de accesos por tecnología

Muestra la proporción de conexiones ADSL, Fibra Óptica, Wireless, etc.
Visualización: Gráfico de barras apiladas.
✔ KPI 3: Velocidad promedio de conexión por provincia

Evalúa la calidad del servicio.
Visualización: Mapa de calor con la velocidad media en cada región.
✔ KPI 4: Ingresos por usuario promedio (ARPU)

Fórmula:
DAX
Copiar
Editar
ARPU = SUM(Ingresos) / SUM(Total de Accesos)
Visualización: Tarjeta KPI y gráfico de tendencia de ingresos.
📊 Estructura del Dashboard en Power BI
El dashboard en Power BI permite interactividad mediante filtros y visualizaciones dinámicas.

🔹 Filtros disponibles:

Provincia
Trimestre
Tipo de tecnología
🔹 Visualizaciones clave:
✅ Indicador KPI → Crecimiento del 2% en accesos por cada 100 hogares.
✅ Gráfico de Barras Apiladas → Distribución de accesos por tecnología.
✅ Mapa de Calor → Velocidad de conexión por provincia.
✅ Gráfico de Tendencia → Evolución del crecimiento de accesos e ingresos.
✅ Mapa Interactivo → Cobertura de acceso a internet por localidad.

🛠️ Herramientas Utilizadas
📌 Python (Pandas, Matplotlib, Seaborn) → Análisis Exploratorio de Datos (EDA).
📌 Power BI → Visualización de datos e interactividad.
📌 DAX → Creación de medidas para cálculos avanzados en Power BI.
📌 GitHub → Gestión del código y documentación.

📌 Cómo Ejecutar el Proyecto
1️⃣ Clonar el repositorio

bash
Copiar
Editar
git clone https://github.com/tu_usuario/penetracion-internet-argentina.git
cd penetracion-internet-argentina
2️⃣ Abrir el Notebook EDA

Ubicado en notebooks/EDA.ipynb
Ejecutar en Jupyter Notebook o Google Colab.
3️⃣ Cargar los datos en Power BI

Abrir el archivo .pbix en powerbi/penetracion_internet.pbix
Actualizar los datos si es necesario.
📢 Contribuciones
Si deseas contribuir con mejoras en el análisis o en la visualización, ¡eres bienvenido!
Para colaborar:

Realiza un fork del repositorio.
Crea una nueva rama (feature/nueva_funcionalidad).
Realiza un pull request con tus cambios.
