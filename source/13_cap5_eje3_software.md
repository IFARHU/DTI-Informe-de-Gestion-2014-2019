# Eje 3: Desarrollo de Software y Plataformas Digitales

## Introducción

El **Eje Desarrollo de Software y Plataformas Digitales** definde todos los trabajos realizados en conjunto por personal interno de la DTI o proveedores externos para desarrollar un ecosistema de aplicaciones que promuevan el uso de tecnología para acelarar y mejorar procesos actuales del IFARHU.

Durante esta administración se incentivó al desarrollo de competencias relacionadas con el desarrollo de software, promoviendo el desarrollo en casa de las necesidades del IFARHU y comprendiendo que la capa de aplicación es de suma importancia para el logro de objetivos y la mejora de resultados operativos.

## Sistema Único de Crédito Educativo (Fase 1)

El PETI del IFARHU, mostrado en el Eje 1, informó que los factores y sistemas críticos del IFARHU estaban ligados con los ejes principales del IFARHU: Becas Educativas y Crédito Educativo.

El Crédito Educativo del IFARHU se compone de 4 procesos principales:

- Trámite de Crédito
- Seguimiento de Crédito
- Pago de Crédito (Préstamos)
- Recuperación

De igual forma distintas unidades administrativas son parte de estos procesos, como podríamos mencionar:

- Dirección de Crédito: Principal _Stakeholder_ del proyecto
- Dirección de Finanzas (Presupuesto, Contabilidad, Tesorería, Caja, Pago de Crédito)
- Dirección de Planificación: Para realizar las revisiones de los procesos.
- Oficina de Asesoría Legal
- Juzgado Ejecutor
- Oficina de Auditoría Interna: sobre todo para los procesos asociados con el registro de las devoluciones.
- Dirección de Tecnología: como apoyo operativo.
- Todos los beneficiarios del Proyecto.

La DTI promovió en diversas ocasiones incorporar el Proyecto de Crédito como el proyecto de mayor prioridad del IFARHU, siendo el caso que los sistemas actuales de crédito ya se encontraban muy por encima de su vida útil y requerían acciones y cambios urgentes.

La DTI realizó una auditoría de los proyectos que fueron realizados para la actualización del Sistema de Crédito, los cuales fracasaron anteriormente, con especial énfasis a los proyectos **IFASYS-CLEARPATH** (2004-2009) y el proyecto **Sistema de Gestión de Cobros** (2009-2014).

En base a lo encontrado, la DTI pudo determinar que el fallo y fracaso de los proyectos se debió mayormente por ver el proyecto de Crédito Educativo como un **proyecto de tecnología y no un proyecto de análisis, diseño y reingeniería de los procesos de crédito educativo y, por consiguiente, la unificación de los procesos bajo un único sistema**.

Dado este análisis, la DTI decidió realizar esto como un Programa (agrupación de proyectos) y no un Proyecto individual. Dicho programa debía contener dos proyectos a ser ejecutados secuencialmente:

- Fase 1 del Proyecto: Que realizaría una auditoría completa de todos los procesos de crédito educativo del IFARHU, redefinirían todos los procesos y crearían un documento base para el desarrollo de la segunda fase: el proyecto de desarrollo e ingeniería.
- Fase 2 del Proyecto: Que utilizaría todos los entregables de la Fase 1 del Proyecto y unificaría todos los procesos de forma técnica, habiendo definido todos los parámetros no técnicos del proceso en la Fase 1 y haciendo una auditoría y estudio completo de todo lo requerido para su ejecución.

El presupuesto para la primera fase del proyecto fue aprobado para el año 2018, ejecutando la primera etapa del proyecto en dicho año. Durante el año 2017 la DTI realizó una pre-auditoría para el proyecto.

Los entregables de esta primera fase fueron:

1. Documento de Visión del Sistema Único de Crédito Educativo (SUCE)
1. Análisis, Revisión y reingeniería de todos los procesos del SUCE
1. Documento del diseño de todas las pantallas del SUCE
1. Revisión Financiera de los sistemas actuales de crédito del IFARHU
1. Project Charter del SUCE
1. Arquitectura Física del SUCE

Este trabajo, el cuál duró aproximadamente 14 meses entre el tiempo invertido por parte de la DTI como por el proveedor externo, se puede catalogar como el factor crítico para que el proyecto de crédito educativo se realice de la forma correcta y evitar cualquier fracaso futuro.

Todos los entregables de este proyecto se encuentran anexos a este informe.

## Nuevos Desarrollos y Plataformas

### Cambio de paradigma

Antes de iniciar cualquier proceso, era necesario hacer un cambio de paradigma, en especial con el Departamento de Desarrollo de Sistemas y el Departamento de Procesamiento de Datos.

Tal como se vió en el **Eje 1** se esclarecieron las funciones de ambos departamentos y se determinó el grado de acción de cada uno de ellos.

Paso seguido, se establecieron procesos y formas de trabajo, como veremos en este **Eje 3** más adelante. De igual forma, se incentivó al desarrollo mediante nuevas y modernas prácticas, además de nuevas y modernas tecnologías.

Se crearon mecanismos de colaboración y se empoderó al colaborador de la DTI con un rol más de ingeniero (desarrollador de software) que de técnico (simple programador de software).

