# Infrastructure Operations Portfolio Charter

**Version:** 1.1
**Baseline date:** 18 July 2026
**Amended:** 22 July 2026
**Owner:** Portfolio owner
**Status:** Approved execution baseline — storage resource amendment

## 1. Purpose

Build a concise, evidence-based infrastructure portfolio that supports the portfolio owner's immediate return to UK IT employment.

The portfolio will demonstrate current hands-on ability for these roles, in priority order:

1. Infrastructure Support Engineer / Infrastructure Technician
2. 2nd Line Support Engineer
3. Operational Windows Systems / Infrastructure Engineer
4. Endpoint / Modern Workplace Engineer after licence-gated evidence is available
5. Azure Infrastructure / Cloud Support Engineer as a progression target

The work is not a training syllabus or an attempt to simulate an entire enterprise. Every component must contribute directly to employability, interview performance, or credible operational evidence.

## 2. Success criteria

The MVP is complete when:

- three coherent case studies are published in one professional portfolio;
- each case study contains implementation, validation, controlled failure, recovery, and operational documentation;
- the evidence covers the critical competencies approved in Task 0.2;
- no secrets, personal identifiers, tenant identifiers, licence keys, private IP dependencies, or uncontrolled costs are exposed;
- each case can be explained as a two-minute interview summary and defended through technical questioning;
- the portfolio supplies accurate material for CV, LinkedIn, applications, and interviews.

The first employable release is Case Study 1. The project does not need to wait for all three cases before being used in applications.

## 3. Approved case studies

### Case Study 1 — Windows Infrastructure Operations and Recovery

**Purpose:** Establish the immediate 2nd-line and infrastructure-support baseline.

**Required outcomes:**

- operate a controlled Windows Server and Windows client environment;
- administer AD DS users, groups, computers, OUs, delegation, and joiner/mover/leaver tasks;
- configure and troubleshoot DNS, DHCP, TCP/IP, domain joining, and Group Policy;
- demonstrate Windows endpoint and server support;
- perform patching, operational checks, backup, restore, and recovery validation;
- document incidents, escalation decisions, changes, problems, knowledge articles, and handovers;
- automate selected repeatable tasks with PowerShell.

### Case Study 2 — Identity and Endpoint Operations

**Purpose:** Demonstrate Microsoft cloud identity and modern endpoint administration.

**Required outcomes:**

- administer Entra users, groups, roles, and identity lifecycle operations;
- use Microsoft Graph and PowerShell for controlled administration;
- demonstrate authentication, access, and audit troubleshooting;
- add Intune enrolment, compliance, configuration, application deployment, and update evidence only when the appropriate trial or entitlement is deliberately activated;
- document joiner/mover/leaver, access review, device non-compliance, and escalation scenarios.

Microsoft 365 Personal is not treated as an enterprise administration licence. Intune and advanced Entra controls remain licence-gated until a timed business trial is approved.

### Case Study 3 — Azure Infrastructure Operations and Automation

**Purpose:** Demonstrate controlled cloud infrastructure deployment and operations.

**Required outcomes:**

- implement resource organisation, RBAC, tags, budgets, and cost alerts;
- deploy and validate Azure networking and Windows workloads;
- demonstrate monitoring, operational diagnostics, backup, and recovery;
- create a repeatable deployment and teardown process using approved infrastructure-as-code and scripting tools;
- show cost-conscious resource lifecycle management.

## 4. Scope boundaries

### Included in the MVP

- Windows Server and Windows 10/11 operations
- VMware Workstation-based local laboratory
- AD DS, DNS, DHCP, Group Policy, TCP/IP, and Windows support
- PowerShell and Microsoft Graph
- Backup, restoration, disaster-recovery reasoning, and validation
- Entra ID fundamentals and identity operations
- Intune and Autopilot only within an approved licence window
- Azure networking, governance, monitoring, backup, and automation
- Incident, request, change, problem, knowledge, validation, and handover records
- One recruiter-facing portfolio entry point

### Deferred

- multi-forest or child-domain architecture
- enterprise PKI / AD CS
- WSUS and DFS unless a selected vacancy makes them materially valuable
- AWS, Oracle Cloud, Kubernetes, and container-platform engineering
- Citrix architecture
- specialist cybersecurity, SIEM, Sentinel, and AI engineering
- Azure Firewall, Bastion, VPN Gateway, and other charge-heavy services unless separately justified
- senior architect, lead, or principal-level scope

Deferred items remain outside the active plan. They may enter the backlog only through a recorded scope decision.

