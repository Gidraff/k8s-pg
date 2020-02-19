#### Kubernetes Resource Object Proof of concepts (POC).

##### Prerequisite:

To follow up, make sure you have the following:

- [Minikube]("https://github.com/kubernetes/minikube/tree/master/docs) or a running Kubernetes on cloud
- [Kubectl](): Interacts with kubernetes API server.



##### Getting started:

To fire up minikube run: `minikube start`:

**Note**: To enable `addons`, for example Ingress, run
```
minikube addons enable ingress
```
This will spin up a Ingress-Contoller Pod in you cluster. 


Now we can start apply  desired state we've defined in the yaml files.
We accomplish this by using ```kubectl command [resource] [--options]```