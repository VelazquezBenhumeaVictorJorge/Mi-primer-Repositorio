**Innovacción virtual | Summer Cloud**
# Mi-primer-Repositorio

# Introducciòn a los aspectos básicos de Azure

**¿Que es la nube Azure?**
Azure es una plataforma de informática en la nube con un conjunto de servicios que se amplía continuamente para ayudarle a crear soluciones que satisfagan los objetivos empresariales.

**¿Qué es la informática en la nube?**
Es la entrega de servicios informáticos a través de Internet, lo que se conoce como la nube.

**¿Por qué suele ser más barato usar la informática en la nube?**
- Reducir los costos operativos.
- Ejecutar la infraestructura de forma más eficaz.
- Escalar a medida que cambien las necesidades empresariales.

**¿Qué es Azure?**
Azure es un conjunto de servicios en la nube en expansión constante que ayudan a la organización a cumplir los desafíos empresariales actuales y futuros

**¿Qué es Azure Portal?**
Azure Portal es una consola unificada basada en web que proporciona una alternativa a las herramientas de línea de comandos. Con Azure Portal, puede administrar la suscripción de Azure mediante una interfaz gráfica de usuario.

**¿Qué es Azure Marketplace?**
facilita la conexión entre los usuarios y los partners de Microsoft, proveedores de software independientes y nuevas empresas que ofrecen sus soluciones y servicios, optimizados para ejecutarse en Azure


**Categorías de Azure**

- Proceso                                   
- Bases de datos
- Redes                                     
- Web
- Almacenamiento                            
- Internet de las cosas (IoT)
- Movil                                     
- Macrodatos
- INTELIGENCIA ARTIFICIA                   
- DevOps


#  Conceptos fundamentales de Azure


**Nube pública**
- No hay gastos de capital para escalar verticalmente.
- Las aplicaciones pueden aprovisionarse y desaprovisionarse rápidamente.
- Las organizaciones solo pagan por lo que usan.


**Nube privada**
- Debe adquirirse hardware para el inicio y el mantenimiento.
- Las organizaciones tienen un control total de los recursos y la seguridad.
- Las organizaciones son responsables del mantenimiento y las actualizaciones del hardware.


**Nube híbrida**
- Proporciona la máxima flexibilidad.
- Las organizaciones determinan dónde se van a ejecutar sus aplicaciones.
- Las organizaciones controlan la seguridad, el cumplimiento o los requisitos legales.
- 

**¿Cuáles son algunas de las ventajas de la informática en la nube?**

- Alta disponibilidad
- Escalabilidad
- Elasticidad
- Agilidad
- Distribución geográfica
- Recuperación ante desastres

**¿Qué son los modelos de servicio en la nube?**
Si hace tiempo que tiene conocimientos sobre la informática en la nube, es probable que haya visto los acrónimos PaaS, IaaS y SaaS de los diferentes modelos de servicio en la nube. Estos modelos definen los diferentes niveles de responsabilidad compartida de un proveedor de nube y un inquilino de nube.


**IaaS (Infraestructura como servicio):**
Su objetivo es ofrecer un control completo sobre el hardware que ejecuta la aplicación. En vez de comprar hardware, con IaaS, se alquila.

**PaaS (Plataforma como servicio):**
PaaS proporciona las mismas ventajas y consideraciones que IaaS, pero ofrece algunas ventajas adicionales que es importante conocer.

**SaaS (Software como servicio):**
Software que se hospeda y administra de forma centralizada para usted y sus usuarios o clientes. Normalmente se usa una versión de la aplicación para todos los clientes y la licencia se obtiene mediante una suscripción mensual o anual.


#  Descripción principal de la arquitectura de Azure

Azure asigna y controla los recursos de forma inteligente dentro de cada región para garantizar que las cargas de trabajo están bien compensadas.

**Regiones de Azure especiales**
Azure tiene regiones especializadas que se pueden usar al crear las aplicaciones, en lo referente al cumplimiento normativo o a aspectos legales. 

**US DoD (centro) US Gov Virginia, US Gov Iowa y más:** 
Estas regiones son instancias físicas y lógicas con aislamiento de red de Azure para asociados y agencias de la administración pública de EE. UU. Estos centros de datos están operados por personal estadounidense sometido a evaluación e incluyen certificaciones de cumplimiento adicionales.

**Este de China Norte de China y más:** 
Estas regiones están disponibles gracias a una asociación exclusiva entre Microsoft y 21Vianet, por la cual Microsoft no mantiene directamente los centros de datos.

**¿Qué es una zona de disponibilidad?**
Las zonas de disponibilidad son centros de datos separados físicamente dentro de una región de Azure. Cada zona de disponibilidad consta de uno o varios centros de datos equipados con alimentación, refrigeración y redes independientes. Una zona de disponibilidad se configura para constituir un límite de aislamiento.


**Recurso:** 
Elemento administrable que está disponible mediante Azure. Algunos ejemplos de recursos son las máquinas virtuales (VM), las cuentas de almacenamiento, las aplicaciones web, las bases de datos y las redes virtuales.

**Grupo de recursos:** 
Contenedor que incluye los recursos relacionados para una solución de Azure. El grupo de recursos incluye los recursos que se quieren administrar como grupo. Decida qué recursos pertenecen a un grupo de recursos según lo que más convenga a su organización.


# Exploración de los servicios de Azure Compute

**Azure Virtual Machines:**
puede crear y utilizar máquinas virtuales en la nube. Estas máquinas virtuales proporcionan una infraestructura como servicio (IaaS) en forma de un servidor virtualizado y se pueden usar de muchas formas.

- Control total sobre el sistema operativo (SO).
- Capacidad de ejecutar software personalizado.
- Usar configuraciones de hospedaje personalizadas.


