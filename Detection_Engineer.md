# Resumen

El Ingeniero de Detección (Detection Engineer) diseña, construye y mantiene la capa de detección de la organización: reglas de detección, telemetría, correlaciones y validaciones que permiten identificar actividad maliciosa (tanto malware conocido como adversarios avanzados) de forma precisa y con el mínimo de falsos positivos. Es un rol puente entre el SOC, la ingeniería de datos y el threat hunting, y uno de los más demandados dentro de la defensa en 2026. Su trabajo se basa en hipótesis derivadas de MITRE ATT&CK y en el ciclo continuo de "detectar → validar → refinar → emular".

# Requisitos previos

* Experiencia previa en SOC o respuesta a incidentes (recomendada)
* Sólidos conocimientos de sistemas (Windows/Linux/macOS), redes, SIEM y lenguajes de scripting (Python, Kusto KQL, SPL)

# Habilidades técnicas

* Desarrollo de reglas de detección en múltiples formatos: Sigma (conversión a SIEM), Splunk SPL, Kusto KQL, Elastic EQL/Lucene, YARA (binarios/memoria) y reglas nativas de EDR (CrowdStrike, Defender, SentinelOne).
* Gestión del pipeline de detección: esquemas comunes, normalización de logs (ECS, CIM), enriquecimiento de eventos e ingeniería de telemetría.
* Correlación y analítica: búsquedas de caza (hunting queries), baselines de comportamiento, detección de anomalías (incluida la analítica de ML) y uso de UEBA.
* Conocimiento profundo del marco MITRE ATT&CK y mapeo de técnicas y subtécnicas a datos y detecciones.
* Emulación de adversarios y validación de detección: uso de herramientas como Atomic Red Team, CALDERA, Infection Monkey y lab entornos para probar que las reglas funcionan (y cuánto tardan en detectar).
* Gestión del ciclo de vida de detección: control de versiones (Git), revisión de reglas, pruebas, depuración y desmantelamiento de reglas ruidosas; documentación y reporting de cobertura.
* Reducción de falsos positivos/negativos: análisis de la tasa de alertas, tuning y mantenimiento continuo.
* Integración con la respuesta: playbooks SOAR, feeds de inteligencia (IOC/STIX-TAXII, MISP) y enriquecimiento de alertas.
* (2026) Detección de ataques a la cadena de suministro de software, detección de abuso de IA/LLMs, y técnicas de evasión moderna (Living off the Land, log tampering, Lolbins).

# Habilidades blandas

* Pensamiento crítico y analítico riguroso.
* Comunicación clara con analistas, gestores de incidentes e ingeniería de plataforma.
* Documentación meticulosa y mentalidad de mejora continua (post-mortems de las detecciones fallidas).

# Educación

  * Grado en Ciencias de la Computación, Ciberseguridad o experiencia equivalente (autoestudio y portafolio de detecciones muy valorados).

# Certificaciones

  * GCIA (SANS Intrusion Analyst) / GCDA (Detection Analyst, en alza en 2026)
  * GREM (Reverse Engineering Malware) complementaria
  * CySA+ o Security+ de entrada
  * Coursos de Sigma/Academia de detección (ej. Detections Lab de Splunk, Elastic Security Fundamentals)

# Salario por región (2026)

Cifras anuales brutas aproximadas `P25 <= Mediana <= P75`.

## Asia
$50K <= $72K <= $100K

## África
$35K <= $50K <= $75K

## Norteamérica
$115K <= $150K <= $200K

## Sudamérica
$45K <= $65K <= $95K

## Europa
€52K <= €75K <= €110K (Reino Unido: £48K <= £68K <= £100K)

## Oceanía
AU$85K <= AU$115K <= AU$160K

# Preguntas de entrevista

* Describe el ciclo de vida de una regla de detección: ¿cómo la escribirías, probarías y refinarías?
* ¿Cómo reducirías el volumen de falsos positivos de una regla concreta sin perder detección?
* ¿Qué fuentes de datos necesitas para detectar la técnica de movimiento lateral (T1021) de MITRE ATT&CK?
* ¿Cómo validas que una nueva detección realmente funciona contra un emulador de adversario?

# Recursos de formación

  * MITRE ATT&CK y recursos de detección (detections/otácticas): https://attack.mitre.org/
  * Sigma (especificación y conversores de reglas): https://sigmahq.io/ y https://github.com/SigmaHQ/sigma
  * Atomic Red Team (emulación y validación): https://github.com/redcanaryco/atomic-red-team
  * Elastic Security Labs y blog de detección: https://www.elastic.co/security-labs
  * Detections Lab (construye tu propio laboratorio de detección, by Splunk/brames): https://www.detectionslab.com/