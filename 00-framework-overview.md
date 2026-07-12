# Framework Overview

## Purpose

This plan governs how the organization detects, contains, eradicates, and recovers from
cybersecurity incidents, and how it captures and applies lessons afterward. It is built on
two layers working together:

- **SANS PICERL** provides the six phases every incident moves through: Preparation,
  Identification, Containment, Eradication, Recovery, Lessons Learned.
- **The 16-Step Battle Procedure** (NATO/Commonwealth military planning doctrine) provides
  the tempo discipline inside those phases — how a commander moves a team from
  notification to synchronized action under time pressure, without wasted motion.

PICERL tells you *what* phase you're in. Battle procedure tells you *how fast and how
formally* to move through it.

## Scope

Applies to any event that meets the Severity Classification criteria in
[Annex A](annexes/A-severity-escalation-matrix.md), across [systems/environments/business
units customize]. Excludes routine security operations (patching, standard alert triage)
that do not meet activation criteria.

## How to Use This Repository

- **[Reference plan](.)** (this repo, phases 01–06) full framework, used for planning,
  onboarding, tabletop exercises, and as the authoritative source when time allows for it.
- **Job aid** (companion one-page-per-phase quick reference, linked from the site) use
  during an active incident for execution. The reference plan explains *why*; the job aid
  tells you *what to do next*.
- **[Playbooks](playbooks/)** incident-type-specific detail that plugs into the phases
  below without altering the core framework.

## Core Definitions

| Term | Definition |
|---|---|
| IC | Incident Commander — single point of authority for the incident, regardless of rank/title outside the incident |
| COA | Course of Action — a proposed containment/eradication approach, evaluated before execution |
| Warning Order (WngO) | Early, incomplete notification that gets people moving before full details are known |
| Frag Order | Abbreviated order issued under time pressure, expanded later if time allows |
| SITREP | Situation Report — standardized status update issued on a set cadence |
| AAR | After Action Review — structured post-incident review |
| Recce | Reconnaissance — the technical investigation/evidence-gathering pass |

## Phase-to-Battle-Procedure Map

| Battle Procedure Step | IR Phase | Function |
|---|---|---|
| 1. Receive Warning Order | [Identification](02-identification.md) | Alert fires, incident suspected |
| 2–3. Quick map/time estimate | [Identification](02-identification.md) | Rapid triage (first ~15 min) |
| 4. Receive formal orders | [Identification](02-identification.md) | Severity classified, IC formally designated |
| 5. Mission analysis | [Identification](02-identification.md) | What's actually being asked of us |
| 6. Issue Warning Order | [Containment](03-containment.md) | Responders and stakeholders put on notice |
| 7–8. Detailed time/map estimate | [Containment](03-containment.md) | Deep scoping — systems, data, timeline |
| 9–10. Recce plan and execution | [Containment](03-containment.md) | Forensic/investigative collection |
| 11. Complete the estimate | [Containment](03-containment.md) | Finalize containment/eradication COA |
| 12. Supplementary Warning Order | [Containment](03-containment.md) | Stakeholders updated with refined plan |
| 13. Prepare and issue orders | [Containment](03-containment.md) | Formal order, [SMESC format](annexes/C-smesc-order-template.md) |
| 14. Coordinate subordinates | [Eradication](04-eradication.md) | Sync across IT, legal, comms, third parties |
| 15. Supervise deployment | [Eradication](04-eradication.md) | Oversee eradication execution |
| 16. Execute mission / AAR | [Recovery](05-recovery.md) / [Lessons Learned](06-lessons-learned.md) | Restore operations; formal After Action Review |
