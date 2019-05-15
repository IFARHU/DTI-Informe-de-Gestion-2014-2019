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

![Vista de un Dashboard de Tableau para el análisis de un tipo de beca en un rango de tiempo (periodo anual). \label{chap6_fig5}](source/figures/chap6_fig5.png)

Para el despliegue de información a través de tableros de mando (_Dashboards_) y la posible generación de conocimiento, se implementó el uso de Tableau\footnote{https://www.tableau.com}, un sistema orientado a la inteligencia de negocios.

Gracias a Tableau podemos generar:

1. Estadísticas rápidas, con ciertos filtros como año o periodos, tipos de beca, programas de beca, provincia, distrito, corregimiento.
1. Podemos generar igualmente tablas o gráficos basados en estos datos.

Desde 2018 desplegamos e instalamos este sistema en los Departamentos de Procesamiento de Datos, Desarrollo de Sistemas (como soporte) y la Dirección de Planificación, intentando que dicha Dirección, a través de su Departamento de Estadística, pudiese consumir los datos sin requerir apoyo técnico de nuestro personal.

## IFARHU Verificar, Concursos, Concurso General, Conecta IFARHU, Administrador de Becas 2.0

Otros proyectos que fueron desarrollados mediante un esquema y cultura de innovación fueron los descritos en el Eje 3, especialmente: IFARHU Verificar, Plataforma de Concursos, Plataforma de Concurso General, Conecta IFARHU y Administrador de Becas 2.0.

Todos estos desarrollos fueron realizados por personal de la DTI y dichos proyectos fueron administrados y gestionados por personal operativo de la DTI directamente.

## Clave Social

La DTI fue un gran impulsor de la incorporación de Clave Social como método de pago para Beca Universal. En la actualidad, más de 120 mil estudiantes cobran a través del método de Clave Social del IFARHU, todo soportado por nuestra plataforma electrónica definida para tales fines.

El IFARHU desarolló seis diferentes fases del programa de Clave Social, adjuntando 392 colegios al programa.

![Estudiante recibiendo su Clave Social para el recibo de sus beneficios de Beca Universal. \label{chap6_fig8}](source/figures/chap6_fig8.jpg)

El papel de la DTI ha sido un papel clave, puesto que al ser pagos electrónicos, mucho del peso administrativo del programa recae sobre la DTI, especialmente los procesos de:

- Levantar los listados de aperturas para el uso del Banco Nacional de Panamá (BNP) para las nuevas aperturas de cuentas únicas simplificadas (clave social).
- Definir con el MEDUCA el proceso de seguimiento (en base a la Ley de Beca Universal y el Manual Operativo de Beca Universal).
- Definir el Manual de Seguimiento de Clave Social (Beca Universal) en conjunto con el MEDUCA.
- Levantar los listados para el seguimiento masivo con MEDUCA.
- Definir el proceso para el seguimiento masivo, a partir del archivo recibido por MEDUCA.

Gracias a estos procesos y la incorporación de Clave Social, el IFARHU redujo el tiempo requerido para pagar masivamente a los beneficiarios de Beca Universal, reduciendo el costo operativo para la entrega de dichos pagos e incluso reduciendo horas de trabajo, la discrecionalidad al momento de entregar el pago.

Otros beneficios de Clave Social son:

- El seguimiento se hace automático, consumiendo directamente de la fuente de información adecuada (el MEDUCA).
- Una vez los pagos son autorizados, todos los estudiantes pertenecientes a una planilla reciben sus pagos.
- Se eliminan las largas filas, los días perdidos de clases y los permisos de los representantes legales de los estudiantes para ir al centro a buscar los pagos.
- No se requieren horas adicionales de trabajo por parte del personal del IFARHU para generar, imprimir y entregar los pagos. Reducen los costos, al no requerir el pago de horario extraordinario ni tantos pagadores.
- **Según se sugirió por parte de la DTI, se podría implementar un control más estricto para el uso racional y correcto de los fondos destinados a la Beca Universal.**

El programa de Clave Social ha sido muy criticado porque los pagos requieren ser realizados solo después de la verificación con el MEDUCA y no antes, a diferencia de los pagos por cheque que pueden ser generados e impresos antes, pero deben verificarse si se cumplen todos los requisitos para el cobro, al momento de entregar el pago.

La DTI, durante el año 2019, ha podido iniciar conversaciones con el BNP y la empresa BioSoft, creadores del programa MEREB para los colegios particulares de Panamá, lo que nos permitiría llegar a estos centros educativos en el programa de Clave Social - Beca Universal.

## Kioskos de Atención

A través del Proyecto "PROY-22-2017 / Implementación de Kioskos de auto-atención en la Sede Central del IFARHU" la DTI implementó un sistema de auto-atención para los beneficiarios del IFARHU que realizan trámites en Sede Central del IFARHU, por instrucciones y directrices de parte del Despacho Superior del IFARHU, quién encomendó inicialmente este proyecto a la Dirección de Planificación, al ser un proyecto orientado al mejoramiento de los procesos, más que una implementación tecnológica. La DTI adquirió el compromiso de realizar el proyecto en el año 2017, mediante un análisis de procesos y de filas, para una posterior implementación tecnológica.

![Usuarios utilizando el sistema de filas. \label{chap6_fig1}](source/figures/chap6_fig1.png)

Este proyecto está dentro del Eje 4 (Innovación) debido a que es el primer proyecto del IFARHU que fue diseñado y desarrollado por la DTI para resolver situaciones cotidianas mediante la incorporación de ingeniería y tecnología, algo que crea un precedente en las operaciones de nuestra Dirección y del IFARHU.

![Pantalla del sistema de filas a través de donde se llaman los números. \label{chap6_fig2}](source/figures/chap6_fig2.png)

Los trabajos de este proyecto incluyeron:

- El estudio de los distintos ciclos de atención, para cada uno de los departamentos.
- La definición de mejores ciclos de atención, para cada uno de los departamentos.
- Incorporación de kioskos de auto-atención, que permitan al usuario obtener un número para recibir su atención.
- Incorporación de métodos de información (pantallas o similares) que le permitan a la persona saber cuando puede ser atendido y por quién será atendido.

El IFARHU recibe gran cantidad de visitas durante todo el año, mayormente debido a su gran población de beneficiarios, la cual asciende a poco más de 800,000 estudiantes a nivel nacional.

Dichos estudiantes requieren realizar constantemente trámites en el IFARHU de distintos tipos, por ejemplo:

- Trámites de Becas.
- Seguimiento de las Becas.
- Pago de Becas.

Para cada uno de estas atenciones físicas, el beneficiario requería formar filas hasta ser atendidos y procesos tradicionales para recibir dicha atención, como lo son números impresos en pequeños cartones y llamadas, por parte del personal de seguridad, en los pasillos con el número de la persona que será atendida.

![Kioskos instalados en el Departamento de Beca Universal. \label{chap6_fig4}](source/figures/chap6_fig4.png)

Igualmente, no se contaban con estadísticas reales de las atenciones que realiza el IFARHU, por lo que es difícil saber los resultados a nuestra atención, que días se recibía más personal, el tiempo que demoraban las visitas, el personal que atendía más o el que atendía menos, entre otras estadísticas.

Se determinó que estos procesos podían ser mejorados mediante la incorporación de tecnología en cada uno de los aspectos, por ejemplo:

- Que el usuario solicite una atención, mediante un kiosko de auto-servicio.
- Una vez solicitada la atención, se le dará un número de ticket, que representará el número de espacio en fila.
- Que una vez registrada la persona en fila, la persona sea atendida cuando le corresponda.
- Que dichas filas puedan ser monitoreada mediante una plataforma administrable y accesible desde un dispositivo (computadora, por ejemplo) y una interfaz web.
- Que el personal de atención pueda llamar a la siguiente persona en fila para su atención.
- Que el beneficiario pueda saber, mediante una pantalla o algún otro irradiador de información, cuando será atendido. Todo esto desde una sala de estar o un espacio destinado para espera.
- Que las estadísticas de atención puedan ser generadas y descargadas para su interpretación.
- Que, mediante la plataforma web, puedan realizarse algunas acciones administrativas de atención (como solicitar una atención express, entre otros).

Mediante la realización de este proyecto hemos podido:

- Evaluar el ciclo de atención de los distintos departamentos de becas del IFARHU.
- Evaluar mejoras que puedan ser implementadas en los distintos ciclos de atención de becas del IFARHU.
- Mejorar los ciclos de atención de IFARHU.
- Mejorar la atención, y la percepción de dicha atención, que reciben nuestos cientos de miles de beneficiarios de nuestra Institución.
- Tener estadísticas de flujo de los usuarios, según puede verse también en la Figura \ref{chap6_fig7}.

![Informe generado a través de las estadísticas generadas por el sistema. Reporte de atención desde el 01 al 24 de diciembre de 2018. \label{chap6_fig7}](source/figures/chap6_fig7.png)

Tal como se mencionó inicialmente, el proyecto no era un proyecto de incorporación tecnológica únicamente.

- Análisis y mejora del ciclo de atención
- Módulo de Cliente (kiosko)
- Módulo de Espera
- Módulo de Atención
- Módulo de Administración
- Entrenamiento

Durante los primeros meses del año 2019 la DTI ha podido realizar entrevistas a los usuarios, dando como resultado una mejora en la percepción de los usuarios. Este mismo sistema se empleó por primera vez en 2019 para el recibo de los documentos de Concurso General y la reacción sobre la atención en Planta Central fue muy buena, según se puede apreciar en algunos mensajes recibidos en las redes sociales, visto en la Figura \ref{chap6_fig6}.

![Mensajes recibidos en las Redes Sociales sobre el recibo de documentación de Concurso General 2019. \label{chap6_fig6}](source/figures/chap6_fig6.png)

## Inteligencia Artificial (AI)

> **Nota:** Este es un proyecto piloto y de investigación.

La DTI ha desarrollado un proyecto conocido como ALEXIS, el cual es un Chatbot desarrollado con el apoyo de la librería BotMan\footnote{https://botman.io/}, un marco de trabajo (_framework_) para el desarrollo de Chatbots en PHP.

La intención principal de este proyecto era desarrollar un Chatbot que pudiese conectarse automáticamente con los servicios de Conecta IFARHU y a su vez, presentar respuestas a preguntas claves como:

- Si tengo actualmente un beneficio con el IFARHU.
- Conocer sobre los pagos que se me han realizado con anterioridad.
- Ubicar las regionales del IFARHU, quizás las regionales más cercanas a mi.

El proyecto se desarrolló hasta una etapa bastante avanzada, pero requiere realizar ajustes y su publicación. El mismo se encuentra en la cuenta privada del IFARHU en GitLab\footnote{https://gitlab.com/ifarhu/alexis}.

## Trámites en línea

La AIG ha desarrollado el proyecto de Panamá en Línea (PEL)\footnote{\url{https://panamatramita.gob.pa/panamaenlinea}}. Este proyecto renueva la forma en que el ciudadano tramita con el Estado, para que todos los procedimientos se hagan de manera ágil y transparente.
 
Esta iniciativa optimiza el desempeño de las funciones gubernamentales para mejorar la prestación del servicio al ciudadano, permitiendo una mayor transparencia y calidad de servicios a todos los panameños y extranjeros, eximiéndolos de presentar documentación sobre información que resida en bases de datos digitales del Estado, trayendo consigo más comodidad, menos visitas a las entidades, menos filas y ahorros de tiempo y costos.

Este proyecto está relacionado con el proyecto de Panamá Tramita, en el cual se establecen todos los procesos que se manejan en el IFARHU a través de un portal único.

El IFARHU fue una de las primeras **7 instituciones** del gobierno que presentó un trámite en línea a través del portal de Panamá en Línea. Adicionalmente renovó todos los trámites que se listaban en el portal de Panamá Tramita para que se reflejaran actualizados.

Al día de hoy, el IFARHU cuenta con dos trámites en línea disponibles en el portal:

- Solicitud de Paz y Salvo (Crédito Educativo)
- Solicitud de Certificación de Crédito (Crédito Educativo)

A través de esta implementación, el IFARHU 

## Interoperabilidad

La interoperabilidad es la capacidad que tiene un producto o un sistema, cuyas interfaces son totalmente conocidas, para funcionar con otros productos o sistemas existentes o futuros y eso sin restricción de acceso o de implementación\footnote{Traducción por Pascual Chevrel}.

En el caso gubernamental, es la capcidad de que sistemas de dos instituciones puedan interoperar o colaborar, permitiendo el flujo de datos e información en ambas vías, mediante un canal designado y un patrón o esquema acordado.

La interoperabilidad con otras instituciones no existieron en el IFARHU hasta el año 2014, entrada esta administración, permitiéndole a esta administración cumplir con lo establecido en la Ley 83 de noviembre de 2012, la cual señala:

> Los usuarios estarán exentos de aportar datos y/o documentos que reposen en las bases de datos de las entidades públicas. Corresponderá a estas entidades obtener dicha información de la base de datos que corresponda. En el caso de información confidencial o de acceso reservado, se deberá contar con el consentimiento expreso de los interesados o cumplir con los requerimientos que reguulan la protección de este tipo de información. El citado consentimiento podrá emitirse y recabarse por medios electrónnicos. — Ley 83 de 2012, Capítulo II, Artículo 4, Numeral 3.

Durante esta administración se pudieron realizar dos proyectos de interoperabilidad del IFARHU con otras instituciones.

### MIDES: Revisión de Corresponsabilidades para el progama de Red de Oportunidades

Durante una reunión con personal del MIDES, donde se analizaban mecanismos más eficientes para verificar la corresponsabilidad del programa de Red de Oportunidades, en uno de sus componentes (Educación). El IFARHU trabajó con el MIDES para ofrecer su apoyo técnico, tecnológico e informativo, para que la verificación de dicha corresponsabilidad se pudiese hacer a través de los sistemas de IFARHU.

Se definió el esquema de interoperabilidad con el MIDES, definiendo las variables de entrada y salida del proceso. Las variables de entrada serían dadas por el MIDES y las variables de salida serían entregadas, luego del procesamiento, por el IFARHU.

Este proyecto se realizó en dos formas o etapas:

1. La primera forma, se realizó entre los años 2014 a 2017, se realizaba mediante la solicitud por escrito de parte del MIDES, con un listado de personas para comparar contra nuestros registros de Beca Universal.
1. La segunda forma, se realizó a partir del año 2018. Esta forma involucraba la incorporación de tecnología en ambos extremos.

En la segunda forma, el IFARHU implementó un API (interfaz de programación de aplicaciones, por sus siglas en inglés) que permitió el consumo de forma segura por parte del sistema del MIDES, siguiendo nuestros modelos y buenas prácticas de seguridad.

Desde su implementación a partir de 2018, el MIDES ha realizado más de 200 mil consultas de forma automática a los sistemas de IFARHU. Dicho API reside como un sub-componente dentro de Conecta IFARHU, descrito en el Eje 3.

### Banco Nacional de Panamá (Clave Social y Beca Universal)

Además de la implementación de Clave Social realizada por el IFARHU en conjunto con el BNP, descrito anteriormente en este capítulo, la DTI pudo realizar en forma colaborativa con el personal del BNP la implementación de un nuevo esquema para la carga masiva de los registros de los becarios de Beca Universal que cobran por cheque.

Todos los cheques que son generados en el IFARHU requieren ser registrados en los sistemas de verificación del BNP para su posterior cobro. Es por ello que el IFARHU envía al BNP el listado de los cheques y sus generales para la respectiva aplicación dentro de sus sistemas.

Con anterioridad, el IFARHU requería enviar estos listados por medio físico (Disco Compacto). Este proceso se agilizó y mejoró mediante la incorporación de un canal privado entre el BNP y el IFARHU.

Los archivos ahora reciden en un sistema de IFARHU y el BNP puede consumir y registrar dichas cargas en cuestión de minutos, reduciendo notablemente el tiempo de registro y entrega de estos listados y agilizando el proceso.

### Tribunal Electoral: Revisión y validación de generales

Tal como describimos en el Eje 3, la primera interoperabilidad con otra institución la realizó el IFARHU con el Tribunal Electoral.

## Trabajo Futuro

- Muchas plataformas requieren ser implementadas en el IFARHU pero, por motivos culturales de la Institución, se imposibilita la introducción en otras áreas operativas tal como debería realizarse. La DTI ha determinado que es requerido un alto esfuerzo de cambio cultural en como la Institución percibe a la DTI, para que se comprenda que la DTI juega un rol clave en la Institución, no solo desde una perspectiva operativa, mas también desde una perspectiva estratégica.
- De igual forma, solicitar al Despacho Superior retomar nuestras recomendaciones para que, a través de la Dirección de Planificación o como una oficina vinculada al Despacho Superior, se cree una PMO para centralizar el proceso de gestión y administración de proyectos.
- Sugerir un cambio de Dirección para la DTI, de Dirección de Tecnología Informática a Dirección de Innovación y Tecnología.
- A nivel de Clave Social, sugerimos que el programa deba incrementar su aplicación a nivel nacional y sugerimos continuar las conversaciones con BioSoft para que el programa pueda llegar a los centros educativos particulares de Panamá.
- Seguir el desarrollo de las plataformas que se encuentran en una producción temprana, especialmente las plataformas de Conecta IFARHU y ALEXIS.
- Incentivar la investigación dentro de la DTI, permitiéndole a los funcionarios de la DTI evaluar proyectos que incorporen tecnología avanzada como Blockchain, Big Data, Analítica de Datos, Machine Learning, Inteligencia Artificial, entre otros.
- Datos Abiertos: Mediante Resolución No. 320-2019-219 se designa a la Dirección de Planificación como el Oficial de Información del IFARHU para coordinar la implementación de Datos Abiertos del IFARHU. Los Datos Abiertos permiten a los ciudadanos generar información y conocimiento a partir de los datos entregados por la Institución. La DTI es parte del comité de Datos Abiertos de la Institución, por lo que se ha encontrado a la espera, por parte de la Dirección de Planificación, de retomar los trabajos orientados a generar un esquema de datos para ser compartidos a través del Portal de Datos Abiertos de Panamá\footnote{\url{https://www.datosabiertos.gob.pa/}}. Queda pendiente a la próxima administración generar los primeros catálogos de datos, trabajo que podría soportarse en el proyecto de Conecta IFARHU y su componente de análisis de datos ya desarrollado.
- A nivel de los kioskos, la implementación de Caja no resultó como teníamos previsto. Todo se debe principalmente al espacio físico en donde se encuentra caja y al proceso relacionado con el pago. Como el espacio físico es reducido, cuando las personas son tantas deben aglomerarse afuera y las pantallas no se encuentran disponibles para su vista. Recomendamos evaluar mover la sección de caja de ubicación, quizás a otro piso, o mover los kioskos de atención para ser utilizados en los procesos de Crédito Educativo (Piso 8). Igualmente, replicar la implementación de los kioskos en regionales como Panamá Norte, Panamá Oeste - La Chorrera, Panamá Oeste - Arraiján, Chiriquí - David y Veraguas - Santiago, para iniciar.
- Abarcar más trámites a través de Panamá en Línea, mediante la incorporación de otros servicios ya disponibles a través de los API disponibles del proyecto de Conecta IFARHU. Se podrían agregar servicios relacionados con las becas, como conocer sobre un pago.