Se promovió el desarrollo _in house_ sobre el desarrollo fuera del IFARHU, comprendiendo que las capacidades técnicas del equipo de Desarrollo eran más que suficientes para suplir al IFARHU de la gran mayoría de las plataformas de desarrollo.

### Concurso General y Platanforma de Concursos

La primera plataforma nueva desarrollada por esta administración del IFARHU fue la nueva Plataforma de Concurso General.

![Vista de la Plataforma de Concurso General de Becas 2019. \label{chap5_fig1}](source/figures/chap5_fig1.png){ width=70% }

Para poner un contexto, la aplicación anterior era una aplicación web, desarrollada con VB.NET cerca del año 2012. Dicha plataforma utilizaba SQL Server para la conectividad y almacenamiento de los datos de los participantes.

![Wireframe original de los primeros bosquejos realizados por la DTI en el rediseño y nuevo desarrollo de la Plataforma de Concurso General para 2015. \label{chap5_fig13}](source/figures/chap5_fig13.png){ width=100% }

Distintos problemas encontrados con este esquema fueron los siguientes:

- Al ser VB.NET y SQL Server se requerían distintas licencias, tanto a nivel del Sistema Operativo (Microsoft) como a nivel de las tecnologías (licencia de SQL Server).
- El grado de participación era un tanto bajo. Se presume que mayormente a la usabilidad y experiencia de usuario de la aplicación. La aplicación no era adaptable a teléfonos celulares ni tabletas.
- La publicación y mantenimiento era tediosa, siendo que estaban en servidores físicos en un IDC de la localidad, tal como se comentó en el **Eje 2**.

Durante el mes de diciembre de 2014, el Departamento de Desarrollo de Sistemas desarrolló una nueva y moderna aplicación web, utilizando una tecnología moderna y un esquema de colaboración y de desarrollo moderno. La aplicación estuvo lista en producción para Enero de 2015, primer concurso general asumido por esta administración.

Algunas de las características de esta nueva aplicación fueron las siguientes:

- Se desarrolló utilizando tecnologías libres y abiertas.
- La plataforma reposa sobre un servidor que corre una distribución de Linux.
- Se desarrollo en PHP y con una Base de Datos Maria DB. Ambos de licenciamiento totalmente gratuito.
- Se publicó en la nueva nube pública del IFARHU, descrita en el **Eje 2**.
- Se rediseño completamente de cero la plataforma, con un diseño pensado en pensamiento "mobile first".
- A partir de este diseño, se creó un sistema de template conocido como "Taboga", el cuál sería la guía para todas las plataformas del IFARHU, lo que permite la uniformidad entre todos nuestros aplicativos.
- Se desarrolló en un ecosistema ágil de proyectos y no tradicional. Todo el departamento de involucró en el desarrollo.

![Estadísticas de participación, concursos realizados en el año 2017. \label{chap5_fig15}](source/figures/chap5_fig15.png)

![Estadísticas de participación, concursos realizados en el año 2018. \label{chap5_fig14}](source/figures/chap5_fig14.png)

De los resultados logrados por este nuevo desarrollo podemos manifestar los siguientes:

- Tal como se mencionó en el **Eje 2**, **los costos anuales se redujeron en un 96%**, eliminando completamente cualquier tipo licenciamiento requerido.
- La usabilidad y experiencia de usuario incrementó y mejoró notablemente, lo que trajo a un incremento en los números de participantes y de visitantes del sitio. Durante el año 2014 participaron 26,716 estudiantes en los distintos niveles (primaria, premedia, media, licenciatura y posgrado/maestría).
- Se midieron, a través de Google Analytics, las visitas y los flujos de los visitantes en el sitio.
- A través de la misma plataforma, se tramitaron todos los estudiantes de Discapacidad a nivel nacional.

Esta misma plataforma se utilizó de base para realizar una Plataforma de Concursos mediante la cuál se realizaron distintos concursos entre los años 2014 a 2019, como por ejemplo aquellos orientados a:

- Idioma inglés
- Idioma mandarín
- Distintos idiomas (para la JMJ)
- Turismo y Hotelería
- Recursos Hídricos
- Nuevas Tecnologías
- Aviación
- Medicina
- Universidad Latina, USMA
- Sector Marítimo y Logístico

Gracias a estas plataformas pudieron participar cientos de miles de estudiantes durante estos 5 años de gestión, permitiéndole a personas de todo el país participar sin necesidad de apersonarse a la Institución para entregar sus papeles y ser considerados.

### SIVIFarhu y verificación con T.E.

Otra de las grandes incorporaciones a nuestra plataforma digital o electrónica fue la adquisición del Sistema Interno de Verificación IFARHU (SIVIFARHU) y la interoperabilidad con el Tribunal Electoral (TE) para la validación de los registros al momento del trámite de cualquier tipo de Beca, incluyendo Beca Universal.

Al inicio de esta administración y luego de algunos informes provenientes de la Oficina de Auditoría Interna del IFARHU, se determinaron que cerca de 30 mil estudiantes tramitados en Beca Universal no tenían sus generales correctas.

Un error en sus generales ocasionaban problemas como:

