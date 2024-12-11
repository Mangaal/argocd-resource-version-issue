## Purpose

Repository containing a reproducer scenario for ArgoCD inserting the resourceVersion inside the last-applied-config annotation when the `.metadata.resourceVersion` is listed in the `.spec.ignoreDifferences`. The `.metadata.resourceVersion` is inserted in the annotation when a second Sybc is triggered in the ArgoCD UI. 

Issue was reproduced in OCP 4.12 and 4.16 with Openshift-GitOps 1.12.6.

The repo reproduce the issue with the BuildConfig but it could be tested also with other resources.