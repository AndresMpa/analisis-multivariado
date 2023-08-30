# Modelo de regresion

Este se compone de 3 componentes

SCT -> Suma de cuadrados totales $\sum{(y_i - \bar{Y})^2}$

SCE -> Suma de cuadrados del error $\sum{(y_i - \hat{y})^2}$

SCR -> Suma de cuadrados de la regresion $\sum{(\hat{y} - \bar{Y})^2}$

SCT -> Total $SCR + SCE$

> La idea es minimizar el SCE
> SCR es la distancia de la regresion al eje cartesiano
> SCE la distancia del punto de error a la regresion

$$
r = 1 - \frac{SCE}{SCT}
$$

r -> Coeficiente de correlación

# Regresiones multiples

Con las regresiones multiples la corelación existente entre 2 variables puede ser muy alta, dado este caso se han de eliminar una de esas variables independedientes para que el modelo pueda funcionar

El analisis para este tipo de modelos se hace de manera bivariada, es decir; se analizan por 2 varbiables, X sub i con Y. Este modelo se ve así:

$$
y = \beta_0 + \beta_1 x_1 + \beta_2x_2 
$$

> En el ejemplo $x_1$ son las entregas y $x_2$ es el tiempo

El modelo general será:

$$
y = \beta_0 + \beta_1 x_1 + \beta_2x_2 + \beta_{k-1}x_{k-1} + \beta_kx_k
$$

Dicho lo anterior:

$$
r = 1 - (\frac{SCE}{SCR})
$$