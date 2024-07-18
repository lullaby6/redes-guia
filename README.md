# Redes

## Índice
- [Tipos de redes de comunicacion](#tipos-de-redes-de-comunicacion)

## To do

- Modelo OSI
- Topologias de red de comunicacion
- Direccionamiento IP
- Enrutamiento IP

## Tipos de redes de comunicacion

## Índice
- [LAN](#lan-red-de-area-local)
- [WAN](#wan-red-de-area-amplia)
- [PAN](#pan-red-de-area-personal)
- [MAN](#man-red-de-area-metropolitana)
- [CAN](#can-red-de-area-de-campus)
- [SAN](#san-red-de-area-de-almacenamiento)

## LAN (Red de Area Local)

### Definicion
- Una LAN es una red de computadoras que interconecta equipos en un área limitada, como una oficina, un edificio o un grupo de edificios cercanos.

### Características principales
- Área geográfica limitada (generalmente menos de 1 km)
- Alta velocidad de transmisión (típicamente de 10 Mbps a 10 Gbps)
- Baja tasa de errores
- Propiedad privada (generalmente pertenece a la organización que la utiliza)

### Componentes típicos
- Computadoras y dispositivos finales (PCs, laptops, impresoras, etc.)
- Switches y/o hubs para conectar los dispositivos
- Routers para conectar la LAN a otras redes
- Cables (Ethernet, fibra óptica) o conexiones inalámbricas
- Servidores (de archivos, de impresión, de aplicaciones, etc.)

### Topologías
- Estrella: Todos los dispositivos se conectan a un punto central
- Bus: Todos los dispositivos se conectan a un cable principal
- Anillo: Los dispositivos se conectan en un círculo cerrado

### Protocolos comunes
- Ethernet (el más común)
- Wi-Fi (para LANs inalámbricas)

### Ventajas
- Alta velocidad de transmisión de datos
- Compartir recursos (archivos, impresoras, conexiones a internet)
- Fácil administración y mantenimiento
- Mayor seguridad al tener control físico de la red

### Usos típicos
- Compartir archivos y recursos
- Comunicación interna (correo electrónico, mensajería instantánea)
- Acceso a aplicaciones compartidas
- Conexión a internet compartida

### Seguridad
- Firewalls para proteger contra amenazas externas
- Control de acceso a la red
- Encriptación de datos (especialmente en Wi-Fi)

### Evolución
- Las LANs modernas son cada vez más rápidas y pueden incluir tecnologías como Power over Ethernet (PoE) para alimentar dispositivos a través del cable de red.

[Volver al inicio](#tipos-de-redes-de-comunicacion)

## WAN (Red de Area Amplia)

### Definición
- Una WAN es una red de computadoras que conecta áreas geográficamente dispersas, pudiendo abarcar ciudades, países o incluso continentes.

### Características principales
- Cobertura geográfica extensa
- Velocidades de transmisión variables (generalmente más lentas que LAN)
- Mayor complejidad en la gestión y mantenimiento
- A menudo utiliza infraestructuras de telecomunicaciones públicas

### Componentes típicos
- Routers para conectar redes locales y dirigir el tráfico
- Switches de capa 3 para enrutamiento
- Módems y líneas de comunicación (fibra óptica, satélite, líneas arrendadas)
- Firewalls y dispositivos de seguridad
- Servidores distribuidos geográficamente

### Topologías
- Punto a punto: Conexión directa entre dos puntos
- Hub and Spoke: Un punto central conectado a múltiples puntos remotos
- Malla: Conexiones redundantes entre múltiples sitios

### Protocolos comunes
- TCP/IP (base de Internet)
- MPLS (Multiprotocol Label Switching)
- Frame Relay (menos común actualmente)
- ATM (Asynchronous Transfer Mode)

### Ventajas
- Conectividad global
- Compartir recursos a larga distancia
- Centralización de datos y aplicaciones
- Soporte para trabajo remoto y oficinas distribuidas

### Usos típicos
- Conexión entre sucursales de empresas
- Acceso a Internet para organizaciones
- Redes de proveedores de servicios de Internet (ISPs)
- Comunicaciones gubernamentales y militares

### Seguridad
- VPNs (Redes Privadas Virtuales) para conexiones seguras
- Encriptación de datos en tránsito
- Sistemas de detección y prevención de intrusiones (IDS/IPS)
Políticas de seguridad rigurosas

### Tecnologías de conexión
- Líneas dedicadas
- Conexiones de banda ancha (DSL, Cable)
- Conexiones satelitales
- Redes móviles (4G, 5G)

### Desafíos
- Mayor latencia debido a las distancias
- Costos más elevados de implementación y mantenimiento
- Dependencia de proveedores de servicios externos
- Complejidad en la resolución de problemas

### Evolución
- Las WANs modernas están adoptando tecnologías como SD-WAN (Software-Defined WAN) para mejorar la gestión y el rendimiento, y están integrando cada vez más servicios en la nube.

[Volver al inicio](#tipos-de-redes-de-comunicacion)

## PAN (Red de Area Personal)

### Definición
- Una PAN es una red de dispositivos electrónicos personales que operan dentro de un rango muy corto, típicamente alrededor de una persona o en un espacio personal.

### Características principales
- Rango muy corto (generalmente menos de 10 metros)
- Normalmente inalámbrica, aunque puede ser cableada
- Baja potencia y bajo consumo de energía
- Centrada en la conectividad de dispositivos personales

### Componentes típicos
- Dispositivos móviles (smartphones, tablets)
- Wearables (smartwatches, auriculares inalámbricos)
- Sensores personales (monitores de ritmo cardíaco, podómetros)
- Computadoras portátiles
- Periféricos (teclados, ratones inalámbricos)

### Tecnologías comunes
- Bluetooth (la más común para PANs)
- NFC (Near Field Communication)
- IrDA (Infrared Data Association, menos común actualmente)
- ZigBee (para aplicaciones de bajo consumo)

### Topologías
- Punto a punto (entre dos dispositivos)
- Estrella (un dispositivo central conectado a varios periféricos- )

### Ventajas
- Facilidad de uso y configuración
- Movilidad y flexibilidad
- Bajo consumo de energía
- Personalización del entorno tecnológico individual

### Usos típicos
- Sincronización de datos entre dispositivos personales
- Conexión de auriculares inalámbricos a smartphones
- Monitoreo de salud y fitness
- Control de dispositivos domésticos inteligentes
Transferencia de archivos entre dispositivos cercanos

### Seguridad
- Emparejamiento seguro de dispositivos
- Encriptación de datos
- Alcance limitado que reduce la exposición a amenazas externas
Controles de acceso (PIN, reconocimiento biométrico)

### Limitaciones
- Alcance muy corto
- Capacidad de red limitada
- Posibles interferencias en entornos congestionados

### Evolución
- Integración cada vez mayor con Internet de las Cosas (IoT)
Mejoras en eficiencia energética y velocidad de transmisión
Desarrollo de nuevos estándares para aplicaciones específicas

### Estándares relevantes
IEEE 802.15 (para PANs inalámbricas)
Bluetooth SIG (Special Interest Group) para especificaciones Bluetooth

### Consideraciones de implementación
- Compatibilidad entre dispositivos de diferentes fabricantes
- Gestión de la coexistencia con otras redes inalámbricas (Wi-Fi, otras PANs)
- Optimización del consumo de batería en dispositivos móviles

[Volver al inicio](#tipos-de-redes-de-comunicacion)

## MAN (Red de Area Metropolitana)

### Definición
- Una MAN es una red de computadoras que abarca un área geográfica más grande que una LAN pero más pequeña que una WAN, típicamente cubriendo una ciudad o un área metropolitana.

### Características principales
- Cobertura geográfica de 5 a 50 km aproximadamente
- Velocidades intermedias entre LAN y WAN
- Puede ser de propiedad privada o pública
- Conecta múltiples LANs dentro de un área metropolitana

### Componentes típicos
- Routers de alta capacidad
- Switches de capa 3
- Líneas de fibra óptica
- Equipos de transmisión inalámbrica (para MANs inalámbricas)
- Servidores distribuidos en la zona metropolitana

### Tecnologías comunes
- Ethernet de alta velocidad (Metro Ethernet)
- SONET/SDH (Synchronous Optical Network/Synchronous Digital Hierarchy)
- WiMAX (para MANs inalámbricas)
- DWDM (Dense Wavelength Division Multiplexing) para fibra óptica

### Topologías
- Anillo (común en redes de fibra óptica)
- Malla (para mayor redundancia)
- Estrella (con un núcleo central conectando sitios remotos)

### Ventajas
- Mayor cobertura que una LAN
- Velocidades relativamente altas
- Capacidad para conectar múltiples organizaciones o campus
- Soporte para una variedad de servicios (voz, datos, video)

### Usos típicos
- Conexión de campus universitarios
- Redes municipales
- Interconexión de sucursales bancarias en una ciudad
- Sistemas de gestión de tráfico urbano
Redes de bibliotecas públicas

### Seguridad
- VPNs para conexiones seguras entre sitios
- Firewalls distribuidos
- Sistemas de detección y prevención de intrusiones
Segmentación de red

### Desafíos
- Coordinación entre múltiples propietarios de infraestructura
- Gestión del ancho de banda en áreas densamente pobladas
- Cumplimiento de regulaciones locales y nacionale- s

### Evolución
- Integración de tecnologías 5G para MANs inalámbricas
Adopción de SDN (Software-Defined Networking) para mejor gestión
Incremento en las velocidades de transmisión

### Consideraciones de implementación
- Planificación cuidadosa de la infraestructura física
- Gestión del espectro radioeléctrico en MANs inalámbricas
- Escalabilidad para acomodar el crecimiento urbano

### Diferencias clave con LAN y WAN
- Mayor que una LAN, pero menor que una WAN en cobertura
- Generalmente más rápida que una WAN, pero puede ser más lenta que una LAN moderna
- Puede ser gestionada por un único operador o entidad, a diferencia de muchas WANs

[Volver al inicio](#tipos-de-redes-de-comunicacion)

## CAN (Red de Area de Campus)

### Definición
- Una CAN es una red de computadoras que interconecta LANs (Redes de Área Local) en un área geográfica limitada, típicamente un campus universitario o un complejo empresarial.

### Características principales
- Cobertura geográfica intermedia entre LAN y MAN (generalmente de 1 a 5 km)
- Alta velocidad de transmisión
- Propiedad y gestión generalmente por una sola organización
- Diseñada para soportar necesidades específicas del campus

### Componentes típicos
- Switches de alta capacidad
- Routers para interconexión de edificios
- Cableado de fibra óptica entre edificios
- Puntos de acceso Wi-Fi para cobertura inalámbrica
- Servidores centralizados y distribuidos

### Tecnologías comunes
- Ethernet de alta velocidad (10 Gbps o más)
- Fibra óptica para conexiones troncales
- Wi-Fi para acceso inalámbrico (802.11ac, 802.11ax)
- VLANs para segmentación lógica de la red

### Topologías
- Estrella jerárquica (común en diseños de campus)
- Anillo (para conexiones entre edificios)
- Malla (para redundancia en conexiones críticas)

### Ventajas
- Alta velocidad y baja latencia en todo el campus
- Gestión centralizada de recursos de red
- Flexibilidad para adaptar la red a necesidades específicas
- Capacidad para soportar una gran variedad de aplicaciones y servicios

### Usos típicos
- Redes universitarias
- Complejos hospitalarios
- Parques empresariales o tecnológicos
- Instalaciones gubernamentales
Grandes campus corporativos

### Seguridad
- Firewalls perimetrales y internos
- Sistemas de autenticación centralizados (como RADIUS)
- Segmentación de red mediante VLANs
Monitoreo y análisis de tráfico en tiempo real

### Desafíos
- Gestión de un gran número de usuarios y dispositivos
- Mantenimiento de la consistencia en la cobertura inalámbrica
- Balanceo entre acceso abierto y segurida- d

### Evolución
- Integración de IoT (Internet de las Cosas) en el campus
Adopción de tecnologías SDN (Software-Defined Networking)
Incremento en la capacidad para soportar aplicaciones de alta demanda (como realidad virtual o streaming de alta definición)

### Consideraciones de implementación
- Planificación cuidadosa de la infraestructura física y lógica
- Escalabilidad para acomodar el crecimiento futuro
- Redundancia en conexiones críticas
- Gestión eficiente del espectro para redes inalámbricas

### Diferencias clave con otras redes
- Mayor que una LAN típica, pero generalmente más pequeña que una MAN
- Más homogénea en tecnología y gestión que una MAN o WAN
- Diseñada específicamente para las necesidades del campus

[Volver al inicio](#tipos-de-redes-de-comunicacion)

## SAN (Red de Area de Almacenamiento)

### Definición
- Una SAN es una red especializada de alta velocidad que proporciona acceso a nivel de bloque a almacenamiento compartido, conectando servidores con dispositivos de almacenamiento.

### Características principales
- Red dedicada al almacenamiento, separada de la red de comunicaciones general
- Alta velocidad y baja latencia
- Escalabilidad en capacidad de almacenamiento
- Acceso compartido a múltiples dispositivos de almacenamiento

### Componentes típicos
- Switches de fibra óptica (Fibre Channel switches)
- HBAs (Host Bus Adapters) en servidores
- Arrays de discos y sistemas de almacenamiento
- Cintas y bibliotecas de cintas para respaldo
- Dispositivos de virtualización de almacenamiento

### Tecnologías comunes
- Fibre Channel (FC) - la más común
- iSCSI (SCSI sobre IP)
- FCoE (Fibre Channel over Ethernet)
- NVMe over Fabrics

### Topologías
- Punto a punto
- Fabric arbitrado (switched fabric)
- Loop arbitrado (menos común actualmente)

### Ventajas
- Centralización y consolidación del almacenamiento
- Mejor utilización y gestión de recursos de almacenamiento
- Alta disponibilidad y redundancia
- Facilita la implementación de soluciones de respaldo y recuperación

### Usos típicos
- Centros de datos empresariales
- Entornos de virtualización de servidores
- Sistemas de bases de datos de alta performance
- Almacenamiento para aplicaciones críticas de negocio

### Seguridad
- Zoning (agrupación lógica de dispositivos)
- LUN masking (control de acceso a nivel de volumen lógico)
- Autenticación de dispositivos
Encriptación de datos en tránsito y en reposo

### Desafíos
- Complejidad en la configuración y gestión
- Costos iniciales elevados
- Necesidad de personal especializad- o

### Evolución
- Integración con tecnologías de nube
Adopción de NVMe (Non-Volatile Memory Express) para menor latencia
Convergencia con redes Ethernet (FCoE)

### Consideraciones de implementación
- Planificación cuidadosa de la capacidad y el rendimiento
- Redundancia en componentes críticos
- Compatibilidad entre dispositivos de diferentes fabricantes
Estrategias de migración de datos

### Diferencias clave con otras redes
- Dedicada exclusivamente al tráfico de almacenamiento
- Utiliza protocolos específicos para acceso a nivel de bloque
- Generalmente tiene requisitos de latencia más estrictos que las redes de datos generales

### Gestión
- Herramientas especializadas para monitoreo y administración
- Virtualización de almacenamiento para mejor utilización de recursos
- Thin provisioning para asignación eficiente de espacio