# Análisis del Incidente de Ciberseguridad

## Resumen del incidente

La organización sufrió un ataque de Denegación de Servicio (DoS) mediante una inundación de paquetes ICMP dirigidos a la red interna. El ataque provocó que los servicios de red dejaran de responder durante aproximadamente dos horas, afectando la disponibilidad de recursos críticos para la organización.

## Tipo de ataque

Denial of Service (DoS) - ICMP Flood

## Sistemas afectados

* Red interna corporativa
* Servicios de red
* Recursos compartidos de la organización

## Causa raíz

La investigación determinó que el firewall de la organización no contaba con una configuración adecuada para filtrar o limitar el tráfico ICMP entrante. Esta vulnerabilidad permitió que un actor malicioso saturara la red mediante una gran cantidad de solicitudes ICMP.

## Impacto técnico

* Saturación de la red interna
* Interrupción de servicios durante dos horas
* Imposibilidad de acceder a recursos de red

## Impacto al negocio

* Interrupción de operaciones
* Reducción de productividad
* Posibles pérdidas económicas
* Afectación de la disponibilidad de servicios

## Controles implementados

* Limitación de paquetes ICMP mediante reglas de firewall
* Verificación de direcciones IP de origen
* Implementación de IDS/IPS
* Software de monitoreo de red

## Lecciones aprendidas

La correcta configuración del firewall y la supervisión continua del tráfico de red son elementos fundamentales para prevenir ataques de denegación de servicio y mantener la disponibilidad de los servicios empresariales.
