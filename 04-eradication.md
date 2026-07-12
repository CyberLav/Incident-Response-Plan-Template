# 4. Eradication

**Objective:** Remove the root cause and any attacker foothold.

*Battle procedure steps 14–15.*

## 4.1 Step 14 — Coordinate Subordinate Activities

- [ ] All teams executing eradication actions synchronized (avoid one team eradicating
      while another is still collecting evidence from the same system)
- [ ] Third parties (MSSP, forensics vendor, cloud provider support) coordinated and
      briefed on the plan
- [ ] Legal/comms kept current as eradication actions are taken, especially if they affect
      systems referenced in a regulatory notification already sent

## 4.2 Step 15 — Supervise Deployment

- [ ] Root cause confirmed removed (not just the symptom) patch applied, credentials
      rotated, malicious accounts removed, persistence mechanisms eliminated
- [ ] Validation performed that eradication was complete before Recovery begins
- [ ] Eradication actions logged with timestamps for the AAR and any post-incident audit

**Decision point:** Do not proceed to Recovery until the IC and technical lead both
formally sign off that eradication is validated complete. Log this sign-off.

---
[← Containment](03-containment.md) | [Next: Recovery →](05-recovery.md)
