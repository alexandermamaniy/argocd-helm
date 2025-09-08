kubectl apply -f argocd/applications/helm-application.yaml 

kubectl create secret docker-registry ghcr-secret --docker-server=ghcr.io --docker-username=USERNAME  --docker-password=PASSWORD --namespace=argocd-helm