<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/hero.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/hero-light.svg">
  <img alt="Adrian D. Moseley — Staff Systems Engineer, Cloud and Endpoint Platform Engineering" src="https://trophy.clouddev.adrianmoseley.com/hero.svg" width="100%">
</picture>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/admoseley/)
[![Website](https://img.shields.io/badge/adrianmoseley.com-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white)](http://www.adrianmoseley.com)
[![Austin, Texas](https://img.shields.io/badge/Austin,_Texas-2F80ED?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 💫 About

I'm a Staff Systems Engineer at The Home Depot with 20+ years in systems engineering.
I led the move from VMware Horizon to Citrix DaaS for **10,800+ virtual desktops**,
moving brokering and management to the cloud. Today I lead Azure engineering for
that platform and our **Windows 365 production pilot**. The pilot serves **50 users
across all regions combined**, with expansion to **1,000+ users planned for Q1 2027**.

Hardware shortages and rising on-premises costs prompted us to move desktop workloads
to the cloud. We started with persistent desktops because employees need their own
applications and settings. Intune provisions their Cloud PCs, and Citrix DaaS manages
access. Our call centers continue to use standardized Citrix PVS desktops, with
FSLogix preserving selected settings between sessions.

PowerShell is the tool I reach for when a fix has to work across a fleet. During
the July 2024 CrowdStrike outage, I wrote and deployed a script that restored
**97%+ of affected systems within hours**. I turn recurring fixes into modules and
runbooks that other engineers can use.

The projects on this profile are my **independent and volunteer work**.

## 🔭 Featured Projects

| Project | What it is |
|---|---|
| **Independent Azure consolidation** | Consolidated about seven live web properties from four paid platforms onto one Azure subscription using Terraform, Azure Static Web Apps, Front Door with WAF, Azure Communication Services and DNS cutovers. |
| **Black Mamas Village delivery app** *(volunteer work)* | Built a delivery app for the nonprofit and migrated it to Azure Functions and Cosmos DB. Terraform provisions the infrastructure, and GitHub Actions deploys to Azure using OpenID Connect (OIDC). |
| **[profile-cards-azure](https://github.com/admoseley/profile-cards-azure)** | The platform rendering this profile’s cards. Prerenders five SVGs every six hours in GitHub Actions and serves them from Azure Static Web Apps — Terraform, CI with secret scanning, $0/month, and no traffic from anyone else can load it. |
| **[Terraform_ADM](https://github.com/admoseley/Terraform_ADM)** | Multi-region Azure web platform in Terraform: Debian + nginx across Central US and East US behind Traffic Manager, with scheduled power on/off for cost control. |
| **[realestate](https://github.com/admoseley/realestate)** | Real-estate investment analysis platform on Azure — FastAPI + React, Container Apps, Azure SQL, background jobs and branded PDF reporting. |
| **[OlindaJohnsonSpeaks](https://github.com/admoseley/OlindaJohnsonSpeaks)** | Marketing site for a CEU speaker and trainer working with nursing organizations. |
| **[donteisha-samuel-portfolio](https://github.com/admoseley/donteisha-samuel-portfolio)** | Portfolio site for an instructional and learner-experience designer. |
| **[NewUbuntuSetup](https://github.com/admoseley/NewUbuntuSetup)** | Bash provisioning script for a fresh Ubuntu workstation. |

## 🎓 Certifications

[![Google Cloud Professional Cloud Architect](https://img.shields.io/badge/Google_Cloud-Professional_Cloud_Architect-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](#)
[![Google Generative AI Leader](https://img.shields.io/badge/Google-Generative_AI_Leader-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)](#)
[![Azure Fundamentals](https://img.shields.io/badge/Microsoft-Azure_Fundamentals_AZ--900-0078D4?style=for-the-badge)](#)
[![VMware vSphere](https://img.shields.io/badge/VMware-vSphere_6.7_Foundations-607078?style=for-the-badge&logo=vmware&logoColor=white)](#)

## 🤖 AI-augmented engineering

I use Claude Code and Codex to build and maintain independent projects. I review
the changes and use GitHub Actions to run tests and scan for secrets before merging.

When the third-party service behind my GitHub profile cards shut down, I built
[`profile-cards-azure`](https://github.com/admoseley/profile-cards-azure).
Terraform provisions the Azure hosting, and a scheduled GitHub Actions workflow
renders the cards you see on this page.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/architecture.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/architecture-light.svg">
  <img alt="Architecture: GitHub Actions renders SVGs and deploys them to an Azure Static Web App, served to this profile through GitHub's camo proxy" src="https://trophy.clouddev.adrianmoseley.com/architecture.svg">
</picture>

</div>

[![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)](#)
[![GitHub Copilot](https://img.shields.io/badge/Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)](#)
[![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)](#)
[![Codex](https://img.shields.io/badge/OpenAI_Codex-202123?style=for-the-badge)](#)

## 💻 Tech Stack

**Cloud & infrastructure**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Virtual desktop & endpoint**

![Windows 365](https://img.shields.io/badge/Windows_365-0078D4?style=for-the-badge)
![Intune](https://img.shields.io/badge/Microsoft_Intune-0078D4?style=for-the-badge)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge)
![Citrix](https://img.shields.io/badge/Citrix_DaaS-452170?style=for-the-badge&logo=citrix&logoColor=white)
![VMware](https://img.shields.io/badge/VMware_Horizon-607078?style=for-the-badge&logo=vmware&logoColor=white)
![FSLogix](https://img.shields.io/badge/FSLogix-0078D4?style=for-the-badge)

**Languages & scripting**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=dotnet&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

**Coursework:** Python and Go

**Web**

![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-70FFAF?style=for-the-badge&logo=deno&logoColor=black)

## 🏆 GitHub Trophies

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/trophy.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/trophy-light.svg">
  <img alt="GitHub trophies" src="https://trophy.clouddev.adrianmoseley.com/trophy.svg">
</picture>

</div>

## 📊 Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/stats.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/stats-light.svg">
  <img alt="GitHub stats" src="https://trophy.clouddev.adrianmoseley.com/stats.svg">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/top-langs.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/top-langs-light.svg">
  <img alt="Top languages" src="https://trophy.clouddev.adrianmoseley.com/top-langs.svg">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/streak.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/streak-light.svg">
  <img alt="Contribution streak" src="https://trophy.clouddev.adrianmoseley.com/streak.svg">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/top-repos.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/top-repos-light.svg">
  <img alt="Top contributed repositories" src="https://trophy.clouddev.adrianmoseley.com/top-repos.svg">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://trophy.clouddev.adrianmoseley.com/activity.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://trophy.clouddev.adrianmoseley.com/activity-light.svg">
  <img alt="Contribution activity over the last twelve months" src="https://trophy.clouddev.adrianmoseley.com/activity.svg">
</picture>

</div>

> Every card here renders from my own platform on Azure rather than a third-party
> service. Most of my commits land in private repositories, so they're rendered under
> my own token to count that work — private repos are ranked but never named.

---

<div align="center">

<sub>

Stat cards **self-hosted** on Azure · [source](https://github.com/admoseley/profile-cards-azure) · [health](https://trophy.clouddev.adrianmoseley.com/health.json)

</sub>

</div>
