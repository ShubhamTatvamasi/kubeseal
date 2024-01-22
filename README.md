# kubeseal


```bash
kubeseal \
  --controller-name=sealed-secrets \
  --controller-namespace=system \
  --format yaml \
  < harbor-registry-secret.yaml > sealed-harbor-registry-secret.yaml
```
