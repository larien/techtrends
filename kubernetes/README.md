## Kubernetes Declarative Manifests 

Place the Kubernetes declarative manifests in this directory.

## Commands

### Create YAML template
kubectl create RESOURCE [REQUIRED FLAGS] --dry-run=client -o yaml
kubectl create deploy demo --image=nginx --dry-run=client -o yaml

### Apply resource from YAML
kubectl apply -f ./namespace.yaml