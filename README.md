# k8s-kafka

Apache Kafka on Kubernetes (minikube) via Helm.

## Prerequisites

- [minikube](https://minikube.sigs.k8s.io/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Helm](https://helm.sh/)

## Quick start

```bash
minikube start
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install kafka bitnami/kafka
```
