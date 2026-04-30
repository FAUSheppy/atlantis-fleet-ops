# Requirements
- Traefik Ingress Class
- certmanager cluster Issuer called letsencrypt-prod
# Manual Configuration Required
## Harbor
- OIDC needs to be manually configured, login via the Admin-Password set in `values.yaml` and go to Configuration -> Authentication
