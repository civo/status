---
title: Cluster launches disrupted in LON1
date: 2021-06-10 10:57:00
resolved: no
resolvedWhen: 
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Compute/LON1
  - Storage/LON1
section: issue
---

LON1 super cluster is still partially degraded due to suspected underlying node storage CSI issues.
We have now re-enabled traffic and are continuing a triage and restoration of impacted nodes/services.

---

We are currently applying a rolling fix to address the underlying issue affecting cluster launches. New clusters will not be able to be launched while this process completes.

---

Cluster launches may be disrupted due to an issue we are aware of and are investigating. This may potentially affect running clusters. We will update here when we know more.
