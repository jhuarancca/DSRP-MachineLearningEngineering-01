
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






⚖️ 3. Factores
Estructurales: tamaño en pies cuadrados, número de habitaciones y baños, año de construcción

Geográficos: ubicación (código postal), cercanía a escuelas, nivel de criminalidad, accesos

Condiciones del mercado: tendencias de precios en la zona, tasa de interés hipotecaria, tiempo promedio en mercado

📊 4. Métricas del Modelo
MAE (Error Absoluto Medio): $13,750

RMSE (Raíz del Error Cuadrático Medio): $21,480

R² (Coeficiente de determinación): 0.89

Intervalo de confianza del 95% para predicción: ± $18,000

📁 5. Datos de Entrenamiento
Tamaño del conjunto: 1,460 propiedades (Ames Housing Dataset + extensiones propias)

Rango temporal: 2006–2010

Ubicación: Ames, Iowa (y simulaciones para otras regiones similares)

Variables: 79 atributos de propiedades (estructurales, geográficos, servicios, etc.)

Preprocesamiento: imputación de valores nulos, codificación de variables categóricas, normalización

🧪 6. Datos de Evaluación
Proporción de entrenamiento/prueba: 80% / 20%

Datos externos utilizados para validación cruzada: Muestras de propiedades de Zillow y Redfin (solo para validación, no entrenamiento)

Distribución geográfica del set de prueba: variada por código postal para evitar sesgo espacial

⚠️ 7. Consideraciones Éticas
El modelo puede reflejar sesgos sociales o estructurales históricos (por ejemplo, desigualdades por zonas geográficas o acceso a servicios).

Riesgo de sobrevaloración o subvaloración en zonas con poca representación en los datos de entrenamiento.

No debe ser usado como única fuente para decisiones financieras o legales sin revisión profesional adicional.

🚨 8. Advertencias y Recomendaciones
No utilizar el modelo fuera del contexto inmobiliario residencial de EE.UU.

Verificar manualmente predicciones fuera del rango promedio de precios (outliers).

Revisar las predicciones en zonas rurales o poco urbanizadas donde el modelo tiene menor precisión.

Actualizar el modelo con datos recientes cada 6–12 meses para evitar obsolescencia.

📈 9. Análisis Cuantitativo
Métrica	Valor
MAE	$13,750
RMSE	$21,480
R² global	0.89
R² para propiedades > $500K	0.82
% predicciones con error < 10%	84%

El modelo tiene mejor desempeño en zonas suburbanas de ingresos medios.

Las zonas urbanas densas muestran mayor varianza, con mayores errores relativos.

Las propiedades de lujo (>$750K) presentan menor precisión por menor representación en los datos.

