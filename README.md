# Kubenetes

## ServiceAccount 作成
```
kubectl create serviceaccount useroot
```
## ACR Pull Secret 作成
```
kubectl create secret docker-registry acr-secret \
    --namespace <namespace> \
    --docker-server=acryutatestregistry.azurecr.io \
    --docker-username=acryutatestregistry \
    --docker-password=xAUSR0+SF2+UbjsIsm5uSjcHHmRJ+/Ml5XkELU6gwO+ACRBe5DTr
```
