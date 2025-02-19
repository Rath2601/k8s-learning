# Kubernetes Overview

Kubernetes is an open-source container orchestration tool that automates the deployment, scaling, and management of containerized applications across multiple systems.

## Uses:

- **Load Balancing & Service Discovery**  
  Kubernetes exposes services via DNS or IP and load balances traffic for stability.

- **Rollouts & Rollbacks**  
  Adjusting containers to the desired state, creating new ones, and removing old ones at a controlled rate.

- **Self-Heal**  
  Automatically restarts, replaces, and kills containers that fail or don't pass health checks (maintains only healthy pods).

- **Secret Management**  
  Manages secrets and configurations, allowing updates without rebuilding containers or exposing sensitive data.

- **Batch Execution**  
  Kubernetes handles batch and CI workloads, automatically replacing failed containers as needed.

- **Scaling**  
  Scales applications up or down easily via command, UI, or automatically based on CPU usage.

- **IPv4/IPv6 Dual-Stack**  
  Allocation of IPv4 and IPv6 addresses to Pods and Services.

- **Storage Orchestration**  
  Manages persistent storage for stateful applications.

- **Multi-Cloud Deployments**  
  Supports deployment across multiple cloud providers.

- **Declarative Nature**  
  You define the desired state of your system, and Kubernetes automatically ensures the actual state matches it.

- **Namespaces**  
  Kubernetes supports multi-tenancy by organizing resources in namespaces.

- **Resource Management**  
  Automatically adjusts resource allocation (like CPU and memory) based on usage, ensuring optimal performance and efficiency.

- **Health Checks**  
  Kubernetes uses liveness and readiness probes to monitor and maintain the health of containers.

- **Disaster recovery**
  backup and restore the latest state after the recovery
