# Caso-practico3

# COMO NO OS LO LEÁIS ESTO ES PARA MATAROS ESTA DETALLADO TODO

## CASO PRÁTICO 3
REQUERIMIENTOS
-- División de las zonas en distinas *V*irtual *L*ocal *A*rea *N*etwork

-- Enrutamiento dinámico entre las distintas VLAN (Protocólos OSPF, que se comportan por el alogritmo de dijsktra facilitando la ruta mas óptima para llegar al destino que se desee)

-- Encriptación de paquetes

-- Seguridad en la red integrando protocolos de encryptación y dispositivos intermedios(routers y firewalls) 
### Esquema de como se dispone la red con dispositivos intermedios para garantizar una seguridad óptima (lo hable con pichu y creo que es así (preguntar a rubén))
PC1

 │
 
 ▼

Switch1

 │
 
 ▼

Firewall

 │
 
 ▼

Router1

 │
 
 ▼

Switch2

 │
 
 ▼

Router2

 │
 
 ▼

Switch3

 │
 
 ▼
PC2

-- Protocólos de transferencia de archivos segura (SFTP, el cual requiere de usuario y contraseña para poder acceder a este protocolo)

-- Servicios de web (HTTP , con una web básica(que es opcional para este, pero requerido en el caso final )

## Archivo word que describa lo propuesto por capa y porque se ha decidido implementar cada cosa


### Apuntes 22/04
Configurar los ICMP para que tengan un timeout establecido(tienen timeout o por defecto)

# Sobre el caso final integrador

Proyecto nuevo --> Arquitectura nueva
hay que utilizar el codigo postal de la localidad 
subred para cada uno de los servicios del gobierno(todos los del ayuntamiento) 
subredes para los servicios municipales (sanitario)
se tiene que conectar a un router central
Dispositivos Iot (con la api rest que se proporciona en la web)
serrvicios multimedia para los ciudadanos (con ipv6)
Robustez hacia posibles amenazas con firewalls --> montar una DMZ en el ayuntamiento 
hay que tener un server por cada servicio multimedia que se ofrece 
VPN ,DNSSEC, CIFRADO
firewalls no se configuran, no dejan configurarlos
catalogo de datos abiertos 
comunicación inter organismos 


Pasos 1,2 --> Entrega adjuntada
Pasos 3,4 --> Entrega adjuntada 
Paso 5 --> Entrega adjuntada

Los centros de control(oficinas gubernamentales) tienen que tener su propia VPN 
Para cifrar los ssl a nivel teorico 

Construir una red integral(con el ayto en el centro)


Podemos simular una web dentro de los servers del cisco



