# taller-docker-ejercicio8

# Crear el namespace
kubectl create namespace poc-ejercicio8

# Aplicar el deployment
kubectl apply -f deployment.yaml -n poc-ejercicio8

# Verificar que levantaron correctamente
kubectl get all -n poc-ejercicio8

# Aplicar el servicio
kubectl apply -f service.yaml -n poc-ejercicio8

# Visualizar los servicio
kubectl get services -n poc-ejercicio8

