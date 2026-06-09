# Hi, I'm Ubaid ur Rehman 👋
### IT Support Specialist | Infrastructure & Cloud Administrator

Welcome to my portfolio! I specialize in core IT operations, data center telemetry, physical hardware deployment, and enterprise Azure hybrid cloud infrastructure.

---

## 🛠️ Core Infrastructure & Cloud Validation Labs

### 🌐 1. Advanced Hybrid Networking & Dynamic Routing (BGP)
* **Objective:** Architectural setup of cross-premises routing and inter-VNet transit.
* **Key Tasks:** Deployed Virtual Network Gateways and Local Network Gateways to establish active Site-to-Site IPsec VPN tunnels. Enabled **Border Gateway Protocol (BGP)** using Azure standard default ASN (`65515`) to handle dynamic route propagation.
* **Validation:** Verified multi-region Global VNet Peering transit paths ensuring data runs exclusively over the private Microsoft global backbone network.

[![VNet Peering & Routing Topology](Peering (1).png)
![BGP Route Verification Table](YOUR_BGP_IMAGE_NAME.png)](https://github.com/ubaid-1987/az104-load-balancing-architecture)

---

### 📦 2. Enterprise Storage & Data Persistence
* **Objective:** Configuring resilient, high-availability data layers for applications and hybrid systems.
* **Key Tasks:** Provisioned storage configurations across LRS/GRS tiers. Engineered stateful persistence for container configurations by mounting secure **Azure File Shares (SMB)** directly into isolated Azure Container Instances (ACI).
* **Validation:** Verified endpoint data integrity and path maps to prevent post-restart container data loss.

![Storage Architecture & Mounting](YOUR_STORAGE_IMAGE_NAME.png)

---

### 🔐 3. Cloud Identity, Access Control & Governance
* **Objective:** Hardening platform authentication and implementing strict least-privilege control loops.
* **Key Tasks:** Configured **Self-Service Password Reset (SSPR)** registration flows, customized directory security boundaries, and tested Azure AD (Entra ID) enterprise logic.
* **Validation:** Resolved data-plane authentication blocks by mapping node-level **Kubelet managed identities** with explicit `AcrPull` security roles to safely communicate with private Azure Container Registries (ACR).

![Identity Access and RBAC Logs](YOUR_IDENTITY_IMAGE_NAME.png)

---

### 🔌 4. Systems Telemetry & Physical Operations
* **Objective:** Monitoring mission-critical infrastructure metrics across cloud resources and physical data centers.
* **Key Tasks:** Enabled **Container Insights** on active cluster runtimes, streaming operational stdout/stderr console data directly into Log Analytics Workspaces to run **Kusto Query Language (KQL)** diagnostic traces.
* **Hardware Scope:** Experienced with physical server rack assembly, CCTV camera matrix layout planning, environmental telemetry monitoring, and physical layer hardware troubleshooting.

![Log Analytics and Telemetry Dasboard](Peering (2).png)
