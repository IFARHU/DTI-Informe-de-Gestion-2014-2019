# Eje 5: Operatividad y Mantenimiento

## Introducción

Tal como lo describe nuestro PETI, la DTI del IFARHU se constituye de dos componentes: un componente operativo y un componente estratégico.

El componente operativo debe velar por la operatividad de nuestro ecosistema informático-tecnológico. Por su parte, nuestro componente estratégico deberá velar por la gobernanza y el enfoque de tecnología para el logro de los objetivos institucionales.

El Eje 5 presenta todos los esfuerzos que propiciaron el reforzamiento de la DTI dentro del componente operativo.

## Sección de Servicio al Usuario (SSU)

El catálogo de servicios de la DTI, creación sugerida por el PETI del IFARHU, se compone de distintos servicios ofrecidos por la DTI: desde comunicaciones satelitales hasta plataformas electrónicas.

El IFARHU implementó una cultura de servicio soportada por algunos conceptos provenientes de ITIL\footnote{Information Technology Infraestructure Library} y COBIT \footnote{Control Objectives for Information and Related Technologies}.

> **Nota:** Para implementar de forma exitosa y completa ambos marcos de trabajo (ITIL y COBIT) es necesaria la capacitación y un proyecto enfocado únicamente en dicha implementación. Por tal motivo, la DTI solo se enfocó en crear una cultura de servicio y en la implementación de ciertos procesos definidos en las mismas.

A nivel de ITIL, _Service Support_ y _Service Delivery_ se consideran como el núcleo del marco de trabajo de ITIL. Entre los procesos cubiertos por _Service Support_ se encuentra un proceso especial llamado _Service Desk_. Además, existen los procesos:

- Incident Management
- Problem Management
- Configuration Management
- Change Management
- Release Management

En 2014, analizamos el proceso de creación de incidentes y notamos lo siguiente:

- Los reportes se generaban de forma casi natural: las personas llamaban a cualquier número de la DTI y se generaba un reporte.
- Los reportes no se les realizaba ningún tipo de seguimiento.
- Los reportes podían ser ingresados en cualquier sistema de los existentes (ver Eje 1).
- Los reportes no tenían ningún tipo de criticidad o ningún nivel de escalamiento.
- Había mucho descontento en el proceso en que las incidencias eran atendidas y existían reportes de que las incidencias, aún si eran reportadas, no eran atendidas (siendo imposible validar esta aseveración).

Dada esta situación, la DTI implementó un proceso de _Service Desk_, según lo establecido en ITIL v3. El Service Desk representa la cara de cualquier departamento de TI, donde un usuario busca un especialista  para resolver una petición. El Service Desk juega un rol muy importante dentro de todo el escenario de ITIL ya que su objetivo es garantizar la oferta de servicios de TI que han sido acordados con el usuario mediante la realización de actividades que están relacionadas con el resto de los procesos de ITIL.

Se hizo un análisis de personal y se creó una sección (con Asignación Interna) y se definió la misma mediante el nombre de **"Sección de Servicio al Usuario"**. Al personal de dicha sección se le capacitó en términos básicos de administración de servicios, informática básica y atención al cliente.

**Se desingó a esta área operativa como la única vía de comunicación para el reporte de cualquier incidencia, entre nuestra Dirección y cualquier otro Departamento o Dirección a nivel nacional.**

Se hizo una jordnada de capacitación y comunicación al personal interno del IFARHU, definiendo un flujo y proceso para el recibo de solicitudes, descrito en este capítulo más adelante.

![Comunicación de como realizar un reporte de incidente en la Intranet \label{chap7_fig1}](source/figures/chap7_fig1.png){ width=90% }

Se aportaron instructivos (en panfletos, correos e Intranet) de como reportar incidentes a la DTI según se muestra en la Figura \ref{chap7_fig1}, incluyendo una serie de preguntas frecuentes en la Wiki, según se muestra en la Figura \ref{chap7_fig2}.

![Instructivo y preguntas frecuentes de la SSU en la Wiki \label{chap7_fig2}](source/figures/chap7_fig2.png){ width=90% }

De igual forma se definió un Acuerdo de Nivel de Servicio (conocido como SLA) y se implementó una plataforma para el recibdo de dichas solicitudes, conocido como OS Ticket y mostrado en el Eje 3.

