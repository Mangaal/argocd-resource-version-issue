## Purpose

Repository containing a reproducer scenario for ArgoCD inserting the resourceVersion inside the last-applied-config annotation when the `.metadata.resourceVersion` is listed in the `.spec.ignoreDifferences`.

The repo reproduce the issue with the BuildConfig but it could be tested also with other resources.