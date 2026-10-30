# Fase 03 · SOC, detección y respuesta

Esta fase describe cómo la telemetría de AegisTech se transforma en alertas investigables y decisiones de respuesta.

## Flujo operativo

**Fuentes de eventos → Ingesta → Normalización → Correlación → Triage → Investigación → Respuesta**

El diseño contempla Wazuh, Sysmon, Zeek y Suricata, además de conceptos de SIEM/SOAR aplicables a otras plataformas. MITRE ATT&CK contextualiza técnicas adversarias y Sigma sirve como referencia para reglas de detección.

## Escenarios

- Accesos anómalos y cambios de privilegios.
- Actividad inusual de procesos y conexiones.
- Correlación entre eventos de host y red.
- Clasificación de alertas, falsos positivos y severidad.
- Evidencias, tickets, escalamiento y playbooks.

Las observaciones se conectan con la [gestión de vulnerabilidades](../04-vulnerability-management/README.md) y la [detección integrada](../06-capstone-project/README.md). Se utilizan únicamente escenarios autorizados.
