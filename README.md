# Hi, I'm Ubaid ur Rehman 👋
### IT Support Specialist | Infrastructure & Cloud Administrator

Welcome to my portfolio! I specialize in core IT operations, data center telemetry, physical hardware deployment, and enterprise Azure hybrid cloud infrastructure.

---

## 🛠️ Core Infrastructure & Cloud Validation Labs

### 🌐 1. Advanced Hybrid Networking & Dynamic Routing (BGP)
* **Objective:** Architectural setup of cross-premises routing and inter-VNet transit.
* **Key Tasks:** Deployed Virtual Network Gateways and Local Network Gateways to establish active Site-to-Site IPsec VPN tunnels. Enabled **Border Gateway Protocol (BGP)** using Azure standard default ASN (`65515`) to handle dynamic route propagation.
* **Validation:** Verified multi-region Global VNet Peering transit paths ensuring data runs exclusively over the private Microsoft global backbone network.


**View Full Lab & Screenshots:** 🔗 [Click here to view my Load Balancer Repository](https://github.com/ubaid-1987/az104-load-balancing-architecture)

---

### 🌐 3. Hub-and-Spoke VNet Routing & Transit Architecture
* **Objective:** Deployed a hub-and-spoke multi-VNet design to handle centralized traffic control and cross-premises pathing.
* **Key Tasks:** Configured regional peering structures with custom Route Tables (UDRs) to handle transitive routing pathways through a central hub infrastructure layer.
* **View Full Lab & Screenshots:** 🔗 [Click here to view my Hub-and-Spoke Repository](https://github.com/ubaid-1987/azure-hub-and-spoke-architecture)

---


### 🚀 4. App Services, Deployment Slots & Containerized Tasks
* **Objective:** Architected scalable web hosting and serverless compute processing modules.
* **Key Tasks:** Leveraged Azure App Service Deployment Slots for zero-downtime production swaps, and deployed on-demand Azure Container Instances (ACI) alongside application traffic telemetry logs.
* **View Full Lab & Screenshots:** 🔗 [Click here to view my App Service Repository](https://github.com/ubaid-1987/azure-app-services-and-containers)


---

### 🛡️ 5. Business Continuity, Azure Backup & Item Recovery
* **Objective:** Built data protection policies and automated backup recovery structures.
* **Key Tasks:** Provisioned Recovery Services Vaults to manage snapshots, and executed operational item-level restorations by dynamically mounting target disks via secure iSCSI executables.
* **View Full Lab & Screenshots:** 🔗 [Click here to view my Backup & Recovery Repository](https://github.com/ubaid-1987/azure-backup-and-recovery-vaults)
---

### 🔐 3. Cloud Identity, Access Control & Governance
* **Objective:** Hardening platform authentication and implementing strict least-privilege control loops.
* **Key Tasks:** Configured **Self-Service Password Reset (SSPR)** registration flows, customized directory security boundaries, and tested Azure AD (Entra ID) enterprise logic.
* **Validation:** Resolved data-plane authentication blocks by mapping node-level **Kubelet managed identities** with explicit `AcrPull` security roles to safely communicate with private Azure Container Registries (ACR).


---

### 🔌 4. Systems Telemetry & Physical Operations
* **Objective:** Monitoring mission-critical infrastructure metrics across cloud resources and physical data centers.
* **Key Tasks:** Enabled **Container Insights** on active cluster runtimes, streaming operational stdout/stderr console data directly into Log Analytics Workspaces to run **Kusto Query Language (KQL)** diagnostic traces.
* **Hardware Scope:** Experienced with physical server rack assembly, CCTV camera matrix layout planning, environmental telemetry monitoring, and physical layer hardware troubleshooting.

