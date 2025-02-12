# k8s_task

ask 1: Create a Deployment and Expose it with a Service
Objective: Deploy a simple NGINX application and expose it within the cluster.

Instructions:
Create a Kubernetes Deployment for an NGINX application (nginx:1.21).
The deployment should have:
2 replicas
Container listening on port 80
Expose the deployment using a ClusterIP service named nginx-service.
Task 2: Expose the Service to External Traffic using Ingress
Objective: Configure an Ingress to expose the service externally.

Instructions:
Deploy an Ingress resource for the nginx-service.
Route traffic from the domain nginx.local to the service.
Task 3: Update the Deployment and Scale it Dynamically
Objective: Test scaling and rolling updates.

Instructions:
Scale the nginx-deployment to 4 replicas.
Update the image to nginx:1.23.
Task 4: Configure Resource Limits for the Deployment
Objective: Improve resource management by setting resource limits.

Instructions:
Set CPU request to 200m and limit to 500m.
Set memory request to 128Mi and limit to 256Mi.
Task 5: Add Health Probes to the Deployment
Objective: Improve application reliability by adding liveness and readiness probes.

Instructions:
Add a liveness probe checking / every 10 seconds.
Add a readiness probe checking / every 5 seconds.
These tasks will cover key aspects of Kubernetes deployments, services, scaling, resource management, and application reliability.
