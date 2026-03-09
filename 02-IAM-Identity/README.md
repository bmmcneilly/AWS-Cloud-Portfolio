# 02 — AWS IAM & Identity

## Overview
This project builds a secure identity foundation using AWS IAM best practices. It focuses on least privilege, role-based access, and identity federation patterns.

## Architecture Summary
- IAM roles and policies
- IAM groups and permission boundaries
- IAM Identity Center (optional)
- Cross-account access patterns
- MFA enforcement

## Infrastructure as Code
This project includes its own Terraform configuration, located in:

./iac/terraform/

Each project in this portfolio is isolated and deployable independently.

## What This Project Demonstrates
- Enterprise-grade IAM design
- Role-based access control (RBAC)
- Secure policy creation and validation
- Identity federation patterns

## Diagrams
See `/diagrams/architecture.png` for IAM trust relationships.

## Notes
See `/notes/troubleshooting.md` for common IAM issues and fixes.