Hasta el mes de mayo de 2019 se han procesado más de 33 mil solicitudes únicas, distribuídas de la siguiente manera:

- 61% correspondiente al Departamento de Procesamiento de Datos
- 22% correspondiente al Departamento de Soporte Técnico
- 7% que no requirieron ser asignados a un departamento específico para su resolución (atendidos en primera línea de soporte)
- 5% correspondiente al Departamento de Desarrollo de Sistemas
- 5% correspondientes a los Departamentos de Telecomunicaciones, Unidad de Seguridad Informática.

## Zonas de Mantenimineto y calendarios de visitas periódicas

La DTI del IFARHU desarrolló un esquema de zonas para las visitas periódicas de mantenimiento preventivo por personal de los Departamentos de Soporte Técnico y Telecomunicaciones. Esto ha reducido el número de incidentes reportados en cada una de nuestras regionales, gracias al mantenimiento constante de los equipos de forma periódica.

Las zonas de atención son las siguientes:

---------------------------------------------------------------------------
Zona               Periodicidad            Sedes a ser atendidas
--------------     ------------------      --------------------------------
Zona 1             Cada 3 meses            Chiriquí (David), Bugaba, Barú, San Félix, Bocas del Toro, Changuinola, Isla Colón, Chiriquí Grande

Zona 2             Cada 3 meses            Veraguas (Santiago), Soná

Zona 3             Cada 3 meses            Herrera, Los Santos

Zona 4             Cada 3 meses            Aguadulce, Penonomé, Coclesito (Centro Estudiantil)

Zona 5             Cada 2 meses            Panamá Oeste (La Chorrera, Arraiján, Coronado)

Zona 6             Cada 2 meses            Panamá Norte, Panamá Este, San Miguelito, CAIPI, Colón

Zona 7             Cada 3 meses            Darién (La Palma), Emberá-Wounaan, Guna Yala, Tortí

---------------------------------------------------------------------------

Igualmente, se determinó un responsable principal por cada zona y se le notificó al personal de cada regional (y se publicó en la Intranet) el calendario exacto de las visitas, para que los Directores Regionales pudiesen saber las fechas de visitas de nuestro personal.

## Enlaces técnicos de regionales

El IFARHU tiene presencia a nivel nacional a través de distintas direcciones y oficinas regionales en todo el país.

La DTI se compone de un grupo reducido de ingenieros, técnicos y personal operativo. Abarcar todo el país para atender de forma oportunda y según lo descrito en el SLAs del IFARHU es una tarea titánica y casi imposible.

Es por ello que la DTI en 2017 desarolló un proyecto de designación de enlaces técnicos en distintas regionales para poder atender problemas de primera línea en las regionales sin necesidad de requerir la visita de un técnico especializado por Planta Central.

> **Nota:** Dicho personal pertenece a las oficinas regionales y desempeñan otras labores. Se escogió el personal con nociones de informática (algunos con estudios universitarios en el área) y se les entrenó y capacitó.

Se escogieron 4 colaboradores del IFARHU a nivel nacional para recibir capacitaciones de CompTIA A+, lo que les permitiría instalar, actualizar, reparar, configurar, solucionar problemas, optimizar, realizar mantenimientos preventivos de los sistemas de hardware de los equipos informáticos y su funcionamiento básico.

![Enlaces Regionales del IFARHU capacitándose en cableado de redes. \label{chap7_fig3}](source/figures/chap7_fig3.jpg){ width=90% }

Mismo personal fue entrenado igualmente en cableado de red básico, como muestra la Figura \ref{chap7_fig3}.

Estas capacitaciones nos aportó en reducir los reportes recibidos a nivel nacional, además de los costos necesarios en movilización a las distintas provincias y sedes del IFARHU para atenciones básicas primarias.

## Creación de contratos de mantenimiento y alquiler a nivel nacional

Tal como se describió en el **Eje 2**, se crearon contratos de mantenimiento de impresoras a nivel nacional y alquiler (impresoras) a nivel de Planta Central.

Sin embargo, estos no fueron los únicos de contratos de licenciamiento que se procuraron mantener durante esta administración. Los contratos de mantenimiento y licenciamiento que se mantienen actualmente en el IFARHU son los siguientes:

