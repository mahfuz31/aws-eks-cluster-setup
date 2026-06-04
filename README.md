# AWS EKS Infrastructure Automation & Lifecycle Blueprint

**Date:** June 4, 2026  
**Target Environment:** Local Windows Machine (MobaXterm / POSIX Emulation)  
**Target AWS Infrastructure:** Amazon EKS (Elastic Kubernetes Service) Cluster  
**Deployment Region:** Mumbai, India (`ap-south-1`) — Optimized for Dhaka network proximity.

---

## 1. Prerequisites & Host Configuration
Before initializing cluster provisioning, ensure that your local CLI terminal environment is authenticated with administrative AWS access privileges.

```bash
# Verify AWS CLI installation and version
aws --version

# Configure regional settings and access keys
aws configure