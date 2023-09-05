<!-- DOCUMENTATION -->
## Documentation

Terraform documentation [is available here](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance).

Langchain agent documentation [can be found here](https://python.langchain.com/docs/modules/agents/tools.html).

YouTube inspiration [can be found here](https://www.youtube.com/watch?v=q-HNphrWsDE&list=PLRmfjgxkmfP0q6vBXZUFTzMX7RbKjDzAg&index=2&t=975s&pp=gAQBiAQB).


<!-- WHAT IS DOES -->
## What does this agent do?

This [Langchain](https://docs.langchain.com/docs/) agent is used to copy a Terraform template to deploy EC2 instances while keeping business settings consistent through deployments. 


<!-- GETTING STARTED -->
## Getting Started

1. To get started use the requirements.txt file
```
pip install -r ./requirements.txt -q
```

2. Replace the following lines in ec2_template.tf
```
key_name                    = # enter your key ""
vpc_security_group_ids      = # enter your SG Id ["sg-"]
subnet_id                   = # enter your subnet "subnet-"
```
