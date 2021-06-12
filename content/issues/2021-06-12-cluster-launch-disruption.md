---
title: Cluster launches disrupted intermittently
date: 2021-06-12 10:57:00
resolved: yes
resolvedWhen: 2021-06-12 17:59:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - LON1/Compute
  - NYC1/Compute
section: issue
---

Should all be fine again, we have implemented a major optimisation that dramatically reduces our internal Kubernetes API usage (with appropriate knock-on effects to etcd performance and network traffic). All graphs look MUCH healthier now.

--- 

Cluster launches may be disrupted intermittently due to an issue we are aware of and are investigating. We will update here when we know more.
