
## Model Card: Modelo de Predicción de Precio de Propiedades 
**📌 1. Detalle del Modelo**
<br>
<br>
<ul>
  <li>Nombre del modelo: ModeloPredictivo v1.0</li>
  <li>Tipo de modelo: Regresion Lineal</li>
  <li>Algoritmo utilizado: Ordinary Least Squares (OLS) regression</li>
  <li>Objetivo: Estimar el precio de venta de una propiedad residencial, basado en sus características estructurales, geográficas y de mercado.</li>
  <li>Fecha de última actualización: Junio 2025</li>
</ul>
<br>
<br>

**📌 2. Casos de Uso**
<br>
<br>

**✔️ Casos de uso recomendados:**
<ul>
  <li>Valoración automática de inmuebles residenciales</li>
  <li>Asistencia a agentes inmobiliarios en fijación de precios</li>
  <li>Evaluación de garantías hipotecarias en procesos de crédito</li>
  <li>Soporte para análisis de inversión inmobiliaria</li>
</ul>
<br>
<br>

**❌ Casos de uso no recomendados:**
<ul>
  <li>Valoración de propiedades comerciales o industriales</li>
  <li>Decisiones legales sin validación profesional</li>
  <li>Predicción de precios en mercados fuera de EE.UU.</li>
</ul>
<br>
<br>

**⚖️ 3. Factores**
<br>
<br>
<ul>
  <li>Estructurales: tamaño en metros cuadrados, area de garage, año de construcción</li>
  <li>Condiciones del mercado: Mes y año vendido</li>
</ul>
<br>
<br>

![image](https://github.com/user-attachments/assets/dc723869-06b0-454c-9f63-7cb8b5f190aa)


**📊 4. Métricas del Modelo**
<br>

<ul>
  <li>RMSE (Raíz del Error Cuadrático Medio): $53,130.76</li>
  <li>R² (Coeficiente de determinación): 0.606 </li>
</ul>

![image](https://github.com/user-attachments/assets/198a2d7c-529e-4f14-8e4a-d640ba4f6d42)

<br>


**📁 5. Datos de Entrenamiento**
<br>
<br>
<ul>
  <li>Tamaño del dataset: 960 propiedades </li>
  <li>Variables: 6 atributos de propiedades </li>
  <li>Preprocesamiento: data cleaning, normalización </li>
</ul>

![image](https://github.com/user-attachments/assets/ac953ffc-5b88-4d31-bb95-6c781d8739de)
<br>

**🧪 6. Datos de Evaluación**
<br>

<ul>
  <li>Proporción de entrenamiento/prueba: 80% / 20%</li>
  <li>Variables: 6 atributos de propiedades </li>
  <li>Preprocesamiento: data cleaning, normalización </li>
</ul>
<br>

**⚠️ 7. Consideraciones Éticas**
<br>
<ul>
  <li>El modelo puede reflejar sesgos sociales o estructurales históricos (por ejemplo, desigualdades por zonas geográficas o acceso a servicios)</li>
  <li>Riesgo de sobrevaloración o subvaloración en zonas con poca representación en los datos de entrenamiento.</li>
  <li>No debe ser usado como única fuente para decisiones financieras o legales sin revisión profesional adicional. </li>
</ul>
<br>

**🚨 8. Advertencias y Recomendaciones**
<br>
<ul>
  <li>No utilizar el modelo fuera del contexto inmobiliario residencial de EE.UU.</li>
  <li>Verificar manualmente predicciones fuera del rango promedio de precios (outliers).</li>
  <li>Revisar las predicciones en zonas rurales o poco urbanizadas donde el modelo tiene menor precisión. </li>
  <li>Actualizar el modelo con datos recientes cada 6–12 meses para evitar obsolescencia. </li>
</ul>
<br>

**📈 9. Análisis Cuantitativo (Comparativo Predicción versus real)**
<br>
![image](https://github.com/user-attachments/assets/2793762b-c056-4808-ab7a-8362264ca1b8)






