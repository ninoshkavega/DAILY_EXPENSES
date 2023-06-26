# DAILY_EXPENSES
ANÁLISIS EXPLORATORIO

El objetivo principal fue realizar un análisis exploratorio y recrearlos visualmente con librerías como #matplotlib y #seaborn.
Además de realizar un análisis, también se aplicó una proyección de suavizado exponencial simple por las características de los datos empleados. El volumen de datos no es grande, y tampoco tiene un patrón definido. El modelo utiliza el parámetro “Alpha” y este controla la ponderación de los datos, suavizando los mismos en caso de existir anomalías. Esta ponderación se realiza para predecir valores futuros o estimar tendencias en el tiempo.

Al realizar el “#EDA” se llegó a las siguientes conclusiones:

📌 Los gastos mayoritariamente son "no esenciales".
📌 Hay ciertas anomalías en los gastos diarios, ya que en la gráfica se puede observar picos excesivos. Habría que verificar si existe alguna relación con el tiempo cuando ocurrió el evento.
📌En los meses de abril y mayo, la diferencia en gastos fue mínima. Sin embargo, abril fue el mes donde más se gastó.
📌 Existe una desviación estándar (std) de 47. Es decir, la cantidad de dinero gastada, puede variar de la media 47 unidades.
📌La moda en gastos es “SNACK”, un gasto No Esencial, ocurriendo con una frecuencia casi diaria. La moda de la frecuencia es 1 día.
📌Existen otros gastos predominantes como “GAS” y “SUPER”, en donde se evaluó con qué frecuencia se realizan los gastos. Estos son considerados gastos esenciales.
📌Se realizó una gráfica de dispersión de los gastos, en donde podemos visualizar que diariamente los gastos casi nunca sobrepasan los 50 dólares.

Recomendaciones:
📌Disminución en ciertos gastos no esenciales.
📌Planificar a futuro los gastos esenciales, debido a que ya podemos identificar ciertas tendencias. Se puede establecer presupuestos dando límites a cada categoría.
📌Evaluar gastos vs ingresos.
