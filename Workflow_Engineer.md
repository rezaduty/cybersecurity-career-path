# Resumen

El Ingeniero de Flujos de Trabajo (Workflow/Orchestration Engineer) diseña, implementa y opera los flujos automatizados que conectan las herramientas, los datos y el personal de seguridad: orquestación de respuesta a incidentes, triage de alertas, aprobaciones y notificaciones, diezimentación de IOCs y coordinación entre SIEM, SOAR, EDR, ticketing (ServiceNow, Jira) y plataformas de colaboración (Slack, Teams). Es el rol que transforma los procesos manuales del equipo en automatizaciones fiables, visibles y probadas, reduciendo el tiempo de respuesta (MTTR). En 2026 está muy valorado por su impacto directo en la rapidez y consistencia del SOC.

# Requisitos previos

* Experiencia operativa en SOC o respuesta a incidentes (comprender el proceso que se automatiza)
* Base fuerte de scripting (Python) y conocimientos de APIs REST y formatos de datos (JSON, YAML)

# Habilidades técnicas

* Diseño e implementación de playbooks y runbooks de orquestación en plataformas SOAR (Splunk SOAR, Cortex XSOAR, Microsoft Sentinel Logic Apps, Tines, Swimlane, Shuffle).
* Integración de APIs REST/GraphQL entre SIEM, EDR, TIP, ticketing, email y colaboración; gestión de webhooks, tokens, autenticación y paginación.
* Desarrollo de integraciones personalizadas y de scripts de automatización en Python, PowerShell o Go; pruebas unitarias y de integración de los flujos.
* Diseño de flujos fiables: idempotencia, reintentos, timeouts, manejo de errores, dead-letter, logs y observabilidad de cada automatización.
* Automatización de triage y respuesta: asignación inteligente de alertas, enriquecimiento automático, bloqueo en EDR/firewall, contención de endpoints, recolección de evidencias.
* Control de versiones y despliegue de los playbooks (CI/CD para contenido) y de configuración de SOAR.
* Métricas y reporte: seguimiento del MTTR, porcentaje de automatización, tasas de éxito/fallo, y optimización continua de los flujos.
* Seguridad de la automatización: manejo seguro de secretos (Vault), mínimos privilegios para cuentas de servicio y chequeo de las acciones de alto riesgo (approval gates).
* (2026) Uso de IA/LLMs en flujos de trabajo (resúmenes de alertas, triage asistido, generación de informes) con controles de revisión humana.

# Habilidades blandas

* Pensamiento de ingeniería y mentalidad de automatizar primero lo repetitivo de alto volumen.
* Comunicación transversal con analistas, detección, respuesta e infraestructura.
* Documentación clara de los flujos (decisiones, condiciones, responsables) para auditoría y continuidad.
* Paciencia y meticulosidad: verificar que cada integración es segura y reversible.

# Educación

  * Grado en Ciencias de la Computación, Sistemas de Información o experiencia equivalente.

# Certificaciones

  * Coursos específicos de SOAR para Splunk y Cortex XSOAR (o equivalentes por plataforma)
  * GIAC Security Automation Engineer (GCSA) — encaja muy bien
  * CompTIA CySA+ u OSCP recomendadas como base de operaciones
  * Certified Automation (AWS) si el entorno es cloud

# Salario por región (2026)

Cifras anuales brutas aproximadas `P25 <= Mediana <= P75`.

## Asia
$50K <= $70K <= $95K

## África
$35K <= $50K <= $72K

## Norteamérica
$105K <= $140K <= $185K

## Sudamérica
$42K <= $62K <= $88K

## Europa
€48K <= €70K <= €100K (Reino Unido: £45K <= £63K <= £92K)

## Oceanía
AU$80K <= AU$105K <= AU$145K

# Preguntas de entrevista

* Describe un playbook de respuesta a incidentes que hayas automatizado: condiciones, acciones y salvaguardas de seguridad.
* ¿Cómo diseñarías un flujo para que falle de forma segura (fall-safe) y no provoque daños colaterales?
* ¿Cómo gestionas secretos y autenticación en integraciones SOAR?
* ¿Qué métricas usarías para demostrar el valor de una automatización al SOC?

# Recursos de formación

  * Documentación de Splunk SOAR y playbooks: https://docs.splunk.com/Documentation/SOAR
  * Cortex XSOAR docs y playbook gallery: https://docs-cortex.paloaltonetworks.com/r/Cortex-XSOAR
  * Tines (automatización moderna low-code) y su academia: https://www.tines.com/
  * Curso de automatización con Python (Coursera): https://www.coursera.org/learn/automating-real-world-tasks-with-python