-------------------------------------------------------------------------------------------
Nombre                             Proveedor actual        Vigente hasta
------------------------------     ------------------      --------------------------------
PROY-2-2019 - Servicio de          Panama Hardware         Diciembre 2019
mantenimiento preventivo
y correctivo al sistema
centralizado de energía
(UPS) del Centro de Datos

PROY-3-2019 - Servicio de          Panama Hardware         Diciembre 2019
mantenimiento al Sistema de
Aire Acondicionado del 
entro de Datos (COMPU-AIRE)

PROY-4-2019 - Servicio de Datos    Cable Onda              Diciembre 2019
para lugares de difícil acceso

PROY-5-2019 - Servicio de          Cable Onda y CWP        Diciembre 2019
Internet y Enlaces de
Comunicaciones

PROY-6-2019 - Licencia Anual       Soluciones Seguras      Marzo 2020
para el Sistema de Cortafuegos
del IFARHU

PROY-7-2019 - Soporte y            Soluciones Seguras      Marzo 2020
mantenimiento para el sistema
de Cortafuegos del IFARHU
y protección contra SPAM

PROY-8-2019 - Mantenimiento        Canon Panamá            Diciembre 2019
para 39 impresoras (Canon)

PROY-9-2019 - Alquiler de 30       Canon Panamá            Diciembre 2019
impresoras en Planta Central

PROY-10-2019 - Servicio de         CWP                     Diciembre 2019
Internet Móvil Inalámbrico

PROY-11-2019 - Mantenimiento y     GSI                     Diciembre 2019
licencias para el sistema de
digitalización documental

PROY-12-2019 - Mantenimiento       Casa de las Baterías    Diciembre 2019
de 3 unidades de Aire
Acondicionado de Respaldo
para el Centro de Datos

PROY-13-2019 - Licencias de        Data Security Solutions Diciembre 2019
Auditor de Active Directory
(JiJi)

PROY-14-2019 - Licencias para      Data Security Solutions Enero 2020
sistema de monitoreo (PRTG)

PROY-15-2019 - Licencias para      WICOSY                  Mayo 2020
sistema basado en VMWare y
RedHat

PROY-16-2019 - Mantenimiento a     RICOH                   Diciembre 2019
impresoras RICOH a nivel
nacional

PROY-17-2019 - Adquisición de       Xplor                  Diciembre 2019
Licencia, Mantenimiento y
Soporte de Sistemas para
Kioskos

PROY-18-2019 - Licencias de         Soft Net               Abril 2020
Adobe Creative Cloud

-------------------------------------------------------------------------------------------

Los mantenimiento que no pudieron realizarse, debido a que no se encontraban en el proceso de renovación durante el cierre de esta administración, son los siguientes:

-------------------------------------------------------------------------------------------
Nombre                             Proveedor actual        Vigente hasta
------------------------------     ------------------      --------------------------------
Licencias de Tableau y             Excibit Corp.           Octubre de 2019
Tableau Server

Renovación de licencias de         Logic Studio            Diciembre de 2019
Jira y Confluence

Renovación de licencias            TECNASA                 Octubre de 2019
Microsoft

-------------------------------------------------------------------------------------------

> **Nota:** Todos los mantenimientos que requirieron ser renovados para el año 2019 fueron renovados con vigencia total de 2019, procurando la operatividad institucional a nivel tecnológico-informático.

## Procesos y Flujos

### Plantilla para Proyectos de Tecnología

La DTI creó una plantilla única para todos los proyectos de tecnología del IFARHU y solicitó que todos los proyectos del IFARHU a nivel de la DTI fueran compartidos a través del sistema ownCloud, descrito en el Eje 3, lo que nos permite tener visibilidad, transparencia y permite la colaboración entre todos los involucrados en crear dicho proceso.

La plantilla de proyectos de la DTI llamada "Acta de Constitución de Proyectos" es una versión pequeña que intenta describir la misión y la visión del proyecto mediante el desarrollo de los siguientes puntos:

