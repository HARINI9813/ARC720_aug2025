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

From Gemini
===========

Essential Application Networking Terms
An Application Networking Architect needs to understand a wide range of terms to design and manage the network infrastructure that supports applications. These terms can be categorized based on their function within the network stack and application delivery process.

Core Networking Concepts
TCP/IP (Transmission Control Protocol/Internet Protocol): The fundamental suite of protocols that govern how data is sent and received over a network. TCP ensures reliable, ordered data delivery, while IP handles the addressing and routing of data packets.

Packet: A formatted unit of data carried by a packet-switched network. A packet consists of a header and a payload.

Latency: The delay before a transfer of data begins following an instruction for its transfer. It's a key metric for application performance.

Bandwidth: The maximum amount of data that can be transmitted over a communication channel in a given amount of time. It's often measured in bits per second (bps).

Routing: The process of selecting a path for traffic in a network, or between or across multiple networks. Routers are the devices that perform this function.

Switching: The process of filtering, forwarding, and flooding frames based on the destination address of the frame. Switches are the devices that connect devices within a local network.

Application Delivery & Security
Load Balancer: A device or software that distributes network traffic among multiple servers to ensure no single server is overworked. This improves application availability and responsiveness.

DNS (Domain Name System): A hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network. It translates human-readable domain names (like google.com) into IP addresses.

Firewall: A network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules.

CDN (Content Delivery Network): A geographically distributed network of proxy servers and their data centers. The goal is to provide high availability and performance by distributing the service spatially relative to end-users.

Proxy Server: A server that acts as an intermediary for requests from clients seeking resources from other servers. It can be used for security, performance, and anonymity.

API Gateway: A server that acts as a single entry point for a set of microservices. It handles requests, routes them to the appropriate service, and can provide additional functionality like security, rate limiting, and analytics.

Cloud & Virtualization
Virtual Private Cloud (VPC): A private, isolated section of a public cloud where you can launch resources in a virtual network that you define.

Software-Defined Networking (SDN): An approach to networking that uses software-based controllers or APIs to manage network devices, rather than relying on manual configuration.

Network Function Virtualization (NFV): A concept that virtualizes entire classes of network node functions into building blocks that can be connected or chained together to create communication services.

Microservices: An architectural style that structures an application as a collection of loosely coupled services.

Performance & Monitoring
Application Performance Monitoring (APM): The process of monitoring and managing the performance and availability of software applications.

Observability: The ability to understand the internal state of a system from its external outputs. It's often achieved through the collection and analysis of logs, metrics, and traces.

SLA (Service Level Agreement): A contract between a service provider and a customer that defines the level of service expected from the provider.

High Availability (HA): A characteristic of a system that aims to ensure a pre-agreed level of operational performance for a higher than normal period.

