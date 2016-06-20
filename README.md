# ecs-primer

Inputs:

- VPC or subnet to create instances
- Name of the project / application used as tag / name in all resources created
- ECS key
- ECS registry / Docker image URL to run

What it does:

- Create auto scaling launch config
- Create AMI role for ECS nodes
- Give AMI role access to ECS registry
- Create auto scaling group for ECS nodes
- Create ECS service
- Create ECS cluster
- Add nodes from auto scaling group into the cluste
- Configure service to run ECS cluster

# Other options

- use the AWS Cosole UI.  Click - no problem.
- Other solutions to run the same setup... fewer commands?  How about docker the compose option... but where to run it on the internet?
- other projects?
- compare costs