**Azure App Service:**

App Service permite crear y hospedar aplicaciones web, trabajos en segundo plano, back-ends móviles y API RESTful en el lenguaje de programación que prefiera, sin tener que administrar la infraestructura. 


**¿Qué son los contenedores?**

Los contenedores son un entorno de virtualización. Al igual que la ejecución de varias máquinas virtuales en un solo host físico, se pueden ejecutar varios contenedores en un solo host físico o virtual. 

**Azure Functions**

El uso de Azure Functions es ideal si le preocupa solo el código que ejecuta el servicio, pero no la infraestructura o la plataforma subyacentes.Las funciones escalan automáticamente según la demanda, para que sean una opción sólida cuando la demanda es variable

**Azure Logic Apps:**

Las aplicaciones lógicas ejecutan flujos de trabajo diseñados para automatizar escenarios empresariales y compilados a partir de bloques lógicos predefinidos.Todos los flujos de trabajo de aplicación lógica de Azure comienza con un desencadenador, que se activa cuando se produce un evento específico o cuando hay nuevos datos disponibles que cumplen determinados criterios. 


**Azure Virtual Desktop:**

Azure Virtual Desktop en Azure es un servicio de virtualización de escritorios y aplicaciones que se ejecuta en la nube. Permite que los usuarios usen una versión hospedada en la nube de Windows desde cualquier ubicación. Azure Virtual Desktop funciona en dispositivos como Windows, Mac, iOS, Android y Linux.



# Exploración de los servicios de red de Azure

**Aspectos básicos de Azure Virtual Network:**

Las redes virtuales de Azure proporcionan las importantes funcionalidades de red siguientes:

- Aislamiento y segmentación
- Comunicación con Internet
- Comunicación entre recursos de Azure
- Comunicación con los recursos locales
- Enrutamiento del tráfico de red
- Filtrado del tráfico de red
- Conexión de redes virtuales

**Aspectos básicos de Azure VPN Gateway:**

Puertas de enlace de VPN
Una puerta de enlace de VPN es un tipo de puerta de enlace de red virtual. Las instancias de Azure VPN Gateway se implementan en instancias de Azure Virtual Network y habilitan la conectividad siguiente:

- Conectar los centros de datos locales a redes virtuales a través de una conexión de sitio a sitio.
- Conectar los dispositivos individuales a redes virtuales a través de una conexión de punto a sitio.
- Conectar las redes virtuales a otras redes virtuales a través de una conexión entre redes.


**Aspectos básicos de Azure ExpressRoute:**

ExpressRoute le permite ampliar las redes locales a la nube de Microsoft mediante una conexión privada con la ayuda de un proveedor de conectividad. Con ExpressRoute, puede establecer conexiones con servicios en la nube de Microsoft, como Microsoft Azure y Microsoft 365.


### Conectividad con los Servicios en la nube de Microsoft
ExpressRoute permite el acceso directo a los siguientes servicios en todas las regiones:

- Microsoft Office 365
- Microsoft Dynamics 365
- Servicios de proceso de Azure, como Azure Virtual Machines
- Servicios en la nube de Azure, como Azure Cosmos DB y Azure Storage

### Modelos de conectividad de ExpressRoute
ExpressRoute admite tres modelos que puede usar para conectar la red local con la nube de Microsoft:

- Ubicación de CloudExchange
- Conexión Ethernet de punto a punto
- Conexión universal


# Exploración de los servicios de Azure Storage

### Disk Storage
Disk Storage proporciona discos para Azure Virtual Machines. Las aplicaciones y otros servicios pueden acceder a estos discos y usarlos cuando sea necesario, igual que se haría en escenarios locales. 

### Azure Blob Storage
Azure Blob Storage es una solución de almacenamiento de objetos para la nube. Puede almacenar grandes cantidades de datos, como datos de texto o binarios.

### zure Files
Azure Files ofrece recursos compartidos de archivos totalmente administrados en la nube a los que se puede acceder mediante los protocolos del Bloque de mensajes del servidor y Network File System (versión preliminar). 

**Niveles de acceso de blobs**

- Nivel de acceso frecuente: optimizado para almacenar datos a los que se accede con frecuencia (por ejemplo, imágenes para el sitio web).
- Nivel de acceso esporádico: optimizado para datos a los que se accede con poca frecuencia y que se almacenan al menos durante 30 días (por ejemplo, las facturas de los clientes).
- Nivel de acceso de archivo: conveniente para datos a los que raramente se accede y que se almacenan durante al menos 180 días con requisitos de latencia flexibles (por ejemplo, copias de seguridad a largo plazo).


### Las siguientes consideraciones se aplican a los distintos niveles de acceso:

- Solo los niveles de acceso frecuente y esporádico se pueden establecer en el nivel de cuenta. El nivel de acceso de archivo no está disponible en el nivel de cuenta.
- Los niveles frecuente, esporádico y de archivo se pueden establecer en el nivel de blob durante la carga o después de esta.
- Los datos del nivel de acceso esporádico pueden tolerar una disponibilidad ligeramente inferior, pero aun así requieren una gran durabilidad, una latencia de recuperación y unas características de rendimiento similares a las de los datos de acceso frecuente. En el caso de los datos de acceso esporádico, un contrato de nivel de servicio (SLA) con una disponibilidad ligeramente inferior y unos costos de acceso mayores, en comparación con los datos de acceso frecuente, es aceptable a cambio de unos costos de almacenamiento menores.
- El almacenamiento de archivo almacena datos sin conexión y ofrece los menores costos de almacenamiento, pero los mayores costos de acceso y rehidratación de datos.


# Exploración de los servicios de análisis y bases de datos de Azure

















