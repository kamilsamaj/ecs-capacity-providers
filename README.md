# ecs-capacity-providers
Demo of setting up ECS capacity providers


# How to

```shell
export AWS_DEFAULT_REGION='us-east-1'
export AWS_ACCOUNT_ID=$(aws sts get-caller-identity --query Account --output text)
poetry install
poetry shell
cd ./git-repos/container-demo/cdk
cdk context --clear && cdk deploy --require-approval never

```

# Source
https://ecsworkshop.com/capacity_providers/software/
