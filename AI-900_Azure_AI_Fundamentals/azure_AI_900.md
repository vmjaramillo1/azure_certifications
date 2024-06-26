# azure_certifications

Proyecto correspondiente a información para lograr la certificacion de Azure AI 900

[Preguntas PREPARATORIAS](https://www.examtopics.com/exams/microsoft/ai-900/)

[Notaciones y concejos para la preparacion del examen](https://ifgeekthen.nttdata.com/es/guia-para-preparar-el-examen-ai-900)

[aspectos basicos y guia de extamen](https://learn.microsoft.com/es-es/certifications/resources/study-guides/AI-900)

[Sumario online de microsoft para preparacion de examen](https://learn.microsoft.com/es-es/certifications/exams/ai-900/#two-ways-to-prepare)

[Examenes de prueba](https://www.youtube.com/watch?v=8XhQcAgdxXI&list=PLGnDOd349NCNxtsQpeWtIyD7lY1IrYw-n&index=7)



VIDEO CURSOS
- [Video curso preparatorio - COMPLETO (varias clases)](https://www.youtube.com/watch?v=6DQvItqEKfI&list=PL3hNLk-aR0J97QHh7uZfafnUxIdQS5nSD&index=5)
- Videos largos
	- [Clase 1](https://www.youtube.com/watch?v=LLpgGnGi-7U)
	- [Clase 2](https://www.youtube.com/watch?v=JLwojTS26Uc)
	- [Final](https://www.youtube.com/watch?v=Dmf8lY7ThZQ)
 - Repaso antes del examen 1 - 5
	- [Clase 1](https://www.youtube.com/watch?v=fAFUTwz8cxM&list=PL7oUSQgo7Mcvf5nMG1GeTqhdsY84kkD72&index=16)

### Temario

1. [Introduccion a la inteligencia artificial](#into)
2. [Fundamentos de Machine learning](#machineLearning)
3. Exploracion de la vision informatica
4. Exploracion del procesamiento de lenguaje natural
5. Exploracion de la ayuda para la toma de decisiones
6. Exploracion de la mineria de conocimientos

## 1 Introduccion a la inteligencia artificial <a name="into"></a>

[Recurso](https://learn.microsoft.com/es-es/training/paths/get-started-with-artificial-intelligence-on-azure/)


### ¿Qué es la inteligencia artificial?

Es la creacion de software que imita el comportamienot y capacidades humanas

Cargas de trabajo:

- **Aprendizaje automatico:** Base del sistema de IA, es la forma de enseñar a un modelo a predecir y obtener concluciones de los datos
- **Deteccion de anomalias:** detectar errores o actividades inusuales
- **Vision informatica:**: (vision por computador) capacidad del software de interpresar el mundo por camaras, video e imagenes.
- **Prosesamiento de lenguaje natural**: (PLN) capacidad para intepresar lenguaje escrito o hablado y responder
- **Mineria de conocimiento**: Capacidad para extraer informacion **util** de grandes volumenes de datos (no exrtucturados) para crear almacen de **conocimiento**

### Aprendizaje automatico

Es la base de la mayoria de las solciones de IA

Permite que las maquinas aprenda mediante el analisis de grandes cantidades de datos

Estos datos se generan todos lods dias mediante nuestras interaciones (dispositivos, mensajes, fotos, redes sociales, ETC)

El ciclo para el ML es el siguiente

1. Se obtienen los datos
2. Se etiquetan los datos
3. Se entrenas modelos con los datos para resolver un tarea
4. Se empasula el resultado en un modelo (h5 x ejemplo)
5. Se crean sistemas q utilizan el modelo

**Aprendizaje automatico en azure**

Azure posee **Azure Machine Learning** q es una plataforma basada en nube para crear, gestionar y publicar modelos de ML. 

Sus funcionalidades son: 


|Caracteristica|Funcionalidad|
|--------------|-------------|
| ML automatizado| permite crear modelos de ML a no expertos (rapido y efectivo a partir de datos)|
| Diseñador de Azure Machine Learning | Interfaz grafica para desarrollar soluciones de AP sin codificar |
| Administracion de datos y procesos | Almacen de datos y recursos de computa para ejecutar experimento de datos a escala (compu laboratorio) |
| Canalizadores (Pipe)| Son Pipes para crear tareas de entrenamiento, implementacion o adminostracion de modelos |

### Deteccion de anomaias

Es una tecnica basada en el aprendizaje atumatco que analiza los datos en el tiempo he identifica fluctuaciones o cambios inusuales

**Deteccion de anomalias en Azure**

Dentro de Azure exite el servicio de deteccion de anomalias mediante la diponibilizacion de una API

### Vision por computador (vision informatica)

Es un area de la IA q se encarga del procesamiento de imagenes para resolver siferntes problemas tales como

|Tarea|Descripcion|
|-----|-----------|
|Clasificacion de imagenes| Se encaga de identificr y clasificar objetos provenienes de imagenes o videos, etiquetando (nombrando) segun la clase a la q pertencen|
|Deteccion de objetos (identificacion)| Se encarga de identificar lso diferntes objetos en una imagen segun lo q son (aqui se trabaja con multiples identificaciones)|
|Segmentacion semantica| meditne mapas de segmentacion se identifica(clasifica) los pixles corrspondiente a un objeto, (clasificacion de pixeles) permitiendo deliminar diferentes objetos dentro de una imagen|
|Analisis de imagenes| consite en obtener una decripcion detalla de la imagen a partir de la infomacion obetenia (etiquetas) de las mismas (es como describir la imagen)|
|Detección, análisis y reconocimiento de caras| Consiste en identificar y nalalizar rostros de las personas con la finalidad de reonocer infivuos a partir de sus rasgos faciales|
|Reconocimiento óptico de caracteres (OCR)| Basicamente extraer caracteristicas de una imgen para recuperar el texto|

**Vision por computador en Azure**

En azure se ofrece los siguientes servicios:

- *Vision de Azure IA:* Sistema para analisar imagenes o video y extraer etiquetas, descripciones, texto y objetos
- *Azure IA custom Vision:* Servicio para entrenar tus propios modelos de analisis de imagenes y deteccion de objetos (con tus propias imagenes)
- *Azure IA Fase:* Deteccion de caras y personas
- *Inteligencia de documentos de azure IA:* Basicamente es un OCR

## Procesmaiento de lenguaje Natural (PLN)

Area de la IA encargada de analizar el lenguaje tanto hablado como escrito entenderlo dar dignificado y actuar en consecencia.

Las tareas de esta area destacan: 

- Analizar he interpretar texto
- Interpretar lenguaje hablado y responder en concecuencia
- Traducion automatica de fraces habladas o escritas
- Interpretacion de comandos y terminacion de acciones apropiadas

**Servicios de Azure con PLN**

- *Lenguaje de Azure:* Servicio para comporende y analizar texto, entrenar modeos para comprender comandos hablados o escritos y actuar en conecuencia
- *Traducto de Azure IA:* Traductor de texto a mas de 60 idiomas
- *Voz de Azure:* reconocer, sintetizar y traducir mensaje de voz
- *Bot de Azure:* brinda acceso a una plataforma de IA conversacional, para gestionar un "agente"convercinal (te da back para generar un bot) y este actue en consecuencia (se conecta a canel web)

## Mineria del conocimiento

Describe el area de la IA que se encarga de la extraccion de informacion de grandes volumenes de datos no estructurados para crear un **almacen de conocimiento indexado** (como un indice en un libro para bucar cosas)

**Minieria de concimiento en Azure**

- *Azure cognitive search:* servicio que permite crear indices de conocimiento (estos se pueden usar internamiente o en busquedas de recursos en internet y de acceso publico)

**Nota:** est servicio hace uso de los demas servicios de azure para obtener informacion de documentos y mejorar las busquedas como antes no era posible (utiliza vision por computatos, PLN, anomalias, etc)


## Desafios y riesgos de la IA

|Desafio|descripcion|
|-------|-----------|
|Segos en el entrenamiento|Entrenar con datos segados puede causar aplicaciones con resultados segados, engañosos, poco fiables y hasta equivocados|
|Errores que causan daños| si un modelo que forma parte de un sitema critico o medico falla puede causar daños no solo fiscos si no tamb a la salud de los pasientes|
|Filtracion de dados| los modelos tienen problema para saber q informacion es sencible o prohibida y podrian terminar filtrando datos sencibles de una empresa o persona|
|Quien es el resposable de las decisiones| En caso que los modelos fallen y causen daños a una persona o la muerte de alguien, quien es el responsable?|
|Las soluciones no funcionan para todos| Relacionado con el sesgo del punto un, puede ser q un modelo no funcione para todos los usuarios, siendo una solucion no solo incompleta si no tamb causar daños a las personas si es un sistema critico como un sitema para invidentes|
|Hacer que las personas confien en la IA| Si un sistema de IA toma deciciones criticas como es q lo hacen ?|


## Inteligencia Artifical responsable

Principios de una IA desponsable de Azure:

![Captura de pantalla 2023-09-25 221859](https://github.com/vmjaramillo1/azure_certifications/assets/6383659/59cf5e57-45fb-4424-86a8-f5c5b395700e)

### 1. Imparcialidad

- Tratar a todos de manera equitativa, sin segos, ni discriminacion alguna.
- Sin dar ventaja o desventaja injusta a nadie
- En una sociddad injusta, los sistemas deben reducir la injusticia
- La IA pued ser mal utilizada en crimenes, denigracion cultural, afianzar estereoritpos, etc, **eso se debe evitar**
- Evitar y afrontar la *sobre representacion* y la *infra representacion*


La imparcialdiad no es un problema de un sistema, **ES UN PROBLEMA SOCIAL** y un desafio **SOCIO TECNICO**

**Azure Machine Learning** brinda la capacidad de interpretar modelos y medirlos pasa saber cmo influye cada caracteristica de los datos en el modelo para mitigar dispariedades y sesgos

### 2. Confiabilidad y seguridad

Los modelos y el software (en general) debe ser seguro -> en especial si se aplican en entornos criticos como hoptales o coches autonomos

Deben ser testeados para ser seguros y confiables -> asi no causen daño en el mundo (autos q atropellan personas)

Los pequeños errores se acumlan y mas si afectan a conjuntos grandes de usuarios

### 3. Privacidad y seguidad

Sistemas de IA deben ser seguros y respetar privacidad de datos

El problema radica q los modelos se entrenan con grandes cantidades de datos (en los q puede haber informacion privada)

Esto puede causar riegos de dibulgacion de informacion

Se debe tener cuidado con los datos usados y evitar poner en riesgo la privacidad o dibulgacion de datos

### 4. Inclucion

Modelos q incluiyan a todos, sin discriinar por ningun aspecto
(ya sea dicapacidad, cultura, credo, religion, color de piel, genero, etc)

Respetar a las comunidades sin ignorar miorias

**EXPERIENCIAS DE IA PARA TODOS**

### 5. Transparencia

Los usuarios deben saber el proposito, funcionamiento y limites del sistema

Asi se genera confianza de los usuarios

### 6. Resonsabilidad

Debemos ser responsables de las soluciones de IA

Garantizar que la IA sea etica y legal

Tener resposansabilidad en cada fase del desarrollo

**DEBEMOS SER RESPONSABLES DE COMO LA IA IMPACTA LA MUNDO**


## 2 Fundamentos de Machine learning <a name="machineLearning"></a>

[Recurso](https://learn.microsoft.com/es-es/training/modules/fundamentals-machine-learning/)


### Introduccion 

El objetivo es usar datos para crear modelos predictivos q se puedan incorporar en aplicacion

El ML (Machine learning) es la union de 2 diciplinas:

- ***Ciencia de datos:*** Explora el modelo, prepara los datos u entrena el modelo

- ***Ingenieria de software:*** Incorpora el modelo en una aplicacion para q sea usado


### Que es el aprendizaje automatico ?

- Se origina de la estadistica y los modelos matematicos
- Objetivo -> usar datos hitoricos para **predecir valores o resultados** 


un modelo de apredizaje automatico -> es un funcion

- f(x)=y

donde datos los valores de X (x es la **obervacion**)

Las observaciones tiene una/varias caracteristicas

x lo tanto X -> es un vector de caracteristias ejm

obsevacion persona= [peso, edad, genero, etc]
El atributo que se queire descrubir de la observacion se llama **etiqueta**


Un modelo de Apredizaje automatico => funcion que toma entradas y produce salidas (la salida es la etiqueta obtenidapor **inferncia** q Es obtener concluciones a partir de premisas)

Entrenar -> proceso de definir o descubrir la f(x) o funcion adecuada q nos obtenga el el resultado o valor *y* buscado

![image](https://github.com/vmjaramillo1/azure_certifications/assets/6383659/4507331c-fdc9-4f9d-ab0a-5fed836f3414)



El modelo es la **encapsulacion de la funcion** f(x) que dada una observacion (conjunto de atributos) nos permite caluclar la etiqueta (valor a descubir) obtenido por inferencia

## Tipos de aprendizaje automatico



![image](https://github.com/vmjaramillo1/azure_certifications/assets/6383659/75e17f43-88b5-4622-af1b-f341233cd49e)

Se debe usar el mejor modelo para cada ocacion:

**Aprendizaje Supervisado**: En los datos de entrenamiento se incluye la variable a predecir

- **Regresion:** El valor predicho es numerico
- **Clasificacion:** El valor a predecir es una categria o clase (y poe lo regular suelen ser mutuamente expluyentes):
	- **Binaria:** determina si el elemento observado pertenece o no a una clase
	- **Multiclase:** predice la etiqueta que representa a una observacion de entre varias clase

**Aprendizaje no supervizado**: En los datos de entrenamiento no constan los calores a predecir (etiqueta)

Se intent descubir patrones para determinar conjuntos/grupos

Los grupos se determinan por la relacion entre las caracteristicas de las observacines

- **Agrupacion de closters**: Es la mas comun, agrupa observacines egun caracteristicas

## Regresion

Se entrenan para predecir etiquetas numericas,basandoe en datos de entrenamiento (hitoricos) que poseen caracteristics y las etiquetas correspondientes

El proceso de entrenamiento de este (y de todos) los modelos es el siguiente:

1. Recopilar datos y dividilos en Train-Test
2. Usar los datos para entrenar el modelo
3. Usar los datos de test para validar el modelos y su resultado (se efectuan prediciones sobre los datos de test)
4. Se comparan resultados, obtienen metricas y en caso de ser necesario ajuste los parametros del modelo y repita el procesos


### Metricas de evaluacion

**Error medio absoluto (MAE) (Mean absolute Error)**
Indica la varianza entre valores predichos y reales, (sin importar si ka varianza es positiva +, o negativa -, se concidera el absoluto y se calcula el valor promedio)

Ejm  Valor predicho 3; valor real 4 -> varianza 1

NOTA: esta metrica valora de igual forma si las fallas son grandes o pequeñas, pues al sacar un promedio podria darse:

- Error 1 -> 0
- Error 2 -> 10
- MAE -> 5

Con esta metrica esperamos tener modelos que se equivoquen poco, pero podria darse que el error cuando se de sea mas grande

**Error cuadrado medio (MSE) (Mean square Error)**

Esta opcion soluciona el problema del MAE, buscando que el modelo se equivo sistematicamente pero por muy poco, en lugar de tener solo algunos errores pero muy grandes.

Esto se logra ampliciando los errores grandes,elevando al cuadrado los valores para sean mas notorios


Ejm  

valores de error: 1,2,3

valor MSE: (1,4,9) => 4.6


Nota: con esta metrica se tiene en cuenta la magnitud de los errores, pero ya no se cuenta con informacion de la precion del modelo, es decir 

si yo quiero predecir helados vendidos, cuantos helados + o - estoy predicneod mal? 

el MSE solo mide la magintud de los errores

**Raiz del error cuadrado medio (RMSE) (Root mean square error)**

Esta metrica solventa el error del MSE, al ejecutar la raiz a la operacion podemos saber la preccion del modelos en terminos de datos predichos, siendo asi q:


el RMSE permite medir en terminos de la observacion cual es el error

Ejem MSE => 4.6

RMSE => 2.1


Si fueran helados diriamos q la predicion de venta tiene un error de 2.1 helados + o - 

**Coeficiente de determinacion**

En lo valores reales siempre existira cierta variacion aleatoria, el medir que tan bien el modelo se adapta a esta variacion se realiza con esta metrica, los valres van de 0 a 1, siento 1 que los valores se adaptan a la perfecion

Es decir mientras mas cercano a 1 mejor se adapta a los datos de validacion.

## Clasificacion binaria

Es una tecnica de el aprendisaje supervizado

Se calucula la probabilidad de una obsercacion de pertenecer a una clase (matematicamente exclueyente - una de dos etiquetas)

La probabilidad se mide en un valor de entre 0 - 1, para la etiqueta verdadera - falsa

Matematicamente es:

```
F(x) = P(y=1|x)
```

Probabilidad q y=1 dado x (para asumir q pertence o no a una categria se establece un **humbral de clasificacion**)

### Metricas

Por lo regular se utiliza la matriz de confcion para sacar la siguientes metricas


IMAGEN

- Verdaderos negativoco
- Verdaderos positivos
- Falsos negativos
- Falsos positivos

**Exactitud (Accurracy)**

Indica el porcentaje de acierto de las prediciones correctas (TN,TP) frente al total de las prediciones

Es util con clases valanceadas

**Eje:** Seria como decir q tan confiable es la predicion de un viejito(80% de acieto ya sea para bien o para mal)

Esta metrica no es util con **clases desvalanceadas**


**Precision (presition)**


De todos los predichos como positivos, cuantos realmente son positivos

```
TP / TP + FP
```

Util cuando el costo de los **falsos posticitivos es alto**

**ejem**

En medicina cuando un falso positivo puede llevar a conllvar un tratamiento peligroso como la detecion del canses y aplicar quimio

**Recuperacion (Recall)**

Indica de todos los TP cuantos fueron recuperados (De los positivos cuanto fueron correctamente clasificados como positivos)

Problema no conciera **como se se clasifican los negativos**, es decir si clasifica un falso como positivo esto no importaria

Ejm: si un modelo clasifica **todo** como positivo, el recall seria de 100% -> **ESTO ESTA MAL**

```
TP / TP+FN
```

**Cuando usar?** Cuando el costo de detectar falsos como postivos es poco y solo intereza recuerar todos los postivios

Ejem: Detectar todos los autos de una imagen


**Puntuacion F1 (F1 Score):**


Es una metrica q combina la precion y el recall para dar valance entre los dos

**Util cuando los datos estan devalanceados**, valore de 0-1

1 indica valor alto de precition y recall
0 indica valores bajos y pobre rendimienot del modelo

**ROC o area bajo la curva**

Consta de dibujar un grafico para identivicar q tan bien predice el modelos ciendo asi q una curba alta y supere la lina diagonal( identifica la aleatoriaedad de predicion 50%) sera un modelos con un rendimineto por lo menos medianamente bueno.



## Clasificacion multiclase

Determna a que clase pertenece la obcervacion -> una de varias etiquetas posibles

Se termina la clase mas probable

Para el entrenamiento es necesario ajustar los datos, exiten 2 enfoques:

**Algoritmo uno frente a todos (OvR):** 
 1. Se entrena una funcion de clasificacion binaria para cada clase
 2. Se calcula la probabilidad de la observacion para cada clase
 3. Se tima la probabilidad mas alta

 ```
 f0(x) = P(y=0|x)
 f1(x) = P(y=1|x)
 f2(x) = P(y=2|x)
 ```

**Algoritmo Multinomial**

Enfoque alterno
1. Se entrena una unica funcion (de salida multivalor)
2. La salida es un vector con la probabilidad de cada clase, -> la suma debe dar 1 Ejm [0.2 ; 0.3 ; 0.5]
3. Se toma la probabilidad mas alta
```
F(x) = [ P(y=1|x) ; P(y=1|x) ; P(y=2|x) ]
```

### Metricas

Se usan las mismas q la clasificacion binaria (Matriz de conficion)

## Agrupacion de Clusters

Aprendizaje no supervisado -> las observaciones se agrupan en clusters segun sus caracteristicas -> el cluster al q sin asignados es su etiqueta

exiten varios algoritmo de clusters Ejem K-menas


## Metricas

La evaluacion se basa en el analisis de clos clusters, como la separacion de los cluster, distacia media de los elementos, etc


- **Distancia media al centro del cluster**: proximidad media de cada elemento al centroide del cluster
- **Distancia media a otro centro** Distancia media entre cada punto de cluster y el centroide de todos los demas cluster
- **Distancia maxima al centro del cluster** distacia mas lejana de un punto al centrodide del cluster
- **Silueta** valor entre 1 y -1 q define cuan alejados estan los puntos de un cluster con relacion a otro (mejor si es mas cercano a 1)


## Deep learning (aprendisaje profundo)


Aprendizaje supervisado que emula la forma en la q el cerebro aprende

se basa en las neuronas atificiales -> una funcion matematica simple -> compuesta de parametro de entreda X, pesos (W), funcion de activacion y salida Y

Una neurona sola no es util -> la union de muchas (cientos o miles) -> permite modelar conocimiento comple

las neuronas de agrupan en capas y las capas se apilan una detras de otras -> a mas capas mas profunda la red (**X eso el nombre de Aprendizaje profundo**)-> mas complejo el conocimiento que modela

Las desde neuronales son las union de funciones simples (neuronas) para formar una funcion anidada sumamente compleja

una red neuronal puede resolver muchos tipos de probleas -> regresion, clasificacion, PLN, vision por computador, Etc


para eso de debe pueden aplicar distintas arquitecturas, neuronas y funciones de activacion

Funcion de activacion es una funcion que determina si la neurona de activa o no dependiendo del umblal definido segun a funcion, si la neurona de activa su valor pasas a la siginete capa, si no se activa su valor no pasa

Esta interconecin neuronal se llama redes neuronales completamente conectadas

Algunas funciones de activacion para la ultima capa de las redes son:

- **Regression** - Linear Activation Function
- **Binary Classification** —Sigmoid/Logistic Activation Function
- **Multiclass Classification** —Softmax
- **Multilabel Classification** —Sigmoid

Redes neuronales profundas ==> DNN

### Entrenamiento

Se aplica de fomra iterativa en EPOCAS

En cada ciclo se ajustan los pesos (W) para minimizar el valor de error o perdida general de la red

Los valores (w) cambian segun una funcion de optimizacion que indica si el valos de W debe subir o bajar para mejorar el valor de perdida

La funcion de obtimizacion se llama: Desenzo del gradiente esticatico -> existen varias variables de esta

El modelo entrenado son los pesos (w) de la red que permiten obtener la mejor predicion, obteniendo el menor error posible y con los mejores resultados aceptables




**NOTA**:  los datos de entrenamiento se procesan por lotes en matrices y se procesan mediante cálculos algebraicos lineales. NO SE PASAN DE UNO EN UNO


Dentro de una función de pérdidas en Deep Learning, las más comunes son:

**Problemas de regresión:**
- Mean Squared Error
- Mean Absolute Error

**Problemas de clasificación:**
- Binary Cross-Entropy
- Categorical Cross-Entropy

## Azure Machine Learning

Servicio en nube de Azure para entrenar, implementar, evaluar y administrar modelos de ML (Todo el ciclo de inicio a fin)

incluye: 
- Explorar y preparar datos
- Entrenar y evaluar modelos
- registrar y administrar modelos
- implementacion de modelos (x apps o servicios)
- revision demo modelos (monitoreo)

Caracteristia del servicio de Azure ML

1. Almacen centralizado de datos (train/test)
2. Gestion de recusos bajo demanda
3. AutoML  -> para entrenar modelos de forma automatica
4. Integracion con framewokrs de desarrollo de ML (MLFlow)
5. Herramientas para gestionar entrenamientos
6. Facilita la visualizacion de metricas

Al usuario se le disponibiliza 

1. Area de trabajo de Azure ML -> para crear el entorno definir recursos y demas
2. Estudio de azure de ML -> Web donde se controla todo a nivel operativo


## Auto ML

Permite entrenar multiples modelos para evaluar y comparar cual seria el mejor para los datos

disponbile dentro **Microsoft Azure Machine Learning Studio**

ahi se debe crear un recurso

La forma de comparar al mejor modelo es un indicador o por early stoping

se utilizaon las siguientes metricas:

NRMSE: raiz del error cuadrado medio normalizado, util para comparar modelos de diferentes escalas

Concepto de valores residuales: diferencia entre valor previsto y real

Histograma de valores residuales: -> frecuencia de intervalo de valores residuales -> se quiere que esten acumulados en torno a 0 -> para minimzar errores grandes (extremos)

![image](https://github.com/vmjaramillo1/azure_certifications/assets/6383659/167232ba-750f-4def-a250-3e0e96fc0dd5)


Valores previstos frente a reales: tendencia diagonal que correlaciona entre valores previstos (puntos) y valores reales(linea) mientras mas serca mejor rendimiento del modelo

![image](https://github.com/vmjaramillo1/azure_certifications/assets/6383659/f23ffb26-8639-4e41-bd50-24c511779945)

## 3 Azure Open IA

- Asociacion entre Azure y Open IA
- Ofrecen un servicio combinado en Azure

**Azure ofrece:**
- Infraestructura
- Implementacion de modelos Open IA en productos Microsoft
- Potencia cargas de trabajo

**Open IA ofrece:**
- Sus modelos para ser utilizados


**Azure Open IA consta de:**
1. Modelos Ia Pre-Entrenados
2. Fine tunning de modelos
3. Herramientas para evitar el mal uso de la IA
4. Seguridad empresarial


**IA generativas** -> genera contenido en base  una entrada

Cargas de trabajo soportadas en Azure Open IA:

- Generacion de PLN 
	- Genera y detia texto
	- Busca clasifica y compara texto
- Generacion de codigo
	- Genera edita y explica codigo
- Genera imagenes
	- Genera y edita imagenes


**DOS OPCIONES DE IA EN AZURE**

- Azure IA -> Para casos genericos
- Azure Open IA -> Para casos especificos

## Funcionalidades de PLN de Open IA

<<<<<<< HEAD
Los modelos entrenan con tokens (segmentos de palabras) asignado a vectores

GPR -> Generate pre-trainet tranformer ->**exelentes para PLN**

- Resumen texto
- Clasifican texto
- Generan nombre o frases
- Traduccion
- Responer preguntas
- Sugerir contenido


**Generadores de Codigo -> modelo CODEX**  

Entrenan con codigo -> ademas de lenguaje natural

**Copilot** Maximo esponenete de funcionalidad integrada en IDE

**Generadores de imagenes -> DALLE**

Genera imagenes basado en una descriocion de la imagen -> PRONT

## IA services

Permite contruir aplicaciones -> Implementa:

- Reconocimineto de imagenes
- PLN
- Lenguaje hablado
- Busquedas
- etc

Esta basdo en -> 3 Principios:

1. **Pre diseñado y listo para usar:** 
   1. Soluciona problema de recursos para entrenar (costos, datos, infraestructura, etc)
   2. Disponible para empresas de todo tamaño (modelos pre entrenado)
   3. Permite Fine Tuning para casos especificos
2. **Acceso basado en API**
   1. Adaptable a diferentes entornos de desarrollo
   2. REST API, librerias, APP de logica (Power Automate)
3. **Disponible en azure**
   1. Perimite q se use la mejor opcion segun el caso: 
      1. Paas -> Plataform as a service
      2. IaaS -> Infraestructure as a service
=======
Entrenamiento de modelos por tokens -> asignados  vectores

GPT -> generative pre-trainet tranformer 

Tareas:
 - Resumen de Texto
 - Clasificacion de texto
 - Generacio de nombres o frases
 - Traduccion
 - Responder preguntas
 - Sugerir contenido

## Generacion de codigo de Open IA

Entrenado con codigo y lenguaje natural

**Copilot** como modelo de codigo -> Open IA Codex (modelo)

## Generacion de Imagenes

Basado en DALLE.3 
Entrenado con imagenes


## IA Services

Servicio -> contruir aplicaciones -> impementando:
- Reconocimiento de imagenes
- PLN
- Lenguaje hablado
- Busquedas
- Etc


IA services -> se basa en **3 principios**

1. Pre diseñado y listo para usar
	- Soluciona problema de recursos (costos de datos, entrenamiento, recursos, etc)
	- Para emprasas de todo porte
	- Modelos pre-entrenados listos para usar (y modificar con fine tunning)
2. Acesso basado en API:
	- Se puede usar en diferentes entornos de desarrollo
	- API REST full, librerias, APP de logica
3. Disponible en Azure:
	- **PaaS**: Plataform as a service
	- **IaaS**: Infraestructure as a service


### Creando Azure IA services

Se deben crear recrusos para ser usados

Dos tipos de servicios:

- **Multi Servicios**: Recursos que brindan acceso a multiples ervicios -> un solo KEY - EndPoint -> al usar uno solo de los recursos **TODO SE FACTURA JUNTO**
- **Single services**: Un solo recurso -> acceso a un unico servicio -> a cada servicio se accede con un KEY-EndPoint -> **SE FACTURA POR SEPARADO**  -> *TIENEN CUPO GRATIS*

### Autenticacion

Limitar accesos -> solo solicitudes autenticadas

API REST Full -> Autenticacion en cada solicitud -> basado en Key de autenticacion

# Implementaciones - practicas


**Instancia de proceso** 

Son recursos para entrenar, 4 ociones de instancias:
- **Instancia de proceso:** Estacion de trabajo para datos y modelos
- **Cluster de proceso:** Maquina virtual ->Procesamiento dedicado por peticion, altamente escalable
- **Cluster de Kubernetes**: Destino de implementacion (Produccion)
- **Proceso Asociado**: Viculos a recuros existentes


## Diseñador

Crear proyetos de ML -> forma grafica -> el flujo se contruye igual q un diagrama

Se usa 3 componentes:

- Conjuntos de datos: Gestiona de datos (archivos locales, almacen de datos, archivos web, dataset)
- Componentes: Accionales para el diagrama, pasos dentro del flujo
- Pipelines: Gestion flujo de trabajo, se pueden reutilizar (para concervar configuracoin, accionables, etc)

## Trabajo de Azure ML




>>>>>>> a3d5f4a1cc9fda34f1bd485a2cdf49525ad72fcb

