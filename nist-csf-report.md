# Reporte de Aplicación del NIST Cybersecurity Framework (CSF)

## Resumen del Incidente

La organización sufrió un ataque de **Denegación de Servicio (DoS)** mediante una inundación de paquetes ICMP dirigida a la red interna. El alto volumen de tráfico saturó la infraestructura de red, provocando la interrupción de los servicios durante aproximadamente dos horas.

La investigación determinó que la causa raíz del incidente fue una configuración inadecuada del firewall, que permitió el ingreso de tráfico ICMP malicioso sin aplicar restricciones suficientes.

---

# Aplicación del NIST Cybersecurity Framework (CSF)

## 1. Identify (Identificar)

### Tipo de incidente

- Ataque de Denegación de Servicio (DoS).
- Inundación de paquetes ICMP (ICMP Flood).

### Activos afectados

- Red interna.
- Servicios de red.
- Operaciones de la organización.

### Vulnerabilidad identificada

- Firewall mal configurado.
- Ausencia de reglas para limitar el tráfico ICMP.
- Controles preventivos insuficientes.

### Impacto al negocio

- Interrupción de los servicios durante aproximadamente dos horas.
- Los empleados no pudieron acceder a los recursos de red.
- Afectación de la continuidad operativa.
- Posibles pérdidas económicas derivadas de la indisponibilidad de los servicios.

---

## 2. Protect (Proteger)

Para reducir el riesgo de futuros incidentes similares se recomienda implementar los siguientes controles:

- Configurar correctamente las reglas del firewall.
- Aplicar limitación de tráfico ICMP (Rate Limiting).
- Validar las direcciones IP de origen.
- Implementar soluciones IDS/IPS.
- Realizar mantenimiento periódico de las configuraciones de seguridad.
- Revisar continuamente las políticas de protección de la red.

---

## 3. Detect (Detectar)

La organización debe fortalecer sus capacidades de detección mediante:

- Monitoreo continuo de la red.
- Supervisión del tráfico mediante IDS/IPS.
- Revisión de registros (logs).
- Generación de alertas automáticas.
- Detección temprana de patrones anómalos de tráfico ICMP.

---

## 4. Respond (Responder)

Durante el incidente se realizaron las siguientes acciones:

- Bloqueo del tráfico ICMP malicioso.
- Contención del incidente para evitar una mayor afectación.
- Restauración de los servicios críticos.
- Investigación del origen del ataque.
- Actualización de las reglas del firewall para prevenir nuevos ataques.

---

## 5. Recover (Recuperar)

Después de controlar el incidente se llevaron a cabo las siguientes actividades:

- Restauración completa de los servicios de red.
- Verificación de la estabilidad de la infraestructura.
- Monitoreo continuo para detectar nuevos intentos de ataque.
- Implementación de mejoras permanentes en la seguridad.
- Documentación del incidente y de las lecciones aprendidas.

---

# Lecciones Aprendidas

Este incidente demostró que una configuración incorrecta del firewall puede comprometer la disponibilidad de los servicios de una organización. La implementación de controles preventivos, el monitoreo continuo y una estrategia adecuada de respuesta a incidentes permiten reducir significativamente el impacto de futuros ataques de Denegación de Servicio.

---

# Conclusiones

- La configuración adecuada del firewall es un control crítico para proteger la infraestructura de red.
- El monitoreo continuo permite detectar actividades maliciosas de forma temprana.
- Las soluciones IDS/IPS fortalecen la capacidad de detección y respuesta.
- Aplicar el NIST Cybersecurity Framework proporciona una metodología estructurada para gestionar incidentes de ciberseguridad.
- La mejora continua de los controles de seguridad incrementa la resiliencia de la organización frente a futuras amenazas.