- Imposibilidad de validar las generales de los estudiantes en nuestros sistemas con las generales de los estudiantes en sus cédulas juveniles u otros documentos de identidad personal.
- Si los cheques contenían errores, era muy común la solicitud de corrección de sus generales a través de la DTI y posterior re-impresión de los nuevos cheques. Esto ocasionaba grandes volúmenes de datos a nuestro personal y acarreaba grandes costos para nuestra Institución.
- Los informes de auditoría señalaban que era muy probable la existencia de casos de Beca Universal captados que no correspondían a personas reales o cuyas cédulas de identidad no fuesen correctas.

Dado este panorama, la DTI ideó un plan en 2014 para crear un mecanismo de validación y consumo con el TE de la siguiente manera:

- Se iniciaron las conversaciones con el MEDUCA y el TE para validar el formato en que pudiésemos asegurar las identidades de los estudiantes.
- Se detectó que la forma correcta sería a través del TE.
- Se solicitaría un listado de validación, en base a un listado de todos los becados activos en los distintos programas de becas del IFARHU.
- Estudiantes cuyas generales no correspondiese a las generales del TE sería puesto para revisión y se haría una limpieza masiva de todos los registros, quedando únicamente con los registros 100% validados por nuestro personal.
- Se creó un algoritmo basado en distancia de palabras para determinar si fuesen casos de mal trámite o "errores de dedo". En caso de que así fuese, el sistema automáticamente corregiría los errores en la plataforma.
- Cada nuevo trámite se re-validaría automáticamente con el TE en el momento del trámite. Si las generales coinciden, el trámite se procesaría. De lo contrario, el trámite se rechazaría. Esto no solo validaría la cédula, nombre y apellido si no también edad del becario.
- Todo esto se haría a través de una interfaz (API \footnote{Interfaz de Programación de Aplicaciones, por sus siglas en inglés}) y se unificaría el proceso en un único aplicativo, para que el resto de aplicaciones pudiese utilizar este aplicativo.

Gracias a esta implementación tecnológica, los errores de tramitación son cosas del pasado y las asignaciones a personal de la DTI para corregir dichos problemas son casi inexistentes, ahorrando costos operativos y apoyando al pago oportuno.

### Sistema de Impresión de Carnet

Durante el año 2016, la DTI desarrolló un nuevo Sistema de Carnet, para ser utilizado como el sistema para la impresión de todos los carnets de los distintos beneficiarios de becas del IFARHU.

Dicha plataforma estuvo en funcionamiento durante los años 2016 y 2017 hasta que por recomendación de la DTI, mayormente por costos operativos, se tomó la decisión en que se solicitarían las cédulas juveniles para los trámites del IFARHU.

El motivo de esto era en base a tres elementos:

1. El costo de los consumibles para realizar los nuevos carnets era extremadamente costoso.
1. Igualmente era complicado mantener estos consumibles en inventario, mayoritariamente por el mecanismo para realizar las compras en el estado.
1. Esto, de igual forma, obligaría a los estudiantes a estar registrados civilmente ante el TE, lo que facilitaría igualmente nuestro trabajo.

> **Nota:** Este proyecto se archivó a partir del año 2017.

### Taboga

El sistema visual desarrollado para el Concurso General y basado en tecnología web de última generación fue extraído y puesto en su propio proyecto. El mismo se le dió el nombre de "Taboga".

Taboga es un sistema de _front-end_ para el desarrollo de los aplicativos de uso interno y público del IFARHU. Utiliza las mejores prácticas definidas por el estándar para aplicaciones web gubernamentales de la AIG \footnote{Resolución No. 55 de 01 de Marzo, 2011, publicado en Gaceta Oficial No. 26749-A}.

![Vista de la documentación de Taboga. \label{chap5_fig2}](source/figures/chap5_fig2.png){ width=70% }

Gracias a Taboga, el IFARHU ha podido desarrollar una serie de proyectos, productos y aplicaciones con el mismo _look and feel_, permitiéndole a sus usuarios una experiencia similar y uniforme con todos sus aplicativos.

