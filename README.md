# 🧬 AFLS Ideas — Repository Index

A table of contents for the [**afls-ideas**](https://github.com/afls-ideas) account: a collection of demos, starter kits, LWCs, and how-to guides for **Agentforce for Life Sciences Cloud (AFLS / LSC)**.

The repos here accumulate faster than anyone can catalog them, so this page is the front door — browse by category below to find the sample, component, or guide you're looking for.

> ⚠️ **Not official Salesforce products.** Everything linked here is provided *AS IS*, without warranty or support. Test and validate before using in any environment.

---

## 📑 Categories

- [📱 Lightning Web Components & Mobile UI](#-lightning-web-components--mobile-ui)
- [🎬 Intelligent Content & Presentations](#-intelligent-content--presentations)
- [🤖 Agentforce & AI Agents](#-agentforce--ai-agents)
- [⚙️ Custom Actions & Extending the Mobile App](#️-custom-actions--extending-the-mobile-app)
- [📊 Demo Data & Starter Kits](#-demo-data--starter-kits)
- [📚 Setup Guides & Data Model Deep-Dives](#-setup-guides--data-model-deep-dives)
- [🛠️ Platform Tooling & Metadata](#️-platform-tooling--metadata)
- [🧑‍💻 Claude Code & Developer Tooling](#-claude-code--developer-tooling)

---

## 📱 Lightning Web Components & Mobile UI

Reusable LWCs and UI components for the Life Sciences Cloud web and mobile (iPad) apps.

| Repo | Description |
|------|-------------|
| [HCP-Analyzer](https://github.com/afls-ideas/HCP-Analyzer) | LWC for the LSC mobile app that lists Accounts and deeplinks to a record via the `lsc://` scheme. |
| [lsc-mobile-inline-composable-lwc](https://github.com/afls-ideas/lsc-mobile-inline-composable-lwc) | Composable LWC demo — one reusable self-querying component composed across two mobile-inline widgets (Visits + Cases). Offline-capable, no Apex. |
| [LWC-as-standalone-tab](https://github.com/afls-ideas/LWC-as-standalone-tab) | Patient Journey Simulator LWC for the LSC mobile app (custom tab / App Page). |
| [medical-insight-signal-map](https://github.com/afls-ideas/medical-insight-signal-map) | Interactive LWC for Agentforce LSC — visualizes Medical Insight relationships as a force-directed graph on iPad. |
| [AFLS_LocalDB_QueryTool](https://github.com/afls-ideas/AFLS_LocalDB_QueryTool) | Diagnostic Intelligent Content tool to inspect the local SQLite database on the LSC iPad app (45+ objects, SOQL builder). |

## 🎬 Intelligent Content & Presentations

eDetailer templates and presentation players for LSC Intelligent Content.

| Repo | Description |
|------|-------------|
| [AFLS-MedTech-IntelligentContent](https://github.com/afls-ideas/AFLS-MedTech-IntelligentContent) | Multi-page zip template for MedTech eDetailer presentations. |
| [AFLS-Multipage-Singlezip-IntelligentContent](https://github.com/afls-ideas/AFLS-Multipage-Singlezip-IntelligentContent) | Multi-page single-zip template — 5-slide eDetailer with PresentationPlayer navigation. |
| [AFLS-Multizip-IntelligentContent](https://github.com/afls-ideas/AFLS-Multizip-IntelligentContent) | Multi-Zip (one zip per slide) template. |
| [Presentation-Pages](https://github.com/afls-ideas/Presentation-Pages) | Presentation page examples with PresentationPlayer API demos. |
| [SPA-Presentation-with-Clicker-Support](https://github.com/afls-ideas/SPA-Presentation-with-Clicker-Support) | Single-page-app presentation with clicker (remote) support. |
| [PresentationSettings-Storage-Migration](https://github.com/afls-ideas/PresentationSettings-Storage-Migration) | How Presentation Settings are stored in the `LifeSciMetadata*` object family and how to migrate between orgs as data. |

## 🤖 Agentforce & AI Agents

Agentforce agents and agent collections for field sales and medical affairs.

| Repo | Description |
|------|-------------|
| [Power_Agent_ADLC](https://github.com/afls-ideas/Power_Agent_ADLC) | Field Sales HCP Power Agent — Agentforce employee agent on the Atlas Reasoning Engine (Agent Script), with 10 country-specific variants. Desktop + mobile SDK. |
| [Field_Medical_AgentForce_Starter](https://github.com/afls-ideas/Field_Medical_AgentForce_Starter) | Field Medical Agentforce Starter Kit. |
| [life-sciences-agency-agents](https://github.com/afls-ideas/life-sciences-agency-agents) | A collection of specialized AI agents for a virtual life sciences company, built for Claude Code and other agentic coding tools. |

## ⚙️ Custom Actions & Extending the Mobile App

Patterns for adding actions and surfacing online-only functionality inside the AFLS mobile app.

| Repo | Description |
|------|-------------|
| [Custom_Action_Starter_Kit](https://github.com/afls-ideas/Custom_Action_Starter_Kit) | Starter kit for building custom actions for AFLS. |
| [Embedding_Online_Tabs_As_CustomActions](https://github.com/afls-ideas/Embedding_Online_Tabs_As_CustomActions) | Configure Quick/Custom Actions to launch online-only functionality (Tableau, Salesforce Maps, full-screen LWCs) without leaving the mobile app. |

## 📊 Demo Data & Starter Kits

Tools and content for spinning up realistic demo orgs quickly.

| Repo | Description |
|------|-------------|
| [AFLSCE-Demo-Data-StarterKit](https://github.com/afls-ideas/AFLSCE-Demo-Data-StarterKit) | LWC admin UI for creating realistic demo data — territories, accounts, HCPs, contact points, and therapy-area scenarios. |
| [Demo-AFLS-1st_3rd_Party_Datasets](https://github.com/afls-ideas/Demo-AFLS-1st_3rd_Party_Datasets) | Generic data loader — load any demo data (Rx, specialty pharmacy, claims, formulary) via JSON payloads. Scenario-swappable, Data Cloud-ready. |
| [Email_Templates_StarterKit](https://github.com/afls-ideas/Email_Templates_StarterKit) | 50 production-ready Field Email templates for HCP communications. |
| [samples-admin-app](https://github.com/afls-ideas/samples-admin-app) | Starter samples admin app to help your samples admin get started quickly. |
| [load_action_plan_templates](https://github.com/afls-ideas/load_action_plan_templates) | Anonymous Apex to create/load Action Plan Templates, plus 40 pre-built templates across 4 LS personas. |

## 📚 Setup Guides & Data Model Deep-Dives

Hands-on "how-to" guides, data model references, and configuration walkthroughs.

| Repo | Description |
|------|-------------|
| [How-to-setup-Consent](https://github.com/afls-ideas/How-to-setup-Consent) | Set up Consent Management — data model, sharing rules, and country-based channel visibility. |
| [Learn-Consent-Management](https://github.com/afls-ideas/Learn-Consent-Management) | Consent Management setup guide with data model diagrams, real-world scenarios, and Apex data load scripts. |
| [Learn-Events_262](https://github.com/afls-ideas/Learn-Events_262) | Events Management demo (262 release) — Immunexis Dinner Event config, OMCC, FlexiPage, workflow path/actions, and data model reference. |
| [Learn_SearchBeforeCreate](https://github.com/afls-ideas/Learn_SearchBeforeCreate) | LWC + Apex tool to diagnose why a user cannot find an account in LSC Search Before Create. |
| [learn-data-change-request](https://github.com/afls-ideas/learn-data-change-request) | Data Change Request (DCR) setup guide — how data changes are submitted, validated, and implemented across LSC. |
| [Multi-Country-Brand-Setup](https://github.com/afls-ideas/Multi-Country-Brand-Setup) | Multi-country brand hierarchy for LSC Product Management — Immunexis & Cordim across US/GB/FR/IT/ES/DE with `Country__c` metadata. |
| [Care-Program-Enrollee](https://github.com/afls-ideas/Care-Program-Enrollee) | SFDX project for Care Program Enrollee configuration — DB Schema, profiles, and metadata. |
| [Leveraging-Financial-Assistance-Data-Model-in-AFLS-Mobile](https://github.com/afls-ideas/Leveraging-Financial-Assistance-Data-Model-in-AFLS-Mobile) | Use the Financial Assistance data model for Co-Pay enrollment and claims/disbursement workflows, including mobile enablement. |
| [Create_New_Patient](https://github.com/afls-ideas/Create_New_Patient) | Screen flows to create/edit Patient PersonAccounts, bypassing the multi-entity create that generates HealthcareProvider records. |
| [Email_Template_Sharing](https://github.com/afls-ideas/Email_Template_Sharing) | Trigger-based sharing for `LifeSciEmailTemplate` by Public Group name. |

## 🛠️ Platform Tooling & Metadata

Utilities and scripts for LSC metadata, caching, and custom scripting.

| Repo | Description |
|------|-------------|
| [metadata-cache-gen](https://github.com/afls-ideas/metadata-cache-gen) | Anonymous Apex scripts to generate LSC Mobile metadata cache programmatically. |
| [skip-validation-metadata-cache-gen](https://github.com/afls-ideas/skip-validation-metadata-cache-gen) | Permission set to skip validations before metadata cache generation. |
| [lsc-custom-scripts-examples](https://github.com/afls-ideas/lsc-custom-scripts-examples) | LSC Custom Scripts examples for pharma — validation, checklist, and visit action validation scripts. |

## 🧑‍💻 Claude Code & Developer Tooling

Agentic-coding setups and learning repos.

| Repo | Description |
|------|-------------|
| [gstack](https://github.com/afls-ideas/gstack) | Garry Tan's exact Claude Code setup — 15 opinionated tools acting as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA. |
| [Learn-262-Features](https://github.com/afls-ideas/Learn-262-Features) | Learning Claude Code 262 features. |

---

<sub>Index of 36 repositories across the <a href="https://github.com/afls-ideas">afls-ideas</a> account. To add a repo, drop it in the matching category above.</sub>
