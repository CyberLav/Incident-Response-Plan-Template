# Annex I — Playbook Index

Modular playbooks that plug into the core phases (01–06) without altering the framework
itself. Each playbook should reference the phase files rather than repeating them.

| Playbook | Status |
|---|---|
| [Ransomware](../playbooks/ransomware.md) | Draft |
| [Business Email Compromise (BEC)](../playbooks/bec.md) | Placeholder |
| [Insider Threat](../playbooks/insider-threat.md) | Placeholder |
| [DDoS](../playbooks/ddos.md) | Placeholder |
| [Cloud Account/Workload Compromise](../playbooks/cloud-compromise.md) | Placeholder |

## Playbook Template Structure

Each playbook should contain only what's *different* from the core framework:

1. Incident-type-specific indicators (how you know this is the type you're facing)
2. Type-specific containment options (e.g., ransomware: isolate vs. shut down entirely)
3. Type-specific stakeholders (e.g., BEC often needs Finance/AP involved immediately)
4. Type-specific regulatory or legal considerations
5. Links back to the relevant core phase for everything else

---
[← Back to framework overview](../00-framework-overview.md)
