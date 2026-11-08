---
title: Degraded storage performance in LON1
date: 2026-11-08 17:30:00
resolved: true
resolvedWhen: 2026-11-08 18:30:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Storage/LON1
  - Compute/LON1
section: issue

---

2026-11-08 18:30 UTC

Storage performance in the London (LON1) region has returned to normal and the fix has held under monitoring. Volume latency is back to expected levels and affected Kubernetes clusters are serving control-plane requests normally again. This incident is now resolved. Thank you for your patience.

---

2026-11-08 17:30 UTC

We are investigating degraded storage performance in the London (LON1) region. Some customers may experience increased latency or intermittent slowness when accessing volumes, and a small number of Kubernetes clusters in this region may see slow or temporarily unresponsive control-plane (API server) requests as a result. Our engineering team is actively investigating and we will provide further updates as more information becomes available.
