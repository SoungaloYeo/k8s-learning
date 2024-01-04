# k8s-learning

# ----------------

## Create pod by yml file on namespace (can be specified on the yml file)

kubectl apply -f pod-blue.yml -n production

## Create service by yml file on namespace:

kubectl apply -f service-nodeport-web.yml -n production

## List services on specific namespace:

kubectl -n production get svc

## Describe service on specific namespace:

kubectl -n production describe service service-nodeport-web
