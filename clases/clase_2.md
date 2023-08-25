## Varianza

$$
\sigma^{2} = \frac{(x_i - \bar{x})^{2}}{n}
$$

## Desviación

$$
\sigma = \sqrt{\sigma^{2}}
$$

## Coeficiente de variazacion

$$
cv = \frac{s}{\bar{x}} * 100%
$$

Si $s \rightarrow 0$; $cv = 0%$

Si el valor de $cv$ es $0%$ significa que los datos están muy juntos. Es decir, si la varianza $\sigma^{2}%¿$ es muy poca porque los datos se parecen mucho

Si $s \rightarrow \bar{x}$ implica que $cv = 100%$ lo que quiere decir que los datos están muy dispersos

La media es una medida muy estable con el pecado de no ser geometica

Todas las medidas están sopesadas al error estandar que está sujeto a la desvianción estandar

La varianza es un promedio de distancias que se buscan minimizar para algunas tecnicas estadisticas

## Covarianza

La covarianza sirve para comparar un par de variables, es la variación conjunta de 2 variables X y Y. Este es un coeficiente ($r$) que puede ser positivo o negativo

> Esta solo se puede usar entre 2 variables; para hacerlo con más variables se necesita de una matriz de covarianza

$$
\sigma_{x,y} = \frac{\sum{(x_i - \bar{x}) * (y_i - \bar{y})}}{n}
$$

Es mejor submuestrear que sobremuestrear,caso de los CV con más hombres que mujeres

Consideraciones importantes para redes: Una RN sobremuestreada está un poco menos estable que una submuestreada