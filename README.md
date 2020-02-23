# kubernetes-introduction
Notes about Kubernetes

### KodeKloud - Kubernetes Concepts Explained in 9 minutes!
  https://youtu.be/QJ4fODH6DXI

### KodeKloud - Kubernetes Architecture Simplified | K8s Explained in 10 Minutes
  https://youtu.be/8C_SCDbUJTg

### - Introduction to Microservices, Docker, and Kubernetes
  https://youtu.be/1xo-0gCVhTU

### CNCF [Cloud Native Computing Foundation] - Effective RBAC - Jordan Liggitt, Red Hat
  https://youtu.be/Nw1ymxcLIDI


## Kubernetes Setting up Role-Based Access Control(RBAC)

Introduction
You define your RBAC permissions by creating objects from the rbac.authorization.k8s.io API group in your cluster. You can create the objects using the kubectl command-line interface, or programmatically.

You'll need to create two kinds of objects:

A Role or ClusterRole object that defines what resource types and operations are allowed for a set of users.
A RoleBinding or ClusterRoleBinding that associates the Role (or ClusterRole) with one or more specific users.
RBAC permissions are purely additive there are no "deny" rules. When structuring your RBAC permissions, you should think in terms of "granting" users access to cluster resources.

![alt text](https://8gwifi.org/docs/img/rolebased.png)