Como parte interesante, Taboga fue publicado y liberado de forma pública por la DTI del IFARHU y hecho público en la plataforma de GitHub\footnote{https://github.com/ifarhu/taboga}, siendo (según nuestro conocimiento) el primer proyecto gubernamental panameño publicado en GitHub bajo licencia MIT \footnote{https://github.com/twbs/bootstrap/blob/master/LICENSE}.

![IFARHU ganó dos categorías en los premios nacionales para la Innovación Gubernamental durante el año 2016. \label{chap5_fig8}](source/figures/chap5_fig8.jpg){ width=100% }

Gracias a su desarrollo, el IFARHU ganó un premio de innovación en 2016 \footnote{http://innovacion.gob.pa/noticia/2721}. Todo el desarrollo de este proyecto fue hecho por el equipo y personal de la DTI.

### Sitio Web IFARHU

![Sitio web del IFARHU en 2014. \label{chap5_fig3}](source/figures/chap5_fig3.png){ width=90% }

El sitio web del IFARHU en 2014 se encontraba atrapado en el tiempo. El IFARHU mantenía un sitio desfasado, que no cumplía con los más mínimos y necesarios estándares web, tal como se muestra en la Figura \ref{chap5_fig3}.

Igualmente, la información dentro del sitio no se encontraba actualizada y el diseño era poco menos que amigable.

La DTI hizo un análisis completo del sitio web del IFARHU y determinó una nueva estructura y diseño, utilizando Taboga como base y entendiendo las nuevas necesidades del público meta del IFARHU.

En tan solo algunos meses de trabajo, el IFARHU desarrolló una nueva imagen, moderna y amigable, responsiva (disponible para dispositivos móviles), fácil de mantener y actualizar, mediante un panel de administración simple y sencillo.

![Sitio web del IFARHU en 2019. \label{chap5_fig4}](source/figures/chap5_fig4.png){ width=90% }

Todo el desarrollo se realizó utilizando tecnologías libres y abiertas, como PHP y Wordpress como sistema de manejo de contenidos (CMS).

Gracias al desarrollo de este nuevo sitio web, el IFARHU ganó un premio de innovación en 2016 como mejor sitio gubernamental de Panamá \footnote{http://innovacion.gob.pa/noticia/2721}. Todo el desarrollo de este proyecto fue hecho por el equipo y personal de la DTI.

### Administrador de Becas 2.0

El IFARHU desarrolló en 2012 un nuevo sisstema para centralizar todos los procesos relacionados con Becas, entendiendo que el proceso de becas se compone de distintos sub-procesos a su vez:

- Trámite de Becas
- Seguimiento de Becas
- Pago de Becas

De estos procesos, los procesos administrativos de becas (trámite y seguimiento) se realizarían a través de una plataforma única, conocido como el **Administrador de Becas**.

Dicho desarrollo se realizó en su debido tiempo con tecnología que, al día de hoy, se encuentra desfasada y en miras a perder cualquier tipo de soporte y validez.

Según el PETI del IFARHU, todos los procesos y sistemas relacionados con becas son parte de los sistemas críticos de IFARHU \footnote{PETI del IFARHU, según lo planteado en el Eje 1}. Dadas estas circunstancias, fue importante desarrollar un nuevo sistema de becas de IFARHU con tecnología nueva y moderna y que, además, soportase las nuevas medidas de verificación cruzada con el TE.

A través del desarrollo de esta nueva plataforma la DTI pudo otorgarle mayores acciones a cada uno de los funcionarios que están relacionados con los distintos sub-procesos de Becas, esto reduciendo las acciones que requirieran el apoyo de DTI.

A nivel de tecnología, el IFARHU pudo logar los siguientes objetivos:

- Modernizar completamente el diseño del sistema, utilizando Taboga. De esta forma homologamos el sistema a un sistema similar a los ya existentes.
- Se migró el desarollo de Visual Basic (un lenguaje totalmente desfasado) a C# y se utilizó ASP.NET MVC, un _framework_ mucho más robusto y moderno.
- A nivel de _front-end_, se desarrollaron varios módulos utilizando Vue.js\footnote{https://vuejs.org/}, un _framework_ de última generación para desarrollar aplicaciones reactivas.

Estas nuevas incorporaciones permitieron que el desarrollo fuese más rápido, moderno y amigable.

A nivel funcional, esta nueva aplicación incorporó dos nuevos flujos que no existían anteriormente:

- Consultas de beneficios históricos y vigentes, en una misma pantalla.
- Impresión de Actas.
- Completa revisión de los trámites con los registros del Tribunal Electoral.

Se mejoraron también todos los procesos ya existentes en la versión 1.0 de dicha plataforma.

### Sistema de Beca Universal

Al igual que la modernización del sistema de Administrador de Becas 2.0, el Sistema de Beca Universal sufrió cambios y mejoras.

El nuevo aplicativo de Beca Universal permitió todas las funcionalidades del aplicativo anterior y se agregaron dos características escenciales:

- Verificación con Tribunal Electoral para todos los trámites.
- Asignación de Resolución: de acuerdo a si es Apertura, Clave Social o Cheque.
- Gestión de todos los procesos relacionados con Clave Social.

### Sistema de Conciliación Bancaria

Auditorías realizadas por la Oficina de Auditoría Interna del IFARHU y algunas recomendaciones de la Contraloría General de la República (CGR) mostraron que uno de los inconvenientes más grandes con los pagos, con mayor énfasis de los pagos de Becas y Beca Universal, son con la verificación a nivel de la conciliación de las cuentas y pagos, en relación con las emisiones de los mismos en los sistemas de emisión de pagos del IFARHU (Sistema de Planillas).

El IFARHU desarrolló, mediante un desarrollo externo, el Sistema de Conciliación Bancaria.

Atendiendo los requerimientos solicitados por las áreas involucradas se desarrolló una aplicación con los siguientes módulos:

**a) Módulo 1: Módulo de Carga de cheques girados por IFARHU:** Módulo que permita procesar un cuyo contenido sea el detalle de cheques emitidos por el IFARHU. En este sentido el modulo debe permitir una validación de los registros a procesar y procesamiento en lote.  

**b) Módulo 2: Módulo de carga de reporte de cheques de banco:** Este módulo permitirá la carga y proceso de archivos de cheques enviados por el banco. El mismo realizará la validación de los datos del archivo con la información de la digitalización de los cheques. Se generarán consultas donde se pueda obtener y exportar información de inconsistencias.

**c) Módulo 3: Módulo de análisis e inconsistencias:** El análisis de inconsistencia del software debe de ser una alternativa amigable y útil para las necesidades de los departamentos de contabilidad, Finanzas y Tesorería. En este módulo, se realizarán las diferentes funcionalidades con respecto al cruce de información de los cheques girados por el IFARHU y los reportados por el banco. El resultado de este módulo arrojará la información resumen y detalle de:

- Cheques Pagados
- Cheques en Circulación
- Inconsistencias
- Cheques Anulados

El módulo podrá manejar lotes de información de acuerdo a fechas de corte, especificación de lotes o mensualmente.

**d) Módulo 4: Módulo de Anulaciones:** En este módulo se deberán registrar, actualizar y procesar:

