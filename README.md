# README

```
$ kustomize build ./manifests/infra/sealed-secrets | kubectl apply -f -
$ kustomize build ./manifests/infra/argocd | kubectl apply -f -
```

```
$ kustomize build ./manifests/cd | kubectl apply -f -
```

## 参考
- https://github.com/GoogleCloudPlatform/microservices-demo
