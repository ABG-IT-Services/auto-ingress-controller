# auto-ingress-controller
auto-ingress-controller is a nginx ingress controller that will watch all the Services in a k8s cluster and create nginx ingress controller based on the annotations in service

### Pre-requisite
- Ingress nginx controller running on your k8s cluster. Guide to [deploy][1] ingress controller.
- [ExternalDNS][2] for linking your domain name provider.



[1]: https://kubernetes.github.io/ingress-nginx/deploy/
[2]: https://github.com/kubernetes-sigs/external-dns
