---
title: Cluster launches unavailable
date: 2021-03-17 13:45:00
resolved: false
resolvedWhen: 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Storage/NYC1
section: issue
---

We have found the cause of the issue stopping from clusters being created.
New clusters should now start successfully.

While we ensure that all compute nodes are updated to resolve the issue, users will see their cluster nodes reboot in turn while each node is updated.

We will continue to monitor the situation to watch that no further disruption to cluster launches.

---

We are investigating a potential internal network issue that is hampering new node creation. This means that new clusters will not create successfully and node recycles/reboots will not complete.

Existing workloads are running, and will continue to do so.
