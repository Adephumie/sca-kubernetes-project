# SCA-kubernetes-project

The aim of the project is to build a simple multi-tier web app using Kubernetes and Docker. This project is not production-ready.

## Pre-requisites
1. A kubernetes cluster- You can install minikube.
2. kubectl to communicate with the cluster.
3. To deploy this application, we will need a cluster with at least two nodes that are not acting as control plane hosts.
    And to achieve this, use this command:
    ```
    minikube start --nodes 3 -p multinode-demo
    ```
4. 

