# Descripción del proyecto
Este proyecto implica la extracción y transformación de datos desde un archivo de Excel con múltiples hojas de cálculo. Cada hoja se exporta como un archivo CSV independiente para su posterior análisis y procesamiento.

### Detalles del archivo de entrada
El archivo de origen contiene las siguientes hojas de cálculo:
- `Acc_vel_loc_sinrangos`
- `Velocidad_sin_Rangos`
- `Accesos_tecnologia_localidad`
- `Velocidad % por prov`
- `Totales VMD`
- `Totales Accesos Por Tecnología`
- `Accesos Por Tecnología`
- `Penetración-poblacion`
- `Penetracion-hogares`
- `Penetracion-totales`
- `Totales Accesos por rango`
- `Accesos por rangos`
- `Dial-BAf`
- `Totales Dial-BAf`
- `Ingresos `

### Proceso de exportación
Se ha implementado un script de Python que:
1. Carga el archivo de Excel.
2. Itera sobre cada hoja de cálculo.
3. Exporta cada hoja a un archivo CSV en la ruta especificada: `C:/Users/maron.LAPTOP-UEJMOSD4/Desktop/PI_2/DATA_LIMPIO`.

### Archivos CSV generados
Los archivos resultantes se guardaron correctamente y se nombraron según la hoja de cálculo original:
- `Acc_vel_loc_sinrangos.csv`
- `Velocidad_sin_Rangos.csv`
- `Accesos_tecnologia_localidad.csv`
- `Velocidad % por prov.csv`
- `Totales VMD.csv`
- `Totales Accesos Por Tecnología.csv`
- `Accesos Por Tecnología.csv`
- `Penetración-poblacion.csv`
- `Penetracion-hogares.csv`
- `Penetracion-totales.csv`
- `Totales Accesos por rango.csv`
- `Accesos por rangos.csv`
- `Dial-BAf.csv`
- `Totales Dial-BAf.csv`
- `Ingresos .csv`

### Consideraciones
- Se recomienda verificar que la ruta de destino (`C:/Users/maron.LAPTOP-UEJMOSD4/Desktop/PI_2/DATA_LIMPIO`) exista antes de ejecutar el script.
- Las barras invertidas en las rutas deben estar correctamente escapadas (o se debe usar `r"..."` para evitar errores de Unicode).

### Próximos pasos
El análisis de los archivos CSV generados puede continuar con herramientas como Pandas para manipulación de datos y Power BI para visualizaciones.

