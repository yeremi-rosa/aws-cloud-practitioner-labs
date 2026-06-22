# Cloud Architecture

Cloud architecture is the way cloud systems are designed so they can be reliable, scalable, secure, and cost-aware.

## Core Ideas

### High Availability

High availability means a system is designed to keep running even when part of the infrastructure has problems.

Common AWS patterns:

- Use multiple Availability Zones
- Put compute behind a load balancer
- Avoid single points of failure
- Monitor health and replace unhealthy resources

### Scalability

Scalability means the system can handle more demand by adding more resources.

Examples:

- Add more EC2 instances
- Increase database capacity
- Use caching
- Use managed services that scale automatically

### Elasticity

Elasticity means resources can grow and shrink based on demand.

This matters because cloud systems should not stay oversized forever. Good cloud design scales up when traffic increases and scales down when traffic drops.

### Fault Tolerance

Fault tolerance means the system can continue operating even when something fails.

Examples:

- Multi-AZ databases
- Replicated storage
- Automatic failover
- Health checks
- Backups and recovery plans

### Disaster Recovery

Disaster recovery is the plan for restoring service after a major failure.

Important terms:

- **RTO:** Recovery Time Objective — how long the system can be down
- **RPO:** Recovery Point Objective — how much data loss is acceptable

## AWS Services Related to Architecture

- Elastic Load Balancing
- Auto Scaling Groups
- EC2
- S3
- RDS Multi-AZ
- Route 53
- CloudWatch
- AWS Backup

## What I Learned

Cloud architecture is not just about launching resources. It is about designing systems that can survive failure, handle change, and stay understandable.
