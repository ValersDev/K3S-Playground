# K3S-Playground

Documentation:

1. Crear carpeta para introducir los archivos necesarios
2. Dentro de la carpeta, crear un archivo llamado nginx.yaml
3. Copiar el codigo deployment de la documentación de kubernetes ofical y pegarlo en el archivo nginx.yaml para empezar a configurar el deployment.
4. Configurar el archivo nginx.yaml en base a las necesidades que tenga tu deployment.
5. Crear en la misma carpeta un archivo llamado node_port.yaml
6. Copiar el codigo service de la documentación de kubernetes ofical y pegarlo en el archivo node_port.yaml para empezar a configurar el service.
7. Aplicamos los cambios con los siguientes comandos a todos los archivos que hayamos creado con el siguiente comando:

kubectl apply -f "nombre del archivo".yaml

8. Ejecutamos los comandos kubectl get rs y kubectl get pods para comprobar que se han creado correctamente.
9. Ejecutamos kubectl get svc para comprobar que el servicio se ha creado correctamente.
10. Eliminamos un pod con el comando kubectl delete pod "nombre del pod", para así comprobar que se crea un nuevo pod con el mismo deployment.
11. Y ejecutamos otra vez kubectl get pods para comprobar que se ha creado un nuevo pod.
12.
