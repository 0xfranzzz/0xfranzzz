```text
 
   ██████  ██   ██ ███████ ██████   █████  ███    ██ ███████ ███████ ███████
  ██  ████  ██ ██  ██      ██   ██ ██   ██ ████   ██    ███     ███     ███
  ██ ██ ██   ███   █████   ██████  ███████ ██ ██  ██   ███     ███     ███
  ████  ██  ██ ██  ██      ██   ██ ██   ██ ██  ██ ██  ███     ███     ███
   ██████  ██   ██ ██      ██   ██ ██   ██ ██   ████ ███████ ███████ ███████
 
  security operations / blue team / network infrastructure
```
 
<a href="https://crti.cl"><code>crti.cl</code></a>&nbsp;
<a href="mailto:contacto@crti.cl"><code>contacto@crti.cl</code></a>
 
```yaml
# sigma rule: perfil del operador
title: 0xfranzzz
status: stable
description: >
  Enfoque analítico en seguridad de la información y operaciones IT.
  Despliegue de infraestructura de red, defensa proactiva y
  telemetría para monitorear y responder ante incidentes.
logsource:
  product: blue_team
  service: soc
detection:
  analisis:       [wireshark, splunk, kali_linux]
  redes:          [cisco, windows_server, docker]
  automatizacion: [python, bash, git]
  condition: analisis and redes and automatizacion
falsepositives:
  - ninguno conocido
level: high
```
 
