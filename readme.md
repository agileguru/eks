1. helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
1. helm repo update
1. kubectl get nodes
1. helm install my-nginx ingress-nginx/ingress-nginx 
1. kubectl get ingressClass
> nginx   k8s.io/ingress-nginx   <none>       4m43s
1. helm repo add kcert https://nabsul.github.io/helm
1. helm install kcert kcert/kcert --namespace kcert --create-namespace --set acmeEmail=webtechguru@gmail.com --set acmeDirUrl=https://acme-v02.api.letsencrypt.org/directory --set acmeTermsAccepted=true --version 1.0.6