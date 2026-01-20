# Kuberenetes

### get all ingress in a cluster
kubectl get ingress --all-namespaces

### describe an ingress implementation
kubectl describe ingress name-of-ingress -n namaspace

### get output
kubectl get ingress name-of-ingress -n namaspace -o yaml

### get ingress controller ingressClass
kubectl get ingressclasses.networking.k8s.io

### get all PVCs in a cluster
kubectl get pvc --all-namespaces

### check if traefik custom resource definition crd exists
kubectl get crd | grep traefik

# --------------------------------------------------------------------------------------------------------------------------------------------

# Python

### create a new virtual environment
python3 -m venv venv

### activate the virtual environment 
Fish -> source venv/bin/activate.fish
bash -> source venv/bin/activate

### deactivate the environment
deactivate
