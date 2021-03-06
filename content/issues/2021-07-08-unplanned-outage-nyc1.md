---
title: Unplanned Outage in NYC1
date: 2021-07-08 12:36:00
resolved: yes
resolvedWhen: 2021-07-08 17:12:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Storage/NYC1
  - Compute/NYC1
  - Civo API
section: issue
---
17:13 GMT+1

NYC1 resources are back online and customers should be able to connect to their clusters and instances as normal. We will continue to monitor the stability of the service. If you continue to experience trouble accessing your resources and workloads, please reach out through our support channels.

---
16:13 GMT+1

In order to restore connectivity we have had to disable the Civo API from the region. Users attempting to view their resources in NYC1 through their Civo account will encounter errors. If you have resources running in other regions these remain accessible.

---
15:40 GMT+1

Our storage partner is working to restore access to the storage nodes.

---
14:12 GMT+1

Restarted virtual machines are reverting to read-only storage status. We have our storage partner investigating why this is and will update as soon as we know more.

---
14:02 GMT+1

We are restarting workloads in NYC1.

---
13:09 GMT+1
Our team is working with our storage partner to identify the cause of the disruption. All existing instances and clusters continue to be affected, but we hope to have them restored back to running status very soon.

---
On Thursday 08 July at 12:34 GMT+1, an alert was generated that workload VMs (K3s and compute instance) were offline. The SRE team is currently
investigating and will provide updates as information is gathered. All workloads in NYC1 are affected by this outage. 
