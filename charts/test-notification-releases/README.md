# helm-chart-release

## Install Chart

```console
helm repo add treezio https://treezio.github.io/helm-chart-release
helm repo update
helm install [RELEASE_NAME] treezio/test-notification-releases
```

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```