# AWS Global Infrastructure

AWS global infrastructure is the worldwide system of Regions, Availability Zones, edge locations, and data centers that AWS uses to deliver cloud services.

## Regions

A Region is a geographic area where AWS has multiple Availability Zones.

Examples:

- `us-east-1`
- `us-east-2`
- `us-west-2`

## Availability Zones

An Availability Zone is one or more isolated data centers inside a Region.

Using multiple Availability Zones helps with high availability and fault tolerance.

## Edge Locations

Edge locations are used by services like Amazon CloudFront to deliver content closer to users.

## Why Region Choice Matters

Region selection affects:

- Latency
- Cost
- Compliance
- Service availability
- Disaster recovery design

## What I Learned

AWS infrastructure is designed so applications can be deployed close to users and across isolated failure zones.
