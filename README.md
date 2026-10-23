# KAOS project repository

This repository is managed by the KAOS platform. It was created from the
`novelcore/kubeproject` template when its KubeProject was provisioned.

The platform writes everything here; do not edit these files by hand.

- `root/autov2/` — ArgoCD ApplicationSets for this project
- `kubeapps/<app>/` — deployment manifests for each KubeApp (overlays per environment)
