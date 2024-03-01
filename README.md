## Kubenetes demo APP
This is 3 tier APP
- frontend: React
- Backend: Node
- Database: Mongodb
Deployment in Kubernetes (AKS)

Task breakdown:
1. Deploy a sample microservices application (e.g., a simple web service and database) into the
Kubernetes cluster. Use Kubernetes --> Implemented
2. Use Kubernetes Deployment resources, manage container replicas, and ensure
high availability and scalability. Configure Persistent Volume(PV) and Persistent Volume
Claims(PVC). --> Implemented
3. Implement Horizontal Pod Autoscaling(HPA) based on CPU or custom metrics. -->  Implemented
4. Use Helm Chart for Deployment of application. --> Implemented (Need to fix Error: INSTALLATION FAILED)
5. Create CI/CD pipelines for deploying applications to the Kubernetes cluster. --> Pending
6. Setup one of the (Janus, emqx) in docker and in Kubernetes --> Pending
7. Setup Kafka(latest version) with Kubernetes Helm. --> Pending

Demo URL: http://a4357803b8e7b47f38d7f5cefa363bfa-654308180.us-east-1.elb.amazonaws.com:3000/
(Ingress is breaking)
