# azure_certifications

Proyecto correspondiente a información para lograr la certificacion de Azure AI 900



[Notaciones y concejos para la preparacion del examen](https://ifgeekthen.nttdata.com/es/guia-para-preparar-el-examen-ai-900)

[aspectos basicos y guia de extamen](https://learn.microsoft.com/es-es/certifications/resources/study-guides/AI-900)

[Sumario online de microsoft para preparacion de examen](https://learn.microsoft.com/es-es/certifications/exams/ai-900/#two-ways-to-prepare)

[Examenes de prueba](https://www.youtube.com/watch?v=8XhQcAgdxXI&list=PLGnDOd349NCNxtsQpeWtIyD7lY1IrYw-n&index=7)

[Video curso preparatorio](https://www.youtube.com/watch?v=6DQvItqEKfI&list=PL3hNLk-aR0J97QHh7uZfafnUxIdQS5nSD&index=5)

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

- **Aprendizaje automatico:** Base del sistema de IA, es la forma de enseñar a un modelo a predecir y opbener conclciones de los datos
- **Deteccion de anomalias:** detectar errores o actividades inusuales
- **Vision informatica:**: (vision por computador) capacidad del software de interpresar el mundo por camaras, video e imagenes.
- **Prosesamiento de lenguaje natural**: (PLN) capacidad para intepresar lenguaje escrito o hablado y responder
- **Mineria de conocimiento**: Capacidad para extraer informacion **util** de grandes volumenes de datos (no exrtucturados) para crear almacen de conocimiento

### Aprendizaje automatico

Es la base de la mayoria de las solciones de IA

Permite que las maquinas aprenda mediante el analisis de grandes cantidades de datos

Estos datos se generan todos lods dias mediante nuestras interaciones (dispositivos, mensajes, fotos, redes sociales, ETC)

El ciclo para el ML es el siguiente

1.- Se obtienen los datos
2.- Se etiquetan los datos
3.- Se entrenas modelos con los datos para resolver un tarea
4.- Se empasula el resultado en un modelo (h5 x ejemplo)
5.- Se grean sistemas q utilizan el modelo

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

Area de la IA encargada de analizar el lengaje tanto hablado como escrito entenderlo dar dignificado y actuar en consecencia.

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

**Nota:** est servicio hace uso de los demas servicios de azure para obtener informacion de documentos y mejorar las busquedas como antes no era posible (utiliza vision por computatos, PLN, anmalias, etc)


## Desafios y riesgos de la IA

|Desafio|descripcion|
|-------|-----------|
|Segos en el entrenamiento|Entrenar con datos segados puede causar aplicaciones con resultados segados, engañosos, poco fiables y hasta equivocados|
|Errores que causan daños| si un modelo que forma parte de un sitema critico o medico falla puede causar daños no solo fiscos si no tamb a la salud de los pasientes|
|Filtracion de dados| los modelos tienen problema para saber q informacion es sencible o prohibida y podrian terminar filtrando datos sencibles de una empresa o persona|
|Quien es el resposable de las decisiones| En caso que los modelos fallen y causen daños a una persona o la muerte de alguien, quien es el responsable?|
|LAs soluciones no funcionan para todos| Relacionado con el sesgo del punto un, puede ser q un modelo no funcione para todos los usuarios, siendo una solucion no solo incompleta si no tamb causar daños a las personas si es un sistema critico como un sitema para invidentes|
|Hacer que las personas confien en la IA| Si un sistema de IA toma deciciones criticas como es q lo hacen ?|


## Inteligencia Artifical responsable

Principios de una IA desponsable de Azure:

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

### Privacidad y seguidad

Sistemas de IA deben ser seguros y respetar privacidad de datos

El problema radica q los modelos se entrenan con grandes cantidades de datos (en los q puede haber informacion privada)

Esto puede causar riegos de dibulgacion de informacion

Se debe tener cuidado con los datos usados y evitar poner en riesgo la privacidad o dibulgacion de datos

### Inclucion

Modelos q incluiyan a todos, sin discriinar por ningun aspecto
(ya sea dicapacidad, cultura, credo, religion, color de piel, genero, etc)

Respetar a las comunidades sin ignorar miorias

**EXOERIENCIAS DE IA PARA TODOS**

### Transparencia

Los usuarios deben saber el proposito, funcionamiento y limites del sistema

Asi se genera confianza de los usuarios

### Resonsabilidad

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





















