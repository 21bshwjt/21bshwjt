<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=0078D4&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B%2C+I'm+Biswajit+Biswas;Cyber+Security+Architect+%7C+Identity-First+Security;500%2B+SaaS+Apps+Migrated+%C2%B7+45K%2B+Users+Separated;Securing+AD+%C2%B7+Entra+ID+%C2%B7+Okta+%C2%B7+Microsoft+365;Zero+Trust+%C2%B7+Privileged+Access+%C2%B7+PKI;Security+Automation+with+PowerShell+%26+Graph+API" alt="Typing SVG" />

# Biswajit Biswas

### 🛡️ Cyber Security Architect · Identity & Access Management · Security Automation

**Identity is the new perimeter — I design, harden, and automate it.**
With **20+ years** in enterprise identity and security, I help organizations reduce identity-driven risk across hybrid Active Directory, Microsoft Entra ID, and Okta, and turn security posture into measurable, automated controls.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bshwjt/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/21bshwjt)
![Location](https://img.shields.io/badge/Location-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 🎯 At a Glance

| | |
|---|---|
| **Role** | Cyber Security Architect — Identity & Access Management |
| **Experience** | **20+ years** in enterprise identity, infrastructure & security |
| **Scale** | ~600,000-user Microsoft 365 tenant · Hybrid identity |
| **Signature Deliveries** | 🔀 **Divestiture tenant separation:** **500+ SaaS apps** (SAML/OIDC) and **45,000+ users** moved to a new Entra ID tenant ahead of the TSA deadline, with zero business disruption<br/>💰 **Cost & entitlement optimization:** about **$35,000 a year** cut from Microsoft 365 licensing by finding underused and wrongly assigned SKUs and removing unused access<br/>📊 **M365 Identity Posture Management:** **400+ automated security checks** across Entra ID, Defender, Intune, Purview and Global Secure Access, mapped to CIS controls |
| **Core Domains** | IAM · On-Prem Active Directory · Hybrid Identity · SSO Federation (SAML / OIDC) · Tenant-to-Tenant Migration (M&A / Divestiture) · PAM / Entra PIM · IGA · Guest (B2B) & Workload Identity Security · PKI & Certificate Lifecycle · Microsoft 365 Security · License & Entitlement Optimization |
| **Platforms** | Active Directory · Microsoft Entra ID · Microsoft PKI (AD CS) · CyberArk Cloud PKI · Okta · Azure · Microsoft 365 |
| **Frameworks** | Zero Trust · Microsoft Enterprise Access Model (Tiering) · CIS Benchmarks |
| **Automation & DevOps** | PowerShell · Microsoft Graph API · Azure Automation · Key Vault · GitHub Actions · Azure DevOps · Atlassian Jira |
| **Logging** | Azure Log Analytics |

---

## 🧭 What I Bring to a Security Program

**🏛️ Identity Security Architecture**
Design Zero Trust identity architectures — tiered administration, Conditional Access frameworks, and least-privilege models that scale across hybrid environments.

**🔀 Identity Migration & Tenant Separation**
Lead large-scale identity programs for M&A and divestitures. I design wave-based migration frameworks and move SAML/OIDC SSO apps and users between Entra ID tenants, keeping the business running and meeting the TSA deadline.

**🔑 Privileged Access & Governance**
Reduce standing privilege with Entra PIM, JIT / JEA, and access reviews; bring guest users and workload identities (service principals, managed identities) under governance.

**🛡️ Attack-Surface Reduction & Hardening**
Assess and harden AD, Entra ID, and Okta tenants against real-world identity attacks — legacy authentication, weak ciphers, misconfigured trusts, and over-privileged identities.

**⚙️ Security Automation & Posture Visibility**
Turn manual checks into automated, repeatable reporting with PowerShell and Graph API — giving leadership continuous visibility into identity posture.

---

## 📈 Impact Highlights

- 🔀 Led the **divestiture identity migration of 500+ SaaS applications (SAML / OIDC)** to a new Microsoft Entra ID tenant. SSO kept working throughout, with **zero business disruption**. I designed the wave-based migration framework and automated app onboarding with **Graph API & PowerShell**, separating **45,000+ users** ahead of the TSA deadline
- 🌐 Securing identity at enterprise scale — a **~600,000-user Microsoft 365 tenant** with hybrid Active Directory
- 💰 Led **Microsoft 365 & Active Directory licensing and entitlement optimization** across enterprise tenants. Automated, data-driven analysis found underused and wrongly assigned SKUs (E3/E5, EMS, add-ons) and unused access. Targeted fixes cut annual licensing spend by **~$35,000** and reduced excessive access risk
- 🧹 Reducing standing privileged access through **Entra PIM, JIT / JEA and tiered administration**
- 🔑 Running **Entra PIM audits**. These cover permanent vs. eligible role assignments, activation settings, approval and MFA requirements, and Global Admin sprawl, so standing access can be turned into just-in-time access
- 👥 Auditing **guest users (B2B)** — stale accounts, excessive access & external collaboration risk
- 🤖 Auditing **workload identities** — service principals, app registrations, managed identities, credentials & API permissions
- 🧩 Moving **app credential lifecycle to self-service** with the [Entra Apps Management](https://github.com/21bshwjt/Entra-Apps-Management) portal. Owners rotate secrets, certificates and federated credentials themselves, so these requests no longer arrive as tickets. Credentials expire less often without anyone noticing. Over-privileged apps get guardrails
- 🚫 Detecting and retiring **legacy authentication & weak ciphers** across domain controllers
- 📊 Built a **Microsoft 365 Identity Posture Management** platform: **400+ automated security checks** that replace manual reviews and give leadership continuous, evidence-based visibility into identity risk ([details below](#-microsoft-365-identity-posture-management))

---

## 📊 Microsoft 365 Identity Posture Management

> **400+ automated security checks** across Entra ID, Defender, Intune, Purview and Global Secure Access, built with **PowerShell and Microsoft Graph (v1.0 and beta)**.
> They turn a tenant's sprawling configuration into a repeatable, auditable view of identity risk, so drift, misconfigurations and over-privilege are found early instead of after an incident.

| Pillar | What It Continuously Assesses |
|---|---|
| 🏆 **Secure Score & Benchmarks** | Secure Score trend (last 90 days), control profiles mapped to **CIS controls**, Defender recommendations, Defender for Identity health and sensors |
| 🔐 **Authentication & MFA** | Phishing-resistant and passwordless authentication strengths, system-preferred MFA, authentication methods policy, Authenticator fatigue, banned passwords, Security Defaults, token lifetimes |
| 🚦 **Conditional Access** | Policy deep-dive, built-in templates, named locations, protected actions, authentication contexts |
| 🧱 **Tenant Hardening** | Stops non-admin users from creating apps, tenants or security groups and from reading other users; restricts guest invites and user consent for risky apps; checks admin consent workflow, authorization policy and SPF records |
| 👑 **Privileged Access** | **Entra PIM audit** for users, groups and service principals; **Global Administrator audit** (users, groups and SPNs with a full summary); role-definition mapping |
| 🤖 **Workload Identities** | App registration owners and secret/certificate expiry, SPN permissions, roles, sign-ins and locations, inactive SPNs, Graph permissions catalog, app consent audit, app management policy |
| 👥 **Guests & B2B** | Guest roles and group memberships, dynamic guest groups, multi-tenant organizations and B2B partners |
| 🧬 **Identity Governance (IGA)** | Access packages, access reviews, custom extensions, lifecycle workflows and task definitions |
| 🚨 **Incident Response (CFIR)** | Defender alerts and incidents, legacy-client sign-ins, repeated failed sign-ins, OAuth consent grants, Identity Protection |
| 💻 **Devices & Intune** | Device registration and configuration, Intune compliance policies, automatic enrollment |
| 🌐 **Global Secure Access** | Enterprise apps, devices, Private Access users, service status, traffic logs |
| 🔄 **Hybrid Identity** | On-premises sync status, Entra Connect extension attributes, custom and verified domains |
| 💰 **Licensing & Data** | License matrix and insights, admin and user licenses, tenant quota, Purview sensitivity labels, SharePoint Online and Microsoft Forms settings |

**Impact:** Tenant reviews that used to be slow and manual now run **on demand**. Findings are evidence-based and mapped to **CIS**. Results feed directly into Conditional Access hardening, PIM cleanup, workload-identity remediation and license optimization.

---

## 🔎 Security Assessment Expertise

| Area | What It Covers |
|---|---|
| 🆔 Microsoft 365 / Entra ID Security Assessment | Tenant-wide security posture review with prioritized, risk-ranked remediation |
| 🔒 Conditional Access Gap Analysis | Policy coverage mapping, bypass detection & Zero Trust hardening |
| 🔑 Privileged Access & Entra PIM Audit | Eligible vs. permanent role assignments, activation settings, approval & MFA requirements, JIT / JEA design |
| 👥 Guest User (B2B) Audit | Stale & inactive guests, guest privileges, cross-tenant access settings & access reviews |
| 🤖 Workload Identity Audit | Service principals, app registrations & managed identities — expiring/over-privileged credentials, high-risk Graph permissions & consent review |
| 🛡️ Tenant Hardening & Baselines | CIS Benchmark reporting & security baseline enforcement |
| 📡 Hybrid Identity Monitoring | Entra Connect health, sync integrity & AD security monitoring |
| 🏰 Active Directory Security | Tier-0 protection, replication health, legacy protocol & cipher detection |

---

## 📌 Featured Projects

| Project | Security Problem Solved | Tech |
|---|---|---|
| [🧩 Entra Apps Management](https://github.com/21bshwjt/Entra-Apps-Management) | Self-service portal for app owners: they rotate secrets, certificates, federated credentials and owners themselves, with no ticket to the admin team. Owners sign in with Entra SSO and see only the apps they own. It uses delegated Graph, blocks high-risk (privileged) apps, rejects weak certificates (RSA under 2048 bits, SHA-1), refuses guests, sends expiry e-mails and keeps a full audit log | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Graph API](https://img.shields.io/badge/Graph_API-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Entra](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| [🔑 Entra Hybrid Identity Toolkit](https://github.com/21bshwjt/entra-hybrid-identity-toolkit) | Administration toolkit for securing and operating hybrid Entra identity | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Entra](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| [🛡️ EntraID Graph Toolkit](https://github.com/21bshwjt/EntraID-Graph-Toolkit) | Microsoft Graph security recipes — Global Admin audit (active + PIM-eligible), Conditional Access what-if evaluation, blocking app client secrets, compromised-account response & app-only auth (certificate, managed identity, Key Vault) | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Graph API](https://img.shields.io/badge/Graph_API-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Entra](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| [⚙️ Az AutomationRunbooks](https://github.com/21bshwjt/AzAutomationRunbooks) | Secure, scheduled cloud automation with Azure Automation runbooks | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| [🏗️ Build Replica DomainController](https://github.com/21bshwjt/Build_Replica_DomainController) | Consistent, automated replica DC deployment — reduces configuration drift | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🎫 Atlassian Jira Automation](https://github.com/21bshwjt/Atlassian_Jira_Automation) | Jira Cloud REST API automation — API token validation, bulk issue updates & Excel reporting, following secure API-token practices | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |
| [🚀 GitHub Actions Jira Reporting](https://github.com/21bshwjt/GHActions_JIRA) | Serverless, one-click Jira Cloud → Excel reporting via GitHub Actions — least-privilege Atlassian service account, OAuth 2.0 client credentials with read-only scopes & secrets in GitHub Secrets | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |
| [🔍 DomainControllers Events](https://github.com/21bshwjt/XDomainControllers-Events) | Detects weak ciphers & legacy authentication protocols on DCs — reduces identity attack surface | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🖥️ AD Replication Monitoring](https://github.com/21bshwjt/ActiveDirectory_Replication_Monitoring) | Continuous AD replication health monitoring with HTML email alerting | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🖥️ SysVol D4 - PowerShell](https://github.com/21bshwjt/SysVol-D4-PowerShell) | Automates authoritative (D4) SYSVOL restore for DFSR recovery & GPO integrity | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![GPO](https://img.shields.io/badge/GPO-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |

---

## 🚀 Currently Building

- 📊 **Identity Posture Management Dashboards**: extending the Microsoft 365 posture platform to Active Directory & Okta
- 🔐 **Conditional Access & Identity Protection** frameworks for Entra ID
- 🏛️ **Zero Trust reference architecture** for hybrid identity
- 🧰 **PowerShell reporting framework** for continuous security assessments

---

## 🛠️ Tech Stack

<div align="center">

**Identity & Security**<br/>
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white)
![SAML / OIDC](https://img.shields.io/badge/SAML_%2F_OIDC_SSO-F59E0B?style=for-the-badge&logo=openid&logoColor=white)
![PAM](https://img.shields.io/badge/Privileged_Access_Management-DC2626?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Identity Governance](https://img.shields.io/badge/Identity_Governance-059669?style=for-the-badge&logo=microsoft&logoColor=white)
![PKI](https://img.shields.io/badge/PKI_Certificate_Services-6D28D9?style=for-the-badge&logo=letsencrypt&logoColor=white)
![Zero Trust](https://img.shields.io/badge/Zero_Trust-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Cloud & Microsoft 365**<br/>
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Graph API](https://img.shields.io/badge/Microsoft_Graph_API-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure Automation](https://img.shields.io/badge/Azure_Automation-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Log Analytics](https://img.shields.io/badge/Azure_Log_Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Automation & Tooling**<br/>
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 🤝 Let's Connect

Always happy to exchange ideas on **identity security architecture**, **Zero Trust**, and **Microsoft security automation**.
Let's connect on [LinkedIn](https://www.linkedin.com/in/bshwjt/).

<div align="center">

*"Security is not a product, but a process."* — Bruce Schneier

🛡️ **Biswajit Biswas** · Cyber Security Architect · Identity-First Security

</div>
