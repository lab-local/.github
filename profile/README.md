<div align="center" style="overflow: hidden; max-height: 220px;">
  <img src="https://raw.githubusercontent.com/lab-local/.github/main/profile/buque_contenedor_vector.jpeg" 
       alt="LAB.LOCAL — Infraestructura y contenedores" 
       width="100%" 
       style="object-fit: cover; object-position: center; margin-top: -20%; margin-bottom: -20%;">
</div>

# LAB.LOCAL
### <img src="https://api.iconify.design/bi/terminal.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> ¿Qué es LAB.LOCAL?

**LAB.LOCAL** es un laboratorio de ingeniería de infraestructura y plataformas de producción. Diseñamos, desplegamos y operamos arquitecturas híbridas orientadas a **máximo rendimiento, seguridad por diseño y soberanía tecnológica**, optimizando costos al límite sin comprometer la resiliencia.

---

### <img src="https://api.iconify.design/bi/lightbulb.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> Aplicaciones en la Vida Real

LAB.LOCAL no es solo un stack técnico: es una propuesta open source para pequeñas y medianas organizaciones, y para profesionales que quieren infraestructura de producción sin depender de grandes presupuestos ni de la nube propietaria.

#### <img src="https://api.iconify.design/bi/people.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> ¿Para quién es esto?
- **Startups y MVPs** que necesitan infraestructura sólida desde el día uno, sin sobreaprovisionar.
- **Pymes** que quieren migrar de servicios cloud caros a infraestructura híbrida propia.
- **Equipos de TI pequeños** que necesitan automatización, seguridad y observabilidad sin un equipo dedicado de SRE.
- **Laboratorios y entornos educativos** que buscan un stack reproducible y soberano.
- **Consultores y freelancers** que despliegan para clientes y quieren reutilizar su stack.

#### <img src="https://api.iconify.design/bi/gear.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Casos de uso reales
- **MVP en producción en semanas, no meses:** Proxmox o Incus para VMs, Podman o CRI-O para contenedores, K3s para orquestación, Flux CD para GitOps. Todo en hardware propio o en un VPS económico.
- **Alternativa híbrida a la nube:** Cloudflare Free Tier para CDN, WAF y DNS; GCP Free Tier para servicios serverless; el resto on-premise.
- **Automatización de una pyme:** Ansible para configuración, OpenTofu para provisioning, n8n para flujos entre servicios (facturación, notificaciones, integraciones).
- **Observabilidad sin Prometheus pesado:** Beszel para 1–50 máquinas, VictoriaMetrics para escalar, OpenObserve para logs.
- **Seguridad por diseño:** AppArmor para confinamiento, Tetragon/Falco para runtime, Sigstore para firmar artefactos, Trivy/Grype para escanear imágenes.
- **Laboratorio de aprendizaje:** Todo el stack es open source, reproducible y documentado. Ideal para formar equipos.

#### <img src="https://api.iconify.design/bi/graph-up.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Impacto medible
- **Costos:** free tiers estratégicos + hardware propio = factura cloud reducida drásticamente.
- **Tiempo:** GitOps + IaC = despliegues repetibles en minutos, no en horas.
- **Riesgo:** seguridad en capas (LSM, eBPF, Supply Chain) = menos superficie de ataque.
- **Soberanía:** los datos y los servicios críticos permanecen bajo tu control.
- **Escalabilidad:** el mismo stack sirve para 1 servidor o para 50, sin reescribir nada.

#### <img src="https://api.iconify.design/bi/rocket.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Cómo empezar
1. **Un servidor, un objetivo:** instala Proxmox o Incus y levanta tu primera VM o LXC.
2. **Contenedores con Podman:** reemplaza Docker donde sea posible; usa Quadlets para systemd.
3. **K3s para orquestar:** cuando necesites más de un nodo o despliegues declarativos.
4. **GitOps con Flux CD:** conecta tu repo Forgejo y sincroniza el estado.
5. **Observabilidad con Beszel:** empieza simple; escala a VictoriaMetrics cuando crezcas.
6. **Seguridad desde el inicio:** AppArmor, Trivy, Sigstore. No lo dejes para el final.

> *No necesitas todo el stack el primer día. Necesitas el primer paso.*

---

### <img src="https://api.iconify.design/bi/star.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> Qué nos hace únicos

No somos un stack más. Somos una propuesta coherente para quien quiere infraestructura moderna sin renunciar a soberanía, seguridad ni rendimiento.

#### <img src="https://api.iconify.design/bi/globe.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Soberanía sin sacrificio
Híbrido real: on-premise para lo crítico, free tiers estratégicos para lo demás. Sin vendor lock-in, sin facturas impredecibles, sin datos fuera de tu control.

#### <img src="https://api.iconify.design/bi/cpu.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> eBPF como base común
La misma tecnología que mide rendimiento protege el runtime. bpftrace para diagnóstico, cilium/ebpf para construcción en Go, bpftool para inspección. Rendimiento y seguridad no compiten: coexisten por diseño.

