# aws-three-tier-network-template
Use this template to setup three tier network on aws using cloudformation

## Usage Instructions:

### Variables

| Parameter            |  Type   | Description            | Default                      | Required |
| -------------------- | ------- | ---------------------- | ---------------------------- | -------- |
| ENV                  | String  | Environment            | stage                        | Y        |
| AppName              | string  | Application Name       | theawslab                    | Y        |


### Outputs

| Output                | Description            |
| --------------------- | ---------------------- |
| VPC                   | VPC ID                 |
| CIDR                  | VPC CIDR Block         |
| DBSubnetAOutput       | DB Subnet A ID         |
| DBSubnetBOutput       | DB Subnet B ID         |
| PublicSubnetAOutput   | Public Subnet A ID     |
| PublicSubnetBOutput   | Public Subnet B ID     |
| PrivateSubnetAOutput  | Private Subnet A ID    |
| PrivateSubnetBOutput  | Private Subnet B ID    |

## Execution Steps:

1. Goto AWS CloudFormation Console.
2. Click on Create stack with new resources
3. Specify Template >> Upload a Template >> Upload file >> Next
4. Give a Stack Name
5. Pass all the parameters
6. Click Next on Configure Stack Options
7. Review and Create Stack
