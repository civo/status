---
title: Services inaccessible in LON1
date: 2021-12-02 14:13:37
resolved: yes
resolvedWhen: 2021-12-02 21:00:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Customer hosted services in our LON1 region
  - Compute/LON1
section: issue
---

21:00 GMT

The last of the affected customer instances are back online in LON1, and this issue is resolved.

---

15:55 GMT

Having identified the issue, we are beginning the work of bringing affected customer clusters/instances back online.

---

14:45 GMT

Our engineers are working on a fix to the issue. To allow us to restore functionality of existing services in LON1 we have temporarily suspended any new launches and access to that region.

---

14:20 GMT

Our automated alerting picked up an issue with our LON1 region at 14:13 GMT. It's reporting that a lot of instances and Kubernetes nodes are currently unavailable (but still present in the region). We're investigating and will update as we know further.
