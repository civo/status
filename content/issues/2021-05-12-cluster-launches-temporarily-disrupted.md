---
title: Civo Volumes not working in LON1
date: 2021-05-08 11:41:00
resolved: no
resolvedWhen:
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - LON1/Storage
section: issue
---

Currently CivoVolumes (the native PV/CSI driver) aren't working in LON1. We're hard at work on the issue, but it's turning out to be very tricky. We'll update as we know more. For the moment, if you just want to experiment with CivoVolumes, NYC1 is working fine.
