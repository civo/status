---
title: Cluster launches affected in All Regions
date: 2023-02-04 14:15:00
resolved: false
resolvedWhen: 
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Compute/FRA1
  - Compute/NYC1
  - Compute/LON1
section: issue

---

2023-02-04 14:15 GMT

We are noticing issues with new node and cluster launches in All Regions.

Existing workloads remain unaffected. Operations such as node recycling (which creates a new node and attaches it to an existing cluster), scaling nodepools and launching new clusters are affected though, and will not complete.

Our team is investigating the cause and we will update here.
