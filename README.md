# Helm Chart

## Package

```shell
helm package ./charts/cp-schema-registry
mv cp-schema-registry-*.tgz docs/
helm repo index docs --url https://shepherd44.github.io/helm-charts
```
