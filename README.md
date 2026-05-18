# P2DP GitOps Repository

## Stack déployé
- **Argo CD** : GitOps sync automatique
- **Prometheus + Grafana** : Monitoring
- **Falco** : Détection menaces runtime
- **Jaeger + OpenTelemetry** : Tracing distribué
- **GitHub Actions** : CI/CD pipeline avec Trivy scan

## Namespaces
- `p2dp` : Application
- `argo` : Argo CD
- `observability` : Prometheus, Grafana, Jaeger, OTel
- `security` : Falco
