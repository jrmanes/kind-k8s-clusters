# Kind-K8S-Clusters

The pourpose of this repository is for store different kind of cluster which will be created using the tool [KIND](https://kind.sigs.k8s.io/).

# Useful commands

```
kind create cluster --config <config_file.yaml>
```

```
kind get clusters
kubectl cluster-info --context kind-kind
kind delete cluster
```