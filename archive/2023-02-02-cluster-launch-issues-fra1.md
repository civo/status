---
title: Cluster launches affected in FRA1
date: 2023-02-02 14:00:00
resolved: yes
resolvedWhen: 2023-02-02 16:00:00 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Compute/FRA1
section: issue

---

2023-02-02 15:48 GMT

We believe we have located the cause of the launch issue and functionality should be restored. We are working on ensuring it does not repeat.

---

2023-02-02 14:00 GMT

We are noticing issues with new node and cluster launches in FRA1.

Existing workloads remain unaffected. Operations such as node recycling (which creates a new node and attaches it to an existing cluster), scaling nodepools and launching new clusters are affected though, and will not complete.

Our team is investigating the cause and we will update here.
