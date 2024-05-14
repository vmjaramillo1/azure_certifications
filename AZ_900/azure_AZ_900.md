# Azure Certifications
Proyecto correspondiente a información para la certificacion de Azure Az 900

## Temario

### Parte 1: Describir los conceptos básicos de Azure


1. [Introduccion a la inteligencia artificial](#into)

 1. [Introduccion](#intro)
 2. [Sobre la certificacion](#cert)
 3. [Introduccion a Azure](#intro_azure)
 4. [Fundamentos de Azure](#fundam)
 5. [Componentes centrales de Azure](#compo)

### Parte 2: Servicios centrales de Azure
 6. Servicios de computo de Azure
 7. Servicios de red de Azure
 8. Servicios de almacenamiento de Azure
 9. Bases de datos de Azure
 10. Big Data y Analytics en Azure

### Parte 3: Soluciones y herramientas de administración de Azure
 11. Azure IoT
 12. IA y Machine Learning
 13. Azure Serverless
 14. Herramientas de Azure DevOps
 15. Herramientas para administrar y configur el entorno
 16. Monitorizacin de Azure

### Parte 4: Características generales de seguridad y seguridad de la red.
 17. Proteccion contra amenazas
 18. Conectividad de la red segura en Azure

### Parte 5: Describir las características de identidad, gobernanza, privacidad y cumplimiento
 19. Acceso seguro a aplicaciones mediante los servicios de identidad
 20. Estrategia de gobernanza

### Parte 6: Administración de costes y los acuerdos de nivel de servicio de Azure
 21. Estandares de privacidad, cumplimiento y proteccin de datos
 22. Planificar y administrar costes
 23. Obtencion de la certificacion
 24. Examen practico 1
 25. Examen practivo 2
 26. Material adicional



## 1.Introduccion <a name="intro"></a>

En el curso se refectuara una aproximacion a los diferentes conveptos de Azure tanto a nivel tecnico como de plataforma.

El curso no tiene requisitos previos para ser aprobado y se encuentra dirigido a las personas interezadas en obtener la certificacin AZ-900


**Introduccion a plataforma**

- La plataforma es intuitiva
- Permite llevar control de las clases completadas
- En la parte inferior esta el texto de la clase
- Existe seccion de preguntas y respuestas (revisa en cada clase)
- Podemos crear notas en clada clase q se vincula al minuto del video
- Existen herramientas de aprendizaje para poder planear y controlar de mejor forma el estudio

**Estructuria del curso**

- Muy concizos
- Condenzados
- Incremento de nivel gradual
- Se pasa de la teoria a la practica
- Actializacion constante

**Acceso a material y certificado**

El material se puede conseguir desde la plataforma, sin embargo tamb esta dentro del proyecto, en el siguiente [link](https://github.com/vmjaramillo1/azure_certifications/blob/main/AZ_900/materiales/Presentacion_Curso_AZ-900.pdf)

El certificado se optinee al completal el 100% de totas las clases

**Mejores practicas para aprender**

- Tomar notas y repasar
- Generar resumenes
- Repazar clases antes de empezar una nueva clase
- Practicar los diferentes temas y efectuar los ejecicios
- Efecutar retos personales
- Buscar material adicional y ampliar le curso

**Consultas**

- Revisar la clase ante alguana duda
- revizar apartado de preguntas y respuestas
- Buscar en Foros


**Descuentos**

- Descuentos peridicos
- revizar linkendin con descunetos


## 2.Contenido del curso <a name="cert"></a>

**Sobre el examen**
Se recomiendo q en los examentes de text loguemos un 80 %

![image](https://user-images.githubusercontent.com/6383659/231333219-bf15d773-4d5d-4188-a03d-d3ad27f86ca0.png)

**Skils**

Se cumbren:

- Conpecto basicos de azzure y cloud
- Servicios de azure
- Herramientas (DB, IoT, IA)
- Seguridad
- Gobernanza
- Costes

![image](https://user-images.githubusercontent.com/6383659/231335647-51cff38d-7c38-453c-b3cc-28abe735ab61.png)



**Tipos de preguntas**

![image](https://user-images.githubusercontent.com/6383659/231337694-56721cc4-b41f-4b8b-a32d-1f067ac4acd1.png)


**Formas de certificacion**

- Presencial: similares al de remoto
- Remoto: necesario DNI, dejas basio el escritorio (sin segunda pantalla), q no entre nadie a la avitacion, pasar el control de acceso (control de programas), fotos del escritorio, no hablar durante certificacion

**Obtener la certificacion**

Se debe registrar en sitio web de microsoft

## 3 Introducion a Azure fundamentals <a name="intro_azure"></a>

**Azure**

Azure es el conjunto de servicios de computacion en nube ofrecidos por microsof.
En azure se arquila recursos y se paga por lo q se usa
Azure ofrece mas de 100 servicios diferentes entre Maquitas virtuales, almacenamiento, IA, etc.

Los servicio de azure se clasifican segun tipo, algunos de ellos son:

- **Compute:** Computadoras virtuales/cntenedores de kubernetes
- **Storage:** Almacenamiento de archivos
  - Blob: para archivos binarios
  - Quetes: colas de datos
  - Files:  para archivos
  - Disck: de espacio en disco
- **Networking:** Todo lo relacionado a como se conecta uno a los servicio de azure, balanceadores de carga, ruteo, VPN Gatewaay, app Gateway
- **Application plataform(Movile):** Para creacion de servicios de aplicaciones (API), escalado automatico, notificaciones, servicios de aplicaciones HTPL, etc
- **Analitics y IoT:** Todo lo relacionado a hadware conectado a nube, tamb servicios de presentacion tipo Power Bi
- **Data:** servicios de base de datos SQL, SQL server, dataWareHouse, cosmos DB, etc
- **Servicios de desarrollo:** Todo lo relacionados a DevOps, IDs, Xamary, etc
- **Intelligence:** servicios para IA, bot chats y servicios cognitivos, temas de Azure ML
- **Seguridad Y manejo:** seguridad apra azure y desarrollos paralelos
- **Computacion hibrida:** para servicios hom premis y cloud


![image](https://user-images.githubusercontent.com/6383659/233551308-91be0f43-915f-4509-b5ca-6d145abd7425.png)

**Cuentas**

Tipos de cuentas:
 - De pago
 - Gratuita
 - De estudiante gratuita

 ![image](https://user-images.githubusercontent.com/6383659/233551490-d5c40df2-7088-43c7-af85-4124ab167d8c.png)

 Nota: A los recursos es bueno agruparlos por "Grupos de recursos"

## 4.Fundamentos de Azure <a name="intro_azure"></a>

***Tipos de nube***

- **Publica:** Es acecible para todos mediante internet, es ofrecida por un proveedor quien la gestiona
  - Caracteristicas
    - Se paga por lo q se usa
    - Facil de escalar (en subidoa o baja de recursos)
    - No se gasta (invercion) para poder ampliar (xq se paga x uso)
- **Privada:** Solo acesible para poersonal de la empresa o personas autorizadas (server local o remoto), aceso controlado
  - Caracteristicas
    - Control total de la seguidad y recursos
    - Requiere invercion incial
    - Gestionada por la organizacion
    - Resonsables del mantenimiento y actualizaciones
- **Hibrida:** Es una mescla de las anteriores, datos y Apps se comparten
  - Caracteristicas
    - Mayor flexibilidd
    - La organicacion tiene control sobre la gestion y temas legales
    - Control sobre donde ejecutar las Apps

Nota: Recorda SLA -> Acuerdos de nivel de servicios

  ***Venrajas de Cloud de Azure***

  1. **Alta disponibilidad:** Recursos siempre disponibles
  2. **Escalabilidad:** Facil crecer vertical u horizotalmente
  3. **Agilidad:** Rapida implementacion y configuracion de recursos
  4. **Distribucion Geografica:** Permite Apps por regiones, mejora rendimiento(siempre optimas), eleccion del mejor nodo
  5. **Recuoeracion ante fallos:** Respaldo de seguidad
  6. **Flexibilidad:** Permite aprobicionar recursos segun la demanda justa de forma *automatica* (mejora costos y rendimiento)


---- grafica

  ***Tipos de gastos***

**CapEx:** Gasto Capital
- Se gasta x adelantado
- Valor reducido en el tiempo
- Coste inicial para la empresa

**OpEx**: Gasto operativo
- Sin coste inicial
- Se paga por lo q se usa
- Deduccion fiscal al final de año

***Modelos de servicio en Nube***

- **IaaS:** Infraestructura como servicio -> Se arquila hadware (Gestion manual de software y actualizacciones)
- **PaaS:** Plataforma como servicio -> Se arquila una plataforma de desrrollo (solo nos preocupamos por el montaje de la App)
- **SaaS:** Software como servicio -> Se arquila un sistema tal cual (Normalmente se usa una licencia, ejem Officce 365)






## 5.Componentes centrales de azure <a name="intro_azure"></a>

**Regiones**
- Una region en un agrea Geografica
- Azure distribuye el trabajo en diferentes areas al rededor del mundo (para tener trabajo equilibrado y escalabilidad)
- Azure tiene mas region q cualquier otro proveedor (mayor recilencia)


**Pares de regiones**

- Son replicas a una *"N"* discancia
- Permite respaldos dentro de la misma Geografia

**Zonas de disponibilidad**

- Se encuentra dentro de la region
- puede haber una o varias en cada region
- Es Infraestructura redundante, protege ante fallos, y brinda alta disponibilidad
- Existe un costo en duplicar el recurso en mas de una Zonas
- En cada zona encontramos un data center


**ASL**

- Recurso solo en una zona  -> 90%
- Recurso duplicado en en misma zona -> 95%
- Recurso duplicado en varias zonas -> 99%


**Redundancia de recursos**

- Si se cae una zona el trafico se pasa a la zona duplicada
- Los pares de zonas de disponibilidd se usan para partes criticas (BD, MV, Discos, Valanceadores de carga)
- Tambien existe pares de regiones

**Categorias de Servicios de Azure por Zonas**

- Servicios Zonales: Recurso en una sola zona
- Servicios con Redundancia de zona: Plataforma de replica automatica de recurso
- Servicios no regionales: Disponibles en todo el mundo


**Niveles organizativos de los recursos y grupos de recursos**

IMAGEN

1. Recurso: instancia de servicio
2. Grupo de recursos: grupo se servicios (Facilita administracion, gestion, orden y manejor de permisos basados en roles)
3. subscriocion: Agrupa cuentas de usuarios (tiene limites o cuotas)
4. Grupo administrativo: Administracion de accesos y politicas, las subscripciones heredan las condiciones aplicadas a cada grupo



**Grupos de recursos**

Hay dos términos importantes:
• Recurso: es un elemento único.
• Grupo de recursos: es una agrupación que contiene recursos relacionados. Ayudan a administrar y organizar los recursos.


Características de los grupos de recursos:
1. Al eliminar un grupo de recursos se eliminan todos los recursos que contiene.
2. Permiten aplicar permisos de control de acceso basado en roles (RBAC)



**Azure Resource Manager**

Grafico

- Permite Gestion de recursos
- Usar bloqueos 
- control de accesos
- Etiquetas
- Bus para gestion de recursos

**Suscripciones de Azure**

- Acceso autenticado y autorizado a serivios de  azure
- Es la unidad logica vinculada a la cuenta de Azure (identidad en aztive directory o directorio de confianza)


1 CUENTA  -> 1 O VARIAS Suscripciones -> diferentes modelos de facturacion o acceso

**limite sde subscriocion: **

- por facturacion
- por control de acceso


**Personalización de la facturación**

- Dentro de misma cuenta mmultiples facturas con subscripciones
subscriocion permite organizar el control de acceso a los recursos y facturacion
- Se puede configurar varias facturas dentro de la misma cuenta de facturación de Azure. Para hacer esto, hay que crear perfiles de facturación adicionales. Cada perfil de facturación tiene su propia factura mensual y método de pago.


**Grupos de administración**

- util si muchas Suscripciones
- organiza Suscripciones en grupos de administracion que heredan politicas

Ejm: Limites de recursos, creacion de NV, etc

# Servicios de Azure

IMAGEN


## Servicios de computo

**Fundamentos**

Azure Compute es un servicio de computación bajo demanda para ejecutar aplicaciones basadas en la nube.

Proporciona recursos informáticos como discos, procesadores, memoria, redes y sistemas operativos. Pago por uso.


**Tipos de servicios de computo**

- Maquinas virtuales: Emulacion de computacion
- Conjuntos de escalado: Administracion de conjuntos de MV, identicas para escalado de recursos
- Contenedores y kubernetes: entornos de APPs virtualizadas y ligeras
- Servicio de aplicaciones: Para implementar y escalar APPs web, movil y API
- Funciones: Para implementar solo codigo y no ocuparnos de la plataforma o Infraestructura



--------------------------



--------------------------

