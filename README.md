# AWS Cloud Practitioner Labs

Self-directed AWS learning repository. Each file documents a concept or lab from the AWS Cloud Practitioner path — notes written for understanding, labs built for hands-on practice.

**Focus:** Learn the service → run the lab → document what happened → note what to watch out for.

---

## Status

| Type | File | Topic | Status |
|------|------|--------|--------|
| 📝 Note | [cloud-architecture.md](notes/cloud-architecture.md) | High availability, scalability, elasticity | ✅ Written |
| 📝 Note | [shared-responsibility-model.md](notes/shared-responsibility-model.md) | AWS vs customer security responsibilities | ✅ Written |
| 📝 Note | [aws-global-infrastructure.md](notes/aws-global-infrastructure.md) | Regions, AZs, edge locations | ✅ Written |
| 🔬 Lab | [iam-users-groups-policies.md](labs/iam-users-groups-policies.md) | IAM users, groups, least-privilege policies | 🔄 In Progress |
| 🔬 Lab | [ec2-basics.md](labs/ec2-basics.md) | Launch EC2, configure security groups, SSH | 🔄 In Progress |
| 🔬 Lab | [s3-static-website.md](labs/s3-static-website.md) | S3 bucket, static hosting, bucket policies | 📋 Planned |

---

## Current Learning Path

- [x] AWS global infrastructure — Regions, Availability Zones, edge locations
- [x] Shared Responsibility Model — what AWS owns vs what you own
- [x] Cloud architecture principles — HA, scalability, elasticity, fault tolerance
- [ ] IAM — users, groups, roles, policies, least privilege
- [ ] EC2 — launch instance, key pairs, security groups, SSH access
- [ ] S3 — buckets, static hosting, bucket policies, access control
- [ ] VPC — subnets, route tables, internet gateway
- [ ] CloudWatch — metrics, alarms, logs

---

## Notes

Conceptual documentation written in plain language to reinforce understanding before touching the console.

- **[Cloud Architecture](notes/cloud-architecture.md)** — High availability, scalability, elasticity, fault tolerance, and the AWS Well-Architected Framework pillars
- **[Shared Responsibility Model](notes/shared-responsibility-model.md)** — What AWS secures (infrastructure) vs what the customer secures (configuration, data, access)
- **[AWS Global Infrastructure](notes/aws-global-infrastructure.md)** — Regions, AZs, edge locations, and why region selection affects latency, cost, and compliance

---

## Labs

Hands-on practice in the AWS console. Each lab documents the goal, services used, steps taken, security considerations, and what was learned.

- **[IAM Users, Groups, and Policies](labs/iam-users-groups-policies.md)** — Practice creating IAM users, groups, and attaching least-privilege policies. Emphasis on not using root and not creating long-term access keys.
- **[EC2 Basics](labs/ec2-basics.md)** — Launch a free-tier EC2 instance, configure a security group, and connect via SSH. Practice restricting SSH to a single IP rather than 0.0.0.0/0.
- **[S3 Static Website](labs/s3-static-website.md)** — Create an S3 bucket, upload an index.html, enable static website hosting, and configure permissions safely without exposing private data.

---

## Security Approach

Every lab in this repository follows a security-first mindset:

- Use **least privilege** — never attach AdministratorAccess for lab purposes
- **No long-term access keys** unless the lab specifically requires them (then rotate/delete after)
- **No sensitive data** in buckets, scripts, or commit history
- **Restrict SSH** to your own IP — never open port 22 to 0.0.0.0/0
- **Stop or terminate** all resources after each lab to avoid unexpected costs

---

## Resources

- [resources/links.md](resources/links.md) — AWS documentation, study workflow, and reference links