- Anulaciones manuales de cheques
- Anulaciones por caducidad de cheque

**e) Módulo 5: Módulo de registros de conciliación bancaria** Este módulo permitirá el registro, consulta y actualización de la información referente a la conciliación por fecha, así como la impresión del mismo.

**f) Módulo 6: Módulo de digitalización** Este módulo permitirá capturar su imagen por medio de un Scanner que nos permita tener acceso a la misma desde el sistema.

**g) Módulo 7: Módulo de Reportes:** Este es un módulo capaz de ofrecer la facilidad de generar reportes que atiendan a las necesidades requeridas de las áreas involucradas.

Por medio de este módulo se deben de generar los siguientes informes:

- Cheques en circulación
- Listado de Cheques pagados por el banco
- Listado de Cheques Anulados
- Listado de Inconsistencia de Cruce
- Resumen de Cruce
- Listado de Cheques Caducados a un rango de fecha dado.

**h) Módulo 8: Módulo de Seguridad:** Este módulo debe de integrar mecanismos de seguridad para manejo y uso exclusivo del personal asignado a la administración de la solución y revisión de las bitácoras.

Dicho sistema se puso en funcionamiento a finales del año 2017 y desde entonces corresponde a la Dirección de Finanzas y el Departamento de Contabilidad utilizar dicho sistema y asegurarse de utilizar el sistema para apalancar sus distintas funciones.

### IFARHU Verificar

Siendo parte de los distintos pagos de Becas y Beca Universal a nivel nacional, la DTI pudo detectar algunas anomalías en el proceso de entrega de los pagos a los beneficiarios, los cuales se realizan al menos tres veces al año de manera presencial en todos los centros educativos a nivel nacional.

![IFARHU Verificar - Aplicación Móvil del IFARHU para verificar los pagos y beneficios. \label{chap5_fig5}](source/figures/chap5_fig5.jpg){ width=90% }

Al evaluar el proceso de pago en los distintos centros, notamos que el proceso se manejaba de forma en gran parte manual y que, por error de trámite, podían darse casos en que los pagos no se pudiesen localizar, principalmente por errores de:

- Grado
- Nivel educativo
- Centro

Cuando los pagos no se encontraban, se solicitaba al estudiante que se apersonara a la Sede del IFARHU más cercana, fuera del día de pago. El problema con este mecanismo es que iría en contra del "pago oportuno", obligación del IFARHU.

La DTI determinó que, mediante un desarrollo a la medida y exponiendo ciertos servicios de forma pública y a través de la nube pública del IFARHU (visto en el Eje 2), se podría desarrollar un aplicativo para consultar las generales de los pagos, según su cédula.

Se hicieron dos iteraciones de este aplicativo:

- Primero se hizo una versión preliminar, totalmente basado en Web. Esto se desarrollo en tan solo un fin de semana para permitir las consultas el lunes que iniciaban los pagos. Esta versión utilizaba los datos exportados y cargados cada cierto tiempo.
- En 2019 se hizo una aplicación nativa para móviles (solamente disponible en Android) que utiliza los datos reales que se aplican todas las noches al sistema. Esta versión se muestra en la Figura \ref{chap5_fig5}.

### Conecta IFARHU

> **Nota:** Al desarrollo de este Informe de Gestión, el proyecto de Conecta IFARHU se encuentra en un _Beta Cerrado_. Se estima que para finales del mes de mayo el proyecto entrará en un _Beta Público_ y posterior lanzamiento público.

![IFARHU Verificar - Aplicación Móvil del IFARHU para verificar los pagos y beneficios. \label{chap5_fig6}](source/figures/chap5_fig6.png){ width=90% }

Conecta IFARHU es el primer proyecto del IFARHU desarrollado desde la perspectiva del beneficiario final del IFARHU.

La idea de este aplicativo surge precisamente del PETI del IFARHU, según lo detallado en el Eje 1. La idea base de Conecta IFARHU es permitir los siguientes servicios, de forma escalonada:

- Conocer los datos de tus beneficios actuales en el IFARHU, si eres beneficiario directo.
- Conocer los datos los beneficios de tus representados.
- Verificar los pagos de tus beneficios o los beneficios de tus representados.
- Realizar todo esto a través de una plataforma abierta de información.

Todo esto a través de un único punto de acceso para toda la información, disponible de forma 24/7/365 para los beneficiarios del IFARHU y que no requieran ir al IFARHU para conocer esta información de primera mano.

El proyecto ha sido desarrollado por el personal de la DTI utilizando tecnología libre y abierta y consideramos que es uno de los proyectos más innovadores que se desarrollaron durante esta administración.

## Políticas y buenas prácticas

### Estandarización del proceso de desarrollo de sistemas

La DTI desarrollo las **"Políticas de Desarrollo de Proyectos de Software"**, mismas aprobadas mediante **Resolución 320-2018-226 de 27 de marzo de 2018**.

