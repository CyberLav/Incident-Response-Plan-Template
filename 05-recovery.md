# 5. Recovery

**Objective:** Return to normal operations without reintroducing risk.

## 5.1 Restoration

- [ ] Systems restored from known-clean backups or rebuilt, not simply "cleaned in place,"
      wherever feasible
- [ ] Restored systems patched and hardened before returning to production
- [ ] Credentials rotated for all potentially exposed accounts, including service accounts
- [ ] Restoration order prioritized by business criticality (see
      [Annex H](annexes/H-tier-scaling-guide.md))

## 5.2 Heightened Monitoring

- [ ] Enhanced monitoring applied to restored systems for a defined period
      (e.g., 30/60/90 days depending on severity) to catch reinfection or missed persistence
- [ ] Monitoring thresholds documented and owned by a specific person, not left ambiguous

## 5.3 Stakeholder Sign-off

- [ ] Business owner confirms system functionality restored
- [ ] Executive sponsor confirms incident status downgraded from active
- [ ] Formal incident closure timestamp logged (this closes MTTR)

---
[← Eradication](04-eradication.md) | [Next: Lessons Learned →](06-lessons-learned.md)
