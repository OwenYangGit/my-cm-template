# My cert-manager template
## helm install cert-manager
```
helm repo add jetstack https://charts.jetstack.io
helm install cert-manager jetstack/cert-manager --namespace cert-manager --version v1.0.0 --set installCRDs=true
```
