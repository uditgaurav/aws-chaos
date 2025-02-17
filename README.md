# AWS Chaos Experiments

This repository contains various AWS HCE experiments. Below is a list of available experiments and their minimum permission requirements.

| Experiment Name | Permission Requirement |
|-----------------|------------------------|
| ALB AZ Down | [Click Here](alb-az-down/policy.json) |
| CLB AZ Down | [Click Here](clb-az-down/policy.json) |
| DynamoDB Replication Pause | [Click Here](dynamodb-replication-pause/policy.json) |
| EBS Loss by ID | [Click Here](ebs-loss-by-id/policy.json) |
| EBS Loss by Tag | [Click Here](ebs-loss-by-tag/policy.json) |
| EC2 CPU Hog | [Click Here](ec2-cpu-hog/policy.json) |
| EC2 DNS Chaos | [Click Here](ec2-dns-chaos/policy.json) |
| EC2 HTTP Latency | [Click Here](ec2-http-latency/policy.json) |
| EC2 HTTP Modify Body | [Click Here](ec2-http-modify-body/policy.json) |
| EC2 HTTP Modify Header | [Click Here](ec2-http-modify-header/policy.json) |
| EC2 HTTP Reset Peer | [Click Here](ec2-http-reset-peer/policy.json) |
| EC2 HTTP Status Code | [Click Here](ec2-http-status-code/policy.json) |
| EC2 IO Stress | [Click Here](ec2-io-stress/policy.json) |
| EC2 Memory Hog | [Click Here](ec2-memory-hog/policy.json) |
| EC2 Network Latency | [Click Here](ec2-network-latency/policy.json) |
| EC2 Network Loss | [Click Here](ec2-network-loss/policy.json) |
| EC2 Process Kill | [Click Here](ec2-process-kill/policy.json) |
| EC2 Stop by ID | [Click Here](ec2-stop-by-id/policy.json) |
| EC2 Stop by Tag | [Click Here](ec2-stop-by-tag/policy.json) |
| ECS Agent Stop | [Click Here](ecs-agent-stop/policy.json) |
| ECS Container CPU Hog | [Click Here](ecs-container-cpu-hog/policy.json) |
| ECS Container HTTP Latency | [Click Here](ecs-container-http-latency/policy.json) |
| ECS Container HTTP Modify Header | [Click Here](ecs-container-http-modify-header/policy.json) |
| ECS Container HTTP Reset Peer | [Click Here](ecs-container-http-reset-peer/policy.json) |
| ECS Container HTTP Status Code | [Click Here](ecs-container-http-status-code/policy.json) |
| ECS Container IO Stress | [Click Here](ecs-container-io-stress/policy.json) |
| ECS Container Memory Hog | [Click Here](ecs-container-memory-hog/policy.json) |
| ECS Container Network Latency | [Click Here](ecs-container-network-latency/policy.json) |
| ECS Container Network Loss | [Click Here](ecs-container-network-loss/policy.json) |
| ECS Container Process Kill | [Click Here](ecs-container-process-kill/policy.json) |
| ECS Service Stop | [Click Here](ecs-service-stop/policy.json) |
| EKS Container CPU Hog | [Click Here](eks-container-cpu-hog/policy.json) |
| EKS Container HTTP Latency | [Click Here](eks-container-http-latency/policy.json) |
| EKS Container HTTP Modify Header | [Click Here](eks-container-http-modify-header/policy.json) |
| EKS Container HTTP Reset Peer | [Click Here](eks-container-http-reset-peer/policy.json) |
| EKS Container HTTP Status Code | [Click Here](eks-container-http-status-code/policy.json) |
| EKS Container IO Stress | [Click Here](eks-container-io-stress/policy.json) |
| EKS Container Memory Hog | [Click Here](eks-container-memory-hog/policy.json) |
| EKS Container Network Latency | [Click Here](eks-container-network-latency/policy.json) |
| EKS Container Network Loss | [Click Here](eks-container-network-loss/policy.json) |
| EKS Container Process Kill | [Click Here](eks-container-process-kill/policy.json) |
| RDS Failover | [Click Here](rds-failover/policy.json) |
| RDS Reboot | [Click Here](rds-reboot/policy.json) |

**Note:** Each experiment directory contains a `policy.json` file that outlines the minimum AWS IAM permissions required to execute the experiment. Ensure that you review and apply these policies carefully to maintain the security and integrity of your AWS environment.