- Definición del Proyecto: Resumen del proyecto y el alcance del mismo.
- Justificación del Proyecto: Define los motivos por los cuales este proyecto es necesario en la Institución y como la misma se beneficiaria por los resultados entregados luego del desarrollo del proyecto.
- Descripción de la necesidad: Explica los requerimientos técnicos completos y el alcance técnico de los trabajos dentro del proyecto. Involucra también la misión y la visión del proyecto.
- Especificaciones técnicas: Lista las especificaciones técnicas que debe cumplir la necesidad como mínimo.
- Requerimientos del oferente: Lista de requerimientos que son de estricto cumplimiento por parte de los oferentes interesados en participar en el proyecto.

Este documento está homologado con la Ley de Contrataciones Públicas, por lo que es utilizado directamente para las licitaciones públicas del IFARHU.

También ha funcionado como un documento de entrada para el personal de Control Fiscal de la Contraloría General de la República y la Dirección de Finanzas, siendo que describe de forma justificada la inversión requerida por la Institución y los beneficios de desarrollar el proyecto.

### Recibo de solicitudes e incidentes

ITIL no indica un proceso de atención determinado para las solicitudes de servicios de TI \footnote{Book Service Support, Office of Government Commerce, UK, 2000.}. Sin embargo nos menciona los siguientes aspectos a considerar:

- Se debe involucrar a todas las partes relevantes
- Se debe asignar tiempo suficiente y recursos
- Deben considerarse posibles alternativas
- Se debe suministrar nuevos materiales de referencias basados en análisis de incidentes y problemas El diseño del proceso de atención utilizado en la herramienta está basado en el trabajo diario. Dicho  proceso debe considerarse desde el envío de la solicitud de TI (incidente) hasta la resolución de la misma.
- Debe existir una herramienta tecnológica que contemple, como mínimo, incidentes y solicitudes de cambio (RFCs) en los servicios ofrecidos.

Se definió igualmente los posibles estados de criticidad de una solicitud (normal, alta o urgente) el proceso de escalamiento de dichas solicitudes (a distintos estados) y el escalamiento automático de las mismas, según la naturaleza de las solicitudes.

Todos estos procesos fueron documentados, capacitados y entregados tanto a personal de la DTI como hecho público a través de nuestros sistemas de Base de Conocimiento (Wiki).

Para las solicitudes que son recibidas por medio físico (a través de notas y memorandos) se estableció un flujo simple, mediante la incorporación de un sello que se incorpora en cada una de las solicitudes físicas recibidas.

El sello contiene un pequeño formulario, llenado a mano, con la siguiente información:

- Número de solicitud (tiquete)
- Criticidad (Normal, Alta, Urgente)
- Departamento que corresponde (Procesamiento, Soporte, Desarrollo)

Al recibir dicha solicitud, la misma pasa a la SSU para ser ingresada en el sistema y se le indica el número de solicitud asignada. Esto es útil para cuando alguien quiera verificar el estado de una solicitud recibida por memorando, a través del memorando físico podemos detectar cualquier comentario relacionado con la solicitud.

Estas medidas fueron notificadas a todo el personal, inicialmente a través del Memorando DTI 490-2014-520 y rectificadas en Memorando DTI 490-2015-230.

### Solicitud de credenciales y permisos

Con anterioridad, las credenciales para distintos aplicativos, correo electrónico o incluso las tarjetas para el acceso físico a ciertas áreas, eran recibidos de manera informal.

Detectamos casos en donde se solicitaban credenciales para funcionarios en trámite o sin número de posición. Por ello establecimos un esquema de solicitud de credenciales, manejado casi en su mayoría de forma física, mediante un formulario que debe ser llenado al momento de solicitar cualquier credencial.

Este formulario debe ser aprobado por la DTI y la Oficina Institucional de Recursos Humanos, donde se debe ingresar el número de posición del funcionario.

La DTI, según las Políticas de Seguridad Informática, tiene la última potestad de dar o no los permisos solicitados para un personal en particular.

### Informe de visitas de regionales

Se creó un nuevo formulario y formato para los técnicos de soporte y de telecomunicaciones, luego de cualquier visita a las Direcciones Regionales del IFARHU.

### Notificaciones de Trabajos a Realizar

Se creó un formato (plantilla) para la notificación de labores que pudiesen realizarse a nivel de la DTI y que pudiesen afectar, parcial o totalmente, la operatividad del IFARHU.

