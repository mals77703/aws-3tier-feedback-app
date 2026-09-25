# AWS 3-Tier Architecture — Feedback Application

Deployed a scalable, secure 3-tier web app on AWS (VPC, EC2, ALB, RDS) 
as a portfolio project.

**Based on starter code from:** https://github.com/Vennilavanguvi/Three-Tier-Architecture

## Stack
- VPC, 6 subnets across 2 AZs, IGW, NAT Gateway
- EC2 (Ubuntu) — Nginx web tier, Flask app tier
- Application Load Balancer (public + internal)
- Amazon RDS MySQL
- Security groups enforcing tier-to-tier access only
- Session Manager for access (no SSH)

## Documentation
Full write-up with screenshots
