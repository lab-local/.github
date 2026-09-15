<div align="center" style="overflow: hidden; max-height: 220px;">
  <img src="https://raw.githubusercontent.com/lab-local/.github/main/profile/venti-views-1cqIcrWFQBI-unsplash.png" 
       alt="LAB.LOCAL — Infraestructura y contenedores" 
       width="100%" 
       style="object-fit: cover; object-position: center; margin-top: -20%; margin-bottom: -20%;">
</div>

# LAB.LOCAL

> **Fast & Secure by Design.**  
> Herramientas *open source* y libros técnicos para la comunidad *tech* en español.

---

### <img src="https://api.iconify.design/bi/terminal.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> ¿Qué es LAB.LOCAL?

**LAB.LOC** es un laboratorio de ingeniería de infraestructura y plataformas de producción. Diseñamos, desplegamos y operamos arquitecturas híbridas orientadas a **máximo rendimiento, seguridad por diseño y soberanía tecnológica**, optimizando costos al límite sin comprometer la resiliencia.

---

### <img src="https://api.iconify.design/bi/cpu.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> Core Stack & Pilares Técnicos

#### <img src="https://api.iconify.design/bi/server.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Plataforma, Virtualización & Contenedores
- **Virtualización:** Proxmox VE (Debian), Incus (Ubuntu), LXC, KVM/QEMU (VMs).
- **Contenedores:** Podman + Quadlets, containerd, Docker.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Podman es el runtime prioritario; Docker se usa solo cuando una herramienta lo requiere explícitamente.</small>*
- **Orquestación:** Kubernetes (K3s / MicroK8s).  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>K3s es el orquestador principal; MicroK8s se usa solo para escenarios específicos.</small>*
- **Host OS:** Debian, Ubuntu, Alpine Linux.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Alpine Linux es el OS base prioritario para LXC, VMs, Podman y Docker siempre que sea técnicamente posible.</small>*

#### <img src="https://api.iconify.design/bi/code-slash.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Automatización, IaC & GitOps
- **IaC:** OpenTofu, Ansible.
- **Gestión de configuración:** Ansible + SSH.
- **GitOps:** Flux CD.
- **CI/CD:** Forgejo Actions + Woodpecker CI.
- **Automatización de flujos:** n8n.

#### <img src="https://api.iconify.design/bi/shield-lock.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Seguridad, Secretos & Redes
- **DNS & Servicios Internos:** DNSMASQ.
- **Zero Trust & Redes:** WireGuard, Cloudflare (Tunnels, WAF, Zero Trust), HAProxy, Keepalived.
- **Secretos & PKI:** OpenBao, Forgejo Secrets, Smallstep.
- **Runtime Security:** eBPF (Tetragon/Falco).
- **Auditoría & Hardening:** Kali Linux, Lynis.
- **Supply Chain Security:** SLSA, Sigstore, Trivy, Grype, GUAC, Bomctl.

#### <img src="https://api.iconify.design/bi/database.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Persistencia, Datos & Mensajería
- **Bases de datos:** PostgreSQL (CloudNativePG), SQLite, MariaDB, Valkey.
- **Almacenamiento:** MinIO, Incus Storage Bucket, NFSv4, RAID1/5.
- **Mensajería & Event Bus:** NATS, MQTT.

#### <img src="https://api.iconify.design/bi/speedometer2.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Observabilidad & Performance
- **Métricas & Logs:** VictoriaMetrics, OpenObserve, Beszel, Kener, Rsyslog, syslog-ng.
- **Kernel Observability:** perf, eBPF, bpftrace, cgroups v2, tuned.
- **Benchmarking:** fio, iperf3.
- **Service Mesh:** Linkerd (mTLS, observabilidad).

#### <img src="https://api.iconify.design/bi/cpu-fill.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> IA Soberana & Servicios Cloud
- **IA Local:** LocalAI, Fabric, MCP Server.
- **Cloud Services:** GCP Free Tier (Cloud Run, Firestore, Cloud Storage).
- **Edge & CDN:** Cloudflare Free Tier (Pages, Workers, D1, R2, KV).
- **FinOps:** Arquitecturas de **$12/mes de OpEx total** — 2 Droplets de DigitalOcean ($6 c/u) + GCP y Cloudflare Free Tier ($0).

---

<details>
  <summary>
    <img src="https://api.iconify.design/bi/journal-bookmark-fill.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 8px;">
    <b>Catálogo de Publicaciones & Libros Técnicos [En Desarrollo]</b>
  </summary>

<br/>

*Próximamente compartiremos una serie de más de 25 manuales y libros técnicos diseñados para la formación en ingeniería soberana:*

- **Linux OS & Kernel Internals:** Guías profundas sobre arquitectura del sistema operativo, automatización con scripting avanzado, observabilidad de kernel y *tuning* de rendimiento.
- **Networking, Defense & Ethical Hacking:** Manuales prácticos de enrutamiento (IPv4/IPv6), arquitectura de red soberana, pentesting defensivo/ofensivo y auditoría de tráfico.
- **On-Premise Virtualization & Cloud:** Arquitecturas de virtualización en línea de comandos, gestión avanzada de clusters, contenedores de sistema y despliegues híbridos en la nube.
- **IaC, Orchestration & Sovereign CI/CD:** Guías de automatización declarativa con OpenTofu, Ansible y n8n, orquestación de contenedores (K8s/OCI) y pipelines de CI/CD autogestionados.
- **Offensive/Defensive Coding & Config:** Desarrollo de herramientas de ciberseguridad en Go, TypeScript para infraestructura, estructuras de datos aplicadas y dominio de lenguajes de configuración (YAML, JSON, TOML, CUE).
- **System Design, Data & Sovereign AI:** Patrones de diseño de sistemas distribuidos a gran escala, gestión y persistencia de bases de datos, e integración de stacks de IA soberana para defensa.

*(Los títulos y accesos se irán liberando progresivamente)*

</details>
