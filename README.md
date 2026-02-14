# Lab 01: SIEM con Wazuh (logs, alertas y triage básico)

## Objetivo
Montar un SIEM gratuito (Wazuh) y demostrar el flujo mínimo de operación:
1) ingestar eventos,
2) detectar alertas,
3) hacer un triage básico,
4) documentar evidencias.

## Entorno
- 1 VM Ubuntu (puede ser Azure o local)
- Wazuh All-in-One (manager + dashboard)
- Generación de eventos desde la propia VM

## Pasos (resumen)
1. Desplegar Wazuh (All-in-One) en Ubuntu.
2. Acceder al Dashboard y validar que el stack está operativo.
3. Generar eventos:
   - intentos de login fallidos (SSH)
   - cambios en ficheros críticos (integrity monitoring)
4. Localizar eventos/alertas en Wazuh.
5. Registrar evidencias y redactar mini análisis (triage).

## Evidencias (capturas)
- `images/01-wazuh-dashboard.png`  
  Dashboard operativo (se vea Wazuh funcionando).
- `images/02-alert-ssh-bruteforce.png`  
  Alerta real de SSH (varios intentos / severidad / IP origen).
- `images/03-triage-notes.png`  
  Nota de triage (qué miré, por qué, y qué haría en un SOC).

## Pruebas reales (comandos)
Generar intentos fallidos SSH desde tu PC (o desde otra shell):
```bash
ssh usuario_inventado@IP_DE_LA_VM
# repetir varias veces con contraseña incorrecta
