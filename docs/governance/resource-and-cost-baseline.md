# Resource and Cost Baseline

**Task:** 0.1 amendment
**Version:** 1.1 — public sanitised edition
**Date:** 22 July 2026
**Status:** Approved; private infrastructure details withheld

## Approved resources

| Resource | Role | Decision |
|---|---|---|
| Capacity-verified Windows host | Primary VMware host | Approved; exact hardware and local storage details remain private |
| Standby host | Recovery and lightweight testing | Approved; not part of Case Study 1 topology |
| Secondary local storage | Private backup and evidence archive | Conditional on health, access-control, and restore testing |
| Stable wired connectivity | Physical host connectivity | Approved; local network details remain private |
| Azure for Students | Case Study 3 | Approved within included credit only |
| Microsoft 365 Personal | Productivity applications and OneDrive | Not an enterprise administration tenant |
| VMware Workstation 25 | Local hypervisor standard | Approved |

## Secondary-storage boundary

Secondary storage is not a hypervisor, domain service, or required runtime dependency. Case Study 1 must continue to operate if it is unavailable.

Secondary storage may be used for:

- a secondary copy of powered-off VM backups;
- private storage of raw evidence before sanitisation;
- versioned copies of project documentation and configuration exports;
- restore testing after its storage and access configuration is verified.

Secondary storage must not be:

- exposed through router port forwarding;
- used to publish credentials, raw Active Directory backups, or personal data;
- accessed directly by the lab VMs during the MVP unless a later change record explicitly authorises it;
- presented as a substitute for the required Windows system-state and GPO recovery evidence.

Its exact IP address, share names, serial numbers, user accounts, and storage configuration remain private.

## Cost ceiling

| Category | Limit |
|---|---:|
| New hardware | £0 |
| Direct Azure spending | £0 |
| Microsoft business licences | £0 |
| Local software | £0 |
| Included Azure education credit | Permitted only under later cost controls |

No Pay-As-You-Go conversion, paid marketplace product, or paid Microsoft trial conversion is authorised.
