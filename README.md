
This is a WIP.

# ecs-primer 

Inputs:

- VPC or subnet to create instances
- Name of the project / application used as tag / name in all resources created
- ECS key
- ECS registry / Docker image URL to run
- Docker compose file to define the service (see http://docs.aws.amazon.com/AmazonECS/latest/developerguide/cmd-ecs-cli-compose.html 
  - but we provide a default spring bootstrap applicaiton)

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
- https://beta.docker.com/docs/aws/ - "Docker for AWS" (should also check out Docker for Azure)
- Docker Cloud
- Docker Datacenter??
- Other solutions to run the same setup... fewer commands?  How about docker the compose option... but where to run it on the internet?
- other projects?
- compare costs
