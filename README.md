## Author: Quang Toan TRAN
### CFA Insta, 06/05/2022
### kubernetes-deployment-app


## Commands: 
### Create pods and services
### Database redis:
```bash
kubectl create -f QuangToanTRAN_redis-deployement.yaml
```
```bash
kubectl create -f QuangToanTRAN_redis-service.yaml
```

### Web Application
```bash
kubectl create -f QuangToanTRAN_webapp-deployement.yaml
```
```bash
kubectl create -f QuangToanTRAN_webapp-service.yaml
```

