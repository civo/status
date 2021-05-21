---
title: Civo Volumes not working in LON1 and NYC1
date: 2021-05-08 11:41:00
resolved: yes
resolvedWhen: 2021-05-21 15:33:20
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - LON1/Storage
  - NYC1/Storage
section: issue
---

CivoVolumes are provisioning correctly in both NYC1 and LON1. If you have a pre-existing volume you had created that did not correctly get provisioned, you may need to delete and re-create these volumes to ensure they get set up correctly. 

If you temporarily switched storageclasses while we were working on this issue, you can now re-enable CivoVolumes as the default storageclass by running:

kubectl patch storageclass civo-volume -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"true"}}}'

kubectl patch storageclass local-path -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"false"}}}'

---

Currently CivoVolumes (the native PV/CSI driver) aren't working correctly in LON1 and NYC1. We're hard at work on the issue, but it's turning out to be very tricky. We'll update as we know more. For the moment, we have a temporary fix if you have a problematic volume. You may change it away from a CivoVolume to local-path by using the following kubectl commands:

kubectl patch storageclass local-path -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"true"}}}'

kubectl patch storageclass civo-volume -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"false"}}}'

As this is a temporary fix until we resolve the issues, the default can be set back to civo-volume once this notice is cleared using the following commands:

kubectl patch storageclass civo-volume -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"true"}}}'

kubectl patch storageclass local-path -p '{"metadata": {"annotations":{"storageclass.kubernetes.io/is-default-class":"false"}}}'

