---
title: Clusters not launching with Traefik and Metrics-server
date: 2021-03-31 12:42:00
resolved: yes
resolvedWhen: 2021-03-31 15:30:00
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Compute/NYC1
  - Storage/NYC1
section: issue
---

Updates to the operator have been completed and clusters launch with the default applications successfully. If you continue to experience issues with launching new clusters, please contact us through your account with details of the cluster(s) affected.

---

We’re seeing an issue with new clusters not starting `Traefik` and `metrics-server` even when not requested to be removed from new clusters. 

We are updating an operator to fix this issue.
If you are seeing a cluster that is not responding correctly, we advise to delete it and start a new cluster once this issue is marked resolved.

Existing workloads are running, and will continue to do so.
