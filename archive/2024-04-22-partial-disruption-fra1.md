---
title: Partial service disruption FRA1
date: 2024-04-22 13:37:00
resolved: yes
resolvedWhen: 2024-04-22 14:47:00
# Possible severity levels: down, disrupted, notice
severity: disrupted 
affected:
  - Compute/FRA1
  - Civo API
  - Civo.com website
section: issue

---

2024-04-22 14:47:00

We believe the timeout issue has been resolved and we are continuing to monitor for stability.

---

2024-04-22 14:42:00

API calls to FRA1 services are taking longer than usual causing timeouts accessing running resource administration pages on FRA1 as well as through the Civo API and CLI. We are working on a solution.

Existing services and resources continue to run and respond as normal.


---

2024-04-22 13:37:00 UTC

We are aware of a disruption in accessing resources in FRA1.

Existing workloads in the region continue to operate as normal. Restarting virtual machine instances or Kubernetes nodes will cause them to be affected.

We will update here when we have more details.
