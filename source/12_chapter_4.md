# Eje 2: Arquitectura Tecnológica, Telecomunicaciones, Seguridad e Infraestructura

## Introducción

El **Eje Arquitectura Tecnológica, Telecomunicaciones, Seguridad e Infraestructura** define todos los esfuerzos relacionados con la arquitectura física y tecnológica del IFARHU y la DTI, parte elemental y escencial de la operatividad, no solamente de la DTI, si no completamente del IFARHU.

Durante administraciones pasadas, se enfocó de gran forma hacia el desarrollo constante sobre este eje y durante la administración 2014-2019 se desarrollaron modificaciones a las infraestructuras existentes, se expandieron las mismas y se coordino una mejora gradual (sobre le margen de tiempo) que nos permitiese crecer a un ritmo constante.

## Arquitectura Tecnológica y Infraestructura

### Ecosistema libre y abierto

Uno de los cambios más fundamentales, a diferencia de las administraciones anterioes, fue la incorporación de otros ambientes, fuera de los predominantemente orientados a infraestructuras privativas de Microsoft.

Se incorporaron servidores, aplicaciones, lenguajes y tecnologías libres y abiertas, especialmente soportados por sistemas operativos basados en Linux. En la actualidad, se cuentan con servidores que corren algunas de las siguientes distribuciones:

- Ubuntu Server 14.04 LTS
- Ubuntu Server 16.04 LTS
- Ubuntu Server 18.04 LTS

Estos servidores permanecen tanto en nuestra red privada como en nuestra red pública.

### Microsoft Azure

Otro de los cambios más importantes fue la equiparación e incorporación de un nuevo ecosistema de nube pública para soportar todos los servicios públicos del IFARHU, con especial énfasis en los que permiten la distribución de los siguientes servicios públicos del IFARHU:

- Sitio web del IFARHU
- Sistema de Concurso General
- Sistema de Otros Concursos
- Aplicaciones de Verificación
- Aplicaciones de Interoperabilidad

Para ello, se evaluaron las disponibilidades actuales en el mercado panameño y se movilizó toda la infraestructura, anteriormente en un Data Center físico, a la nube de Microsoft Azure.

Gracias a este cambio **el IFARHU redujo en un 96% los gastos** relacionados con mantener estas plataformas operativamente activas y con un **99.99% de _uptime_** para todas las aplicaciones, además de contar con mayor facilidad y flexibilidad para el manejo y administración de todos sus recursos en la nube, permitiéndole mayor agilidad para desarrollar nuevas aplicaciones o servicios públicos.

### Expansión de nodos virtuales (HP)

<!-- TODO -->

### Expansión de nodos virtuales (Dell)

<!-- TODO -->

### Monitoreo y variables de ambiente

<!-- TODO -->

Se detectó la imposibilidad de poder medir las variables físicas, o de ambiente, tanto en el Centro de Datos de Planta Central como en los cuartos de comunicación de todas las Sedes y Oficinas Regionales del IFARHU a nivel nacional.

Es por ello que adquirimos un sistema de monitoreo de variables de entorno para medir las siguientes variables de entorno y generar reportes o alertas, de ocurrir alguna anomalía:

- Temperatura
- Humedad
- Humo
- Agua / Inundación

De esta forma, hemos podido detectar de forma segura y reaccionar ante imprevistos, evitando errores costosos a nuestra infraestructura y permitiéndonos preservar la operatividad de la Institución durante estos años.

Actualmente dichas variables de entorno se verifican de forma completa en Sede Central y de forma parcial en las siguientes sedes del IFARHU:

- Chiriquí - David
- Veraguas - Santiago
- Coclé - Penonomé

### Instalación de Aires Acondicionados de Precisión

<!-- TODO -->

Anteriormente, el Centro de Datos del IFARHU, localizado en Planta Central del IFARHU, contaba con dos aires acondicionados de tipo split, los cuales funcionaban 24/7/365.

