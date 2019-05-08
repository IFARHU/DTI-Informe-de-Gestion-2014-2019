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

### Expansión de nodos virtuales (HP y DELL)

### Monitoreo y variables de ambiente

Se detectó la imposibilidad de poder medir las variables físicas, o de ambiente, tanto en el Centro de Datos de Planta Central como en los cuartos de comunicación de todas las Sedes y Oficinas Regionales del IFARHU a nivel nacional.

Es por ello que adquirimos un sistema de monitoreo de variables de entorno para medir las siguientes variables de entorno y generar reportes o alertas, de ocurrir alguna anomalía:

- Temperatura
- Humedad
- Humo
- Agua / Inundación

De esta forma, hemos podido detectar de forma segura y reaccionar ante imprevistos, evitando errores costosos a nuestra infraestructura y permitiéndonos preservar la operatividad de la Institución durante estos años.

Actualmente dichas variables de entorno se verifican de forma completa en Sede Central y de forma parcial en las siguientes sedes del IFARHU:

- Bocas del Toro
- Panamá Oeste - La Chorrera
- Colón - Colón
- Chiriquí - David
- Herrera - Chitré
- Los Santos - Las Tablas
- Panamá - Panamá Este
- Panamá - San Miguelito
- Veraguas - Santiago
- Panamá - Panamá Centro - Data Center
- Panamá - Panamá Centro - Piso 16 (Tecnología)

### Instalación de Aires Acondicionados de Precisión

Anteriormente, el Centro de Datos del IFARHU, localizado en Planta Central del IFARHU, contaba con dos aires acondicionados de tipo split, los cuales funcionaban 24/7/365.

A partir de la instalación de los equipos para detectar y medir las variables de entorno, encontramos que tanto la temperatura como la humedad del Centro de Datos del IFARHU no se mantenían ni de forma estable ni en las condiciones propicias para mantener un equipo informático. Es por ello que desarrollamos un proyecto en dos fases, para equipar a nuestro Centro de Datos de equipos de enfriamiento nuevos, con unidades de precisión.

Los equipos adquiridos fueron los siguientes:

- Compu Aire, con mantenimiento de la empresa Panama Hardware
- TrippLite, con mantenimiento de la empresa La Casa de las Baterías

Los aires acondicionados de precisión son sistemas específicos para ser utilizados en centros de datos y tienen la capacidad de crear y generar ambientes de temperatura y humedad regulada. De igual forma mantienen de forma más eficiente la pureza del aire.

Otra gran ventaja de estos aires acondicionados es que permiten la regulación exacta de la temperatura. Un error es pensar que los Centros de Datos deben ser cuartos de frigoríficos, pero es escencial que los mismos puedan mantener una temperatura constante y activa que no supere ni reduzca los umbrales de operatividad definidos.

#### Deshumidificador de aire

De forma paralela y como paleativo a la humedad proveniente del espacio externo al Centro de Datos (al no contar con un ambiente cerrado y controlado externo) se adquirió un pequeño deshumidificador de aire, reduciendo la humedad del centro de datos.

### Limpieza y Acondicionamiento del Centro de Datos

El Centro de Datos cuenta con un piso falso que, por el tiempo desde su instalación y por carencia de limpieza, ha acumulado sucio en la parte inferior del mismo. Se realizó una limpieza profunda del Centro de Datos, con especial énfasis en el área debajo del piso falso.

De igual forma, se realizaron trabajos de pintura en las paredes y en el techo del Centro de Datos para que no existiesen las láminas de cielo raso, tapar cualquier escape de aire en el Centro de Datos y pintura (de color adecuado) para reducir ligeramente las variables de ambiente.

Para mejorar la eficiencia del aire acondicionado y el deshumidificador de aire instalado, se cerró de forma permanente el área operativa del Centro de Datos con respecto a la entrada del Centro de Datos mismo.

Se instaló una separación en vidrio y aluminio, conteniendo de forma completa el área de servidores.

### Incorporación de UPS centralizados (Direcciones Regionales) e Instalación de "Tierra" (Ground)

Gracias a la generación de giras constantes con las distintas sedes del IFARHU se detectaron ciertas anomalías con sus sistemas eléctricos y se definieron tres grupos para su atención.

Anteriormente se instalaban equipos de supresión de voltaje y baterías (UPS) independientes para cada cubículo o espacio de trabajo. Los equipos de comunicación de la regional no se encontraban instalados correctamente desde una perspectiva eléctrica igualmente.

