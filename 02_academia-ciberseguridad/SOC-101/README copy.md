
Clase 1:

Redes 
 |_ Sistemas Operativos 
     |_ Programacion 
          |_ Ciberseguridad


Es como una escala de conociento para llergar a un objetivo de ciber seguridad


SOC (Security Operations Center - Centro de Operaciones de Seguridad)

Es el nucleo encargado de algunos componentes 
(que monitorea, detecta, responde y previene incidentes de seguridad)

Su obejtico es proteger los activos digitales y garantizar y coordinar las 
acciones ante amenazas ciberneticas

FUNDAMENTOS DE REDES DE COMPUTADORAS

Una red de compuratdoras su objetivo es tener una comunicacion rapida y confiable con 
diferentes tecnologias (como cableado, wifi, routers switch, etc) 
para compartir informcion y recursos.

FUNDAMENTOS DE REDES DOMESTICAS O IoT (INTERDET DE LAS COSAS)

Las IoT que son dispositivos inteligentes ya estan expandidas en una red algunas de ellas
mas hay de una red domestica. (Ejemplo PSL )

CONECTIVIDAD GLOBAL

Hoy en dia las organizaciones coorporatovas ncecesitamos una conectividad global para ello
utlizamos las VPNs (Virtual Private Networks - Red Privada Virtual) donde nos permite
una contividad remota de manera segura para una continuidad de las operaciones.

ESCABILIDAD DE ARQUITECTURA CLIENTE-SERVIDOR

La arquitectura cleinte - servidor estan diseñadas para recibir grandes cantidad de sprocesos 
gracias a esta arquitectura lso server puedes recibir, procesar y responder algun proceso solicitado
y esto nos da una flexibilidad y comodidad para las operecaiones.

Modelo TCP/IP

Es como esta estruturado el interntet, este modleo esta compuesto por 4 capas donde cada capa 
se trabaja con protocolos

 1. Capa de Aplicacion: En esta capa es como se comunica la aplicacion con la red y como se realiza
                         el cambio de informacion.

                         HTTP / HTTPS: Navegacion segura 
                         FTP: transferecnia de archivos
                         DNS: Reaolucion de nombres de dominio
                         SMTP: Evio de correos electronicos

 2. Capa de Transporte: Se garantiza la comunicacion de extremo a extremo al enviar un mensaje 
                        de emeisor a recepto

                        TCP: Transmision Control Protocol
                              Asegura que los datos lleguen completos y en orden correccfto

                        UDP: User Datagram Protocol
                             Mas rapido sin control de errores 

                        RTP: Real-time Transport Protocol
                             Optimizar audio y video en tiempo real

 3. Capa de interntet: Se encarga de direccionar y enrutar los paquetes en diferentes rees ahsta que llegue a su destino

                        IP (Ipv4 / Ipv6): Intenert Protocolo
                            Este protocolo define las direccion unicas de una dispositivo 
                        
                        ARP: Ar Resotions Protocol
                            traduce las IP en direcciones MAC 
                        ICMP: 
                            Realiza diagnostico y mensajes de errores con el comando ping
                        RARP: 
                            Hace traduccion inversa de MAC a IP

 4. Capa interfaz de red: Se encarga de la comunicacion fisica entre dispositivos de la misma red, donde controla y envia datos 

                        Encapsulado
                        Direcciones didicas 
                        Deteccion de eerreos bassicos y transmision



Modelo OSI

Open Systems Interconnection

Es un marco desarrollado por la ISO, esta en comparacion al modelo
TCP/IP tenemos 7 capas para entender y estandarizar las redes.




TIPO DE REDES

LAN: Local Area Network
        Conecta dispositivos en una red local pequeña
PAN: Personal Area Network
        Conecta en dispositivos personales con un area muy corta (ejemplo bluetto, audifonos)
WLAN: Wireless Local Area Network
        similar a una Lan pero con wifi
MAN: Metropolitan Area Network
        Cubre una area geografica como una cuidad
