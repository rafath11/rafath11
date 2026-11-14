![A guardian watching over the city at night](banner.webp)

# Hi, I'm Rafath Mohammed

**ServiceNow ITAM & SAM Specialist** — Dallas, Texas

*Watching over the systems nobody thinks about — and building small tools that help people before things break.*

![ServiceNow](https://img.shields.io/badge/ServiceNow-SAM%20Pro%20%C2%B7%20HAM%20Pro%20%C2%B7%20CMDB-62D84E?style=flat&logo=servicenow&logoColor=white)
![Flexera](https://img.shields.io/badge/Flexera-License%20Reconciliation-0055A5?style=flat)
![Python](https://img.shields.io/badge/Python-Tools%20%26%20Automation-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Integrations-F7DF1E?style=flat&logo=javascript&logoColor=black)
![REST APIs](https://img.shields.io/badge/REST%20APIs-Integrations-009688?style=flat)
![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?style=flat&logo=github&logoColor=white)

## About me

I work in IT asset management — software and hardware asset lifecycles, CMDB health,
software license reconciliation, and the automation that keeps asset data honest.
Day to day that's entitlements, normalization, discovery data, and finding the records
that don't line up before an audit finds them first.

- Currently supporting **Oncor Electric Delivery** (Dec 2024 – present)
- Previously **OCC** and **Fidelity Investments**
- Based in **Dallas, Texas** · working remote-first
- On the side: I build small, zero-dependency open-source tools for everyday IT
  problems, then write up what I learned on LinkedIn

## What I work with

| Area | Details |
| --- | --- |
| **Platforms** | ServiceNow (SAM Pro, HAM Pro, CMDB, Discovery, Integration Hub, Virtual Agent, Now Assist), Flexera |
| **Day to day** | Software license reconciliation, CMDB health & remediation, asset lifecycle processes, integrations, discovery data quality |
| **Building with** | Python, JavaScript, REST APIs, Git / GitHub |
| **Exploring** | AI agents applied to ITSM / ITAM workflows — small, verified, human-approved steps, never automation for its own sake |

## Projects — small tools, real problems

Every tool here started as an annoyance in real IT work. All are zero-dependency
Python unless noted — download one file and run it.

| Tool | What it does |
| --- | --- |
| **[certwatch](https://github.com/rafath11/certwatch)** | Checks TLS certificate expiry across a list of domains and flags them *before* they take a service down. CI-friendly exit codes, JSON output, works through corporate proxies. |
| **[csv-dedupe](https://github.com/rafath11/csv-dedupe)** | Finds duplicate rows in CSV exports (CMDB and asset data are full of them) and writes a report plus a cleaned file. |
| **[leadlog](https://github.com/rafath11/leadlog)** | One line per lead — source, booked or not, value — then a monthly report by source, so a small business can see which marketing actually works. Built to help a real owner who was tracking leads in a notebook. |
| **[linkrot](https://github.com/rafath11/linkrot)** | Checks a list of documentation / runbook URLs for dead links and redirects, and groups the report so you fix the worst first. |
| **[subnet-scout](https://github.com/rafath11/subnet-scout)** | A safe CIDR free-IP calculator: give it a subnet and the IPs already used, it hands back the free ones. Pure math — no scanning. |
| **[logtrim](https://github.com/rafath11/logtrim)** | Summarizes a big log file — counts by error pattern, top offenders, and time range — so you read the summary instead of the whole file. |
| **[expiry-board](https://github.com/rafath11/expiry-board)** | One board for everything that expires — certs, licenses, contracts, warranties — sorted by days left, with a 30/60/90-day warning view. |

**Labs & forks**

- **[servicenow-github-demo](https://github.com/rafath11/servicenow-github-demo)** — ServiceNow ↔ GitHub integration experiments.
- **[ECC](https://github.com/rafath11/ECC)** (fork of affaan-m/ECC) — an agent-harness pack for Claude Code / Codex that I'm evaluating for agent-team workflows.
- In the workshop: the next tool is being scouted — one real problem at a time, built properly before it ships.


## Community

The tools here are built in the open, and the Discussions tab on this profile repo is where practitioners compare notes: CMDB challenges, ITAM edge cases, and what actually works in a real estate. New challenge most weeks — bring a problem, leave with an answer.

- [Join the discussions](https://github.com/rafath11/rafath11/discussions)

## Repos I am studying / building on

I did not build the repos below — I am studying and analysing them for patterns I can apply to ServiceNow ITAM / SAM work, and writing up what I learn on LinkedIn.

- [grokability/snipe-it](https://github.com/grokability/snipe-it) — Studying: the best-known open-source ITAM system, for asset and license check-in/out and custody patterns.
- [glpi-project/glpi](https://github.com/glpi-project/glpi) — Studying: license tracking and software auditing in open-source ITAM, compared with SAM Pro.
- [ercole-io/ercole](https://github.com/ercole-io/ercole) — Studying: proactive SAM — catching license risk before an audit does.
- [aartiq/servicenow-mcp](https://github.com/aartiq/servicenow-mcp) — Studying: how AI assistants can touch ServiceNow safely via MCP.
- [Snow-Shell/servicenow-powershell](https://github.com/Snow-Shell/servicenow-powershell) — Studying: PowerShell automation for repetitive ServiceNow asset work.
- [netbox-community/netbox](https://github.com/netbox-community/netbox) — Studying: DCIM/IPAM as a dedicated source of truth, compared with the CMDB.
- [fleetdm/fleet](https://github.com/fleetdm/fleet) — Studying: live endpoint device and software inventory for CMDB reconciliation.
- [anchore/syft](https://github.com/anchore/syft) — Studying: SBOM generation as inventory evidence for SAM normalization and reconciliation.
- [endoflife-date/endoflife.date](https://github.com/endoflife-date/endoflife.date) — Studying: end-of-life and support lifecycle data for HAM/SAM lifecycle reviews.
- [Combodo/iTop](https://github.com/Combodo/iTop) — Studying: an open-source CMDB and ITSM data model, compared with ServiceNow.
- [ansible-collections/servicenow.itsm](https://github.com/ansible-collections/servicenow.itsm) — Studying: ITSM automation from Ansible for incidents, changes and problem records.
- [denis-prilepskiy/governed-agentic-itsm-blueprint](https://github.com/denis-prilepskiy/governed-agentic-itsm-blueprint) — Studying: tool contracts, policy gates and evidence schemas for governed agentic ITSM.
- [jameshgordy/snipeit-mcp](https://github.com/jameshgordy/snipeit-mcp) — Studying: MCP access to an ITAM system with per-user identity and read-only modes.
- [dotdna-io/assetatlas](https://github.com/dotdna-io/assetatlas) — Studying: how scattered, contradictory tool data is reconciled into one reliable inventory.
- [IvanBBaev/servicenow-mcp-ai](https://github.com/IvanBBaev/servicenow-mcp-ai) — Studying: safe AI writes to ServiceNow — plan, approve, apply, revert — plus drift checks.
- [TencentBlueKing/bk-cmdb](https://github.com/TencentBlueKing/bk-cmdb) — Studying: a large-scale open CMDB model and how it handles CI relationships.
- [Shelf-nu/shelf.nu](https://github.com/Shelf-nu/shelf.nu) — Studying: modern, lighter IT asset and equipment management and scheduling.
- [allegro/ralph](https://github.com/allegro/ralph) — Studying: data-center CMDB, hardware lifecycle and rack-level truth vs discovery data.
- [veops/cmdb](https://github.com/veops/cmdb) — Studying: a focused, actively maintained open CMDB and CI/resource modelling.
- [rbw/pysnow](https://github.com/rbw/pysnow) — Studying: scripting ServiceNow API pulls for asset data reconciliation instead of manual exports.
- [serac-labs/serac](https://github.com/serac-labs/serac) — Studying: ServiceNow MCP with blast-radius impact analysis before acting on a CI.

## Certifications

11 and counting — the full, verifiable list lives on my LinkedIn.

- ServiceNow Micro-Certification — **Integration Hub** (passed 97%)
- ServiceNow Micro-Certification — **Configure the CMDB**
- ServiceNow Micro-Certification — **CMDB Health**
- ServiceNow Micro-Certification — **Flows**
- ServiceNow Micro-Certification — **Virtual Agent** (passed 100%)
- ServiceNow Micro-Certification — **Now Assist Executive**
- **BlueTally** — ITAM Foundations
- **Anthropic** — Model Context Protocol (MCP)
- **Anthropic** — AI Fluency
- **Hugging Face** — Agents Course, Unit 1
- **Palantir** — Introduction to Foundry & AIP for Enterprise Organizations

## What I'm focused on now

- Keeping CMDB and license data honest at enterprise scale
- Small tools that save IT teams an hour at a time
- AI agents in ITAM — with a human verification gate on everything they produce
- Writing it all up on LinkedIn as I go, the way a practitioner actually talks

## Connect

- **LinkedIn:** [rafath-mohammed-69389b294](https://www.linkedin.com/in/rafath-mohammed-69389b294) — where I post the write-ups
- **GitHub:** [@rafath11](https://github.com/rafath11)
- **Open to:** remote C2C contract roles in ServiceNow ITAM / SAM

*If one of the tools saved you some time, a star helps the next person find it.*
