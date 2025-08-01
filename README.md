# Project 4: Container Security Pipeline with Trivy and Checkov

## Overview

This project models enterprise DevSecOps pipelines by integrating automated vulnerability scanning of container images and infrastructure code to ensure compliance before deployment.

## Business Problem Solved

Undetected vulnerabilities in code and containers can cause data breaches and downtime. Enterprises require early detection and enforcement in CI pipelines.

## What You Will Build

- GitHub Actions workflows integrating Trivy for Docker image scans.
- Checkov scanning for Terraform infrastructure code.
- Automated pipeline failures on high-risk vulnerabilities.
- Software Bill of Materials (SBOM) generation for compliance.

## Enterprise Impact

- Significantly reduces production security incidents.
- Provides traceable security evidence for audits.
- Enforces a "shift-left" security culture.

## Step-by-Step

1. Incorporate Trivy scanning in Docker build workflow.
2. Add Checkov scan stage before Terraform apply.
3. Configure pipeline to fail on critical vulnerabilities.
4. Generate and store SBOM artifacts.
5. Monitor and remediate security findings.

## Prerequisites

- GitHub repository with Docker and Terraform code
- GitHub Actions enabled

## References

- [Trivy Vulnerability Scanner](https://aquasecurity.github.io/trivy/)
- [Checkov Infrastructure Code Scanner](https://www.checkov.io/)
