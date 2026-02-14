# Security Portfolio – Antonio Zapata

Este repositorio centraliza mi portfolio práctico orientado a **Ciberseguridad (SOC N1/N2)**.
El objetivo es demostrar, con evidencias reales, cómo trabajo en tareas típicas de operación: **monitorización**, **triage**, **detección** y **documentación/escalado**.

La idea es mantenerlo simple y realista: laboratorios que se pueden hacer sin licencias caras ni infraestructura grande, usando herramientas abiertas y generando eventos/alertas de forma controlada.

---

## Enfoque del portfolio

Este portfolio está pensado para roles de entrada en operaciones de seguridad:

- Monitorización y análisis inicial de alertas
- Revisión de eventos y correlación básica
- Detección en endpoint / servidor (agente)
- Detección en red (IDS)
- Registro de evidencias y documentación tipo SOC (ticketing / escalado)

---

## Laboratorios

Cada laboratorio se documenta con:

- Objetivo y alcance
- Pasos realizados (reproducibles)
- Evidencias (capturas y comandos)
- Qué aportaría en un entorno real (SOC / operaciones)

> Iremos completando cada repo poco a poco conforme avance con las pruebas y capturas.

| Nº | Laboratorio | Qué se practica | Herramientas | Repo |
|---:|------------|-----------------|--------------|------|
| 01 | SIEM básico con Wazuh (recolección + alertas) | Ingesta de logs, reglas, alertas, dashboards | Wazuh | [Security-Lab-01-Wazuh-SIEM](https://github.com/zapata-antonio/Security-Lab-01-Wazuh-SIEM) |
| 02 | Detección en red con Suricata (IDS) | Alertas de red, pruebas controladas, evidencia | Suricata | [Security-Lab-02-Suricata-IDS](https://github.com/zapata-antonio/Security-Lab-02-Suricata-IDS) |
| 03 | Triage + documentación tipo SOC (ITSM) | Clasificación, severidad, escalado, evidencias | Plantilla SOC | [Security-Lab-03-SOC-Triage-ITSM](https://github.com/zapata-antonio/Security-Lab-03-SOC-Triage-ITSM) |

---

## Estructura recomendada (en cada laboratorio)

Dentro de cada repo verás una estructura similar:

- `README.md` con el paso a paso
- carpeta `images/` con capturas numeradas
- sección final con “qué diría en entrevista” (en 4–6 líneas)

Ejemplo de nomenclatura de evidencias:
- `images/01-...png`
- `images/02-...png`
- `images/03-...png`

---

## Sobre mí

Perfil técnico con base fuerte en **operación, troubleshooting y documentación**, y formación específica en ciberseguridad:

- CompTIA Security+ (SY0-701)
- IFCT124 – Respuesta a incidentes de ciberseguridad
- Experiencia extensa en entornos de producción (incidencias, procedimientos, escalado)

---

## Contacto

- Email: zapataantonio@gmail.com
- GitHub: https://github.com/zapata-antonio

