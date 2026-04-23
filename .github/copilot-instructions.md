# Copilot Instructions: KB Clean-up Project

You are working on **Project2: KB Clean-up**, a NetApp initiative to audit, deduplicate, and improve Knowledge Base content across all BlueXP support specializations.

## Project Context

- **Confluence page**: https://netapp.atlassian.net/wiki/spaces/GENESIS/pages/583791168/Project2+KB+Clean-up
- **Goal**: Audit, clean up, and deduplicate KB articles across all specialization areas; confirm top issues surface in front-end AI tools (shift-left)

## Success Criteria

1. Reference Guides published for each specialization area with identified top KB needs
2. Duplicate KB articles across all areas identified and removed or merged
3. Top issues per area confirmed appearing in front-end AI tools (shift-left validated)

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

## Work Tracks

### Phase 1 — Active
1. **Licensing** (Chris Huff) — Gathering all relevant KBs → building a Reference Guide
2. **Ransomware Resilience** (Jeff Pastva) — Gathering all relevant KBs → building a Reference Guide
3. **AI Cleanup** (Kristena) — Piloting KDE AI tool; testing with Cloud SME areas; coordinating with Andre/AK
4. **Duplicate Clean-up** (Unassigned) — Identify what creates duplicates; align with AI Cleanup for tooling

### Phase 2 — Next
5. **CBS** (Zach Wylie) — Kicks off after AI tool is available
6. **CVO Data Services** (Vijaya Subramanian) — Kicks off after AI tool is available
7. **Platform (General)** (Fernando Alfaro Castillo) — Coordinate with Federation and Licensing leads
8. **Platform (Federation)** (Chris Huff & Mike Seagle)
9. **Platform (Licensing)** (Darius Bell)

### Phase 3 — Future
10. **Classification / DS** (Mohamed Obayd)
11. **CVO Ontap (VSA)** (Jared Parker)

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

## How to Help

When working on tasks in this repo:
- Keep task status up to date in `tasks/tracker.md`
- When drafting KB content, use clear, technical, customer-facing language appropriate for NetApp support documentation
- When writing scripts (e.g., for KB auditing or duplicate detection), prefer Python
- When suggesting delegations or next steps, reference the team members and their current workloads above
- Always link back to the Confluence page when summarizing project status
- Ask clarifying questions when scope is ambiguous rather than assuming

## Conventions

- Task status values: `Not Started`, `Started`, `In Progress`, `Reviewing`, `Done`
- Date format: `YYYY-MM-DD`
- File naming: `kebab-case`
- Phase labels: `phase-1`, `phase-2`, `phase-3`