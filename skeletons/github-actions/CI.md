# CI/CD

No GitHub Actions workflows are included in this repository.

The upstream version of this skeleton ships a CI workflow (build + push to Quay.io)
and an ArgoCD deployment workflow, both of which require infrastructure
(a Quay registry and an OpenShift cluster) that this environment doesn't have
configured. Rather than generate workflows that would fail on first push, they
were removed here.

To add them back, see the originals at:
https://github.com/redhat-developer/red-hat-developer-hub-software-templates/tree/main/skeletons/github-actions/.github/workflows
