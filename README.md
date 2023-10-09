# Ericsson Cloud Ran Challenge

## Application deployment

To deploy [hello-app](https://console.cloud.google.com/gcr/images/google-samples/GLOBAL/hello-app:2.0/details), run the following commands:

1. `kubectl apply -f deployment.yaml`
2. `kubectl apply -f service.yaml`

And finally test it with `curl http://localhost:8080`.

## Application deployment using Helm Chart

To deploy [hello-app](https://console.cloud.google.com/gcr/images/google-samples/GLOBAL/hello-app:2.0/details) using a Helm Chart, run the following commands:

1. `helm install hello-app-helm hello-app-chart`

## Additional useful commands to check progress

1. `kubectl get service`
2. `kubectl get pod`
3. `helm list`


