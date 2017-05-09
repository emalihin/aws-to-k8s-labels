## aws-to-k8s-labels

Translate AWS instance tags into Kubernetes labels.

This Pod runs in the `kube-system` namespace on k8s master nodes.

### Deployment

```
kubectl --context CONTEXT -n kube-system apply -f deploy.yml
```
