---
title: Civo Volumes not working in LON1 and NYC1
date: 2021-05-08 11:41:00
resolved: no
resolvedWhen:
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - LON1/Storage
  - NYC1/Storage
section: issue
---

Currently CivoVolumes (the native PV/CSI driver) aren't working correctly in LON1 and NYC1. We're hard at work on the issue, but it's turning out to be very tricky. We'll update as we know more. For the moment, we have a temporary fix if you have a problematic volume. You may change it away from a CivoVolume to local-path by using the following kubectl commands:

kubectl patch storageclass local-path -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"true"}}}'

kubectl patch storageclass civo-volume -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"false"}}}'
