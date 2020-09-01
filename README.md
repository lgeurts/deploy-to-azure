[![AUR](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/lgeurts/deploy-to-azure/blob/master/LICENSE.md) [![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flgeurts%2Fdeploy-to-azure%2Fmaster%2Ftemplate.json)

***Created for HUISMAN EQUIPMENT B.V., Schiedam, the Netherlands***

This repository contains a fully-functioning push-to-portal button to deploy a virtual machine in Azure. 
Because I am 'mostly' Linux focused the template uses a CentOS image but this can be easily replaced.

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

I followed the instructions found [here](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button) in Microsoft Docs for adding a Deploy to Azure button. Pretty straight forward using some PowerShell or an [online tool](https://www.urlencoder.org/) to encode the URL.

## Next Steps
Add deployment of services and required information to the JSON.

                        <kbd>[WARNING]: THIS TEMPLATE IS ONLY AVAILABLE ON APPROVAL BY YOUR MANAGER!</kbd>

## Authors

This config was created by [Luc Geurts](https://lgeurts.github.io). Creds to [Jeff Brown](https://github.com/JeffBrownTech) for the idea and initial setup.

<3

***
*Tested on Windows 10 1809 and Ubuntu 18.04 LTS*
