---
title: Disruptions in Kubernetes cluster and compute instance launches in LON1
date: 2021-10-06 15:32:00
resolved: no
resolvedWhen:
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Compute/LON1

section: issue

---

update 15:40 GMT+1

The cause of hanging builds has been identified and we have applied a fix. We believe this should allow all new instances in LON1 to create successfully from this point onwards.

We would request that you delete any failed or "hanging" instances and Kubernetes clusters you may see in your account, and they should now build successfully on a subsequent attempt.

---

We are aware of an issue with the launches of new instances and Kubernetes clusters/nodes in the LON1 region.

We are investigating the cause and will update here when we know more.

Other Civo regions continue to function as normal, and existing workloads are not affected.
