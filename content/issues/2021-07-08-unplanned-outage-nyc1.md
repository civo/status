---
title: Unplanned Outage in NYC1
date: 2021-07-08 12:36:00
resolved: no
resolvedWhen:
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Storage/NYC1
  - Compute/NYC1
section: issue
---
14:12 GMT+1

Restarted virtual machines are reverting to read-only storage statu. We have our storage partner investigating why this is and will update as soon as we know more.

---
14:02 GMT+1

We are restarting workloads in NYC1.

---
13:09 GMT+1
Our team is working with our storage partner to identify the cause of the disruption. All existing instances and clusters continue to be affected, but we hope to have them restored back to running status very soon.

---
On Thursday 08 July at 12:34 GMT+1, an alert was generated that workload VMs (K3s and compute instance) were offline. The SRE team is currently
investigating and will provide updates as information is gathered. All workloads in NYC1 are affected by this outage. 
