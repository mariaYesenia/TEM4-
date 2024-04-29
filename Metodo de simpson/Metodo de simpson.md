# Metodo de Simpson 
La regla de Simpson es una de las fórmulas utilizadas para encontrar el valor aproximado de una integral definida. Una integral definida es una integral con límites superior e inferior. Por lo general, para evaluar una integral definida, primero integramos (usando las técnicas de integración) y luego usamos el teorema fundamental del cálculo para aplicar los límites.

La regla de Simpson se utiliza para encontrar el valor estimado de una integral definida (es decir, de la forma b ∫ₐ f(x) dx) aproximando el área bajo la gráfica de la función f(x). Mientras usamos la suma de Riemann, calculamos el área bajo una curva (una integral definida) dividiendo el área bajo la curva en rectángulos, mientras que cuando usamos la regla de Simpson, evaluamos el área bajo una curva dividiendo el área total en parábolas .

Hay 2 variaciones de la regla de Simpson llamadas  regla de Simpson 1/3 y regla de Simpson 3/8 que son las siguientes 

## Metodo simpson 1/3
La regla de 1/3 de Simpson es una extensión de la regla trapezoidal en la que el integrando se aproxima mediante un polinomio de segundo orden. La regla de Simpson se puede derivar de diversas formas utilizando el polinomio en diferencias divididas de Newton, el polinomio de Lagrange y el método de los coeficientes. La regla del 1/3 de Simpson se define por:
La regla de Simpson del 1/3 proporciona una aproximación más precisa. Estos son los pasos que explican cómo aplicar la regla de Simpson para aproximar la integral b ∫ₐ f(x) dx.


∫ a b f(x) dx = h/3 [(y 0  + y n ) + 4(y 1  + y 3  + y 5  + …. + y n-1 ) + 2(y 2  + y 4  + y 6  + ….. + y n-2 )]
Esta regla se conoce como regla del tercio de Simpson .

## Metodo de simpson 3/8
Otro método de integración numérica se llama "regla de los 3/8 de Simpson". Se basa completamente en la interpolación cúbica en lugar de la interpolación cuadrática. La regla de Simpson 3/8 o tres ocho viene dada por:

∫ a b f(x) dx = 3h/8 [(y 0  + y n ) + 3(y 1  + y 2  + y 4  + y 5  + …. + y n-1 ) + 2(y 3  + y 6  + y 9  + ….. + y n-3 )]

Esta regla es más precisa que el método estándar, ya que utiliza un valor funcional más. Para la regla de 3/8, también existe la regla de Simpson compuesta de 3/8, que es similar a la forma generalizada. La regla de los 3/8 se conoce como la segunda regla de integración de Simpson.

## Aplicacion de la regla de Simpson 1/3
*Paso 1:* Identifique los valores de 'a' y 'b' del intervalo [a, b] e identifique el valor de 'n', que es el número de subintervalos.

*Paso 2:* Utilice la fórmula h = (b - a)/n para calcular el ancho de cada subintervalo.

*Paso 3:* Divida el intervalo [a, b] en 'n' subintervalos [x 0 , x 1 ], [x 1 , x 2 ], [x 2 , x 3 ], ..., [x n-2 , x n-1 ], [x n-1 , x n ] usando el ancho del intervalo 'h'.

*Paso 4:* Sustituye todos estos valores en la fórmula de la regla de Simpson y simplifica.

