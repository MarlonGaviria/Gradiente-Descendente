El metodo de descenso por gradiente, "gradient descent" de ahora en adelante, es uno de los algoritmos de optimizacion mas populares en aprendizaje automatico, particularmente por su uso extensivo en el campo de las redes neuronales. Gradient descent es un metodo general de minimizacion para cualquier funcion $f$. A la version original se le considera lenta pero versatil.

Al algoritmo gradient descent se le conoce por varios nombres, sobretodo en la literatura en inglesa (vanilla gradient descent, batch gradient descent). A veces se les da el nombre de steepest descent, pero este termino es mas propio para aproximacion analatica de integrales. El algoritmo tambien tiene una version gemela bizarra que en lugar de buscar por un minimo busca el punto maximo de una funcion.

# Funcion a optimizar 
este metodo ofrece una  identificacion, en principio basica, de el minimo o maximo de una funcion en <img src="https://render.githubusercontent.com/render/math?math={ R }^{ n }">; Particularmente veamos el caso en <img src="https://render.githubusercontent.com/render/math?math={ R }^{ 2 }">.

En ocaciones es sencillo buscar m?nimos o maximos en una funcion <img src="https://render.githubusercontent.com/render/math?math=f(x)">; como el caso de la funcion concava <img src="https://render.githubusercontent.com/render/math?math={f(x)}= {x}^2">, como se ve en el siguiente grafico:

