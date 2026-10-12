# Práctica DHCP en VirtualBox

## Descripción

Práctica de Servicios en Red realizada durante el ciclo de Sistemas Microinformáticos y Redes (SMR).

El objetivo es configurar y comprobar el funcionamiento de un servicio DHCP en un entorno virtualizado con VirtualBox.

## Tecnologías y entorno

* **Virtualización:** Oracle VirtualBox
* **Servidor DHCP:** Windows Server
* **Cliente:** Debian 13 XFCE
* **Puerta de enlace:** Debian 13
* **Red virtual:** `intnet`

## Configuración de red

| Elemento         | Dirección IP                  |
| ---------------- | ----------------------------- |
| Servidor DHCP    | `192.168.20.4/24`             |
| Puerta de enlace | `192.168.20.2/24`             |
| Rango DHCP       | `192.168.20.10–192.168.20.12` |

## Objetivos

* Configurar un ámbito DHCP.
* Definir un rango de direcciones IP.
* Configurar los parámetros de red del ámbito.
* Comprobar la conectividad entre máquinas virtuales.
* Documentar la configuración y las pruebas realizadas.

## Evidencias

La práctica completa y sus capturas se encuentran en el documento PDF del repositorio.

## Autor

Estudiante de Sistemas Microinformáticos y Redes (SMR).
