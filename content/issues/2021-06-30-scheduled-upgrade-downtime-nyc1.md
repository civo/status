---
title: Planned Outage in NYC1 on 5 July 2021
date: 2021-06-30 14:35:00
resolved: no
resolvedWhen: 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Storage/NYC1
  - Compute/NYC1
  - Network/NYC1
section: issue
---
On Monday the 5th of July at 6am GMT+1 (1am ET, 10pm PT July 4th), there will be a planned outage of Civo region NYC1. We anticipate a window of three hours of unavailability for this region. 

This is to facilitate work to upgrade the data storage layer in use across our clusters, which will also enable non-disruptive updates in future. Whilst we apologise for the disruption, this is a vital upgrade that will enable faster and more efficient provisioning of volumes for Civo Kubernetes clusters and Infrastructure-as-a-Service Instances.

Users with active services on NYC1 will see connectivity restored as soon as the upgrade window is complete.