Se realizó:

- Una instalación eléctrica nueva que incorporase _ground_ a la instalación del equipo de comunicación y el gabinete.
- Instalación de un sistema de supresión y respaldo (UPS) central y cableado paralelo para los equipos informáticos de la regional.

> **Nota:** Se hace constar que el trabajo eléctrico de la incorporación del _ground_ pudo realizarse parcialmente con apoyo de la Dirección de Administración del IFARHU pero en algunas ocasiones se realizó con personal externo a IFARHU.

#### Grupo 1 - Prioritario

Se instalaron UPS centralizados en las siguientes regionales en el primer grupo de instalaciones:

1. Coclé - Penonomé
1. Herrera - Chitré
1. Los Santos - Las Tablas

Se escogieron estas regionales principales para el grupo prioritario, debido a que las mismas representaban las regionales con mayor incidentes eléctricos reportados.

Este primer grupo nos permitiría hacer una evaluación de la efectividad de centralizar el sistema de UPS en las regionales y hacer una evaluación monetaria.

#### Grupo 2 - Secundario

Posterior a la primera fase del Grupo 1 - Prioritario, y habiendo hecho las evaluaciones que arrojaron resultados significativamente positivos, listamos las siguientes regionales que están listas para incorporar una unidad de UPS centralizada:

1. Panamá - San Miguelito
1. Panamá - Panamá Norte
1. Chiriquí - David
1. Veraguas - Santiago
1. Colón - Colón

#### Grupo 3 - A futuro

El tercer grupo lo incorporan regionales que requieren trabajos eléctricos por parte del Departamento de Obras Físicas de la Institución (parte de la Dirección de Administración) previo al trabajo por parte de nuestra Dirección en la incorporación de dichas unidades centralizdas.

1. Panamá Oeste - Arraiján
1. Panamá Oeste - La Chorrera

#### Supresores de Voltaje

En las regionales de Changuinola, Chiriquí Grande, David, Panamá Norte, San Miguelito y Centro de Datos de Sede Central, se requirió adquirir e instalar un supresor de tensión (Protector eléctrico) en el panel eléctrico principal donde se suministra energía eléctrica a los equipos informáticos, la instalación de estos equipos tienen la función de contrarrestar las variaciones o sobre tensiones que afectan los equipos (Routers, switches, central telefónica, laptops, impresoras, entre otros), comunicaciones y el trabajo  (Consultas, tramites, entre otras funciones) diario de los usuarios internos de la institución, tanto en la atención a los usuarios externos.

Se instalaron los siguientes equipos y en las siguientes Oficinas:

- Bocas del Toro (Changuinola): 1 Supresor de tensión 50 kA por modo, 100 kA por fase.
- Bocas del Toro (Chiriquí Grande): 1	Supresor de tensión 50 kA por modo, 100 kA por fase.
- Chiriquí (David): 1 Supresor de tensión 50 kA por modo, 100 kA por fase.
- Panamá Norte: 1 Supresor de tensión 50 kA por modo, 100 kA por fase.
- San Miguelito: 1 Supresor de tensión 50 kA por modo, 100 kA por fase.
- Planta Central Centro de Datos - Sede Central: 1 Supresor de tensión 50 kA por modo, 100 kA por fase.

La problemática de las frecuentes variaciones y sobre-tensiones en la zona donde están ubicadas cada regional afectan directamente los equipos informáticos y de comunicaciones por estas anomalías eléctricas que se introducen por la red eléctrica donde se alimentan estos equipos; por consiguiente la instalación de un supresor de tensión es de importancia para evitar el daño de los equipos a mencionar: impresoras, computadoras (laptop y escritorio), central telefónica, switches, routers, entre otros.
Esta instalación nos permitirá evitar el daño y aumentar el tiempo de vida de los equipos, ya que son la base del sistema de la institución y son muy costosos, agregando el aumento del tiempo de vida de los mismos, optimizar el rendimiento, mantener la comunicación entre el centro de datos y regionales que podrían ser afectadas, la continuidad del sistema y seguir brindando una excelente atención al cliente. 

### Incorporación de nuevas oficinas regionales

La DTI trabajó en la incorporación de nuevas oficinas regionales del IFARHU, las cuales fueron inauguradas durante la administración 2014-2019.

Se realizó:

