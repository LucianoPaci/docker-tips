# Docker & Kubernetes

[Docker Cheat Sheet](https://gist.github.com/LucianoPaci/34be1566e3487164a642926f78dbcfb8)

## Kubernetes

- [Introduccion](https://www.youtube.com/watch?v=6jeCUFNv0XI&t=952s)

**Es un 'Orquestador'**
Permite definir la manera en la que se van a levantar y comunicar los diferentes Pods (unidad minima, compuesta por 1 o muchos containers de Docker, por ej)

- Las instrucciones se definen en archivos yaml

Para iniciar el deploy

```
kubectl apply -f <k8s folder or file/s>
```

Para cortar la ejecucion de todo

```
$ kubectl delete deployment.apps/<name del deployment>
```

Para borrar todos los pods (si sigue corriendo el deployment, se van a volver a reinstanciar)

```
$ kubectl delete pods  --all
```
