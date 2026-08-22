Recalling CloudFormation

1. Basic example
aws --profile sysops  --region us-east-1 cloudformation deploy --template-file basic.yaml --stack-name basic

2. Deploy EC2
aws --profile sysops  --region us-east-1 cloudformation deploy --template-file compute-stack.yaml --stack-name compute
