# Power Bi - Analisis de la cobertura de servicios públicos en Colombia para el 2023 

![](https://signpost-colombia.zendesk.com/hc/article_attachments/8932427789597)

Este repositorio contiene un análisis de la cobertura de los principales servicios públicos en Colombia para el año 2023. Se basa en la información proporcionada en una base de datos que muestra el porcentaje de cobertura de servicios como acueducto, alcantarillado, energía, gas y telefonía por regiones y departamentos.

![image](https://github.com/user-attachments/assets/7a01ea84-765b-4db8-bcb7-3612eb66ba75)       ![image](https://github.com/user-attachments/assets/c0c9db6e-26df-4115-b462-8abbdc2286bc)


## Descripción

El objetivo de este proyecto es visualizar las diferencias en la cobertura de servicios públicos entre las distintas regiones de Colombia. A través de gráficos y tablas, se observa cómo la electrificación ha avanzado más en comparación con otros servicios como el gas o el alcantarillado, especialmente en áreas rurales.

## Vizualizaciones

### Cobertura total por región
![image](https://github.com/user-attachments/assets/b8111ffa-c318-4eaf-bb64-533dedaa6325)

### Comparativa de Cobertura de Alcantarillado vs Gas
![image](https://github.com/user-attachments/assets/92f0f6b4-2bfb-4cab-863b-684c7ef1b6ae)

### Cobertura de Servicios Públicos por Regiones
![image](https://github.com/user-attachments/assets/cdc28b09-9eaf-46e7-9e1c-c5afed571589)

## Datos
Los datos proporcionados sobre la cobertura de servicios públicos en Colombia y se han organizado en formato CSV para facilitar su análisis:

## Tecnologías Utilizadas
- **Power BI**: Para la visualización de datos y gráficos interactivos.
- **Python**: Se utilizaron scripts en Python para organizar los datos y generar gráficos adicionales.

## Conclusiones

- **Cobertura energética**: Las regiones Insular y Caribe tienen la mayor cobertura en energía eléctrica, mientras que la Amazonia presenta una menor cobertura.
- **Desigualdades**: La cobertura de servicios como el alcantarillado y el gas sigue siendo desigual, con regiones como la Amazonia y la Pacífica con los valores más bajos.
- **Comparativa de servicios**: La cobertura de gas natural y telefonía es significativamente más baja en comparación con otros servicios como energía y acueducto.

## Cómo Usar Este Repositorio

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Titania77/CoberturaServiciosColombia2023.git


Aquí les dejo algunas pautas para que puedan tenerlas en cuenta a la hora de realizar un informe en POWER BI
---

# 📊 Pasos para Realizar un Informe Estructurado en Power BI

### 1. 🎯 Definir el Objetivo del Informe
   - **Descripción del objetivo**: Comienza definiendo claramente el propósito del análisis. ¿Qué deseas investigar o mostrar? Por ejemplo, podrías analizar el consumo de un producto entre distintos grupos o identificar patrones en datos financieros.
   - **Audiencia**: Identifica quiénes serán los lectores del informe (ejecutivos, analistas, clientes) y adapta el nivel de detalle a sus necesidades.

### 2. 📥 Preparar los Datos
   - **Revisión de datos**: Asegúrate de que los datos estén completos y organizados en un formato adecuado para análisis. Identifica y corrige posibles errores o datos faltantes.
   - **Importación y transformación en Power BI**: Carga los datos en Power BI y utiliza el editor de consultas para realizar transformaciones como:
     - Cambiar tipos de datos.
     - Quitar columnas innecesarias.
     - Realizar cálculos previos (agregar columnas calculadas o medidas para promedios, totales, porcentajes, etc.).

### 3. 📈 Diseño y Selección de Visualizaciones
   - **Elegir gráficos relevantes**: Selecciona los gráficos que mejor se adapten a la información que deseas comunicar:
     - 📊 Gráfico de barras o columnas para comparaciones entre categorías.
     - 📉 Gráfico de líneas para mostrar tendencias temporales.
     - 🗺️ Mapas para datos geográficos.
     - 🔍 Gráfico de dispersión para analizar relaciones entre variables.
   - **Aplicar segmentaciones y filtros**: Permite que el usuario del informe filtre datos por categoría, período de tiempo, etc., para facilitar la exploración.
   - **Consistencia visual**: Usa una paleta de colores coherente y una tipografía clara. Asegúrate de que todos los gráficos mantengan un estilo visual uniforme para la cohesión del informe.

### 4. 🧮 Creación de Medidas y Cálculos Personalizados
   - **Cálculos básicos**: Agrega medidas para cálculos como suma, promedio, conteo y porcentajes que aporten valor al análisis.
   - **Medidas personalizadas en DAX**: Si es necesario, utiliza DAX para crear medidas más complejas, como cálculos de variación interanual, índices de crecimiento, o cualquier métrica clave específica para tu análisis.

### 5. 📑 Estructurar el Informe por Secciones
   - **Introducción**: Explica brevemente el contexto del análisis, el alcance del informe y los objetivos específicos.
   - **Análisis detallado**: Divide la información en secciones claras, cada una abordando un aspecto específico del análisis:
     - **Análisis descriptivo**: Presenta gráficos de resumen que muestren los datos generales y las tendencias principales.
     - **Análisis comparativo**: Muestra comparaciones relevantes entre grupos o períodos, si corresponde.
     - **Análisis de correlación**: Si has realizado un análisis de relaciones entre variables, presenta tus hallazgos y explica las conclusiones.
   - **Conclusiones**: Resalta los hallazgos clave de tu análisis y su importancia. Incluye cualquier recomendación práctica derivada de los datos.

### 6. 🔄 Añadir Elementos de Interactividad
   - **Segmentadores y filtros de visualización**: Incluye segmentadores de datos para que el usuario pueda explorar diferentes cortes de la información.
   - **Botones y navegación**: Si tienes varias páginas, considera agregar botones o una navegación clara para facilitar el desplazamiento entre secciones.
   - **Tooltips personalizados**: Utiliza tooltips para proporcionar información adicional cuando el usuario pase el cursor sobre ciertos elementos en los gráficos.

### 7. ✅ Conclusión y Recomendaciones Finales
   - **Resumen de hallazgos clave**: Resume las conclusiones principales de cada sección en un lenguaje claro y conciso.
   - **Implicaciones prácticas**: Describe las implicaciones de tus hallazgos y cualquier recomendación que el equipo o la audiencia del informe debería considerar.

### 8. 🔍 Revisión Final y Publicación
   - **Revisión de coherencia**: Asegúrate de que el informe sea visualmente coherente, fácil de leer y sin errores de formato o datos.
   - **Prueba de navegación**: Navega por el informe y verifica que todos los filtros, botones y tooltips funcionen correctamente.
   - **Publicación y exportación**: Publica el informe en la plataforma deseada (Power BI Service, PDF, PowerPoint) y verifica que sea accesible para tu audiencia.

---


