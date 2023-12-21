# k8s-aepc-back configuration files
- each configurations made in each application.properties permit Pods communicate each other in Kubernetes principles
- each line configuration starting by ***http://k8s-*** indicates the url of Kubernetes **Service** associated to a **Deployment**.
    - ***k8s-*: port*** are the name and port of Kubernetes Service

For more about Kubernetes ***Deployment*** and ***Service*** refer to Kubernetes documentation:
- [Deployment](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
- [Service](https://kubernetes.io/docs/concepts/services-networking/service/)
