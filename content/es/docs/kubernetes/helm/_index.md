---
Title: Gráficos de Helm de OpenTelemetry
linkTitle: Gráficos de Helm
default_lang_commit: f9893e13ba9ea10f1b5bcecb52cdd3d907bf0fd9
---

## Introducción

[Helm](https://helm.sh/) es una solución CLI para administrar aplicaciones de
Kubernetes.

Si eligió usar Helm, puede usar [OpenTelemetry Helm Charts]
(https://github.com/open-telemetry/opentelemetry-helm-charts) para gestionar las
instalaciones del [OpenTelemetry Collector](/docs/collector),
[OpenTelemetry Operator](/docs/kubernetes/operator), y
[OpenTelemetry Demo](/docs/demo).

Agregue el repositorio OpenTelemetry Helm con:

```sh
helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts
```
