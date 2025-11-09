# Predicción de Precios de Viviendas — *King County, Washington*

Este proyecto analiza el conjunto de datos de viviendas en **King County (EE. UU.)**, aplicando técnicas de **análisis exploratorio de datos (EDA)** y **modelos de regresión lineal** para comprender los factores que más influyen en el precio de las propiedades.  


## Análisis y Visualización de Datos  
Se emplean visualizaciones como **histogramas**, **boxplots** y **gráficos de dispersión** para comprender la distribución y las relaciones entre variables.  
Además, se genera un **mapa de calor de correlaciones** para identificar los vínculos más fuertes con el precio.  

Entre los hallazgos principales:
- Las viviendas con **vista al agua** presentan precios en promedio **2.3 veces mayores**.  
- Existe una **correlación positiva significativa** entre el **área habitable (sqft_living)** y el **precio final de la propiedad**.  


##  Modelado Predictivo
Se desarrolló un modelo de **Regresión Lineal** utilizando la librería `Scikit-learn`.  
El modelo sigue un enfoque **supervisado** con división del dataset en **entrenamiento** y **prueba**, evaluando el desempeño mediante las métricas:

- `R²` (Coeficiente de determinación)  
- `MAE` (Error Absoluto Medio)  
- `RMSE` (Raíz del Error Cuadrático Medio)  

Se analizaron los **coeficientes de las variables** y se compararon los **valores reales vs predichos**, identificando las características con **mayor impacto económico** en el precio.



##  Resultados Destacados
- Correlación positiva clara entre **área habitable (sqft_living)** y **precio**.  
- Las propiedades con **vista al agua (waterfront = 1)** tienen precios notablemente más altos.  
- El modelo predictivo logra **capturar la tendencia general del mercado** con un ajuste satisfactorio.  
- Los resultados sugieren que **ubicación**, **vista** y **tamaño** son los principales factores que determinan el valor de una pro