- Instalación del equipo informático (computadoras, baterías de respaldo, impresoras, cámaras).
- Cableado estructurado.
- Equipos de comunicación (switches, router).
- Instalación de servicios de comunicación (enlaces).

Las regionales nuevas que requirieron ser equipadas fueron las siguientes:

- Panamá Oeste - Arraiján
- Tortí
- Coclé - Aguadulce
- Bocas del Toro - Chiriquí Grande
- Veraguas - Santiago (mudanza, debido a construcción de nuevo edificio)

### Actualización de equipos

Anualmente, se han ido reemplazando y actualizando los equipos informáticos que han ido requiriendo cambios constantes.

Durante los años 2018 y 2019 se han comprado equipos informáticos para reemplazar los equipos que cumplieron su vida útil, especialmente los que corren sobre sistema operativo Microsoft Windows 7.

Se decidió durante esta administración:

- No comprar más equipos de tipo portatil (laptops).
- Comprar equipos pequeños, que pudiesen ser montados de forma fácil y rápida e idealmente al monitor directamente (lo que los hace más seguros ante robos).

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

Se necesitó crear nuevamente 2 servidores de correo (principal y respaldo) del IFARHU y actualizarlos a la última versión. Uno de ellos debe ser activo y otro pasivo, esto es necesario porque los servidores confrontaron anomalías en su actualización, debido a que muchas veces se perdió el fluido eléctrico y los mismos sufrieron daños en sus librerías y bases de datos internas.

Se requierió la creación de una nueva plataforma de 2 servidores de correos y posterior a la creación se deberá migrar 3 bases de datos de usuarios a la nueva plataforma, las bases de datos ya están creadas: Administrativos, Críticos y VIP en las servidores antiguos.

Se requirió instalar la última versión de Microsoft Exchange 2016 para brindar un mejor servicio a todos los funcionarios que requieren de esta herramienta, a su vez se debe de programar mantenimientos y limpieza de las bases de datos por parte de los usuarios y de los administradores de los servidores constantemente ósea semestralmente o trimestral, para mantener optimas las bases de datos al igual que a los servidores.

El servicio debe se ejecutó por una empresa (TECNASA) certificada que garantizó la instalación y configuraciones según las reglas de ITIL.

Gracias a esta migación, el servicio de correos del IFARHU ha funcionado de forma regular y con las últimas prestaciones de esta versión.

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

### Descentralización del Sistema de Vídeo Vigilancia a nivel nacional

En administraciones previas, el IFARHU invirtió en un Sistema Centralizado de Vídeo Vigilancia para todas sus sedes operativas a nivel nacional. La intención de dicho proyecto se centraba en permitir la convergencia de todas las grabaciones en un único punto: la Sede Central del IFARHU ubicada en Planta Central.

La inversión para este proyecto ascendió a más de B/. 700,000, entre la adquisición de todos los equipos tecnológicos y la mano de obra para la instalación de los mismos.

Durante una auditoría técnica desarrollada por la DTI durante esta administración, encontramos dos grandes problemas al enfoque planteado durante estas inversiones previas:

**Problema #1 – Ancho de Banda Escaso**

Este proyecto no contemplo la débil infraestructura de telecomunicaciones nacional, la cual no permite mediante los canales actuales la transmisión de vídeo y datos en forma paralela en tiempo real.

El impedimento principal para esta infraestructura centralizada es la carencia de suficiente ancho de banda que permita transmitir tantos datos en tiempo real, entendiéndose que la transferencia de datos de vídeo es un proceso que consume gran parte del ancho de banda en cada una de las regionales.

**Problema #2 – Pérdida de comunicación**

Un segundo problema común  son las pérdidas de comunicación con las regionales, lo que ocasiona  directamente que los equipos pierdan comunicación y dejen de realizar su trabajo de grabación de forma abrupta e inmediata.

En numerosas ocasiones, esto ha imposibilitado la grabación de importantes eventos en las sedes regionales del IFARHU, como robos, pérdidas de equipo o documentación de hechos.

Dados estos problemas la DTI ideó un nuevo proyecto para la descentralización total del sistema de vídeo vigilancia a nivel nacional.

Se solicitó la descentralización completa de los sistemas de vídeo vigilancia a nivel nacional, mediante la instalación de equipos de grabación por red (NVR – Network Video Recorder) en cada una de las Oficinas Regionales del IFARHU y según la descripción técnica provista para cada uno de los puntos señalados de igual forma.

