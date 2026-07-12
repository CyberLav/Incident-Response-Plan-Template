# 1. Preparation

**Objective:** Ensure the organization can detect and respond before an incident occurs.
This phase never truly ends; it runs continuously between incidents.

## 1.1 Standing Readiness Posture

Preparation is the organization's standing Warning Order, it is a permanent state of readiness, not a one-off task.

- [ ] Incident response team roster current, with backups identified for every role
- [ ] Out-of-band communication channel established (assume primary email/chat may be
      compromised during an incident — e.g., dedicated Signal group, phone tree)
- [ ] Tooling access verified: EDR, SIEM, log retention, forensic imaging capability,
      network isolation capability (VLAN quarantine, firewall block, cloud security groups)
- [ ] Legal, PR/comms, and executive escalation contacts confirmed and reachable 24/7
- [ ] Cyber insurance and outside counsel/forensics retainer details on file
- [ ] Regulatory notification obligations mapped by jurisdiction (see
      [Annex A](annexes/A-severity-escalation-matrix.md))
- [ ] Evidence handling and chain-of-custody procedure understood by all responders

## 1.2 Team Structure and RACI

See [Annex B](annexes/B-raci-matrix.md) for full RACI by organizational tier. At minimum,
define:

- **Incident Commander (IC):** owns the incident end to end, issues orders, is the single
  point of decision authority
- **Technical Lead(s):** execute containment/eradication actions
- **Scribe:** maintains the decision log and timeline in real time — do not skip this role,
  even in a one-person response
- **Communications Lead:** owns internal and external messaging
- **Executive Sponsor:** authorizes decisions above the IC's authority

## 1.3 Severity Classification

See [Annex A](annexes/A-severity-escalation-matrix.md). Every incident is classified
SEV1–SEV4 at Identification and re-classified if scope changes. Severity determines
escalation path *and* how much of the 16-step template can be compressed.

## 1.4 Training and Exercise Cadence

- [ ] Tabletop exercise minimum [quarterly / semi-annually]
- [ ] At least one exercise per year run at full template (timed, no advance warning)
- [ ] [Playbooks](playbooks/) reviewed and updated after every real incident and exercise

---
[← Framework overview](00-framework-overview.md) | [Next: Identification →](02-identification.md)
