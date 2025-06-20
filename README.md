# mineriaAIEP_02

aca esta el readmi de inicio.


URL KAGLE

https://www.kaggle.com/datasets/atharvasoundankar/taco-sales-dataset-20242025


En este caso sí podrías hacer una regresión lineal, ya que hay variables numéricas continuas que pueden servir como predictores. Algunas opciones interesantes para aplicar una regresión lineal incluyen:
Posibles modelos de regresión lineal
- 1 Predecir el tiempo de entrega (Delivery Duration (min))
 - 1.1. 	Variables independientes: Distance (km), Weekend Order, Order Time
 - 1.2. 	¿La distancia y el horario afectan el tiempo de entrega?
- 2	Predecir el monto del precio del pedido (Price ($))
 - 2.1.	Variables independientes: Taco Size, Taco Type, Toppings Count
 - 2.2.	¿El tipo de taco y la cantidad de ingredientes afectan el precio?
- 3	Predecir la propina (Tip ($))
 - 3.1.	Variables independientes: Delivery Duration (min), Weekend Order, Price ($)
 - 3.2.	¿Los clientes dejan más propina si el pedido llega rápido o si es fin de semana?

# *Evaluación de Actividad 1*

Desarrollar proyecto elegido por el grupo, tomando un DataSet desde Kaggle.com, el cual debe estar inscrito en la planilla de proyecto compartida para estos efectos.

Que se evaluará:

De la Metodología CRISP-DM, se evaluará los primeros 3 pasos.

    1.- Conocer el Negocio: Dependiendo del proyecto seleccionado, explicar con detalle el contexto. Para esto busque información en Internet y si puede relacionarlo a la realidad de nuestro país, ayudaría bastante.

 

    2.- Conocer los Datos: Explicar los datos que vienen en su origen. Esto implica no solamente definir el nombre de la columna, sino que también explicar los posibles rengos de valores, lo que permitirá entender la información contenida.



Acá también se debe mostrar los datos, estructura del dataframe, ver los diferentes valores de los atributos, revisar la completitud de los datos, mostrar estadísticas de los datos, explicar los datos utilizando gráficos (esto permitirá ver cantidades, porcentajes, tendencias, etc).

 

Definir y responder 3 preguntas de negocio: Esto aplicando groupby y desplegando resultados con gráficos.

 

    3.- Limpieza de Datos:

Identificar valores nulos, imputar valores para reemplazar los nulos, identificar valores outliers (utilice gráficos) e identifique los registros.

Reemplazar valores de tipo string por datos numéricos.

# **Fin evaliacion 1**


-----------------------------



#**Sugerencia de roto para trabajo competo porte 1 y 2**

Para que tu trabajo de análisis de datos en **Jupyter Notebook** sea evaluado de manera integral, debes cubrir los siguientes puntos clave en tu estructura, alineados con una posible **rúbrica de evaluación**:

---

### **1. Introducción y Contexto del Negocio**
   - **Descripción del problema**: Explicar el objetivo del análisis y el tipo de negocio (ej: ventas, marketing, logística).
   - **Fuente de los datos**: Origen del dataset (ej: Kaggle, empresa, simulado) y variables disponibles.
   - **Preguntas de análisis**: Plantear 3-5 preguntas concretas que guíen el análisis. Ejemplo:
     - *¿Qué factores influyen más en las ventas?*
     - *¿Existe estacionalidad en la demanda?*
     - *¿Qué segmentos de clientes son más rentables?*

---

### **2. Preparación y Exploración de Datos (EDA)**
   - **Carga y visualización inicial**: Mostrar las primeras filas del dataset con `head()`, `info()`, `describe()`.
   - **Limpieza de datos**:
     - Manejo de valores nulos o duplicados.
     - Corrección de tipos de datos (ej: fechas como `datetime`).
   - **Análisis exploratorio**:
     - Visualizaciones (histogramas, boxplots, scatter plots) para entender distribuciones y relaciones.
     - Identificación de outliers o patrones iniciales.

---

### **3. Análisis Estadístico y Respuesta a Preguntas**
   - **Técnicas aplicadas**:
     - Agrupaciones (`groupby`), correlaciones, pruebas de hipótesis (si es relevante).
     - Uso de métricas como media, mediana, desviación estándar.
   - **Visualizaciones clave**: Gráficos que respondan directamente a las preguntas planteadas (ej: heatmaps de correlación, series de tiempo).
   - **Interpretación**: Explicación clara de los hallazgos en contexto del negocio.

---

### **4. Modelado (Opcional, dependiendo del nivel)**
   - Si aplica: Modelos simples (regresión, clustering) para predecir o segmentar.
   - Evaluación del modelo (métricas como R², precisión) y conclusiones.

---

### **5. Conclusiones y Recomendaciones**
   - **Resumen de insights**: Principales hallazgos vinculados a las preguntas iniciales.
   - **Recomendaciones accionables**: Propuestas concretas para el negocio basadas en datos.
   - **Limitaciones**: Problemas con los datos (ej: falta de información, sesgos).

---

### **6. Presentación y Código**
   - **Organización del Notebook**:
     - Títulos y markdowns explicativos (no solo código).
     - Código bien comentado y estructurado.
   - **Reproducibilidad**: El notebook debe ejecutarse sin errores (incluyendo librerías usadas en un `requirements.txt`).

---

### **Posibles Criterios de Evaluación en una Rúbrica**
| **Categoría**               | **Puntos a Evaluar**                                                                 |
|-----------------------------|-------------------------------------------------------------------------------------|
| **Claridad de preguntas**    | Preguntas relevantes y alineadas con el negocio.                                    |
| **Limpieza de datos**       | Manejo adecuado de missing values, outliers y transformaciones.                    |
| **Análisis exploratorio**   | Visualizaciones informativas y descripción de patrones.                            |
| **Profundidad del análisis**| Uso de técnicas estadísticas/modelos apropiados para responder preguntas.          |
| **Conclusiones**            | Insights útiles y recomendaciones prácticas.                                        |
| **Presentación**            | Notebook organizado, código claro y documentación explicativa.                     |

---

### **Tips Adicionales**
- Usa librerías como `pandas`, `matplotlib/seaborn`, y `scipy/statsmodels`.
- Incluye un **README** si entregas archivos adicionales.
- Si es un equipo, define roles (ej: uno para EDA, otro para modelado).

¡Este esquema asegurará que cubras todos los aspectos esenciales para un análisis profesional!
