Co jest potrzebne?
- minikube
- kubectl
- obraz w webapp - jest z publicznego repozytorium dockera Nany: nanajanashia/k8s-demo-app:v1.0

Jak zbudować?
Budujemy każdy plik zaczynajac od:
mongo-config.yaml
mongo-secret.yaml
mongo.yaml
webapp.yaml

Przykład:
"kubectl apply -f mongo-config.yaml"