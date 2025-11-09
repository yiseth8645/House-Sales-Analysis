# House-Sales-Analysis
Este proyecto realiza un **análisis exploratorio de los precios de viviendas en King County (EE. UU.)**, utilizando **Python**, **Pandas**, **Matplotlib** y **Seaborn**.  
Forma parte de mi formación en análisis de datos dentro del programa de **IBM Data Analyst**.

 Objetivo
Identificar los factores que más influyen en el precio de las viviendas y visualizar sus relaciones mediante técnicas de análisis estadístico y regresión lineal.

ontenido del Proyecto
El proyecto inicia con la limpieza y preparación del conjunto de datos `kc_house_data.csv`, eliminando valores nulos, transformando columnas y seleccionando las variables más relevantes.  
Posteriormente, se realiza un **análisis descriptivo y exploratorio**, identificando comportamientos de variables como el número de habitaciones, baños, área habitable y la presencia de vista al agua.  

Se emplean visualizaciones como histogramas, boxplots y gráficos de dispersión para comprender la distribución y las relaciones entre variables. También se genera un mapa de calor de correlaciones para observar los vínculos más fuertes con el precio.  
Entre los principales hallazgos se destaca que las viviendas con vista al agua presentan precios en promedio **2.3 veces mayores**, y que existe una **correlación positiva entre el área habitable y el valor final de la propiedad**.

A continuación, se desarrolla un modelo de **regresión lineal** con la librería Scikit-learn, usando un enfoque supervisado para predecir precios. Se divide el conjunto de datos en entrenamiento y prueba, evaluando el desempeño del modelo mediante métricas como `R²`, `MAE` y `RMSE`.  
Se analizan los coeficientes de las variables y se visualiza la comparación entre los valores reales y los valores predichos, destacando las variables con mayor impacto económico.

Finalmente, se plantea la posibilidad de ampliar el estudio mediante el uso de modelos más complejos como **árboles de decisión** o **Random Forest**, así como la creación de un **dashboard interactivo** (con Streamlit o Power BI) que permita visualizar los resultados en tiempo real. Este tipo de herramientas serían útiles para apoyar decisiones estratégicas en el sector inmobiliario, identificando oportunidades de inversión y patrones de comportamiento del mercado.

Herramientas y Librerías Utilizadas
- **Python**
- **Pandas** y **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn**
- **Jupyter Notebook**


esultados Destacados
- Se identificó una correlación positiva entre el área habitable (*sqft_living*) y el precio de la vivienda.  
- Las propiedades con vista al agua (*waterfront = 1*) muestran precios notablemente superiores.  
- El modelo predictivo de regresión lineal logra capturar la tendencia general del mercado con un nivel de ajuste adecuado.  
- Los resultados sugieren que la ubicación, la vista y el tamaño son los principales factores que determinan el valor de las propiedades en King County.  


Autor
**Juliana Yiseth Rengifo Rincón**  
Estudiante de Ingeniería Industrial – Universidad Nacional de Colombia  
Apasionada por el análisis de datos, la automatización de procesos y la innovación tecnológica.

Contacto:  
- [LinkedIn](https://www.linkedin.com/in/juliana-yiseth-rengifo-rincon-02aa51151 )  
- **Correo:** julianayiseth.rengiforincon@gmail.com  

