<!-- Cyberpunk Banner -->
<div align="center">
  <img src="./assets/banner.png" width="100%" alt="Cyberpunk Banner"/>
</div>

<h1 align="center">🛡️ ThryLox — Enterprise Cloud Identity & GRC Security Engineer</h1>

<p align="center">
  <a href="https://github.com/ThryLox">
    <img src="https://komarev.com/ghpvc/?username=ThryLox&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
  </a>
</p>

> [!IMPORTANT]
> **Federal GRC Guardrails & Identity Compliance Baseline Enforced**  
> Aligned with ITSG-33, NIST SP 800-53 r5, Zero Trust Architecture, and TBS Cloud Guardrails. I specialize in translating complex security policies into automated policy-as-code audits, securing Azure/M365 cloud environments, and engineering high-resilience, low-blast-radius security systems.

---

## 🟣 Who Am I?

I am an **Enterprise Cloud Identity and Compliance professional** supporting Azure and Microsoft 365 platforms in federal government environments. My mission is to build highly secure, transparent, and auditable systems by merging defensive software engineering with formal compliance frameworks.

**Core Architectural Principles:**
- 🔑 **Identity as the Primary Boundary:** Enforcing strict conditional access, multi-tenant directory isolations, and role-based privilege segregation.
- 🤖 **Zero-Trust AI Containment:** Designing secure token vaults for LLM-driven remediation tools, ensuring AI operates inside sandboxed, step-up authorized gates.
- 📊 **Policy-as-Code Automation:** Automating continuous control validation so that GRC evidence is programmatically compiled rather than manually gathered.

---

## ⚖️ GRC & Compliance Control Matrix

This control matrix maps my flagship repositories directly to formal security guidelines, demonstrating how abstract compliance requirements are translated into functional, automated codebases:

