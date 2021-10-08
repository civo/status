---
title: Disruptions in Kubernetes cluster and compute instance launches as well as API access in FRA1
date: 2021-10-08 10:59:00
resolved: no
resolvedWhen: 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Compute/FRA1
  - Network/FRA1
  - Civo API

section: issue

---

11:55 GMT+1

API queries to FRA1 are responding again, and new cluster nodes/instances are building successfully. We believe our mitigation efforts have worked. The API may respond with a bit of a delay until the issue is fully resolved.

We will continue to monitor to make sure the situation keeps improving. Thank you for your patience.

---

11:13 GMT+1

We believe we have identified the issue that is causing API timeouts and slow instance builds, and are working on mitigating it and restoring access.

---

10:59 GMT+1

We are aware of an issue with FRA1 which is causing timeouts and access errors through the Civo API, CLI and website. It is also affecting instance/cluster builds in that region.

We are investigating the cause and will update here when we know more.

Other regions and existing workloads continue to operate normally.
