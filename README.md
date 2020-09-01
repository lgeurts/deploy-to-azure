[![AUR](https://img.shields.io/aur/license/apt)](https://github.com/lgeurts/deply-to-azure/LICENSE.md) [![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flgeurts%2Fdeploy-to-azure%2Fmaster%2Ftemplate.json)

***Created for HUISMAN EQUIPMENT B.V., Schiedam, the Netherlands***

This repository contains a fully-functioning demo pipeline that uses a push-to-portal button to deploy a virtual machine in Azure. 
Because I'm mostly Linux focused the template uses a CentOS image but this is easily changed.

## Prerequisites

A template and GitHub account.

## What will this template do

This template will deploy:

- A virtual network and subnet.
- Public IP address.
- Network security group allowing SSH on port 22 from the Internet.
- Virtual machine running CentOS.

Required information:

- Azure subscription.
- Resource group.
- Region (auto-selected from resource group region).
- Virtual machine name.
- Administrator name.
- Password.

I followed the instructions found [here](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button) in Microsoft Docs for adding a Deploy to Azure button. It's pretty straight forward using some PowerShell or an [online tool](https://www.urlencoder.org/) to encode the URL.

## Next Steps
Add the deployment of services and required information to the JSON.

                        <kbd>[WARNING]: THIS TEMPLATE IS ONLY AVAILABLE ON APPROVAL BY YOUR MANAGER!</kbd>

## Authors

The initial setup and this file was created by [Luc Geurts](https://lgeurts.github.io).

<3

***
*Tested on Windows 10 1809 and Ubuntu 18.04 LTS*