| GRC Control ID | Regulatory Framework | Security Control Domain | Automated Technical Solution |
| :--- | :--- | :--- | :--- |
| **ITSG-33 / NIST AC-2** | ITSG-33 / NIST SP 800-53 | Account & Access Control Boundary | **[aegis-sentinel](https://github.com/ThryLox/aegis-sentinel)**: Zero-Trust cloud auditing using Auth0 Token Vault and Step-Up authentication gates to limit LLM blast radius. |
| **ITSG-33 / NIST SI-4** | ITSG-33 / NIST SP 800-53 | Information System Monitoring (Telemetry) | **[ssl-ids-2026](https://github.com/ThryLox/ssl-ids-2026)**: Self-supervised network intrusion detection (PyTorch) using contrastive manifolds and LOATO zero-day evaluation. |
| **ITSG-33 / NIST PL-2** | ITSG-33 / NIST SP 800-53 | System Security Planning (Human Factors) | **[CogSec](https://github.com/ThryLox/CogSec)**: Cognitive Threat Modeling Assistant evaluating user automation bias, alert fatigue, and cognitive load limits. |
| **TBS Guardrail 2** | TBS Cloud Guardrails | Cloud Tenant Identity Separation | **[project-gavel](https://github.com/ThryLox/project-gavel)**: Python compliance auditing engine verifying M365 and Azure environments against YAML policy rules. |
| **NIST SC-8 / SC-28** | NIST SP 800-53 | Data in Transit & at Rest Protection | **[mini-explanations](https://github.com/ThryLox/mini-explanations)**: A defensive laboratory proving secure OIDC handshakes, SQLi query sanitizations, and XSS input filters. |
| **ITSG-33 / NIST SI-4** | ITSG-33 / NIST SP 800-53 | Telemetry Drift & Anomaly Auditing | **[drift-research](https://github.com/ThryLox/drift-research)**: Statistical analysis monitoring logs for data/concept drift via KS-tests and Population Stability Index (PSI). |

---

## 🚀 Curated Flagship Projects

### 🛡️ [Aegis Sentinel](https://github.com/ThryLox/aegis-sentinel) — Autonomous Zero-Trust Cloud Security Auditor
*An advanced cloud security orchestrator that identifies infrastructure vulnerabilities and operates under a strict, step-up human-authorization paradigm.*
- **The Security Challenge:** Granting AI agents permanent, high-privilege write access is an unacceptable risk. Aegis Sentinel can *detect* threats autonomously, but is blocked from *remediation* without human Step-Up authentication.
- **Technical Architecture:** Built with **Node.js** and **Auth0 Token Vault**. Gemini 2.5 Flash acts as the threat intelligence scanner. When a fix is proposed, the agent initiates an Auth0 Step-Up challenge, securely retrieving scoped API tokens (like a GitHub PAT) from the vault only after the user explicitly grants access.
- **Compliance Alignment:** ITSG-33 / NIST SP 800-53 **AC-2 (Access Control)**, **AC-3 (Dual Authorization)**, and **AC-6 (Least Privilege)**.

### 🧠 [CogSec](https://github.com/ThryLox/CogSec) — Cognitive Threat Modeling Assistant (CTMA)
*A world-class cybersecurity forensic application shifting threat modeling from "System-Centric" to "Human-Centric" by analyzing cognitive failure boundaries.*
- **Technical Architecture:** Built with **React, TypeScript, and Vite**, powered by **Gemini 3 Pro**. Ingests millisecond-level telemetry from the **Cognitive Telemetry Sandbox (CTS)** mapping user workload, alert density, visual alert similarity, and response latency.
- **Cognitive Science Engines:** Quantifies the point of cognitive overload based on *Dual Process Theory* (Kahneman), *Cognitive Load Theory* (Sweller), and *Vigilance Decrement* (Mackworth) to identify habituation loops where users dismiss critical alerts in <500ms due to visual similarity.
- **Compliance Alignment:** ITSG-33 / NIST SP 800-53 **PL-2 (Security Planning)**, **AR-4 (Privacy-by-Design)**, and **AT-3 (Security Training)**.

### 🌐 [ssl-ids-2026](https://github.com/ThryLox/ssl-ids-2026) — Self-Supervised Network Intrusion Detection
*Academic-grade manifold novelty detection utilizing Contrastive Self-Supervised Learning (SSL) to learn a behavioral baseline of normal network traffic.*
- **Technical Architecture:** Core implementation in **PyTorch**. Optimizes an MLP encoder via **InfoNCE loss** to project network flows into a geometrically stable 32-dimensional unit hypersphere. Anomalies and zero-day threats are detected as statistical displacements using a regularized Mahalanobis distance metric (Ledoit-Wolf shrinkage).
- **Evasion Resilience:** Benchmarked against the **CIC-IDS2017 dataset** using a strict **Leave-One-Attack-Type-Out (LOATO)** validation protocol. Achieves high detection rates at a strict 1% False Positive Rate (FPR) threshold to eliminate SOC alert fatigue.
- **Compliance Alignment:** ITSG-33 / NIST SP 800-53 **SI-4 (System Monitoring)**, **SC-8 (Transmission Confidentiality)**, and **SC-28 (Protection of Information at Rest)**.

---

## 🧰 Tech Arsenal & Specialized Capabilities

### 🔑 Identity & Access Management (IAM)
<img src="https://img.shields.io/badge/Microsoft_Entra_ID-008AD7?style=for-the-badge&logo=microsoft&logoColor=white"/> <img src="https://img.shields.io/badge/Conditional_Access-0b75b6?style=for-the-badge&logo=azure&logoColor=white"/> <img src="https://img.shields.io/badge/Auth0_Token_Vault-EB5424?style=for-the-badge&logo=auth0&logoColor=white"/> <img src="https://img.shields.io/badge/MFA_Enforcement-000000?style=for-the-badge&logo=security&logoColor=green"/>

### ⚖️ GRC Compliance Frameworks
<img src="https://img.shields.io/badge/ITSG--33_Baseline-123456?style=for-the-badge&logo=government&logoColor=white"/> <img src="https://img.shields.io/badge/NIST_SP_800--53-002F6C?style=for-the-badge&logo=nist&logoColor=white"/> <img src="https://img.shields.io/badge/Zero_Trust_Architecture-818cf8?style=for-the-badge&logo=lock&logoColor=white"/> <img src="https://img.shields.io/badge/TBS_Cloud_Guardrails-000000?style=for-the-badge&logo=shield&logoColor=orange"/>

### 🛠️ Security Engineering & Automation
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/> <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white"/> <img src="https://img.shields.io/badge/OPA_Rego-3C82F6?style=for-the-badge&logo=open-policy-agent&logoColor=white"/>

### ☁️ Platforms & Infrastructure
<img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white"/> <img src="https://img.shields.io/badge/Microsoft_365-FF5F00?style=for-the-badge&logo=microsoft-office&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>

---

## 💬 Active GRC Systems Log Console
```text
[2026-05-26] [INFO] Initiating Zero Trust handshakes...
[2026-05-26] [PASS] aegis-sentinel: Auth0 Token Vault conforms to NIST AC-2 access controls.
[2026-05-26] [PASS] project-gavel: OPA policy-as-code audits conform to TBS Guardrail 2.
[2026-05-26] [PASS] ssl-ids-2026: PyTorch InfoNCE manifold analysis conforms to NIST SI-4 monitoring.
[2026-05-26] [PASS] CogSec: Cognitive load sandbox telemetry conforms to ITSG-33 PL-2 system planning.
[2026-05-26] [INFO] Security Health Index: 100% Audited & Compliant.
```

---

## 🐍 Contribution Graph  

<div align="center">
  <img src="https://raw.githubusercontent.com/ThryLox/ThryLox/output/snake.svg" alt="Snake Animation" width="100%" />
</div>

---

<p align="center">
  <sub>🚀 Engineered securely with neon, logic, and compliant GRC guardrails.</sub>
</p>
