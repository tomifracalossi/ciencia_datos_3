# Mi módulo de Ciencia de Datos III

*Tomás Agustín Sanchez Fracalossi*

---

Este es un módulo que contiene algunas clases utilizadas en la asignatura Ciencia de Datos III de la Licenciatura en Ciencia de Datos de la Universidad Nacional del Litoral.

---

## Clases

- `AnalisisDescriptivo`: clase para realizar un análisis descriptivo de un conjunto de datos cuantitativos, estimando su densidad con un histograma o con kernels (gaussiano, uniforme, cuadrático o triangular). A su vez permite graficar el QQ plot con distribución normal estándar, mostrar las estadísticas principales y graficar los datos con boxplots.

- `GeneradoraDeDatos`: clase para generar muestras de datos con distribución específica: normal, uniforme, t-Student, exponencial y BS.

- `Regresion`: clase padre que provee herramientas para realizar análisis de regresión lineal simple o múltiple, así como también análisis de regresión logística.

- `RegresionLineal`: clase hija que hereda propiedades de la clase Regresion para hacer regresión lineal simple o múltiple.

- `RegresionLogistica`: clase hija que hereda propiedades de la clase Regresion para hacer regresión lineal simple o múltiple.