Es de nuestro conocimiento que dichas políticas se componen como las primeras políticas orientadas al desarrollo de proyectos nétamente de software, elaboradas por algún organismo gubernamental en Panamá.

El objetivo de dichas políticas es \footnote{Objetivos, según lo señalado en el documento de Políticas de Desarrollo de Proyectos de Software}:

> Presentar de forma clara y simple, todas las medidas, estándares, buenas prácticas, procesos, controles que deben ser llevados a cabo para el desarrollo, mantenimiento o adquisición de nuevos sistemas de información en el IFARHU.

De esta forma, la DTI pudo unificar en un solo lugar políticas para el cumplimiento de:

- La arquitectura del software.
- Tecnologías de desarrollo.
- Documentación.
- Requerimientos de seguridad.
- Validación de sistemas de entrada y salida.
- Proceso de desarrollo de software.
- Firma digital y encriptación.
- Administración de claves.
- Control de versiones.
- Cambios.
- Capacitación.

### Desarrollo ágil

Las políticas del punto anterior también establecen un estándar para el modo en que se desarrollarían los proyectos de software, tanto para proveedores internos como para proveedores externos y es a través de un nuevo paradigma de desarrollo de software basado en desarrollo ágil de software y pensamientos ágiles.

De esta forma, el IFARHU ha podido desarrollar internamente los siguientes proyectos:

- Administrador de Becas 2.0
- Concurso General
- Plataforma de Concursos
- Sitio Web del IFARHU
- Taboga
- Cémaco (sistema de librerías del IFARHU para PHP)
- Catálogos de IFARHU (PHP)
- SIVIFARHU
- IFARHU Verificar
- Conecta IFARHU

De igual forma, se han ejecutado proyectos externos, como el Sistema de Conciliación Bancaria, el cuál se desarrollo con una perspectiva completamente ágil.

![Desarrollo Ágil vs. Tradicional \label{chap5_fig7}](source/figures/chap5_fig7.png){ width=90% }

Para ello, se hizo necesario el desarrollo de competencias y habilidades, pero más importante un cambio de paradigma en el desarrollo de proyectos ágiles de software.

El desarrollo ágil se centra en la **generación de valor** mediante el trabajo en equipo y la comunicación y deja elementos tradicionales a un lado, como el tiempo o el alcance.

### Nuevas tecnologías y lenguajes de desarrollo

La DTI durante esta administración se centró en la generación de capacidades y competencias, además del empoderamiento del equipo de Desarrollo y que el mismo pudiese enfocarse estrictamente en el desarrollo de nuevos sistemas y aplicativos y no al soporte.

