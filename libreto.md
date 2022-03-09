# Libreto presentación tesis

## # 0 (Presentarme)

1. Buenas tardes a todos, quería agradecer por su presencia en esta presentación de memoria de tesis.
2. Mi nombre es Benjamín Gautier Ortiz, estudiante de la carrera ingeniería civil informática en la Universidad técnica federico santa maría y en esta instancia les presentaré la tesis que he desarrollado para postular al título de ingenierio civil en informática.
3. La tesis se nombra como "plataforma web de un sistema de gestión de la calidad de los procesos formativos de una unidad compleja, caso departamento de informática". En donde el guía del proceso ha sido el profesor Luis Hevia y el correferente la profesora Cecilia Reyes.

---

## # 1 (Qué veremos)

- Primero vamos a describir el **contexto** bajo el cual se desarrolla esta memoria,
- Segundo veremos cual es el **tema principal** de la memoria, y que se hace en torno a este actualmente
- Tercero veremos cuales son los **problemas** que se presentan bajo el tema de la memoria
- Cuarto se presentarán el **objetivo** principal y los específicos para mitigar la problemática planteada en el punto anterior
- Quinto veremos el **estado del arte** en torno a la problemática
- Sexto veremos la **metodología de estudio** para plantear una solución
- Séptimo se **planteará una solución** a la problemática
- Octavo se mostrarán las **tecnologías** asociadas a la solución planteada
- Noveno se mostrará el proceso de **validación** de la solución
- Finalmente comentaremos las **conclusiones** mas importantes del estudio.

---

## # 1 (Plantear problemática y definir el tema)
<!--  - Contextualizar OCDE + normas internacionales + creciente demanda de Educación terciaria.
      - El tema principal de la memoria: Gestionar la calidad de los procesos formativos de una unidad compleja.
      - Como se relaciona este con el DI y por qué se plantea que es una tarea compleja.
      - Que se hace actualmente para medir lo anterior.
      - Plantear el enunciado de la problemática.
-->

_keywords_: Contexto - Tema principal - Relación con el DI - Actualidad - Problemática

### Contexto

Desde el 2010 Chile es un miembro pleno de la OCDE, el cual es un organismo de cooperación internacional en donde actualmente existen 38 países afiliados. Estos trabajan en conjunto para solucionar problemáticas comunes, compartir experiencias e identificar las mejores práticas que permitan promover políticas que mejoren los estándares de vida de sus ciudadanos.

Según el último informe de este organismo, los países miembros deben redoblar sus esfuerzos para mejorar la calidad y la igualdad de sus sistemas educativos como parte de sus compromisos de cumplir con el objetivo del desarrollo sostenible (ODS).

Por otro lado, como muestran los indicadores OCDE de las figuras, el número de estudiantes cursando estudios de nivel superior ha ido en aumento con el transcurso de los años, al igual que con la cantidad de población que logró titularse en una institución de Educación superior. Con esto se infiere que la demanda irá en aumento.

Entonces, debido al compromiso con el desarrollo sostenible, más la masificación de la educación de nivel superior, es que es esencial que las instituciones de educación entreguen formación de calidad. 

Uno de los valores declarados por el DI es la adopción de la mejora continua como una herramienta para llegar a la visión establecida, pero, ¿cómo podemos adoptar la mejora continua?...
Según organismos internacionales como ISO, es necesario implementar Sistemas de Gestión de la calidad para adoptar un enfoque de procesos y así lograr una mejora continua. Aquí es donde encontramos la Norma ISO 9001:2015, la cual establece los requisitos para implementar un sistema de gestión de la calidad,
y se le suma la reciente norma ISO 21001:2018, la cual es una extensión especializada para organizaciones con rol educativo.

### Tema principal

Este concepto recién mencionado es el tema principal de esta memoria: Un sistema de gestión gestión de la calidad de los procesos formativos.

### Relación con el DI

El DI al ser parte de una institución con estructura organizacional vertical, se le delega la responsabilidad de controlar, dirigir y gestionar los procesos institucionales y formativos relacionados con su área. Además dado que su dirección se extiende a tres sedes, podemos afirmar que la gestión del mismo es una tarea compleja.

