# How to setup two-tier application deployment on kubernetes cluster
## First setup kubernetes kubeadm cluster
## SetUp
- First clone the code to your machine
```bash
git clone https://github.com/Sachinsharmak/2-Tier-Application-Deployment.git
```
- Move to k8s directory
```bash
cd 2-Tier-Application-Deployment/K8s
```
- Now, execute below commands one by one
```bash
kubectl apply -f two-tier-app-pod.yml
```
```bash
kubectl apply -f two-tier-app-deployment.yml
```
```bash
kubectl apply -f two-tier-app-svc.yml
```
```bash
kubectl apply -f mysql-deployment.yml
```
```bash
kubectl apply -f mysql-pv.yml
```
```bash
kubectl apply -f mysql-pvc.yml
```
```bash
kubectl apply -f mysql-svc.yml
```