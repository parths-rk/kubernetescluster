# Kubernetes Deployment with Monitoring (Minikube)

## Goal
Deploy an application on Kubernetes and implement observability using Prometheus and Grafana on a local Minikube cluster.

## Stack
- Minikube
- Kubernetes
- Nginx
- Prometheus
- kube-state-metrics
- Grafana
- Docker

## What I Implemented
- Local Kubernetes cluster using Minikube
- Nginx deployment with Service and ConfigMap
- Kubernetes manifests for application workloads
- Prometheus deployment for metrics collection
- kube-state-metrics integration
- Grafana setup for visualization
- Dashboard access and metrics validation

## Architecture
Client → Kubernetes (Nginx)  
Prometheus scrapes cluster + app metrics  
Grafana visualizes metrics dashboards  

## Workflow
1. Start Minikube cluster
2. Apply Kubernetes manifests
3. Deploy Prometheus and kube-state-metrics
4. Deploy Grafana
5. Access dashboards and verify metrics

## Verification
- Pods running successfully
- Services exposed
- Prometheus targets in UP state
- Grafana dashboards displaying live metrics

## Structure
- k8s/ → Kubernetes application manifests
- monitoring/ → Prometheus and metrics setup
- screenshots/ → Cluster and monitoring proof

## Screenshots
See screenshots folder for:
- kubectl outputs
- Prometheus targets
- Grafana dashboards
- Service access
