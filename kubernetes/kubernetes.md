# 🚀 Kubernetes Learning Guide

A structured guide to learn Kubernetes with both **theoretical foundations** and **practical hands-on labs**. Ideal for developers, DevOps engineers, and cloud practitioners.

---

## 🧠 Theory: Kubernetes Fundamentals

### 1. Introduction to Kubernetes
- What is Kubernetes?
- Why use Kubernetes?
- Kubernetes architecture overview (Master/Control Plane & Worker Nodes)

### 2. Core Concepts
- **Pods**: The smallest deployable unit
- **ReplicaSets**: Ensures desired number of pod replicas
- **Deployments**: Declarative updates for pods and ReplicaSets
- **Services**: Networking abstraction for pods
- **Namespaces**: Logical isolation within the cluster
- **ConfigMaps & Secrets**: External configuration management
- **Volumes & PersistentVolumes**: Storage management
- **Jobs & CronJobs**: One-time and scheduled workloads

### 3. Control Plane Components
- `kube-apiserver`: The front-end
- `etcd`: Cluster state store
- `kube-scheduler`: Assigns pods to nodes
- `kube-controller-manager`: Runs controllers
- `cloud-controller-manager`: Integrates cloud provider APIs

### 4. Node Components
- `kubelet`: Ensures containers are running
- `kube-proxy`: Maintains network rules
- `Container Runtime`: e.g., containerd, CRI-O

### 5. Networking in Kubernetes
- Pod-to-Pod communication
- ClusterIP, NodePort, LoadBalancer
- Ingress controllers and rules

### 6. Helm
- What is Helm?
- Installing and using Helm Charts
- Creating your own charts