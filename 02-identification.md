# 2. Identification

**Objective:** Confirm whether a suspected incident is real, establish initial scope, and
formally activate the response.

*Battle procedure steps 1–5.*

## 2.1 Entry Criteria

Any of: automated alert, user report, third-party notification, threat intel match,
anomaly detected during routine monitoring.

## 2.2 Step 1 — Receive Warning Order

The moment of detection. Log the exact timestamp, this starts the clock for MTTD (Mean
Time to Detect) and, in many jurisdictions, regulatory notification timers.

- [ ] Timestamp recorded
- [ ] Initial detection source logged (tool, person, alert ID)
- [ ] On-call responder acknowledges within [target: 15 min]

## 2.3 Steps 2–3 — Quick Triage (target: 15 minutes)

Deliberately shallow, deliberately fast. The goal is a go/no-go decision, not full
understanding.

- [ ] What alerted, and on what asset/system?
- [ ] Is this plausibly a true positive?
- [ ] What is the apparent blast radius (single host vs. multiple, single user vs.
      privileged account, internal-only vs. internet-facing)?
- [ ] Initial severity estimate ([Annex A](annexes/A-severity-escalation-matrix.md))

**Decision point:** False positive → close and log for tuning. True positive or
uncertain → proceed to formal activation.

## 2.4 Step 4 — Formal Activation

- [ ] Incident formally declared, unique incident ID assigned
- [ ] IC designated (by role, not by whoever happened to be online)
- [ ] Severity classification confirmed ([Annex A](annexes/A-severity-escalation-matrix.md))
- [ ] Decision log opened ([Annex E](annexes/E-decision-log-template.md))

## 2.5 Step 5 — Mission Analysis

Before anyone touches a keyboard to contain anything, answer:

- What is actually being asked of us? (Stop the bleeding? Preserve evidence for
  prosecution? If both, which takes priority if they conflict?)
- What constraints apply? (Regulatory notification clocks, contractual SLAs, litigation
  hold requirements, business-critical system uptime commitments)
- What don't we know yet, and does that gap change our first move?

Output of this step is a one-paragraph mission statement the IC can state in plain
language to anyone who asks "what are we doing right now." If the IC can't state it in
one paragraph, this step isn't done.

---
[← Preparation](01-preparation.md) | [Next: Containment →](03-containment.md)