Anteriormente la DTI desarrollaba exclusivamente en ASP clásico con lenguaje de desarrollo VB.NET. Ambas tecnologías son consideradas, incluso por Microsoft, como tecnologías en plan de desfase\footnote{https://blogs.msdn.microsoft.com/dotnet/2017/02/01/the-net-language-strategy/}. La intención fue adquirir conocimientos y desarrollar en nuevas y modernas tecnologías, no solo para mantener la operatividad a salvo, si no para que el desarrollo vuelva a ser una actividad demandante e interesante para los colaboradores de la Dirección.

Se han trabajado y se sugiere que los proyectos fueran enfocados en los siguientes lenguajes:

- C#
- PHP 7
- JavaScript (ES6, ES7 y ES8) o TypeScript
- Ruby
- Python
- Java

De igual forma quedó establecido en las Políticas, permitiendo uniformidad absoluta de todo el ecosistema de desarrollo.

## Plataformas implementadas

El IFARHU no solamente se dedicó a desarrollas plataformas y sistemas, igualmente se dedicó a implementar algunos sistemas libres y abiertos, que no generasen costos adicionales a la DTI o al IFARHU, pero que si pudiesen apoyar a la gestión del IFARHU.

### Intranet

La Intranet anterior del IFARHU estaba basada en Microsoft SharePoint y requería una Base de Datos SQL y un servidor basado en Microsoft Server.

![Intranet del IFARHU, según vista en el 2019 \label{chap5_fig8}](source/figures/chap5_fig8.png){ width=90% }

La intranet solamente funcionaba como un centro de información de noticias internas del IFARHU y como un portal para las fechas de cumpleaños de los distintos colaboradores del IFARHU. El resto de características dentro de la Intranet no solamente no eran utilizadas, no fueron implementadas de forma completa.

![Sistema de Intranet ofrecido la Dirección Digital del Gobierno Británico e implementada por el IFARHU \label{chap5_fig9}](source/figures/chap5_fig9.png){ width=90% }

Para evitar costos de licenciamiento asociado, el IFARHU implementó una Intranet utilizando tecnologías libres y abiertas, eliminando cualquier costo de licenciamiento asociado con el funcionamiento de la tecnología.

La Intranet que utiliza el IFARHU es el mismo sistema de Intranet que utilizan todas las instituciones del Gobierno Británico \footnote{https://gds.blog.gov.uk/2013/03/18/intranets-dcms/} y se encuentra desarrollada bajo Wordpress y lenguaje PHP, corriendo sobre una base de Datos MySQL. El costo de operatividad es de B/. 0.00 anuales.

### Wiki (Base de Conocimiento): Confluence

El conocimiento en una herramienta que puede permitir a distintos usuarios entender como realizar procesos constantes y recurrentes.

![Sistema de Base de Conocimiento (Wiki) del IFARHU \label{chap5_fig10}](source/figures/chap5_fig10.png){ width=90% }

A inicios de la Administración 2014-2019 se encontró una gran dificultad para poder obtener en un único lugar todas las documentaciones útiles para los usuarios del IFARHU y de la DTI.

Se implementó un software de clase mundial conocido como Confluence y fabricado por Atlassian, líderes del mercado en estos sistemas.

### Gestión de Proyectos de TI: Jira y Trello

Anteriormente, los proyectos de Software del IFARHU (y otros proyectos) no se manejaban con el apoyo de ninguna plataforma o sistema.

El IFARHU adquirió licencias de Jira Software, sistema que está diseñado para que todos los miembros de tu equipo de software puedan planificar y publicar un magnífico software, así como realizar un seguimiento de él.

A través de Jira, los equipos de desarrollo de IFARHU pueden:

**Planificar** Crear historias de usuario e incidencias, planificar sprints y distrbuir tareas entre el equipo de software.

**Supervisar:** Priorizar y analizar el trabajo del equipo en su contexto y con una completa visibilidad.

**Lanzar:** Realizar lanzamientos con confianza y seguridad, sabiendo que la información que se tiene es siempre la más actualizada.

**Crea informes:** Mejorar el rendimiento del equipo con datos visuales en tiempo real que el equipo puede emplear.

Jira también soporta los marcos de trabajos ágiles como Kanban y Scrum, además de estar perfectamente integrado con el sistema de Confluence (Wiki) y Slack (comunicación).

### Reportes y Tiquetera: OS Ticket

Anteriormente, el IFARHU mantenía al menos 3 sistemas distintos para el recibo de los reportes y tiquetes de los usuarios.

De igual forma, el flujo para que dichos reportes llegaran no era uniforme y para nada homogeneo, algo que discutirmos en el Eje 5.

La SSU asumió completa responsabilidad para el recibo de dichos reportes, pero los mismos debían ingresarse en un único y centralizado sistema.

El IFARHU eliminó las licencias de los otros sistemass e implementó un sistema libre, abierto y de licenciamiento gratuito conocido como osTicket\footnote{https://osticket.com/}, considerado como uno de los mejores de soporte de software gratuitos del mercado.

A través de este sistema, al día de hoy se han registrado y cerrado más de 33 mil incidencias y reportes en el IFARHU, desde su implementación en 2014, permitiendo completa visibilidad y mejorar índices de satisfacción por el servicio del IFARHU\footnote{"Según los resultados de las encuestas de satisfacción de los clientes de la DTI, la inmensa mayoría está satisfecha con nuestro servicio" - PETI del IFARHU - Entregable 1 - Diagnóstico}.

#### Sistema de Dashboard para los Tiquetes

La DTI desarrolló e implementó un Tablero de Mando basado en una tecnología conocida como "Dashing", desarrollada por Shopify y liberó todo el código fuente\footnote{\url{https://github.com/IFARHU/osticket_dashing/}} de dicho proyecto para hacerlo de uso libre y gratuito para cualquier otra entidad que quisiera implementarlo.

![Tablero de Mando de los tiquetes \label{chap5_fig11}](source/figures/chap5_fig11.png){ width=90% }

Este proyecto fue mencionado como un proyecto novedoso en los Premios Nacionales de Innovación Gubernamental en 2016, dentro de la categoría de Proyectos Open Source, solamente superado por IFARHU Taboga.

### Repositorios, Integración Continua y Despliegue Continuo: GitLab y GitHub

Otra de las grandes debilidades a nivel del proceso de desarrollo de software en el IFARHU tuvo que ver a nivel de como los equipos compartían los esfuerzos para trabajar de forma colaborativa un mismo proyecto.

Esta administración implementó un concepto de colaboración y de código compartido entre los distintos desarrolladores de software del IFARHU, promoviendo no solo las mejores prácticas si no también promoviendo prácticas elementales para el mercado laboral de hoy en día.

Se capacitó a todo el personal en técnicas de desarrollo colaborativo y el uso de sistemas de control de versiones, específicamente Git\footnote{https://git-scm.com/}.

Se implementaron de igual forma dos sistemas visuales web y de repositorios de Git:

- GitHub\footnote{https://github.com/ifarhu}: Como sistema principal para todos los proyectos del IFARHU enfocados en liberar el código fuente.
- GitLab\footnote{https://gitlab.com/ifarhu/}: Como sistema principal de repositorio para todos los proyectos privados del IFARHU. Se cuenta con una instalación local y una instalación pública (pero de acceso privado restringido).

Gracias a esta innovación simple, pero con resultados importantes, se pudo:

- Acceder al registro de modificaciones sobre un fichero. Esto nos permite además ver los comentarios asociados a cada modificación y la persona que ha realizado dicha modificación.
- Posibilidad de regresar al estado anterior de un fichero o conjunto de ficheros.
- Desarrollar un esquema de calidad y aprobación de cambios (definido en las Políticas descritas en este eje).
- Crear de ramas para gestionar cambios que finalmente se mezclarán con la rama principal.
- Etiquetar modificaciones concretas. Esto además, acaba desembocando en un DML de ITIL, con lo que conseguimos un repositorio con todas las entregas del producto.
- Permitir y promover la colaboración entre todos los desarrolladores de un mismo proyecto y no dependiendo de que uno de los desarrolladores tenga la voluntad de entregar sus avances.
- Visibilidad y transparencia, dos aspectos elementales en el desarrollo ágil de software.

GitLab también nos funciona como sistema de Integración Continua y sistema de Despliegue Continuo. Ambas características han sido utilizadas constantemente a través del desarrollo del sistema Conecta IFARHU, siendo un caso de éxito.

### Comunicación interna: Slack

![Canal de Comunicación de Slack de la DTI del IFARHU \label{chap5_fig12}](source/figures/chap5_fig12.png){ width=90% }

Otra de las grandes e importantes nuevas incorporaciones ha sido un sistema centralizado de comunicación de la DTI, utilizando Slack\footnote{https://slack.com/}, reconocida como una de las aplicaciones de colaboración y comunicación más utilizadas en los últimos años por equipos de tecnología a nivel mundial.

La intención de Slack no es la de reemplazar la comunicación cara a cara, si no la de otorgar un nuevo canal de comunicación que permite no solamente compartir mensajes, mas también elementos audiovisuales, enlaces a sitios u otras plataformas e incluso integraciones con dichas plataformas.

Un ejemplo claro del uso de Slack con otras plataformas es con los proyectos de Software, mostrando de forma eficiente las actualizaciones en las tareas o cuando un nuevo código, relacionado a una tarea, ha sido desplegado y está pendiente para ser aprobado.

### Nube de archivos: ownCloud

El IFARHU ya poseía una serie de discos conectados a la red (NAS - _Network-attached Storage_), con una serie de carpetas compartidas entre distintos usuarios.

Si bien es cierto y esta es una opción que funciona correctamente, la misma no permite la colaboración de distintas personas en los mismos archivos. Los archivos tampoco se encuentran en cada una de las computadoras que acceden a la carpeta compartida, lo que requiere que cada vez que un archivo sea necesario, la persona que requiere acceso al archivo debe descargar el mismo desde la carpeta compartida y luego modificarlo.

Se implentó ownCloud\footnote{https://owncloud.org/} un potente sistema, de código libre y abierto, muy similar en términos a funcionalidad a Dropbox\footnote{https://www.dropbox.com/}.

Algunas de las funcionalidades de ownCloud son las siguientes:

- Tiene clientes para PC, Mac y Linux
- Igualmente aplicaciones nativas para iOS y Android (sin embargo no las podemos utilizar, al estar en una red privada)
- Permite compartir archivos a través de links públicos (dentro de la red privada)
- Notificaciones
- Colaboración y edición de documentos en línea
- Etiquetados y comentarios
- Calendarios y contactos
- Versionamiento: si alteras un archivo, puedes volver a la versión anterior
- Galerías y vídeos

#### Migración a Nextcloud

ownCloud funcionó perfectamente durante los años 2014 a 2019. En el año 2019 hemos migrado a una opción, basada en ownCloud, llamada Nextcloud\footnote{https://nextcloud.com/}.

Nextcloud es un _fork_\footnote{Una versión de la comunidad, basado en el código fuente original pero que se ha ido modificando y alterando en su propia cuenta y "rama" de desarrollo.} de ownCloud.

Muchos de los desarrolladores originales de ownCloud han migrado a Nextcloud, lo que hace que esta sea una versión con mayores actualizaciones a futuro.

## Trabajo futuro

- **Sistema Único de Crédito Educativo (Fases posteriores): Todo lo concerniente a este proyecto se encuentra en su propio anexo.** Consideramos que este proyecto debe ser la pr
- Seguir incentivando el desarrollo en nuevas tecnologías y bajo nuevos modelos y mecanismos de desarrollo.
- Realizar un trabajo completo en la re-arquitectura y re-ingeniería de los sistemas de bases de datos del IFARHU. En auditorías previas, se determinaron malas prácticas en el diseño actual, sin embargo se requeriría un trabajo titánico para hacer la migración a un esquema adecuado.
- En cuanto al punto anterior, se determinó que la forma más correcta sería migrar las aplicaciones mediante el nuevo desarrollo de muchos de estos aplicativos en forma completa.
- Desarrollar más aplicaciones para el usuario final (nuestros beneficiarios).
- Desarrollar una nueva aplicación de Recursos Humanos. Esta aplicación no fue desarrollada por esta administración debido a que no es un proyecto de prioridad, según lo definido en el PETI.
- Migrar el resto de aplicaciones realizadas en tecnología desfasada (VB, mayoritariamente) a un nuevo esquema de tecnologías, que permita su mejora de forma más ágil.
- Evaluar la incorporación de Firma Electrónica en algunos procesos del IFARHU. La Ley 51 de 22 de julio de 2008, define y regula los documentos electrónicos y las firmas electrónicas y la prestación de servicios de almacenamiento tecnológico de documentos y de certificación de firmas electrónicas y adopta otras disposiciones para el desarrollo del comercio electrónico. La Ley 82 de 9 de noviembre de 2012, otorga al Registro Público de Panamá atribuciones de autoridad registradora y certificadora raíz de firma electrónica para la República de Panamá, modifica la Ley 51 de 2008.
