# Desafío SRE/DevOps Engineer Dafiti


# **Requisitos previos**

Para ejecutar correctament la solucion es necesario los soguientes pasos:
1. en caso de ejecutar la solucion con minikube ejecutar el siguiente comando eval $(minikube docker-env) (esta solucioin fue desplegada haciendo uso de la extensiond e kubernetes que tiene ya el docker desktop (con esta alternativa, este paso no es necesario)
2. ejecutar un docker build a ambos Dockerfile dentro de las carpetas api y listener utilizando los tags api y listener respectivamente


**Ejecucion de la solucion**<p>
Con los 2 pasos anteriores listos, procedemos a ejecutar los archivos (kubectl apply -f <file>) en el siguiente orden:
1. db-claim0-persistentvolumeclaim.yaml
2. db-deployment.yaml
3. rabbitmq-deployment.yaml
4. listener-deployment.taml
5. api-deployment.yaml
6. api-service.yaml

Una vez ejecutados los archivos en el orden indicado se puede testear la aplicacion con `curl localhost:30002`
