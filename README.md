# Análisis de Comunicaciones de Red con Wireshark

Este proyecto forma parte de la asignatura **Sistemas Informáticos** de primer año del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. El objetivo principal es analizar el tráfico de red capturado utilizando la herramienta **Wireshark**, enfocado en el análisis de los protocolos de red, como **ICMP**, en diferentes escenarios de redes locales (LAN) y remotas.

## Descripción

A lo largo de este proyecto, se ha llevado a cabo el siguiente análisis:

1. **Captura de datos ICMP locales**: Se realizó un análisis del tráfico de ping (ICMP) entre dispositivos en la misma red local, capturando direcciones IP y MAC.
2. **Análisis de hosts remotos**: Se capturaron datos de pings a hosts remotos (fuera de la LAN), observando las diferencias en las direcciones IP y MAC.
3. **Captura de datos de sitios web**: Se realizó un análisis de tráfico al hacer ping a varias URLs de sitios web como www.cisco.com, www.wikipedia.org y www.educa2.madrid.org.
4. **Inspección de datos de servidores remotos**: Se examinó cómo las direcciones MAC de los servidores no son directamente accesibles desde Wireshark, ya que los pings pasan por routers intermedios.

## Formato del Proyecto

Lo que se subirá a este repositorio es un **PDF** que contiene las capturas de pantalla documentadas de las pruebas realizadas, junto con las respuestas y análisis detallados de cada paso del proyecto.

## Requisitos

Para reproducir este análisis, he necesitado tener:

- **Wireshark** instalado.
- Acceso a una red local o conexión a internet para realizar las capturas de datos.

## Conclusiones

A través de este proyecto, se observó cómo los protocolos de red y las direcciones MAC cambian dependiendo de si la comunicación es local o remota. También se evidenció cómo los routers intermedios en las redes remotas manejan las direcciones MAC de los paquetes ICMP.
