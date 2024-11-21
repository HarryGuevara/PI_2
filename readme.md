### Resumen del Proyecto

#### Descripción General
Este proyecto consistió en la extracción y transformación de datos desde un archivo de Excel con múltiples hojas. Cada hoja se exportó como un archivo CSV independiente para su análisis posterior.

#### Proceso Realizado
1. **Extracción de Hojas**: Se utilizaron scripts en Python para iterar por las hojas del archivo Excel y exportarlas como CSV.
2. **Transformación de Datos**: 
   - Las columnas clave fueron ajustadas a formatos adecuados para análisis (fechas, períodos trimestrales, entre otros).
   - Se manejaron valores nulos y formatos inconsistentes.
3. **Análisis Exploratorio de Datos (EDA)**:
   - Exploración inicial con herramientas como `.info()` y `.describe()`.
   - Visualización de correlaciones con mapas de calor.
   - Análisis de tendencias por provincia, tecnología y período.

#### Principales Resultados
- **Distribución Regional**: Buenos Aires y CABA lideran en accesos a tecnologías como Cablemodem y Fibra óptica.
- **Tendencias Tecnológicas**: Cablemodem y Fibra óptica muestran un crecimiento destacado, mientras ADSL y Wireless están en declive.
- **Correlaciones**: Relación significativa entre tecnologías avanzadas y mayores velocidades de bajada.

#### Archivos de Entrada y Salida
- Archivos Excel procesados: Hojas como `Accesos por Tecnología`, `Velocidad % por prov` y más.
- Archivos CSV generados: Ej. `Penetracion-hogares.csv`, `Totales VMD.csv`.

#### Próximos Pasos
- Análisis temporal detallado para identificar tendencias en accesos por tecnología.
- Generación de visualizaciones avanzadas en herramientas como Power BI para presentar hallazgos.

#### Requisitos Técnicos
Librerías utilizadas:
```bash
pip install pandas matplotlib seaborn
```

#### Conclusión
Este proyecto proporciona una base sólida para comprender la distribución y evolución del acceso a tecnologías en distintas regiones. Las herramientas desarrolladas facilitan el análisis continuo y permiten decisiones informadas basadas en datos.