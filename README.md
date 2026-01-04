# 📉 Análisis Multivariado: Predicción de Grasa Corporal

Este proyecto fue desarrollado para la materia de **Análisis Multivariado** asinatura que llevé en la Facultad de Ciencias de la UNAM. El objetivo principal es explorar las interrelaciones entre diversas medidas antropométricas y determinar cómo este conjunto de variables predictoras puede explicar la varianza en el porcentaje de grasa corporal.

## 🧠 Enfoque del Proyecto

A diferencia de un análisis simple, este trabajo aborda el problema desde una perspectiva multivariada, considerando que las medidas corporales no actúan de forma aislada. Nos enfocamos en entender la estructura de los datos, la correlación entre variables y la construcción de un modelo robusto.

## 🛠️ Metodología Aplicada

El análisis incluye pasos críticos de la estadística multivariada:

* **Exploración de la Estructura de Datos:** Identificación de patrones de comportamiento entre múltiples medidas (Pecho, Abdomen, Cadera, Cuello, etc.).
* **Análisis de Correlación:** Estudio de las relaciones lineales entre las variables para detectar multicolinealidad y entender qué medidas aportan información redundante.
* **Modelado Multivariado:** Implementación de modelos que consideran el efecto conjunto de los predictores para minimizar el error en la estimación del porcentaje de grasa corporal.
* **Visualización Multivariable:** Uso de `Pair Plots` y Mapas de Calor (`Heatmaps`) para visualizar la densidad y relación de los datos en un espacio multidimensional.

## 📊 Hallazgos Clave

* **Variables de Alto Impacto:** Se identificó mediante el análisis de coeficientes qué medidas (como el abdomen) tienen una mayor carga predictiva en el modelo.
* **Relaciones Inter-variables:** El estudio permitió observar cómo variables como el Peso y el IMC interactúan con medidas específicas, validando supuestos teóricos de la composición corporal.

## 📂 Estructura del Repositorio

* `Bodyfat_Model.ipynb`: Desarrollo del análisis estadístico y entrenamiento de modelos.
* `bodyfat.csv`: Dataset con las mediciones antropométricas utilizadas.
