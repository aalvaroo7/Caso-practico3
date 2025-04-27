# Caso-practico3

# COMO NO OS LO LEÁIS ESTO ES PARA MATAROS ESTA DETALLADO TODO

## CASO PRÁTICO 3
### REQUERIMIENTOS

-- Encriptación de paquetes

-- Seguridad en la red integrando protocolos de encryptación y dispositivos intermedios(routers y firewalls) 

-- Protocólos de transferencia de archivos segura (SFTP, el cual requiere de usuario y contraseña para poder acceder a este protocolo)

-- Servicios de web (HTTP , con una web básica(que es opcional para este, pero requerido en el caso final )

-- Tunnelado para pasar de ipv4 a ipv6 si es necesario

## Archivo word que describa lo propuesto por capa y porque se ha decidido implementar cada cosa

## VIDEOS

https://www.youtube.com/watch?v=CsAROSbZF-Y&list=PLvUOx2WG6R7N5mUWwB-_YLWEkk491XqKx&index=62&t=315s <--- Montado de una vpn con ipsec(encriptación)

https://www.youtube.com/watch?v=OQVKp6VLyls&t=127s <--- Tunnelado de ipv6  SOBRE  ipv4


### Apuntes 22/04
Configurar los ICMP para que tengan un timeout establecido(tienen timeout 0 por defecto)













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



Capas 1,2 --> Entrega adjuntada

Capas 3,4 --> Entrega adjuntada 

Capas 5 --> Entrega adjuntada


Los centros de control(oficinas gubernamentales) tienen que tener su propia VPN 

Para cifrar los ssl a nivel teorico 

Construir una red integral(con el ayto en el centro)


Podemos simular una web dentro de los servers del cisco