#### <img src="https://api.iconify.design/bi/shield-check.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Minimalismo como seguridad
Cada herramienta tiene un rol. Sin solapamientos, sin dependencias innecesarias, sin superficie de ataque extra. Podman, CRI-O, containerd: cada uno donde corresponde. Alpine como base cuando es posible.

#### <img src="https://api.iconify.design/bi/arrow-repeat.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Ciclo de ingeniería explícito
**Construimos → Automatizamos → Observamos → Optimizamos → Aseguramos.** Cada herramienta del stack está mapeada a un paso. No se optimiza lo que no se mide, no se asegura lo que no se entiende.

#### <img src="https://api.iconify.design/bi/people.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Comunidad hispana, conocimiento abierto
Stack documentado en español, +25 libros técnicos en camino, herramientas open source. No solo construimos infraestructura: construimos comunidad.

---

### <img src="https://api.iconify.design/bi/graph-up-arrow.svg?color=%237d8590" width="24" height="24" style="vertical-align: middle; margin-right: 8px;"> Beneficios para infraestructura y plataformas modernas

| Beneficio | Cómo se materializa |
|-----------|---------------------|
| **Reducción de costos** | Free tiers + hardware propio + FinOps |
| **Portabilidad real** | OCI + K8s + CO-RE = sin lock-in |
| **Seguridad en capas** | LSM + eBPF + Supply Chain + Zero Trust |
| **Rendimiento medible** | eBPF + perf + fio + iperf3 |
| **Soberanía tecnológica** | Datos y servicios bajo tu control |
| **Automatización completa** | IaC + GitOps + CI/CD |
| **Observabilidad real** | Métricas + logs + kernel + eBPF |
| **Reproducibilidad** | Todo declarativo, todo documentado |
| **Educación integrada** | Stack + libros + comunidad |
| **Escalabilidad** | De 1 servidor a cientos, mismo stack (Beszel → VictoriaMetrics) |

---

#### <img src="https://api.iconify.design/bi/server.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Plataforma, Virtualización & Contenedores
- **Virtualización:** Proxmox VE (Debian), Incus (Ubuntu), LXC, KVM/QEMU (VMs).
- **Contenedores:** Podman + Quadlets, containerd, **CRI-O**, Docker.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small><b>Runtimes de contenedores:</b> Podman para uso general (rootless, systemd, Quadlets); CRI-O y containerd como runtimes CRI para Kubernetes; Docker solo cuando una herramienta lo requiere. CRI-O destaca por su minimalismo y menor superficie de ataque, alineado con Fast & Secure by Design.</small>*
- **Orquestación:** Kubernetes (K3s / MicroK8s).  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>K3s es el orquestador principal; MicroK8s se usa solo para escenarios específicos. CRI-O se usa como runtime CRI ligero cuando se busca mínima superficie de ataque.</small>*
- **Host OS:** Debian, Ubuntu, Alpine Linux.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Alpine Linux es el OS base prioritario para LXC, VMs, Podman y Docker siempre que sea técnicamente posible.</small>*

#### <img src="https://api.iconify.design/bi/code-slash.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Automatización, IaC & GitOps
- **Control de versiones:** Forgejo (Git self-hosted).
- **Provisioning (IaC):** OpenTofu — infraestructura declarativa.
- **Gestión de configuración:** Ansible (sobre SSH) — estado deseado de los sistemas.
- **GitOps:** Flux CD — sincronización continua desde Git.
- **CI/CD:** Forgejo Actions, Woodpecker CI — pipelines autogestionados.
- **Orquestación de workflows:** n8n — automatización entre servicios.

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>OpenTofu provisiona infraestructura; Ansible configura los sistemas resultantes; Flux CD sincroniza el estado desde Git. Cada capa tiene su rol y no se solapan.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Woodpecker CI: alternativa ligera a GitHub Actions, integrada con Forgejo.</small>*

#### <img src="https://api.iconify.design/bi/shield-lock.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Seguridad, Secretos & Redes
- **DNS & DHCP:** DNSMASQ.
- **Zero Trust & Redes:** WireGuard, Cloudflare (Tunnel, WAF, Zero Trust), Nginx, HAProxy, Keepalived.
- **Secretos & PKI:** OpenBao, Forgejo Secrets, Smallstep.
- **Runtime Security (LSM & eBPF):**
  - *LSM:* AppArmor — confinamiento de aplicaciones.
  - *eBPF runtime:* Tetragon, Falco — detección y bloqueo de comportamiento anómalo en tiempo real.
  - *Diagnóstico:* bpftrace — tracing ad-hoc para investigación de incidentes.
  - *Construcción:* cilium/ebpf (Go) — agentes de seguridad portables con CO-RE.
