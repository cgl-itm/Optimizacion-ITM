# Optimizacion-ITM
Material para curso de Optimización en Ingeniería Electrónica y Telecomunicaciones del Instituto Tecnológico Metropolitano (ITM).

# Calendario
| Semana |                             Tema                              |                  Material practico |
| :-----------: | :--------------------------------------------------------------: |:----------------------------------------------------------------------------------------------------------------------------: | 
|      01       |  [**Introduccion al curso**](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/slides/00_Introduccion.pdf), [**Repaso Algebra Lineal**](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/slides/00_RepasoVectoresMatrices.pdf): Vectores, Norma, Producto Punto, Matrices, Valores Propios, Determinante.   |    [Taller 1 - Algebra Lineal](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/Talleres/1_Taller_Algebra_Lineal.pdf) [Numpy - Vectores](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/00_Matrices_Numpy.ipynb) [Numpy - Matrices](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/00_Vectores_Numpy.ipynb)         | 
|      02       |  **Definición de Problema de Optimización y Convexidad**: [Funcion objetivo, restricciones de igualdad y desigualdad. Minimo local y global](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/slides/01_FomulacionProblemas.pdf). [Definicion de Convexidad](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/slides/02_Convexidad.pdf). <br> **Optimización sin restricciones**: Primer Orden (Gradiente descendente)    | [Definicion Problema de Optimización](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/01_FomulacionMatematica.ipynb), <br> [Herramientas para calcular gradientes y Hessianas](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/02_Graficas_Calculos.ipynb),<br> [Sympy - Encontrar puntos estacionarios](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/03_SymPy_GradienteHessiana.ipynb), <br> [Metodo Directo - Gradiente descendente](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/04_MetodosDirectos_Gradientes.ipynb) |
|      03       |  **Optimización sin restricciones**: Segundo Orden, Newton. <br> Clase Taller. |      | 
|      04       |  [**Optimización con restricciones**](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/slides/04_OptConRestricciones.pdf): Multiplicadores de Lagrange y Condiciones KKT. <br> Examen   |  [YT - Intuition behind the Lagrangian](https://www.youtube.com/watch?v=GR4ff0dTLTw) <br> [Notebook - Optimizacion con restricciones KKT](https://github.com/cgl-itm/Optimizacion-ITM/blob/main/notebooks/06_OptConRestricciones_Lagrange.ipynb)   | 
|      05       |  Optimización con restricciones: Programacion Lineal - Simplex  y Punto Interior|      | 
|      06       |  Tecnicas NLP - Aproximacion a problemas sin restricciones  |      | 
|      07       |  Tecnicas NLP - Aproximacion a problemas simples con restricciones y Taller Tecnicas NLP |      | 
|      08       |  Examen LP y KKT. Programación Entera Mixta - MIP, MILP, MINLP  |      | 
|      09       | Clase Taller  MIP  |      | 
|      10       |  Examen Tecnicas NLP y MINLP. Optimizacion Heuristica  |      | 
|      11       |  Optimizacion Heuristica 2 - PSO |      | 
|      12       |  Optimizacion Heuristica 3 - Geneticos |      | 
|      13       |  Surrogate Optimization |      | 
|      14       |  Aprendizaje Automático en Optimización |      | 

# Libros
* [Numerical Optimization - J. Nocedal & S.J. Writght](https://link.springer.com/content/pdf/10.1007/978-0-387-40065-5.pdf)
* [Introduction to Optimization - E.K.P. Chong and S.H. Zak](https://github.com/benjamincrom/optimization/blob/master/An%20Introduction%20to%20Optimization-%20E.%20Chong%2C%20S.%20Zak.pdf)
* [Optimizacion Convexa - Alejandro Garces](https://repositorio.utp.edu.co/bitstreams/4c8af0a3-0988-450c-9618-0bb9d8a04a27/download)
* [Convex Optimization - Boyd](https://web.stanford.edu/~boyd/cvxbook/)
* [Formulacion y Resolucion de problema de Programacion Matematica - Antonio Conejo](https://eco.mdp.edu.ar/cendocu/repositorio/00216.pdf)
* [Linear Programming and Algorithms for Communication Networks](http://ndl.ethernet.edu.et/bitstream/123456789/33961/1/5.pdf.pdf)
* [MO-BOOK: Hands-On Mathematical Optimization with AMPL in Python](https://ampl.com/mo-book/index.html)

# Librerias de Optimizacion en Python
* [Modeling and Solving Optimization Problems - Keivan Tafakkori](https://www.supplychaindataanalytics.com/modeling-and-solving-optimization-problems-in-python/)
* [Bayesian Optimizacion - Python](https://github.com/bayesian-optimization/BayesianOptimization/tree/master)

## Programas Lineales
* Nelson Uhan - [Notebook](https://github.com/nelsonuhan/simplex)

## Programacion Entera Mixta (MIP)
* [Scipy MIP](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.milp.html)
* [MIP Python](https://python-mip.readthedocs.io/en/latest/examples.html)
* [PuLP](https://coin-or.github.io/pulp/CaseStudies/index.html)

## Algoritmos Metaheuristicos
* [pyMetaheuristic](https://github.com/Valdecy/pyMetaheuristic)
* [mealPy](https://github.com/thieu1995/mealpy)
* [EvoloPy](https://github.com/7ossam81/EvoloPy)
* [MetaHeuristic.jl - Julia](https://github.com/jmejia8/Metaheuristics.jl)
* [Ejemplo Genetic Car](https://rednuht.org/genetic_cars_2/)
  
# Cursos similares
* [Mathematical Optimization - Stanford](https://web.stanford.edu/group/sisl/k12/optimization/#!index.md) 
* [Machine Learning Refined - Optimization animations](https://github.com/jermwatt/machine_learning_refined) 
* [Optim - Repositorio con material en Optimizacion](https://github.com/MerkulovDaniil/optim/tree/master)
* [Solmaz - Mathematical Optimization](https://solmaz.eng.uci.edu/Teaching/mae206.html)
* [Optimization for ML](https://www.lamsade.dauphine.fr/%7Ecroyer/teachOID.html)

# Telecommunications
## Least Squares 
* [Coherent Detection of Turbo-Coded OFDM Signals Transmitted Through Frequency Selective Rayleigh Fading Channels with Receiver Diversity and Increased Throughput](https://link.springer.com/article/10.1007/s11277-015-2303-8)
* [Least Squares Channel Estimation of an OFDM Massive MIMO System for 5G Wireless Communications](https://link.springer.com/chapter/10.1007/978-3-030-21009-0_43)
* [Adaptive least squares channel estimation for visible light communications based on tap detection](https://www.sciencedirect.com/science/article/pii/S0030401820302534)
  
## Antenna Design
* [Optimization Methods in Antenna Engineering
](https://link.springer.com/referenceworkentry/10.1007/978-981-4560-44-3_15)
* [Optimization Strategies for Efficient Antenna Design](https://link.springer.com/chapter/10.1007/978-3-030-51260-6_18)

## Several Examples
* [Optimization for the Telecommunications Industry -  Gurobi](https://www.gurobi.com/industry/optimization-for-the-telecommunications-industry/)
* [Cell tower optimization problem - Gurobi](https://www.gurobi.com/jupyter_models/cell-tower-coverage-problem/)
* [Examples using AMPL and StreamLit](https://amplopt.streamlit.app/)

# Notebooks
## Gradiente
* [Steepest Descent](https://github.com/mkozturk/notebooks/blob/master/Rosenbrock%2C%20steepest%20descent.ipynb)
* [Newton's Method](https://github.com/mkozturk/notebooks/blob/master/Rosenbrock%2C%20Newton's%20method.ipynb) 
* [Quasi-Newton Method](https://github.com/mkozturk/notebooks/blob/master/Rosenbrock%2C%20quasi-Newton%20methods.ipynb) 
* [Optimization in Deep Learning](https://artemoppermann.com/optimization-in-deep-learning-adagrad-rmsprop-adam/)
* [Overview of different optimizers for neural networks](https://medium.datadriveninvestor.com/overview-of-different-optimizers-for-neural-networks-e0ed119440c3)
# Links
* [Awesome Optimization](https://github.com/ebrahimpichka/awesome-optimization?tab=readme-ov-file#video-lectures-and-courses)
