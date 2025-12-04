# Auto Scaling

AWS Auto Scaling automatically adjusts EC2 capacity.

### Key Components:
- **Auto Scaling Group (ASG)** → Group of EC2 instances
- **Launch Template** → Defines instance configuration
- **Scaling Policies:**
  - Target tracking (recommended)
  - Step scaling
  - Simple scaling

### Benefits:
- High availability
- Cost efficiency
- Automatic scaling based on metrics like CPU, requests, etc.
