---
title: Services inaccessible in NYC1
date: 2021-12-19 09:23:00
resolved: yes
resolvedWhen: 2021-12-19 10:22:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - Customer hosted services in our NYC1 region
  - Compute/NYC1
section: issue

---

10:22GMT

All affected customer VMs have been restarted now. Event closed.

---

10:03GMT

All affected compute hosts have been rebooted, just rolling through affected customer VMs restarting them. About 30 minutes until things are back to normal.

---

09:23GMT

NYC1 is being hit by the same issue as recently. Some workloads remain running and we're cycling through the remaining ones to restore availability now.

StorageOS has a release candidate of a fix for this issue which we're hoping to have as a full release and roll out early next week.