Dicho trabajo incluyó:

- Proveer los equipos tecnológicos o informáticos necesarios para la descentralización total de cada una de las regionales listadas, incluyendo planta central.
- Proveer los equipos tecnológicos necesarios para el monitoreo mediante pantallas digitales, donde sea necesario.
- Instalación de dichos equipos en sitio.
- Configuración de dichos equipos y de todas las cámaras locales para la grabación y monitoreo completo de forma local.
- Configuración de las reglas de red necesarias para la operatividad de dicho equipo (el dispositivo de grabación) de forma local y el monitoreo externo, cuando sea necesario.
- Capacitación total de forma operativa técnica al personal de la Dirección de Tecnología Informática.
- Capacitación total de forma operativa final al personal del Departamento de Seguridad de la Institución.
- Garantías totales en piezas y mano de obra, por el periodo que se establezca.
- Mantenimiento preventivo y correctivo, en el periodo que se establezca.

De igual se instalaron los siguientes equipos a nivel nacional, intentando reutilizar (en la mayoría de los casos) la inversión total realizada por el IFARHU en administraciones anteriores.

-------------------------------------------------------------------------------------------------
Regional                                  Descripcinón
------------------------------------     --------------------------------------------------------
Planta Central del IFARHU                2 Grabador NVR de 64 canales y 32TB de almacenamiento. 2 Monitor especial para vídeo vigilancia de 40" o superior, LED, operable a 1080p con salidas DVI, HDMI, VGA. 2 Brazo para pared compatible para el monitor. 2 Cable HDMI para el monitor de 15 pies.

Regional de Chiriquí - Bugaba            1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Chiriquí – Barú              1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de San Félix – Comarca Ngöbe    1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Bocas del Toro – Changuinola 1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Bocas del Toro – C. Grande   1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Veraguas – Soná              1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Panamá Oeste – Coronado      1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Coclé – Aguadulce            1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Colón – Colón                1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Darién – La Palma            1 Grabador NVR de 4 canales y 2TB de almacenamiento.

Regional de Veraguas – Santiago          1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Los Santos – Las Tablas      1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Herrera – Chitré             1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Coclé – Penonomé             1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Panamá Oeste - Arraiján      1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Panamá Oeste – La Chorrera   1 Grabador NVR de 8 canales y 3TB de almacenamiento.

Regional de Panamá – Panamá Norte        1 Grabador NVR de 16 canales y 4TB de almacenamiento.

Regional de Panamá – San Miguelito       1 Grabador NVR de 16 canales y 4TB de almacenamiento.

Regional de Chiriquí – David             1 Grabador NVR de 16 canales y 4TB de almacenamiento.

Regional de Panamá – Panamá Este         1 Grabador NVR de 16 canales y 4TB de almacenamiento.

Regional de Panamá                       2 Monitores de vídeo vigilancia, especial. 2 Montajes para la pared de ambos monitores. 2 Cables HDMI para la conexión de ambos computadores.

Planta Central	                         1 Software de Gestión y Administración de Vídeos, licenciamiento a perpetuidad.

-------------------------------------------------------------------------------------------------

El trabajo se realizó mediante Licitación Pública 2016-1-20-0-99-LP-005491 y los resultados, luego de 3 años de haber realizado los mismos, han sido excelentes y se han corregido ambos problemas encontrados inicialmente por nuestra administración

De igual forma, se eliminó el licenciamiento anual que se tenía contemplado para el sistema anterior, el cuál generaba grandes gastos en licenciamiento a la Institución, siendo que la solución actual no requiere una renovación de los licenciamientos para su operación anual (única inversión al inicio).

### Políticas de Seguridad Informática del IFARHU

El PETI realizado por la DTI arrojó que uno de los factores críticos de éxito para la DTI, a nivel de Seguridad Informática, estaba relacionado con la elaboración de una Política de Seguridad Informática en el IFARHU.

La DTI, mediante la colaboración con consultores externos, personal de la Dirección y apoyo de la CSIRT\footnote{Equipo de Respuesta a Incidentes de Seguridad de la Información, parte de la Autoridad Nacional para la Innovación Gubernamental} pudimos desarrollar las **"Políticas de Seguridad para las Tecnologías de la Información y Comunicaciones (TICS)"**.