- **Auditoría & Hardening:** Lynis, Kali Linux (pentesting).
- **Supply Chain Security:** SLSA, Sigstore, Trivy, Grype, GUAC, Bomctl.

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>AppArmor es el LSM prioritario para confinamiento de aplicaciones. Tetragon/Falco usan eBPF para detección y bloqueo en runtime. bpftrace cubre el diagnóstico ad-hoc; cilium/ebpf permite construir agentes de seguridad en Go, portables entre kernels con CO-RE.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small><b>Supply Chain Security en runtime:</b> la cadena no termina cuando despliegas. eBPF permite observar y proteger la ejecución — binarios no esperados, conexiones anómalas, syscalls fuera de política. La misma base que optimiza el rendimiento protege el runtime.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small><b>Fast & Secure by Design:</b> seguridad y rendimiento no compiten. AppArmor confina, eBPF observa y bloquea, y el mismo stack que mide rendimiento protege el sistema. Diseño, no parche.</small>*

#### <img src="https://api.iconify.design/bi/database.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Persistencia, Datos & Mensajería
- **Bases de datos relacionales:** PostgreSQL (CloudNativePG en K8s), MariaDB.
- **Bases de datos embebidas:** SQLite.
- **Caché & estructuras en memoria:** Valkey.
- **Almacenamiento de objetos:** MinIO e Incus Storage Bucket.
- **Almacenamiento en red:** NFSv4.
- **Almacenamiento físico:** RAID1/5/6.
- **Mensajería & Event Bus:** NATS, MQTT (Mosquitto).
- **Backup & replicación:** pgBackRest, restic, rsync.

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>CloudNativePG es el operador que gestiona PostgreSQL en Kubernetes; PostgreSQL es la base de datos subyacente. SQLite se usa para aplicaciones embebidas o edge; no compite con PostgreSQL.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Valkey es el fork open source de Redis, mantenido por la Linux Foundation. MinIO e Incus Storage Bucket proveen almacenamiento S3-compatible on-premise. NATS para mensajería ligera; MQTT para IoT y dispositivos.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small><b>Backup & replicación:</b> ninguna arquitectura de datos es completa sin estrategia de recuperación. pgBackRest para PostgreSQL, restic para backups cifrados, rsync para sincronización.</small>*

#### <img src="https://api.iconify.design/bi/speedometer2.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> Observabilidad & Performance
- **Métricas & Dashboards:** Beszel (vista 360 ligera), VictoriaMetrics, OpenObserve, Kener.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>Beszel es el punto de entrada ideal para flotas de 1 a 50 máquinas (su sweet spot de diseño, con arquitectura de un solo Hub y SQLite para hasta ~100 hosts). Al superar ese umbral, donde el historial y la concurrencia empiezan a tensionar la base de datos embebida, VictoriaMetrics toma el relevo para escalar a cientos o miles de servidores con PromQL.</small>*
- **Logs:** Rsyslog, syslog-ng.
- **Kernel Observability:**
  - *Profiling de CPU:* perf.
  - *Tracing Ad-hoc:* **bpftrace** — una línea, sin compilar, respuesta inmediata.
  - *Construcción en Go:* **cilium/ebpf** — herramientas portables con CO-RE, binario único sin CGO, integrables en Kubernetes.
  - *Inspección & Skeletons:* **bpftool** — listar programas y mapas, generar skeletons.
  - *Control de recursos:* cgroups v2.
  - *Ajuste de sistema:* tuned.
- **Benchmarking:** fio (disco), iperf3 (red).
- **Service Mesh:** Linkerd (mTLS, observabilidad).

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>eBPF es la infraestructura de kernel (máquina virtual) que habilita herramientas como bpftrace y cilium/ebpf. El programa que corre en el kernel se escribe en C y se compila con clang; el loader que lo carga y gestiona se escribe en Go con cilium/ebpf. No se invoca directamente.</small>*

<img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small><b>Fast & Secure by Design:</b> bpftrace para diagnóstico rápido en producción; cilium/ebpf en Go para construir herramientas estables y distribuibles; bpftool para inspección. La misma base eBPF sirve a rendimiento y seguridad — no como trade-off, sino como decisión de diseño.</small>*

#### <img src="https://api.iconify.design/bi/cpu-fill.svg?color=%237d8590" width="20" height="20" style="vertical-align: middle; margin-right: 6px;"> IA Soberana & Servicios Cloud
- **IA Local:** OpenCode, NanoClaw, MCP Server.  
  <img src="https://api.iconify.design/bi/info-circle.svg?color=%237d8590" width="14" height="14" style="vertical-align: middle; margin-right: 4px;"> *<small>OpenCode: asistente de código local. NanoClaw: runtime ligero para agentes. MCP Server: protocolo de contexto para modelos.</small>*
- **Cloud Services:** GCP Free Tier (Cloud Run, Firestore, Cloud Storage).
- **Edge & CDN:** Cloudflare Free Tier (Pages, Workers, D1, R2, KV).
- **FinOps:** Disciplina financiera aplicada a la ingeniería — free tiers estratégicos, almacenamiento local eficiente y monitoreo activo para evitar sobreaprovisionamiento, sin comprometer resiliencia ni rendimiento.

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

---

> *Fast & Secure by Design.*  
> *Herramientas **open source** y libros técnicos para la comunidad tech en español.*  
> *Construido desde cero, con disciplina de ingeniería y pasión por compartir.*  
> *Enseñar también es asegurar.*