A partir de la instalación de los equipos para detectar y medir las variables de entorno, encontramos que tanto la temperatura como la humedad del Centro de Datos del IFARHU no se mantenían ni de forma estable ni en las condiciones propicias para mantener un equipo informático. Es por ello que desarrollamos un proyecto en dos fases, para equipar a nuestro Centro de Datos de equipos de enfriamiento nuevos, con unidades de precisión.

Los equipos adquiridos fueron los siguientes:

-
-

Los aires acondicionados de precisión son sistemas específicos para ser utilizados en centros de datos y tienen la capacidad de crear y generar ambientes de temperatura y humedad regulada. De igual forma mantienen de forma más eficiente la pureza del aire.

Otra gran ventaja de estos aires acondicionados es que permiten la regulación exacta de la temperatura. Un error es pensar que los Centros de Datos deben ser cuartos de frigoríficos, pero es escencial que los mismos puedan mantener una temperatura constante y activa que no supere ni reduzca los umbrales de operatividad definidos.

#### Deshumidificador de aire

De forma paralela y como paleativo a la humedad proveniente del espacio externo al Centro de Datos (al no contar con un ambiente cerrado y controlado externo) se adquirió un pequeño deshumidificador de aire, reduciendo la humedad del centro de datos.

### Limpieza y Acondicionamiento del Centro de Datos

El Centro de Datos cuenta con un piso falso que, por el tiempo desde su instalación y por carencia de limpieza, ha acumulado sucio en la parte inferior del mismo. Se realizó una limpieza profunda del Centro de Datos, con especial énfasis en el área debajo del piso falso.

De igual forma, se realizaron trabajos de pintura en las paredes y en el techo del Centro de Datos para que no existiesen las láminas de cielo raso, tapar cualquier escape de aire en el Centro de Datos y pintura (de color adecuado) para reducir ligeramente las variables de ambiente.

Para mejorar la eficiencia del aire acondicionado y el deshumidificador de aire instalado, se cerró de forma permanente el área operativa del Centro de Datos con respecto a la entrada del Centro de Datos mismo.

Se instaló una separación en vidrio y aluminio, conteniendo de forma completa el área de servidores.

### Mejora del sistema eléctrico del centro de datos

### Incorporación de UPS centralizados (Direcciones Regionales) e Instalación de "Tierra" (Ground)

Gracias a la generación de giras constantes con las distintas sedes del IFARHU se detectaron ciertas anomalías con sus sistemas eléctricos y se definieron dos grupos para su atención.

Anteriormente se instalaban equipos de supresión de voltaje y baterías (UPS) independientes para cada cubículo o espacio de trabajo. Los equipos de comunicación de la regional no se encontraban instalados correctamente desde una perspectiva eléctrica igualmente.

Se realizó:

- Una instalación eléctrica nueva que incorporase _ground_ a la instalación del equipo de comunicación y el gabinete.
- Instalación de un sistema de supresión y respaldo (UPS) central y cableado paralelo para los equipos informáticos de la regional.

> **Nota:** Se hace constar que el trabajo eléctrico de la incorporación del _ground_ pudo realizarse parcialmente con apoyo de la Dirección de Administración del IFARHU pero en algunas ocasiones se realizó con personal externo a IFARHU.

#### Grupo 1 - Prioritario

<!-- TODO -->

Se instalaron UPS centralizados en las siguientes regionales en el primer grupo de instalaciones:

1. 

#### Grupo 2 - Secundario

<!-- TODO -->

### Actualización de equipos

<!-- TODO -->

### Adquisición de planes de alquiler para impresoras y unificación de los equipos

Con anterioridad, la Institución contaba con al menos 6 marcas distintas de equipos (HP, Xerox, Lexmark, RICOH, Canon) creando una tarea difícil contar con mantenimiento constante para dichos equipos.

