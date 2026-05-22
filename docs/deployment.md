# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-alluxio
kubectl get svc -n nexoryx-alluxio
kubectl get ingress -n nexoryx-alluxio
