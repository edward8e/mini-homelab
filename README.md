# Mini-Homelab helm chart

## About
k3s-homelab-arm64-cluster
This is my personal Homelab cluster, using 4 raspberry pis running rapios arm64 bit os. 

## Installation

```console
helm repo add edward8e https://edward8e.github.io/mini-homelab/
helm upgrade -i mini-homelab edward8e/mini-homelab -f values.yaml
```