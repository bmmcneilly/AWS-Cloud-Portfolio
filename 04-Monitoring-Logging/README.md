# 04 — AWS Monitoring & Logging

## Overview
This project implements observability across AWS using CloudWatch, CloudTrail, Config, and centralized log storage.

## Architecture Summary
- CloudWatch metrics, dashboards, and alarms
- CloudTrail logging
- AWS Config rules
- Centralized S3 log buckets
- SNS or EventBridge alerting

## Infrastructure as Code
This project includes its own Terraform configuration, located in:

./iac/terraform/

Each project in this portfolio is self-contained and deployable independently.

## What This Project Demonstrates
- End-to-end observability
- Automated compliance monitoring
- Alerting and event-driven responses
- Terraform-based monitoring pipelines

## Diagrams
See `/diagrams/architecture.png` for the monitoring flow.

## Notes
See `/notes/design-decisions.md` for alerting strategy and thresholds.
