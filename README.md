# Setup

1. [Install `kubectl` from apt](https://kubernetes.io/docs/tasks/tools/install-minikube/)
2. [Install `minikube` from .dev](https://github.com/kubernetes/minikube/releases)
3. Install a VM backend for minikube (`sudo apt install virtualbox`)
4. Start `minikube` VM (`minikube start`)
6. Deploy Ingress-NGINX Pods (`kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/mandatory.yaml`)
7. Enable `ingress` addon (`minikube addons enable ingress`)
8. Deploy anything you want


