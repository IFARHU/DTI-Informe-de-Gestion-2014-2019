# Eje 3: Desarrollo de Software y Plataformas Digitales

## Introducción

El **Eje Desarrollo de Software y Plataformas Digitales** definde todos los trabajos realizados en conjunto por personal interno de la DTI o proveedores externos para desarrollar un ecosistema de aplicaciones que promuevan el uso de tecnología para acelarar y mejorar procesos actuales del IFARHU.

Durante esta administración se incentivó al desarrollo de competencias relacionadas con el desarrollo de software, promoviendo el desarrollo en casa de las necesidades del IFARHU y comprendiendo que la capa de aplicación es de suma importancia para el logro de objetivos y la mejora de resultados operativos.

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

Gracias a su desarrollo, el IFARHU ganó un premio de innovación en 2016. Todo el desarrollo de este proyecto fue hecho por el equipo y personal de la DTI.

### Sitio Web IFARHU

![Sitio web del IFARHU en 2014. \label{chap5_fig3}](source/figures/chap5_fig3.png){ width=90% }

El sitio web del IFARHU en 2014 se encontraba atrapado en el tiempo. El IFARHU mantenía un sitio desfasado, que no cumplía con los más mínimos y necesarios estándares web, tal como se muestra en la Figura \ref{chap5_fig3}.

Igualmente, la información dentro del sitio no se encontraba actualizada y el diseño era poco menos que amigable.

La DTI hizo un análisis completo del sitio web del IFARHU y determinó una nueva estructura y diseño, utilizando Taboga como base y entendiendo las nuevas necesidades del público meta del IFARHU.

En tan solo algunos meses de trabajo, el IFARHU desarrolló una nueva imagen, moderna y amigable, responsiva (disponible para dispositivos móviles), fácil de mantener y actualizar, mediante un panel de administración simple y sencillo.

![Sitio web del IFARHU en 2019. \label{chap5_fig4}](source/figures/chap5_fig4.png){ width=90% }

Todo el desarrollo se realizó utilizando tecnologías libres y abiertas, como PHP y Wordpress como sistema de manejo de contenidos (CMS).

Gracias al desarrollo de este nuevo sitio web, el IFARHU ganó un premio de innovación en 2016 como mejor sitio gubernamental de Panamá. Todo el desarrollo de este proyecto fue hecho por el equipo y personal de la DTI.

### Administrador de Becas 2.0

### Sistema de Beca Universal

### Sistema de Conciliación Bancaria

### IFARHU Verificar

### Conecta IFARHU

### Conecta Móvil

## Políticas y buenas prácticas

### Estandarización del proceso de desarrollo de sistemas

### Desarrollo ágil

## Plataformas implementadas

### Wiki

Confluence

### Proyectos

Jira

### Repositorios, Integración Continua y Despliegue Continuo

GitLab y GitHub

### Comunicación interna

Slack

### Nube de archivos

ownCloud
