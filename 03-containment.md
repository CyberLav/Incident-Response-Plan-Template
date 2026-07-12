# 3. Containment

**Objective:** Stop the incident from getting worse while preserving the ability to
investigate and eradicate properly.

*Battle procedure steps 6–13.*

## 3.1 Step 6 — Issue Warning Order

Put responders and stakeholders on notice before you have the full picture. This is
deliberately incomplete, the goal is getting the right people moving, not full briefing.

- [ ] Response team notified via out-of-band channel
- [ ] Executive sponsor notified per severity threshold ([Annex A](annexes/A-severity-escalation-matrix.md))
- [ ] Legal notified if data exposure, regulated data, or litigation risk is plausible
- [ ] Initial holding statement drafted if customer/public-facing impact possible

## 3.2 Steps 7–8 — Detailed Scoping

- [ ] Full timeline of attacker activity reconstructed (earliest indicator to present)
- [ ] All affected systems, accounts, and data identified, not just the ones that alerted
- [ ] Persistence mechanisms identified (scheduled tasks, new accounts, implants, etc.)
- [ ] Data exposure scope assessed (what data, how sensitive, regulatory classification)

## 3.3 Steps 9–10 — Reconnaissance Plan and Execution

The forensic collection pass. Plan it before executing it.

- [ ] Collection priorities set (volatile evidence first: memory, active connections,
      running processes — before disk images)
- [ ] Chain of custody log opened for every artifact collected
      ([Annex F](annexes/F-evidence-chain-of-custody.md))
- [ ] Collection executed without altering evidence where avoidable (write blockers,
      read-only mounts, documented exceptions when live response is unavoidable)

## 3.4 Step 11 — Complete the Estimate

Synthesize scoping and recce findings into 2–3 candidate courses of action, each with:

- What it stops
- What it doesn't stop
- Operational cost (downtime, user impact, business disruption)
- Evidence impact (does this action destroy anything not yet collected?)

IC selects a COA and logs the decision and rationale
([Annex E](annexes/E-decision-log-template.md)).

## 3.5 Step 12 — Supplementary Warning Order

Update stakeholders with the refined plan before executing it, especially if the chosen
COA has business impact.

## 3.6 Step 13 — Prepare and Issue Orders

Formal order to the technical team executing containment. Use the SMESC format
([Annex C](annexes/C-smesc-order-template.md)) — Situation, Mission, Execution, Service
Support, Command & Signal.

- [ ] Short-term containment executed (isolate, block, disable. Stop the immediate bleeding)
- [ ] Long-term containment planned if short-term is a stopgap. Log the gap so it doesn't
      get forgotten once the pressure is off

---
[← Identification](02-identification.md) | [Next: Eradication →](04-eradication.md)
