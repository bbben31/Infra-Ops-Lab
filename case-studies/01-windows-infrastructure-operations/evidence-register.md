# Case Study 1 Evidence Register

**Status:** Not started
**Rule:** A path is created only when verified evidence exists. `Planned` does not mean implemented.

| ID | Evidence unit | Planned repository path | Acceptance mapping | Status |
|---|---|---|---|---|
| E-01 | Final case-study overview and business outcome | `case-studies/01-windows-infrastructure-operations/README.md` | AC-01–AC-15 | Planned |
| E-02 | Final architecture and addressing record | `case-studies/01-windows-infrastructure-operations/design/` | AC-01–AC-05 | Planned |
| E-03 | Build and change record | `case-studies/01-windows-infrastructure-operations/operations/changes/` | AC-01–AC-09 | Planned |
| E-04 | Sanitised AD DS, DNS, DHCP, GPO, patching, and backup validation | `case-studies/01-windows-infrastructure-operations/evidence/validation/` | AC-02–AC-11 | Planned |
| E-05 | PowerShell lifecycle automation and usage guide | `case-studies/01-windows-infrastructure-operations/automation/` | AC-10 | Planned |
| E-06 | DNS incident record | `case-studies/01-windows-infrastructure-operations/operations/incidents/INC-01-dns.md` | AC-13 | Planned |
| E-07 | GPO incident record | `case-studies/01-windows-infrastructure-operations/operations/incidents/INC-02-gpo.md` | AC-13 | Planned |
| E-08 | DHCP incident record | `case-studies/01-windows-infrastructure-operations/operations/incidents/INC-03-dhcp.md` | AC-13 | Planned |
| E-09 | Directory-object and GPO recovery record | `case-studies/01-windows-infrastructure-operations/operations/recovery/` | AC-11–AC-12 | Planned |
| E-10 | Domain-join or DNS knowledge article | `case-studies/01-windows-infrastructure-operations/operations/knowledge/` | AC-03–AC-05 | Planned |
| E-11 | Operational handover | `case-studies/01-windows-infrastructure-operations/operations/handover.md` | AC-09, AC-15 | Planned |
| E-12 | CV bullets and 90-second interview explanation | `case-studies/01-windows-infrastructure-operations/recruitment/` | AC-15 | Planned |

## Publication controls

Before any evidence is committed:

- replace real people with synthetic lab identities;
- remove home-network addresses, hostnames, account names, device identifiers, and storage paths;
- exclude passwords, licence keys, tokens, tenant or subscription identifiers, and recovery material;
- convert raw outputs into the smallest useful sanitised excerpt;
- verify that screenshots add information not already conveyed by text;
- run a final content and secret scan.