Durante esta administración, a nivel del mantenimiento y gestión impresoras, se realizaron las siguientes labores:

1. Se disminuyó la cantidad de impresoras por departamentos. Notamos que anteriormente se tenían muchos equipos individuales, por lo que se intentó centralizar en los Departamentos los equipos de impresión.
1. Se establecieron marcas con las que se trabajarían, en espcial RICOH y Canon, siendo ambas marcas con las que contábamos mayormente en el momento en que se tomó la decisión.
1. Se crearon contratos de mantenimiento completo para todos los equipos RICOH y Canon a nivel nacional, permitiéndonos disminuir la cantidad de equipos que, por desgaste, quedaban fuera de operación.
1. Para las áreas con mayor volumen y de alto impacto para la Institución (Finanzas, Becas, Recursos Humanos, Administración) se adquirieron contratos de alquiler. La ventaja de los contratos de alquiler es que obliga a la empresa al reemplazo del equipo y consumibles (como tóner) de forma automática y sin costo adicional.

Los resultados de dichas acciones han ocasionado cierta disconformidad en las áreas operativas del IFARHU, acostumbradas a tener una impresora a un lado, pero ha disminuído notablemente el número de incidentes reportados en relación a las impresoras y, de igual forma disminuir los costos operativos y de compra de nuevo equipo.

Notamos igualmente que al disminuir la cantidad de equipos, pero comprar equipos de mayores prestaciones y agregarles un contrato de mantenimiento, la vida útil de los equipos ha aumentado.

### Actualización de Sistema de Correos Electrónicos

<!-- TODO -->

Durante el año 2018 se hizo una actualización completa a la última versión del sistema de correos electrónicos. De igual forma, en años anteriores, se creó un servidor paralelo para no contar con un único servidor para tal fin.

## Redes y Telecomunicaciones

### Sistemas alternos de comunicación

En todas las Direcciones Provinciales y Sede Central de Panamá, con disponibilidad para ello, se aseguró contar con dualidad en las comunicaciones con los dos principales proveedores de comunicaciones: Cable & Wireless y Cable Onda / Telecarrier.

De igual forma, se hicieron las adecuaciones a los equipos de comunicación para permitir ambas interfaces y determinar o detectar, según la disponibilidad de los servicios de comunicación, cuál de los dos enlaces u operadores escoger para enrutar el tráfico.

### Reconfiguración de la Red Nacional del IFARHU a nivel nacional

La AIG otorga al IFARHU los siguientes segmentos de red:

- `10.252.164.0/22`
- `10.252.168.0/22`
- `10.252.104.0/22`
- `10.252.176.0/22`

![Direccionamiento de Red - Sede Central. \label{chap4_fig2}](source/figures/chap4_fig2.png)

![Direccionamiento de Red - Oficinas Regionales. \label{chap4_fig3}](source/figures/chap4_fig3.png)

Nos pudimos topar en 2015 con regionales que ya habían sobrepasado las cantidades de equipos que podrían conectarse a la red del IFARHU, por lo que se hizo necesario una reconfiguración de la red, alterando el direccionamiento de Red a nivel nacional.

En las Figuras \ref{chap4_fig2} y \ref{chap4_fig3} pueden apreciarse los resultados de la reconfiguración de la red a nivel nacional, tanto en la Sede Central del IFARHU como en sus distintas oficinas a nivel nacional.

### Expansión de las líneas telefónicas a nivel nacional

<!-- TODO -->

### Migración de tecnología satelital (Regionales de Difícil Acceso)

Durante el año 2015, y luego de una auditoría de los servicios ofrecidos y requeridos para mantener la conectividad con las Sedes de Difícil Acceso y Sede Central del IFARHU, se hizo un estudio y evaluación para mejorar las comunicaciones satelitales con dichas regionales.

Al no contar con la posibilidad de interconectar nuestras 3 sedes apartadas a través de métodos tradicionales, como cableado en fibra/cobre o a través de microondas, tenemos que realizar la interconexión a través de un medio satelital.

