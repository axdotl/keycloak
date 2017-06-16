# Keycloak on Kubernetes

To get Keycloak running in Kubernetes adjust the yaml files to your needs (e.g. Ingress host address).

Deploy:
```
$ kubectl apply -f keycloak_postgres.yaml
$ kubectl apply -f keycloak.yaml
```
