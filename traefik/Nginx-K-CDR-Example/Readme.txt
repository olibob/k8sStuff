# Nginx example

Start with the secret needed for basic auth:

```
kubectl apply -f ng-basic-auth-secret.yaml
```

Then add the middlewares.
Then add the ingress for http/https
