![Version: 0.1.2](https://img.shields.io/badge/Version-0.1.2-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) 

# Homer
Homer Helm Chart compatible with ARM64 and ARM Docker Images.
Tested on K3s Raspberry Pi4 cluster.


### Testing on:
- Nodes: 4
- Kubernetes: k3s v1.22.6
- Hardware: Raspberry Pi 4 8gbs ram
- OS: Raspbian 64bit


## Installation

```console
# Add Helm Repo
helm repo add edward8e https://edward8e.github.io/mini-homelab/

# Update Repo list
helm repo update

# Install/Upgrade chart
helm upgrade -i homer edward8e/homer -f values.yaml

# List Charts
helm search repo edward8e
```
## Prerequisites
- Kubernetes 1.12+
- Helm 3.x
- PV provisioner support in the underlying infrastructure