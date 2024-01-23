## Algoritmos heurísticos y metaheurísticos para problemas de carga de camiones
Se proporciona una jupyter notebook que contiene diversas implementaciones de técnicas heurísticas y metaheurísticas para resolver el CLP o container loading problem.
Este problema consiste en seleccionar la mejor disposición de pallets dentro de un contenedor, de forma que se pueda maximizar el volumen cargado cumpliendo una serie de restricciones. 

<img src="/figs/problema.png" alt="Texto Alternativo"  height="200">



En código se divide en hasta cuatro partes:

### Fuentes de datos usadas para la prueba e interfaz gráfica para la evaluación de los resultados.
Se implementa un algoritmo capaz de proporcionar una representacion gráfica de la disposición de los pallets dada. Un ejemplo es el siguiente:
<img src="/figs/interfaz.png" alt="Texto Alternativo" height="200">



## Implementación de las heurísticas para la resolución del problema.
Se implementan diversos algoritmos de optimización a mano, donde se encuentra GRASP, variantes genéticas o SA

## Ajuste de los parámetros para los algoritmos metaheurísticos y evaluación de los resultados.
Dados conjuntos de datos reales, proporcionados por [el grupo Renault](https://www.roadef.org/challenge/2022/en/) y combinados con datos de distribuciones gaussianas para incrementar el no determinismo, se estudian los resultados obtenidos tomando como métrica de referencia el porcentaje de llenado del contenedor

<img src="/figs/results.png" alt="Resultados" height="200">



En la carpeta `\docs` se incluye un pdf con resultados más detallados de la implementación y resultados