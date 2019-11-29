                          Deploy microservices application on bare-metal kubernetes cluster.

This project is about demonstrating deployment of microservices application on kubernetes cluster.
It includes:
1  Install cluster using kubeadm tool.
2  Configure kubectl to remotely manage the cluster and setup helm to install packages on cluster.
3  Configure NFS server and kubenetes worker nodes to dynamically provision persistant volumes on kubernetes cluster.
4  Configure NFS client provisioner to dynamically create PVs from default storage class.
5  Configure MetalLB load-balancer for bare metal Kubernetes cluster.
6  Configure kubernetes dashboard to manage cluster using GUI.
7  Configure NGINX Ingress Controller and ISTIO service mesh for Kubernetes cluster.
8  Configure cluster monitoring using prometheus and grafana.
9  Exposing services to be accessed outside the cluster using nginx ingress controller.
10 Exposing cluster services to be accessed outside the cluster using ISTIO service mesh
11 Example use cases for ISTIO

