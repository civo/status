---
title: Unplanned Outage in NYC01 on 7 July 2021
date: 2021-07-07 06:08:00
resolved: yes
resolvedWhen: 2021-07-07 07:24:00
# Possible severity levels: down, disrupted, notice
severity: Observing
affected:
  - Storage/NYC1
  - Compute/NYC1
section: issue
---
On Wednesday the 7th of July at 6:08am GMT+1, an alert was generated that workload VMs (k3s and compute instance) were offline. The SRE team is currently
investigating and will provide updates as information is gathered. All workloads in NYC1 are affected by this outage. 


At 6:48 GMT, all workloads were restarted. 

At 7:03 AM GMT, workloads startup began

At 7:24 AM GMT, all workloads have been started and are running

