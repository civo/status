---
title: Degraded storage performance in LON1
date: 2026-11-08 17:30:00
resolved: true
resolvedWhen: 2026-11-09 19:30:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Storage/LON1
  - Compute/LON1
section: issue

---

2026-11-09 19:30 UTC

The underlying fault in the London (LON1) region has been repaired, and storage performance has remained stable under monitoring since our last update. This incident is now resolved. Thank you for your patience.

---

2026-11-08 18:30 UTC

We have applied a mitigation and storage performance in the London (LON1) region has returned to normal. Volume latency is back to expected levels and affected Kubernetes clusters are serving control-plane requests normally again. We are keeping this incident open and continuing to monitor until the underlying issue is fully resolved. Thank you for your patience.

---

2026-11-08 17:30 UTC

We are investigating degraded storage performance in the London (LON1) region. Some customers may experience increased latency or intermittent slowness when accessing volumes, and a small number of Kubernetes clusters in this region may see slow or temporarily unresponsive control-plane (API server) requests as a result. Our engineering team is actively investigating and we will provide further updates as more information becomes available.
