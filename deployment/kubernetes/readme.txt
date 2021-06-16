kubectl apply -f .\deployment\kubernetes\stateful-services\
kubectl apply -f .\deployment\kubernetes\cdc-services\


kubectl apply -f .\ftgo-accounting-service/src/deployment/kubernetes/ftgo-accounting-service.yml
kubectl apply -f .\ftgo-kitchen-service/src/deployment/kubernetes/ftgo-kitchen-service.yml
kubectl apply -f .\ftgo-restaurant-service/src/deployment/kubernetes/ftgo-restaurant-service.yml
kubectl apply -f .\ftgo-api-gateway/src/deployment/kubernetes/ftgo-api-gateway.yml
kubectl apply -f .\ftgo-order-history-service/src/deployment/kubernetes/ftgo-order-history-service.yml
kubectl apply -f .\ftgo-consumer-service/src/deployment/kubernetes/ftgo-consumer-service.yml
kubectl apply -f .\ftgo-order-service/src/deployment/kubernetes/ftgo-order-service.yml
