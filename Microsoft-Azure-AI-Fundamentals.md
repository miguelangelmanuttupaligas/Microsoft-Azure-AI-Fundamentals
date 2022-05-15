# **Microsoft Azure AI Fundamentals**
## **Temario**
- [**Microsoft Azure AI Fundamentals**](#microsoft-azure-ai-fundamentals)
  - [**Temario**](#temario)
  - [**Inteligencia Artificial**](#inteligencia-artificial)
    - [**Aprendizaje automático**](#aprendizaje-automático)
    - [**Detección de anomalías**](#detección-de-anomalías)
    - [**Visión informática**](#visión-informática)
    - [**Procesamiento de lenguaje natural**](#procesamiento-de-lenguaje-natural)
    - [**Minería del conocimiento**](#minería-del-conocimiento)
  - [**Desafíos y principios responsables con la inteligencia artificial**](#desafíos-y-principios-responsables-con-la-inteligencia-artificial)
    - [**Desafíos de la IA**](#desafíos-de-la-ia)
    - [**Principios responsables en Azure**](#principios-responsables-en-azure)
  - [**Azure Machine Learning**](#azure-machine-learning)
    - [**Creación de un modelo de regresión**](#creación-de-un-modelo-de-regresión)
    - [**Creación de un modelo de clasificación**](#creación-de-un-modelo-de-clasificación)
    - [**Creación de un modelo de agrupación en clústeres**](#creación-de-un-modelo-de-agrupación-en-clústeres)
  - [**Análisis de imágenes con Computer Vision**](#análisis-de-imágenes-con-computer-vision)
    - [**Clasificación de imágenes**](#clasificación-de-imágenes)
    - [**Detección de objetos**](#detección-de-objetos)
  - [**Detección y análisis de rostros con Face Service**](#detección-y-análisis-de-rostros-con-face-service)
  - [**Lectura de textos con Computer Vision**](#lectura-de-textos-con-computer-vision)
  - [**Análisis de recibos con Form Recognizer**](#análisis-de-recibos-con-form-recognizer)
  - [**Análisis de texto con Language**](#análisis-de-texto-con-language)
  - [**Reconocimiento y síntesis de voz**](#reconocimiento-y-síntesis-de-voz)
    - [**Reconocimiento de voz**](#reconocimiento-de-voz)
    - [**Síntesis de voz**](#síntesis-de-voz)
    - [**Traducción de texto y voz**](#traducción-de-texto-y-voz)
  - [**Lenguaje conversacional con Language Service**](#lenguaje-conversacional-con-language-service)
  - [**Bot con Language Service y Azure Bot Service**](#bot-con-language-service-y-azure-bot-service)
  - [**Toma de decisiones con Anomaly Detector**](#toma-de-decisiones-con-anomaly-detector)

## **Inteligencia Artificial**
Creación de software que imita comportamientos y capacidades humanas.  
Cargas de trabajo clave incluyen a:
- **Aprendizaje automático**
- **Detección de anomalías**
- **Visión informática**
- **Procesamiento de lenguaje natural**
- **Minería de conocimiento**

### **Aprendizaje automático**
A menudo es la base de la mayoría de soluciones de IA.  
**Funcionamiento del aprendizaje automático**
- Las máquinas aprenden a partir de los datos
- Entrenar modelos de Machine Learning 
- Modelos realizan predicciones e inferencias en función de las relaciones que encuentran en los datos
**Aprendizaje automático en Microsoft Azure**  
Se proporciona el servicio **Azure Machine Learning**. Permite crear, administrar y publicar modelos de **Machine Learning**. Características del servicio

Característica|Funcionalidad
---|---
ML Automatizado|Permite a los no expertos crear un modelo de ML efectivo a partir de datos
Diseñador de soluciones|Interfaz gráfica que permite desarrollo sin código de soluciones de ML
Administración de datos y procesos|Almacenamiento de datos y recursos de procesos disponibles para su uso
Canalizaciones|Permite definir canalizaciones para organizar las tareas de entrenamiento, implementación y administración de modelos

### **Detección de anomalías**
Técnica basada en el aprendizaje automático que analiza los datos en el tiempo e identifica cambios inusuales.  
En **Microsoft Azure** el servicio **Anomaly Detector** proporciona una interfaz de programación de aplicaciones (API) que los desarrolladores pueden usar para crear soluciones de detección de anomalías.

### **Visión informática**
Área de la IA que trata el procesamiento visual. La mayoría de las soluciones se basan en modelos de ML que se pueden aplicar a la entrada visual de cámaras, videos o imágenes: 
- **Clasificación de imágenes**
- **Detección de objetos**
- **Segmentación semántica**
- **Análisis de imágenes**
- **Detección, análisis y reconocimiento de caras**
- **Reconocimiento óptico de caracteres (OCR)**
**Servicios de visión artificial en Microsoft Azure**:  
Servicio|Funciones
---|---
Computer Vision|Analizar imágenes y video, y extraer descripciones, etiquetas, objetos y texto
Custom Vision| Entrenar modelos de clasificación de imágenes y de detección de objetos personalizados mediante imágenes propias
Face|Crea soluciones de detección de caras y personas
Form Recognizer|Extrae información de facturas y formularios escaneados

### **Procesamiento de lenguaje natural**
En sus siglas PNL es el área de la IA que se ocupa de crear software capaz de entender el lenguaje escrito y hablado. En sus capacidades se encuentran:
- Analizar e interpretar texto en documentos, correos, etc.
- Interpretar el lenguaje hablado y sintetizar las respuestas del habla.
- Traducir automáticamente frases habladas o escritas entre idiomas
- Interpretar comandos y determinar las acciones apropiadas
**Procesamiento de lenguaje natural en Microsoft Azure**:  
Servicio|Funciones
---|---
Lenguaje|Comprende y analiza texto, entrenar modelos de lenguaje que comprendan comandos de texto o hablados
Translator|Traduce texto en más de 60 idiomas
Voz|Reconoce y sintetiza mensajes de voz y traducir idiomas hablados
Azure Bot|Plataforma para IA conversacional, permite crear un bot y administrarlo a través de *Bot Framework* con **Azure Bot Service**

### **Minería del conocimiento**
Soluciones que implican extracción de información de grandes volúmenes de datos no estructurados en general para crear un almacén de conocimiento indexado.
**Minería de conocimientos en Microsoft Azure**  
**Azure Cognitive Search** es una solución de búsqueda privada y empresarial que incluye herramientas para crear índices. Estos índices pueden ser internos o habilitados para permitir búsquedas en recursos de internet de acceso público.
**Azure Cognitive Search** puede usar las funcionalidades integradas de **Azure Cognitive Services**

## **Desafíos y principios responsables con la inteligencia artificial**
### **Desafíos de la IA**
- El sesgo puede afectar a los resultados
- Los errores pueden causar daños
- Se podrían exponer datos
- Es posible que las soluciones no funciones para todos los usuarios
- Los usuarios deben confiar en un sistema complejo
- ¿Quién es responsable de las decisiones basadas en la IA?
### **Principios responsables en Azure**
En Microsoft, el desarrollo de IA se guía por un conjunto de seis principios
- **Imparcialidad** - Tratamiento equitativo
  - **Azure Machine Learning** puede interpretar modelos y cuantificar en qué medidad cada característica de los datos influye en la predicción para así identificar y mitigar sesgos en el modelo.
- **Confiabilidad y seguridad** - Sistemas confiables y seguros
- **Privacidad y seguridad** - Seguros y respetar la privacidad
- **Inclusión** - Empoder e involucrar a todas las personas 
- **Transparencia** - Sistemas comprensibles y los usuarios ser conscientes del propósito del sistema, funcionamiento y limitaciones
- **Responsabilidad** - Diseñadores y desarrollados deben trabajar dentro de un marco de gobernanza y principios de organización que garanticen cumpla con estándares éticos y legales

## **Azure Machine Learning**
- **Área de trabajo**  
Para usar el servicio, se debe crear un área de trabajo. En esta se pueden administrar datos, recursos de proceso, código, modelos y otros artefactos relacionados con las cargas de trabajo.  
- **Destinos de proceso**
Lugares donde se ejecutan procesos de entrenamiento de modelos y exploración de datos. Puede crear 4 tipos: 
  - **Instancias de proceso** - Estaciones de trabajo de **desarrollo**. Trabajar con datos y modelos
  - **Clústeres de proceso** - Escalables para procesamiento a petición de código de experimento
  - **Clústeres de inferencia** - Destinos de implementación para servicios predictivos que usan los modelos entrenados
  - **Proceso asociado** - Vínculos a recursos de procesos de Azure existentes, como clústeres de Azure Virtual Machines o Azure Databricks
- **Exploración de datos**
Los datos para el entrenamiento de modelos y otras operaciones se encapsulan en un objeto **"Conjunto de datos"**
- **Entrenamiento de un modelo de ML**
**Azure Machine Learning** incluye una capacidad de aprendizaje automático automatizado que prueba varias técnicas de procesamiento previo y algoritmos de entrenamiento de modelos en parlelo y encontrar el modelo de ML con mejor rendimiento para los datos.
  - Las operaciones que se ejecutan se denominan *experimentos*. 
    - En **Azure Machine Learning Studio**, en **ML automatizado**
    - Selección del conjunto de datos, Tipo de tarea, Métricas, etc.

> ML automatizado solo admite modelos de ML supervisados
> Regresión para valores numéricos
> Clasificación para categorías o clases
> Agrupación en clústeres es una técnica de ML no supervisado
> Agrupación en clústeres agrupa entidades similares en función de sus características
- **Implementación de un modelo como servicio**
Publicarlo como servicio para que lo usen las aplicaciones cliente, ubicado en una instancia de **Azure Container Instances (ACI)** o clúster de **Azure Kubernetes Services (AKS)**(Recomendado en producción), por lo que debe crear un **clúster de inferencia**.

> Algunas notas
> - Validación cruzada para calcular la métrica de evaluación
> - La diferencia entre el valor previsto y el real: **valores residuales** que indica la cantidad de error en el modelo.
> - ACI no requiere un clúster de inferencia para implementar un modelo como servicio
> - Para usar el diseñador de Azure Machine Learning se debe crear una **canalización**
> - Generalmente crea una canalización de entrenamiento, canalización de inferencia y posteriormente implementa el modelo como un servicio
### **Creación de un modelo de regresión**
- Predecir etiquetas numéricas
- Técnica de aprendizaje automático supervisado
**Uso de diseñador**
  - Crear una canalización que iniciará con el conjunto de datos desde el que quiere entrenar el modelo.  
  - Deberá especificar un **destino de proceso**, especificamente un **clúster de proceso**
  - Agregar los campos necesarios

### **Creación de un modelo de clasificación**
- Predecir a qué categoría o clase pertenece un objeto
- Técnica de aprendizaje automático supervisado
- Aquí aparece **la matriz de confusión**. Para predecido-actual (1|0 - 1|0)
  - Verdaderos positivos 1 - 1
  - Verdaderos negativos 0 - 0
  - Falsos positivos 1 - 0
  - Falsos negativos 0 - 1
- También se ofrecen otras métricas como:
  - Exactitud - Proporciones correctas
  - Precisión - Fracción de casos positivos
  - Coincidencia - Fracción de los casos positivos + negativos
  - Puntuación F1 - combina precisión y coincidencia
> "Verdadero" es aquel que indica que el positivo o negativo es real
### **Creación de un modelo de agrupación en clústeres**
- Agrupar elementos similares en grupos según sus características
- Técnica de aprendizaje automático no supervisado (no existe etiqueta)
- Canalización de entrenamiento,Modelo de asignación de datos a clústeres, Canalización de inferencia

## **Análisis de imágenes con Computer Vision**
Para usar este servicio debe crear un recurso:
- **Computer Vision** - Recursos específico, útil si no piensa usar otro servicio cognitivo o un seguimiento de uso y costo por separado.
- **Cognitnive Services** - Recurso general que incluyo otros servicios.
El servicio requiere independientemente 2 variables:
- Clave - autenticar aplicaciones de cliente
- Punto de conexión - dirección HTTP donde se puede acceder al recurso

> Si crea un recurso de Cognitive Services, las aplicaciones de cliente usan la misma clave y punto de conexión independientemente del servicio específico que estén utilizando.

Envias una imágen al servicio con el cual puedes realizar tareas analíticas como:
- **Descripción de una imagen** - Se muestran las descripciones con más confianza primero
- **Etiquetado de características visuales** - Asociadas como metadatos que resumen atributos de la imagen
- **Detección de objetos** - Devuelve etiquetas de los objetos reconocidos y sus coordenadas de ubicación
- **Detección de marcas** - Identifica marcas(negocio) reconocidas y devuelve el valor booleano, confianza, matriz de coordenadas y el nombre de la marca
- **Detección de caras - detectar y analizar caras, edad y un cuadro de límite para ubicarlas (Las capacidades del servicio son un subconjunto de **Face service** dedicado)
- **Categorización de una imagen** - Clasifica imágenes según contenido
- **Detección de contenido específico del dominio** - Detecta personajes y puntos de referencia(lugares famosos)
- **Reconocimiento óptico de caracteres**
- **Funcionalidades adicionales**
  - Detectar tipos de imágen
  - Esquemas de colores de imágen
  - Vistas en miniatura
  - Moderar el contenido de una imágen

### **Clasificación de imágenes**
Crear una solución implica 2 tareas principales:
- Usar imágenes existentes para entrenar el modelo
- Publicarlo
Para cada tarea se necesita un recurso, puede adoptar 2 enfoques
- Crear 2 recursos en Custom Visión: entrenamiento y predicción
- Custom Vision para entrenamiento y Cognitive Search para predicción(Ambos en misma región)

**Entrenamiento**
- Cargar imágenes y etiquetarlas
- Evaluar los resultados
- Consideraciones:
  - Puede usar SDK o desde el Portal
  - Tener varias imagenes de diferentes angulos
**Evaluación**
- Proceso iterativo que devuelve las sgtes métricas:
  - **Precisión** - Modelo dice que habia 10, pero en realidad fueron 8 (80%)
  - **Coincidencia** - Modelo encuentra 7 de 10 manzanas (70%)
  - **Promedio de precisión (PP)** - Considera a ambos

### **Detección de objetos**
Un modelo de detección de objetos devuelve:
  - La clase de cada objeto
  - Puntuación de probabilidad de la clasificación (confianza)
  - Coordenadas de un cuadro de límite
Debe cargar imágenes, etiquetar los objetos individuales de la imágen y luego se entrenarán con esta, la carga y etiquetas se pueden hacer desde Portal.

## **Detección y análisis de rostros con Face Service**
Microsoft Azure proporciona varios servicios cognitivos:
- **Computer Vision** - Detección de caras y análisis básico como la edad
- **Video Indexer** - Detección e identifica caras en un video
- **Face** - Algoritmos pregenerados que pueden detectar, reconocer y analizar caras
> Face ofrece la gama más amplia de funcionalidades
**Face**  
Admite detección facial, comprobación de caras, buscar caras similares, agrupar caras basadas en similitudes, identificar personas.  
Además puede devolver coordenadas y atributos relacionados como:  
Edad,Desenfoque,Emoción,Exposición,Vello facil,Gafas,Cabello,etc.
**Recursos de Azure para Face**
- Face - Recurso específico
- Cognitive Services - Recurso general
Independientemente necesita una clave y un punto de conexión
**Consejos para resultados más precisos**
- Formatos de imagen: JPEG,PNG,GIF y BMP
- Tamaño de archivo: 6MB o menos
- Rango de tamaño de cara: desde 36x36 hasta 4096x4096
- Gafas de sol o una mano pueden afectar la detección de caras

## **Lectura de textos con Computer Vision**
Extraer texto de imágenes, usando los recursos siguientes:
- Computer Vision
- Cognitive Services
Independientemente necesita una clave y un punto de conexión  
**Computer Vision** proporciona dos API: **API de OCR** y **Read API**
- API de OCR
  - Es sincrónico
  - Extrae rápidamente pequeñas cantidades de texto en imágenes (reconoce texto en varios idiomas)
  - Devuelve información:
    - Regiones en la imagen que contienen texto
    - Líneas de texto en cada región
    - Palabras en cada línea de texto
    - y los rectángulos que indican ubicación de cada uno de estos elementos
- Read API
  - Asincrónico
  - Optimizada para imágenes con cantidad significativa de texto o ruido visual considerable
  - Opcion contra documentos digitalizados, Escritura a mano, Imágenes con texto como apoyo
  - El proceso implica enviar la imagen, recuperar el identificador de operación de la respuesta
  - Esperar que se complete y recuperar los resultados
  - Devuelve información:
    - Páginas
    - Líneas
    - Palabras

## **Análisis de recibos con Form Recognizer**
Combina el OCR con modelos predictivos que interpreten datos de formulario mediante:
- Relación de nombres de campo con valores
- Proceasmiento de tablas de datos
- Identificación de los tipos específicos de campo 
También admite el procesamiento automatizado de documentos a través de:
- Modelo de recibo pregenerado
- Modelos personalizados
**Recursos**
- Form Recognizer
- Cognitive Services
Independientemente necesita una clave y un punto de conexión   
**Consejos para resultados más precisos**
- En modelo de recibo pregenerado está habituado a EE.UU.
- Las imágenes deben estar en formato JPEG,PNG,BMP,PDF O TIFF
- Tamaño inferior a 50MB
- Tamaño de imagen entre 50x50 y 10_000x10_000 píxeles
- Para PDF, no debe ser mayores a 17x17 pulgadas

## **Análisis de texto con Language**
Se evaluan distintos aspectos de un documento o frase para obtener conclusiones sobre el contenido de ese texto.  
**Recursos**  
- Language
- Cognitive Services
**Usos**
- Puede detectar idiomas incluso con contenido de idioma ambiguo o mixto  
- Análisis de opinión (de sentimientos)
- Extracción de frases clave
- Reconocimiento de entidades

## **Reconocimiento y síntesis de voz**
- Reconocimiento de voz: capacidad de detectar e interpretar la entrada hablada.
- Síntesis de voz: capacidad de generar salida verbal.
### **Reconocimiento de voz**
Toma texto oral y lo convierte en datos procesables, a menudo mediante su transcripción a texto, para lograr esto se usan 2 tipos de modelos(juntos):
- acústico: señal de audio en fonemas
- lingüístico: fonemas a palabras

### **Síntesis de voz**
Lo contrario al reconocimiento de voz. Necesita de
- texto que se pronunciará
- Voz que se va a usar para vocalizar
Se suele acortar el texto para dividirlo en palabras y asigna sonidos foneticos a cada palabra.Después, divide la transcripción fonética en unidades prosodicas para crear fonemas que se convertirán al formato de audio. Estos fonemas se sintetizan usando parametros de una voz (tono y timbre)
**Recursos**
- Voice
- Cognitive Services
**Interfaces**
- API Speech to Text - transcripción en tiempo real o por lotes de audio a texto
- API Text to Speech - entrada de texto a voz audible, además permite flexibilidad de personalizar la solución de síntesis de voz y darle un carácter concreto

### **Traducción de texto y voz**
**Servicios**
- Translator - Traducir un texto a otro texto.
- Speech - Convertir los mensajes de voz en texto o traducir la voz.
**Recursos**
- Translator
- Speech
- Cognitive Services
**Configuraciones opcionales**
- La API de Translator permite ajustar el filtrado de lenguaje obsceno, traducción selectiva(etiquetar contenido para que no se traduzca, ejm marcas,ciudades)
**API´s de Speech**
Incluye 3 API:
- Conversion voz en texto
- Conversion texto a voz
- Traducción de voz

## **Lenguaje conversacional con Language Service**
No solo tienen que poder aceptar el lenguaje como entrada, sino también interpretar el significado semántico de la entrada(entender lo que se está diciendo).
**Conceptos básicos**:
"Enciende la lampara"
- Expresiones
  - Ejemplo de algo que un usuario podría decir
  - "Encender la lámpara"
- Entidades 
  - Elemento al que hace referencia una expresión
  - "Lámpara"
- Intenciones
  - Finalidad o el objetivo que se manifiestan en la expresión de un usuario
  - "Turn On a la lámpara"

**Un modelo se compone de intenciones y entidades**. Las expresiones se usan para entrenar el modelo con el fin de identificar la intención más probable y las entidades a las que se debe aplicar
**Servicios**
- Language Service
- Cognitive Services
**Pasos**
- Entrenamiento con intenciones,expresiones y entidades
- Publicación (Predicción)
**Creación**
- Proporcionan una colección exhaustiva de "dominios" precompilados que incluyen intenciones y entidades predefinidas para escenarios

## **Bot con Language Service y Azure Bot Service**
- Se necesita de una base de conocimiento de pares de preguntas y respuestas
- Un servicio de bot que proporciona una interfaz a la base de conocimientos a través de uno o más canales
**Creación**
Puede crear un bot mediante una combinación de los dos servicios
- Language Service - Incluye una característica de respuesta a preguntas personalizadas en una base de conocimiento de pares de preguntas y respuestas consultables mediante entradas de lenguaje natural
- Azure Bot Service - Marco para desarrollar, publicar y administrar bots en Azure
**Language Studio**
Crear la base de conocimiento es el primer paso, En Studio se crea,entrena,publica y administran bases de conocimientos.
Una vez esté satisfecho con su base de conocmiento, implementela y se puede usar a través de interfaz REST. Se requiere para acceder:
- Id. de la base de conocimiento
- Punto de conexión de la base de conocmiento
- Clave de autorización de la base de conocimiento
**Bot con Azure Bot Service**
Crear un bot mediante SDK o creación automática de bots. Una vez creado puede administrarlo:
- Extender su funcionalidad agregando código
- Probar el bot en una interfaz de prueba interactiva
- Configurar el registro, análisis y la interrogación con otros servicios
- Una vez listo puede conectar el bot a multiples canales

## **Toma de decisiones con Anomaly Detector**
Detección de anomalías es una técnica de IA para determinar si los valores están entre parámetros esperados.
- Anomaly Detector forma parte de la categoría de servicios de decisión de Azure Cognitive Services
- El limite establecido mediante un valor de sensibilidad, de forma predeterminada se calculan con **expectedValue**,**upperMargin** y **lowerMargin**. Paa ajustar los márgenes superior e inferior con **marginScale**
- El servicio acepta datos en formato JSON (Se especifica la granularidad)
- El servicio admitirá 8640 puntos de datos como máximo por un archivo JSON, pero esto puede generar latencia.
- En streaming, solo se enviaria un punto de datos y se evaluaria con el anterior enviado
- Si faltan menos de 10% de puntos, no habría efecto. Caso contrario, es mejor usar interpolación lineal para rellenar los huecos.
- Si los datos se distribuyen uniformemente, se ofrece mejores resultados

- Datos estacionales se entiende por datos que se producen a intervalos regurales (horarios,diarios,mensuales)

