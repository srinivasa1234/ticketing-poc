# Microservices app running through docker & kubernets

### Install all dependencies individually

```bash
npm install
```

### Run all individually

```bash
npm start
```

### docker commands

```bash
docker build -t  dockerid/client

docker push dockerid/client

```

### kubernets commands

```bash
kubectl get pods or services or deployments

kubectl delete pod pod_name

kubectl logs  pod_name

kubectl apply -f config-file-name

kubectl create secret generic stripe-secret  --from-literal STRIPE_KEY=sk-test-key

kubectl get secrets
```
