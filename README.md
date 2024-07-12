# nlw-journey-go

utlizando o https://supabase.com/ pra criar uma imagem externa de um banco de dados

```

kubectl create namespace journey

kubectl apply -f k8s/secret.yml -n journey
kubectl apply -f k8s/deployment.yml -n journey

<!-- se nao passar o namespace, pega o default -->
kubectl get pods -n journey

 kubectl delete deployment journey-deployment -n journey
```
