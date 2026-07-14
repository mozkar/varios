# Formulario de Estadística Descriptiva

Este formulario compendia las métricas fundamentales para el análisis exploratorio de datos, divididas por sus respectivas dimensiones estadísticas.

---

## 1. Medidas de Tendencia Central

Representan el punto en torno al cual se concentran los datos de una distribución.

### Media Aritmética ($\mu$ o $\bar{x}$)
* **Poblacional:**
  $$\mu = \frac{\sum_{i=1}^{N} x_i}{N} \tag{1.1}$$
* **Muestral:**
  $$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n} \tag{1.2}$$

### Mediana ($\tilde{x}$)
Es el valor que divide la distribución en dos partes iguales una vez ordenados los datos de forma ascendente.
* Si $n$ es impar, la posición del elemento central es: $\frac{n + 1}{2}$
* Si $n$ es par, la mediana se calcula como el promedio de los dos valores centrales: 
  $$\tilde{x} = \frac{x_{(n/2)} + x_{(n/2 + 1)}}{2} \tag{1.3}$$

---

## 2. Medidas de Dispersión

Miden el grado de variabilidad o alejamiento de los datos respecto a la media aritmética.

### Rango ($R$)
$$R = x_{max} - x_{min} \tag{2.1}$$

### Varianza ($\sigma^2$ o $s^2$)
* **Poblacional:**
  $$\sigma^2 = \frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N} \tag{2.2}$$
* **Muestral (con corrección de Bessel):**
  $$s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n - 1} \tag{2.3}$$

### Desviación Estándar ($\sigma$ o $s$)
* **Poblacional:**
  $$\sigma = \sqrt{\frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N}} \tag{2.4}$$
* **Muestral:**
  $$s = \sqrt{\frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n - 1}} \tag{2.5}$$

### Coeficiente de Variación ($CV$)
$$CV = \left( \frac{s}{\bar{x}} \right) \times 100\% \tag{2.6}$$

---

## 3. Medidas de Forma y Distribución

Definen el comportamiento geométrico y el perfil de la curva de frecuencias de los datos.

### Asimetría (Skewness - $g_1$)
Mide el grado de distorsión o simetría de la distribución respecto a su media.



* **Coeficiente de Asimetría de Fisher (Muestral):**
  $$g_1 = \frac{\frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^3}{s^3} \tag{3.1}$$

* **Interpretación:**
  * $g_1 > 0$: Asimetría positiva (cola larga a la derecha).
  * $g_1 = 0$: Distribución perfectamente simétrica.
  * $g_1 < 0$: Asimetría negativa (cola larga a la izquierda).

### Curtosis (Kurtosis - $g_2$)
Mide qué tan escarpada o achatada es la curva de una distribución en comparación con una distribución normal.



* **Coeficiente de Curtosis de Fisher (Exceso de Curtosis Muestral):**
  $$g_2 = \frac{\frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^4}{s^4} - 3 \tag{3.2}$$

* **Interpretación:**
  * $g_2 > 0$: **Leptocúrtica** (curva apuntada, colas pesadas).
  * $g_2 = 0$: **Mesocúrtica** (distribución normal estándar).
  * $g_2 < 0$: **Platicúrtica** (curva achatada, colas ligeras).

---

## 4. Medidas de Posición No Central

Dividen un conjunto de datos ordenados en intervalos iguales.

### Percentil ($P_k$)
El valor bajo el cual se encuentra el $k\%$ de los datos.
$$\text{Posición de } P_k = \frac{k \cdot (n + 1)}{100} \tag{4.1}$$

* **Rango Intercuartílico ($IQR$):** Mide la dispersión del 50% central de los datos ($Q_3 - Q_1$).
  $$IQR = Q_3 - Q_1 \tag{4.2}$$
