[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flgeurts%2Fdeploy-to-azure%2Fmaster%2Ftemplate.json)

# Linux Lab Azure Deployment

This is a template used to deploy a quick lab for learning Linux.

This template deploys:

- Virtual network and subnet
- Public IP address
- Network security group allowing SSH on port 22 from the Internet
- Virtual machine running CentOS

Required information:

- Azure subscription
- Resource group
- Region (auto-selected from resource group region)
- Virtual machine name
- Administrator name
- Password
