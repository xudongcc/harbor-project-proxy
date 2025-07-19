# Harbor Project Proxy

## Install

```bash
helm upgrade harbor-project-proxy oci://ghcr.io/xudongcc/harbor-project-proxy \
  --install \
  --create-namespace \
  --namespace harbor \
  --set nginx.ingress.enabled=true \
  --set nginx.ingress.hostname=docker.example.com
```
