🔹 Networking Fundamentals
IP Address – A unique identifier for a device on a network.

Subnetting – Dividing an IP network into smaller sub-networks.

CIDR (Classless Inter-Domain Routing) – IP address allocation method to improve routing efficiency.

NAT (Network Address Translation) – Translates private IP addresses to public IPs.

DNS (Domain Name System) – Resolves human-readable names to IP addresses.

Load Balancer – Distributes traffic across multiple servers to ensure availability and scalability.

L4/L7 – Refers to OSI layers 4 (Transport) and 7 (Application) for load balancing and policy enforcement.

🔹 Application Networking
Service Mesh – A dedicated infrastructure layer (e.g., Istio, Linkerd) for managing service-to-service communication.

Ingress Controller – Manages external access to services in Kubernetes.

API Gateway – Manages, authenticates, and routes API traffic (e.g., Kong, Apigee, AWS API Gateway).

Reverse Proxy – Forwards requests from clients to backend servers (e.g., NGINX, Envoy).

East-West Traffic – Internal service-to-service communication.

North-South Traffic – External client-to-service communication.

TLS Termination – Decryption of incoming TLS traffic at a proxy/load balancer.

🔹 Security & Policies
Zero Trust – A security model that assumes no implicit trust, verifying every access attempt.

mTLS (Mutual TLS) – Both client and server authenticate each other using TLS certificates.

WAF (Web Application Firewall) – Protects web applications from common threats like SQL injection.

RBAC (Role-Based Access Control) – Limits access based on user roles.

Network Policies – Define how groups of pods/services are allowed to communicate.

🔹 Cloud & Hybrid Networking
VPC (Virtual Private Cloud) – Isolated network environment in public cloud providers.

Transit Gateway – Central hub for connecting multiple VPCs and on-prem networks (e.g., AWS Transit Gateway).

Service Discovery – Dynamically locates services in a distributed system.

Cloud Load Balancer – Managed load balancing service provided by cloud vendors (e.g., AWS ALB, Azure Load Balancer).

Peering – Direct network connection between two cloud networks or VPCs.

🔹 Kubernetes & Microservices
Kube-Proxy – Maintains network rules for pod communication in Kubernetes.

ClusterIP / NodePort / LoadBalancer – Kubernetes service types for exposing applications.

Network Overlay – Abstracts network connectivity between containers across hosts.

CNI (Container Network Interface) – Plugins that configure network interfaces in containers (e.g., Calico, Cilium).

🔹 Observability & Monitoring
Telemetry – Collection of metrics, logs, and traces.

Distributed Tracing – Tracks a request across services to diagnose performance issues.

Latency / Throughput / Errors / Saturation (L.T.E.S.) – Key metrics in application performance monitoring.

Prometheus / Grafana – Common tools for metrics collection and visualization.

OpenTelemetry – Open standard for observability instrumentation.

