# Annex H — Tier Scaling Guide

This plan is designed to scale without duplicating the core framework. Pick the tier that
matches your organization and apply its adjustments on top of phases 01–06.

## Small Org (1–2 person security function)

- Formality: verbal/chat-based orders acceptable; SMESC format still recommended for
  anything beyond a SEV3/4 incident
- IC may hold multiple roles simultaneously (see [Annex B](B-raci-matrix.md))
- Tooling assumption: basic logging, no dedicated SIEM/SOAR — investigation steps in
  [Containment](../03-containment.md) may take longer; adjust time targets accordingly

## Mid-size (dedicated security team, no full SOC)

- Formality: written orders for SEV1/2, verbal acceptable for SEV3/4
- Role separation begins (IC, Technical Lead, Scribe as distinct people)
- Tooling assumption: SIEM in place, manual correlation

## Enterprise (SOC/CSIRT, full hierarchy)

- Formality: written SMESC orders standard for all severities
- Full role separation, SOC tier 1/2/3 escalation path, dedicated forensics function,
  legal counsel and PR agency on retainer
- Tooling assumption: SIEM/SOAR, automated playbook execution for common containment
  actions

---
[← Back to framework overview](../00-framework-overview.md)
