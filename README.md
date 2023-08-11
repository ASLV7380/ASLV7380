31. En un determinado casino hay un juego de azar que consiste en tirar dos dados y sumar los números de las caras superiores. Observe que las sumas de las caras pueden ser de un mínimo de 2 y de un máximo de 12. Cada número que surge de estas sumas en un lanzamiento tiene asociado una Ganancia o pérdida. La fórmula que se utiliza para determinar la ganancia o pérdida dado que se obtuvo el número “k” en un lanzamiento es: Premio = 50 « (|7 — k| — 2) Lempiras, donde k = 2.3,4,...,12. Observe que el premio puede ser positivo (cuando k = 2,3,4.10, 11,12) o puede ser negativo (cuando k = 6,7,8); cuando el premio es positivo significa que el jugador gana la cantidad que dice la fórmula y cuando es negativo significa que el jugador pierde la cantidad que dice la fóxmula. Un jugador empedernido a juegos de azar quiere realizar un experimento para determinar si el juego es justo o a la larga el jugador siempre lleva las de perder. El jugador se propone jugar durante 30 días consecutivos realizando 10 lanzamientos por día y ver si al final acumuló ganancia o pérdida. El jugador quiere hacer una simulación de dicho experimento antes de arriesgarse a perder dinero jugando de verdad. Elabore un programa que simule el experimento; para ello haga lo siguiente: 

e Construir un arreglo de enteros bidimensional de tamaño 30x10 con nombre E que corresponde a los resultados obtenidos de los 10 lanzamientos de los dados por día, durante los 30 días. Para simular los resultados de los lanzamientos, se generan dos número aleatorios que oscilan entre 1 y 6, por tanto los elementos de £ es la suma de estos dos números aleatorios. 

e Imprimir el arreglo £ de forma tabulada por filas y columnas. 

5 

e A partir de la matriz £ determine la ganancia o pérdida acumulada al final de los 30 días. Usar la fórmula “Premio” para calcular los premios por cada resultado de los lanzamientos registrados en L y acumularlos. Fórmula: Premio = 50 + (|7 — k| — 2) Lempiras, donde “A” es el resultado del lanzamiento. 

e Construya un arreglo unidimensional con nombre FR de tamaño 11 cuyos elementos son las frecuencias de cada uno de los resultados registrados en £, es decir, el primer elemento de FR es el número de veces que se obtuvo el resultado 2 hasta el, el segundo elemento es el número de veces que se obtuvo el resultado 3, y asi sucesivamente. 

e Imprimir de forma tabulada los resultados (2. 3.4.... 12) y su respetiva frecuencia. 

e Ordenar e imprimir el arreglo FR de menor a mayor. 