### Estado actual

Actualmente no existe un Sistema de Gestión de Organizaciones Educativas en la Universidad ni en el DI, pero si se tiene un Manual del Sistema de Aseguramiento de la Calidad UTFSM, el cual refleja el compromiso con la calidad de los procesos organizacionales y las metodologías propuestas para conllevar lo anterior. No obstante, dicho manual no es específico para los procesos foramtivos, si no que una base orientadora para cada unidad académica, docente y administrativa, y que debe ser considerada en la aplicación específica de actividaddes y procesos.

### Problemática

Incapacidad de gestionar eficiente y equitativamente la calidad de los procesos formativos, y así asegurar la calidad de los mismo 
en el Departamento de Informática

---

## # 2 (¿Marco Conceptual?)

La base teórica en la que se basa el desarrollo de esta memoria son los siguientes:
- Norma ISO 21001:2018.
- Encuestas basadas en cuestionarios.
- Aplicaciones web SPA.
- REST API.
- DDD.
- Visualización de datos.

### Norma ISO 21001:2018

Creada por la Organización Internacional de Normalización, la cual la hizo oficial en mayo del 2018. 

Esta establece los requisitos de un Sistema de Gestión para Organizaciones Educativas, proporcionando una herramienta de gestión común a organizaciones que proveen productos y servicios educativos capaces de cumplir con los requisitos de los estudiantes y otros beneficiarios. Esta Norma nace bajo la necesidad crítica y continua de que las organizaciones estén en posición de evaluar el grado de cunplimiento de los requisitos de los estudiantes y otros beneficiarios, así como también a las partes pertinentes interesados.

Dentro de los principios de un SGOE encontramos:
1. Enfoque y compromiso con los estudiantes y otros beneficiarios.
2. Mejora continua y enfoque de procesos.
3. Toma de decisiones basada en evidencia.
4. Seguridad y protección de los datos.
5. Entre otros.

Por otro lado, esta norma impulsa la mejora continua y el enfoque a procesos al desarrollar, implementar y mejorar la eficacia de un SGOE, mediante el cumplimiento de los requisitos de los estudiantes y otros beneficiarios.

La Norma recomienda la metodología PHVA para adoptar la mejora continua en todos los procesos y actividades de la organización, en donde todas las etapas son importantes, pero esta memoria planea apoyar en la "verificación" y el "actuar".

---

### Encuestas basadas en cuestionarios

Uno de los métodos más utilizados para tener conocimiento de las necesidades, expectaticas y requisitos de los usuarios de un servicio es la ejecución de encuestas a estos, con la finalidad de saber el grado de cumplimiento y el nivel de satisfacción. Una vez recolectados los datos estos pueden ser utilizados para realizar un análisis más profundo, con la finalidad de buscar tendenciar y hacer visualización de estos con la finalidad de entregar información de utilidad para los cargos directivos.

### Aplicaciones web SPA

Bien sabemos que el Internet cada día llega a más personas en el mudno, en paralelo, las compañías y organizaciones han aprovechado de aumentar su cuota de participación y presencia medainte la creación de aplicaciones y páginas web's, con la finalidad de ofrecer servicios y productos de forma virtual o entregar información a muchas personas.

Una página web es un documento que puede contener: texto, sonido, videos, programas, enlaces, imágenes, hipervínculos y muchas otras cosas, adaptada para la WWW y que puede ser accedidad mediante un  navegador web.

Bajo el contexto de tecnologías y aplicaciones web encontramos dos tipos de implementaciones:
1. MPA: Cargan todo el contenido nuevamente al cambiar de ruta
2. SPA: Cargan el contenido que se necesita, y al cambiar de ruta solicita los nuevos necesarios.

### REST API

Una REST API es una interfaz de programación de aplicaciones que cumple las condiciones de arquitecturas REST y permite la interacción con servicios web mediante html y json.

