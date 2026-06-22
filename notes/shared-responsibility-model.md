# Shared Responsibility Model

The AWS shared responsibility model explains which security tasks belong to AWS and which tasks belong to the customer.

## AWS Is Responsible For Security **of** the Cloud

AWS manages the infrastructure that runs AWS services.

Examples:

- Physical data centers
- Hardware
- Networking infrastructure
- Managed service infrastructure
- Availability Zones and Regions

## Customer Is Responsible For Security **in** the Cloud

The customer manages how AWS services are configured and used.

Examples:

- IAM users, roles, and permissions
- Data protection and encryption choices
- Security groups and network access
- Operating system patching for EC2
- Application security
- Logging and monitoring configuration

## Why This Matters

Cloud security is not automatic. AWS gives the tools, but the customer must configure them correctly.

Bad examples:

- Public S3 bucket with sensitive data
- Over-permissive IAM policy
- EC2 instance open to the internet unnecessarily
- No logging or monitoring enabled

## What I Learned

The shared responsibility model is one of the most important cloud security concepts. It defines who owns each part of the security work.
