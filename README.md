# Infrastructure Operations Portfolio

An evidence-led portfolio demonstrating operational capability in Windows infrastructure, Microsoft identity and endpoint administration, and cost-controlled Azure infrastructure.

## Current status

**Case Study 1 — design approved; implementation not yet started.**

This repository does not claim that planned work has already been completed. Evidence is published only after implementation, validation, controlled failure, diagnosis, recovery, and sanitisation.

## Portfolio roadmap

1. **Windows Infrastructure Operations and Recovery** — Active
2. **Identity and Endpoint Operations** — Deferred until Case Study 1 passes its release gate
3. **Azure Infrastructure Operations and Automation** — Deferred until Case Study 2 is complete

## Case Study 1

The first case study models a small organisation that requires central identity, workstation management, IP address allocation, name resolution, operational support, and tested recovery.

The approved minimum environment contains:

- one Windows Server 2025 domain controller;
- one Windows 11 Enterprise client;
- Active Directory Domain Services, DNS, DHCP, and Group Policy;
- the isolated `corp.test` lab domain;
- PowerShell lifecycle automation;
- controlled DNS, GPO, and DHCP incidents;
- directory-object and GPO recovery drills.

See the [approved requirements and architecture](docs/design/case-study-01-requirements-and-architecture.md) and the [Case Study 1 evidence register](case-studies/01-windows-infrastructure-operations/evidence-register.md).

## Evidence policy

Every published claim must be supported by a working implementation, a repeatable validation, a relevant troubleshooting or recovery exercise, and an operational record. Screenshots are supporting material, not standalone proof.

Evaluation media, virtual machines, raw backups, credentials, tenant identifiers, home-network details, personal data, and unsanitised evidence are never committed.
