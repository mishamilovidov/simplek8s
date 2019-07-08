
# simplek8s 👶☸️

A project for explorign k8s. This accompanies Stephen Grider's Udemy course, 
"Docker adnd Kubernetes: The Complete Guide."

## Notes
* Kubernetes Objects
  * Kinds
    * `Pod` - runs one or more closely related containers (ex. db with logger and back-up manager)
    * `Service` - sets up networking in a k8s cluster
      * `ClusterIP`
      * `NodePort` - exposes a container to the outside world (only for dev!!!)
      * `LoadBalancer`
      * `Ingress`