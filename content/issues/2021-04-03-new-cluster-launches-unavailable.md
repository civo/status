---
title: Clusters and instances won't launch
date: 2021-05-03 09:00:00
resolved: yes
resolvedWhen: 2021-05-03 22:00:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Compute/NYC1
  - Storage/NYC1
section: issue
---

Got the storage cluster system working again, nothing like a pre-launch excitement. Thanks everyone for your patience.

---

We’re seeing an issue with new clusters and instances not launching, due to their underlying volumes not launching. This was due to an internally rotated TLS certificate.

We are working with our storage partners to re-enable new volume creation.

Existing workloads are running, and will continue to do so.
