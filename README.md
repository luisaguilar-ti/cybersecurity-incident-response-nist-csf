.
Cybersecurity Incident Response using the NIST Cybersecurity Framework (CSF)
Descripción del proyecto

Este proyecto documenta el análisis de un incidente de ciberseguridad utilizando el NIST Cybersecurity Framework (CSF). El escenario describe un ataque de Denegación de Servicio (DoS) basado en una inundación de paquetes ICMP que afectó la disponibilidad de la red corporativa durante dos horas.

El objetivo es analizar el incidente, identificar la causa raíz, evaluar el impacto sobre la organización y proponer controles de seguridad utilizando las cinco funciones del NIST CSF.

Objetivos
Analizar un incidente de Denegación de Servicio (DoS).
Identificar vulnerabilidades en la infraestructura de red.
Aplicar el marco NIST Cybersecurity Framework (CSF).
Diseñar un plan de protección, detección, respuesta y recuperación.
Documentar el incidente siguiendo buenas prácticas de ciberseguridad.
Conceptos aplicados
NIST Cybersecurity Framework (CSF)
Denial of Service (DoS)
ICMP Flood
Firewall Security
Rate Limiting
IP Source Verification
IDS / IPS
Network Monitoring
Incident Response
Network Availability
Hallazgos principales
Se identificó un ataque DoS mediante tráfico ICMP.
La causa raíz fue una configuración inadecuada del firewall.
La red interna permaneció indisponible durante aproximadamente dos horas.
Se implementaron nuevas reglas de firewall para limitar paquetes ICMP.
Se añadió validación de direcciones IP de origen.
Se implementó un sistema IDS/IPS y monitoreo continuo de la red.
Aplicación del NIST CSF
Identify
Identificación del ataque DoS.
Identificación de la vulnerabilidad del firewall.
Evaluación del impacto sobre la red.
Protect
Configuración de reglas de firewall.
Limitación de tráfico ICMP.
Verificación de direcciones IP.
Detect
Monitoreo continuo de la red.
IDS/IPS.
Detección de tráfico anómalo.
Respond
Bloqueo del tráfico ICMP.
Contención del incidente.
Restauración de servicios críticos.
Recover
Recuperación de los servicios.
Verificación de la estabilidad de la red.
Implementación de mejoras para prevenir futuros incidentes.
Estructura del proyecto

incident-analysis.md → Análisis técnico del incidente

nist-csf-report.md → Aplicación del NIST Cybersecurity Framework

assets/ → Diagramas, dashboards y evidencias visuales

Conclusión

Este proyecto demuestra cómo utilizar el NIST Cybersecurity Framework para gestionar un incidente de ciberseguridad desde su identificación hasta la recuperación. La correcta configuración del firewall, el monitoreo continuo y la implementación de controles preventivos fortalecen la resiliencia de la organización frente a futuros ataques de Denegación de Servicio.
