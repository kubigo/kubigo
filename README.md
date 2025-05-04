# Kubigo
Official issue repository for Kubigo project

Website: [https://kubigo.cloud/](https://kubigo.cloud/)

This project is a web-based dashboard for managing Kubernetes clusters. It provides a user-friendly interface for viewing and managing Kubernetes resources across multiple clusters.
Additionally, the dashboard now includes deployment history and rollback features, allowing users to track changes to their deployments and easily revert to previous versions if needed.

## Key Features 🌟

- **Multi-Cluster Support:** Add, select, and manage multiple Kubernetes clusters with support for ServiceAccountToken, ClientCertificate, Azure, and KubeConfig authentication.
- **Namespace Isolation:** All resource actions are namespace-aware and scoped.
- **Resource CRUD:** Create, view, edit (YAML and forms), and delete for Deployments, StatefulSets, DaemonSets, Pods, Jobs, CronJobs, Services, Ingresses, ConfigMaps, Secrets, PersistentVolumes, PersistentVolumeClaims, Nodes, Namespaces, and Custom Resources (CRDs).
- **Direct Single Resource Fetch:** Efficient API endpoints and UI logic to fetch individual resource details (reduces frontend load).
- **YAML Editing & Viewing:** Edit and apply YAML for resources, with syntax highlighting and validation.
- **Resource Rollout/Rollback:** Dedicated endpoints and UI for deployment rollout history and safe rollback operations.
- **Resource Metrics:** Pod and Node metrics (CPU, memory, etc.) with backend support for metrics endpoints.
- **KEDA Autoscaling:** View and manage KEDA ScaledObjects, including pause/resume and YAML editing.
- **Helm Chart Management:** View Helm releases and charts (if enabled).

### Resource Management
- View and manage Kubernetes resources (pods, deployments, services, etc.)
- Filter resources by namespace and cluster
- View detailed information about resources
- YAML viewer for all resources
- Consistent UI with card-based layouts and blue headers

### Pod Management
- View pod details including containers, status, and events
- View pod logs with real-time updates
- View container resource requests and limits
- Pod monitoring with crash detection and notifications

### Deployment Management
- View deployment details and status
- Scale deployments up or down
- Update deployment images
- Restart deployments
- Clone deployments to new namespaces
- View deployment rollout history
- Rollback deployments to previous revisions

### Namespace Management
- View and create namespaces
- Filter resources by namespace
- View namespace details and YAML

### KEDA Integration
- View and manage ScaledObjects
- Pause/resume autoscaling
- Fix replica counts
- View scaling triggers and metadata

### Ingress Management
- View and manage Ingress resources
- View Ingress details, hosts, and endpoints
- Clickable host links that open in new tabs
- Delete Ingress resources

### Secret Management
- View and manage Kubernetes secrets
- Create, update, and delete secrets
- Base64 encoding/decoding support

### ConfigMap Management
- View and manage ConfigMaps
- Create, update, and delete ConfigMaps

### Node Management
- View node details and status
- View node resource usage
- View pods running on nodes

### Helm Integration
- View and manage Helm releases
- Install, upgrade, and delete Helm charts

### User Management
- Role-based access control
- User authentication with JWT
- Permission management

### Monitoring
- Real-time pod monitoring
- Crash detection and notifications
- Resource usage visualization

### Authentication & Authorization
- JWT-based authentication
- Role-based access control
- Permission-based API access


