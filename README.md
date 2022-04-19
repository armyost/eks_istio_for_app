# Environments
1. AWS EKS Cluster : "Step 3_install_ingress_controller" is only for EKS 
2. EKS 1.22 (Docker Runtime)
3. Helm version 3

# Components
1. ALB Ingress Controller (Installed by Helm) for Kubernetes Dashboard, Istio GateWay
2. Sample APP (Meshed by Istio)
3. Istio (Installed by Helm)
4. Monitors Components : Prometheus, Grafana, Zipkin, Jaeger, Kiali (Installed by Helm addon)

# Tutorial
Each folder includes "command.txt" provides whole command lines in each steps. 
Download this project first.
Enter each directories and run as "command.txt".
