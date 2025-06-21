# Machine Learning Engineering: Curso I
Objetive: Entender el ciclo de vida de un proyecto de Machine Learning, el ecosistema y las tecnologías de ML, y los algotirmos clasicos de ML.

<img src="https://ci3.googleusercontent.com/mail-sig/AIorK4zt6tOa3204Znd9u8YWMhVnZGy1TWuE7fovhJFzJFvFsfBrTb4F2vc6V99oNs0LODE1jmt1Nqo" width=250>


## 1.Definición del problema
<br>
ABC es una empresa del sector inmobiliario peruano que desea implementar una solución de Machine Learning para predecir el precio final de venta de propiedades residenciales, utilizando datos históricos del mercado y características detalladas de las viviendas. Este modelo permitirá anticipar el valor real de una propiedad antes de ponerla en venta, durante negociaciones o como parte de un análisis de inversión..
<br>
<br>
<b>🎯 Beneficios para la empresa : </b>
<br>
<br>
<ul>
<li>Mayor eficiencia en la tasación y cierre de ventas</li>
<li>Mejora en la precisión de presupuestos y pronósticos</li>
<li>Reducción de tiempo en el ciclo de ventas</li>
<li>Ventaja competitiva en análisis de datos inmobiliarios</li>
</ul>

<br>
<br>
<b>🎯 Objetivo del Modelo ML : </b> 
Desarrollar un modelo de regresión predictiva que pueda estimar con precisión el precio de venta más probable en el mercado actual, a partir de información estructurada sobre una vivienda, como:
<br>
<br>
<ul>
  <li>Tamaño en metros cuadrados</li>
  <li>Número de habitaciones y baños</li>
  <li>Año de construcción</li>
  <li>Tipo de construcción y materiales</li>
  <li>Ubicación (ciudad, código postal, cercanía a servicios)</li>
  <li>Condiciones del mercado local</li> 
</ul>
<br>
<br>

## 2.Diagrama de Flujo del Proyecto ML
<br>
<img width="707" alt="image" src="https://github.com/user-attachments/assets/3b82e5de-60b4-40b7-a844-2f5a52d66175" />
<br>
<br>

## 3.Data set
<br>

**Descripcion**
<br>
<br>
El conjunto de datos de Ames Housing fue compilado por Dean De Cock para su uso en la enseñanza de la ciencia de los datos. Es una increíble alternativa para los científicos de datos que buscan una versión modernizada y ampliada del tan citado conjunto de datos de Boston Housing. 
<br>

**Data dictionary**
<br>
<br>
<img width="578" alt="image" src="https://github.com/user-attachments/assets/5784b528-b6f6-4435-bc21-dccf6739441d" />
<img width="581" alt="image" src="https://github.com/user-attachments/assets/dceb4e3c-2c77-42f6-9afb-9405b86746e7" />

<br>

**Fuente de datos**
<br>
<br>
<li> <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">House Prices - Advanced Regression Techniques</a></li>
<br>
<br>

## 4.Model Card 
* <a href="https://github.com/jhuarancca/DSRP-MachineLearningEngineering-01/blob/main/ModelCard.md">ML Model Card</a>
<br>
<br>

## 5.Resultados (métricas)

**Offline assesment**

<ul>
<li>Incremento el 5% de la eficiencia en la tasación de inmuebles</li>
<li>Reducción de tiempo en el ciclo de ventas a 3 semanas en promedio</li>
</ul>

**Online assesment**

 ![image](https://github.com/user-attachments/assets/7871e5fa-3fc6-4dd1-8e51-e6cda4786535)


<br>
<br>

## 7.ML Technologies
* `scikit-learn`: librería algoritmos ML
* `pandas`: libreria análisis y manipulación de datos
  
  **MLOPs Architecture**
  <br>
  ![image](https://github.com/user-attachments/assets/e67bb64b-a008-4d86-a997-a49dc7f73a7d)

<br>
<br>

## 6.Conclusiones
<br>
<ul>
  <li>No utilizar el modelo fuera del contexto inmobiliario residencial de EE.UU.</li>
  <li>Verificar manualmente predicciones fuera del rango promedio de precios (outliers).</li> 
  <li>Revisar las predicciones en zonas rurales o poco urbanizadas donde el modelo tiene menor precisión.</li> 
  <li>Actualizar el modelo con datos recientes cada 6–12 meses para evitar obsolescencia.</li>
</ul>

## 9.Bibliografía
<br>
<ul>
  <li> <a href="https://medium.com/inside-intelligence/flujo-completo-de-machine-learning-95a1c8219296">Flujo de Trabajo de Machine Learning</a></li>
    <li> <a href="https://ihsanulpro.medium.com/complete-machine-learning-project-flowchart-explained-0f55e52b9381">Complete Machine Learning Project Flowchart Explained</a></li>
    <li> <a href="https://www.ibm.com/docs/es/SS3RA7_18.4.0/pdf/ModelerCRISPDM.pdf">Guía de CRISP-DM de IBM SPSS Modeler</a></li>
    <li> <a href="https://mllops.vercel.app/">MyMLOPs</a></li>
  <li> <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">House Prices - Advanced Regression Techniques</a></li>
</ul>


