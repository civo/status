---
title: DNS issue affecting Civo.com and domains managed by Civo's domain functionality
date: 2021-11-29 14:55:00
resolved: yes
resolvedWhen: 2021-11-29 15:46:00 
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Customer hosted domains
  - Civo.com Website
  - Civo API
section: issue
---

15:46 GMT

We believe the last propagation throughout the Domain Name System should be complete, meaning that access to civo.com, and any domains configured on Civo, should resolve correctly.

---

15:00 GMT

We are implementing a fix to restore service to one of our name servers which should allow access as soon as the update propagates through the Domain Name System.

---

14:55 GMT

We are aware of a DNS resolution issue affecting civo.com . Customer resources are running but access to the Civo website and any domain names within Civo's service are inaccessible at the moment.
