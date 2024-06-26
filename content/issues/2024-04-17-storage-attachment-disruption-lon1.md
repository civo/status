---
title: Disruption in storage attachments in LON1
date: 2024-04-17 16:50:00
resolved: yes
resolvedWhen: 2024-04-17 17:00:00 
# Possible severity levels: down, disrupted, notice
severity: disrupted 
affected:
  - Compute/LON1
  - Storage/LON1
section: issue

---

2024-04-17 17:00:00

We believe the issue causing storage attachments to fail on new launches and volume mounts has been resolved and will continue to monitor the functionality of the platform.


---

2024-04-17 16:50:00 UTC

We are aware of a disruption in storage attachments in the LON1 region. Mounting volumes to existing virtual machine instances and nodes will not currently complete successfully. This is also impacting launches of new VM instances/Kubernetes nodes as they require a volume attachment to come online.

Existing workloads in the region continue to operate as normal. Restarting virtual machine instances or Kubernetes nodes will cause them to be affected.

We will update here when we have more details.
