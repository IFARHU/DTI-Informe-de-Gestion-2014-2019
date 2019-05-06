# Eje 4: Liderazgo e Innovación

## Introducción

La innovación no es únicamente el producto de la implementación de nuevas tecnologías o sistemas, ni tampoco está relacionada con realizar revoluciones amplias en las estructuras existentes.

La innovación está relacionada con el proceso de análisis de una situación, sintetizar lo levantado a través del proceso de análisis, desarrollar un plan de mejora y ejecutar el mismo en miras de solventar las situaciones presentadas durante la etapa de análisis.

De igual forma, la innovación requiere liderazgo, el cual tiende a confundirse con los cargos jerárquicos y no suele relacionarse con todo el personal operativo.

La innovación no es una acción, está relacionada más con la cultura dentro de una organización, según lo señala el Dr. Peter F. Drucker.

En este Eje, mencionamos proyectos que fueron desarrollados mediante los primeros cambios culturales a nivel del empoderamiento de liderazgo e innovación.

### Preparando al personal

Antes de iniciar cualquier proyecto de innovación, es necesario desarrollar ciertas competencias y capacidades blandas en el personal, además de descentralizar el mando y toma de decisión dentro del departamento, haciéndolo más participativo.

En estos temas, junto con el personal se realizaron capacitaciones:

- En temas de innovación.
- Nuevas tecnologías y tecnologías de desarrollo.
- Nuevos paradigmas de desarrollo y prácticas de desarrollo moderno.
- Marcos y pensamientos ágiles, como Scrum, XP, Lean y Kanban.
- Procesos de innovación.

De igual forma, se recayó el peso de proyectos enteros a unidades de la Dirección, para que los mismos pudiesen desarrollar sus respectivas habilidades blandas en negociación, dirección de proyectos, comunicación escrita, comunicación verbal y organización: habilidades necesarias en cualquier ambiente colaborativo.

**Estos esfuerzos parecen insignificantes, pero en esquemas y organizaciones gubernamentales, los colaboradores tienden a ejercer un papel a nivel de ejecución y no de toma de decisión. La innovación, al ser cultural, requiere cambiar el papel de los colaboradores desde solo ejecutores a ser líderes y tomadores de decisión.**

## Viernes IDI (Investigación, desarrollo e innovación)

> **Nota:** Este proyecto fue un proyecto piloto.