![Vista del formato para notificar un trabajo a ser realizado por la DTI y que afectarían ciertos servicios. \label{chap7_fig4}](source/figures/chap7_fig4.png){ width=70% }

Igualmente se ideó un mecanismo para poder desplegar dichas notificaciones a todo el personal, mediante una dirección de correo electrónico para dichos fines comunicativos.

### Formato de Pruebas: Desarrollador de Software

Se creó un formato de prueba de conocimientos y competencias para las posiciones de Ingenieros y Desarrolladores de Software del IFARHU.

Dicha prueba fue aplicada a todo el personal que participó del proceso de ingreso al IFARHU. La misma consta de preguntas teóricas sobre conceptos escenciales de programación y programación a objetos, de una sección de desarrollo de algoritmos y una sección de consultas de bases de datos mediante sentencias SQL.

### Solicitud de publicación de contenidos web

El Despacho Superior del IFARHU, mediante Memorando DG-110-2016-1520, estableció la norma mediante la cual se establece que cualquier contenido a ser publicado en el sitio web público del IFARHU debía ser aprobado por personal asesor o parte de la Dirección General del IFARHU.

Por tal motivo, y considerando que los contenidos con fines comunicativos por parte del IFARHU son canalizados a través de la Oficina de Relaciones Públicas del IFARHU\footnote{Según los objetivos de dicha Oficina, establecidos en el Manual de Organización y Funciones del IFARHU} la Dirección de Tecnología Informática estableció un formulario para la solicitud de publicación de nuevos contenidos para la web pública del IFARHU.

Dicho formulario físico debe contener la firma autorizada de:

- Personal solicitante de la publicación de dicha información.
- Personal de la Dirección General del IFARHU.
- Personal de la Oficina de Relaciones Públicas del IFARHU.

Una vez recibida dicha solicitud, se realizaría una solicitud de un reporte a través del sistema de atención del IFARHU y se designaría al personal de la DTI para la publicación del contenido (si el mismo procede).

Dicho flujo se realiza igualmente para ciertos contenidos a ser publicados públicamente del IFARHU, como fondos de pantalla o noticias especiales en la Intranet.

## Trabajo Futuro

- Trabajar con la OIRH para crear la figura de enlaces técnicos regionales o poder contratar a personal anexo a la DTI pero que se encuentre en las oficinas regionales principales y que puedan brindar respaldo a las oficinas aledañas.
- Mejorar la capacitación del personal de enlace de la DTI en las oficinas regionales.
- Desarrollar una capacitación integrada en temas tecnológicos orientado al personal del IFARHU, apoyándonos en instituciones como INADEH. Este proyecto se intentó realizar durante esta administración, pero por cambios administrativos en INADEH el proyecto quedó desamparado.
- Aumentar la operatividad de los planes de alquiler de impresoras, los cuales han dado excelentes resultados, a las oficinas regionales del IFARHU a nivel nacional, con especial énfasis en las Direcciones Provinciales y Comarcales, las que usulamente desarrollan el mayor de los flujos.
- Seguir con las visitas periódicas, ya que los resultados han sido efectivos en disminuir los incidentes reportados en las distintas direcciones regionales.
- Uno de los grandes problemas que hemos tenido en esta administración está orientado a la compra de equipos para mantener en inventario, en referencia a cuestionamientos por la Oficina de Control Fiscal de la Contraloría General de la República. La DTI no ha podido mantener un _stock_ de inventario de equipos que frecuentemente se requieren, como UPS, computadoras (laptops y de escritorio), componentes (memorias, discos duro, placas madre, etc.), baterías de reemplazo en UPS, impresoras, entre otros. Esto ocasiona un problema ya que, de requerir un equipo, debemos hacer la solicitud cuando la necesidad se de y no antes. **Esto afecta la operatividad y el servicio que como DTI brindamos, ya que en muchos casos debemos esperar varios meses para poder suministrar los equipos que se están requiriendo, lo que ocasiona retrasos en brindar nuestros servicios e incumplimientos en los acuerdos de niveles de servicio (SLA)**.
- Solicitarle a la OIRH una mejor comunicación con la DTI en temas de manejo de personal, especialmente cuando se den contrataciones y destituciones.
