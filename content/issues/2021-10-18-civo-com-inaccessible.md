---
title: Disruptions in DNS preventing access to civo.com
date: 2021-10-18 16:55:00
resolved: yes
resolvedWhen: 2021-10-18 17:45:00 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Civo.com Website
  - Civo API

section: issue

---

17:38 GMT+1

We have restored service to our nameserver which is permitting the resolution of .civo.com domains once again. We believe this should allow all users to access the site and API, but are continuing to monitor the situation and build resilience.

---

17:08 GMT+1

We have isolated the cause of the issue causing DNS resolution to civo.com and subdomains to fail. We are working on getting mitigation in place.

---

16:55 GMT+1

Due to an issue with DNS that we are investigating, civo.com and pages under it may appear unreachable. We are working on getting this mitigated as soon as possible.

Existing workloads continue to operate as normal.
