# 01 — AWS Account Foundation

## Overview
This project establishes the foundational AWS account structure required for secure, scalable cloud environments. It includes baseline guardrails, identity configuration, logging, and governance controls.

## Architecture Summary
- AWS Organizations (optional)
- IAM account baseline (admin roles, MFA, least privilege)
- CloudTrail organization trail or account-level trail
- AWS Config rules and conformance packs
- Centralized S3 logging buckets
- Guardrails and SCPs (if applicable)

## Infrastructure as Code
This project contains its own Terraform configuration, located in:

./iac/terraform/

Each project in this portfolio is fully self‑contained and includes its own IaC, state, and deployment workflow.

## What This Project Demonstrates
- Secure-by-default AWS account setup
- Governance and compliance alignment
- Centralized logging and auditing
- Modular Terraform project structure

## Diagrams
See `/diagrams/architecture.png` for the full layout.

## Notes
See `/notes/design-decisions.md` for reasoning behind architectural choices.
