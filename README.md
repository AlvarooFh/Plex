# Writeup

## Conocer la red

Lo primero de todos es encontrar equipos dentro de mi red.

`sudo arp-scan -I eth0 --localnet`

![captura-red](https://github.com/AlvarooFh/Plex/assets/148774363/f8868383-1b04-4df1-98d9-29cd3690c682)

Ahora podemos saber cuál es la máquina atacante ya que estamos en VMware y la MAC siempre empieza por **00:0c** Por lo tanto sería la **192.168.95.104**

## Conectividad con la máquina atacante

Comprobamos que tenemos conectividad
