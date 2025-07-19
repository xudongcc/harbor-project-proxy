# Harbor Project Proxy

## Install

```bash
helm upgrade --install harbor-project-proxy oci://ghcr.io/xudongcc/harbor-project-proxy -n harbor \
  --create-namespace \
  --set nginx.ingress.enabled=true \
  --set nginx.ingress.hostname=docker.example.com
```
