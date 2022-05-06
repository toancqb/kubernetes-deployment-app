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

### Demo
![alt text](https://github.com/toancqb/kubernetes-deployment-app/blob/master/images/Screenshot_from_2022-05-06_15-22-00.png?raw=true)

![alt text](https://github.com/toancqb/kubernetes-deployment-app/blob/master/images/Screenshot_from_2022-05-06_15-22-27.png?raw=true)