En las comunicaciones satelitales se generan muchas pérdidas, muchas de ellas debido a la propagación de las señales. A mayor frecuencia de transmisión y recepción, mayor atenuación de las comunicaciones.

![Esquema de conectividad de las regionales de difícil acceso a través de los sistemas de comunicaciones satelitales. \label{chap4_fig1}](source/figures/chap4_fig1.png)

Los satélites comerciales funcionan en tres bandas de frecuencias establecidas, llamadas Banda C, Ku y Ka. Una gran mayoría de las comunicaciones regulares se realizan a través de la Banda Ku, a una frecuencia de 14,0-14,5Ghz (transmisión) y a 11,7-12,2Ghz (recepción), frecuencias muy superiores a las operativas de la Banda C, quien opera en 5,92-6,42Ghz (transmisión) y a 3,7-4,2Ghz (recepción).

Con anterioridad, hemos trabajado bajo Banda Ku, pero nos hemos topado con uno de los grandes enemigos de la Banda Ku: la lluvia y el mal tiempo. Este factor es común en nuestras 3 sedes de difícil acceso, lo que ha ocasionado diversos problemas y fallas de comunicaciones en estas distintas Sedes.

Entre las pérdidas que podemos obtener en estas comunicaciones, podemos destacar:

- Las pérdidas por absorción atmosférica.
- Las pérdidas por atenuación por lluvia.

Es por ello que se realizó un cambio de tecnología satelital de las ya existentes, pasando de Banda Ku a Banda C, evitando las atenuaciones del servicio por absorción atmosférica o lluvia.

> **Nota**: Se hace constar que a partir del año 2019 y por motivos de incorporación del Sistema ISTMO, no se pudo realizar una nueva licitación para contar con la misma calidad del servicio, entendiendo que el mismo requería una autorización especial por parte de la Dirección General de Contrataciones Públicas (DGCP). Para mantener una operatividad del servicio, se tuvo que recurrir a uno de los servicios disponibles a través del Convenio Marco del Portal de Panamá Compra.

### Adquisición de Planes de Internet Inalámbrico

Para apoyar a las gestiones fuera del IFARHU, tanto por personal de la DTI como por personal de otras direcciones como Dirección General, Asesoría de Dirección General, Relaciones Públicas y Compras, el IFARHU adquirió una serie de equipos de comunicaciones inalámbrica por GSM y sus debidos contratos de alquiler y datos.

Dichos equipos se conectan a través de la red celular del operador y permiten la conectividad a distintos equipos por medio de una red WiFi que los mismos exponen.

Gracias a la adquisición de estos equipos se ha podido apoyar al personal en actividades como:

- Ferias Edúcate
- Distintas Ferias (Azuero, La Chorrera, David)
- Pagos de Becas y Beca Universal
- Recepción de documentos de Concurso General

De igual forma, cada departamento de la DTI cuenta con un equipo, para realizar trabajos especiales, en caso de requerirse, sin la necesidad de apersonarse al IFARHU para ello.

La conectividad con la red del IFARHU, a su vez, se realiza mediante la incorporación de mecanismos de seguridad y una red segura (VPN).

### Creación de Central Telefónica con licenciamiento libre y abierto

<!-- TODO -->

Mediante un desarrollo interno con personal de la DTI y consultores externos, se pudo realizar la instalación de un servidor PBX que utiliza tecnología libre y abierta, como Asterisk.

La intención de realizar este trabajo es debido a que cada licencia AVAYA (nuestra Central Telefónica principal) tiene un costo unitario de **XX**, mientras que las líneas 

Hasta el día de hoy contamos con **X** líneas instaladas que utilizan esta tecnología y la calidad del servicio ha sido comparable con las otras dos tecnologías con las que contamos en la actualidad y sin costo alguno más que la compra del equipo telefónico.

