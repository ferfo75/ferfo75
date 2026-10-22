# Hola, soy Fernando Calvo 👋

**Infraestructura y seguridad IT**

Administro la infraestructura de una empresa industrial (servidores Windows y Linux, red, virtualización, backups y
seguridad) y automatizo lo que se repite. Prefiero medir antes de afirmar, hacer cambios reversibles y dejar todo
documentado.

---

## En qué trabajo

- **Monitoreo y observabilidad:** disponibilidad, alertas sin ruido, informes de SLA, SNMP, agentes propios.
- **Seguridad y auditoría:** Active Directory y GPO, eventos de seguridad de Windows, antivirus centralizado,
  endurecimiento de servicios expuestos, gestión de secretos.
- **Automatización:** scripts de despliegue por GPO, backups, parches, reportes.
- **Continuidad:** copias de respaldo, pruebas de restauración, vigilancia del propio monitor.

## Herramientas

| Área | Con qué |
|---|---|
| Sistemas | Windows Server, Active Directory, GPO, Debian / Linux, systemd |
| Redes | SNMP, WatchGuard, switches gestionables, VPN, MPLS |
| Virtualización y backup | VMware ESXi, Proxmox, Veeam |
| Seguridad | Kaspersky Security Center, auditoría avanzada de Windows, TLS, nginx |
| Desarrollo | Python (FastAPI, SQLAlchemy), PowerShell, Bash, JavaScript |
| Datos | PostgreSQL, SQLite |
| Otros | Docker, Git y GitHub |

## Proyecto destacado: Infra Monitor

Sistema de monitoreo, seguridad y auditoría de infraestructura hecho a medida y **en producción**:

- Monitorea **249 equipos** con un agente propio (Windows y Linux) y colectores para switches, firewalls, UPS, NAS,
  cámaras, Veeam, Proxmox, ESXi y Kaspersky.
- Servidor en **FastAPI + PostgreSQL** (más de 15.000 líneas de Python), con dashboard web en vivo.
- Agente que **se actualiza solo con firma RSA**: aunque alguien tome el servidor, no puede ejecutar código en la flota.
- Higiene de Active Directory por LDAP con una cuenta sin privilegios, cambios de GPO, RDP y Kerberos débil.
- Despliegue detrás de **nginx** (HTTPS para el dashboard y un puerto filtrado para los agentes ya instalados).

Por contener la arquitectura de una red real, el repositorio es **privado**. Puedo mostrar el código y explicar las
decisiones de diseño en una entrevista.

## Cómo trabajo

- **Verifico antes de afirmar:** cada cambio en producción lleva su comprobación y su marcha atrás.
- **Documento los errores también:** lo que se probó y falló ahorra tiempo al próximo.
- **Secretos fuera del código** y datos reales fuera de los repositorios públicos.

## Contacto

- LinkedIn: https://www.linkedin.com/in/fernando-calvo-23388514b/
- - Email: fernandoecalvo@gmail.com
  - - Ubicación: Exaltación de la Cruz, Argentina
    - 
