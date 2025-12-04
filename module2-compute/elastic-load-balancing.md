# Elastic Load Balancing (ELB)

Distributes traffic across multiple EC2 instances.

### Why ELB?
- Prevents single points of failure
- Improves fault tolerance
- Provides health checks
- Integrates with Auto Scaling

### Types of Load Balancers:
1. **Application Load Balancer (ALB)**
   - HTTP/HTTPS
   - Path-based routing
   - Ideal for web apps & microservices

2. **Network Load Balancer (NLB)**
   - TCP/UDP
   - Extreme performance
   - Millions of requests/second

3. **Gateway Load Balancer (GWLB)**
   - For firewalls, intrusion systems

### Features:
- SSL/TLS termination
- Sticky sessions (session affinity)
- Cross-zone load balancing
