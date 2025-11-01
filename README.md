# homelab-node-feature-discovery

This is a mirco-services repo for deploying
[node-feature-discovery](https://kubernetes-sigs.github.io/node-feature-discovery/stable/get-started/index.html)
into [my homelab](https://github.com/charlesthomas/homelab).

```
$ helm template -n node-feature-discovery --namespace node-feature-discovery oci://registry.k8s.io/nfd/charts/node-feature-discovery --version 0.18.2 | split-by-kind
```

---
This repo is templated via
[homelab-template](https://github.com/charlesthomas/homelab-template)
and automatically updated via
[🤖 Templatron](https://github.com/charlesthomas/templatron).
