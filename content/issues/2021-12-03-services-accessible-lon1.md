---
title: Services inaccessible in LON1
date: 2021-12-03 11:09:04
resolved: no
# resolvedWhen: 2021-12-02 21:00:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Customer hosted services in our LON1 region
  - Compute/LON1
section: issue
---

11:09 GMT

We've been alerted again to an issue with our LON1 region where our storage platform has caused some nodes in the supercluster to pause their workloads (in order to ensure data safety). Some workloads remain running and we're cycling through the remaining ones to restore availability now. We'll also be getting deeper in to this with our storage provider to determine the cause of these issues.
