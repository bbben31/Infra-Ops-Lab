# Case Study 1 — Windows Infrastructure Operations and Recovery

## Status

Design approved. Build and evidence collection have not started.

## Business problem

A small organisation needs central identity, managed Windows endpoints, reliable DNS and DHCP, controlled administrative delegation, repeatable user lifecycle operations, and tested recovery without new infrastructure expenditure.

## Approved solution

- `DC01`: Windows Server 2025 Evaluation; AD DS, DNS, DHCP, and Windows Server Backup
- `CL01`: Windows 11 Enterprise Evaluation domain client
- Domain: `corp.test`
- Dedicated VMware NAT network using a private, non-overlapping lab subnet
- Direct spend: £0

## Completion rule

This case study becomes publishable only after all 15 acceptance criteria pass. Implementation notes, evidence files, scripts, incident records, and recovery records will be added only when the corresponding activity has been performed and sanitised.

Progress is controlled through the [evidence register](evidence-register.md).
