---
title: DNS resolution of new Civo clusters disrupted
date: 2021-11-12 13:32:00
resolved: no
resolvedWhen:
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Network/NYC1
  - Network/FRA1
  - Network/LON1
  
section: issue
---

17:00 GMT

DNS resolution of new clusters (and any created in the meantime) should now be successful. It may take a bit of time for the change to propagate, and we will continue to monitor this issue, but it should be resolved.

---
13:32 GMT

We are aware of DNS resolution of new clusters not working in all regions. The cluster master IP is connectable and routable, but the generated DNS name is currently not functioning correctly.

We are working in implementing a fix, and apologise for the inconvenience.
