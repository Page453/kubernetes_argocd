Dieses Repository enthält Kubernetes-Deployments und Helm Charts für Demo-Zwecke mit ArgoCD.

## Projektstruktur

```
.
├── Argocd_Demo/          # Helm Chart für Argocd Demo
│   ├── Chart.yaml
│   ├── values.yaml       
│   ├── values-dev.yaml   
│   ├── values-prod.yaml  
│   └── templates/
│       ├── deployment.yaml
│       ├── service.yaml
│       └── configmap.yaml
└── Nginx_Demo/           # Nginx - Deployment und Service
    ├── nginx-deployment.yaml
    └── nginx-service.yaml
