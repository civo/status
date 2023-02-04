---
title: Node pool scaling affected in All Regions
date: 2023-02-04 14:15:00
resolved: true
resolvedWhen: 2023-02-04 23:50:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Compute/FRA1
  - Compute/NYC1
  - Compute/LON1
section: issue

---

2023-02-04 18:20 GMT

The issue we have seen is now confined to node pool scaling. The issue around cluster launches has been mitigated, and  all pending cluster launches should be up.

---

2023-02-04 18:00 GMT

Clusters in regions are launching. New node pool creation is still disrupted.

---

2023-02-04 17:00 GMT

Our team has rolled out a fix to an issue but we are still working on enabling cluster and node starts. We apologize for the inconvenience. Existing workloads in all regions continue to run.

---

2023-02-04 14:15 GMT

We are noticing issues with new node and cluster launches in All Regions.

Existing workloads remain unaffected. Operations such as node recycling (which creates a new node and attaches it to an existing cluster), scaling nodepools and launching new clusters are affected though, and will not complete.

Our team is investigating the cause and we will update here.
