
## Conceptos 

### IP (Internet Protocol)
Sistema numérico que identifica de manera única cada dispositivo conectado a una red informática que utiliza el protocolo IP para la comunicación. Funciona como una dirección postal para los dispositivos, permitiendo que los datos encuentren su destino correcto en la red. Existen dos versiones principales: IPv4 (32 bits) e IPv6 (128 bits).

**Ejemplos:**
- IPv4: 192.168.1.100 (red local), 8.8.8.8 (DNS de Google)
- IPv6: 2001:db8:3333:4444:5555:6666:7777:8888, fe80::1ff:fe23:4567:890a

### Dominio
Sistema jerárquico de nombres que facilita la identificación de recursos en internet. Actúa como una capa de abstracción que convierte direcciones IP numéricas en nombres fácilmente recordables para los usuarios. Incluye diferentes niveles separados por puntos, donde cada nivel proporciona información específica sobre la ubicación del recurso.

**Ejemplos:**
- amazon.com, aws.amazon.com
- blog.ejemplo.es, tienda.ejemplo.com

### OpenLDAP
Sistema de directorio de código abierto que implementa el protocolo LDAP (Lightweight Directory Access Protocol). Proporciona un método centralizado para almacenar y organizar información sobre usuarios, sistemas y recursos de red. Es altamente personalizable y se puede integrar con múltiples plataformas.

**Ejemplos:**
- directorio.empresa.com:389 (servidor LDAP empresarial)
- ldaps://auth.organización.org:636 (LDAP sobre SSL)

### Active Directory
Servicio de directorio desarrollado por Microsoft que proporciona un framework completo para la gestión de identidades y accesos en entornos Windows. Almacena información sobre objetos de red y hace esta información disponible para usuarios y administradores.

**Ejemplos:**
- dc1.corporacion.local (controlador de dominio principal)
- child.parent.local (dominio hijo en una estructura jerárquica)

### URL (Uniform Resource Locator)
Cadena de caracteres que proporciona una referencia a un recurso en internet. Incluye el protocolo utilizado, el nombre del servidor, la ruta al recurso y parámetros opcionales. Es la forma estándar de especificar la ubicación de recursos web.

**Ejemplos:**
- https://www.ejemplo.com/productos?categoria=electronica&id=123
- ftp://servidor.empresa.com/archivos/documento.pdf

### Puerto
Punto de conexión lógico que se utiliza para diferenciar las distintas aplicaciones y servicios que se ejecutan en un mismo dispositivo. Los puertos se identifican mediante números del 0 al 65535, donde ciertos números están reservados para servicios específicos.

**Ejemplos:**
- mysql://localhost:3306 (base de datos MySQL)
- https://api.servicio.com:8443 (API segura en puerto personalizado)

### Diferencia entre HTTP y HTTPS
HTTP (Hypertext Transfer Protocol) es el protocolo base para la transferencia de datos en la web, mientras que HTTPS (HTTP Secure) es su versión segura que utiliza cifrado SSL/TLS para proteger las comunicaciones entre el cliente y el servidor.

**Ejemplos:**
- http://periódico.com (conexión no cifrada visualizable)
- https://banco.com (conexión cifrada para transacciones seguras)

### Protocolo
Conjunto estandarizado de reglas que determina cómo se debe establecer y mantener una comunicación entre diferentes dispositivos en una red. Define el formato, sincronización, secuenciación y control de errores en la comunicación de datos.

**Ejemplos:**
- smtp://mail.empresa.com (envío de correo)
- sftp://storage.cloud.com (transferencia segura de archivos)

### RDP (Remote Desktop Protocol)
Protocolo propietario desarrollado por Microsoft que proporciona acceso gráfico remoto a un equipo Windows. Permite la transmisión del escritorio completo, incluyendo movimientos del ratón, pulsaciones de teclado y audio.

**Ejemplos:**
- workstation01.office.com:3389
- terminal.empresa.local:3389

### SSH (Secure Shell)
Protocolo de red que permite el acceso remoto seguro a sistemas mediante una shell cifrada. Proporciona autenticación fuerte y comunicaciones seguras sobre canales no seguros. Es el estándar de facto para administración remota de sistemas Unix/Linux.

**Ejemplos:**
- ssh usuario@servidor.empresa.com -p 22
- sftp://respaldos.cloud.com:2222

## Plataformas Cloud

### Cloud Computing
Modelo de entrega de servicios informáticos a través de internet, incluyendo servidores, almacenamiento, bases de datos, redes, software y análisis. Permite acceso bajo demanda a recursos compartidos configurables.

**Ejemplos:**
- Netflix (streaming basado en AWS)
- Spotify (servicio de música en Google Cloud)

### AWS (Amazon Web Services)
Plataforma de servicios en la nube más grande del mundo, que ofrece una amplia gama de servicios globales de computación, almacenamiento, bases de datos, análisis, machine learning, IoT y más.

**Ejemplos:**
- netflix.com (infraestructura completa en AWS)
- airbnb.com (procesamiento de datos y hosting)

### Proxmox
Plataforma de virtualización de código abierto que combina virtualización KVM y contenedores Linux. Incluye una interfaz web de gestión y herramientas para la administración de clusters de alta disponibilidad.

**Ejemplos:**
- cluster.datacenter.local:8006 (interfaz web de gestión)
- node1.cluster.local (nodo de virtualización)

### Google Cloud
Plataforma de servicios en la nube de Google que ofrece una amplia gama de servicios de infraestructura y aplicaciones en la nube, respaldada por la infraestructura global de Google.

**Ejemplos:**
- Pokemon Go (juego basado en GCP)
- Snapchat (procesamiento de imágenes y videos)

### Azure
Plataforma de computación en la nube de Microsoft que proporciona una amplia gama de servicios integrados, incluyendo análisis, computación, bases de datos, móvil, redes, almacenamiento y web.

**Ejemplos:**
- Office 365 (suite ofimática en la nube)
- xbox.com (servicios de juegos en línea)

## Roles Profesionales

### Administrador de Sistemas
Profesional responsable de la implementación, configuración, mantenimiento y confiabilidad de los sistemas informáticos de una organización. Gestiona tanto el hardware como el software necesario para las operaciones empresariales.

**Ejemplos:**
- Administrador de sistemas de un hospital gestionando sistemas críticos 24/7
- Administrador IT de una universidad gestionando infraestructura para 50,000 usuarios

### DevOps
Profesional que combina prácticas de desarrollo de software y operaciones IT, enfocándose en la automatización del ciclo de vida del software, desde el desarrollo hasta la implementación y monitorización.

**Ejemplos:**
- DevOps en Spotify gestionando microservicios y despliegues continuos
- DevOps en Amazon manteniendo la infraestructura de comercio electrónico

---