## Seguridad Informática

### Políticas de Seguridad Informática del IFARHU

El PETI realizado por la DTI arrojó que uno de los factores críticos de éxito para la DTI, a nivel de Seguridad Informática, estaba relacionado con la elaboración de una Política de Seguridad Informática en el IFARHU.

La DTI, mediante la colaboración con consultores externos, personal de la Dirección y apoyo de la CSIRT\footnote{Equipo de Respuesta a Incidentes de Seguridad de la Información, parte de la Autoridad Nacional para la Innovación Gubernamental} pudimos desarrollar las **"Políticas de Seguridad para las Tecnologías de la Información y Comunicaciones (TICS)"**.

Dichas Políticas fueron finalmente aprobadas por **Resolución No. 320-2017-439 de 10 de mayo de 2017**, iniciando en el año 2017 el proceso de comunicación, capacitación y aplicación de las mismas.

Se conoce que el IFARHU es una de las únicas instituciones gubernamentales de Panamá que desarrolló de manera formal una serie de políticas institucionales.

### Restructuración de los cortafuegos

<!-- TODO -->

### Unidad de Seguridad Informática

Junto con la creación de las **"Políticas de Seguridad para las Tecnologías de la Información y Comunicaciones (TICS)"** se designó (Asignación Interna) la creación de la Unidad de Seguridad Informática, personal con capacidades y competencias necesarias para verlar por el entendimiento, comunicación, cumplimineto y mantenimiento de todos los equipos y plataformas relacionadas con mantener la operatividad de la Institución en términos de Seguridad Informática.

Se hizo la solicitud a la Dirección de Planificación, de la creación de la Unidad a nivel del esquema jerárquico de la Institución, incluyendo las responsabilidades y objetivos de dicha unidad. Al año 2019, la Dirección de Planificación no ha ejecutado dichas mejoras en el Manual de Organización y Funciones del IFARHU.

## Trabajo Futuro

**Arquitectura**

- Considerar el movimiento del Centro de Datos a una Oficina fuera de la Planta Central del IFARHU o la creación de un Centro de Datos paralelo.
- Implementar la "Guía para la implementación de un Plan de Recuperación ante Desastres (DRP) para el IFARHU" \footnote{'Guía para implementación de un Plan de Recuperación ante Desastres (DRP) para el IFARHU, Panamá' - Lic. Roberto Chan - Universidad de Panamá - Visitado el 2/5/2019 http://www.repositoriodev.up.ac.pa/358/}, trabajo de investigación realizado por el Lic. Roberto Chan, ex-director de la DTI en la administración 2009-2014.
- Ejecutar el Grupo 2 de la instalación de los UPS en las Oficinas Regionales. Dicha instalación no se pudo realizar por carencia de presupuesto en los años anteriores.
- Evaluar la modernización y migración de la granja virutal de servidores Dell a una nueva y moderna tecnología.
- Ampliar los contratos de alquiler de impresoras, promoviendo las mismas en distintas sedes regionales de Panamá. Este trabajo se estipuló realizarlo en el año 2019, mas no fue desarrollado por implementación del sistema ISTMO durante los meses de enero a mayo de 2019.
- Realizar un descarte total de las impresoras que, por malgaste en las piezas y su vigencia en el mercado, no pueden ser reparadas.

**Redes y Telecomunicaciones**

- Realizar una auditoría completa de los espacios disponibles en cada uno de los segmentos de red y verificar la necesidad de crear nuevos segmentos o redistribuir los ya existentes.
- Adquisición de nuevos equipos de comunicación de _backup_, en caso de que sean necesarios por desperfectos o daños en los equipos actuales.

**Seguridad Informática**

- Promover la creación de la Unidad de Seguridad Informática y la creación del Oficial de Seguridad Informática, con sus respectivas designaciones y funciones bien establecidas.
- Capacitar al personal en dichas competencias.
