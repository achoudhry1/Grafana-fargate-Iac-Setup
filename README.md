# Grafana-fargate-Iac-Setup
Description:
  This template deploys Grafana to an AWS Fargate Cluster on user-defined VPC and Subnets. Container definition is pulled from the public Docker image for Grafana (https://hub.docker.com/r/grafana/grafana/). An ECS Service ensures Grafana continues to run on the created Cluster. Logging is captured within CloudWatch.