Dichas Políticas fueron finalmente aprobadas por **Resolución No. 320-2017-439 de 10 de mayo de 2017**, iniciando en el año 2017 el proceso de comunicación, capacitación y aplicación de las mismas.

Se conoce que el IFARHU es una de las únicas instituciones gubernamentales de Panamá que desarrolló de manera formal una serie de políticas institucionales.

### Unidad de Seguridad Informática

Junto con la creación de las **"Políticas de Seguridad para las Tecnologías de la Información y Comunicaciones (TICS)"** se designó (Asignación Interna) la creación de la Unidad de Seguridad Informática, personal con capacidades y competencias necesarias para verlar por el entendimiento, comunicación, cumplimineto y mantenimiento de todos los equipos y plataformas relacionadas con mantener la operatividad de la Institución en términos de Seguridad Informática.

Se hizo la solicitud a la Dirección de Planificación, de la creación de la Unidad a nivel del esquema jerárquico de la Institución, incluyendo las responsabilidades y objetivos de dicha unidad. Al año 2019, la Dirección de Planificación no ha ejecutado dichas mejoras en el Manual de Organización y Funciones del IFARHU.

### Sistemas Anti-Spam

El crecimiento de la institución hizo que la granja de servidores virtuales presente ciertas limitaciones de espacio por el alto volumen de información que se tiene y los correos basura son una de las causas de que se llene nuestro sistema de almacenamiento de correos.

Se hizo necesario filtrar los correos electrónico, evitando el alojamiento de espacio no deseado en la granja de servidores, implementándole un nuevo Anti-Spam aumentando nuestra capacidad de seguridad y reduciendo posbibles ataques de seguridad proveniente de fuentes no autorizadas de correo electrónico.

Por lo tanto, nuestra institución adquirió un nuevo equipo para prevenir el correo basura. Dicho equipo se implementó en el Centro de Datos central para proteger la capacidad de almacenamiento en disco. Con esta adquisición se minimiza el riesgo de fallas por falta de espacio y se mejora la seguridad de nuestros sistemas, al filtrar correo basura o malicioso, que hoy en día ingresa a nuestros sistemas sin ninguna verificación.

Requerimos este equipo instalado de tipo _appliance_ (hardware) y el sistema completo debía:

- Suministrar el equipamiento necesario para proporcionar el servicio de filtrado de correo y cifrado de correo electrónico a nivel de Gateway, para al menos 5,000 usuarios.
- Ser ofrecida en Hardware Appliance de propósito único para el manejo de correo electrónico.
- Tener disco duro con un mínimo de 60 GB de espacio para el almacenamiento de correos, cuarentenas, y otros.
- Ofrecer protección del servicio de correo en múltiples capas, utilizando técnicas de filtrado de conexiones y escaneo profundo en los mensajes.
- Permitir rechazar el correo no deseado (spam), mediante la previa verificación y comprobación de las direcciones IP de mensajería entrante, en bases de datos especializadas con registros de  sitios considerados como altamente generadores de "spam".

A nivel de protección, la solución cuenta con algunas características a mencionar:

- Posee mínimo 2 capas de protección antivirus.
- Realiza caché de firmas de antivirus localmente y automáticamente actualizable.
- Ofrece protección en tiempo real que bloqueará nuevos spam y los virus en tiempo real, sin tener que esperar nuevas definiciones estén descargadas en el appliance.
- Es capaz de proteger correo electrónico entrante (desde Internet) y correo saliente (hacia Internet).
- Tiene la capacidad de conectarse en tiempo real a una base de datos centralizada en el fabricante para descargar actualizaciones.
- Tiene incorporada protección contra ataques de negación de servicio (DoS).
- Realiza verificaciones de DNS en reversa para proveer protección tipo Anti-Spoofing.
- Establece límites en la tasa de correos enviados y recibidos.
- Tiene la capacidad de soportar múltiples dominios de correo electrónico.
- Establece políticas de correo electrónico por dominio, para correo entrante o correo saliente.
- Tiene la capacidad de establecer perfiles (políticas) granulares  de detección de SPAM.
- Realiza el enrutamiento de correo basado en LDAP.
- Realiza cuarentena de correo entrante y saliente.
- Soporta colas de correo para mensajes fallidos, retardados y no entregables.
- Realiza autenticación para SMTP a través de LDAP, RADIUS, POP3 o IMAP.
- Filtra archivos anexos (attachments) y contenido de mensaje de correo.
- Posee la capacidad de bloquear usando listas RBL de SPAM.
- Filtra por palabra prohibida.
- Entre otras capacidades del sistema.

