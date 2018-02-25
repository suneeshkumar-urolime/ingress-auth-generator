# Ingress Auth Generator Daemon For Kubernetes Ingress

Uses the `IngressAuthGenerator`  to create  basic authentication for Kubernetes ingress controllers.


## How it works?

This simple `Golang` application helps you to transform your passwords from `k8s secrets` to `htaccess k8s secrets`. It can use the ingress controllers by default.


## How can you use it?

Please take the exaple files to replace the placeholder variables, and apply them with [kubectl](https://kubernetes-v1-4.github.io/docs/user-guide/kubectl/kubectl_apply/).
