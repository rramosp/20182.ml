# 2018/2 Machine Learning

## Contenidos

1. Mathematical optimization and symbolic computing
2. Linear Regression
3. Logistic Regression
4. Neural Networks
5. Regularization and performance evaluation
6. Kernel methods
7. Ensemble methods
8. Learning representations
9. Deep learning



## Calificación

40% Problemsets<br/>
30% Quizes<br/>
30% Data analytics project

## Reference MOOCs

- [EDX Machine Learning Fundamentals UCSanDiegoX: DSE220x](https://courses.edx.org/courses/course-v1:UCSanDiegoX+DS220x+1T2018/course/) 10 semanas
- [UDACITY Google Deep Learning Course](https://classroom.udacity.com/courses/ud730) 7 lecciones

## Máquina Virtual

Usaremos esta máquina virtual que tiene instalado un entorno Python Anaconda con Jupyter Notebooks disponibles en  [localhost:8008](http://localhost:8008) una vez que la máquina arranca.

**Observa la configuración de la máquina**

- Si tu máquina física tiene al menos 4GB de memoria configura la máquina virtual **con 2GB de memoria**
- Aunque casi no necesitarás un terminal, el interfaz de Jupyter Notebooks tiene un terminal para acceder a través del navegador. En cualquier caso, la máquina virtual tiene un servidor SSH en el puerto 2222 con user/user como usuario y pwd. Si tu máquina física es mac o linux usa `ssh -p 2222 user@localhost` para conectarte. Si es windows, usa [putty](https://www.putty.org/)
- Si compartes una carpeta entre la física y virtual asegúrate que **el nombre cone el que se comparte** sea `share` (aunque el nombre de la carpeta en la máquina física puede ser distinto)


## Data analytics project

Deberás de abordar un problema de analítica de datos, 1) elegir dataset, 2) definir tarea, 3) implementar la analítica de datos. El resultado ha de ser un notebook ejecutable que contenga, preprocesado (latent semantics y/o transformaciones), varios algoritmos de clasificación o regresión, análisis de rendimiento y curvas de aprendizaje.

Hay muchas fuentes de datos y sitios de competiciones de machine learning en internet, entre ellas: [kaggle](https://www.kaggle.com/competitions), [kdnudgets](http://www.kdnuggets.com/competitions/) 


#### Primera entrega

Un archivo PDF llamado **PROJECT_description.pdf** donde se describa brevemente (2 páginas máximo):

- el problema a abordar (p.ej. _los fallos en producción de una fábrica suponen un coste de tanto_)
- el dataset (p.ej. _datos de ventas + datos de sensores en máquinas de producción_)
- la tarea de machine learning (p.ej. _detectar anomalías en producción y medir su impacto en costes_)

#### Segunda entrega

Un archivo PDF llamado **PROJECT_final_report.pdf** donde se incluya un resumen del desarrollo del proyecto que incluya:

- descripción del preprocesado de datos.
- estrategias de generación de modelos predictivos.
- resúmen de resultados predictivos y su impacto en el problema abordado.

Una carpeta llamada **PROJECT_notebooks_and_data** donde se incluyan los notebooks y datos que realizaste para el desarrollo del proyecto, desde los cuales se puedan reproducir los resultados que expongas en el reporte final.

<font color="RED"><b>TUS RESULTADOS HAN DE SER REPRODUCIBLES, si no es así, LA ENTREGA NO SERÁ VÁLIDA</b></font> 


Criterios de evaluación: 

1. Claridad y precisión de la primera entrega.
2. Claridad y coherencia del reporte final.
3. Coherencia de la evidencia analítica generada (i.e. estabilidad de los resultados de predicción, corrección de los procesos de validación y selección de modelos, etc.).