WAN: Wide Area Nerwork
        Red con alcance para cubrir paises


CONTROLES DE SEGURIDAD 

Los controles de seguridad son medidas y mecanismos de seguridad de proteccion
su objeticio es garantizar la confidencialidad, integridad, disponibilidad (CIA)
estos ayudana a mitigar detectar prevenir riesgos y vulnerabilidades.


Existen varios activos como
Firewall : Controla y monitorea el trafico de la red  entrantes y salientes segun las reglas predeterminadas.
                Firewal de hardware y software

WAF (Web Aplication Firewall): Protege las aplicaciones web filtrando y monitoreando el trafico de HTTP y HTTPS.
IPS (Intrusion Prevention System): Controla y monitore el trafico en tiempo real y bloquea amenazas, puede operar a nivel de red o host.
VPN (Virtual Private Network): Crea un canal o tunel de manera segura mediante un cifrado de datos para conectar a una red de una organizacion por remoto. 
NAC (Network Access Control): Controla y gestiiona el acceso de la red basandose con politicas de seguridad.
SEGMENTACION DE RED (Network Segmentation): Divide la red en semengtos separadas.
ANTIVIRUS Y ANTIMALWARE: Detectan, previene y elimina software malicioso.
CIFRADO DE RED:  Protege los datos en transmicion convirtiendolo en codgio que solo puede decifrar el destinatario 
     SSL/TLS: para navegacion segura de la web 
     IPSEC: asgura a nivel de red
SIEM




SEGURIDAD DE WINDOWS

Windows Security es un conjunto de herramientas y caracteristi para poteger sistemas operativos de Microsofts Wiwndows-

Los omponentes de Windows Security es Malware Protecticion. User Authentication, Access Control, Encryptation and data protection

Widowns Defender Antivirus: Antvirus que se maneja en segundo planta, analizando y eliminasdo amenazas
Windows Defender SmartScreen: Protede de amenazas en sitios web, phishing y archivos maliciosos
Microsodft Defender Enppoint: Solucion empresarial para ptretecion avanzado para endpoint y gestionde de vulnerabilidades
Controller Folder Access: Bloquea acceso a carperas crutcas, ataquees en rasonware
Microsoft defender Office: Herramitna qe analiza y elimina amenzas fuera del sistema operatico


ESTANDARES Y LEYES DE SEGURIDAD

        Los estandares y leyes son importnates ya que ellos establecen reglas claras y especificas para proteger inforamacion,
        de como proveer estruturas de organizaciones y tecnicas, para seguir las normas para que aumente la confianza del usuario cliente o entidad.

NIS Directive (Network and Information Systems Directive) - Union Europea

Diseñada para mejorar la ciberseguridad en los servicios en linea y infraestruturas criticas

estbleciendo: 
  1. Esturuturas de segurida para una mejora de os servicion en linea
  2. Protocolos de reporte par aalgun inidente de seguridad

objetibo es formatezimiento de respuesta antes amenazas 

HIPAA (Health Insuarace Protability and Accountabilty Act) - Estados Unidos

        esta enfocada en proteger las informacion de salud y esta basada en dos
  basada:
  1. Security Rule: define como proteger de manera electroica la informacion de salud 
  2. Privacy Rule: define como, quien puede usar la inforamcion medica

NIST SP 800-53 (National Institute od Standards and Technology - NIST) - Estados Unidos 
       Proporcioan una guia completa de controles de seguridad y provacidada
  incluye:
  1. familias de controlds de sguridad por categorias 
  2. configuraciones bases apra un entorno de seguridad 

ISO/IECC 27001 - Estandar Internacional
        Es un estandar reconocido internacionalmente para inplemnetar y mantenimiento de un sistema de gestion de segurdad de informacaion (ISMS)
  el objetivo:
  1. identifica riegos de informacion
  2. establece controles de seguridad para mitigarlos
  3. promueve la merjora continua
  