## 5. Resource and cost constraints

- The primary laboratory host has passed a private capacity and virtualisation audit.
- Standby and secondary-storage details remain in the private resource baseline and are not public dependencies.
- VMware Workstation is the single local hypervisor standard.
- Hyper-V and VirtualBox will not be used for the MVP.
- Direct project spend is capped at **£0** unless the portfolio owner explicitly approves a change.
- Azure for Students is the only approved Azure subscription for the MVP.
- Azure budgets, alerts, shutdown, deallocation, and teardown controls must exist before chargeable workloads are deployed.
- Microsoft business trials will not be activated until the associated build and evidence plan is ready for immediate execution.

## 6. Delivery method

Only one case study and one implementation task may be active at a time.

Every technical module follows this sequence:

1. Define the requirement and acceptance checks.
2. Approve the minimum architecture.
3. Implement the change.
4. Validate the expected state.
5. Introduce one controlled and relevant failure.
6. Diagnose and recover the service.
7. Record operational and interview evidence.
8. Review quality before publication.

New technologies, features, repositories, and documentation categories cannot be introduced during a module unless they are required to meet its acceptance criteria.

## 7. Evidence standard

A competency counts only when it is:

- **implemented** in a functioning environment;
- **validated** with suitable commands, logs, or tests;
- **troubleshot** through a controlled failure or realistic incident;
- **documented** as an operational record;
- **explainable** clearly in an interview.

Each case study must contain only the evidence needed to support its claims:

- architecture decision and diagram;
- implementation record;
- sanitised command or log evidence;
- validation checklist;
- incident or troubleshooting record;
- change record with risk, rollback, and result;
- knowledge article or operator procedure;
- concise lessons learned and interview explanation.

Screenshots alone are not accepted as proof.

## 8. Repository and documentation rules

- Use one portfolio repository with three numbered case-study directories.
- Do not create the repository until Case Study 1 requirements, architecture, naming, addressing, evidence structure, and acceptance criteria are approved.
- Use professional naming; the former public name **Back on Track** is retired.
- Existing portfolio repositories and files are legacy material and are not implementation sources for the reset.
- No empty scaffolding, placeholder-heavy folder trees, copied chat transcripts, or documentation for work that has not been performed.
- Commit by completed evidence unit, not by arbitrary activity.
- Never commit credentials, keys, tokens, recovery material, personal data, subscription identifiers, tenant identifiers, or unsanitised screenshots.

Approved repository: `bbben31/Infra-Ops-Lab`.

## 9. Delivery targets

Planning assumption: approximately 8–12 focused project hours per week around paid work and travel.

| Milestone | Target effort | Release condition |
|---|---:|---|
| Foundation and Case 1 design | 3–5 hours | Architecture and acceptance criteria approved |
| Case Study 1 | 16–20 hours | Publishable Windows operations and recovery evidence |
| Case Study 2 | 10–14 hours | Publishable identity and endpoint evidence |
| Case Study 3 | 12–16 hours | Publishable Azure operations and automation evidence |
| Portfolio integration and application material | 4–6 hours | Recruiter-facing release reviewed |

**First publishable release:** within approximately 14 calendar days.
**Complete MVP:** approximately 5–6 weeks, subject to the stated weekly availability and licence windows.

Applications continue during delivery. Case Study 1 is added to application materials immediately after its release gate.

## 10. Governance rules

- This charter is the scope baseline.
- One task is issued, completed, and checked before the next task begins.
- New ideas are placed in a backlog and do not interrupt active work.
- A change is accepted only when it improves target-role evidence, removes a blocker, reduces risk, or lowers delivery time/cost.
- Technical implementation cannot begin without defined acceptance criteria.
- Documentation describes verified work; it does not substitute for implementation.
- Failed tests and recovery actions are retained when they provide useful, sanitised evidence.
- The shortest solution that meets the evidence standard is preferred.

## 11. Stage gates

| Gate | Required decision |
|---|---|
| Gate 0 | Resource audit, role matrix, and charter approved |
| Gate 1 | Case Study 1 requirements and architecture approved |
| Gate 2 | Case Study 1 validated and published |
| Gate 3 | Case Study 2 validated and published |
| Gate 4 | Case Study 3 validated and published |
| Gate 5 | Integrated portfolio and application narrative approved |

## 12. Current execution point

Gate 1 and Task 1.2 have passed. The active task is **Task 1.3 — local build preflight**.

Task 1.3 privately validates VMware, evaluation media, host connectivity, local storage, and backup prerequisites. No VM construction is authorised before that preflight passes.