Desarrollamos un proyecto piloto conocido comom "Los Viernes IDI" de la DTI y escribimos sobre él en nuestro propio blog\footnote{https://ifarhu.github.io/2016/09/viernes-idi/}.

La tecnología es cambiante, e incluso en instituciones gubernamentales como el IFARHU es algo que no puede detenerse. Cada día salen nuevas formas de hacer las mismas cosas, nuevas tecnologías para reemplazar las ya existentes o nuevos métodos para mejorar la productividad de los procesos.

En nuestras Instituciones, es difícil mantenerse actualizado, por ende muchas de nuestras Instituciones siguen trabajando en tecnología inadecuada o anticuada (como Visual Basic).

Tomando la iniciativa de Google con la regla del 80-20\footnote{http://www.wired.com/insights/2013/08/innovate-or-die-why-googles-8020-rule-is-a-red-herring/}, algo que los ha hecho famosos para incentivar la innovación, el IFARHU en la Dirección de Tecnología Informática ha promovido los Viernes I+D+i (Investigación, desarrollo e innovación), o Viernes “IDI”, como regularmente le llamamos.

Este proyecto se implementó durante el año 2016 y la intención principal, más que desarrollar proyectos finales, era que los colaboradores de la DTI pudiesen despertar su instinto creativo, pudiesen evaluar nuevas tecnologías y desarrollar habilidades blandas de comunicación.

El proyecto estuvo vigente únicamente durante el año 2016 y de los resultados que hubo durante el proyecto fueron:

- Personal de la DTI pudo aprender de nuevas tecnologías, como Ruby (Sinatra y Rails), Agular y Vue.
- Uno de estos proyectos precisamente aportó al desarrollo base del Administrador de Becas 2.0, el cuál está basado en tecnología aprendida durante el Viernes IDI (ASP.NET MVC y Vue).

## Software Libre y Abierto

- Desarrollamos los primeros proyectos de Software Libre y Abierto en la historia del IFARHU y el primero (según nuestro conocimiento) en el Gobierno panameño.
- Somos una de las únicas organizaciones gubermentales con presencia en GitHub.
- Promovimos el uso y desarrollo de código libre y abierto.

## _Big Data_ y _Business Inteligence_ (BI)

A través de los sistemas del IFARHU y procesos digitalizados, se generan datos que residen en sistemas de bases de datos relacionales (RDBMS) que corren principalmente en motores de bases de datos basados en Microsoft SQL Server, representando decenas de millones de filas de pagos y algunos millones de registros, tantos históricos como activos. Dichos datos no han sido ni analizados ni aprovechados, permitiéndole al IFARHU tener una probable mina de oro para análisis futura.

El trabajo pretende desarrollar un sistema de EDW\footnote{Enterprise Data Warehouse.} que permita el manejo completo de grandes cantidades de información, la cual crece incrementalmente cada año.

El resultado de este trabajo se basa únicamente en la implementación de métodos que permitan la Extracción, Transformación y Carga (ETL) de los millones de datos, provenientes de los sistemas relacionales basados en SQL Server, a una plataforma basada en Apache Hadoop, un ecosistema de Big Data basado en código libre y que permite, sin problemas, la operación con grandes bloques de datos.

El resultado de esta transformación, será utilizado para ser presentado en un sistema propio que permita la generación de reportes y Dashboards en base a la información disponible, una actividad que se realiza en la actualidad de forma manual solo en momentos en que las Bases de Datos no son consultadas y bajo ciertos parámetros específicos.

Implementamos dos esquemas en paralelo:

### Equema 1: MongoDB

Se utilizó MongoDB, un sistema de bases de datos multiplataforma. MongoDB es clasificado como un base de datos de formato NoSQL, ya que utiliza esquemas basados principalmente en documentos de tipo JSON\footnote{JavaScript Object Notation}. MongoDB es desarrollado por MongoDB Inc. y licenciado de forma abierta y gratuita para su uso.

Realizamos una pequeña especie de Almacén de Datos basado en MongoDB, que recopila la información de los pagos y los beneficiarios. Este esquema replica la arquitectura ya existente en los sistemas relacionales.

### Esquema 2: Ecosistema Hadoop

Este mismo esquema se replicó en un ambiente orientado al manejo de Big Data.

Conforme pasa el tiempo, la información sigue creciendo. Por poner un caso particular, posterior a cada periodo de Beca Universal\footnote{Cada periodo tiene una duración anual}, todos los detalles de los pagos son trasladados a una Base de Datos relacional secundaria, donde se tiene acceso solo de lectura y no son consultados ni analizados.

Esta data, tanto la activa como la inactiva, representa grandes cantidades de información útil y que en la actualidad no se le saca provecho alguno, salvo para la evaluación puntual de cada beneficiario.

A través de la elaboración de este trabajo, se planea la implementación de un sistema de Big Data como Hadoop, no solamente para el consumo y generación de conocimiento a través de esta información, sino para que la arquitectura que resulte de este trabajo sirva como punto de partida para nuevas implementaciones que consuman la información almacenada en la arquitectura que arroje el trabajo.

Consideramos que era necesario un almacén de información, utilizando tecnologías de Big Data debido a:

1. Que la solución debe poder manejar grandes volúmenes de datos.
1. Dichos volúmenes de datos, además de ser grandes, no están estructurados de la misma forma.
1. Los tiempos de respuesta, incluso para los procesamientos más complejos, deben ser cortos y eficientes.

Es por ello que implementamos un EDW\footnote{Enterprise Datawarehouse} basado en el ecosistema de Hadoop, como una prueba de concepto para la manipulación de dichos volúmenes de datos.

### Consumiendo información y generando conocimiento

Para el despliegue de información a través de tableros de mando (_Dashboards_) y la posible generación de conocimiento, se implementó el uso de Tableau\footnote{https://www.tableau.com}, un sistema orientado a la inteligencia de negocios.

Gracias a Tableau podemos generar:

1. Estadísticas rápidas, con ciertos filtros como año o periodos, tipos de beca, programas de beca, provincia, distrito, corregimiento.
1. Podemos generar igualmente tablas o gráficos basados en estos datos.

Desde 2018 desplegamos e instalamos este sistema en los Departamentos de Procesamiento de Datos, Desarrollo de Sistemas (como soporte) y la Dirección de Planificación, intentando que dicha Dirección, a través de su Departamento de Estadística, pudiese consumir los datos sin requerir apoyo técnico de nuestro personal.

## IFARHU Verificar, Concursos, Concurso General, Conecta IFARHU, Administrador de Becas 2.0

Otros proyectos que fueron desarrollados mediante un esquema y cultura de innovación fueron los descritos en el Eje 3, especialmente: IFARHU Verificar, Plataforma de Concursos, Plataforma de Concurso General, Conecta IFARHU y Administrador de Becas 2.0.

Todos estos desarrollos fueron realizados por personal de la DTI y dichos proyectos fueron administrados y gestionados por personal operativo de la DTI directamente.