### Vulnerability Manager

Dentro de todo nuestro plan de Seguridad Informática para el IFARHU, se han adquirido distintas herramientas y tecnologías, para proteger distintos sistemas y mitigar situaciones que puedan atacar la seguridad informática de la organización. Uno de los pilares más importantes para la protección hoy en día es la protección a nivel de usuario final, siendo éste el eslabón más débil dentr de la cadena de seguridad dentro de una organización, es por ello que hemos decidido adquirir una solución precisamente enfocada en atender tres pilares de esta parte de seguridad:

1. Detectar ataques dirigidos a usuarios y dispositivos finales, como malware, exploits y ransomware.
1. Identificar estos ataques, mediante una solución que pueda crecer y aprender por si sola, utilizando incluso mecanismos como inteligencia artificial.
1. Responder a dichos ataques para mitigar los efectos que puedan causarse con ellos.

Mediante el "PROY-26-2018 — Adquisición, implementación y adiestramiento para un sistema de seguridad informática para la  detección y prevención de ataques a dispositivos finales (Endpoint Detection and Response)" se desarrolló un proyecto para contrarrestar con estas situaciones y poder brindar una solución más amplia y enfocada a proteger sistemáticamente y completamente a la organización.

Se adquirió de una solución completa de protección al usuario y dispositivo final (_endpoint_), incluyendo la instalación y entrenamiento de la solución al personal de la DTI.

Dicha solución fue ser desplegada para suplir a una necesidad de aproximadamente 150 clientes activos del IFARHU, entre los cuales podemos mencionar servidores (de tipo Linux y Windows) como clientes (de tipo Windows y macOS).

## Trabajo Futuro

**Arquitectura**

- Considerar el movimiento del Centro de Datos a una Oficina fuera de la Planta Central del IFARHU o la creación de un Centro de Datos paralelo.
- Implementar la "Guía para la implementación de un Plan de Recuperación ante Desastres (DRP) para el IFARHU" \footnote{'Guía para implementación de un Plan de Recuperación ante Desastres (DRP) para el IFARHU, Panamá' - Lic. Roberto Chan - Universidad de Panamá - Visitado el 2/5/2019 http://www.repositoriodev.up.ac.pa/358/}, trabajo de investigación realizado por el Lic. Roberto Chan, ex-director de la DTI en la administración 2009-2014.
- Ejecutar el Grupo 2 y Grupo 3 de la instalación de los UPS en las Oficinas Regionales. La instalación del Grupo 2 no se pudo realizar por carencia de presupuesto en los años anteriores.
- Evaluar la modernización y migración de la granja virutal de servidores Dell a una nueva y moderna tecnología.
- Ampliar los contratos de alquiler de impresoras, promoviendo las mismas en distintas sedes regionales de Panamá. Este trabajo se estipuló realizarlo en el año 2019, mas no fue desarrollado por implementación del sistema ISTMO durante los meses de enero a mayo de 2019.
- Realizar un descarte total de las impresoras que, por malgaste en las piezas y su vigencia en el mercado, no pueden ser reparadas.
- Ampliar la granja de servidores HP de forma escalonada, tal como se ha ido realizando, para soportar el crecimiento actual del IFARHU.
- Evaluar la migración de ciertos servicios desde la red interna del IFARHU a la nube privada del IFARHU, basada en Microsoft Azure.

**Redes y Telecomunicaciones**

- Realizar una auditoría completa de los espacios disponibles en cada uno de los segmentos de red y verificar la necesidad de crear nuevos segmentos o redistribuir los ya existentes.
- Adquisición de nuevos equipos de comunicación de _backup_, en caso de que sean necesarios por desperfectos o daños en los equipos actuales.

**Seguridad Informática**

- Promover la creación de la Unidad de Seguridad Informática y la creación del Oficial de Seguridad Informática, con sus respectivas designaciones y funciones bien establecidas.
- Reforzar la capacitación del personal en competencias de seguridad.
- Promover el rol de Agente de Seguridad Informática.
- Asignar funciones no solamente reactivas por parte de esta unidad.
- Desarrollar mejoras en las Políticas de Seguridad, tomando en consideración que las mismas deben ser lo suficientemente flexibles para no amarrarnos tecnológicamente.
