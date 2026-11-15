<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=0078D4&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B%2C+I'm+Biswajit+Biswas;Cyber+Security+Architect+%7C+Identity-First+Security;500%2B+SaaS+Apps+Migrated+%C2%B7+45K%2B+Users+Separated;Securing+AD+%C2%B7+Entra+ID+%C2%B7+Okta+%C2%B7+Microsoft+365;Zero+Trust+%C2%B7+Privileged+Access+%C2%B7+PKI;Security+Automation+with+PowerShell+%26+Graph+API" alt="Typing SVG" />

# Biswajit Biswas

### 🛡️ Cyber Security Architect · Identity & Access Management · Security Automation

**Identity is the new perimeter — I design, harden, and automate it.**
**20+ years** securing identity for global enterprises in **retail, banking, financial services and healthcare**, where a single compromised identity can halt operations, expose customer data or fail an audit.
I harden hybrid Active Directory, Microsoft Entra ID and Okta, and turn security posture into **measurable, automated controls**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bshwjt/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/21bshwjt)
![Location](https://img.shields.io/badge/Location-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 🎯 At a Glance

| | |
|---|---|
| **Scale** | ~600,000-user Microsoft 365 tenant · Hybrid identity |
| **Industries** | Global clients in 🛒 Retail · 🏦 Banking · 💹 Financial Services · 🏥 Healthcare |
| **Core Domains** | IAM · Hybrid Identity · SSO Federation (SAML / OIDC) · Tenant-to-Tenant Migration (M&A / Divestiture) · PAM / Entra PIM · IGA · Guest (B2B) & Workload Identity Security · PKI & Certificate Lifecycle · License & Entitlement Optimization |
| **Platforms** | Active Directory · Microsoft Entra ID · Microsoft PKI (AD CS) · CyberArk Cloud PKI · Okta · Azure · Microsoft 365 |
| **Frameworks** | Zero Trust · Microsoft Enterprise Access Model (Tiering) · CIS Benchmarks |
| **Automation & DevOps** | PowerShell · Microsoft Graph API · Azure Automation · Key Vault · GitHub Actions · Azure DevOps · Atlassian Jira |
| **Logging** | Azure Log Analytics |

---

## 🏆 Signature Deliveries

| Delivery | What I Did | Impact & Result |
|---|---|---|
| 🔀 **Divestiture Tenant Separation** | Designed a wave-based migration framework. Automated app onboarding with Graph API & PowerShell | **500+ SaaS apps (SAML / OIDC)** and **45,000+ users** moved to a new Entra ID tenant **ahead of the TSA deadline**, with **zero business disruption** |
| 📊 **M365 Identity Posture Management** | Built **400+ automated security checks**, mapped to CIS ([coverage](#-microsoft-365-identity-posture-management)) | Tenant reviews that were slow and manual now run **on demand**. Misconfigurations and over-privilege are found **before an incident** |
| 🏰 **On-Prem AD Security Posture (ISPM)** | Automated Active Directory posture assessments in PowerShell against a **75-control framework** | **Repeatable, measurable** gains in security hygiene, compliance and risk visibility across on-prem AD |
| ⚙️ **Audit & Compliance Automation** | Automated tenant-wide Directory Services audits with cloud-run PowerShell and **GitHub Actions**. Built reusable PowerShell tooling for Jira using its REST APIs ([Jira Automation](https://github.com/21bshwjt/Atlassian_Jira_Automation), [GitHub Actions Jira Reporting](https://github.com/21bshwjt/GHActions_JIRA)) | **Standardized compliance reporting**, with audits that run automatically instead of by hand |
| 💰 **Cost & Entitlement Optimization** | Data-driven analysis of underused and wrongly assigned SKUs (E3/E5, EMS, add-ons) and of unused access | **~$35,000 a year** saved on licensing. **Excessive access risk reduced** |
| 🧩 **App Credential Self-Service** | Built the [Entra Apps Management](https://github.com/21bshwjt/Entra-Apps-Management) portal with privileged-app guardrails | App owners rotate their own secrets and certificates, so **these tickets are gone**. **Fewer outages from expired credentials** |

---

## 📊 Microsoft 365 Identity Posture Management

The checks are built with **PowerShell and Microsoft Graph (v1.0 and beta)**. They catch drift, misconfiguration and over-privilege early, and the findings drive Conditional Access hardening, PIM cleanup and workload-identity fixes.

| Pillar | What It Assesses |
|---|---|
| 🏆 **Secure Score & CIS** | Secure Score trend, CIS-mapped control profiles, Defender recommendations, Defender for Identity health |
| 🔐 **Authentication & MFA** | Phishing-resistant and passwordless strengths, authentication methods, Authenticator fatigue, banned passwords, token lifetimes |
| 🚦 **Conditional Access** | Policy deep-dive, templates, named locations, protected actions, authentication contexts |
| 🧱 **Tenant Hardening** | Limits on what non-admins can create or read, guest invites, user and admin consent, authorization policy, SPF |
| 👑 **Privileged Access** | Entra PIM audit (users, groups, SPNs), Global Administrator audit, role mapping |
| 🤖 **Workload Identities** | App owners and credential expiry, SPN permissions, roles and sign-ins, inactive SPNs, consent audit |
| 👥 **Guests & IGA** | Guest roles and memberships, B2B / multi-tenant partners, access packages, access reviews, lifecycle workflows |
| 🚨 **Incident Response** | Defender alerts and incidents, legacy-client and failed sign-ins, OAuth consents, Identity Protection |
| 💻 **Devices & Access** | Intune compliance and enrollment, device registration, Global Secure Access apps, devices and traffic |
| 🔄 **Hybrid, Licensing & Data** | Sync status, domains, license matrix, Purview sensitivity labels, SharePoint Online settings |

---

## 📌 Featured Projects

| Project | Security Problem Solved | Tech |
|---|---|---|
| [🧩 Entra Apps Management](https://github.com/21bshwjt/Entra-Apps-Management) | Self-service portal where app owners rotate their own secrets, certificates and federated credentials, so no ticket is needed. Guardrails block privileged apps, weak certificates and guests, and every change is audited | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Graph API](https://img.shields.io/badge/Graph_API-0078D4?style=flat-square&logo=microsoft&logoColor=white) |
| [🔑 Entra Hybrid Identity Toolkit](https://github.com/21bshwjt/entra-hybrid-identity-toolkit) | Tools for securing and operating hybrid Entra identity | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🛡️ EntraID Graph Toolkit](https://github.com/21bshwjt/EntraID-Graph-Toolkit) | Graph security recipes: Global Admin audit, CA what-if checks, compromised-account response, app-only auth | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Graph API](https://img.shields.io/badge/Graph_API-0078D4?style=flat-square&logo=microsoft&logoColor=white) |
| [⚙️ Az AutomationRunbooks](https://github.com/21bshwjt/AzAutomationRunbooks) | Secure, scheduled cloud automation | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| [🏗️ Build Replica DomainController](https://github.com/21bshwjt/Build_Replica_DomainController) | Automated replica DC deployment that cuts configuration drift | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🎫 Atlassian Jira Automation](https://github.com/21bshwjt/Atlassian_Jira_Automation) | Jira Cloud REST automation with secure API-token handling | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |
| [🚀 GitHub Actions Jira Reporting](https://github.com/21bshwjt/GHActions_JIRA) | One-click, serverless Jira reporting with least-privilege OAuth 2.0 and read-only scopes | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| [🔍 DomainControllers Events](https://github.com/21bshwjt/XDomainControllers-Events) | Finds weak ciphers and legacy authentication on DCs | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🖥️ AD Replication Monitoring](https://github.com/21bshwjt/ActiveDirectory_Replication_Monitoring) | Monitors AD replication health and sends e-mail alerts | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| [🖥️ SysVol D4 - PowerShell](https://github.com/21bshwjt/SysVol-D4-PowerShell) | Automates authoritative SYSVOL restore to protect GPO integrity | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |

---

## 🚀 Currently Building

- 📊 Extending posture management to **Okta**
- 🔐 **Conditional Access & Identity Protection** frameworks for Entra ID
- 🏛️ **Zero Trust reference architecture** for hybrid identity

---

## 🛠️ Tech Stack

<div align="center">

**Identity & Security**<br/>
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white)
![SAML / OIDC](https://img.shields.io/badge/SAML_%2F_OIDC_SSO-F59E0B?style=for-the-badge&logo=openid&logoColor=white)
![PKI](https://img.shields.io/badge/PKI_Certificate_Services-6D28D9?style=for-the-badge&logo=letsencrypt&logoColor=white)

**Cloud & Microsoft 365**<br/>
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Graph API](https://img.shields.io/badge/Microsoft_Graph_API-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure Automation](https://img.shields.io/badge/Azure_Automation-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Log Analytics](https://img.shields.io/badge/Azure_Log_Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Automation & DevOps**<br/>
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

<div align="center">

Happy to talk **identity security architecture**, **Zero Trust** and **Microsoft security automation**. [Connect on LinkedIn](https://www.linkedin.com/in/bshwjt/).

*"Security is not a product, but a process."* — Bruce Schneier

</div>
