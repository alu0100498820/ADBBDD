# Protocolos 

Un protocolo es  un conjunto de reglas y procedimientos que deben respetarse para el 
envío y la recepción de datos a través de una red. 

Existen diversos protocolos de acuerdo a cómo se espera que sea la comunicación. Algunos protocolos, por ejemplo, se especializarán en el intercambio de archivos
(FTP); otros pueden utilizarse simplemente para administrar el estado de la 
transmisión y los errores (como es el caso de ICMP), etc.


Un protocolo de seguridad es la parte visible de una aplicación, es el conjunto de programas y actividades programadas que cumplen con un objetivo específico y que usan esquemas de seguridad criptográfica. Define las reglas que gobiernan estas comunicaciones. Diseñadas para que el sistema pueda soportar ataques de carácter maliciosos. Los protocolos son diseñados bajo ciertas primicias con respecto a los riesgos.

Los protocolos que se aplican a las bases de datos seguras depende del proveedor SGBD y del lenguaje de programación que se quiera usar.

- Active Directory, termino usado por Microsft para referirse a su servicio de directorio en una red de computadores. Utiliza distintos protocolos tales como LDAP, DNS, DHCP, Kerberos,etc.

- SSL/TLS nivel seguro de socket o seguridad a nivel de trasporte, estandar IETF, utiliza certificados y socket TCP para proveer conexiones seguras. 

    Esta seguridad es en forma de privacidad y autenticación: por un lado autentica el servidor de la comunicación (mediante certificados), y por otra parte selecciona un algoritmo de cifrado, permite el intercambio de claves de forma segura entre cliente y servidor, y cifra la información con cifrado simétrico.

- Kerberos. Sistema de autentificacion de unica firma en red con posibilidad de privacidad. Estandar IETF, utiliza tecnología de clave simetrica. 

- SSH (Secure Shell), protocolo de entrada en seción y/o ejecución de comandos en una maquina remota.

- IKE(Internet Key Exchange), Protocolo utilizado para establecer una asociación de seguridad(SA) usando el protocolo IPsec, emplea un intercambio secreto de claves tipo Diffie-Hellman para establecer el secreto compartido de la sesión(suele usar sistemas de clave pública).

Algunos otros protocolos usasados en las bases de datos NOsql.

- P2P con lo que la redundancia es maxima.

- Gossip para permitir comunicacion dentro de un ring(cada nodo sabe de otros nodos),  usado para descubrir la hubicacón y la información de estado a cerca de los otros nodos.

