# CLase #5

Regresión lineal multiple con variable dicotomica

$$
\hat{y} = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + ... + \beta_p x_p
$$

| Variable |
| -------- |
| 1        |
| 0        |
| 0        |
| 0        |
| 1        |

Esto será dicotommicoen terminos de que 0 respresntará un "no" y 1 representará un "si".

$$
\hat{y} = 0,9305 + 0,3876 x_1 + 1,2627 x_2
$$

Donde $x_2$ es una variable dicotomica (0 o 1).

Pronosticar el valor para $\hat{y}$ si han pasado $10$ meses desde el último mantenimiento y es electrico

$$
\hat{y} = 0,9305 + 0,3876 (2,627) + 1,2627 x_2
$$

Siendo $x_2$ dicotomico se 

$R$ lineal significa en cuenta aumenta la variable dependiente

$R^2$ significa cuanto explica de lo que pase con Y


La relación entre $x_1$ y $x_2$ debe ser baja para evitar la colinealidad, es decir; evitar que las variables sean redundantes, ejemplo; la pariedad entre pesos y dolares