Una API es un conjunto de definiciones y protocolos utilizado para integrar el software de las aplicaciones.

REST es el acrónimo de Representational State Trasfer, el cual es una arquitectura para sistemas distribuidos de hipermedia para diseñar aplicaciones bajamente acopladas a través de la comunicación HTTP. 

Esta posee 6 condiciones para que ssea considerada como RESTful:
1. Arquitectura Cliente-Servidor
2. Protocolo sin estado (Stateless)
3. Almacenable en caché
4. Interfaces uniformes
5. Dividido por capas
6. Código o funcionalidades on-demand (opcional)

### DDD

El diseño guíado por el dominio es un enfoque para desarrollar software que se centra en el desarrollo de un modelo evolutivo que se va enrriqueciendo al entender los procesos y reglas del dominio. Este enfoque conlleva a utilizar Programación Orientada a Objetos y los principios SOLID.

POO: Rádica en los conceptos de clases y objetos, en donde una clase es la agrupación de propiedades y de métodos que operan sobre esos datos, y un objeto es la instancia de una.

SOLID: es el acrónimo para los 5 principios establecidos por Robert C. Martin, los cuales establecen prácticas de diseño para considerar la mantención, extensión y escalabilidad del código fuente de un sistema.

Además el sistema debe estar dividido por capas:
1. Capa de presentación,
2. Aplicativa,
3. De dominio,
4. De infraestructura.

La forma en que las 4 capas mencionadas anteriormente se organizan implementan la arquitectura CLEAN, la cual hace referencia a desacoplar las dependencias entre los módulos.

### Visualización de datos

Un dato se define como:
1. información fáctica que es utilizada como base para el razonamiento, la discusión o el cálculo. 
2. Información en forma digital que se puede transmitir o procesar.

Por otro lado, la información es el conocimiento obtenido de la investigación, estudio o instrucción.

A los cargos directivos y usuarios les es de utilidad la información, pero primero estos deben ser recolectados y procesados para proporcionar información significativa para sus consumidores.

En base a lo anterior, la visualización de datos es una herramienta que permite proporcionar información a los cargos directivos o usuarios, mediante el despliegue de elementos gráficos.

## # 3 (Objetivo principal y específicos para mitigar la problemática)

### Objetivo general

Diseñar e implementar una herramienta para el apoyo en la toma de decisiones en cuanto a la gestión de la Calidad de los Procesos Formativos del Departamento de Informática de la UTFSM.

### Objetivos específicos

1. Proporcionar métricas e indicadores de la calidad de los procesos formativos del departamento de informática.
2. Proponer los elementos de gestión más relevantes sel SGOE establecido por la norma ISO 21001:2018 y que el DI debiese de implementar en sus carreras.
3. Implementar un método que permita la detección de procesos y actividades que no entregan valor al proceso formativo o que pueden mejorar sus indicadores.

---

## # 4 (Estado del arte)

- ISOTools
- Plataformas de encuestas

---

## # 5 (Metodología de estudio)

- Se estudia la situación actual del DI
- Se realiza el ejercicio de ingestión de datos de los resultados de encuestas de años anteriores y visualización de los resultados.
- Se estableció la problemática.
- Se plantea una solución desde la perspectiva informática e ingenieril.
- Se desarrolla iterativamente la plataforma, comenzando desde módulos principales y más pequeños hacia los más complejos, DDD 
- Luego se hace una etapa de pre-validación y validación de la solución con estudiantes de una asignatura del DI.

---

## # 6 (Solución a la problemática)

Establecer la solución a la problemática detallando las desventajas de otras herramientas.

---

## # 7 (Tecnologías subyacentes)

- ASP .NET CORE
- Angular 12
- NG-Zorro
- Bootstrap
- Microsoft SQL server
- ABP Framework
- Azure
- Background jobs

---

## # 8 (Validación de la solución)

- Etapa de prevalidación
- Etapa de validación
- Mostrar imágenes de este proceso de creación de encuestas, lanzamiento y visualización de los resultados.

---

## # 9 (Conclusiones)

...



---
