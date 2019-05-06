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
- 5% correspondiente al Departamento de Desarrollo de Sistemas
- 22% correspondiente al Departamento de Soporte Técnico
- 5% correspondientes a los Departamentos de Telecomunicaciones, Unidad de Seguridad Informática.
- 7% que no requirieron ser asignados a un departamento específico para su resolución (atendidos en primera línea de soporte)

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

## Creación de contratos de mantenimiento a nivel nacional

## Procesos y Flujos

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

### Solicitud de credenciales y permisos

Con anterioridad, las credenciales para distintos aplicativos, correo electrónico o incluso las tarjetas para el acceso físico a ciertas áreas, eran recibidos de manera informal.

Detectamos casos en donde se solicitaban credenciales para funcionarios en trámite o sin número de posición. Por ello establecimos un esquema de solicitud de credenciales, manejado casi en su mayoría de forma física, mediante un formulario que debe ser llenado al momento de solicitar cualquier credencial.

Este formulario debe ser aprobado por la DTI y la Oficina Institucional de Recursos Humanos, donde se debe ingresar el número de posición del funcionario.

La DTI, según las Políticas de Seguridad Informática, tiene la última potestad de dar o no los permisos solicitados para un personal en particular.

### Solicitud de publicación de contenidos web
