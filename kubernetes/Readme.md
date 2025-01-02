## Kubernetes Pod Definitions

This repository contains Kubernetes Component definitions and yaml files for various applications.

### Pod: For Nginx
**File:** `pods/yaml/pod-nginx.yaml`

This Pod runs an NGINX container serving static content.

#### Apply the Pod
To deploy this Pod, run:
```bash
kubectl apply -f pods/pod-nginx.yaml
