# Project2: KB Clean-up

A structured, phased effort to audit, deduplicate, and improve NetApp Knowledge Base content across all BlueXP support specializations — with confirmation that top issues surface in front-end AI tools for shift-left.

📄 **Confluence Tracking Page**: [Project2: KB Clean-up](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/583791168/Project2+KB+Clean-up)

---

## Success Criteria

1. **Reference Guides published** — Each specialization area with identified top KB needs has a published KB Reference Guide
2. **Duplicates eliminated** — Duplicate KB articles across all areas are identified and removed or merged
3. **AI tool confirmation** — Top issues per area are confirmed appearing in front-end AI tools (shift-left validated)

---

## Team

| Name | Role |
|------|------|
| Kristena | Project Lead / AI Cleanup |
| Chris Huff | Licensing · Platform (Federation) |
| Jeff Pastva | Ransomware |
| Anee | Team Member |
| Zach Wylie | CBS (AMCS) |
| Vijaya Subramanian | CVO Data Services (APAC) |
| Fernando Alfaro Castillo | Platform - General (AMCS) |
| Mike Seagle | Platform - Federation (AMCS) |
| Darius Bell | Platform - Licensing (AMCS) |
| Mohamed Obayd | Classification / DS (AMCS) |
| Jared Parker | CVO Ontap / VSA (AMCS) |
| SMEs | [Advanced BXP Support Team — Geo SME Reference](https://netapp.atlassian.net/wiki/spaces/CDSS/pages/118129521) |

---

## Phase 1 — Active (Licensing · Ransomware · AI Cleanup)

| Item # | Theme | Task | Status | Prime(s) | Next Steps |
|--------|-------|------|--------|----------|------------|
| [1](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600718384) | Licensing | Gather list of all relevant KBs | 🔵 In Progress | Chris Huff | Build Reference Guide |
| [2](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600679734) | Ransomware Resilience | Gather all relevant KBs | 🟡 Started | Jeff Pastva | Build Reference Guide |
| [3](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600745884) | AI Cleanup | KDE team pilot AI tool — request access via Andre/AK | 🟣 Reviewing | Kristena | Use Cloud SME areas to test and improve tool |
| [4](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600718395) | Duplicate Clean-up | Identify root causes; use AI tool for cleanup | ⚪ Not Started | TBD | Coordinate with Item 3 |

---

## Phase 2 — Next (CBS · CVO Data Services · Platform)

| Item # | Theme | Task | Status | Prime(s) | Next Steps |
|--------|-------|------|--------|----------|------------|
| [5](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600679725) | CBS | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Zach Wylie (AMCS) | Kick off with APAC/EMEA SMEs once scoped |
| [6](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600745882) | CVO Data Services | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Vijaya Subramanian (APAC) | Kick off with AMCS/EMEA SMEs once scoped |
| [7](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600718380) | Platform (General) | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Fernando Alfaro Castillo (AMCS) | Coordinate with Federation and Licensing leads |
| [8](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600647328) | Platform (Federation) | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Chris Huff & Mike Seagle (AMCS) | — |
| [9](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600679728) | Platform (Licensing) | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Darius Bell (AMCS) | — |

---

## Phase 3 — Future (Classification/DS · CVO Ontap/VSA)

| Item # | Theme | Task | Status | Prime(s) | Next Steps |
|--------|-------|------|--------|----------|------------|
| [10](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600718378) | Classification / DS | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Mohamed Obayd (AMCS) | — |
| [11](https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/600647342) | CVO Ontap (VSA) | Gather list of all relevant KBs; identify top needs | ⚪ Not Started | Jared Parker (AMCS) | — |

---

## KB Specialty → SME Area Mapping

| KB Specialty | SME Area | Article Count |
|---|---|---|
| CLOUD | Platform | 388 |
| NETAPP_CONSOLE | Platform | 921 |
| DS_CBS | CBS | 94 |
| DS_CT | Tiering | 66 |
| DS_CVO | CVO Ontap (VSA) | 413 |
| DS_DC | Classification/DS | 109 |
| DS_RP | Ransomware Resilience | 7 |
| DS_CS | N/A - Not our team | 9 |
| DS_VC | N/A - Not our team | 4 |
| DS_WF | N/A - Not our team | 4 |
| (none) | Review Needed | 30 |

---

## Collateral

| Resource | Description | Link |
|---|---|---|
| 📊 KB Specialty Analysis - Combined | Combined citation data across all 10 KB specialties (2,045 rows) with SME Area mapping | [Open in OneDrive](https://netapp-my.sharepoint.com/:x:/r/personal/kristenh_netapp_com1/Documents/Documents/Copilot/KB%20Specialty%20Analysis/KB%20Specialty%20Analysis%20-%20Combined.xlsx?d=wa6a0e2e50cc8450c9eddde7c24cb2058&csf=1&web=1&e=oR5WnJ&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMTAwLTAwMDAwMDAwMDAwMH0) |

---

## Using Copilot on This Project

This repo is configured with a Copilot coding agent. When you assign Copilot a task via a GitHub Issue, it will:
- Have full context of the KB Clean-up project, team, and goals
- Be able to draft KB content, scripts, or tracking templates
- Follow the conventions defined in `.github/copilot-instructions.md`

To assign Copilot a task: **create a GitHub Issue**, then use `@copilot` in the issue body or comments.