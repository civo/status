---
title: Cluster launches disrupted in LON1
date: 2021-06-10 10:57:00
resolved: yes
resolvedWhen: 2021-06-10 16:57:25
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Compute/LON1
  - Storage/LON1
section: issue
---

We have implemented a fix and resources on LON1 should be behaving as normal.

The incident that impacted our LON1 region was due to an underlying incompatibility with the container storage interface (CSI) provider implementation and containerd. This issue was the result of a build up of errors over time and resulted in a full scale outage when many of our supercluster nodes started flapping their readiness.

Whilst our initial investigation was delayed to the systemic nature and complexity in establishing a direct cause, the remediation once identified occurred within 45 minutes. We would like to reassure customers that all data is intact and only restarts have occurred on some customer workloads.

If for any reason you continue to see issues with your clusters or instances, please reach out to Civo support through your account.


---

We are continuing work on mitigating the disruption caused by underlying node storage issues. Currently, cluster launches are available as normal in the NYC1 region. While we work on the issue we cannot rule out the possibility of temporary disruption to existing nodes or instances.

---

LON1 super cluster is still partially degraded due to suspected underlying node storage CSI issues.
We have now re-enabled traffic and are continuing a triage and restoration of impacted nodes/services.

---

We are currently applying a rolling fix to address the underlying issue affecting cluster launches. New clusters will not be able to be launched while this process completes.

---

Cluster launches may be disrupted due to an issue we are aware of and are investigating. This may potentially affect running clusters. We will update here when we know more.
