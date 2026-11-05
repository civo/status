---
title: Scheduled Maintenance — Public Ingress (LON1, FRA1, NYC1, MUM1)
date: 2026-11-05 06:00:00
resolved: false
severity: notice
affected:
  - Storage/LON1
  - Compute/LON1
  - Storage/FRA1
  - Compute/FRA1
  - Storage/NYC1
  - Compute/NYC1
  - Storage/MUM1
  - Compute/MUM1
section: issue

---
We will be performing scheduled maintenance on the public ingress across LON1, FRA1, NYC1 and MUM1 between **06:00 and 21:30 UTC on 5 November 2026**. Regions will be updated one at a time.

Each region's ingress controller will be briefly restarted to apply a configuration change. During its update, you may experience a short interruption (around 30 seconds) to Object Storage and the VNC console in that region. No action is required on your part, and DNS resolution is not affected.

We will update this notice as the maintenance progresses.
