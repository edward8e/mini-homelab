![Version: 0.1.4](https://img.shields.io/badge/Version-0.1.4-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) 

<p align="center">
  <a href="https://github.com/edward8e/mini-homelab">
    <img src="./assets/homelab.svg" height="200" />
  </a>
</p>

# Mini-Homelab Helm Charts
Homelab Helm Charts compatible with ARM64 and ARM Docker Images.

Helm charts I've put together to quickly get up and running with the most popular homelab applications with the intension to run them on a Raspberry Pi k3s cluster.


## Installation

```console
# Add Helm Repo
helm repo add edward8e https://edward8e.github.io/mini-homelab/

# Update Repo list
helm repo update

# Install/Upgrade chart
helm upgrade -i sonarr edward8e/sonarr -f values.yaml

# List Charts
helm search repo edward8e

# Get values.yaml
helm show values edward8e/sonarr > values.yaml
```


