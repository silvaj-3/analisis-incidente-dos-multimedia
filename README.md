# Caso de Estudio: Mitigación de Ataque DoS (Inundación ICMP) 🛡️

Este proyecto presenta el análisis detallado de un incidente de seguridad real donde una empresa multimedia sufrió un ataque de denegación de servicio.

## 📝 Resumen de la Incidencia
* **Tipo de ataque:** Denegación de Servicio (DoS) mediante inundación de pings ICMP[cite: 3, 27].
* [cite_start]**Duración:** 2 horas[cite: 4, 12].
* [cite_start]**Impacto:** Los servicios críticos y no críticos quedaron fuera de línea, afectando procesos de diseño web y marketing[cite: 8, 31, 35].
* [cite_start]**Causa Raíz:** Cortafuegos mal configurado sin límites de velocidad (rate limiting)[cite: 6, 7].

## 🛠️ Plan de Acción (Marco NIST CSF)

### 1. Proteger y Detectar
* [cite_start]**Configuración:** Implementación de reglas de *rate-limiting* en el firewall para paquetes ICMP[cite: 40].
* [cite_start]**Identidad:** Activación de verificación de IP de origen para prevenir *spoofing*[cite: 43].
* [cite_start]**Supervisión:** Instalación de sistemas IDS/IPS y software de monitoreo de red en tiempo real[cite: 45, 57, 59].

### 2. Responder y Recuperar
* [cite_start]**Contención:** Bloqueo inmediato de paquetes maliciosos y aislamiento de servicios no críticos[cite: 15, 78].
* [cite_start]**Validación:** Verificación de integridad del hardware tras aplicar las nuevas reglas de seguridad[cite: 100].

## 🎓 Certificación Relacionada
Como base técnica para este análisis, completé con éxito la certificación:
**Connect and Protect: Networks and Network Security** (Autorizado por Google y ofrecido a través de Coursera).

![Certificado de Juan Manuel García Silva](./Captura%20de%20pantalla%202026-01-03%20133450.jpg)

---
*Para ver el análisis completo, puedes consultar el [Portafolio.pdf](./Portafolio.pdf).*
