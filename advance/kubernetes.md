# Kubernetes Learning Roadmap

## 1. Introduction
- What is Kubernetes? Why use it?
- Containers vs Virtual Machines
- Kubernetes Architecture
  - Master Node (Control Plane)
  - Worker Nodes
- Key Components
  - API Server
  - etcd
  - Controller Manager
  - Scheduler
  - Kubelet
  - Kube-proxy

## 2. Setup & Basics
- Installing Kubernetes
  - Minikube / kind (local cluster)
  - kubeadm
  - Managed Kubernetes (EKS, GKE, AKS)
- kubectl CLI basics
- Namespaces
- Pods
- ReplicaSets
- Deployments

## 3. Core Workloads
- Services
  - ClusterIP
  - NodePort
  - LoadBalancer
- ConfigMaps
- Secrets
- Volumes & Persistent Volumes
- Persistent Volume Claims
- Storage Classes

## 4. Scaling & Availability
- Horizontal Pod Autoscaler (HPA)
- Vertical Pod Autoscaler (VPA)
- Cluster Autoscaler
- Rolling Updates & Rollbacks
- DaemonSets
- StatefulSets
- Jobs & CronJobs

## 5. Networking
- Pod-to-Pod Communication
- CNI Plugins (Flannel, Calico, Cilium)
- DNS in Kubernetes
- Ingress & Ingress Controllers (NGINX, Traefik, Istio Gateway)
- Network Policies

## 6. Security
- Role-Based Access Control (RBAC)
- Service Accounts
- Pod Security Policies (PSP) / Pod Security Standards (PSS)
- Network Policies for Isolation
- Secrets Management
- TLS & Certificates
- Image Security (Scanning, Trusted Registries)

## 7. Observability
- Logging in Kubernetes
- Monitoring with Prometheus & Grafana
- Metrics Server
- Liveness & Readiness Probes
- Tracing (Jaeger, OpenTelemetry)
- Debugging with `kubectl logs`, `kubectl exec`, `kubectl describe`

## 8. Configuration Management
- Labels & Annotations
- Taints & Tolerations
- Node Selectors
- Affinity & Anti-Affinity
- Resource Requests & Limits

## 9. Advanced Topics
- Operators & Custom Resource Definitions (CRDs)
- Helm (Package Manager for Kubernetes)
- Kustomize
- Sidecar Pattern
- Init Containers
- Multi-Cluster Kubernetes
- Federation

## 10. Cloud-Native Ecosystem
- Service Mesh (Istio, Linkerd)
- API Gateway with Kubernetes
- Event-Driven Workloads (Knative, KEDA)
- GitOps with ArgoCD / Flux
- CI/CD Integration (Jenkins, GitHub Actions, Tekton)

## 11. High Availability & Scaling
- HA Control Plane
- etcd Backup & Restore
- Multi-AZ / Multi-Region Clusters
- Disaster Recovery Strategies
- Blue-Green & Canary Deployments

## 12. Security & Compliance (Advanced)
- OPA / Gatekeeper (Policy Enforcement)
- Kubernetes Security Benchmarks (CIS)
- Image Signing & Verification (Cosign)
- Vault Integration for Secrets
- Zero Trust in Kubernetes

## 13. Certifications Roadmap
- CKA (Certified Kubernetes Administrator)
- CKAD (Certified Kubernetes Application Developer)
- CKS (Certified Kubernetes Security Specialist)

---
✅ Suggested Path:
- **Beginner:** Intro → Setup → Pods → Deployments → Services → ConfigMaps & Secrets  
- **Intermediate:** Scaling → Storage → Networking → Security → Observability  
- **Advanced:** Operators → Helm → GitOps → Service Mesh → HA & DR → Security & Compliance
