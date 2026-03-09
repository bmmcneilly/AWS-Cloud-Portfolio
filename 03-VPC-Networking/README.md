# 03 — AWS VPC Networking

## Overview
This project builds a production-ready VPC using AWS networking best practices. It includes subnets, routing, NAT gateways, security groups, and optional private connectivity.

## Architecture Summary
- Multi-AZ VPC
- Public and private subnets
- Route tables, IGW, and NAT gateways
- Security groups and NACLs
- VPC endpoints (optional)
- DNS and DHCP options

## Infrastructure as Code
This project contains its own Terraform configuration, located in:

./iac/terraform/

Each project is modular and can be deployed independently.

## What This Project Demonstrates
- Scalable, multi-AZ VPC design
- Secure ingress/egress patterns
- Private connectivity using endpoints
- Modular Terraform networking patterns

## Diagrams
See `/diagrams/architecture.png` for the VPC layout.

## Notes
See `/notes/commands-used.md` for AWS CLI networking commands.
