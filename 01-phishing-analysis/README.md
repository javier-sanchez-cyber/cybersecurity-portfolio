# Phishing Analysis Report

## Objetivo

Analizar una muestra simulada de phishing desde una perspectiva Blue Team/SOC, identificando indicadores de compromiso, técnicas de ingeniería social, nivel de riesgo y medidas de respuesta recomendadas.

## Fuente del escenario

Este proyecto utiliza una muestra simulada y sanitizada con fines educativos.

No contiene datos personales reales, credenciales, infraestructura real comprometida ni enlaces maliciosos activos.

El objetivo no es atribuir una campaña real, sino demostrar una metodología de análisis de phishing desde una perspectiva SOC.

## Escenario

Un empleado recibe un correo que aparenta provenir del equipo de Microsoft 365 indicando que su cuenta será bloqueada si no verifica sus credenciales.

El mensaje contiene un enlace a una página falsa de inicio de sesión.

El análisis busca determinar si el correo es malicioso, extraer indicadores relevantes y proponer medidas de contención, erradicación, recuperación y prevención.

## Skills demostradas

- Phishing Analysis
- Email Security
- SPF / DKIM / DMARC
- Indicadores de compromiso
- Ingeniería social
- MITRE ATT&CK
- Incident Response
- Documentación técnica

## Herramientas utilizadas

- Análisis manual de cabeceras
- VirusTotal
- URLScan
- MXToolbox
- CyberChef
- WHOIS
- MITRE ATT&CK

## Archivos del proyecto

| Archivo | Descripción |
|---|---|
| `informe-phishing.md` | Informe técnico completo |
| `recomendaciones.md` | Plan de actuación resumido |
| `evidencias/email-sanitized.txt` | Muestra simulada del correo |
| `evidencias/headers-sanitized.txt` | Cabeceras simuladas y sanitizadas |
| `evidencias/iocs.txt` | Indicadores de compromiso extraídos |

## Resultado esperado

El análisis permite identificar señales compatibles con un intento de phishing orientado al robo de credenciales y propone medidas defensivas aplicables en un entorno SOC.
