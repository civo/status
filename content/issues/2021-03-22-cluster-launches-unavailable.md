---
title: Cluster launches unavailable
date: 2021-03-22 10:45:00
resolved: true
resolvedWhen: 2021-03-22 11:30:00
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Storage/NYC1
  - Compute/NYC1
section: issue
---

The issue with new cluster launches has been fixed and users should be able to launch new Kubernetes clusters in the NYC1 region. Clusters that were launched prior to this fix may not come up and we advise you delete any pending clusters and launch again.

---

We have been alerted to an issue in cluster deployments that is preventing new clusters from launching. We are investigating the cause and will update here as soon as we have more information
